# info.C.K.A


<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Головна</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="center">
        <button onclick="goToPhotoPage()">Перейти до фото</button>
    </div>
    <script src="script.js"></script>
</body>
</html>


<!DOCTYPE html>
<html lang="uk">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Фото</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="center">
        <img src="https://i.pinimg.com/736x/ea/c2/52/eac252c37ce77e91363113c3c4dee577.jpg" alt="Фото">
        <br><br>
        <a href="index.html" class="btn">⬅ Назад</a>
    </div>
</body>
</html>


body {
    margin: 0;
    height: 100vh;
    font-family: Arial, sans-serif;
    background-color: #f5f5f5;
    display: flex;
    justify-content: center;
    align-items: center;
}

.center {
    text-align: center;
}

button, .btn {
    background-color: #3498db;
    color: white;
    padding: 15px 25px;
    border: none;
    border-radius: 8px;
    font-size: 18px;
    cursor: pointer;
    text-decoration: none;
}

button:hover, .btn:hover {
    background-color: #2980b9;
}

img {
    max-width: 90%;
    border-radius: 10px;
}


function goToPhotoPage() {
    window.location.href = "photo.html";
}
