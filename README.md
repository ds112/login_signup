<!DOCTYPE html>
<html lang="vi" >

<head>
  <meta charset="UTF-8">

  <title>Sliding Login Form</title>
  <meta name="viewport" content="width=device-width, initial-scale=1">
<link href='https://fonts.googleapis.com/css?family=Roboto:300,400' rel='stylesheet' type='text/css'>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/normalize/5.0.0/normalize.min.css">

  
      <link rel="stylesheet" href="css/style.css">

  
</head>

<body>

  <div id="back">
  <div class="backRight"></div>
  <div class="backLeft"></div>
</div>

<div id="slideBox">
  <div class="topLayer">
    <div class="left">
      <div class="content">
        <h2>ĐĂNG KÝ</h2>
        <form method="post" onsubmit="return false;">
          <div class="form-group">
            <input type="text" placeholder="username" />
            <input type="password" placeholder="enter password" />
            <input type="password" placeholder="enter again password" />
            <input type="text" placeholder="enter invitation" />
          </div>
          <div class="form-group"></div>
          <div class="form-group"></div>
          <div class="form-group"></div>
        </form>
        <button id="goLeft" class="off">Login</button>
        <button>Sign up</button>
      </div>
    </div>
    <div class="right">
      <div class="content">
        <h2>ĐĂNG NHẬP</h2>
        
        <form method="post" onsubmit="return false;">
          <div class="form-group">
            <label for="username" class="form-label" >Username</label>
            <input type="text" />
            <label for="password" class="form-label" >Password</label>
            <input type="password" />
          </div>
          <button id="goRight" class="off">Sign up</button>
          <button id="login" type="submit">Login</button>
          <h4>Website chỉ dành cho người được mời, nếu bạn có lời mời, vui lòng nhấn đăng ký (Sign up) để sử dụng được dịch vụ của chúng tôi.</h4>
        </form>
      </div>
    </div>
  </div>
</div>

<!--Inspiration from: http://ertekinn.com/loginsignup/-->
  <script src='http://cdnjs.cloudflare.com/ajax/libs/jquery/2.1.3/jquery.min.js'></script>

  

    <script  src="js/index.js"></script>




</body>

