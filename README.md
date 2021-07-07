<!DOCTYPE html>
<html>
    <head>
        <title>The woodcutter game</title>
    <!-- made by Yashas the monkey coder(ambassador yashas) -->
    <style>
        <!-- i suck at animation😂 -->
@import url('https://fonts.googleapis.com/css2?family=Work+Sans:wght@543&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Otomanopee+One&display=swap');
body {
    width:280px;
    height:2000px;
}
@keyframes hip {
    0% {
        padding:0px;
        padding-left:0px;
    }
    100% {
        padding-left:50px;
        color:aqua;
    }
}

.back{
    width:350px;
    height:580px;
    
}
.tree{
    width:350px;
    height:450px;
    padding-bottom:10px;
    padding:0px;
    padding-left:5px;
    padding-top:10px;
    
}
.id{
    padding:0px;
    padding-left:116px;
    font-size:20px;
    border:solid #101010 2px;
    border-radius:10px;
    font-style:italic;
    font-family: 'Work Sans', sans-serif;
    letter-spacing:2px;
    
    
}
.id2{
padding:0px;
    padding-left:116px;
    font-size:20px;
    border:solid #101010 2px;
    border-radius:10px;
    font-style:italic ;
    font-family: 'Work Sans', sans-serif;
    letter-spacing:2px;
    
    }
.id3{
    width:350px;
    height:30px;
    background-color:#59f776;
    font-size:20px;
    text-align:center ;
    padding:0px;
    padding-left:0px;
    
}
.buttt{
    width:140px;
    border-color:#3b96eb;
    background-color:#d1d14f;
    border-width:5px;
    border-radius:15px;
    font-weight:3px;
}
.batt{
    width:130px;
    border-width:3px;
    border-color:black;
    border-radius:10px;
    background-color:aqua;
    font-weight:3px;
    
}
.batttt{
    width:335px;
    border-width:5px;
    border-color:#f09984;
    border-radius:21px;
    background-color:#97de33;
    font-weight:3px;
    padding:10px;
    position:center ;
    letter-spacing:2px;
    
    
    
}
@keyframes congo{
    0%{transform:scale(0.7,0.7);}
    15%{transform:scale(0.8,0.8);}
    25%{transform:scale(0.9,0.9);}
    35%{transform:scale(1.0,1.0);}
    50%{transform:scale(1.1,1.1);}
    60%{transform:scale(1.1,1.1);}
    75%{transform:scale(1.1,1.1);}
    85%{transform:scale(1.1,1.1);}
    100%{transform:scale(1.1,1.1);}
}
.diva{
    animation-name:congo;
    animation-duration:3s;
    animation-delay:1s;
    animation-iteration-count:infinite;
}
@keyframes laste{
    0%{padding-bottom:500px;}
    100%{padding-bottom:0px;}
}
.last{
    animation-name:congo;
    animation-duration:15s;
    animation-iteration-count:infinite;
    position:center ;
}
.butt9{
    border:solid green 4px;
    border-spacing:5px;
    border-radius:10px;
    
}
.butt9 h3{
    font-family: 'Work Sans', sans-serif;
    letter-spacing:2px;
    padding-left:50px;
}
.line{
    border:solid black 1px;
}
.line2{
    padding-left:113px;
    
}
.newid{

    width:260px;
    height:63px;
    background-color:#6ec9d4;
    padding-left:100px;
    padding-top:5px;
    font-size:20px;
    font-family: 'Otomanopee One', sans-serif;
    letter-spacing:1.5px;
    border-radius:80px;
    border:solid green 3px;
    color:#29435e;
    }
