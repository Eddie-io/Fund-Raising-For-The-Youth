# Fund-Raising-For-The-Youth
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Support the Youth Tech Hub in Accra</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .container {
      background: #fff;
      padding: 2rem;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      max-width: 500px;
      text-align: center;
    }
    h1 {
      color: #333;
    }
    p {
      color: #555;
      margin-bottom: 1rem;
    }
    .momo-info {
      background: #f1f1f1;
      padding: 1rem;
      border-radius: 8px;
      margin-bottom: 1.5rem;
    }
    .copy-btn {
      background: #007bff;
      color: white;
      border: none;
      padding: 0.5rem 1rem;
      font-size: 1rem;
      border-radius: 5px;
      cursor: pointer;
    }
    .copy-btn:hover {
      background: #0056b3;
    }
  </style>
</head>
<body>
  <div class="container">
    <h1>Help Launch a Youth Tech Hub in Accra</h1>
    <p>We're raising $10,000 to build a community tech hub in Accra that provides free coding and design classes to underprivileged youth. Be a part of shaping the future.</p>
    <div class="momo-info">
      <p><strong>MTN MoMo Number:</strong> <span id="momo-number">0531399910</span></p>
      <p><strong>Name:</strong> Jennifer Agyemang</p>
      <button class="copy-btn" onclick="copyMoMo()">Copy Number</button>
    </div>
    <p>Please send your donation via MTN Mobile Money and include your name as a reference. Thank you!</p>
  </div>

  <script>
    function copyMoMo() {
      const momoNumber = document.getElementById("momo-number").textContent;
      navigator.clipboard.writeText(momoNumber).then(() => {
        alert("MoMo number copied to clipboard!");
      });
    }
  </script>
</body>
</html>
