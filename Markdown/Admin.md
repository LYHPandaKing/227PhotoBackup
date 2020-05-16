<!DOCTYPE html>
<html lang="{{ site.lang | default: "en-US" }}">
  <head>
    <script>
function decrypt(str, pwd) {
if(str == null || str.length < 8) {
alert('A salt value could not be extracted from the encrypted message because its length is too short. The message cannot be decrypted.');
return;
}
if(pwd == null || pwd.length <= 0) {
alert('Please enter a password with which to decrypt the message.');
return;
}
var prand ='';
for(var i=0; i<pwd.length; i++) {
prand += pwd.charCodeAt(i).toString();
}
var sPos = Math.floor(prand.length / 5);
var mult = parseInt(prand.charAt(sPos) + prand.charAt(sPos*2) + prand.charAt(sPos*3) + prand.charAt(sPos*4) + prand.charAt(sPos*5));
var incr = Math.round(pwd.length / 2);
var modu = Math.pow(2, 31) - 1;
var salt = parseInt(str.substring(str.length - 8, str.length), 16);
str = str.substring(0, str.length - 8);
prand += salt;
while(prand.length > 10) {
prand = (parseInt(prand.substring(0, 10)) + parseInt(prand.substring(10, prand.length))).toString();
}
prand = (mult * prand + incr) % modu;
var enc_chr = '';
var enc_str = '';
for(var i=0; i<str.length; i+=2) {
enc_chr = parseInt(parseInt(str.substring(i, i+2), 16) ^ Math.floor((prand / modu) * 255));
enc_str += String.fromCharCode(enc_chr);
prand = (mult * prand + incr) % modu;
}
return enc_str;
}

function protection() {
encURL = '310165f709933d498150e401f119cae9c7d738c18616b8971e8256227f9205c9b6bb';
password=prompt('請輸入密碼：','');
if (password != '' && password != null) {
decURL=decrypt(encURL, password);
location.href= decURL;
}
}
</script>

</head>
  <body>
  <button onclick="protection()">進入保護頁。</button>
  
  ### Test , this is pw proected page.
  content
  ![227](../Img/227Blur.PNG)
  ok now
  see if can see the above content or not 
 </body>
</html>
