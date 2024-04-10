# zae0i.github.io
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>자기소개 page</title>
    <script>
        function region(){
            alert('동탄!');
        }
    </script>
    <script>
        function bomb(){
            alert('펑!');
        }
    </script>
    <link href="style.css" rel="stylesheet">
</head>

<body>
    <img src="https://builder.hufs.ac.kr/user/iso/k2board/iso1463374352015_b_img.png" alt="실패한 이미지"/>
    <hr>
    <h1>안녕하세요, 멋사 12기 박재영입니다.</h1>
    <hr>
    <h2>내가 좋아하는 음식</h2>
    <ul>
        <li>빅맥</li>
        <li>떡볶이</li>
        <li>요즘은 <span style="color:orange">양꼬치</span>가 맛있더라고요.</li>
    <hr>
    <h2>Quiz</h2>
    <h3>제가 거주하고 있는 지역은 어디일까요?</h3>
    <textarea>입력해주세요.</textarea>
    <button onclick="region()"> 제출</button>
    <hr>
    <h2>나와 멋사가 함께하는 이 순간</h2>
    <div class="container">
        <div class="clock">
            <h1 id="time"></h1>
        </div>
        <button id="stop">STOP</button>
        <button id="go">GO</button>
    </div>

    <script src="script.js"></script>
    <hr>
    <button ondblclick="bomb()"> 절대 더블 클릭하지 마세요</button>