.conti{
    width:400px;
    height:220px;
    background-color:#29435e;
    letter-spacing:3px;
    font-size:50px;
    border-radius:50px;
    color:white;
}
.ko{
    border:solid black 3px;
    width:50px;
    height:50px;
    background-color:#f09984;
    color:white;
    border-radius:15px;
}
.fir{
    width:100px;
    height:50px;
    padding-bottom:1000px;
    background-color:lime;
    color:white;
}
    </style>
    </head>
    <body>
    
    
    <h5 class="newid">The Woodcutter:<br />       idel game</h5>
    <h3 id="cou" class="id" style="display:true">wood:0</h3>
    <h3 id="cre" class="id2" style="display:true">credits:0</h3>
    <h3 id="wor" class="id2" style="display:true"></h3>
    <button id="butttt" class="buttt" onclick="worker()" style="display:true">2x wood: can only be used once</button>
    
    
    
    <div>
     <img src="https://i.postimg.cc/6psP7d2L/Pngtree-green-tree-2865510.png" class="tree" onclick="wood()" id="imag" style="display:true"> 
         </div>
         <h2 id="sell" class="id3" onclick="pay()" style="display:true">Sell wood for:0$</h2>
         <button id="bat" class="batt" onclick="deal()" style="display:true">Deal a bussiness man</button><br /><br />
         <h3 id="foot2" style="display:true">power ups <br />----------</h3>
       <div class="butt9" id="butt9" style="visibility:visible">  <button id="bat1" class="batttt" onclick="deal1()" style="display:true">Get 2x wood:500$</button><br />
         <button id="bat2" class="batttt" onclick="deal2()" style="display:true">Get 3x wood:700$</button><br />
         <button id="bat3" class="batttt" onclick="deal3()" style="display:true">Get 4x wood:1500$</button>
         
         </div><br /><div id="foot1" style="visibility:visible">
         <p class="line"></p>
         <p class="line2">-----------------------------</p>
         <p class="line"></p>
         <footer id="foot">MADE BY- Yashas monkey coder <br /> Copyright 2021 ©</footer></div>
         <audio controls loop autoplay="true" id="music" hidden="true">
        <source src="https://dl.dropbox.com/s/argiz22fs7mm02f/cali-1171.mp3?dl=0" autoplay="true">
        Your browser does not support audio file
    </audio>
         <button class="conti" id="conti" onclick="counti()" style="visibility:hidden">Continue--></button>
         <div class=""></div>
          
      </body>
      <body>
          <div class="diva" id="anime" style="display:true; visibility:hidden">
              <h4 id="anime1" style="padding:40px"> CONGRAGULATIONS! 🎉 </h4>
              <p id="anime2" style="font-weight:4px">You have completed the game and reached the level of sucsess which is to get 100k credits. please send the screen shot of this screen in a link of any social media platform that you like.I will announce the winners in the next post of solo learn, thanks..did your hand hurt!?</p>
              <button class="ko" id="ko" onclick="okbe()">OK</button>
          </div>
          <div class="last" id="latpa" style="visibility:hidden">
              <h4>THANKS FOR PLAYING!</h4>
              <p>Made by-
                  Yashas monkey coder
                  <br />
                  <br />
                  
                  Sponsered by-
                    honey
                    <br />
                    <br />
                    
                    created with-
                       web
                        <br />
                        <br/>
                        
                     Special guest-
                         Lohith King
                         <br />
                             <br />
                             THE END
                             (MAYBE!?)
                         </p>
          </div>
          
          
          
          
          
          
      </body>
      <script>
      // long code, sorry

alert("welcome to the game The Woodcutter!")
alert("The goal of this game is to sell and make the wood properly to get 100K credits")
alert("INSTRUCTIONS:- 1.Clicking on the tree provides you one wood.    2.using powerups you can get 2x,3x and 4x wood.     3. dealing with a bussiness man provides you 2x credits at once.       4. getting 2x wood will provide you 2x wood at once")
alert("Tap the tree to start the game")
alert("Thats it. Play fair - yashas the monkey coder")
alert("hi lohith!")
var wood1 = 0;
var crefits = 0;
var wood3 = 0;
var wood4 = 0;
var woodd = 0;
var dous = 0;
var sus = 0;
var make = 0;

