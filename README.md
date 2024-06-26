# Superior-Login
It's my first web page.
HTML Code
<html>

<head>
    <title>Login | Superior</title>
    <link rel="stylesheet" href="pratice.css">

</head>
<script>
    function validateLogin() {
        const username = document.getElementById('username').value;
        const password = document.getElementById('password').value;

        if (username == "" || password == "") {
            alert("Please enter both username and password.");
        } else {
            //alert("Login successful.");
            window.location.href="http://127.0.0.1:3000/page3.html";
        }
    }

</script>
<body>
    <div class="nav">
        <img style="width:70px; height:70px; padding-left: 30px;margin-left: 15px;" src="/assets/splogo.png" alt="">
        <h1 style="padding-top:px; color: white; ">Superior University</h1>
    </div>
    <center>
        <br><br>

       <div class="box">
        <img src="/assets/image.png" alt="">
        <p>Superior University</p>
        <div class="box2">
            <h2><b>Campus Management Solution</b></h2>
        <p><b>Note: For admission applicants only, Please enter your CNIC (i.e 82301-3629828-5) or Passport # as your User ID. Kindly use Google Chrome to singup and submit application form.</b></p>
        </div>
        <input type="username" class="username" id="username" placeholder="User ID"><br>
        <input type="password" class="password" id="password" placeholder="Password">
        <br><br>
        <button type="button" onclick="validateLogin()">Login</button><br>
        <a href="/web/reset password">Reset Password</a>

    </div>
</center>
</body>

</html>





Css File


.nav{
    background-color: #875A7B;
    width: 100%;
    height: 70;
    display: flex;
    align-items: center;
    gap: 12px;
    
}

body{
    background-color: rgb(224, 206, 221);
    color: black;
    width: 99%;
    margin: 0;
    padding: 0;
}

div {
    border: 5px solid transparent;
    width: 400px;
    background-color: white;
    overflow: hidden;
    box-shadow: 0 5px 10px transparent;
}


.box {
    background-color: white; 
    width:370px; 
    height:475px;
    padding: 20px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
    text-align: center;
}
.box img{
    margin-top: -15px;
    margin-bottom: -20px;
    width:100px;
    height:100px;
    padding-left: 5px;
}
.box p{
    color: #212529;
    font-size: 30px;
    padding-left: 20px;
    font-family: 'Times New Roman', Times,'Arial Narrow',;
    margin-bottom: -15px;
    margin-left: -25;
}
.box2 h2{
    color: #28292966;
    margin-bottom: -15px;
    margin-left: -25;
    font-size: 27;
}
.box2 p{
    font-size: 16px;
    font-family: 'Times New Roman';
    color: F44336;
    text-align: left;
    padding-left: 75px;
    padding-right: 75px;
    margin-bottom: -1px;
}
.box input {
    
    width: calc(100% - 95px);
    padding: 8px;
    margin: 10px 0 1;
    border: 1px solid #ccc;
    border-radius: 5px;
    box-sizing: border-box;
}

.box button {
    background-color: #875A7B;
    width: 270px;
    height: 50px;
    text-align:center;
    border: transparent;
    border-radius: 4px;
    color: white;
    font-size: 16px;
}
.box a {
    display: block;
    font-size: 14px;
    margin-top: 10px;
    color: #212529;
    text-align: left;
    padding-left: 20px;
    margin-left: 30;
    text-decoration: none;
}

