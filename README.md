<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CodingChicken TeamPage</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: white;
            padding: 20px;
            align-items: center;
            justify-content: space-between;
        }

        .header-content {
            display: flex;
            align-items: center;
            justify-content: space-between;
            width: 100%;
        }

        h1 {
            margin: 0;
            font-size: 48px;
            color: black;
        }

        .button-container {
            display: flex;
            gap: 10px;
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
        }

        .container {
            display: flex;
            margin: 20px;
        }

        .image {
            flex: 1;
            margin-right: 20px;
        }

        .cards {
            display: flex;
            flex-direction: column;
            flex: 1;
        }

        .card {

            border-radius: 5px;
            padding: 20px;
            text-align: left;
            margin-bottom: 20px;
            box-sizing: border-box;
        }

        .card h5 {
            margin: 0 0 10px;
        }

        .card p {
            background-color: white;
            padding: 10px;
            border-radius: 5px;
            font-size: 1.2em;
        }

        img {
            max-width: 100%;
            height: auto;
        }
    </style>
</head>

<body>
    <header>
        <div class="header-content">
            <h1>코딩치킨</h1>
            <div class="button-container">
                <button>팀 소개</button>
                <button>멤버 소개</button>
            </div>
        </div>
    </header>
    <div class="container">
        <div class="image">
            <img src="https://img.freepik.com/free-vector/cute-chicken-standing-weight-scale-cartoon-vector-icon-illustration-animal-healthy-isolated-flat_138676-11482.jpg"
                alt="코딩치킨">
        </div>
        <div class="cards">
            <div class="card">
                <h5>팀소개</h5>
                <p>설명 내용 1</p>
            </div>
            <div class="card">
                <h5>우리 팀의 목표</h5>
                <p>설명 내용 2</p>
            </div>
            <div class="card">
                <h5>우리 팀의 특징</h5>
                <p>설명 내용 3</p>
            </div>
            <div class="card">
                <h5>우리 팀원의 약속</h5>
                <p>설명 내용 4</p>
            </div>
        </div>
    </div>
</body>

</html>
