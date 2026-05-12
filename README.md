# My-Site<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proje Liderlik Tablosu</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="leaderboard-container">
        <h1>🏆 Liderlik Tablosu</h1>
        <table id="leaderboard">
            <thead>
                <tr>
                    <th>Sıra</th>
                    <th>Oyuncu</th>
                    <th>Puan</th>
                </tr>
            </thead>
            <tbody id="data-output">
                </tbody>
        </table>
    </div>

    <script src="script.js"></script>
</body>
</html>body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    background-color: #1a1a2e;
    color: white;
    display: flex;
    justify-content: center;
    padding-top: 50px;
}

.leaderboard-container {
    background: #16213e;
    padding: 2rem;
    border-radius: 15px;
    box-shadow: 0 10px 30px rgba(0,0,0,0.5);
    width: 350px;
    text-align: center;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

th {
    border-bottom: 2px solid #e94560;
    padding: 10px;
}

td {
    padding: 12px;
    border-bottom: 1px solid #24344d;
}

tr:hover {
    background-color: #0f3460;
}
