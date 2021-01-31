### Tokyo MX 直播源 Live Stream
##### [Back](../readme.md)

#### Tokyo MX
- <a target="_blank" rel="noopener noreferrer" href="http://dsgstng.herokuapp.com/tv">Dテレ</a><br>
<img src="../Img/dsgstng.JPG" alt="dsgstng" width="50%">

- <a target="_blank" rel="noopener noreferrer" href="https://aqstream.com/jp/tmx/Tokyo-MX">Aqstream</a><br>
<img src="../Img/aqstream.png" alt="aqstream" width="50%">

- <a target="_blank" rel="noopener noreferrer" href="http://mov3.co/tokyomx/">mov3 日本電視台</a><br>
<img src="../Img/mov3.jpeg" alt="mov3.co" width="50%">

- <a target="_blank" rel="noopener noreferrer" href="https://github.com/imDazui/Tvlist-awesome-m3u-m3u8#%E7%A8%B3%E5%AE%9A%E5%9C%B0%E5%9D%80">IPTV </a><a target="_blank" rel="noopener noreferrer" href="https://yamcode.com/FuwF14dxih">m3u8</a><br>
<blockquote>
エムキャス MX CASTING (1280x720): http://movie.mcas.jp/mcas/mx1_2/chunklist.m3u8<br>
us195 (960x540) : https://cdn.us195.jpnettv.live/jptv/kanto_tokyo_mx1_540/playlist.m3u8<br>
jpth10 (960x540) : https://cdn.jpth10.jpnettv.live/jptv/kanto_tokyo_mx1_540/playlist.m3u8<br>
</blockquote><br>

<script src="https://cdn.jsdelivr.net/npm/hls.js@latest"></script>
    <video id="video" controls></video>
    <script>
    if(Hls.isSupported())
    {
        var video = document.getElementById('video');
        var hls = new Hls();
        hls.loadSource('playlist.m3u8');
        hls.attachMedia(video);
        hls.on(Hls.Events.MANIFEST_PARSED,function()
        {
            video.play();
        });
    }
    else if (video.canPlayType('application/vnd.apple.mpegurl'))
    {
        video.src = 'https://cdn.us195.jpnettv.live/jptv/kanto_tokyo_mx1_540/playlist.m3u8';
        video.addEventListener('canplay',function()
        {
            video.play();
        });
    }
    </script>

<!--
<hr>
##### 付費 Paid<br>
- <a target="_blank" rel="noopener noreferrer" href="http://www.isakuraiptv.com/">iSakura</a><br>
- <a target="_blank" rel="noopener noreferrer" href="https://sky-stream.info/">Sky Stream</a><br>
- <a target="_blank" rel="noopener noreferrer" href="https://joytv.com.tw/">Joytv TW</a><br>
-->
