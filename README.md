<!DOCTYPE html>
<html>
<head>
<style>
  body {
    background-color: #111;
  }

  .box {
    width: 100px;
    height: 100px;
    background-color: red;
    position: relative;
    animation: moveBox 3s infinite alternate;
  }

  @keyframes moveBox {
    from {
      left: 0px;
    }
    to {
      left: 300px;
    }
  }
</style>
</head>
<body>

<div class="box"></div>

</body>
</html>
