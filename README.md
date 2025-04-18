# inner-field-booking
心靈療癒預約頁面
<!-- 靜界 Inner Field｜療癒預約頁面 -->
<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>靜界 Inner Field｜預約療癒</title>
  <link href="https://fonts.googleapis.com/css2?family=Noto+Serif+TC:wght@500&display=swap" rel="stylesheet">
  <style>
    body {
      font-family: 'Noto Serif TC', serif;
      background-color: #f9f6f3;
      color: #3e3e3e;
      padding: 2em;
      line-height: 1.6;
    }
    h1 {
      text-align: center;
      color: #6b5e58;
    }
    form {
      background-color: #ffffff;
      padding: 1.5em;
      border-radius: 12px;
      max-width: 480px;
      margin: 2em auto;
      box-shadow: 0 4px 12px rgba(0,0,0,0.08);
    }
    input, select, textarea {
      width: 100%;
      padding: 0.8em;
      margin-bottom: 1em;
      border: 1px solid #ccc;
      border-radius: 8px;
    }
    button {
      background-color: #a79382;
      color: white;
      border: none;
      padding: 0.8em;
      border-radius: 8px;
      cursor: pointer;
      width: 100%;
    }
    p {
      text-align: center;
    }
  </style>
</head>
<body>
  <h1>靜界 Inner Field｜預約療癒</h1>
  <p>感謝你願意走進內在的靜謐之地<br>請填寫以下資訊，我們會盡快與你聯繫</p>
  
  <form action="https://formsubmit.co/你的email@example.com" method="POST">
    <input type="text" name="name" placeholder="你的名字" required>
    <input type="email" name="email" placeholder="聯絡信箱" required>
    <select name="service" required>
      <option value="">選擇想預約的服務</option>
      <option value="靜心引導">靜心引導</option>
      <option value="身心療癒對話">身心療癒對話</option>
      <option value="心靈卡牌占卜">心靈卡牌占卜</option>
    </select>
    <input type="text" name="preferred_time" placeholder="你偏好的時間（如 週五下午）" required>
    <textarea name="message" placeholder="有什麼想說的話嗎？" rows="4"></textarea>
    
    <input type="hidden" name="_captcha" value="false">
    <button type="submit">送出預約</button>
  </form>
</body>
</html>
