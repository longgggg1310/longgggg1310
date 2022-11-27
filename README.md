<!DOCTYPE html>
<html lang="en" >
<head>
  <meta charset="UTF-8">
  <title> Kodama with Family https://codepen.io/WilliamStaudenmeier/pen/xxzjgwd </title>
  <meta name="viewport" content="width=device-width, initial-scale=1"><link rel="stylesheet">
<link rel="stylesheet" href="./style.css">
<META HTTP-EQUIV=”refresh” CONTENT=”10″>
</head>
<body>
<!-- partial:index.partial.html -->
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>
<div class="firefly"></div>

<div class="wrapper">
   <h1 class='intro'> 
    <img src="https://readme-typing-svg.demolab.com?font=Arial&size=20&duration=8000&color=FFFFFF&background=00000010&pause=10000&multiline=true&width=200&height=30&lines= + +Hm...+strange+weather"alt="Typing SVG" />
  </h1>
  <div class="wrapper2">
  <div class="kodama">
    <div class="body">
      <div class="legs"></div>
    </div>
    <div class="head">
      <div class="mouth"></div>
      <h1 class ="dialogue"></>
    </div>
    </div>
  </div>
</div>

<div class="kodama2">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
  <div class="mouth"></div>
</div>
<div class="kodama3">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>
<div class="kodama4">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>

<div class="kodama5">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>

<div class="kodama6">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>

<div class="kodama7">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>

<div class="kodama8">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>

<div class="kodama8">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>

<div class="kodama9">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>

<div class="kodama10">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>
<div class="kodama11">
  <div class="head"></div>
  <div class="eye1"></div>
  <div class="eye2"></div>
  <div class="body"></div>
  <div class="arm1"></div>
  <div class="arm2"></div>
</div>

<div class="moon"></div>
<!-- partial -->
  <script  src="./script.js"></script>

</body>
</html>

  # studio ghibli
  # princess mononoke




*, *:after, *:before {
  box-sizing: border-box;
}

html, body {margin: 0; height: 100%; overflow: hidden}

.firefly {
  position: fixed;
  left: 50%;
  top: 50%;
  width: 4vw;
  height: 4vw;
  margin: -0.2vw 0 0 9.8vw;
  animation: ease 200s alternate infinite;
  pointer-events: none;
  z-index:1000;
}

div {
  animation:b 10000000000s linear 100;
}

@keyframes b {
  100% { bottom:50%; opacity:0; }
}

.kodama {
  buffer-top:24px;
  box-shadow:50%;
  display: flex;
  flex-direction: column-reverse;
  align-items: center;
}

