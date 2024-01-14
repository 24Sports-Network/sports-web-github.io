<html>
  <head></head>
  <body class="vsc-initialized">
    <title>24 SPORTS NETWORK</title>
    <meta content="width=device-width,user-scalable=no,initial-scale=1,maximum-scale=1,minimum-scale=1" name="viewport">
    <meta content="IE=edge" http-equiv="X-UA-Compatible">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Lobster">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.1/jquery.min.js"></script>
    <style>
      .loading {
        margin-top: 0;
        font-weight: 700;
        vertical-align: middle;
        line-height: 150px;
        font-size: 25px;
        text-transform: uppercase;
        background: linear-gradient(to right, red 30%, rgb(10, 60, 215) 75%);
        -webkit-background-clip: text;
        -webkit-text-fill-color: transparent;
      }

      h1 {
        background-color: #000;
        margin: 0;
        text-align: center;
        padding: 5px
      }

      a {
        color: #fff;
        text-decoration: none
      }

      tr th {
        font-tvv-name: bold;
        background-color: green;
        padding: 1px
      }

      * {
        box-sizing: border-box
      }

      @keyframes fadein {
        0% {
          opacity: 0
        }

        66% {
          opacity: 0
        }

        100% {
          opacity: 1
        }
      }

      @-webkit-keyframes fadein {
        0% {
          opacity: 0
        }

        66% {
          opacity: 0
        }

        100% {
          opacity: 1
        }
      }

      .tvv-item {
        position: relative;
        display: inline-block;
        width: 120px;
        height: 150px;
        margin: 3px;
        padding: 10px;
        border: 1px solid green z-index: 1;
        background: White;
        box-shadow: 1px 2px 2px red;
        overflow: hidden;
        border-radius: 4px;
        filter: contrast(100%)
      }

      .tvv-item>* {
        margin: 0;
        padding: 0
      }

      .tvv-item .tvv-thumb {
        width: 100%;
        bottom: 10px;
        top: 0px;
        position: absolute;
        right: 0;
        float: center;
      }

      .tvv-item .tvv-thumb img {
        width: 100%;
        pointer-events: none
      }

      .tvv-item .tvv-name {
        position: absolute;
        left: 0;
        bottom: 0;
        font-size: 12px;
        display: block;
        text-align: center;
        width: 100%;
        color: black;
        padding: 5px;
        font-weight: 800;
        text-overflow: ellipsis;
        black-space: nowrap;
        overflow: hidden;
        background: linear-gradient(to bottom left, #ccffff 7%, #ffffff 100%);
        box-shadow: inset 2px 2px 2px 0px rgba(255, 255, 255, .5);
        7px 7px 20px 0px rgba(0, 0, 0, .1),
        4px 4px 5px 0px rgba(0, 0, 0, .1);
        transition: all 0.3s ease;
      }

      .tvv-item img {
        width: 100%;
        pointer-events: none
      }

      .tvv-item:after {
        position: absolute;
        content: "";
        width: 100%;
        height: 0;
        top: 0;
        left: 0;
        z-index: -1;
        border-radius: 5px;
        border: 0px solid green;
        background-color: black;
        background-image: linear-gradient(to bottom left, #ccffff 7%, #ffffcc 100%);
        box-shadow: inset 2px 2px 2px 0px rgba(255, 255, 255, .5);
        7px 7px 20px 0px rgba(0, 0, 0, .1),
        4px 4px 5px 0px rgba(0, 0, 0, .1);
        transition: all 0.3s ease;
      }

      .tvv-item:hover {
        color: #000;
      }

      .tvv-item:hover:after {
        top: auto;
        bottom: 0;
        height: 100%;
      }

      .tvv-item:active {
        top: 5px;
      }

      .tvv-name:hover {}

      .fin {
        width: 100%;
        margin-top: 1px;
        margin-bottom: 2px;
        float: center;
        height: 30px;
        font-size: small;
        background-color: rgb(40, 40, 40);
        color: black;
        border-radius: 10px;
        border: 3px solid greenoutline: none;
        text-align: center;
        font-family: "Poppins", sans-serif;
      }

      .fin,
      .dftr {
        width: 100%;
        margin-top: 1px;
        margin-bottom: 2px;
        float: center;
        height: 30px;
        font-style: bold;
        background-color: rgb(40, 40, 40);
        color: purple;
        background: linear-gradient(135deg, snow 0%, seashell 64%);
        border-radius: 0px;
        border: 2px solid red;
        outline: none;
        text-align: center;
        font-family: "Poppins", sans-serif;
      }

      .fin:hover,
      .dftr:hover {
        border: 3px solid rgb(255, 60, 140);
        color: red;
        background: linear-gradient(135deg, azure 0%, floralwhite 64%);
      }

      .tvv-item {
        width: calc(100%/20 - 10px)
      }
      }

      @media only screen and (max-width:2600px) {
        .tvv-item {
          width: calc(100%/19 - 10px)
        }
      }

      @media only screen and (max-width:2470px) {
        .tvv-item {
          width: calc(100%/18 - 10px)
        }
      }

      @media only screen and (max-width:2340px) {
        .tvv-item {
          width: calc(100%/17 - 10px)
        }
      }

      @media only screen and (max-width:2210px) {
        .tvv-item {
          width: calc(100%/16 - 10px)
        }
      }

      @media only screen and (max-width:2080px) {
        .tvv-item {
          width: calc(100%/15 - 10px)
        }
      }

      @media only screen and (max-width:1950px) {
        .tvv-item {
          width: calc(100%/14 - 10px)
        }
      }

      @media only screen and (max-width:1820px) {
        .tvv-item {
          width: calc(100%/13 - 10px)
        }
      }

      @media only screen and (max-width:1690px) {
        .tvv-item {
          width: calc(100%/12 - 10px)
        }
      }

      @media only screen and (max-width:1560px) {
        .tvv-item {
          width: calc(100%/11 - 10px)
        }
      }

      @media only screen and (max-width:1430px) {
        .tvv-item {
          width: calc(100%/10 - 10px)
        }
      }

      @media only screen and (max-width:1300px) {
        .tvv-item {
          width: calc(100%/9 - 10px)
        }
      }

      @media only screen and (max-width:1170px) {
        .tvv-item {
          width: calc(100%/8 - 10px)
        }
      }

      @media only screen and (max-width:1040px) {
        .tvv-item {
          width: calc(100%/7 - 10px)
        }
      }

      @media only screen and (max-width:910px) {
        .tvv-item {
          width: calc(100%/6 - 10px)
        }
      }

      @media only screen and (max-width:780px) {
        .tvv-item {
          width: calc(100%/5 - 10px)
        }
      }

      @media only screen and (max-width:650px) {
        .tvv-item {
          width: calc(100%/4 - 10px)
        }
      }

      @media only screen and (max-width:520px) {
        .tvv-item {
          width: calc(100%/3 - 10px)
        }
      }

      @media only screen and (max-width:390px) {
        .tvv-item {
          width: calc(100%/2 - 10px)
        }
      }

      .custom-btn {
        width: 130px;
        height: 40px;
        color: #fff;
        border-radius: 5px;
        padding: 10px 25px;
        font-family: 'Lato', sans-serif;
        font-weight: 500;
        background: transparent;
        cursor: pointer;
        transition: all 0.3s ease;
        position: relative;
        display: inline-block;
        box-shadow: inset 2px 2px 2px 0px rgba(255, 255, 255, .5), 7px 7px 20px 0px rgba(0, 0, 0, .1), 4px 4px 5px 0px rgba(0, 0, 0, .1);
        outline: none;
      }

      .btn-11 {
        border: white;
        background: green;
        background: linear-gradient(80deg, yellow 0%, teal 100%);
        color: #fff;
        overflow: hidden;
      }

      .btn-11:hover {
        text-decoration: none;
        color: #fff;
        background-image: linear-gradient(135deg, red 0%, purple 64%);
      }

      .btn-11:before {
        position: absolute;
        content: '';
        display: inline-block;
        top: -180px;
        left: 0;
        width: 30px;
        height: 100%;
        background-color: #fff;
        animation: shiny-btn1 3s ease-in-out infinite;
      }

      .btn-11:hover {
        opacity: .7;
        color: white;
      }

      .btn-11:active {
        box-shadow: 4px 4px 6px 0 rgba(255, 255, 255, .3), -4px -4px 6px 0 rgba(116, 125, 136, .2), inset -4px -4px 6px 0 rgba(255, 255, 255, .2), inset 4px 4px 6px 0 rgba(0, 0, 0, .2);
      }

      @-webkit-keyframes shiny-btn1 {
        0% {
          -webkit-transform: scale(0) rotate(45deg);
          opacity: 0;
        }

        80% {
          -webkit-transform: scale(0) rotate(45deg);
          opacity: 0.5;
        }

        81% {
          -webkit-transform: scale(4) rotate(45deg);
          opacity: 1;
        }

        100% {
          -webkit-transform: scale(50) rotate(45deg);
          opacity: 0;
        }
      }

      @import url("https://fonts.googleapis.com/css?family=Roboto");

      @-webkit-keyframes come-in {
        0% {
          -webkit-transform: translatey(100px);
          transform: translatey(100px);
          opacity: 0;
        }

        30% {
          -webkit-transform: translateX(-50px) scale(0.4);
          transform: translateX(-50px) scale(0.4);
        }

        70% {
          -webkit-transform: translateX(0px) scale(1.2);
          transform: translateX(0px) scale(1.2);
        }

        100% {
          -webkit-transform: translatey(0px) scale(1);
          transform: translatey(0px) scale(1);
          opacity: 1;
        }
      }

      @keyframes come-in {
        0% {
          -webkit-transform: translatey(100px);
          transform: translatey(100px);
          opacity: 0;
        }

        30% {
          -webkit-transform: translateX(-50px) scale(0.4);
          transform: translateX(-50px) scale(0.4);
        }

        70% {
          -webkit-transform: translateX(0px) scale(1.2);
          transform: translateX(0px) scale(1.2);
        }

        100% {
          -webkit-transform: translatey(0px) scale(1);
          transform: translatey(0px) scale(1);
          opacity: 1;
        }
      }

      * {
        margin: 0;
        padding: 0;
      }

      html,
      body {
        background: #eaedf2;
        font-family: 'Roboto', sans-serif;
      }

      .stwBlurRainbow,
      .stwRainbow {
        position: fixed;
        width: 100%;
        bottom: 0;
        left: 0;
        right: 0;
        height: 3px;
        z-index: 23;
        background: linear-gradient(-45deg, #4086f4, #31a952, #fbbe01, #eb4132, #4086f4, #31a952, #fbbe01, #eb4132);
        background-size: 200%;
        -webkit-animation: animeBar 5s linear infinite;
        animation: animeBar 5s linear infinite
      }

      .stwBlurRainbow {
        height: 10px;
        z-index: 22;
        filter: blur(10px);
        opacity: .7
      }

      @-webkit-keyframes animeBar {
        0% {
          background-position: 0 50%
        }

        50% {
          background-position: 100% 50%
        }

        100% {
          background-position: 0 50%
        }
      }

      @keyframes animeBar {
        0% {
          background-position: 0 50%
        }

        50% {
          background-position: 100% 50%
        }

        100% {
          background-position: 0 50%
        }
      }
    </style>
    <center><a href="https://t.me/+sFANm-FHD_k1ZTY9"> <button class="btn-11 custom-btn" style="width:100%;font-weight:100;height:70px;font-size:35px;position:top:0px;z-index:3; font-family: Jazz LET, fantasy">24 SPORTS NETWORK</button></a>
<div class="no-items section" id="search_top" name="Search (Top)" style="z-index:3;position:top:44px;border-radius:10px"></div>
<input class="fin" placeholder="Search here.." style="z-index:3;position:top:44px;border-radius:10px;height: 40px;font-size: 24px;">


<a href="https://dora-bash-live.blogspot.com/p/cartoon-network.html">
<div class="tvv-item">  <img class="loading" alt="Cartoon Network" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-11161-j99h67u8-v1/imageContent-11161-j99h67u8-m1.png" class="lazyload">
<div class="tvv-name">Cartoon Network
<div hidden>Kids
</div hidden></div></a></div>

<a href="https://dora-bash-live.blogspot.com/p/cartoon-network-hd.html">
<div class="tvv-item">  <img class="loading" alt="Cartoon Network HD+" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-34164-jok06xoo-v1/imageContent-34164-jok06xoo-m1.png" class="lazyload">
<div class="tvv-name">Cartoon Network HD+
<div hidden>Kids
</div hidden></div></a></div>


<a href="https://dora-bash-live.blogspot.com/p/cn-hd-tamil.html">
<div class="tvv-item">  <img class="loading" alt="Cartoon Network HD+" src="https://i.postimg.cc/J0zwxzzX/CN-HD-Tamil.png" class="lazyload">
<div class="tvv-name">Cartoon Network HD+ Tamil
<div hidden>Kids
</div hidden></div></a></div>          


<a href="https://dora-bash-live.blogspot.com/p/cn-hd-telegu.html">
<div class="tvv-item">  <img class="loading" alt="Cartoon Network HD+" src="https://i.postimg.cc/1RCbPPzW/CN-HD-Telugu.png" class="lazyload">
<div class="tvv-name">Cartoon Network HD+ Telegu
<div hidden>Kids
</div hidden></div></a></div>


<a href="https://dora-bash-live.blogspot.com/p/discovery-kids.html">
<div class="tvv-item">  <img class="loading" alt="Discovery Kids" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-24724-jgvwokqw-v1/imageContent-24724-jgvwokqw-m1.png" class="lazyload">
<div class="tvv-name">Discovery Kids
<div hidden>Kids
</div hidden></div></a></div>

<a href="https://dora-bash-live.blogspot.com/p/nick-hd.html">
<div class="tvv-item">  <img class="loading" alt="Nick HD+" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-11658-j9k5lvgo-v1/imageContent-11658-j9k5lvgo-m1.png" class="lazyload">
<div class="tvv-name">Nick HD+
<div hidden>Kids
</div hidden></div></a></div>

<a href="https://dora-bash-live.blogspot.com/p/sony-yay.html">
<div class="tvv-item">  <img class="loading" alt="SONY YAY!" src="https://jiotv.catchup.cdn.jio.com/dare_images/images/Sony_Yay_Hindi.png" class="lazyload">
<div class="tvv-name">SONY YAY! Hindi
<div hidden>Kids
</div hidden></div></a></div>    


<a href="https://dora-bash-live.blogspot.com/p/sony-yay-tamil_18.html">
<div class="tvv-item">  <img class="loading" alt="SONY YAY!" src="https://jiotv.catchup.cdn.jio.com/dare_images/images/Sony_Yay_Tamil.png" class="lazyload">
<div class="tvv-name">SONY YAY! Tamil
<div hidden>Kids
</div hidden></div></a></div> 


<a href="https://dora-bash-live.blogspot.com/p/sony-yay-telegu_18.html">
<div class="tvv-item">  <img class="loading" alt="SONY YAY!" src="https://jiotv.catchup.cdn.jio.com/dare_images/images/Sony_Yay_Telugu.png" class="lazyload">
<div class="tvv-name">SONY YAY! Telugu
<div hidden>Kids
</div hidden></div></a></div>       


<a href="https://dora-bash-live.blogspot.com/p/super-hungama.html">
<div class="tvv-item">  <img class="loading" alt="Super Hungama" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-35365-jr3xz4uo-v5/imageContent-35365-jr3xz4uo-m6.png" class="lazyload">
<div class="tvv-name">Super Hungama
<div hidden>Kids
</div hidden></div></a></div>

<a href="https://dora-bash-live.blogspot.com/p/disney.html">
<div class="tvv-item">  <img class="loading" alt="Disney" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-1356-j5tdnwmw-v1/imageContent-1356-j5tdnwmw-m1.png" class="lazyload">
<div class="tvv-name">Disney
<div hidden>Kids
</div hidden></div></a></div>


<a href="http://dora-bash-live.blogspot.com/p/disney-hd.html">
<div class="tvv-item">  <img class="loading" alt="Disney HD 1" src="https://i.postimg.cc/sxrdh4tT/Untitled-design-3.png" class="lazyload">
<div class="tvv-name">Disney HD 1
<div hidden>Kids
</div hidden></div></a></div>


<a href="http://dora-bash-live.blogspot.com/p/disney-hd_98.html">
<div class="tvv-item">  <img class="loading" alt="Disney HD 2" src="https://i.postimg.cc/sxrdh4tT/Untitled-design-3.png" class="lazyload">
<div class="tvv-name">Disney HD 2
<div hidden>Kids
</div hidden></div></a></div>

<a href="intent:https://8ieb.short.gy/Disney_HD-Dora_Bash.m3u#Intent;package=com.mxtech.videoplayer.ad;S.title=Disney_HD-Dora_Bash;end">
<div class="tvv-item">  <img class="loading" alt="Disney HD 3" src="https://i.postimg.cc/sxrdh4tT/Untitled-design-3.png" class="lazyload">
<div class="tvv-name">Disney HD 3
<div hidden>Kids
</div hidden></div></a></div>


<a href="https://dora-bash-live.blogspot.com/p/disney-junior.html">
<div class="tvv-item">  <img class="loading" alt="Disney Junior" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-35368-jr3xz7xs-v1/imageContent-35368-jr3xz7xs-m1.png" class="lazyload">
<div class="tvv-name">Disney Junior
<div hidden>Kids
</div hidden></div></a></div>


<a href="https://dora-bash-live.blogspot.com/p/etv-bal-bharat.html">
<div class="tvv-item">  <img class="loading" alt="ETV Bal Bharat" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-62236-kny7yzaw-v1/imageContent-62236-kny7yzaw-m1.png" class="lazyload">
<div class="tvv-name">ETV Bal Bharat
<div hidden>Kids
</div hidden></div></a></div>



<a href="https://dora-bash-live.blogspot.com/p/pogo.html">
<div class="tvv-item">  <img class="loading" alt="Pogo" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-2694-j638bugw-v1/imageContent-2694-j638bugw-m1.png" class="lazyload">
<div class="tvv-name">Pogo
<div hidden>Kids
</div hidden></div></a></div>

<a href="https://dora-bash-live.blogspot.com/p/nick_56.html">
<div class="tvv-item">  <img class="loading" alt="Nick" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-465-j5jw9va0-v1/imageContent-465-j5jw9va0-m1.png" class="lazyload">
<div class="tvv-name">Nick
<div hidden>Kids
</div hidden></div></a></div>


<a href="https://dora-bash-live.blogspot.com/p/nick-junior.html">
<div class="tvv-item">  <img class="loading" alt="Nick Junior" src="https://i.postimg.cc/c1F6SKYV/Nick-Junior.png" class="lazyload">
<div class="tvv-name">Nick Junior
<div hidden>Kids
</div hidden></div></a></div>


<a href="https://dora-bash-live.blogspot.com/p/gubbare.html">
<div class="tvv-item">  <img class="loading" alt="Gubbare" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-57985-khvdchrs-v2/imageContent-57985-khvdchrs-m2.png" class="lazyload">
<div class="tvv-name">Gubbare
<div hidden>Kids
</div hidden></div></a></div>


<a href="https://dora-bash-live.blogspot.com/p/sonic.html">
<div class="tvv-item">  <img class="loading" alt="Sonic" src="https://ltsk-cdn.s3.eu-west-1.amazonaws.com/jumpstart/Temp_Live/cdn/HLS/Channel/imageContent-8018-j7a7n1a8-v1/imageContent-8018-j7a7n1a8-m1.png" class="lazyload">
<div class="tvv-name">Sonic
<div hidden>Kids
</div hidden></div></a></div>


<a href="intent:https://8ieb.short.gy/Hungama_Live_1-Dora_Bash.ts#Intent;package=com.mxtech.videoplayer.ad;S.title=Hungama_Live-Dora_Bash;end">
<div class="tvv-item">  <img class="loading" alt="Hungama 1" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/Hungama_TV.svg/1200px-Hungama_TV.svg.png" class="lazyload">
<div class="tvv-name">Hungama 1
<div hidden>Kids
</div hidden></div></a></div>


<a href="intent:https://8ieb.short.gy/Hungama_Live-Dora_Bash.m3u#Intent;package=com.mxtech.videoplayer.ad;S.title=Hungama_Live-Dora_Bash;end">
<div class="tvv-item">  <img class="loading" alt="Hungama 2" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/Hungama_TV.svg/1200px-Hungama_TV.svg.png" class="lazyload">
<div class="tvv-name">Hungama 2
<div hidden>Kids
</div hidden></div></a></div>      

<a href="intent:http://202.125.144.115:8000/play/a00g/index.m3u8#Intent;package=com.mxtech.videoplayer.ad;S.title=Hungama_Live-Dora_Bash;end">
<div class="tvv-item">  <img class="loading" alt="Hungama 3" src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/9c/Hungama_TV.svg/1200px-Hungama_TV.svg.png" class="lazyload">
<div class="tvv-name">Hungama 3
<div hidden>Kids
</div hidden></div></a></div>      

<a href="https://dora-bash-live.blogspot.com/p/animax-india.html">
<div class="tvv-item">  <img class="loading" alt="Animax" src="https://jiotv.catchup.cdn.jio.com/dare_images/images/Animax.png" class="lazyload">
<div class="tvv-name">Animax India
<div hidden>Kids
</div hidden></div></a></div>



           </div>
         </a>
         </div>
      <center></center>
      <div style="display:inline-block">
        <b>
          <a href="https://t.me/+sFANm-FHD_k1ZTY9">
            <button class="btn-11 custom-btn" style="width:100vw;height:40px;margin-top:10px;font-size:15px; font-family: cursive">
              <b>Made By Dora Bash</b>
            </button>
          </a>
          <b></b>
        </b>
      </div>
      <b>
        <b></b>
      </b>
    </center>
    <b>
      <b>
        <div><br>
       <p><center>Note: Hungama And Disney HD 3 Needs<a href="https://play.google.com/store/apps/details?id=com.mxtech.videoplayer.ad"><p style="color:red;">MX Player</p></a>To Play</center></p>
        <div class="stwRainbow"></div>
        <div class="stwBlurRainbow"></div>
        <script>
          $(document).ready(function() {
            var dftr = $('select.dftr'),
              headerCount = $('#headerCount');
            headerCount.html('select a filter or use search');
            dftr.on('change', function() {
              dftr.attr('disabled', 'disabled');
              var records = $('#tvvTable').find('.tvv-item');
              records.hide();
              var critriaAttributes = [];
              dftr.each(function() {
                var $this = $(this),
                  $selectedLength = $this.find(':selected').length,
                  $critriaAttribute = '';
                if ($selectedLength > 0 && $this.val() != '0') {
                  if ($selectedLength == 1) {
                    $critriaAttribute += '[data-' + $this.data('attribute') + '*="' + $this.val() + '"]';
                  } else {
                    var $startDataAttribute = '[data-' + $this.data('attribute') + '*="',
                      $endDataAttribute = '"]',
                      $selectedValues = $this.val().toString();
                    $critriaAttribute += $startDataAttribute + $selectedValues.replaceAll(',', ($endDataAttribute + ',' + $startDataAttribute)) + $endDataAttribute;
                  }
                  critriaAttributes.push($critriaAttribute);
                }
              });
              var $showRecords = records;
              if (critriaAttributes.length > 0) {
                $.each(critriaAttributes, function(i, filterValue) {
                  $showRecords = $showRecords.filter(filterValue);
                });
              }
              $showRecords.show();
              headerCount.html($showRecords.length + ' channels filtered');
              dftr.removeAttr('disabled');
              $(".fin").val('');
            });
            $(".fin").keyup(function() {
              var filter = $(this).val(),
                count = 0;
              $('select.dftr').prop('selectedIndex', 0);
              $(".tvv-item").each(function() {
                if ($(this).text().search(new RegExp(filter, "i")) < 0) {
                  $(this).fadeOut();
                } else {
                  $(this).show();
                  count++;
                }
              });
            });
          });
        </script>
      </b>
    </b>
  </body>
</html>
