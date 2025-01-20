<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ahmed Anwar's Profile</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #121212;
            color: white;
            margin: 0;
            padding: 0;
        }

  .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
        }

  .animated-text {
            font-size: 24px;
            color: red;
            margin-bottom: 20px;
            overflow: hidden;
            white-space: nowrap;
            display: inline-block;
            animation: slideIn 2s ease-in-out forwards;
        }

  @keyframes slideIn {
            0% {
                transform: translateX(-100%);
                opacity: 0;
            }
            100% {
                transform: translateX(0);
                opacity: 1;
            }
        }

   .function-code {
            color: #00ff00;
            font-family: monospace;
            font-size: 16px;
        }

  .profile-image {
            display: flex;
            align-items: center;
            gap: 20px;
        }

  .profile-image img {
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Welcome to Ahmed Anwar's Profile! 👋</h1>
        <div class="animated-text">Always learning new things</div>

   <p>💼 <b>I'm a Flutter developer.</b></p>
   <p>🎓 <b>I'm a CS student at Zagazig University.</b></p>
   <p>🔧 <b>Ask me about my experience with Dart, Flutter, or anything related to mobile application development.</b></p>

   <hr />

  <h2>Connect with Me:</h2>
        <a href="https://facebook.com/ahmedanwar10" target="_blank">Facebook</a> |
        <a href="https://linkedin.com/in/ahmed-anwar10" target="_blank">LinkedIn</a>

 <hr />

  <h2>🔧 Tech Stack</h2>
   <p>Dart, Flutter, Firebase, Postman, Git, GitHub, VSCode, Android Studio</p>
        <hr />
        <h2>Most Used Languages</h2>
        <p>Dart, C++, CMake, Swift, HTML</p>

   <hr />

  <div class="profile-image">
            <img src="download.jpeg" alt="profile image" width="200" />
            <div class="function-code">
                (function repeat() { <br />
                &nbsp;&nbsp;eat(); <br />
                &nbsp;&nbsp;sleep(); <br />
                &nbsp;&nbsp;code(); <br />
                &nbsp;&nbsp;repeat(); <br />
                })();
            </div>
        </div>

        <hr />

        <h3>Profile Views:</h3>
        <img src="https://komarev.com/ghpvc/?username=Ahmedanwar10&color=blue&style=flat-square" alt="Profile Views" />
    </div>
</body>
</html>
