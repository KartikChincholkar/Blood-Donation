# Blood-Donation
<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        body{
            background-image: url(g.jpg);
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: 100% 100%;
        }
    </style>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <link rel="stylesheet" href="login.css">
    <title>Document</title>
    
</head>

<body>
   

   
    <div class="container">
        <div class="form-box">
            <div class="button-box">
                <div id="btn"></div>
                <button type="button" class="toggle-btn" onclick="login()">LogIn</button>
                <button type="button" class="toggle-btn" onclick="register()">Register</button>
            </div>
        <div class="social-media">
            <a href="https://m.facebook.com"><img src="C:\Users\karti\OneDrive\Desktop\html programs\facebookicon.png" alt="facebook"></a>
            <a href="https:www.instagram.com"><img src="C:\Users\karti\OneDrive\Desktop\html programs\instagram.png" alt="instagram"></a>
            <a href="https://twitter.com"><img src="C:\Users\karti\OneDrive\Desktop\html programs\twittericon (1).png" alt="twitter"></a>
        
        </div>
        
        <form class="login-form" id="login">
            <input type="text" class="form-field" placeholder="Username" required>
            <input type="password" class="form-field" placeholder="Password" required>
        
            <input type="checkbox" class="checkbox"><span>Remember Password</span>
            <a href="file:///C:/Users/karti/OneDrive/Desktop/blood%20donation/blood%201.html"><button type="submit" class="submit">LogIn</button></a>
        </form>
        <form class="login-form" id="register">
            
            <input type="text" class="form-field" placeholder="Username" required>
            <input type="email" class="form-field" placeholder="Email Address" required>
            <input type="password" class="form-field" placeholder="Password" required>
            <input type="checkbox" class="checkbox"><span>I Accept the Terms and Conditions</span>
            <button type="submit" class="submit">Register</button>
        </form>
        </div>
    </div>
<script>
    var x = document.getElementById("login");
    var y = document.getElementById("register");
    var z = document.getElementById("btn");

    function register()
    {
        x.style.left ="-400px" ;
        y.style.left ="50px" ;
        z.style.left ="110px" ;

    }
    function login()
    {
        x.style.left ="50px" ;
        y.style.left ="450px" ;
        z.style.left ="0" ;

    }
</script>

</body>
</html>
