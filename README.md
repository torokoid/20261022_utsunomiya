# 20261022_utsunomiya
<html lang="ja" data-loaded="false" data-scrolled="false" data-spmenu="closed">
<head>

<meta charset="UTF-8">
<meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
<meta http-equiv="X-UA-Compatible" content="IE=EmulateIE10" />
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<!--ここから上はお決まりの定型文です-->


<!--ここからが表現の書式などを決めるcssという部分-->

<style type="text/css">
p {
color: #fffafa;
font-size: 1.5em;
}


.red {color:#ff0000;}
.grey {color:#ffffff; background:#999999;}
.snow {color:#fffafa;}
.yellow {color:#ff0000; background:#ffff00;}
.blue {color:#0000ff;}
.white {color:#ffffff;}
.waku {border:2px dotted #99cc66;
line-height: 200%;
padding: 10px;}


main {
background-color: rgba(255, 255, 255, 0.5);
}

section {
background-color: rgba(0, 225, 0, 0.3);
}


/* 点滅 */
.blinking{
-webkit-animation:blink 1.5s ease-in-out infinite alternate;
-moz-animation:blink 1.5s ease-in-out infinite alternate;
animation:blink 1.5s ease-in-out infinite alternate;
}
@-webkit-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@-moz-keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}
@keyframes blink{
0% {opacity:0;}
100% {opacity:1;}
}

#wrap {background:none} /*PC用の背景はオフ*/

/*背景を表示させる部分*/
body::before {
content:"";
display:block;
position:fixed;
top:0;
left:0;
z-index:-1;
width:100%;
height:100vh;
background:url(https://torokoid.github.io/20261022_utsunomiya/20261022_00024.jpeg) center/cover no-repeat;
-webkit-background-size:cover;/*Android4*/
}

a.p:hover {
position: relative;
text-decoration: none;
}
a.p span {
display: none;
position: relative;
top: -0.5em;
left: 2em;
}
a.p:hover span {
border: none;
display: block;
width: 800px;
}


@media screen and (min-width: 540px),
screen and (orientation: landscape) {
p.note { display: none; }
}


.media-container {
  width: 100%;
  max-width: 900px;
  margin: 0 auto;
}

.responsive-media {
  width: 100%;
  display: block;
}

.youtube-wrapper {
  position: relative;
  width: 100%;
  padding-bottom: 56.25%; /* 16:9比率 */
  height: 0;
}

.youtube-wrapper iframe {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  border: none;
}





/* オープニング画面のスタイリング（写真を表示するように変更） */
#splash {
  position: fixed;
  top: 0;
  left: 0;
  width: 100%;
  height: 100vh;
  background-color: #000000; /* 読み込み前の万一の背景（黒） */
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  z-index: 9999; /* 最前面に表示 */
  opacity: 1;
  visibility: visible;
  transition: opacity 0.8s ease, visibility 0.8s ease; /* 0.8秒かけてふわっと消える */
  padding: 20px;
  box-sizing: border-box;
}

.splash-content {
  max-width: 800px;
  width: 100%;
  text-align: center;
}

.splash-content img {
  width: 100%;
  height: auto;
  max-height: 75vh;
  object-fit: contain;
  box-shadow: 0 10px 30px rgba(0,0,0,0.5);
  border-radius: 4px;
}

.splash-text {
  color: #fff;
  margin-top: 15px;
  font-size: 1.2em;
}

/* 読み込み完了後に付与するクラス（非表示状態） */
#splash.loaded {
  opacity: 0;
  visibility: hidden;
}

/* メインコンテンツ */
#container {
  opacity: 1;
}




/* --- スクロールでズームインしながら浮き出るアニメーション --- */
.scroll-fade {
  opacity: 0;
  transform: translateY(40px) scale(0.85); /* 最初は少し下にいて、サイズも少し縮小（0.85倍）しておく */
  transition: opacity 1.2s cubic-bezier(0.16, 1, 0.3, 1), transform 1.2s cubic-bezier(0.16, 1, 0.3, 1);
  will-change: opacity, transform;
}

/* 画面内に入ったときに、元のサイズ・透明度になりながらズームイン・アップする */
.scroll-fade.is-show {
  opacity: 1;
  transform: translateY(0) scale(1); /* 通常のサイズ・位置に戻る（ズームイン） */
}



</style>

<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/css/lightbox.css" rel="stylesheet">

</head>

<body>

<!-- オープニング（スプラッシュ画面に写真とタイトルを配置） -->
<div id="splash">
  <div class="splash-content">
    <img src="20261022_00021.jpeg" alt="オープニング画像">
    <div class="splash-text">最初の一枚は一輪の薔薇</div>
  </div>
</div>

<!-- メインコンテンツ -->
<div id="container">
  <h1>メインのホームページ画像</h1>
  <p><a href="20261022_00021.jpeg" target="_blank"><img src="20261022_00021.jpeg" alt="サンプル画像" class="responsive-media"></a></p>
</div>



<!--
    <p><a href="https://peyng.github.io/restart/">前回までの記録</a>><a><span class="grey">今回2026,05,28</span></a></p>
-->


<p class="note">
モバイル端末をお使いの場合は、画面を横向きにすると
背景画像の横方向がご覧頂けます。
</p>


<!--ここ上は、ほぼそのまま使います！-->


<!--QRコードの挿入例-->
<p align="left"> <img src="QR_2026Oct22.png" alt="アクセス用QRコード" width="100">QR for Access</p>
<p align="right"><marquee direction="left" scrollamount="20" width="30%">(^_^)/~alis</marquee></p>

<!--流れ文字の挿入例-->
<h1><span class="yellow"><marquee behavior="left">!!! 2026/10/22、ご近所のお花達から、夕空のお月様と飛行機雲まで !!!</marquee></span></h1>




<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

<!--ここから下が、本体部分-->


<div class="media-container">

<h2><span class="yellow">2026Oct21、ご近所のお花達は手入れが行き届いて綺麗に満開</span></h2>
<a href="20261022_00001.jpeg" target="_blank"><img src="20261022_00001.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00002.jpeg" target="_blank"><img src="20261022_00002.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00003.jpeg" target="_blank"><img src="20261022_00003.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00004.jpeg" target="_blank"><img src="20261022_00004.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00005.jpeg" target="_blank"><img src="20261022_00005.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00006.jpeg" target="_blank"><img src="20261022_00006.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00007.jpeg" target="_blank"><img src="20261022_00007.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00008.jpeg" target="_blank"><img src="20261022_00008.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00009.jpeg" target="_blank"><img src="20261022_00009.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00010.jpeg" target="_blank"><img src="20261022_00010.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00011.jpeg" target="_blank"><img src="20261022_00011.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00012.jpeg" target="_blank"><img src="20261022_00012.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00013.jpeg" target="_blank"><img src="20261022_00013.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00014.jpeg" target="_blank"><img src="20261022_00014.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00015.jpeg" target="_blank"><img src="20261022_00015.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00016.jpeg" target="_blank"><img src="20261022_00016.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00017.jpeg" target="_blank"><img src="20261022_00017.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00018.jpeg" target="_blank"><img src="20261022_00018.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00019.jpeg" target="_blank"><img src="20261022_00019.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00020.jpeg" target="_blank"><img src="20261022_00020.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">オープニング画像になった一輪の薔薇</span></h2>
<a href="20261022_00021.jpeg" target="_blank"><img src="20261022_00021.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00022.jpeg" target="_blank"><img src="20261022_00022.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00023.jpeg" target="_blank"><img src="20261022_00023.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">本日の背景はこちらのシクラメン</span></h2>
<a href="20261022_00024.jpeg" target="_blank"><img src="20261022_00024.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00025.jpeg" target="_blank"><img src="20261022_00025.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00026.jpeg" target="_blank"><img src="20261022_00026.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00027.jpeg" target="_blank"><img src="20261022_00027.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00028.jpeg" target="_blank"><img src="20261022_00028.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00029.jpeg" target="_blank"><img src="20261022_00029.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">お昼はスーパーのお弁当でした</span></h2>
<a href="20261022_00030.jpeg" target="_blank"><img src="20261022_00030.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">デザートはフライドポテト</span></h2>
<a href="20261022_00031.jpeg" target="_blank"><img src="20261022_00031.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">庭に来た野鳥と目があって、網戸越しにパチリ！</span></h2>
<a href="20261022_00032.jpeg" target="_blank"><img src="20261022_00032.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">夕方の空にお月様が浮かびました</span></h2>
<a href="20261022_00033.jpeg" target="_blank"><img src="20261022_00033.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">月齢は、9.9日、うさぎさんも見えています</span></h2>
<a href="20261022_00034.jpeg" target="_blank"><img src="20261022_00034.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00035.jpeg" target="_blank"><img src="20261022_00035.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">薔薇の蕾も控えています</span></h2>
<a href="20261022_00036.jpeg" target="_blank"><img src="20261022_00036.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">サルビアもまだまだ元気</span></h2>
<a href="20261022_00037.jpeg" target="_blank"><img src="20261022_00037.jpeg" alt="サンプル画像" class="responsive-media"></a>
<a href="20261022_00038.jpeg" target="_blank"><img src="20261022_00038.jpeg" alt="サンプル画像" class="responsive-media"></a>

<h2><span class="yellow">青空に飛行機雲が綺麗でした</span></h2>
<a href="20261022_00039.jpeg" target="_blank"><img src="20261022_00039.jpeg" alt="サンプル画像" class="responsive-media"></a>


<h2><span class="yellow">宇都宮市北部、ヨークベニマル御幸ヶ原店までの走行経路はこのルート</span></h2>
<a href="20261022_00001.png" target="_blank"><img src="20261022_00001.png" alt="サンプル画像" class="responsive-media"></a>


<h2><span class="yellow">ヨークベニマル御幸ヶ原店までの行き帰り運転動画</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/-Wua99x_vac?si=UUJzB1QLhTCnXvD_&autoplay=1&mute=1&loop=1&playlist=-Wua99x_vac" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>


<h2><span class="yellow">以上、今回は、ご近所のお花達がメインでした</span></h2>


<br><br>
<h2><span class="yellow">月齢の説明リンク貼ります</span></h2>
<h2><a href="https://starwalk.space/ja/moon-calendar" target="_blank"><span class="snow">月齢カレンダー・リンク</span></a></h2>

<br><br>
<br><br>

<h2><span class="yellow">今日のBGMは、Koji Tamaki, Miyuki Nakajima, Shogo Hamada & Kazumasa Oda | 心に響く日本の名曲 Timeless Japanese Hits</span></h2>
<div class="youtube-wrapper">
<iframe width="560" height="315" src="https://www.youtube.com/embed/IO9O0n0Wi3Q?si=g6LZbyt-2EO5yUBp&autoplay=1&mute=0&loop=1&playlist=IO9O0n0Wi3Q" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>

<br><br><br>
<h2><span class="yellow">2026Oct22、ご近所のお花達から、夕空のお月様と飛行機雲まででした<br>Thank you for reading this far.</span></h2>

<br><br><br>

<!-- hitwebcounter Code START -->
<a href="https://www.hitwebcounter.com" target="_blank">
<p>you are <img src="https://hitwebcounter.com/counter/counter.php?page=21345151&style=0018&nbdigits=5&type=page&initCount=0" title="Counter Widget" Alt="Visit counter For Websites"   border="0" />visitor<br>The numbers are cumulative for the Bangkok ＆ Utsunomiya series websites launched since 2025 August 1st.</p></a>  



<style>
.responsive-media {
    opacity: 1 !important;
    filter: brightness(100%) !important;
}
</style>


<br><br><br><br><br><br><br><br><br>





<br><br>

<br><br><br><br><br><br>

<!--本体はここまで-->
    </div>

<!--画面に空白地帯を作って、背景が見えるようにしています-->
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>



<!-- フッタ -->
<footer>
<p>Copyright 2026/10/22 alis</p>
</footer>

<!--HPにさまざまなJavaScriptを呼び込むための書式-->
<script src="https://code.jquery.com/jquery-1.12.4.min.js" type="text/javascript"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.7.1/js/lightbox.min.js" type="text/javascript"></script>

<script type='text/javascript' src='https://torokoid.github.io/shiba/jquery.js?ver=1.12.4'></script>
<script src="https://torokoid.github.io/shiba/jquery.goup.min.js"></script>
<script src="https://torokoid.github.io/shiba/my.js"></script>


<script>
window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 800);
});
</script>


<script>
// オープニング画面を消す既存のコード
window.addEventListener('load', function() {
  const splash = document.querySelector('#splash');
  setTimeout(function() {
    splash.classList.add('loaded');
  }, 800);
});

// --- スクロール連動のフェードイン処理 ---
document.addEventListener("DOMContentLoaded", function() {
  // 動きをつけたい要素（ここでは画像と見出し h2）を指定
  const targets = document.querySelectorAll('.responsive-media, h2');

  const observer = new IntersectionObserver((entries, observer) => {
    entries.forEach(entry => {
      // 画面に少し入ってきたら
      if (entry.isIntersecting) {
        entry.target.classList.add('is-show');
        // 何度もアニメーションさせたい場合は unobserve を外してください
        // observer.unobserve(entry.target); 
      }
    });
  }, {
    threshold: 0.25 // 要素が25%見えたタイミングで発火
  });

  targets.forEach(target => {
    target.classList.add('scroll-fade'); // 初期状態のクラスを付与
    observer.observe(target); // 監視を開始
  });
});
</script>

    </body>
    
</html>
