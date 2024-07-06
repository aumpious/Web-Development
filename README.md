#  H T M L C O D E

<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <link rel="stylesheet" href="./codinglab.css">
</head>

<body>
  
  <nav>
    
    <b>CODING LAB</b>
    <p style="display: inline;">Home</p>
    <p style="display: inline;">Product</p>
    <p style="display: inline;">Services</p>
    <p style="display: inline;">Contact</p>
    <div class="login-bar">
      <button type="button" id="login-btn" onclick="SubmitEvent()">Login</button>
    </div>
  </nav>

  <fieldset>
  
    <h1>Login</h1>

    <div class="login-container">
      <form action="" id="login-form">
        <input type="email" id="email" placeholder="Enter your email"><br><br>
        <input type="password" id="password-input" placeholder="Enter your password"><br><br>
        
      </form>
    </div>
    <div class="login-actions">
      <input type="checkbox" id="remember-me">
      <label for="remember-me">Remember me</label>
      <a href="#" style="margin-left: 10px;">Forgot password</a><br><br>
      <button type="button" id="login-input" onclick="SubmitEvent()">Login Now</button>
    </div>
  
      </form>
    </div>
   </fieldset>



  <div class="mainDiv">
    <aside></aside>
    <main></main>
  </div>
  <footer></footer>
</body>

</html>
