# Javasript
Check button Coding
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>
 <div style="border: 3px double #ccc; padding: 5px; margin-top: 5px; width: 200px;">
<form>
  What color do you prefer?<br>

   <input type="radio" id="redRadio" name="color" value="red">
  <label for="redRadio" style="color: red;">Red</label>

  <input type="radio" id="blueRadio" name="color" value="blue">
  <label for="blueRadio" style="color: blue;">Blue</label>
</form>
  <button onclick="checkRed()">Check Red</button>
  <button onclick="checkBlue()">Check Blue</button>

</div>

  <script>
    function checkRed() {
      document.getElementById('redRadio').checked = true;
      document.getElementById('blueRadio').checked = false;
    }

    function checkBlue() {
      document.getElementById('redRadio').checked = false;
      document.getElementById('blueRadio').checked = true;
    }
  </script>

</body>
</html>
