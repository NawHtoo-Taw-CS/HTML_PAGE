<!DOCTYPE html>
<html>
<head>
<title>PingPong</title>
  </head>
    <style>
    .aa {
      margin: 0px 0px 0px 683px;
    }
    .bb {
      margin: -525px 0px 0px 725px;
    }
    .cc {
      margin: -129px 0px 0px 0px;
    }
    .dd {
      margin:  -208px 0px 0px 900px;
    }
    .ee {
      margin:  -208px 0px 0px 900px;
    }
ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    overflow: hidden;
    background-color: #333;
}
li {
    float: left;
}
li a {
    display: block;
    color: white;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
}
li a:hover {
    background-color: #111;
}
</style>
</head>
<script type=text/javascript>
var links = document.getElementsByTagName("a");
var len = links.length
for(var i=0; i<len; i++)
{
	links[i].target += "_blank";
}
</script>
<body>
<body background="grey2.jpg">
<ul>
  <li><a class="active" href="PingPong.html">Home</a></li>
</ul>
<div class="container-fluid">
  <div class="aa"><h1><font color="white">Home</font></h1></div>
  <h4>
  <H2><font color="white">T.G.R</font></H2>
      <body>
   <img src="grey2.jpg" alt="Destiny 2" style="width:700px;height:500px;">
   </body
     <font color="white">
       <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
       <script>
       $(document).ready(function(){
           $("h2").click(function(){
               $(this).hide();
           });
       });
       </script>
       </head>
       <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
       <script>
       $(document).ready(function(){
           $("h1").click(function(){
               $(this).hide();
           });
       });
       </script>
       </head>
       <body>
       <div class="bb">
       <h2><font color="white">Best Ping Pong Game In The World</h2>
</font>
</div>
      </body>
    <body>
            <div class="cc">
    <img id="myImage" src="games.jpg" style="width:700px;height:500px">
     <button onclick="document.getElementById('myImage').src='games.jpg'">Picture #1</button>
     <button onclick="document.getElementById('myImage').src='games2.jpg'">Picture #2</button>
            </div>
         <div class="dd">
  <button onclick="document.getElementById('myImage2').src='games4.gif'">Click Me</button>
  <button onclick="document.getElementById('myImage2').src='grey2.jpg'">Click Me</button>
  <img id="myImage2" src="grey2.jpg" style="width:400px;height:200px">
        </div>
   </body>
</html>
