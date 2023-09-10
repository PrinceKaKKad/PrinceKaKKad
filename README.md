<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  margin: 0;
  padding: 0;
}

body {
  background: url(https://newevolutiondesigns.com/images/freebies/city-wallpaper-18.jpg);
  background-size: cover;
  font-family: verdana;
}

.bg-cover {
  position: fixed;
  top: 0;
  width: 100%;
  height: 100%;
  background: rgba(0, 0, 255, 0.2);
  z-index: -1;
}

.container {
  width: 400px;
  height: 500px;
  background-color: #f9690E;
  margin: 50px auto;
  border-radius: 12px;
  overflow: hidden;
}

.header i{
  font-size: 20px;
  color: rgba(255,255,255,0.7);
  padding: 10px;
  margin-top:20px;
}

.fa-bars{
  float: left;
  margin-left:20px;
}

.fa-bars:hover{
  cursor: pointer;
  animation: bars 0.3s ease-in forwards;
}

.fa-cog{
  float: right;
  margin-right:20px;
}

.fa-cog:hover{
  cursor: pointer;
  animation: rotate 1s ease-in infinite;
}

div.middle{
  position:relative;
  text-align: center;
  top: 70px;
}

img.user-pic{
  width:110px;
  height: 110px;
  border-radius: 100%;
  background: rgba(255,255,255,0.7);
  border: 5px solid rgba(255,255,255,1);
}

h4.name{
  font-size: 18px;
  color: rgba(255,255,255,0.8);
  padding: 10px;
}

h4.work{
  font-size: 14px;
  color: rgba(255,255,255,0.5);
  padding: 10px;
  padding-top: 0px;
}

h4.social{
  font-size: 15px;
  color: rgba(255,255,255,0.5);
  padding: 15px;
}

div.footer{
  position: relative;
  background: rgba(255,255,255,1);
  top:110px;
  height:180px;
  text-align: center;
}

.btn-follow
{
  position: relative;
  padding: 15px 70px;
  top: -22px;
  background: rgba(255,255,255,1);
  border: none;
  border-radius: 20px;
  text-transform: uppercase;
  letter-spacing: 1px;
  color: #f9690E;
  box-shadow: 0px 5px 45px rgba(249,105,14,0.4);
  border: 1px solid transparent;
  transition: all 0.5s ease-in;
}

.btn-follow:hover
{
  cursor: pointer;
  border: 1px solid rgba(255,255,255,0.2);
  background: #f9690E;
  color: rgba(255,255,255,1);
}

.fa-lock{
  font-size: 20px;
  color: rgba(0,0,0,0.2);
  padding-top:15px;
}

.profile-status{
  font-size: 12px;
  color: rgba(0,0,0,0.2);
  padding-top: 7px;
}

@keyframes rotate{
  0%{
    transform: rotate(0deg);
  }
  100%{
    transform: rotate(180deg);
  }
}

@keyframes bars{
  0%{
    transform: rotate(0deg);
  }
  100%{
    transform: rotate(90deg);
  }
}

@keyframes img3d{
  0%{
    transform: rotateY(0deg);
  }
  100%{
    transform: rotateY(55deg);
  }
}

 transform-origin: left top;
 animation: swing 2s ease-in forwards;
}


@-moz-keyframes swing {
  0% {
    -moz-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -moz-transform: rotate(45deg);
    transform: rotate(45deg);
  }
}
@-webkit-keyframes swing {
  0% {
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg);
  }
}
@keyframes swing {
  0% {
    -moz-transform: rotate(0deg);
    -ms-transform: rotate(0deg);
    -webkit-transform: rotate(0deg);
    transform: rotate(0deg);
  }
  100% {
    -moz-transform: rotate(45deg);
    -ms-transform: rotate(45deg);
    -webkit-transform: rotate(45deg);
    transform: rotate(45deg);
  }
}
	</style>
</head>
<body>
<div class="bg-cover"></div>
<div class="container">
  <div class="header">
    <i class="fa fa-bars"></i>
    <i class="fa fa-cog"></i>
  </div>
  <div class="middle">
    <img src="http://www.tomatinatrip.com/wp-content/uploads/2015/07/Picture-of-person.png" alt="" class="user-pic" />
    <h4 class="name">Steve Regan</h4>
    <h4 class="work">ASP.net | HTML | CSS</h4>
    <h4 class="social"><i class="fa fa-facebook"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <i class="fa fa-dribbble"></i>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <i class="fa fa-twitter"></i></h4>
  </div>
  <div class="footer">
   <button class="btn-follow">follow </button><br/>
    <i class="fa fa-lock"></i>
    <br/>
    <h4 class="profile-status">This profile is hidden</h4>
  </div>
</div>
</body>
</html>
