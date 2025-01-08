<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
    <style> 
    body {
  margin: 0;
  overflow: hidden;
  display: flex;
}

.octocat {
  height: 79px;
  width: 55px;
  background: url(https://raw.githubusercontent.com/codypearce/codepen-files/main/pens/octocat/octocat.png) left center;
  animation: animateSprite 15s steps(1) infinite, swim 15s ease-in-out infinite ;
  position: absolute;
  background-size: 200px;
  right: 9px;
  top: 1%;
  margin-top: -150px;
  z-index: 100;
}

.one--1{
  position: absolute;
  right: 50px;
}

.one--3{
  position: absolute;
  left: 50px;
}

.one--4{
  position: absolute;
  left: 5px;
}




@keyframes animateSprite{
0%{
  background-position: 0%;
}
10%{
  background-position: -46px;
}

20%{
  background-position: 0%;
}

30% {
  background-position: -46px;
}

40%{
  background-position: 0%;
}
50%{
  background-position: -46px;
}

60%{
  background-position: 0%;
}

70% {
  background-position: -46px;
}

80%{
  background-position: 0%;
}
100%{
  background-position: -46px;
}

}

@keyframes swim{

  0%{
    transform: translateY(110vh);
  }

  25%{
    transform: translateY(60vh);
  }

  50%{
    transform: translateY(40vh);
  }

  75%{
    transform: translateY(20vh);
  }

  100%{
    transform: translateY(0vh);
  }

}


.ocean {
  position: relative;
  width: 100vw;
  height: 100vh;
  background-image: linear-gradient(0deg, #182848, #2980b9)
}

.bubble {
  width: 30px;
  height: 30px;
  border-radius: 100%;
  position: absolute;
  background-color: white;
  bottom: -30px;
  opacity: 0.2;
  animation: bubble 15s ease-in-out infinite,
    sideWays 4s ease-in-out infinite alternate;
}

@keyframes bubble {
  0% {
    transform: translateY(0%);
    opacity: 0.06;
  }
  100% {
    transform: translateY(-120vh);
  }
}

@keyframes sideWays {
  0% {
    margin-left: 0px;
  }
  100% {
    margin-left: 200px;
  }
}

.bubble--1 {
  left: 10%;
  animation-delay: 0.5s;
  animation-duration: 16s;
  opacity: 0.2;
}

.bubble--2 {
  width: 15px;
  height: 15px;
  left: 40%;
  animation-delay: 1s;
  animation-duration: 10s;
  opacity: 0.1;
}

.bubble--3 {
  width: 10px;
  height: 10px;
  left: 30%;
  animation-delay: 5s;
  animation-duration: 20s;
  opacity: 0.3;
}

.bubble--4 {
  width: 25px;
  height: 25px;
  left: 40%;
  animation-delay: 8s;
  animation-duration: 17s;
  opacity: 0.2;
}

.bubble--5 {
  width: 30px;
  height: 30px;
  left: 60%;
  animation-delay: 10s;
  animation-duration: 15s;
  opacity: 0.1;
}

.bubble--6 {
  width: 10px;
  height: 10px;
  left: 80%;
  animation-delay: 3s;
  animation-duration: 30s;
  opacity: 0.4;
}

.bubble--7 {
  width: 15px;
  height: 15px;
  left: 90%;
  animation-delay: -7s;
  animation-duration: 25s;
  opacity: 0.3;
}

.bubble--9 {
  width: 20px;
  height: 20px;
  left: 50%;
  bottom: 30px;
  animation-delay: -5s;
  animation-duration: 19s;
  opacity: 0.2;
}

.bubble--10 {
  width: 40px;
  height: 40px;
  left: 30%;
  bottom: 30px;
  animation-delay: -21s;
  animation-duration: 16s;
  opacity: 0.3;
}

.bubble--11 {
  width: 30px;
  height: 30px;
  left: 60%;
  bottom: 30px;
  animation-delay: -13.75s;
  animation-duration: 20s;
  opacity: 0.3;
}

.bubble--11 {
  width: 25px;
  height: 25px;
  left: 90%;
  bottom: 30px;
  animation-delay: -10.5s;
  animation-duration: 19s;
  opacity: 0.3;
}

.intro {
  display: flex;
  position: absolute;
  z-index: 104;
  flex-wrap: wrap;
}

/* DEMO-SPECIFIC STYLES */
.typewriter h1 {
  color: #fff;
  font-family: monospace;
  overflow: hidden; 
  border-right: .15em solid orange; 
  white-space: nowrap;
  margin: 0 auto; 
  letter-spacing: .15em;
  animation: 
    typing 8.5s steps(30, end) infinite,
    blink-caret .5s step-end infinite;
}

/* The typing effect */
@keyframes typing {
  0% { width: 0 }
  80% { width: 100% }
  100% { width: 100% }
}

/* The typewriter cursor effect */
@keyframes blink-caret {
  from, to { border-color: transparent }
  50% { border-color: orange }
}

.typewriter {
  width: 100vw;
  display: flex;
  justify-content: center;
  padding: 20px;
}
    </style>
</head>
<body>
<div class="ocean">
    <div class="bubble bubble--1"></div>
    <div class="bubble bubble--2"></div>
    <div class="bubble bubble--3"></div>
    <div class="bubble bubble--4"></div>
    <div class="bubble bubble--5"></div>
    <div class="bubble bubble--6"></div>
    <div class="bubble bubble--7"></div>
    <div class="bubble bubble--8"></div>
    <div class="bubble bubble--9"></div>
    <div class="bubble bubble--10"></div>
    <div class="bubble bubble--11"></div>
    <div class="bubble bubble--12"></div>
    <div class="octocat"></div>

    <div class="octocat one--1"></div>
    <div class="octocat one--2"></div>
    <div class="octocat one--3"></div>
    <div class="octocat one--4"></div>
</div>

<div class="intro">

    <div class="typewriter">
        <h1>Hi, My Name is Krishna Nice to Meet you.</h1>
      </div>

</div>

</body>
</html>