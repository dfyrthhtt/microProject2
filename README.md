<!DOCTYPE html>
<html lang="en">
<head>
    <title>Micro Project</title>
  <style>
    *{
    padding: 0;
    margin: 0;
    text-decoration: none;
    list-style: none;
    box-sizing: border-box;
}
body{
    font-family: monospace;
}
nav{
    background-color: #6F6AF7;
    height: 100%;
    width: 100%;
    overflow-x: hidden;
}
label.logo{
    color: white;
    font-size: 35px;
    line-height:80px ;
    padding: 0 100px;
    font-weight: bold;
}
nav ul{
    float:right ;
    margin-right: 20px;
}
nav ul li{
    display:inline-block;
    line-height: 70px;
    margin:0 5px;
    padding: 0 50px;
    
}
nav ul li a{
    color: white;
    font-size: 18px;
}
#imge{
 text-align: justify;
}
.Search{
    /* width: 10px; */
    height: 50px;
    background-color: white;
    display: flex;
    align-items: center;
    border-radius: 63px;
    padding: 10px 20px;
    backdrop-filter: blur(24.43px) saturation(180%);
}
.Search input{
    background: transparent;
    flex: 1;
    border: 0;
    outline: none;
    padding: 0px 0px;
    color: gray;
    /* font-size: 5px; */

}
::placeholder
{
    color: gray;
}
.Search button img{
    width: 10px;
}
.Search button{
    border: 0;
    border-radius: 50%;
    width: 10px;
    height:10px ;
    background:white;
    cursor: pointer;
}
#text{
    width: 119px;
height: 23px;
flex-shrink: 0;
color: #9F9F9F;
font-size: 24.43px;
font-style: normal;
font-weight: 400;
line-height: normal;
}

.box2{
    padding: 10px 10px 10px 10px;
    height: 500px;
    width: 600px;
    font-family: 'Lucida Sans Unicode';
    box-shadow: 0px 9px 31px 0px rgba(0, 0, 0, 0.40);
    border: 1px solid black;
    border-radius: 20px;
    background-color: #E5D8FF;
    display: flex;
    flex-direction: row;
}
.middle_part{
    display: flex;
    flex-direction: row;
    justify-content: center;
    justify-content: space-around;
    padding: 40px 40px ;
}
.img1{
    box-shadow: 0px 9px 31px 0px rgba(0, 0, 0, 0.5);
     height: 500px;
     width: 370px;
}
.image1{
    height: 400px;
    width: 400px;
    box-shadow: 20px 50px 31px 0px rgba(0, 0, 0, 0.40);
}
.Question{
    width: 200px;
height: 70px;
margin: 10px 15px;
flex-shrink: 0;
border-radius: 11px;
padding: 10px 10px;
background: #b0b7f6;
color: white;
box-shadow: 0px 9px 31px 0px rgba(0, 0, 0, 0.40);
}
.Answer{
    width: 200px;
height: 70px;
margin: 10px 15px;
flex-shrink: 0;
border-radius: 11px;
padding: 10px 10px;
background:#532bd5;
color: white;
box-shadow: 0px 9px 31px 0px rgba(0, 0, 0, 0.40);
}
.Participated{
    color: white;
    width: 200px;
height: 70px;
margin: 10px 15px;
flex-shrink: 0;
border-radius: 11px;
padding: 10px 10px;
background:#D288FF;
box-shadow: 0px 9px 31px 0px rgba(0, 0, 0, 0.40);
}
.Pass{
    color: white;
    width: 200px;
height: 70px;
margin: 10px 15px;
flex-shrink: 0;
border-radius: 11px;
padding: 10px 10px;
background:black;
box-shadow: 0px 9px 31px 0px rgba(0, 0, 0, 0.40);
}
.boxes{
    display: flex;
    flex-direction: row;
    justify-content: center;
    justify-content: space-around;
    padding: 40px 40px ;
}
.what{
    padding: 0px 0px 20px 0px;
    width: 75px;
height: 75px;
flex-shrink: 0;
position: fixed;
border-radius: 11px;
border: 3px solid #000;
background: #FFF;
}
.face{
    position: fixed;
    padding: 100px 0px 100px 0px;
    width: 40px;
height: 68.612px;
flex-shrink: 0;
}
.twitter{
    position: fixed;
    padding: 200px 0px 200px 0px;
    width: 40px;
height: 68.612px;
flex-shrink: 0;
}
.social{
    display: flex;
width: 88px;
height: 261px;
padding-left: 0px;

flex-direction: column;
justify-content:center;
align-items: center;
}

#help{
    display: flex;
justify-content:start;
align-items:end;
padding: 80px 0px 0px 885px;
    width: 0%;
height: 0%;
flex-shrink: 0;
    position: fixed;
}
#boxes{
    display: flex;
    justify-content: center;
    padding: 0 40px 0 40px;
}
#big_box{
    padding: 20px 20px;
    width: 1400px;
height: 550px;
flex-shrink: 0;
    border-radius: 21px;
background: #483EFF;
}
#yourInfo{
    border-radius: 22px;
background: #BCE0F6;
box-shadow: 0px 6px 35px 0px rgba(0, 0, 0, 0.39);
width: 397px;
height: 133px;
flex-shrink: 0;
padding: 50px 50px 50px 150px;
}
#yourInfoText{
    width: 20px;
