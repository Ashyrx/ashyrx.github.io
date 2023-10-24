<!DOCTYPE html>
<html>
<head>
  <title>Download Button</title>
  <style>
    body {
      background-color: lightblue;
    }

    .center {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    button {
      padding: 20px 40px;
      font-size: 16px;
      background-color: grey;
      color: white;
      border-radius: 10px;
      margin: 0 10px;
    }

    .navbar {
      background-color: white;
      height: 50px;
      display: flex;
      justify-content: center;
      align-items: center;
    }

    .navbar a {
      margin: 0 10px;
      text-decoration: none;
      color: black;
    }
  </style>
</head>
<body>
  <div class="navbar">
    <a href="https://example.com/users">Users</a>
  </div>

  <div class="center">
    <button onclick="window.location.href='https://github.com/cymuuos'">Download</button>
    <button onclick="window.location.href='https://github.com/cymuuos'">GitHub</button>
    <button onclick="window.location.href='https://discord.gg/cymuuos'">Discord</button>
  </div>

  <script>
    function downloadFile() {
      // Add your download logic here
      console.log("File download initiated!");
    }
  </script>
</body>
</html>
