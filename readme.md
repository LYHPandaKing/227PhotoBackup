
<div class="slideshow-container">

<div class="mySlides fade">
  <div class="numbertext">1 / 13</div>
  <img src="Img/Slideshow/SS_DebutSG.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">2 / 13</div>
  <img src="Img/Slideshow/SS_11Characters.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">3 / 13</div>
  <img src="Img/Slideshow/SS_Halloween.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">4 / 13</div>
  <img src="Img/Slideshow/SS_2ndSG.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">5 / 13</div>
  <img src="Img/Slideshow/SS_3rdSG.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">6 / 13</div>
  <img src="Img/Slideshow/SS_4thSG.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">7 / 13</div>
  <img src="Img/Slideshow/SS_5thSG.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">8 / 13</div>
  <img src="Img/Slideshow/SS_6thSG.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">9 / 13</div>
  <img src="Img/Slideshow/SS_11色の風.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">10 / 13</div>
  <img src="Img/Slideshow/SS_7thSG.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">11 / 13</div>
  <img src="Img/Slideshow/SS_1stAL.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">12 / 13</div>
  <img src="Img/Slideshow/SS_8thSG.jpg" style="width:100%">
</div>

<div class="mySlides fade">
  <div class="numbertext">13 / 13</div>
  <img src="Img/Slideshow/SS_9thSG.jpg" style="width:100%">
</div>

<a class="prev" onclick="plusSlides(-1)">❮</a>
<a class="next" onclick="plusSlides(1)">❯</a>

</div>
<br>

<div style="text-align:center">
  <span class="dot" onclick="currentSlide(1)"></span> 
  <span class="dot" onclick="currentSlide(2)"></span> 
  <span class="dot" onclick="currentSlide(3)"></span> 
  <span class="dot" onclick="currentSlide(4)"></span> 
  <span class="dot" onclick="currentSlide(5)"></span> 
  <span class="dot" onclick="currentSlide(6)"></span> 
  <span class="dot" onclick="currentSlide(7)"></span> 
  <span class="dot" onclick="currentSlide(8)"></span> 
  <span class="dot" onclick="currentSlide(9)"></span> 
  <span class="dot" onclick="currentSlide(10)"></span> 
  <span class="dot" onclick="currentSlide(11)"></span> 
  <span class="dot" onclick="currentSlide(12)"></span> 
  <span class="dot" onclick="currentSlide(13)"></span> 
</div>

<script>
let slideIndex = 13;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  let i;
  let slides = document.getElementsByClassName("mySlides");
  let dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>



**最後更新日期 Last Update: 23May,2022 14:10 (HKT)**

### 相簿 Album
- [出道前 Pre-Debut](Docs/Album/PreDebut.md)
- [出道單曲 Debut Single](Docs/Album/1st%20Single.html)
- [第二單曲 2nd Single](Docs/Album/2nd%20Single.html)
- [角色設計 Character Design](Docs/Album/CharacterDesgin.md)
- [22/7 音楽の時間 Ongaku no Jikan](Docs/Album/Nanaon/Nanaon.md)
<br><br>
- [天城サリー Amaki Sally](Docs/Album/AmakiSally/AmakiSally.md)
- [花川芽衣 Hanakawa Mei](Docs/Album/HanakawaMei/HanakawaMei.md) > 浅倉唯 Asakura Yui
- [帆風千春 Hokaze Chiharu](Docs/Album/HokazeChiharu/HokazeChiharu.md) > 千春 Chiharu
- [河瀬詩 Kawase Uta](Docs/Album/KawaseUta/KawaseUta.md)
- [倉岡水巴 Kuraoka Mizuha](Docs/Album/KuraokaMizuha/KuraokaMizuha.md) > 倉丸莉子 Kuramaru Riko
- [宮瀬玲奈 Miyase Reina](Docs/Album/MiyaseReina/MiyaseReina.md)
- [西條和 Saijo Nagomi](Docs/Album/SaijoNagomi/SaijoNagomi.md)
- [白沢かなえ Shirosawa Kanae](Docs/Album/ShirosawaKanae/ShirosawaKanae.md)
- [涼花萌 Suzuhana Moe](Docs/Album/SuzuhanaMoe/SuzuhanaMoe.md)
- [高辻麗 Takatsuji Urara](Docs/Album/TakatsujiUrara/TakatsujiUrara.md) > 日永麗 Hinaga Urara
- [武田愛奈 Takeda Aina](Docs/Album/TakedaAina/TakedaAina.md)
- [海乃るり Umino Ruri](Docs/Album/UminoRuri/UminoRuri.md) > 吉宮瑠織

### 備份 Backup
- [Instagram](Docs/Backup/Instagram/IG_List.md)
- [Showroom](Docs/Backup/Showroom/Showroom_List.md)
- [YouTube](Docs/Backup/YouTube_List.md)
- [22/7 Official Blog](Docs/Backup/Blog/Blog_List.md)
- [22/7 Live](Docs/Backup/227Live/Live_List.md)
- [22/7 動畫 Anime](Docs/Backup/Anime/Anime_List.md)
- [22/7 電台節目 Radio](Docs/Backup/227Radio/Radio_List.md)
- [22/7 計算中 Keisanchu](Docs/Backup/227Keisanchu/227Keisanchu_List.md)
- [22/7 検算中 Kenzanchu](Docs/Backup/227Kenzanchu/227Kenzanchu_List.md)
- [22/7 成員冠名節目 Members Own Program](Docs/Backup/MembersOwnProgram/MembersOwnProgram_List.md)
- [22/7 相關影片 Related Videos](Docs/Backup/227Related/227Related.md)
- [二人三脚プロジェクト 2nin3kyaku Project](Docs/Backup/Nanaon/2nin3kyaku_List.md)
<br><br>
- [萬聖節限定頭像及壁紙 Halloween Special Icon & Wallpaper 2019](Docs/Backup/2019HalloweenSpecial.md)
- [22/7 計算中 放送紀念頭像及壁紙<br>Commemoration Icons & Wallpapers for 22/7 Keisanchuu](Docs/Backup/KeisanchuuBroadcast.md)
- [22/7 anime 20,000 followers 紀念頭像 Icon](Docs/Backup/TW20000fol.md)
- [22/7 anime 30,000 followers 紀念頭像 Icon](Docs/Backup/TW30000fol.md)
- [22/7 計算中 Blu-ray 發售紀念頭像<br>Commemoration Icons for release of 22/7 Keisanchuu Blu-ray](Docs/Backup/KeisanchuuBluray.md)

### 其他資訊 Other Information
- [音樂 Music](Docs/Music/Music_List.md)
- [雜誌 Magazines](Docs/Magazines/Magazines_List.md)
- [直播源 Live Stream](Docs/Streaming.md)
- [版主作品 Host's Creation](Docs/HostsCreation/HostsCreation.md)
- [22/7 日曆 Calender](Docs/Calendar.md)
- [22/7 官方商店 Official Online Store](Docs/OfficialStore.md)
<br><br>
- [Aniplex Online Fest](Docs/Backup/Aniplex_Online_Fest/AOF_List.md)

### [鳴謝 Credit](Docs/Credit.md)