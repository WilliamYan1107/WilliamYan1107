<!DOCTYPE html>
<html lang="en">
<head>
    <title>St.Cecilia Orphanage</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
  <style>
    *{
    margin:0;
    padding:0;

}

.main{
    width:100%;
    background-image: linear-gradient(to top, rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%),url(https://www.humanium.org/en/wp-content/uploads/2020/03/shutterstock_1180465816-830x553.jpg);
    background-position: center;
    background-size:cover;
    position:relative;
    height:109vh;
}

.navbor{
    width:1200px;
    height:75px;
    margin:auto;
}

.icon{
    width:200px;
    float:left;
    height:70px;
}

.logo{
    color:#ff7200;
    font-size:35px;
    font-family: Arial;
    padding-left:20px ;
    float:left;
    padding-top:10px;
}

.menu{
    width:500px;
    float:left;
    height:70px;
}

ul{
    float:left;
    display:flex;
    justify-content:center;
    align-items:center;

}

ul li{
    list-style:none;
    margin-left: 62px;
    margin-top: 27px;
    font-size: 14px;
}

ul li a{
    text-decoration: none;
    color: #fff;
    font-family: Arial;
    font-weight:bold;
    transition: 0.4s ease-in-out;
}

.search{
    width: 330px;
    float: left;
    margin-left: 270px;
}

.srch{
    font-family: 'Times New Roman';
    width: 200px;
    height: 40px;
    background-color: transparent;
    border: 1px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    border-right: none;
    font-size: 16px;
    float: left;
    padding: 10px;
    border-bottom-left-radius: 5px;
    border-top-left-radius: 5px;
}

.btn{
    width: 100px;
    height: 40px;
    background: #ff7200;
    border: 2px solid #ff7200;
    margin-top: 13px;
    color: #fff;
    font-size: 15px;
    border-bottom-right-radius: 5px;
    border-bottom-right-radius: 5px;
}
    
.btn:focus{
    outline: none;
}

.srch:focus{
    outline: none;
}

.content{
    width:1200px;
    height:auto;
    margin:auto;
    color:#fff;
    position:relative;
}

.conetnt.par{
    padding-left: 20px;
    padding-bottom: 25px;
    font-family: Arial;
    letter-spacing:1.2px;
    line-height:30px;
}

.content h1{
    font-family: 'Times New Roman';
    font-size: 50px;
    padding-left:20px;
    margin-top: 9%;
    letter-spacing: 2px;
}

.content .cn{
    width: 160px;
    height: 40px;
    background:#ff7200;
    border: none;
    margin-bottom:10px;
    margin-left:20px;
    font-size:18px;
    border-radius: 10px;
    cursor: pointer;
    transition: .4s ease;
}

.content .cn a{
    text-decoration: none;
    color:#000;
    transition: .3s ease;
}

.cn:hover{
    background-color:aliceblue
}

.form{
    width: 250px;
    height: 380px;
    background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
    position: relative;
    top: -2px;
    left:870px;
    border-radius: 10px;
    padding: 25px;
}

.form h2{
    width: 220px;
    font-family: sans-serif;
    text-align: center;
    color:#ff7200;
    font-size: 22px;
    background-color:aliceblue;
    border-radius: 10px;
    margin: 2px;
    padding: 8px;
}

.form input{
    width: 240px;
    height: 35px;
    background: transparent;
    border-bottom: 1px solid #ff7200;
    border-top: none;
    border-right: none;
    border-left: none;
    color:aliceblue;
    font-size: 15px;
    letter-spacing: 1px;
    margin-top: 30px;
    font-family: sans-serif;
}

.form input:focus{
    outline:none;
}

::placeholder{
    color:aliceblue;
    font-family: Arial;
}

.btrn{
    width: 220px;
    height: 40px;
    background: #ff7200;
    border: 35px;
    font-size: 18px;
    border-radius: 10px;
    cursor: pointer;
    color:#fff;
    transition: 0.4s ease;
}

.btnn:hover{
    background: #fff;
    color:#ff7200
}

.btnn a{
    text-decoration: none;
    color:#000;
    font-weight: bold;
}
.form .link{
    font-family: Arial, Helvetica, sans-serif;
    font-size: 17px;
    padding-top: 20px;
    text-align: center;
}

.form .link a{
    text-decoration: none;
    color:#ff7200;
}

.liw{
    padding-top: 15px;
    padding-bottom: 10px;
    text-align: center;
}

.icon a{
    text-decoration: none;
    color: #fff;
}

.icon ion-icon{
    color: #fff;
    font-size: 23px;
    padding-left: 12.5px;
    padding-top: 5px;
    transition: 0.3s ease;
}

.icon ion-icon:hover{
    color:#ff7200;
}


@media screen and (max-width:1200px) {
    /*Normal Screen*/
    .navbar{
        width: 100%;
        height: 100px;
    }
    ul{
        margin-left: 30px;
    }   
    ul li{
        margin-left: 60px;
    }
    ul li a{
       font-size: 1.6vw; 
    }
    .search{
        margin-top: 3px;
        margin-left: 290px;
    }
    .srch{
        height: 40px;
        width: 190px;
        font-size: 14px;
    }
    .btn{
        height:40px;
        width: 80px;
    }
    .content{
        width: 100%;
    }
    .content h1, .content span{
        font-size: 4.5vw; 
    }
    .content .par{
        width: 90%;
        font-size: 1.5vw;
    }
    .content .cn{
        width: 13%;
        height: 3.5vw;
        font-size: 1.8vw;
    }
    .content a{
        font-size: 1.6vw
    }
}

@media screen and (max-width:1170px) {
    /*Login-box*/
    .main{
        padding-left: 20px;
        height: 180vh;
    }
    .form{
        margin-left: -30px;
        width: 250px;
        height: 370px;
        background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
        position: absolute;
        top: 420px;
        left: 50px;
        transform: translate(0%,-5%);
        border-radius: 10px;
        padding: 25px;
    }
    .form input{
        width: 240px;
        height: 35px;
        background: transparent;
        border-bottom: 1px solid #ff7200;
        border-top: none;
        border-right: none;
        border-left: none;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        margin-top: 30px;
        font-family: sans-serif;
    }
    .btnn a{
        font-size: 16px;
    }
    .form .link a{
        font-size: 16px;
    }
}

@media screen and (max-width: 830px){
    /*For tablet*/
   
    .content{
        margin-top: 120px;
        width: 80%;   
        margin-left: 40px;  
    }
    .content h1, .content span{
        font-size: 6vw; 
    }
    .content .par{
        width: 90%;
        font-size: 1.8vw;
    }
    .content .cn{
        width: 15%;
        height: 4.5vw;
        font-size: 2vw;
    }
    .content a{
        font-size: 2vw
    }
    .logo{
        margin-left: 240px;
        width: 100%;
        margin-top: 15px;
        font-size: 5vw;
    }
    .menu{
        width: 100%;
    }
    ul{
        margin-top: -5px;
        margin-left: 5px;
    }
    ul li{
        margin-left: 60px;
    }
    ul li a{
       font-size: 2vw; 
    }
    .search{
        margin-top: -20px;
        margin-left: 60px;   
    }   
    .srch{
        height: 30px;
        width: 160px;
        font-size: 12px;
    }
    .btn{
        height:30px;
        width: 70px;
    }
    .main{
        padding-left: 20px;
        height: 180vh;
    }
    .form{
        margin-left: -30px;
        width: 250px;
        height: 370px;
        background: linear-gradient(to top, rgba(0,0,0,0.8)50%,rgba(0,0,0,0.8)50%);
        position: absolute;
        top: 430px;
        left: 50px;
        transform: translate(0%,-5%);
        border-radius: 10px;
        padding: 25px;
    }
    .form input{
        width: 240px;
        height: 35px;
        background: transparent;
        border-bottom: 1px solid #ff7200;
        border-top: none;
        border-right: none;
        border-left: none;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        margin-top: 30px;
        font-family: sans-serif;
    }
    .btnn a{
        font-size: 16px;
    }
    .form .link a{
        font-size: 16px;
    }
}

@media screen and (max-width: 600px){
    /*IPAD*/
    
    .content{
        margin-top: 80px;
        margin-left: 20px;
    }
    .search{
        margin-top: -40px;
        margin-left: 42px;
    }
    .logo{
        margin-left: 180px;
        font-size: 4vw;
    }
    ul{
        margin-top: -25px;
        margin-left: -5px;
    }
    ul li {
        margin-left: 50px;
    }
    ul li a{
        font-size: 2vw;
    }   
}

@media screen and (max-width: 450px){
    /*mobile*/
    .logo{
        margin-left: 140px;
        font-size: 4vw;
    }
    ul{
        margin-top: -25px;
    }
    ul li {
        margin-left: 42px;
    }
    ul li a{
        font-size: 2vw;
    }  
    .search{
        margin-top: -40px;
        margin-left: 38px;
    } 

}
  </style>
    <div class="main">
        <div class="navbar">
           <div class="icon">
               <h2 class="logo">St.Cecilia Orphanage</h2>
           </div>

           <div class="menu">
               <ul>
                   <li><a href="home.html">HOME</a></li>
                   <li><a href="about_us/about_us.html">ABOUT</a></li>
                   <li><a href="Goal/goal.html">GOAL</a></li>
                   <li><a href="challenge/challenge.html">CHALLENGE</a></li>
                   <li><a href="Donation/donation.html">DONATION</a></li>
                   <li><a href="contact_page/contact.html">CONTACT</a></li>
               </ul>
           </div>

           <div class="search">
               <input class="srch" type="search" name="" placeholder="Type To text">
               <a href="#"> <button class="btn">Search</button></a>

           </div>
            
        </div>
        <div class="content">
            <br><br>
            
            <h1>Our Charity & Our Community</h1>
            <p class="par"></br>We have always believed that education changes lives.</br>2020 will be a dark year for the whole world due to the spread of the COVID-19 pandemic. </br>Like any child in the world,children in orphanages deserve a quality education.
                <br>Let's work together for St.Cecilia Orphanage!</p>


                <div class="form">
                    <h2>Login Here</h2>
                    <input type="email" name="email" placeholder="Enter Email Here">
                    <input type="password" name="" placeholder="Enter Password Here">
                    <button class="btnn"><a href="#">Login</a></button>

                    <p class="link">Don't have an account<br>
                    <a href="#">Sign up </a> here</a></p>
                    <p class="liw">Log in with</p>

                    <div class="icon">
                        <a href="#"><ion-icon name="logo-facebook"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-instagram"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-twitter"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-google"></ion-icon></a>
                        <a href="#"><ion-icon name="logo-wechat"></ion-icon></a>
                    </div>
                    
            
                    
        </div> 
        <script src="https://unpkg.com/ionicons@5.4.0/dist/ionicons.js" ></script> 
    
        

        
    </section>

</body>
</html>



