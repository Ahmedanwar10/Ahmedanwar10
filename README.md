<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Ahmed Anwar's Profile</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #1e1e2f;
      color: #ffffff;
      margin: 0;
      padding: 20px;
    }

   .container {
      display: flex;
      align-items: flex-start;
      gap: 20px;
    }
    .profile-info {
      flex: 1;
      font-size: 16px;
    }
    .profile-info h3 {
      font-size: 20px;
      color: #ff6347;
      margin-bottom: 10px;
      animation: slide-in 2s ease-in-out;
    }

  .code-container {
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      gap: 20px;
    }
    .code {
      color: blue;
      font-family: monospace;
      font-size: 16px;
      text-align: left;
    }

   img {
      border-radius: 10px;
      border: 2px solid #fff;
    }

   ul {
      list-style: none;
      padding: 0;
    }

   ul li {
      margin-bottom: 10px;
    }

   @keyframes slide-in {
      from {
        transform: translateX(-100%);
        opacity: 0;
      }
      to {
        transform: translateX(0);
        opacity: 1;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <!-- الجانب الأيسر: الكود والصورة -->
    <div class="code-container">
      <img src="download.jpeg" alt="profile image" width="200" />
      <div class="code">
        (function repeat() { <br />
        &nbsp;&nbsp;eat(); <br />
        &nbsp;&nbsp;sleep(); <br />
        &nbsp;&nbsp;code(); <br />
        &nbsp;&nbsp;repeat(); <br />
        })();
      </div>
    </div>

    <!-- الجانب الأيمن: النص -->
   <div class="profile-info">
      <h3>Always learning new things</h3>
      <ul>
        <li>💼 <strong>I'm a Flutter developer.</strong></li>
        <li>🎓 <strong>I'm a CS student at Zagazig University.</strong></li>
        <li>🔧 <strong>Ask me about my experience with Dart, Flutter, or anything related to mobile application development.</strong></li>
      </ul>
    </div>
  </div>
</body>
</html>