height: 23px;
flex-shrink: 0;
color: #000;
font-family: sans-serif;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 178.7%; /* 62.545px */
letter-spacing: 1.4px;
}
#BookMarks{
    border-radius: 22px;
background:#483EFF;
box-shadow: 0px 6px 35px 0px rgba(0, 0, 0, 0.39);
width: 397px;
height: 133px;
flex-shrink: 0;
padding: 50px 50px 50px 150px;
margin-top: 30px;
border:2px solid white;
}
#BookMarksText{
    width: 20px;
height: 23px;
flex-shrink: 0;
color:white;
font-family: sans-serif;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 178.7%; /* 62.545px */
letter-spacing: 1.4px;
}
#Settting{
    border-radius: 22px;
background:#483EFF;
box-shadow: 0px 6px 35px 0px rgba(0, 0, 0, 0.39);
width: 397px;
height: 133px;
flex-shrink: 0;
padding: 50px 50px 50px 150px;
margin-top: 30px;
border:2px solid white;
}
#SetttingText{
    width: 20px;
height: 23px;
flex-shrink: 0;
color:white;
font-family: sans-serif;
font-size: 20px;
font-style: normal;
font-weight: 700;
line-height: 178.7%; /* 62.545px */
letter-spacing: 1.4px;
}
#whiteBox{
    display: flex;
    align-items: left;
    justify-content: left;
    margin: -450px 600px;
    padding: 20px 20px 20px 20px;
    width: 750px;
height: 500px;
flex-shrink: 0;
border-radius: 19px;
background: #FFF;
}
#yourInfoText1{
    padding: 10px 50px 50px 10px;
    width: 370px;
height: 36px;
flex-shrink: 0;
color: #04285A;
font-family: Inter;
font-size: 38px;
font-style: normal;
font-weight: 700;
line-height: normal;
letter-spacing: 3.99px;
}
#info{
    line-height: 1.8;
    padding: 100px 20px 10px 100px;
    width: 153px;
height: 22px;
flex-shrink: 0;
color: #143565;
font-family: Roboto;
font-size: 24px;
font-style: normal;
font-weight: 400;
line-height: normal;
letter-spacing: 1.2px;
}
#next{
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    border-radius: 22px;
background:black;
width: 1px;
height: 1px;
flex-shrink: 0;
padding: 50px 75px;
margin-top: 200px;
margin-left: 520px;
border:2px solid black;
}
#next1{
    width: 67px;
height: 28px;
flex-shrink: 0;
color: #FFF;
font-family: Roboto;
font-size: 30px;
font-style: normal;
font-weight: 400;
line-height: normal;
letter-spacing: 1.5px;
}

    </style>
</head>
<body>
  <nav>
    <label class="logo">Dappr</label>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About Us</a></li>
      <li><a href="#">Information</a></li>
      <li><a href="#">More</a><img src="Vector.svg" alt=""></li>
      <li> <form action="" class="Search">
        <div class="inside"><input type="search" name="Search" id="Search" placeholder="search">
       <button><img src="search.svg"></button></form></div></li>
      <li style="height: 20px;width: 20px; padding: 10px 50px;"><img src="Vector1.svg"></li>
    </ul>
  </nav>
  <ul>

  </ul>
   <ul class="middle_part">
    <li class="img1">
      <img src="image 4.png">
    </li> 
    <li>
   <div class="box2">It's not only writers who can benefit from this free online tool. If
      you're a programmer who's working on a ......</div></li>
      <ul class="social">
        <div> 
          <div class="what">  <li><img src="logos_whatsapp-icon.svg"></li> </div>
        <li class="face"><img src="facebook.svg"></li>
        <li class="twitter"><img src="twitter.svg"></li>
        </div>
      </ul>
   </ul>
  <ul class="boxes">
    <div class="Question">
      Total Question’s <br>
      200,000
    </div>
    <div class="Answer">
      Total Answer’s <br>
      105,000
    </div>
    <div class="Participated">
      Participated <br>
      10,000
    </div>
    <div class="Pass">
      Total Passed <br>
      6,000
    </div>
    <div id="help">
      <img  src="help.svg" >
    </div>
  </ul>
  <div id="boxes">
  <div id="big_box">
    <div id="yourInfo">
      <span id="yourInfoText">YOUR INFO</span>
      </div>
      <div id="BookMarks">
        <span id="BookMarksText">YOUR INFO</span>
        </div>
        <div id="Settting">
          <span id="SetttingText">YOUR INFO</span>
          </div>
          <div id="whiteBox">
            <ul>
              <li><span id="yourInfoText1">Your information</span></li>
              <li><span id="info"><b> Name:</b> Atul Singhal</span></li>
              <li><span id="info"><b>Email: </b> atul@gmail.com</span></li>
              <li><span id="info"> <b>Phone:</b> +91 8131424888</span></li>
              <li> <span id="info"> <b>Marks: </b>500.00</span></li>
            <li> <div id="next">
              <span id="next1">Next</span>
              <img src="Arrow 1.svg" >
            </div></li>
            </ul>
            </div>
    </div>
  </div>
</body>
</html>
