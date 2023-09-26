<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aktan resume</title>
    <style>
      * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: Verdana, Geneva, Tahoma, sans-serif;
}

.col {
    width: 45%;
    height: 1000px;
    border: 1px solid black;
    margin-top: 20px;
    margin-bottom: 20px;
    border-radius: 10px;
    padding: 30px;
    max-width: 1200px;
}

.col:first-child {
    background: rgba(196, 196, 196, 0.30);
}

body {
    display: flex;
    justify-content: space-around;
    background: linear-gradient(180deg, rgba(3, 56, 244, 0.71) 0%, rgba(224, 37, 206, 0.79) 93.75%);
}

.profile img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    border-radius: 50%;
}

.profile {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.profile h1 {
    color: #CECACA;
}

.profile h2 {
    color: white;
}
.personal{
    margin-top: 30px;
}

.personal_block {
    background: rgba(196, 196, 196, 0.35);
    width: 100%;
    max-width: 600px;
    margin: auto;
    margin-bottom: 10px;
    height: 40px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    border-radius: 20px;
}
.ability{
    max-width: 600px;
    margin: auto;
    width: 100%;
}
    </style>
</head>
<body>
    
<div class="col">
    <div class="profile">
        <img src="https://avatars.mds.yandex.net/get-kinopoisk-post-img/1528730/f4fb0265f72faa9d0445b6aeb775c7d1/960x540" alt="">
        <div class="profile_texts">
            <h1>Актан</h1>
            <h1>Кенешбек уулу</h1>
            <h2>FrontEnd Devoloper</h2>
        </div>
    </div>
    <div class="personal">
        <div class="personal_block">kenesbekuuluaktan@gmail.com</div>
        <div class="personal_block">+996507874865</div>
        <div class="personal_block">https://t.me/Aktan3020</div>
        <div class="personal_block">Osh</div>
    </div>
    <div class="ability">
        <h1>Мои навыки</h1>
        <span>Строю дом</span>
        <span>Умею готовить</span>
        <span>Создавать сайты</span>
    </div>
</div>
<div class="col">

</div>

</body>
</html>