function wood(){
    wood1+=1;
    document.getElementById("cou").innerHTML="wood:"+wood1
    document.getElementById("sell").innerHTML="Sell  wood for "+wood1/2+" $"
    document.getElementById("wor").innerHTML=""
    document.getElementById("music").play()
    if(dous==1){
        wood1+=1
        document.getElementById("cou").innerHTML="wood:"+wood1
    }
    if(dous==2){
        wood1+=2
        document.getElementById("cou").innerHTML="wood:"+wood1
    }
    if(dous==3){
        wood1+=3
        document.getElementById("cou").innerHTML="wood:"+wood1
        
    }
}    
function pay(){
    crefits+=wood1/2;
    wood3 += wood1/2; document.getElementById("cre").innerHTML="Credits: "+crefits
    wood1-=wood1;
    document.getElementById("cou").innerHTML="wood:"+wood1
    if(crefits > 0){
        var al = alert(crefits+" current balance ✓");
        document.getElementById("sell").innerHTML="Sell  wood for "+wood1/2+" $"
    }
    else{
        alert("please gain some money by cutting trees.. payment cancelled ×")
    }
    if(crefits >= 100000){
       var crefits2 = crefits/1000+'K'
       document.getElementById("cre").innerHTML="Credits: "+crefits2
    }
    if(crefits>=100000){
    alert("working...")
    document.getElementById("cou").style.display="none"
    document.getElementById("cre").style.display="none"
    document.getElementById("wor").style.display="none"
    document.getElementById("butttt").style.display="none"
    document.getElementById("imag").style.display="none"
    document.getElementById("sell").style.display="none"
    document.getElementById("bat").style.display="none"
    document.getElementById("bat1").style.display="none"
    document.getElementById("bat2").style.display="none"
    document.getElementById("bat3").style.display="none"
    document.getElementById("anime").style.display="true"
    document.getElementById("anime").style.display="true"
    document.getElementById("conti").style.visibility="visible"
    document.getElementById("foot1").style.visibility="hidden"
    document.getElementById("foot2").style.display="none"
    document.getElementById("butt9").style.visibility="hidden"
    
}
    

}
function worker(){
    if(crefits >= 200){
        if(wood1>0){
            crefits-=200;
         document.getElementById("cre").innerHTML="Credits: "+crefits
         wood1 = wood1+wood1;
         document.getElementById("cou").innerHTML="wood:"+wood1
         document.getElementById("butttt").style.display="none"
         alert("you have multiplied "+wood1/2+" wood to "+wood1+" wood")
        }
        else{
            alert("you must have more than one wood to multiply ×")
        }
    }
    else{
        alert("you need to have 200$, payment cancelled ×");
    }
}
function deal(){
    if(wood1>=1000){
        crefits+=wood1;
        alert("you have dealed "+wood1+" with the bussiness man and he has gave you "+wood1+" credits")
        document.getElementById("cre").innerHTML="Credits: "+crefits
         wood1-=wood1;
         document.getElementById("cou").innerHTML="wood:"+wood1
         document.getElementById("sell").innerHTML="Sell  wood for "+wood1/2+" $"
         document.getElementById("bat").style.display="none"
    }
    else{
        alert("you need to have atleast 1000 wood to sell the bussiness man");
    }
}
function deal1(){
     if(crefits>=500){
         dous+=1
         crefits-=500
         alert("you have got 2x wood");
         sus+=1
         document.getElementById("cre").innerHTML="Credits:"+crefits
         document.getElementById("bat1").style.display="none"
         
     }
     
     else{
         alert("you need to have 500$ to get 2x wood");
}
}
function deal2(){
    if(crefits>=700){
        if(sus==1){
            dous+=1
            crefits-=700
            sus+=1
            alert("you have got 3x wood")
            document.getElementById("cre").innerHTML="Credits:"+crefits
            document.getElementById("bat2").style.display="none"
            
        }
        else{
            alert("you need to unlock 2x first")
        }
        
    }
    else{
        alert("you need to have 700$ to get 3x wood");
    }
}
function deal3(){
    if(crefits>=1500){
        if(sus==2){
            dous+=1
            crefits-=1500
            alert("you have got 4x wood")
            document.getElementById("cre").innerHTML="Credits:"+crefits
            document.getElementById("bat3").style.display="none"
            document.getElementById("butt9").style.visibility="hidden"
        }
        else{
            alert("you need to unlock 3x wood first")}
        if(sus==1){
            alert("you need to unlock 2x and 3x wood first")
        }
        
        
    }
    else(
        alert("you need to have 1500$ to unlock 4x wood")
    )
}
function counti(){
    document.getElementById("anime").style.display="true"
    document.getElementById("anime").style.visibility="visible"
    document.getElementById("conti").style.visibility="hidden"
}
function okbe(){
    alert("working...")
    document.getElementById("anime").style.display="none"
    document.getElementById("anime").style.visibility="hidden"
    document.getElementById("conti").style.visibility="hidden"
    document.getElementById("latpa").style.visibility="visible"
    

}



</script>
          
