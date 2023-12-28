<!DOCTYPE html>

<html lang="en">
  <head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <link rel="icon" type="image/png" href="./assets/img/favicon.png">
    <title>Redirecting</title>

    <!--     Fonts and icons     -->
    <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,400,600,700" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <script src="https://kit.fontawesome.com/42d5adcbca.js" crossorigin="anonymous"></script>

    <!-- CSS Files -->
    <link id="pagestyle" href="./assets/css/soft-ui-dashboard.css?v=1.0.7" rel="stylesheet">


    <style>
      body
      {
        margin:0;
        padding:0;
        background:#262626;
      }
      
      .h6
      {
        color: antiquewhite;
      }
      .a
      {
        color: rgb(255, 255, 255);
      }
      
      .ring
      {
        position:absolute;
        top:50%;
        left:50%;
        transform:translate(-50%,-50%);
        width:150px;
        height:150px;
        background:transparent;
        border:3px solid #3c3c3c;
        border-radius:50%;
        text-align:center;
        line-height:150px;
        font-family:sans-serif;
        font-size:20px;
        color:#fff000;
        letter-spacing:4px;
        text-transform:uppercase;
        text-shadow:0 0 10px #fff000;
        box-shadow:0 0 20px rgba(0,0,0,.5);
      }
      .ring:before
      {
        content:'';
        position:absolute;
        top:-3px;
        left:-3px;
        width:100%;
        height:100%;
        border:3px solid transparent;
        border-top:3px solid #fff000;
        border-right:3px solid #fff000;
        border-radius:50%;
        animation:animateC 2s linear infinite;
      }
      span
      {
        display:block;
        position:absolute;
        top:calc(50% - 2px);
        left:50%;
        width:50%;
        height:4px;
        background:transparent;
        transform-origin:left;
        animation:animate 2s linear infinite;
      }
      span:before
      {
        content:'';
        position:absolute;
        width:16px;
        height:16px;
        border-radius:50%;
        background:#fff000;
        top:-6px;
        right:-8px;
        box-shadow:0 0 20px #fff000;
      }
      @keyframes animateC
      {
        0%
        {
          transform:rotate(0deg);
        }
        100%
        {
          transform:rotate(360deg);
        }
      }
      @keyframes animate
      {
        0%
        {
          transform:rotate(45deg);
        }
        100%
        {
          transform:rotate(405deg);
        }
      }</style>

  <meta http-equiv="Refresh" content="2; url='https://youtu.be/dQw4w9WgXcQ'">
  </head>
  <body class="vh-100" oncontextmenu="disableRightClick(event)">

    <div class="ring" oncontextmenu="disableRightClick(event)">Loading
      <span oncontextmenu="disableRightClick(event)"></span>
    </div>
    
    <script>
      function disableRightClick(event) {
        if (event.button == 2) {
          event.preventDefault(); // Prevent the default right-click behavior
          return false;
        }
      }
    </script>
  </body>
</html>
