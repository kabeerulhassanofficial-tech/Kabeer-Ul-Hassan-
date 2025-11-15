# Kabeer-Ul-Hassan-
Information about Kabeer Ul Hassan 
```<html>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Kabeer Ul Hassan - Introduction</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      padding: 20px;
      line-height: 1.8;
}
.container {
      max-width: 700px;
      margin: auto;
      background: #fff;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
    h1 {
      text-align: center;
      color: #006699;
}
.section {
      margin-bottom: 20px;
}
.profile {
      text-align: center;
      margin-bottom: 20px;
}
.profile img {
      width: 150px;
      height: 150px;
      object-fit: cover;
      border-radius: 50%;
      box-shadow: 0 0 8px rgba(0,0,0,0.2);
}
.profile-name {
      font-size: 1.5em;
      font-weight: bold;
      margin-top: 10px;
      color: #006699;
}
.social-links a {
      display: block;
      margin: 5px 0;
      color: #006699;
      text-decoration: none;
}
.social-links a:hover {
      text-decoration: underline;
}
.status {
      padding: 15px;
      border-radius: 8px;
      font-weight: bold;
      text-align: center;
      color: white;
}
.study {
      background-color: #007bff;
}
.sleep {
      background-color: #6c757d;
}
.available {
      background-color: #28a745;
}
  </style>
</head>
<body>
  <div class="container">
    <div class="profile">
      <img src="your-image-path.jpg" alt="Kabeer Ul Hassan">
      <div class="profile-name">Kabeer Ul Hassan</div>
    </div>

    <h1>تعارف / Introduction</h1>

    <div class="section">
      <h2>اردو</h2>
      <p><strong>نام:</strong> کبیر ال حسن</p>
      <p><strong>تاریخ پیدائش:</strong> 27 مئی 2010</p>
      <p><strong>شہر:</strong> قصور</p>
      <p><strong>تعلیم:</strong> میٹرک - گورنمنٹ ایم سی ہائی سکول قصور</p>
    </div>

    <div class="section">
      <h2>English</h2>
      <p><strong>Name:</strong> Kabeer Ul Hassan</p>
      <p><strong>Date of Birth:</strong> May 27, 2010</p>
      <p><strong>City:</strong> Kasur</p>
      <p><strong>Education:</strong> Matriculation from Govt. MC High School Kasur</p>
    </div>

    <div class="section">
      <h2>Current Status</h2>
      <div id="statusBox" class="status">Loading status...</div>
    </div>

    <div class="section social-links">
      <h2>Social Media Links</h2>
      <a href="https://facebook.com/kabeeerulhassan" target="_blank">Facebook</a>
      <a href="https://www.tiktok.com/@kabeeerulhassanofficial" target="_blank">TikTok</a>
      <a href="https://instagram.com/kabeeerulhassanofficiall" target="_blank">Instagram</a>
      <a href="https://x.com/KabeerAnxari" target="_blank">X (Twitter)</a>
    </div>
  </div>

  <script>
    function updateStatus() {
      const now = new Date();
      const hour = now.getHours();
      const statusBox = document.getElementById("statusBox");

      if (hour>= 8 && hour < 17) {
        statusBox.textContent = "📘 Study Time (8 AM - 5 PM)";
        statusBox.className = "status study";
} else if (hour>= 23 || hour < 5) {
        statusBox.textContent = "😴 Sleep Time (11 PM - 5 AM)";
        statusBox.className = "status sleep";
} else {
        statusBox.textContent = "✅ Available";
        statusBox.className = "status available";
}
}

    updateStatus();
    setInterval(updateStatus, 60000);
  </script>
</body>
</html>
```