.kodama .head {
  opacity:.8;
  margin-top:4px;
  width: 68px;
  height: 65px; 
  background-image: linear-gradient(#fff,#fff,#fff,#fff,#fff,#fff,#fff,#fff,#fff,#7caead);
  transform: rotateZ(15deg);
  border-radius: 50% 50% 40% 70% / 50% 50% 60% 50%; 
 
  -webkit-animation: rotation 8s 4s infinite;
          animation: rotation 8s 4s i nfinite;
  box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6)
}
.kodama .head:after {
  content: "";
  width: 10px;
  height: 10px;
  background-color: #334;
  position: absolute;
  top: 25px;
  left: 10px;
  border-radius: 20px;
}
.kodama .head:before {
  content: "";
  width: 7px;
  height: 7px;
  background-color: #334;
  position: absolute;
  top: 10px;
  right: 10px;
  border-radius: 20px;
}
.kodama .head .mouth {
  content: "";
  width: 7px;
  height: 7px;
  background-color: #334;
  position: absolute;
  bottom: 10px;
  right: 10px;
  border-radius: 20px;
}
@-webkit-keyframes rotation {
  0%, 40%, 42%, 44%, 46%, 48%, 50%, 52%, 54%, 56%, 58%, 60%, 62%, 64%, 66%, 68%, 70%, 72%, 74%, 76%, 78%, 80%, 82%, 84%, 86%, 88%, 90%, 100% {
    transform: rotateZ(15deg);
  
  }
  39% {
    transform: rotateZ(-35deg);
   
  }
  
  85% {
    transform: rotateZ(10deg);
  
  }
  87% {
    transform: rotateZ(12deg);
   
  }
  89% {
    transform: rotateZ(14deg);

  }
}
@keyframes rotation {
  0%, 40%, 42%, 44%, 46%, 48%, 50%, 52%, 54%, 56%, 58%, 60%, 62%, 64%, 66%, 68%, 70%, 72%, 74%, 76%, 78%, 80%, 82%, 84%, 86%, 88%, 90%, 100% {
    transform: rotateZ(-95deg);
    
  }
  39% {
    transform: rotateZ(-35deg);
  }
  41% {
    transform: rotateZ(-34deg);
  }
  43% {
    transform: rotateZ(-32deg);
  }
  45% {
    transform: rotateZ(-30deg);
  }
  47% {
    transform: rotateZ(-28deg);
  }
  49% {
    transform: rotateZ(-26deg);
  }
  
  59% {
    transform: rotateZ(-16deg);
  }
  61% {
    transform: rotateZ(-14deg);
  }
  63% {
    transform: rotateZ(-12deg);
  }
  65% {
    transform: rotateZ(-10deg);
  }
  67% {
    transform: rotateZ(-8deg);
  }
  69% {
    transform: rotateZ(-6deg);
  }
  71% {
    transform: rotateZ(-4deg);
  }
  73% {
    transform: rotateZ(-2deg);
  }

  89% {
    transform: rotateZ(14deg);
  }
}
.kodama .body {
  background-image: linear-gradient(#7caead,#fff,#7caead, transparent);
  opacity:.1;
  height: 35px;
  width: 20px;
  border-radius: 0 0 20px 20px;
 
  margin-top: -10px;
  z-index: 0;
  
  position: relative;
  box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
}
.kodama .body:after, .kodama .body:before {
  #opacity:.8;
  content: "";
  height: 80%;
  width: 15px;
  background-image: linear-gradient(#7caead,#fff,#7caead);
  position: absolute;
  box-shadow: 0 0 5px 10px rgb(0, 51, 34,.5);
  #border: 2px solid #112;
}
.kodama .body:after {
  left: 85%;
  border-radius: 100% 100% 20px 20px;
  transform: rotateZ(-10deg);
}
.kodama .body:before {
  right: 85%;
  border-radius: 100% 100% 20px 20px;
  transform: rotateZ(10deg);
}
.kodama .body .legs {
  opacity:.8;
  position: absolute;
  top: 70%;
  left: 50%;
  transform: translateX(-50%);
}
.kodama .body .legs:after, .kodama .body .legs:before {
  box-shadow: 0 0 5px 10px rgb(0, 51, 34,.5);
  content: "";
  height: 25px;
  width: 9px;
  background-image: linear-gradient(transparent,#7caead,#fff,#7caead, transparent);
  position: absolute;
  #border: 2px solid #112;
}
.kodama .body .legs:after {
  left: 90%;
  border-radius: 20px 20px 100% 100%;
  transform: rotateZ(1deg);
}
.kodama .body .legs:before {
  right: 90%;
  border-radius: 20px 20px 100% 100%;
  transform: rotateZ(-1deg);
}


.intro {
  top:2vh;
  right:10vh;
  color:rgb(238, 230, 255);
  font-family: Arial;
  font-size: 1.2em;
}

.dialog {
  top:2vh;
  right:10vh;
  color: transparent;
  font-family: Arial;
  font-size: 1.2em;
}

hr:not(.bomb) {
  width: 50px;
  border-color: transparent;
  #border-style: solid;
  border-right-color: rgb(0, 255, 204);
  box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
  border-right-width: 100px;
  opacity: .3;
  position: absolute;
  bottom: 100%;
  transform-origin: 100% 50%;
  animation-name: rain;
  animation-duration: 2s;
  animation-timing-function: linear;
  animation-iteration-count: 20;
  -webkit-animation: rainshadow 1s infinite;
  -webkit-animation-duration: 5s; 
}
@-webkit-keyframes rainshadow {

  100% {border-right-color: transparent;}

}

@-webkit-keyframes rotation2 {
  0%, 40%, 42%, 44%, 46%, 48%, 50%, 52%, 54%, 56%, 58%, 60%, 62%, 64%, 66%, 68%, 70%, 72%, 74%, 76%, 78%, 80%, 82%, 84%, 86%, 88%, 90%, 100% {
    transform: rotateZ(15deg);
  }
  39% {
    transform: rotateZ(-35deg);
  }
  41% {
    transform: rotateZ(-34deg);
  }
  43% {
    transform: rotateZ(-32deg);
  }
  45% {
    transform: rotateZ(-30deg);
  }
  47% {
    transform: rotateZ(-28deg);
  }
  49% {
    transform: rotateZ(-26deg);
  }
  51% {
    transform: rotateZ(-24deg);
  }
  53% {
    transform: rotateZ(-22deg);
  }
  55% {
    transform: rotateZ(-20deg);
  }
  57% {
    transform: rotateZ(-18deg);
  }
  59% {
    transform: rotateZ(-16deg);
  }
  61% {
    transform: rotateZ(-14deg);
  }
  63% {
    transform: rotateZ(-12deg);
  }
  65% {
    transform: rotateZ(-10deg);
  }
  67% {
    transform: rotateZ(-8deg);
  }
  69% {
    transform: rotateZ(-6deg);
  }
  71% {
    transform: rotateZ(-4deg);
  }
  73% {
    transform: rotateZ(-2deg);
  }
  75% {
    transform: rotateZ(0deg);
  }
  77% {
    transform: rotateZ(2deg);
  }
  79% {
    transform: rotateZ(4deg);
  }
  81% {
    transform: rotateZ(6deg);
  }
  83% {
    transform: rotateZ(8deg);
  }
  85% {
    transform: rotateZ(10deg);
  }
  87% {
    transform: rotateZ(12deg);
  }
  89% {
    transform: rotateZ(14deg);
  }
}
@keyframes rotation2 {
  0%, 40%, 42%, 44%, 46%, 48%, 50%, 52%, 54%, 56%, 58%, 60%, 62%, 64%, 66%, 68%, 70%, 72%, 74%, 76%, 78%, 80%, 82%, 84%, 86%, 88%, 90%, 100% {
    transform: rotateZ(15deg);
  }
  39% {
    transform: rotateZ(-35deg);
  }
  41% {
    transform: rotateZ(-34deg);
  }
  43% {
    transform: rotateZ(-32deg);
  }
  45% {
    transform: rotateZ(-30deg);
  }
  47% {
    transform: rotateZ(-28deg);
  }
  49% {
    transform: rotateZ(-26deg);
  }
  51% {
    transform: rotateZ(-24deg);
  }
  53% {
    transform: rotateZ(-22deg);
  }
  55% {
    transform: rotateZ(-20deg);
  }
  57% {
    transform: rotateZ(-18deg);
  }
  59% {
    transform: rotateZ(-16deg);
  }
  61% {
    transform: rotateZ(-14deg);
  }
  63% {
    transform: rotateZ(-12deg);
  }
  65% {
    transform: rotateZ(-10deg);
  }
  67% {
    transform: rotateZ(-8deg);
  }
  69% {
    transform: rotateZ(-6deg);
  }
  71% {
    transform: rotateZ(-4deg);
  }
  73% {
    transform: rotateZ(-2deg);
  }
  75% {
    transform: rotateZ(0deg);
  }
  77% {
    transform: rotateZ(2deg);
  }
  79% {
    transform: rotateZ(4deg);
  }
  81% {
    transform: rotateZ(6deg);
  }
  83% {
    transform: rotateZ(8deg);
  }
  85% {
    transform: rotateZ(10deg);
  }
  87% {
    transform: rotateZ(12deg);
  }
  89% {
    transform: rotateZ(14deg);
  }
}

@keyframes rain {
  from {
    transform: rotate(95deg) translateX(0);
  }
  to {
    transform: rotate(50deg) translateX(calc(100vh + 20px));
  }
   to {
    transform: rotate(95deg) translateX(calc(100vh + 20px));
  }
}

.firefly::before, .firefly::after {
  content: "";
  position: absolute;
  width: 100%;
  height: 100%;
  border-radius: 50%;
  transform-origin: -10vw;
}
.firefly::before {
  background: transparent;
  opacity: 0.1;
  animation: drift ease alternate infinite;
}
.firefly::after {
  background: white;
  opacity: 0;
  box-shadow: 0 0 0vw 0vw blue;
  animation: drift ease alternate infinite, flash ease infinite;
}

.firefly:nth-child(1) {
  animation-name: move1;
}
.firefly:nth-child(1)::before {
  animation-duration: 15s;
}
.firefly:nth-child(1)::after {
  animation-duration: 15s, 10452ms;
  animation-delay: 0ms, 2217ms;
}

@keyframes move1 {
  0% {
    transform: translateX(14vw) translateY(38vh) scale(0.55);
  }
  5.8823529412% {
    transform: translateX(49vw) translateY(-6vh) scale(0.29);
  }
  11.7647058824% {
    transform: translateX(24vw) translateY(-36vh) scale(0.4);
  }
  17.6470588235% {
    transform: translateX(-12vw) translateY(23vh) scale(0.92);
  }
  23.5294117647% {
    transform: translateX(-13vw) translateY(49vh) scale(0.98);
  }
  29.4117647059% {
    transform: translateX(-13vw) translateY(-36vh) scale(0.59);
  }
  35.2941176471% {
    transform: translateX(-29vw) translateY(13vh) scale(0.5);
  }
  41.1764705882% {
    transform: translateX(-42vw) translateY(-6vh) scale(0.85);
  }
  47.0588235294% {
    transform: translateX(-12vw) translateY(5vh) scale(0.65);
  }
  52.9411764706% {
    transform: translateX(47vw) translateY(22vh) scale(0.93);
  }
  58.8235294118% {
    transform: translateX(-12vw) translateY(33vh) scale(1);
  }
  64.7058823529% {
    transform: translateX(-37vw) translateY(-25vh) scale(0.66);
  }
  70.5882352941% {
    transform: translateX(-9vw) translateY(17vh) scale(0.84);
  }
  76.4705882353% {
    transform: translateX(34vw) translateY(15vh) scale(0.29);
  }
  82.3529411765% {
    transform: translateX(-11vw) translateY(-15vh) scale(0.86);
  }
  88.2352941176% {
    transform: translateX(-35vw) translateY(30vh) scale(0.94);
  }
  94.1176470588% {
    transform: translateX(22vw) translateY(-1vh) scale(0.51);
  }
  100% {
    transform: translateX(-19vw) translateY(6vh) scale(0.9);
  }
}
.firefly:nth-child(2) {
  animation-name: move2;
}
.firefly:nth-child(2)::before {
  animation-duration: 14s;
}
.firefly:nth-child(2)::after {
  animation-duration: 14s, 5687ms;
  animation-delay: 0ms, 7606ms;
}

@keyframes move2 {
  0% {
    transform: translateX(-49vw) translateY(45vh) scale(0.26);
  }
  5% {
    transform: translateX(23vw) translateY(-8vh) scale(0.96);
  }
  10% {
    transform: translateX(-34vw) translateY(-40vh) scale(0.57);
  }
  15% {
    transform: translateX(23vw) translateY(20vh) scale(0.4);
  }
  20% {
    transform: translateX(-31vw) translateY(31vh) scale(0.84);
  }
  25% {
    transform: translateX(18vw) translateY(-39vh) scale(0.42);
  }
  30% {
    transform: translateX(-43vw) translateY(45vh) scale(0.68);
  }
  35% {
    transform: translateX(-41vw) translateY(50vh) scale(0.5);
  }
  40% {
    transform: translateX(19vw) translateY(19vh) scale(0.95);
  }
  45% {
    transform: translateX(-33vw) translateY(43vh) scale(0.66);
  }
  50% {
    transform: translateX(24vw) translateY(-20vh) scale(0.57);
  }
  55% {
    transform: translateX(18vw) translateY(-42vh) scale(0.83);
  }
  60% {
    transform: translateX(25vw) translateY(32vh) scale(1);
  }
  65% {
    transform: translateX(11vw) translateY(15vh) scale(0.33);
  }
  70% {
    transform: translateX(-12vw) translateY(-23vh) scale(0.63);
  }
  75% {
    transform: translateX(49vw) translateY(37vh) scale(0.51);
  }
  80% {
    transform: translateX(-11vw) translateY(-10vh) scale(0.77);
  }
  85% {
    transform: translateX(-25vw) translateY(-5vh) scale(0.42);
  }
  90% {
    transform: translateX(-32vw) translateY(2vh) scale(0.96);
  }
  95% {
    transform: translateX(45vw) translateY(-30vh) scale(0.3);
  }
  100% {
    transform: translateX(8vw) translateY(-41vh) scale(0.52);
  }
}
.firefly:nth-child(3) {
  animation-name: move3;
}
.firefly:nth-child(3)::before {
  animation-duration: 10s;
}
.firefly:nth-child(3)::after {
  animation-duration: 10s, 10797ms;
  animation-delay: 0ms, 2193ms;
}

@keyframes move3 {
  0% {
    transform: translateX(23vw) translateY(44vh) scale(0.59);
  }
  3.8461538462% {
    transform: translateX(-48vw) translateY(31vh) scale(0.31);
  }
  7.6923076923% {
    transform: translateX(-2vw) translateY(-15vh) scale(0.41);
  }
  11.5384615385% {
    transform: translateX(0vw) translateY(-17vh) scale(0.98);
  }
  15.3846153846% {
    transform: translateX(48vw) translateY(0vh) scale(0.81);
  }
  19.2307692308% {
    transform: translateX(21vw) translateY(-13vh) scale(0.79);
  }
  23.0769230769% {
    transform: translateX(-2vw) translateY(-44vh) scale(0.58);
  }
  26.9230769231% {
    transform: translateX(-3vw) translateY(33vh) scale(0.75);
  }
  30.7692307692% {
    transform: translateX(6vw) translateY(-6vh) scale(0.84);
  }
  34.6153846154% {
    transform: translateX(-17vw) translateY(39vh) scale(0.86);
  }
  38.4615384615% {
    transform: translateX(1vw) translateY(3vh) scale(0.62);
  }
  42.3076923077% {
    transform: translateX(-6vw) translateY(48vh) scale(0.5);
  }
  46.1538461538% {
    transform: translateX(43vw) translateY(30vh) scale(0.82);
  }
  50% {
    transform: translateX(14vw) translateY(32vh) scale(0.46);
  }
  53.8461538462% {
    transform: translateX(-24vw) translateY(11vh) scale(0.33);
  }
  57.6923076923% {
    transform: translateX(6vw) translateY(5vh) scale(0.35);
  }
  61.5384615385% {
    transform: translateX(26vw) translateY(42vh) scale(0.69);
  }
  65.3846153846% {
    transform: translateX(33vw) translateY(-29vh) scale(0.94);
  }
  69.2307692308% {
    transform: translateX(46vw) translateY(-32vh) scale(0.8);
  }
  73.0769230769% {
    transform: translateX(-35vw) translateY(45vh) scale(0.7);
  }
  76.9230769231% {
    transform: translateX(-27vw) translateY(4vh) scale(0.52);
  }
  80.7692307692% {
    transform: translateX(-35vw) translateY(41vh) scale(0.78);
  }
  84.6153846154% {
    transform: translateX(-31vw) translateY(-37vh) scale(0.34);
  }
  88.4615384615% {
    transform: translateX(-35vw) translateY(9vh) scale(0.34);
  }
  92.3076923077% {
    transform: translateX(-23vw) translateY(26vh) scale(0.82);
  }
  96.1538461538% {
    transform: translateX(-35vw) translateY(-18vh) scale(0.29);
  }
  100% {
    transform: translateX(23vw) translateY(50vh) scale(0.39);
  }
}
.firefly:nth-child(4) {
  animation-name: move4;
}
.firefly:nth-child(4)::before {
  animation-duration: 14s;
}
.firefly:nth-child(4)::after {
  animation-duration: 14s, 9436ms;
  animation-delay: 0ms, 1078ms;
}

@keyframes move4 {
  0% {
    transform: translateX(-15vw) translateY(16vh) scale(0.4);
  }
  5% {
    transform: translateX(-20vw) translateY(44vh) scale(0.31);
  }
  10% {
    transform: translateX(-40vw) translateY(-14vh) scale(0.48);
  }
  15% {
    transform: translateX(30vw) translateY(-13vh) scale(0.72);
  }
  20% {
    transform: translateX(31vw) translateY(-38vh) scale(0.27);
  }
  25% {
    transform: translateX(-45vw) translateY(-1vh) scale(0.72);
  }
  30% {
    transform: translateX(-39vw) translateY(-42vh) scale(0.92);
  }
  35% {
    transform: translateX(17vw) translateY(-24vh) scale(0.85);
  }
  40% {
    transform: translateX(2vw) translateY(8vh) scale(0.47);
  }
  45% {
    transform: translateX(29vw) translateY(50vh) scale(0.32);
  }
  50% {
    transform: translateX(-24vw) translateY(-46vh) scale(0.32);
  }
  55% {
    transform: translateX(-19vw) translateY(44vh) scale(0.65);
  }
  60% {
    transform: translateX(35vw) translateY(-6vh) scale(0.98);
  }
  65% {
    transform: translateX(40vw) translateY(-25vh) scale(0.85);
  }
  70% {
    transform: translateX(-46vw) translateY(7vh) scale(0.38);
  }
  75% {
    transform: translateX(48vw) translateY(-8vh) scale(0.74);
  }
  80% {
    transform: translateX(42vw) translateY(36vh) scale(0.41);
  }
  85% {
    transform: translateX(15vw) translateY(-33vh) scale(0.9);
  }
  90% {
    transform: translateX(-10vw) translateY(-18vh) scale(0.6);
  }
  95% {
    transform: translateX(47vw) translateY(9vh) scale(0.55);
  }
  100% {
    transform: translateX(1vw) translateY(-28vh) scale(0.33);
  }
}
.firefly:nth-child(5) {
  animation-name: move5;
}
.firefly:nth-child(5)::before {
  animation-duration: 11s;
}
.firefly:nth-child(5)::after {
  animation-duration: 11s, 5316ms;
  animation-delay: 0ms, 3010ms;
}

@keyframes move5 {
  0% {
    transform: translateX(41vw) translateY(-19vh) scale(0.72);
  }
  4.7619047619% {
    transform: translateX(13vw) translateY(20vh) scale(0.73);
  }
  9.5238095238% {
    transform: translateX(-35vw) translateY(-40vh) scale(0.33);
  }
  14.2857142857% {
    transform: translateX(-4vw) translateY(-47vh) scale(0.55);
  }
  19.0476190476% {
    transform: translateX(8vw) translateY(-18vh) scale(0.56);
  }
  23.8095238095% {
    transform: translateX(42vw) translateY(-15vh) scale(0.94);
  }
  28.5714285714% {
    transform: translateX(-30vw) translateY(20vh) scale(0.42);
  }
  33.3333333333% {
    transform: translateX(10vw) translateY(-21vh) scale(0.8);
  }
  38.0952380952% {
    transform: translateX(-27vw) translateY(50vh) scale(0.95);
  }
  42.8571428571% {
    transform: translateX(-37vw) translateY(-17vh) scale(0.26);
  }
  47.619047619% {
    transform: translateX(-39vw) translateY(-45vh) scale(0.73);
  }
  52.380952381% {
    transform: translateX(-19vw) translateY(46vh) scale(0.54);
  }
  57.1428571429% {
    transform: translateX(-11vw) translateY(14vh) scale(0.29);
  }
  61.9047619048% {
    transform: translateX(36vw) translateY(-11vh) scale(0.6);
  }
  66.6666666667% {
    transform: translateX(-18vw) translateY(27vh) scale(0.49);
  }
  71.4285714286% {
    transform: translateX(-31vw) translateY(-23vh) scale(0.49);
  }
  76.1904761905% {
    transform: translateX(19vw) translateY(-20vh) scale(0.41);
  }
  80.9523809524% {
    transform: translateX(-49vw) translateY(39vh) scale(0.92);
  }
  85.7142857143% {
    transform: translateX(47vw) translateY(-40vh) scale(0.29);
  }
  90.4761904762% {
    transform: translateX(13vw) translateY(41vh) scale(0.37);
  }
  95.2380952381% {
    transform: translateX(13vw) translateY(50vh) scale(0.67);
  }
  100% {
    transform: translateX(-6vw) translateY(-25vh) scale(0.27);
  }
}
.firefly:nth-child(6) {
  animation-name: move6;
}
.firefly:nth-child(6)::before {
  animation-duration: 9s;
}
.firefly:nth-child(6)::after {
  animation-duration: 9s, 6543ms;
  animation-delay: 0ms, 4421ms;
}

@keyframes move6 {
  0% {
    transform: translateX(-15vw) translateY(-14vh) scale(0.74);
  }
  4.1666666667% {
    transform: translateX(13vw) translateY(-44vh) scale(0.69);
  }
  8.3333333333% {
    transform: translateX(-15vw) translateY(44vh) scale(0.7);
  }
  12.5% {
    transform: translateX(8vw) translateY(-45vh) scale(0.88);
  }
  16.6666666667% {
    transform: translateX(-36vw) translateY(-5vh) scale(0.66);
  }
  20.8333333333% {
    transform: translateX(26vw) translateY(-9vh) scale(0.51);
  }
  25% {
    transform: translateX(35vw) translateY(21vh) scale(0.83);
  }
  29.1666666667% {
    transform: translateX(-23vw) translateY(-3vh) scale(0.63);
  }
  33.3333333333% {
    transform: translateX(42vw) translateY(11vh) scale(0.82);
  }
  37.5% {
    transform: translateX(14vw) translateY(47vh) scale(0.29);
  }
  41.6666666667% {
    transform: translateX(-15vw) translateY(-28vh) scale(0.29);
  }
  45.8333333333% {
    transform: translateX(43vw) translateY(-14vh) scale(0.29);
  }
  50% {
    transform: translateX(41vw) translateY(18vh) scale(0.9);
  }
  54.1666666667% {
    transform: translateX(42vw) translateY(33vh) scale(0.75);
  }
  58.3333333333% {
    transform: translateX(-45vw) translateY(49vh) scale(0.77);
  }
  62.5% {
    transform: translateX(45vw) translateY(7vh) scale(0.49);
  }
  66.6666666667% {
    transform: translateX(-43vw) translateY(-30vh) scale(0.63);
  }
  70.8333333333% {
    transform: translateX(4vw) translateY(-18vh) scale(0.78);
  }
  75% {
    transform: translateX(-43vw) translateY(-8vh) scale(0.6);
  }
  79.1666666667% {
    transform: translateX(3vw) translateY(41vh) scale(0.94);
  }
  83.3333333333% {
    transform: translateX(27vw) translateY(29vh) scale(0.73);
  }
  87.5% {
    transform: translateX(-47vw) translateY(-31vh) scale(0.5);
  }
  91.6666666667% {
    transform: translateX(48vw) translateY(4vh) scale(0.37);
  }
  95.8333333333% {
    transform: translateX(-21vw) translateY(33vh) scale(0.34);
  }
  100% {
    transform: translateX(8vw) translateY(23vh) scale(0.72);
  }
}
.firefly:nth-child(7) {
  animation-name: move7;
}
.firefly:nth-child(7)::before {
  animation-duration: 13s;
}
.firefly:nth-child(7)::after {
  animation-duration: 13s, 7135ms;
  animation-delay: 0ms, 1608ms;
}

@keyframes move7 {
  0% {
    transform: translateX(33vw) translateY(-36vh) scale(0.95);
  }
  4.347826087% {
    transform: translateX(-19vw) translateY(-45vh) scale(0.63);
  }
  8.6956521739% {
    transform: translateX(15vw) translateY(30vh) scale(0.69);
  }
  13.0434782609% {
    transform: translateX(-12vw) translateY(-31vh) scale(0.52);
  }
  17.3913043478% {
    transform: translateX(-27vw) translateY(13vh) scale(0.59);
  }
  21.7391304348% {
    transform: translateX(9vw) translateY(1vh) scale(0.57);
  }
  26.0869565217% {
    transform: translateX(-5vw) translateY(-36vh) scale(0.94);
  }
  30.4347826087% {
    transform: translateX(9vw) translateY(24vh) scale(0.99);
  }
  34.7826086957% {
    transform: translateX(11vw) translateY(34vh) scale(0.33);
  }
  39.1304347826% {
    transform: translateX(19vw) translateY(-5vh) scale(0.85);
  }
  43.4782608696% {
    transform: translateX(-22vw) translateY(-1vh) scale(0.47);
  }
  47.8260869565% {
    transform: translateX(39vw) translateY(-46vh) scale(0.7);
  }
  52.1739130435% {
    transform: translateX(-31vw) translateY(42vh) scale(0.63);
  }
  56.5217391304% {
    transform: translateX(-20vw) translateY(10vh) scale(0.58);
  }
  60.8695652174% {
    transform: translateX(-46vw) translateY(45vh) scale(0.95);
  }
  65.2173913043% {
    transform: translateX(-17vw) translateY(-34vh) scale(0.98);
  }
  69.5652173913% {
    transform: translateX(-5vw) translateY(33vh) scale(0.51);
  }
  73.9130434783% {
    transform: translateX(30vw) translateY(2vh) scale(0.72);
  }
  78.2608695652% {
    transform: translateX(5vw) translateY(-17vh) scale(0.73);
  }
  82.6086956522% {
    transform: translateX(6vw) translateY(39vh) scale(0.53);
  }
  86.9565217391% {
    transform: translateX(50vw) translateY(-40vh) scale(0.8);
  }
  91.3043478261% {
    transform: translateX(-35vw) translateY(12vh) scale(1);
  }
  95.652173913% {
    transform: translateX(40vw) translateY(-31vh) scale(0.44);
  }
  100% {
    transform: translateX(26vw) translateY(-4vh) scale(0.87);
  }
}
.firefly:nth-child(8) {
  animation-name: move8;
}
.firefly:nth-child(8)::before {
  animation-duration: 10s;
}
.firefly:nth-child(8)::after {
  animation-duration: 10s, 6493ms;
  animation-delay: 0ms, 6096ms;
}

@keyframes move8 {
  0% {
    transform: translateX(0vw) translateY(-7vh) scale(0.97);
  }
  5% {
    transform: translateX(42vw) translateY(46vh) scale(0.74);
  }
  10% {
    transform: translateX(48vw) translateY(-22vh) scale(0.59);
  }
  15% {
    transform: translateX(-5vw) translateY(31vh) scale(0.74);
  }
  20% {
    transform: translateX(28vw) translateY(16vh) scale(0.3);
  }
  25% {
    transform: translateX(-11vw) translateY(-38vh) scale(0.35);
  }
  30% {
    transform: translateX(-48vw) translateY(1vh) scale(0.35);
  }
  35% {
    transform: translateX(-15vw) translateY(-11vh) scale(0.51);
  }
  40% {
    transform: translateX(-41vw) translateY(-12vh) scale(0.82);
  }
  45% {
    transform: translateX(-3vw) translateY(15vh) scale(0.5);
  }
  50% {
    transform: translateX(42vw) translateY(20vh) scale(0.78);
  }
  55% {
    transform: translateX(-36vw) translateY(-22vh) scale(0.97);
  }
  60% {
    transform: translateX(28vw) translateY(-32vh) scale(0.43);
  }
  65% {
    transform: translateX(12vw) translateY(-28vh) scale(0.69);
  }
  70% {
    transform: translateX(-1vw) translateY(19vh) scale(0.91);
  }
  75% {
    transform: translateX(13vw) translateY(39vh) scale(0.74);
  }
  80% {
    transform: translateX(-39vw) translateY(33vh) scale(0.99);
  }
  85% {
    transform: translateX(-21vw) translateY(41vh) scale(0.74);
  }
  90% {
    transform: translateX(-3vw) translateY(10vh) scale(0.86);
  }
  95% {
    transform: translateX(17vw) translateY(2vh) scale(0.5);
  }
  100% {
    transform: translateX(17vw) translateY(-27vh) scale(0.54);
  }
}
.firefly:nth-child(9) {
  animation-name: move9;
}
.firefly:nth-child(9)::before {
  animation-duration: 15s;
}
.firefly:nth-child(9)::after {
  animation-duration: 15s, 7503ms;
  animation-delay: 0ms, 5146ms;
}

@keyframes move9 {
  0% {
    transform: translateX(-8vw) translateY(-3vh) scale(0.57);
  }
  5.5555555556% {
    transform: translateX(-43vw) translateY(9vh) scale(0.44);
  }
  11.1111111111% {
    transform: translateX(44vw) translateY(-14vh) scale(0.8);
  }
  16.6666666667% {
    transform: translateX(-49vw) translateY(-35vh) scale(0.95);
  }
  22.2222222222% {
    transform: translateX(-12vw) translateY(2vh) scale(0.46);
  }
  27.7777777778% {
    transform: translateX(-33vw) translateY(18vh) scale(0.34);
  }
  33.3333333333% {
    transform: translateX(3vw) translateY(-15vh) scale(1);
  }
  38.8888888889% {
    transform: translateX(-41vw) translateY(17vh) scale(0.34);
  }
  44.4444444444% {
    transform: translateX(-47vw) translateY(9vh) scale(0.41);
  }
  50% {
    transform: translateX(-18vw) translateY(-37vh) scale(0.67);
  }
  55.5555555556% {
    transform: translateX(11vw) translateY(-6vh) scale(0.57);
  }
  61.1111111111% {
    transform: translateX(-11vw) translateY(-39vh) scale(0.44);
  }
  66.6666666667% {
    transform: translateX(11vw) translateY(48vh) scale(0.27);
  }
  72.2222222222% {
    transform: translateX(7vw) translateY(-18vh) scale(0.35);
  }
  77.7777777778% {
    transform: translateX(-46vw) translateY(-33vh) scale(0.81);
  }
  83.3333333333% {
    transform: translateX(33vw) translateY(2vh) scale(0.45);
  }
  88.8888888889% {
    transform: translateX(26vw) translateY(-9vh) scale(0.89);
  }
  94.4444444444% {
    transform: translateX(11vw) translateY(-15vh) scale(0.9);
  }
  100% {
    transform: translateX(-10vw) translateY(38vh) scale(0.58);
  }
}
.firefly:nth-child(10) {
  animation-name: move10;
}
.firefly:nth-child(10)::before {
  animation-duration: 11s;
}
.firefly:nth-child(10)::after {
  animation-duration: 11s, 8772ms;
  animation-delay: 0ms, 4701ms;
}

@keyframes move10 {
  0% {
    transform: translateX(-20vw) translateY(-27vh) scale(0.89);
  }
  4.5454545455% {
    transform: translateX(31vw) translateY(-49vh) scale(0.71);
  }
  9.0909090909% {
    transform: translateX(35vw) translateY(34vh) scale(0.89);
  }
  13.6363636364% {
    transform: translateX(27vw) translateY(-43vh) scale(0.37);
  }
  18.1818181818% {
    transform: translateX(-6vw) translateY(35vh) scale(0.63);
  }
  22.7272727273% {
    transform: translateX(-48vw) translateY(-4vh) scale(0.96);
  }
  27.2727272727% {
    transform: translateX(48vw) translateY(21vh) scale(0.9);
  }
  31.8181818182% {
    transform: translateX(-30vw) translateY(33vh) scale(0.89);
  }
  36.3636363636% {
    transform: translateX(-46vw) translateY(-34vh) scale(0.51);
  }
  40.9090909091% {
    transform: translateX(-47vw) translateY(-1vh) scale(0.91);
  }
  45.4545454545% {
    transform: translateX(-10vw) translateY(48vh) scale(0.31);
  }
  50% {
    transform: translateX(-5vw) translateY(-37vh) scale(0.4);
  }
  54.5454545455% {
    transform: translateX(15vw) translateY(-2vh) scale(0.5);
  }
  59.0909090909% {
    transform: translateX(11vw) translateY(21vh) scale(0.66);
  }
  63.6363636364% {
    transform: translateX(-2vw) translateY(29vh) scale(0.96);
  }
  68.1818181818% {
    transform: translateX(-17vw) translateY(-47vh) scale(0.35);
  }
  72.7272727273% {
    transform: translateX(-8vw) translateY(-14vh) scale(0.42);
  }
  77.2727272727% {
    transform: translateX(17vw) translateY(11vh) scale(0.42);
  }
  81.8181818182% {
    transform: translateX(7vw) translateY(43vh) scale(0.26);
  }
  86.3636363636% {
    transform: translateX(20vw) translateY(33vh) scale(0.3);
  }
  90.9090909091% {
    transform: translateX(40vw) translateY(-13vh) scale(0.96);
  }
  95.4545454545% {
    transform: translateX(-20vw) translateY(-28vh) scale(0.57);
  }
  100% {
    transform: translateX(-25vw) translateY(36vh) scale(0.33);
  }
}
.firefly:nth-child(11) {
  animation-name: move11;
}
.firefly:nth-child(11)::before {
  animation-duration: 18s;
}
.firefly:nth-child(11)::after {
  animation-duration: 18s, 6659ms;
  animation-delay: 0ms, 4057ms;
}

@keyframes move11 {
  0% {
    transform: translateX(30vw) translateY(28vh) scale(0.49);
  }
  3.7037037037% {
    transform: translateX(-6vw) translateY(-14vh) scale(0.94);
  }
  7.4074074074% {
    transform: translateX(-6vw) translateY(-44vh) scale(0.86);
  }
  11.1111111111% {
    transform: translateX(24vw) translateY(31vh) scale(0.52);
  }
  14.8148148148% {
    transform: translateX(-28vw) translateY(-13vh) scale(0.82);
  }
  18.5185185185% {
    transform: translateX(-16vw) translateY(0vh) scale(0.61);
  }
  22.2222222222% {
    transform: translateX(-30vw) translateY(28vh) scale(0.98);
  }
  25.9259259259% {
    transform: translateX(-31vw) translateY(16vh) scale(0.63);
  }
  29.6296296296% {
    transform: translateX(37vw) translateY(36vh) scale(0.49);
  }
  33.3333333333% {
    transform: translateX(22vw) translateY(-47vh) scale(0.83);
  }
  37.037037037% {
    transform: translateX(7vw) translateY(3vh) scale(0.4);
  }
  40.7407407407% {
    transform: translateX(8vw) translateY(-13vh) scale(0.36);
  }
  44.4444444444% {
    transform: translateX(19vw) translateY(-45vh) scale(0.35);
  }
  48.1481481481% {
    transform: translateX(-10vw) translateY(34vh) scale(0.89);
  }
  51.8518518519% {
    transform: translateX(39vw) translateY(50vh) scale(0.57);
  }
  55.5555555556% {
    transform: translateX(22vw) translateY(45vh) scale(0.33);
  }
  59.2592592593% {
    transform: translateX(35vw) translateY(17vh) scale(0.8);
  }
  62.962962963% {
    transform: translateX(-42vw) translateY(21vh) scale(0.89);
  }
  66.6666666667% {
    transform: translateX(2vw) translateY(-42vh) scale(0.45);
  }
  70.3703703704% {
    transform: translateX(29vw) translateY(-14vh) scale(0.5);
  }
  74.0740740741% {
    transform: translateX(-13vw) translateY(19vh) scale(0.34);
  }
  77.7777777778% {
    transform: translateX(41vw) translateY(45vh) scale(0.64);
  }
  81.4814814815% {
    transform: translateX(-22vw) translateY(-33vh) scale(0.88);
  }
  85.1851851852% {
    transform: translateX(3vw) translateY(-3vh) scale(0.61);
  }
  88.8888888889% {
    transform: translateX(44vw) translateY(47vh) scale(0.4);
  }
  92.5925925926% {
    transform: translateX(25vw) translateY(-40vh) scale(0.9);
  }
  96.2962962963% {
    transform: translateX(1vw) translateY(-13vh) scale(0.9);
  }
  100% {
    transform: translateX(35vw) translateY(33vh) scale(0.72);
  }
}
.firefly:nth-child(12) {
  animation-name: move12;
}
.firefly:nth-child(12)::before {
  animation-duration: 10s;
}
.firefly:nth-child(12)::after {
  animation-duration: 10s, 10555ms;
  animation-delay: 0ms, 1505ms;
}

@keyframes move12 {
  0% {
    transform: translateX(-44vw) translateY(-27vh) scale(0.37);
  }
  3.7037037037% {
    transform: translateX(44vw) translateY(-45vh) scale(0.77);
  }
  7.4074074074% {
    transform: translateX(22vw) translateY(15vh) scale(0.7);
  }
  11.1111111111% {
    transform: translateX(-2vw) translateY(-24vh) scale(0.79);
  }
  14.8148148148% {
    transform: translateX(-24vw) translateY(45vh) scale(0.39);
  }
  18.5185185185% {
    transform: translateX(-15vw) translateY(-17vh) scale(0.49);
  }
  22.2222222222% {
    transform: translateX(3vw) translateY(-39vh) scale(0.69);
  }
  25.9259259259% {
    transform: translateX(-35vw) translateY(30vh) scale(0.66);
  }
  29.6296296296% {
    transform: translateX(-6vw) translateY(12vh) scale(0.63);
  }
  33.3333333333% {
    transform: translateX(4vw) translateY(-9vh) scale(0.36);
  }
  37.037037037% {
    transform: translateX(-25vw) translateY(41vh) scale(0.86);
  }
  40.7407407407% {
    transform: translateX(21vw) translateY(-7vh) scale(0.86);
  }
  44.4444444444% {
    transform: translateX(38vw) translateY(-29vh) scale(0.67);
  }
  48.1481481481% {
    transform: translateX(-47vw) translateY(30vh) scale(0.85);
  }
  51.8518518519% {
    transform: translateX(26vw) translateY(-19vh) scale(0.97);
  }
  55.5555555556% {
    transform: translateX(2vw) translateY(39vh) scale(0.95);
  }
  59.2592592593% {
    transform: translateX(-36vw) translateY(-45vh) scale(0.57);
  }
  62.962962963% {
    transform: translateX(14vw) translateY(-47vh) scale(0.43);
  }
  66.6666666667% {
    transform: translateX(23vw) translateY(-14vh) scale(0.42);
  }
  70.3703703704% {
    transform: translateX(5vw) translateY(44vh) scale(0.88);
  }
  74.0740740741% {
    transform: translateX(-43vw) translateY(33vh) scale(0.35);
  }
  77.7777777778% {
    transform: translateX(49vw) translateY(12vh) scale(0.34);
  }
  81.4814814815% {
    transform: translateX(-28vw) translateY(6vh) scale(0.48);
  }
  85.1851851852% {
    transform: translateX(36vw) translateY(-23vh) scale(0.26);
  }
  88.8888888889% {
    transform: translateX(35vw) translateY(-49vh) scale(0.51);
  }
  92.5925925926% {
    transform: translateX(-25vw) translateY(31vh) scale(0.75);
  }
  96.2962962963% {
    transform: translateX(3vw) translateY(7vh) scale(0.5);
  }
  100% {
    transform: translateX(45vw) translateY(16vh) scale(0.38);
  }
}
.firefly:nth-child(13) {
  animation-name: move13;
}
.firefly:nth-child(13)::before {
  animation-duration: 16s;
}
.firefly:nth-child(13)::after {
  animation-duration: 16s, 7788ms;
  animation-delay: 0ms, 6289ms;
}

@keyframes move13 {
  0% {
    transform: translateX(18vw) translateY(-24vh) scale(0.65);
  }
  5% {
    transform: translateX(46vw) translateY(46vh) scale(0.3);
  }
  10% {
    transform: translateX(44vw) translateY(30vh) scale(0.26);
  }
  15% {
    transform: translateX(-15vw) translateY(-44vh) scale(0.55);
  }
  20% {
    transform: translateX(50vw) translateY(-34vh) scale(0.66);
  }
  25% {
    transform: translateX(19vw) translateY(-14vh) scale(0.87);
  }
  30% {
    transform: translateX(31vw) translateY(-34vh) scale(0.83);
  }
  35% {
    transform: translateX(15vw) translateY(8vh) scale(0.62);
  }
  40% {
    transform: translateX(12vw) translateY(-20vh) scale(0.72);
  }
  45% {
    transform: translateX(3vw) translateY(-46vh) scale(0.92);
  }
  50% {
    transform: translateX(31vw) translateY(-23vh) scale(0.34);
  }
  55% {
    transform: translateX(42vw) translateY(-10vh) scale(0.78);
  }
  60% {
    transform: translateX(44vw) translateY(-22vh) scale(0.41);
  }
  65% {
    transform: translateX(-29vw) translateY(-8vh) scale(0.58);
  }
  70% {
    transform: translateX(16vw) translateY(49vh) scale(0.67);
  }
  75% {
    transform: translateX(14vw) translateY(-6vh) scale(0.66);
  }
  80% {
    transform: translateX(-44vw) translateY(-27vh) scale(0.39);
  }
  85% {
    transform: translateX(40vw) translateY(-33vh) scale(0.88);
  }
  90% {
    transform: translateX(22vw) translateY(48vh) scale(0.7);
  }
  95% {
    transform: translateX(19vw) translateY(-47vh) scale(0.55);
  }
  100% {
    transform: translateX(-9vw) translateY(-24vh) scale(0.76);
  }
}
.firefly:nth-child(14) {
  animation-name: move14;
}
.firefly:nth-child(14)::before {
  animation-duration: 15s;
}
.firefly:nth-child(14)::after {
  animation-duration: 15s, 7619ms;
  animation-delay: 0ms, 4394ms;
}

@keyframes move14 {
  0% {
    transform: translateX(49vw) translateY(-1vh) scale(0.44);
  }
  5.5555555556% {
    transform: translateX(20vw) translateY(3vh) scale(0.93);
  }
  11.1111111111% {
    transform: translateX(3vw) translateY(-46vh) scale(0.77);
  }
  16.6666666667% {
    transform: translateX(0vw) translateY(37vh) scale(0.26);
  }
  22.2222222222% {
    transform: translateX(35vw) translateY(-6vh) scale(0.62);
  }
  27.7777777778% {
    transform: translateX(-27vw) translateY(-41vh) scale(0.5);
  }
  33.3333333333% {
    transform: translateX(-26vw) translateY(49vh) scale(0.69);
  }
  38.8888888889% {
    transform: translateX(28vw) translateY(-34vh) scale(0.39);
  }
  44.4444444444% {
    transform: translateX(-5vw) translateY(-31vh) scale(0.77);
  }
  50% {
    transform: translateX(41vw) translateY(6vh) scale(0.95);
  }
  55.5555555556% {
    transform: translateX(40vw) translateY(4vh) scale(0.76);
  }
  61.1111111111% {
    transform: translateX(-2vw) translateY(-22vh) scale(0.29);
  }
  66.6666666667% {
    transform: translateX(40vw) translateY(-16vh) scale(0.39);
  }
  72.2222222222% {
    transform: translateX(12vw) translateY(-4vh) scale(0.6);
  }
  77.7777777778% {
    transform: translateX(-13vw) translateY(16vh) scale(0.76);
  }
  83.3333333333% {
    transform: translateX(44vw) translateY(8vh) scale(0.5);
  }
  88.8888888889% {
    transform: translateX(3vw) translateY(-45vh) scale(0.84);
  }
  94.4444444444% {
    transform: translateX(-29vw) translateY(16vh) scale(0.72);
  }
  100% {
    transform: translateX(-48vw) translateY(12vh) scale(0.9);
  }
}
.firefly:nth-child(15) {
  animation-name: move15;
}
.firefly:nth-child(15)::before {
  animation-duration: 15s;
}
.firefly:nth-child(15)::after {
  animation-duration: 15s, 8296ms;
  animation-delay: 0ms, 2911ms;
}

@keyframes move15 {
  0% {
    transform: translateX(-16vw) translateY(-23vh) scale(0.67);
  }
  5.8823529412% {
    transform: translateX(47vw) translateY(-44vh) scale(0.53);
  }
  11.7647058824% {
    transform: translateX(20vw) translateY(-39vh) scale(0.26);
  }
  17.6470588235% {
    transform: translateX(-22vw) translateY(-3vh) scale(0.36);
  }
  23.5294117647% {
    transform: translateX(-10vw) translateY(-10vh) scale(0.75);
  }
  29.4117647059% {
    transform: translateX(-46vw) translateY(15vh) scale(0.98);
  }
  35.2941176471% {
    transform: translateX(0vw) translateY(-43vh) scale(0.81);
  }
  41.1764705882% {
    transform: translateX(-43vw) translateY(44vh) scale(0.33);
  }
  47.0588235294% {
    transform: translateX(27vw) translateY(-43vh) scale(0.66);
  }
  52.9411764706% {
    transform: translateX(-23vw) translateY(32vh) scale(0.95);
  }
  58.8235294118% {
    transform: translateX(-8vw) translateY(-41vh) scale(0.93);
  }
  64.7058823529% {
    transform: translateX(25vw) translateY(25vh) scale(0.87);
  }
  70.5882352941% {
    transform: translateX(-44vw) translateY(47vh) scale(0.82);
  }
  76.4705882353% {
    transform: translateX(46vw) translateY(-41vh) scale(0.56);
  }
  82.3529411765% {
    transform: translateX(-46vw) translateY(-9vh) scale(0.53);
  }
  88.2352941176% {
    transform: translateX(37vw) translateY(-29vh) scale(0.85);
  }
  94.1176470588% {
    transform: translateX(36vw) translateY(-24vh) scale(0.65);
  }
  100% {
    transform: translateX(11vw) translateY(3vh) scale(1);
  }
}
@keyframes drift {
  0% {
    transform: rotate(0deg);
  }
  100% {
    transform: rotate(360deg);
  }
}
@keyframes flash {
  0%, 30%, 100% {
    opacity: 0;
    box-shadow: 0 0 0vw 0vw yellow;
  }
  5% {
    opacity: 1;
    box-shadow: 0 0 2vw 0.4vw yellow;
  }
}





.wrapper {
  min-height: 100vh;
  background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 42),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  z-index:-10000000000;
  position: relative;
  -webkit-animation:colors 5s infinite;
  -webkit-animation-duration: 30s; 
}

@-webkit-keyframes colors {  
  0% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 40),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}
  5% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 39),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}
  15% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 32),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}
  35% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 24),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}
  
  50% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 14),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}
  65% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 20),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}
  75% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 28),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}
  85% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 30),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}
  95% { background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 36),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));}

   
}



