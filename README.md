<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<title>Document</title>
    </head>
    <style>
        .container
        {
            display: flex;
            flex-direction: column;
            flex-wrap: wrap;
            columns:50% 50%;
            height: 100vh;
            margin:100px;
            background-color: white;
        }
        .col-2
        {
            margin-top: 85px;
            width:70vh;
            background-color: white;
        }
        .logins
        {
            color:rgb(6, 114, 172);
             font-size:30px;
             font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;
        }
        .button
        {
            border: 0;
             background-color:aliceblue;
              color:rgb(3, 114, 249);
               font-size:10px; 
               
            font-weight:100;
        }
        .login
        {
            background-color: darkorange;
            color: aliceblue;
            border:0;
            margin:25px;
            padding-left: 50px;
            padding-right: 50px;
            font-size: 20px;
        }
        
    </style>
</head>
<body>
    <div class="container">
       
        <div class="col-2">
	        <b><i class="logins">Login</i>
            <p style="color:gray; font-size:10px">Login to your Account</p><br>
            <form action="#">
                <input type="text"  id="form" placeholder="Email id/Mobile Number"style="border:0;"/><hr><br>
                <input type="passward" id="form" placeholder="Enter Passward" style="border:0"/><hr><br>
                <input type="checkbox" id="checkbox"><label  style="color:gray; font: size 15px;">keep me signed in</label><br>
                <button class="button"> <p style="left:15px;">Forgot Passward</p></button><br>
                <button class="login">Login</button>
                <small>or</small>
                <button class="button">Request OTP</button>
            </form>
             <small>Dont have an account?<button class="button">Signup</button>
        </div>
    </div>
    
</body>
</html>
