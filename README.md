# Abhishek-

Abhi_
<!DOCTYPE html>
<html>
<head>
<title>CUSTOMER Login</title>
<style>
body {
    font-family: "Times New Roman";
    background-image: url("https://www.pinterest.com/pin/797559415243769241/");
    background-size: cover;
}

button {
    background-color: white;
    width: 30%;
    color: black;
    padding: 10px;
    margin: 10px 19px;
    border: 1px solid black;
    cursor: pointer;
    text-align: center;
}


img {
    float: right;
    border-style: ridge;
    border: 3px solid gray;
    margin: 5px 1px;
    padding: 5px;
}

form {
    height: auto;
    width: auto;
    padding-top: 90px;
    padding-right: 2px;
    padding-bottom: 50px;
    padding-left: 240px;
}

input[type=text], input[type=password] {
    width: 50%;
    margin: 8px 0;
    padding: 12px 10px;
    display: inline-block;
    border: 1px solid black;
    box-sizing: border-box;
}

button:hover {
    opacity: 0.7;
}

.cancelbtn {
    width: auto;
    padding: 10px 12px;
    margin: 10px 10px;
    border: 1px solid black;
    background-color: white;
}

.center {
    width: 700px;
    padding: 20px;
    background-color: #8ba9cd;
}

.customer {
   text-align: center;
    background-color: rgba(89, 254, 182, 0.597);
    border: 2px solid rgb(250, 202, 57);
    width: 700px;
    height: 70px;
}

hr.a, hr.line {
    display: inline-block;
    width: 17%;
    height: 2px;
    background-color: black;
    border: none;
    margin: 0 5px;
}
</style>
</head>
<body>
<form>
    <div class="center">
        <div class="customer">
            <h1>LOGIN PAGE</h1>
        </div>
        <img src="https://tse2.mm.bing.net/th/id/OIP.3u1MppCjDAOUFN0P2ncKHgHaLG?w=1600&h=2397&rs=1&pid=ImgDetMain&o=7&rm=3" 
             alt="foodWet" style="width:300px;height:450px;">
        <label><b>Username:</b></label><br>
        <input type="text" placeholder="Enter Email-ID" name="Email-ID" required><br>

        <label><b>Password:</b></label><br>
        <input type="password" placeholder="Enter Password" name="password" required><br><br>

        <button type="button" onclick="history.back()" class="cancelbtn"><b>Cancel</b></button>
         <button type="submit"><b>Login</b></button><br>

        <input type="checkbox" checked="checked"><b> Remember me</b><br><br>

        <hr class="a">
        <span><b>OR login with</b></span>
        <hr class="line"><br><br>

        <a href="https://example.com/forgot-password"><b>Forgot password?</b></a><br>


        <br><br><a href="https://www.google.com" class="google"><b>Google</b></a>
<span>OR</span>
<a href="https://www.facebook.com" class="facebook"><b>Facebook</b></a>
<span>OR</span>
<a href="https://www.instagram.com" class="instagram"><b>Instagram</b></a>

        <button type="button" class="login"><b>Sign-up</b></button><br>
    </div>
</form>
</body>
</html>
