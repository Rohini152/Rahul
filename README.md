# Rahul
RahulRahini
<!DOCTYPE html>
<html>
<head>
  <title>Why I Love You</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
    }
    .reason {
      background-color: #f7f7f7;
      padding: 20px;
      margin: 20px;
      border: 1px solid #ddd;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    .reason:hover {
      background-color: #fff;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
    }
  </style>
</head>
<body>
  <h1>Why I Love You</h1>
  <p>Click on a reason to reveal why I love you!</p>
  <div class="reason" onclick="showReason(this)">
    <span>Reason 1</span>
    <p id="reason-1" style="display: none;">You make me laugh every day.</p>
  </div>
  <div class="reason" onclick="showReason(this)">
    <span>Reason 2</span>
    <p id="reason-2" style="display: none;">You're an amazing partner and friend.</p>
  </div>
  <div class="reason" onclick="showReason(this)">
    <span>Reason 3</span>
    <p id="reason-3" style="display: none;">You support me in everything I do.</p>
  </div>
  <!-- Add more reasons here! -->
  <script>
    function showReason(element) {
      var reasonId = element.children[1].id;
      document.getElementById(reasonId).style.display = "block";
    }
  </script>
</body>
</html>
