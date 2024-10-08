<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>악성코드 탐지 모델</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 10px 20px;
            background-color: white; /* Background color changed to white */
            color: black; /* Text color changed to black */
            box-shadow: 0px 2px 5px rgba(0, 0, 0, 0.1); /* Add slight shadow for separation */
        }
        header img {
            height: 90px; /* Adjusted the logo size */
        }
        nav {
            font-size: 18px;
        }
        nav a {
            color: black; /* Changed link color to black */
            text-decoration: none;
            margin-left: 20px;
        }
        .main-content {
            display: flex;
            justify-content: center;
            padding: 20px;
            margin-top: 20px;
        }
        .left {
            flex: 70%;
            text-align: left; /* Changed to left-align text */
            padding: 20px;
            background-color: white;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            position: relative;
            height: 300px; /* Set a fixed height for the content box */
        }
        }
        .left h2 {
            margin-top: 80px; /* Adjusted margin to accommodate image */
            margin-left: 150px; /* Adjusted to align text with image */
            font-size: 30px;
        }
        .right {
            flex: 30%;
            padding: 20px;
            background-color: #f4f4f4;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            margin-left: 20px;
            height: 300px; /* Match height with the left box */
        }
        .right h3 {
            margin-top: 0;
            font-size: 20px;
        }
        .right ul {
            list-style-type: none;
            padding: 0;
        }
        .right li {
            background-color: white; /* Changed background color of list items */
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 8px;
            font-size: 16px;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: white; /* Changed footer background to white */
            color: black; /* Changed footer text color to black */
            margin-top: 20px;
            box-shadow: 0px -2px 5px rgba(0, 0, 0, 0.1); /* Add shadow on top of footer */
        }
        .download-button {
            display: inline-block;
            background-color: #007BFF;
            color: white;
            padding: 15px 30px;
            font-size: 18px;
            text-align: center;
            text-decoration: none;
            border-radius: 8px;
            margin-top: 10px;
        }
        .credits {
            margin-top: 20px;
            text-align: left;
            font-size: 16px;
            line-height: 1.5;
        }
    </style>
</head>
<body>

<header>
    <div class="logo">
        <img src="images/logo.png" alt="T-PLIA 로고">
    </div>
    <div class="title">
        <h1>악성코드 탐지 모델</h1>
    </div>
    <nav>
        <a href="#contact">문의 -> T-PLIA 부장</a>
    </nav>
</header>

<div class="main-content">
    <div class="left">
        <h2>모델에 대한 간략적인 소개글</h2>
    </div>
    <div class="right">
        <h3>목차</h3>
        <ul>
            <li>1. 사용법</li>
            <li>2. 주요 기능</li>
            <li>3. 제작자</li>
        </ul>
    </div>
</div>

<footer>
    <a href="https://colab.research.google.com/drive/1xT56BenLauIlcm2j7yoKWoQhf4uCGY4m?usp=sharing" class="download-button">사용</a>
    <div class="credits">
        <h3>제작자</h3>
        <p><strong>악성코드 탐지 모델 개발자:</strong><br>
        김세희, 서재환, 이준우, 정가은, 조성환, 한승환</p>
        <p><strong>웹사이트 제작자:</strong><br>
        김민서, 박영우, 조예원</p>
    </div>
</footer>

</body>
</html>
