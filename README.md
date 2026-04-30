# my-first-page
<!DOCTYPE html>

<html>

<head>

  <title>互動版</title>

  <style>

    body {

      background: black;

      text-align: center;

      color: white;

    }

    .box {

      width: 100px;

      height: 100px;

      background: lime;

      margin: 50px auto;

      animation: move 2s infinite alternate;

    }

    @keyframes move {

      from { transform: translateY(0); }

      to { transform: translateY(200px); }

    }

  </style>

</head>

<body>

  <h1>點我試試看</h1>

  <div class="box" onclick="changeColor()"></div>

  <script>

    function changeColor() {

      document.querySelector('.box').style.background = 'red';

    }

  </script>

</body>

</html>
