# wldud96305-bot.github.io
My portfolio website
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
    <style>
        /* 레퍼런스 사이트의 감성을 살린 스타일링 */
        body {
            margin: 0;
            padding: 40px;
            font-family: 'Helvetica', sans-serif;
            background-color: #fff;
            color: #000;
            line-height: 1.6;
        }

        header {
            margin-bottom: 100px;
        }

        h1 {
            font-size: 24px;
            font-weight: normal;
            letter-spacing: -1px;
        }

        nav {
            margin-top: 20px;
        }

        nav a {
            text-decoration: none;
            color: #888;
            margin-right: 20px;
            font-size: 14px;
        }

        nav a:hover {
            color: #000;
        }

        /* 이미지 그리드 설정 */
        .container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 40px;
        }

        .project-card {
            text-decoration: none;
            color: inherit;
            transition: opacity 0.3s;
        }

        .project-card:hover {
            opacity: 0.7;
        }

        .project-image {
            width: 100%;
            aspect-ratio: 4 / 3;
            background-color: #f0f0f0; /* 이미지가 없을 때 보이는 회색 박스 */
            object-fit: cover;
            margin-bottom: 10px;
        }

        .project-title {
            font-size: 16px;
            font-weight: bold;
        }

        .project-category {
            font-size: 13px;
            color: #888;
        }

        /* 모바일 대응 */
        @media (max-width: 600px) {
            body { padding: 20px; }
            header { margin-bottom: 50px; }
        }
    </style>
</head>
<body>

    <header>
        <h1>wldud96305-bot<br>Graphic Designer / Artist</h1>
        <nav>
            <a href="#">Work</a>
            <a href="#">About</a>
            <a href="#">Contact</a>
        </nav>
    </header>

    <main class="container">
        <!-- 프로젝트 1 -->
        <a href="#" class="project-card">
            <div class="project-image"></div> <!-- 나중에 이미지 주소를 넣으세요 -->
            <div class="project-title">Project Name 01</div>
            <div class="project-category">Branding, 2024</div>
        </a>

        <!-- 프로젝트 2 -->
        <a href="#" class="project-card">
            <div class="project-image"></div>
            <div class="project-title">Project Name 02</div>
            <div class="project-category">Photography, 2024</div>
        </a>

        <!-- 프로젝트 3 -->
        <a href="#" class="project-card">
            <div class="project-image"></div>
            <div class="project-title">Project Name 03</div>
            <div class="project-category">Editorial, 2024</div>
        </a>
    </main>

</body>
</html>
