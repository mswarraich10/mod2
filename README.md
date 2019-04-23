<!DOCTYPE html>
<html>
<head>
<title>Our Manue</title>
<style>

 *{
  box-sizing: border-box;
  margin: 0;
  padding: 0;
 }
 body{
  position: relative;;
 }
h1{
  margin-bottom: 50px;
  text-align: center;
  size: 50%;
  color: #6e6e6e;
}
 #containor{
  position: relative;
  padding: 0;
  border: 0;
  margin: 0;
 }
  #p1{

  color: tomato red;
  }
  #p12{
    position: absolute;
    top:0;
    left: 65;
    clear: left;
  }

  #p11{
    float: right
    margin-bottom: 10px;
    top: 0;
    left: 0;
    height: 30px;
    width: 100px;
    background-color: brown;
    border: 2px solid black;
    position: relative;
  }
  #p1{
 //   float: left;
   position: relative;
    padding: 0px 0px 0px 0px;
    background-color: grey;
    border: 2px solid black;
    width: 30%;
    margin: 20px;
    height: 180px;
  }
    #p2{
   // padding: 6px 6px 6px 6px;
    background-color: grey;
    border: 2px solid black;
    width: 30%;
    height: 180px;
    margin: 20px;
    position: relative;
  }

   #p3{
    background-color: grey;
    border: 2px solid black;
    width: 30%;
    height: 180px;
     margin: 20px;
    position: relative;
  }
@media(min-width: 992px) {
 
  #p1{
    width: 30%''
  }
    #p2{
    width: 30%;
  }

   #p3{
    width: 30%;
  }

}

@media(min-width: 768px) and (max-width: 991px){
  #p1{
    width: 40%''
  }
    #p2{
    width: 40%;
  }

   #p3{
    width: 100%;
  }

}

}
section{
  clear: left;
}

</style>
</head>

<body>
 <h1>Our Menu</h1>
<div id="containor">
<div id="p1">
  <p id="p11">Chicken</p>
  <p id="p12">Text messaging, or texting, is the act of composing and sending electronic messages, typically consisting of alphabetic and numeric characters, between two or more users of mobile devices, desktops/laptops, or other type of compatible computer</p>
</div>

<div id="p2"> <p id="p11">Chicken</p>
  <p id="p12">Text messaging, or texting, is the act of composing and sending electronic messages, typically consisting of alphabetic and numeric characters, between two or more users of mobile devices, desktops/laptops, or other type of compatible computer s,</p></div>

<div id="p3"> <p id="p11">Chicken</p>
  <p id="p12">Text messaging, or texting, is the act of composing and sending electronic messages, typically consisting of alphabetic and numeric characters, between two or more users of mobile devices, desktops/laptops, or other type of compatible computer s, or other type of compatible computer</p></div>
</div>
</body>
</html>