.kodama2 {
  position:absolute; 
  left:10%;
  bottom:10%;

  align-items: center;
}

.kodama2 .head {
  opacity:.6;
  width: 40px;
  height: 40px;
  background-color: #fff;
  border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
  transform: rotateZ(15deg);
  -webkit-animation: rotation2 8s 5s infinite;
          animation: rotation2 8s 5s infinite;
  box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
}


.kodama2 .eye1 {

opacity:.8;
  position:absolute;
  z-index:94;
  top:40%;
  left:23%;
  height: 20%;
  width: 20%;
  border: 2px solid #112;
   background-image: radial-gradient(#212121 50%, #fff 31%);
  border-radius: 100% 100% 60% 100%;
  box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);

}

.kodama2 .eye2 {

  opacity:.8;
    position:absolute;
    z-index:94;
    top:30%;
    left:63%;
    height: 5%;
    width: 5%;
    border: 2px solid #112;
     background-image: radial-gradient(#212121 50%, #fff 31%);
    border-radius: 100% 100% 60% 100%;
    box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
  
  }

  .kodama2 .mouth {

    opacity:.8;
      position:absolute;
      z-index:94;
      top:70%;
      left:63%;
      height: 5%;
      width: 15%;
      border: 2px solid #112;
       background-image: radial-gradient(#212121 100%, #fff 100%);
      border-radius: 50%;
      box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
    
    }



  .kodama2 .body {
    position:absolute;
    opacity:.1;
    z-index:-1;
    top:50%;
    right:0%;
    height: 205%;
    width: 75%;
    background-image: linear-gradient(transparent,transparent,transparent,rgb(17, 17, 3),transparent);
    border-radius: 0 0 20px 20px;
    box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
  }

  .kodama2 .arm1 {
    position:absolute;
    opacity:.1;
    z-index:30;
    top:70%;
    right:70%;
    height: 105%;
    width: 25%;
    transform: rotateZ(10deg);
    background-image: linear-gradient(transparent,transparent,transparent,rgb(17, 17, 3),transparent);
    border-radius: 0 0 20px 20px;
    box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
  }

  .kodama2 .arm2 {
    position:absolute;
    opacity:.1;
    z-index:30;
    top:70%;
    left:90%;
    height: 105%;
    width: 25%;
    transform: rotateZ(-10deg);
    background-image: linear-gradient(transparent,transparent,transparent,rgb(17, 17, 3),transparent);
    border-radius: 0 0 20px 20px;
    box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
  }

  .kodama3 {
    position:absolute; 
    left:20%;
    bottom:22%;
  
    align-items: center;
  }
  
  .kodama3 .head {
    opacity:.8;
    width: 22px;
    height: 22px;
    background-color: #fff;
    border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
    transform: rotateZ(15deg);
    -webkit-animation: rotation 5s 5s infinite;
            animation: rotation 5s 5s infinite;
    box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
  }
  
  
  .kodama3 .eye1 {
  
  opacity:.6;
    position:absolute;
    z-index:94;
    top:40%;
    left:23%;
    height: 20%;
    width: 20%;
    border: 2px solid #112;
     background-image: radial-gradient(#212121 50%, #fff 31%);
    border-radius: 100% 100% 60% 100%;
    box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
  
  }
  
  .kodama3 .eye2 {
  
    opacity:.6;
      position:absolute;
      z-index:94;
      top:30%;
      left:63%;
      height: 5%;
      width: 5%;
      border: 2px solid #112;
       background-image: radial-gradient(#212121 50%, #fff 31%);
      border-radius: 100% 100% 60% 100%;
      box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
    
    }
  
  
  
    .kodama3 .body {
      position:absolute;
      opacity:.1;
      z-index:-1;
      top:50%;
      right:0%;
      height: 205%;
      width: 75%;
      background-image: linear-gradient(transparent,transparent,transparent,rgb(17, 17, 3),transparent);
      border-radius: 0 0 20px 20px;
      box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
    }
  
    .kodama3 .arm1 {
      position:absolute;
      opacity:.1;
      z-index:30;
      top:70%;
      right:70%;
      height: 105%;
      width: 25%;
      transform: rotateZ(10deg);
      background-image: linear-gradient(transparent,transparent,transparent,rgb(17, 17, 3),transparent);
      border-radius: 0 0 20px 20px;
      box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
    }
  
    .kodama3 .arm2 {
      position:absolute;
      opacity:.1;
      z-index:30;
      top:70%;
      left:90%;
      height: 105%;
      width: 25%;
      transform: rotateZ(-10deg);
      background-image: linear-gradient(transparent,transparent,transparent,rgb(17, 17, 3),transparent);
      border-radius: 0 0 20px 20px;
      box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
    }

    .kodama4 {
      position:absolute; 
      left:30%;
      bottom:22%;
    
      align-items: center;
    }
    
    .kodama4 .head {
      opacity:.8;
      width: 18px;
      height: 18px;
      background-color: #fff;
      border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
      transform: rotateZ(15deg);
      -webkit-animation: rotation2 4s 2s infinite;
              animation: rotation2 4s 2s infinite;
      box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
    }
    
    
    .kodama4 .eye1 {
    
    opacity:.6;
      position:absolute;
      z-index:94;
      top:40%;
      left:23%;
      height: 20%;
      width: 20%;
      border: 2px solid #112;
       background-image: radial-gradient(#212121 50%, #fff 31%);
      border-radius: 100% 100% 60% 100%;
      box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
    
    }
    
    .kodama4 .eye2 {
    
      opacity:.6;
        position:absolute;
        z-index:94;
        top:30%;
        left:63%;
        height: 5%;
        width: 5%;
        border: 2px solid #112;
         background-image: radial-gradient(#212121 50%, #fff 31%);
        border-radius: 100% 100% 60% 100%;
        box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
      
      }
    
    
    
      .kodama4 .body {
        position:absolute;
        opacity:.1;
        z-index:-1;
        top:50%;
        right:0%;
        height: 205%;
        width: 75%;
        background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
        border-radius: 0 0 20px 20px;
        box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
      }
    
      .kodama4 .arm1 {
        position:absolute;
        opacity:.2;
        z-index:30;
        top:70%;
        right:60%;
        height: 105%;
        width: 25%;
        transform: rotateZ(10deg);
        background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
        border-radius: 0 0 20px 20px;
        box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
      }
    
      .kodama4 .arm2 {
        position:absolute;
        opacity:.2;
        z-index:30;
        top:70%;
        left:80%;
        height: 105%;
        width: 25%;
        transform: rotateZ(-10deg);
        background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
        border-radius: 0 0 20px 20px;
        box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
      }


      .kodama5 {
        position:absolute; 
        left:40%;
        bottom:20%;
      
        align-items: center;
      }
      
      .kodama5 .head {
        opacity:.7;
        width: 11px;
        height: 11px;
        background-color: #fff;
        border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
        transform: rotateZ(15deg);
        -webkit-animation: rotation2 4s 2s infinite;
                animation: rotation2 4s 2s infinite;
        box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
      }
      
      
      .kodama5 .eye1 {
      
      opacity:.8;
        position:absolute;
        z-index:94;
        top:40%;
        left:23%;
        height: 20%;
        width: 20%;
        border: 2px solid #112;
         background-image: radial-gradient(#212121 50%, #fff 31%);
        border-radius: 100% 100% 60% 100%;
        box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
      
      }
      
      .kodama5 .eye2 {
      
        opacity:.8;
          position:absolute;
          z-index:94;
          top:30%;
          left:63%;
          height: 5%;
          width: 5%;
          border: 2px solid #112;
           background-image: radial-gradient(#212121 50%, #fff 31%);
          border-radius: 100% 100% 60% 100%;
          box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
        
        }
      
        .kodama5 .mouth {
      
          opacity:.8;
            position:absolute;
            z-index:94;
            top:70%;
            left:63%;
            height: 5%;
            width: 15%;
            border: 2px solid #112;
             background-image: radial-gradient(#212121 100%, #fff 100%);
            border-radius: 50%;
            box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
          
          }
      
      
      
        .kodama5 .body {
          position:absolute;
          opacity:.1;
          z-index:-1;
          top:50%;
          right:0%;
          height: 205%;
          width: 75%;
          background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
          border-radius: 0 0 20px 20px;
          box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
        }
      
        .kodama5 .arm1 {
          position:absolute;
          opacity:.1;
          z-index:30;
          top:70%;
          right:60%;
          height: 105%;
          width: 25%;
          transform: rotateZ(10deg);
          background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
          border-radius: 0 0 20px 20px;
          box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
        }
      
        .kodama5 .arm2 {
          position:absolute;
          opacity:.1;
          z-index:30;
          top:70%;
          left:80%;
          height: 105%;
          width: 25%;
          transform: rotateZ(-10deg);
          background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
          border-radius: 0 0 20px 20px;
          box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
        }
      
        .kodama6 {
          position:absolute; 
          right:40%;
          bottom:20%;
        
          align-items: center;
        }
        
        .kodama6 .head {
          opacity:.5;
          width: 15px;
          height: 15px;
          background-color: #fff;
          border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
          transform: rotateZ(15deg);
          -webkit-animation: rotation2 4s 2s infinite;
                  animation: rotation2 4s 2s infinite;
          box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
        }
        
        
        .kodama6 .eye1 {
        
        opacity:.8;
          position:absolute;
          z-index:94;
          top:40%;
          left:23%;
          height: 20%;
          width: 20%;
          border: 2px solid #112;
           background-image: radial-gradient(#212121 50%, #fff 31%);
          border-radius: 100% 100% 60% 100%;
          box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
        
        }
        
        .kodama6 .eye2 {
        
          opacity:.8;
            position:absolute;
            z-index:94;
            top:30%;
            left:63%;
            height: 5%;
            width: 5%;
            border: 2px solid #112;
             background-image: radial-gradient(#212121 50%, #fff 31%);
            border-radius: 100% 100% 60% 100%;
            box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
          
          }
        
          .kodama6 .mouth {
        
            opacity:.8;
              position:absolute;
              z-index:94;
              top:70%;
              left:63%;
              height: 5%;
              width: 15%;
              border: 2px solid #112;
               background-image: radial-gradient(#212121 100%, #fff 100%);
              border-radius: 50%;
              box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
            
            }
        
        
        
          .kodama6 .body {
            position:absolute;
            opacity:.1;
            z-index:-1;
            top:50%;
            right:0%;
            height: 205%;
            width: 75%;
            background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
            border-radius: 0 0 20px 20px;
            box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
          }
        
          .kodama6 .arm1 {
            position:absolute;
            opacity:.1;
            z-index:30;
            top:70%;
            right:60%;
            height: 105%;
            width: 25%;
            transform: rotateZ(10deg);
            background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
            border-radius: 0 0 20px 20px;
            box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
          }
        
          .kodama6 .arm2 {
            position:absolute;
            opacity:.1;
            z-index:30;
            top:70%;
            left:80%;
            height: 105%;
            width: 25%;
            transform: rotateZ(-10deg);
            background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
            border-radius: 0 0 20px 20px;
            box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
          }


          .kodama7 {
            position:absolute; 
            right:25%;
            bottom:27%;
          
            align-items: center;
          }
          
          .kodama7 .head {
            opacity:.5;
            width: 15px;
            height: 15px;
            background-color: #fff;
            border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
            transform: rotateZ(15deg);
            -webkit-animation: rotation 4s 2s infinite;
                    animation: rotation 4s 2s infinite;
            box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
          }
          
          
          .kodama7 .eye1 {
          
          opacity:.8;
            position:absolute;
            z-index:94;
            top:40%;
            left:23%;
            height: 20%;
            width: 20%;
            border: 2px solid #112;
             background-image: radial-gradient(#212121 50%, #fff 31%);
            border-radius: 100% 100% 60% 100%;
            box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
          
          }
          
          .kodama7 .eye2 {
          
            opacity:.8;
              position:absolute;
              z-index:94;
              top:30%;
              left:63%;
              height: 5%;
              width: 5%;
              border: 2px solid #112;
               background-image: radial-gradient(#212121 50%, #fff 31%);
              border-radius: 100% 100% 60% 100%;
              box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
            
            }
          
            .kodama7 .mouth {
          
              opacity:.8;
                position:absolute;
                z-index:94;
                top:70%;
                left:63%;
                height: 5%;
                width: 15%;
                border: 2px solid #112;
                 background-image: radial-gradient(#212121 100%, #fff 100%);
                border-radius: 50%;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
              
              }
          
          
          
            .kodama7 .body {
              position:absolute;
              opacity:.1;
              z-index:-1;
              top:50%;
              right:0%;
              height: 205%;
              width: 75%;
              background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
              border-radius: 0 0 20px 20px;
              box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
            }
          
            .kodama7 .arm1 {
              position:absolute;
              opacity:.1;
              z-index:30;
              top:70%;
              right:60%;
              height: 105%;
              width: 25%;
              transform: rotateZ(10deg);
              background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
              border-radius: 0 0 20px 20px;
              box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
            }
          
            .kodama7 .arm2 {
              position:absolute;
              opacity:.1;
              z-index:30;
              top:70%;
              left:80%;
              height: 105%;
              width: 25%;
              transform: rotateZ(-10deg);
              background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
              border-radius: 0 0 20px 20px;
              box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
            }
          
            .kodama8 {
              position:absolute; 
              right:10%;
              top:7%;
            
              align-items: center;
            }
            
            .kodama8 .head {
              opacity:.5;
              width: 10px;
              height: 10px;
              background-color: #fff;
              border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
              transform: rotateZ(15deg);
              -webkit-animation: rotation 4s 2s infinite;
                      animation: rotation 4s 2s infinite;
              box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
            }
            
            
            .kodama8 .eye1 {
            
            opacity:.7;
              position:absolute;
              z-index:94;
              top:40%;
              left:23%;
              height: 4%;
              width: 4%;
              border: 2px solid #112;
               background-image: radial-gradient(#212121 50%, #fff 31%);
              border-radius: 100% 100% 60% 100%;
              box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
            
            }
            
            .kodama8 .eye2 {
            
              opacity:.7;
                position:absolute;
                z-index:94;
                top:30%;
                left:63%;
                height: 4%;
                width: 4%;
                border: 2px solid #112;
                 background-image: radial-gradient(#212121 50%, #fff 31%);
                border-radius: 100% 100% 60% 100%;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
              
              }
            
       
              .kodama8 .body {
                position:absolute;
                opacity:.1;
                z-index:-1;
                top:50%;
                right:0%;
                height: 205%;
                width: 75%;
                background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
                border-radius: 0 0 20px 20px;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
              }
            
              .kodama8 .arm1 {
                position:absolute;
                opacity:.1;
                z-index:30;
                top:70%;
                right:60%;
                height: 105%;
                width: 25%;
                transform: rotateZ(10deg);
                background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
                border-radius: 0 0 20px 20px;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
              }
            
              .kodama8 .arm2 {
                position:absolute;
                opacity:.1;
                z-index:30;
                top:70%;
                left:80%;
                height: 105%;
                width: 25%;
                transform: rotateZ(-10deg);
                background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
                border-radius: 0 0 20px 20px;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
              }
            
              .kodama9 {
                position:absolute; 
                left:10%;
                top:7%;
              
                align-items: center;
              }
              
              .kodama9 .head {
                opacity:.7;
                width: 5px;
                height: 5px;
                background-color: #fff;
                border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
                transform: rotateZ(15deg);
                -webkit-animation: rotation 4s 2s infinite;
                        animation: rotation 4s 2s infinite;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
              }
              .kodama9 {
                position:absolute; 
                left:65%;
                top:7%;
              
                align-items: center;
              }
              
              .kodama9 .head {
                opacity:.7;
                width: 10px;
                height: 10px;
                background-color: #fff;
                border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
                transform: rotateZ(15deg);
                -webkit-animation: rotation 4s 2s infinite;
                        animation: rotation 4s 2s infinite;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
              }
              .kodama9 .body {
                position:absolute;
                opacity:.1;
                z-index:-1;
                top:50%;
                right:0%;
                height: 205%;
                width: 75%;
                background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
                border-radius: 0 0 20px 20px;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
              }

              .kodama10 {
                position:absolute; 
                left:60%;
                top:7%;
              
                align-items: center;
              }
              
              .kodama10 .head {
                opacity:.7;
                width: 5px;
                height: 5px;
                background-color: #fff;
                border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
                transform: rotateZ(15deg);
                -webkit-animation: rotation 4s 2s infinite;
                        animation: rotation 4s 2s infinite;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
              }

              .kodama10 .body {
                position:absolute;
                opacity:.1;
                z-index:-1;
                top:50%;
                right:0%;
                height: 205%;
                width: 75%;
                background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
                border-radius: 0 0 20px 20px;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
              }

              .kodama11 {
                position:absolute; 
                left:70%;
                top:5%;
              
                align-items: center;
              }
              
              .kodama11 .head {
                opacity:.7;
                width: 7px;
                height: 7px;
                background-color: #fff;
                border-radius: 100% 50% 40% 70% / 80% 50% 60% 50%;
                transform: rotateZ(15deg);
                -webkit-animation: rotation 4s 2s infinite;
                        animation: rotation 4s 2s infinite;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.6);
              }

              .kodama11 .body {
                position:absolute;
                opacity:.1;
                z-index:-1;
                top:50%;
                right:0%;
                height: 205%;
                width: 75%;
                background-image: linear-gradient(rgb(250,250,250),rgb(17, 17, 13));
                border-radius: 0 0 20px 20px;
                box-shadow: 0 0 65px 10px rgba(250, 250, 250, 0.4);
              }

            
              .moon

              {
                position:absolute;
         
                opacity:.3;
                z-index:-1;
                top:-10%;
                left:-5%;
                height: min(40vw,60vh);
                width: min(40vw,60vh);
                 background-image: linear-gradient(to bottom right, transparent,rgb(200, 255, 255),rgb(200, 255, 255),rgb(17, 0, 0));
                border-radius: 50%;
                box-shadow: 0 0 5px 10px rgb(0, 51, 34,.2);
                  -webkit-animation:moonshadow 5s infinite;
                  -webkit-animation-duration: 30s; 
                 }

@-webkit-keyframes moonshadow {  
  
  5% { opacity:.2;}
  15% { opacity:.3;}
  40% { opacity:.4;}
  50% { opacity:.5;}
  
  60% { opacity:.6;}
  70% { opacity:.5;}
  90% { opacity:.4;}
  100% { opacity:.3;}
    
}

@media screen and (max-width : 900px) {
  
   .moon

              {
                position:absolute;
         
                opacity:.3;
                z-index:-1;
                top:-10%;
                left:-5%;
                height: 170px;
                width: 170px;
                background-image: linear-gradient(to bottom right, transparent,rgb(200, 255, 255),rgb(200, 255, 255),rgb(17, 0, 0));
                border-radius: 50%;
                box-shadow: 0 0 5px 10px rgb(0, 51, 34,.2);
                 -webkit-animation:moonshadow 5s infinite;
                  -webkit-animation-duration: 30s; 
              }
  
}

@media screen and (max-width : 400px) {
  
   .moon

              {
                position:absolute;
         
                opacity:.3;
                z-index:-1;
                top:-10%;
                left:-5%;
                height: .1*window.innerWidth;
                width: .1*window.innerWidth;
                 background-image: linear-gradient(to bottom right, transparent,rgb(200, 255, 255),rgb(200, 255, 255),rgb(17, 0, 0));
                border-radius: 50%;
                box-shadow: 0 0 5px 10px rgb(0, 51, 34,.2);
                 -webkit-animation:moonshadow 5s infinite;
                  -webkit-animation-duration: 30s; 
              }
  
}

@media screen and (max-height : 350px) {
  
   .moon

              {
                position:absolute;
         
                opacity:.3;
                z-index:-1;
                top:-10%;
                left:-5%;
                height: 200px;
                width: 200px;
                 background-image: linear-gradient(to bottom right, transparent,rgb(200, 255, 255),rgb(200, 255, 255),rgb(17, 0, 0));
                border-radius: 50%;
                box-shadow: 0 0 5px 10px rgb(0, 51, 34,.2);
                 -webkit-animation:moonshadow 5s infinite;
                  -webkit-animation-duration: 30s; 
              }
  
}

@media screen and (max-height : 250px) {
  
  
  .kodama {transform: scale(0.7);}
  
   .moon

              {
                position:absolute;
         
                opacity:.5;
                z-index:-1;
                top:-10%;
                left:-5%;
                height: 150px;
                width: 150px;
                 background-image: linear-gradient(to bottom right, transparent,rgb(200, 255, 255),rgb(200, 255, 255),rgb(17, 0, 0));
                border-radius: 50%;
                box-shadow: 0 0 5px 10px rgb(0, 51, 34,.2);
                 -webkit-animation:moonshadow 5s infinite;
                 -webkit-animation-duration: 30s; 
              }
  
}

.wrapper2 {
  min-height: 10vh;
  background-image: linear-gradient(rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 42),rgb(17, 17, 13),rgb(17, 17, 13),rgb(17, 17, 13));
  display: flex;
  align-items: center;
  justify-content: center;
  flex-direction: column;
  z-index:-10000000000;
  position: relative;
  -webkit-animation:colors2 0s 1;
  -webkit-animation-duration: 5s; 
}

@-webkit-keyframes colors2 {  
  0% {opacity:.1;}
  20% {opacity:.1;}
  100% { background-image:transparent;}
  
} 



number = 4
function smoke() {
  var b = document.createElement('div')
  var size = (Math.random()*75) + 75
  var skew = Math.random()*50
  b.style.width = size +'px'
  b.style.height = size +'px'
  b.style.filter = 'blur(20px)'
  b.style.transform = Math.random() < .5 ? 'skew('+skew*(-1)+'deg)' : 'skew('+skew+'deg)'
  b.style.borderRadius = '50%'
  b.style.background = 'rgb(230, 255, 255)'
  b.style.opacity = '.1'
  b.style.position = 'absolute'
  b.style.top = '0px'
  b.style.left = Math.random()*(window.innerWidth - 75)-70 + 'px'
  b.style.animationDelay = Math.random()*10 + 's'
  b.style.animationDuration = (Math.random()*30) + 2 + 's'
  document.body.appendChild(b)
}

setTimeout(function() {
  for(var i=0;i<number;i++) { smoke() }
},100)



function toggleText(element, texts, delay) {
  let i = 0;
  
  const work = () => {
    element.innerHTML = texts[i].text;

    setTimeout(work, (texts[i].delay * 3000))

    i = (i < texts.length - 1) ? i + 1 : 0;
  }

  setTimeout(work, (delay * 1000))
}

