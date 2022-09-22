# css
css ve html ile yaptığım örnek çalışmam 


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title> Örnek Css </title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="navbar">
          <div class="logo">
            <a href="#"> LOGO </a>
          </div>  
          <ul>
            <li><a href="#" class="active"> Ana Sayfa</a></li>
            <li><a href="#"> Hakkımızda</a></li>
            <li><a href="#"> Ürünler</a></li>
            <li><a href="#"> Hizmetler</a></li>
            <li><a href="#"> İletişim</a></li>
          </ul>   
        </div>
    <div class="center">
    <h1> Takı Dünyasına</h1>
    <h2> HOŞGELDİNİZ </h2>
<div class="buttons">
<button> Giriş Yap </button>
<button> Kaydol </button>
         </div>
      </div>
  </div>

</body>
</html>





@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@1,100&display=swap');


* {
   margin:0; 
   padding:0;
}

.container{ 
    background: url(takı.jpg);
    height: 100vh;
    background-size: 100% 100%;
}
    
.container .navbar {
width: 100%;
height:80px;
background: rgba(22,112,214,0.4)

 }

   .navbar .logo{
    display: inline-block;
    margin-left: 50px;
    margin-top: 20px;
 }
  .navbar .logo a{
    text-decoration: none;
    font-size: 30px;
    font-family: sans-serif;
    color: #f3f3f3;
  }
   .navbar ul {
    float: right;
    margin-right: 20px;
}
.navbar ul li{
    list-style: none;
    display: inline-block;
    margin:0 8px;
    line-height: 80px;

}

.navbar ul li a{
    color:white;
    text-decoration: none;
    font-size: 20px;
    padding: 6px 13px;
    font-family: Roboto;
    transition: 5s;
}

.navbar ul li a.active,
.navbar ul li a:hover{
   background:#ff6e00;
   border-radius: 2px;
 
}

.container .center{
    position: absolute;
    top:50%;
    left:50%;
    transform: translate(-50%,-50%);
    font-family: sans-serif;
    user-select: none;
}
.center h1 {
    color:black;
    font-size: 70px;
    font-weight: bold;
    width: 900px;
    text-align: center;
}

.center h2 {
    color:red;
    font-size: 50px;
    font-weight: bold;
    width: 885px;
    margin-top: 10px;
    text-align: center;
 }

 .center .buttons {
    margin:35px 280px;
    }

    .buttons button{
        height: 50px;
        width:150px;
        font-size: 18px;
        font-weight: bold;
        color:#ffb3b3;
        background: rgb(207,96,88);
        border:solid 1px red;
        cursor:pointer;
        outline: none;
        border-radius: 25px;
        transition: 5s;
    }
 .buttons .button:hover{
    background: #fff;
 }


