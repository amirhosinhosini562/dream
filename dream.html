<!DOCTYPE html>
<html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>فرم سفارش دریم لیگ 2025</title>
  <link href="https://fonts.googleapis.com/css2?family=Vazirmatn:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Vazirmatn', sans-serif;
      background: linear-gradient(to bottom, #0f2027, #203a43, #2c5364);
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 20px;
    }
    .header-img {
      width: 100%;
      max-width: 600px;
      border-radius: 15px;
      box-shadow: 0 0 20px rgba(255,255,255,0.4);
      margin-bottom: 20px;
    }
    .form-container {
      background: rgba(255, 255, 255, 0.1);
      backdrop-filter: blur(10px);
      padding: 20px;
      border-radius: 20px;
      width: 100%;
      max-width: 400px;
      box-shadow: 0 0 15px rgba(0, 0, 0, 0.6);
    }
    input {
      width: 100%;
      padding: 10px;
      margin: 10px 0;
      border-radius: 10px;
      border: none;
      font-size: 16px;
    }
    button {
      width: 100%;
      padding: 12px;
      background-color: #1abc9c;
      border: none;
      border-radius: 12px;
      color: white;
      font-size: 18px;
      cursor: pointer;
    }
    button:hover {
      background-color: #16a085;
    }
    .message {
      margin-top: 15px;
      font-weight: bold;
      display: none;
    }
  </style>
</head>
<body>
  <img src="dream.jpg" alt="Dream League" class="header-img">

  <div class="form-container">
    <form method="post">
      <input type="text" name="code" pattern="[A-Za-z]{1,6}" title="حداکثر 6 حرف، فقط حروف انگلیسی" placeholder="کد اکانت" required>
      <input type="number" name="diamond" placeholder="مقدار الماس" required>
      <input type="number" name="coins" placeholder="مقدار سکه" required>
      <button type="submit">ارسال</button>
    </form>
    <div class="message" id="message">لطفا صبر کنید...</div>
  </div>

  <?php
  if ($_SERVER['REQUEST_METHOD'] === 'POST') {
    function sanitize($data) {
      return htmlspecialchars(trim($data), ENT_QUOTES, 'UTF-8');
    }

    $code = sanitize($_POST['code']);
    $diamond = (int) $_POST['diamond'];
    $coins = (int) $_POST['coins'];

    date_default_timezone_set("Asia/Tehran");
    $date = date("Y-m-d H:i:s");

    $data = [
      "code" => $code,
      "diamond" => $diamond,
      "coins" => $coins,
      "time" => $date
    ];

    $dir = __DIR__ . '/dreams';
    if (!is_dir($dir)) mkdir($dir, 0755, true);

    $filename = $dir . '/code.json';
    file_put_contents($filename, json_encode($data, JSON_UNESCAPED_UNICODE | JSON_PRETTY_PRINT));

    echo "<script>
      document.getElementById('message').style.display = 'block';
      setTimeout(() => {
        document.getElementById('message').innerText = 'سفارش با موفقیت ثبت شد';
      }, 2000);
    </script>";
  }
  ?>
</body>
</html>
