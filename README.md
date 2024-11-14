# Framework DESIGN
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Framework Design</title>
    <style>
      body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
}

header {
    background: #333;
    color: white;
    padding: 1em;
}

header nav ul {
    list-style-type: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin-right: 20px;
}

section {
    padding: 20px;
}

table {
    width: 100%;
    border-collapse: collapse;
}

table, th, td {
    border: 1px solid black;
}

th, td {
    padding: 10px;
    text-align: left;
}
    </style>
</head>
<body>
    <header>
        <h1>Framework Design</h1>
        <nav>
            <ul>
                <li><a href="#home">홈</a></li>
                <li><a href="#comparison">프레임워크 비교</a></li>
                <li><a href="#examples">예제 코드</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>웹 프레임워크란?</h2>
        <p>웹 프레임워크는 웹 애플리케이션을 개발할 때 필요한 구성 요소를 제공하는 소프트웨어입니다.</p>
    </section>

    <section id="comparison">
        <h2>프레임워크 비교</h2>
        <table>
            <tr>
                <th>프레임워크</th>
                <th>언어</th>
                <th>특징</th>
            </tr>
            <tr>
                <td>Django</td>
                <td>Python</td>
                <td>MTV 아키텍처, ORM 지원</td>
            </tr>
            <tr>
                <td>Flask</td>
                <td>Python</td>
                <td>경량, 유연성, 모듈화</td>
            </tr>
            <tr>
                <td>Ruby on Rails</td>
                <td>Ruby</td>
                <td>Convention over Configuration</td>
            </tr>
            <tr>
                <td>Express.js</td>
                <td>JavaScript</td>
                <td>빠르고 미니멀한 웹 서버 구축</td>
            </tr>
        </table>
    </section>

    <section id="examples">
        <h2>예제 코드</h2>
        <pre>
            <code>
                # Flask 예제
                from flask import Flask
                app = Flask(__name__)

                @app.route('/')
                def hello():
                    return 'Hello, World!'
            </code>
        </pre>
    </section>

    <footer>
        <p>&copy; 2024 Framework Design. All rights reserved.</p>
    </footer>
</body>
</html>
