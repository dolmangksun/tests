<!DOCTYPE HTML>
<html>
  <head>
    <title>This is a test</title>
  </head>
  <body>
    Your password : <input type="text" id="PS">
    <button onclick="MyFunction()">Submit</button>
    <p id="p1"></p>
    <script>
      function MyFunction() {
      var x = document.getElemantById("PS").value;
      if (x="1234a") {
      document.getElementById("p1").innerHTML="loged in"
      }
    </script>
  </body>
</html>
