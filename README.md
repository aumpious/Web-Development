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



# C S S  C O D E


body {
    background-image: url('https://images.pexels.com/photos/7130464/pexels-photo-7130464.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=2');
    background-size: cover; /* cover the entire element */
    background-repeat: no-repeat; /* don't repeat the image */
    background-position: bottom; /* center the image */
  }

/* Targeting a specific element, in this case, the body element */
body {
    /* Font Family */
    font-family: 'Poppins', sans-serif;
    
    /* Font Size */
    font-size: 18px;
  
    /* Font Style */
    font-style: normal; /* or italic, oblique, etc. */
  
    /* Font Weight */
    font-weight: 400; /* or 500, 600, 700, etc. */
  
    /* Font Variant */
    font-variant: normal; /* or small-caps, etc. */
  
    /* Line Height */
    line-height: 1.5;
  
    /* Text Alignment */
    text-align: left; /* or center, right, justify, etc. */
  
    /* Text Decoration */
    text-decoration: none; /* or underline, overline, line-through, etc. */
  
    /* Text Transform */
    text-transform: none; /* or uppercase, lowercase, capitalize, etc. */
  }

  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
  }
  
  nav {
    display: flex;
    justify-content: space-around;
    align-items: center;
    height: 15vh;


  }

  


  #login-btn {
    font-size: 16px;
    padding: 0.5px 5px;
    border-radius: 5px;
    background-color: #efce5f;
    color: #121111;
    cursor: pointer;
  }
  
  #login-input{
    font-size: 18px;
    padding: 0.8px 80px;
    border-radius: unset;
    background-color: #ea68d4;
    color: #ffffff;
    cursor: pointer;
    
  }
  fieldset {
    width: 400px;
    height: 300px;
    padding: 20px; /* add some padding to make it look nicer */
    border: 1px solid #0c0000; /* add a border to make it stand out */
  }

  
  aside {
    width: 30vw;
    height: 65vh;

  }
  
  main {
    width: 70vw;
    height: 65vh;

  }
  
  .mainDiv {
    display: flex;
  }
  
  footer {
    height: 20vh;

  }

  fieldset {
    margin: 0 auto; /* horizontal centering */
    width: 50%; /* adjust the width to your liking */
  }

  h1{
    text-align: center; 
  }
 

  #myInput {
    text-align: center;
  }

div {
text-align: center;

}




