<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="style/index.css" rel="stylesheet" type="text/css" />
    <title>Jagermeister</title>
  <style>
    body.b1 {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: grey;
}
.header {
    background-color: #000;
    color: white;
    padding: 10px 0;
    text-align: center;
    position: relative;

}
.header img {
    height: 100px;
    vertical-align: middle;
}
.header h1 {
    display: inline;
    font-size: 36px;
    margin: 0;
    vertical-align: middle;
}
.header .contact-info {
    position: absolute;
    top: 40px;
    right: 15px;
    text-align: right;
    font-family: 'Roboto', sans-serif;
}
.header .contact-info p {
    margin: 0;
}
.nav {
    background-color: #8B0000;
    text-align: center;
    padding: 10px 0;
}
.nav a {
    color: white;
    text-decoration: none;
    margin: 0 15px;
    font-size: 18px;
    transition: color 0.3s ease
}
.nav a:hover {
    color: #ffd700;
}

.content {
    display: flex;
    justify-content: center;
    margin: 20px;
}
.box {
    border: 1px solid #000;
    padding: 20px;
    margin: 10px;
    width: 500px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    animation: slideIn 1s ease-in-out;
}
.box img {
    height: 100px;
    vertical-align: middle;
    animation: slideIn 1s ease-in-out;
}


.main-page-text {
    background: linear-gradient(246.81deg, #000 19.52%, #8B0000 86.89%);
    padding-top: 60px;
    padding-left: 60px;
    padding-right: 60px;
    padding-bottom: 150px;
    color: #FFFFFF;
}
.about-text {
    display: flex;
    font-family: Arial, sans-serif;
    font-size: 20px;
    margin-top: 30px;
    justify-content: space-around;
    align-items: flex;
    text-align: center;
    display: flex;
    gap: 20px;
}
.bg2 {
    position: absolute;
    width: 1300px;
    height: auto;
    text-align: center;
}

.bg2 img {
    width: 100%;
    height: auto;
}

.napitok {
    font-size: 45px;
    position: relative;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white; /* Цвет текста, чтобы он был виден на фоне */
    text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7); /* Тень для улучшения читаемости */
}
.about-company {
    background-image: url('https://wallpapers.com/images/hd/table-background-ehvksujm2s1m1b9a.jpg');
    background-size: cover;
    background-position: center;
    padding: 120px 20px;
    color: #fff;
    text-align: center;
}

.about-company h1 {
    font-size: 40px;
    margin-bottom: 20px;
    font-family: 'Roboto', sans-serif;
    animation: slideIn 1s ease-in-out;
}
@keyframes slideIn {
    from {
        opacity: 0;
        transform: translateX(-50px);
    }
    to {
        opacity: 1;
        transform: translateX(0);
    }
}

body.b2 {
    background-color: black;
    color: white;
    font-family: Arial, sans-serif;
    text-align: center;
}
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 50px;
}
.item {
    margin: 0 50px;
}
.item img {
    border: 1px solid white;
    display: flex;
    justify-content: space-between;
    float: left;
    margin-right: 10px;
    
}
.title {
    font-size: 24px;
    font-weight: bold;
    margin-top: 550px;
    text-align: center;
    animation: slideIn 1s ease-in-out;
}
.description {
    font-size: 20px;
    margin-top: 20px;
    font-family: 'Georgia', sans-serif;
    text-align: center;
    animation: slideIn 1s ease-in-out;
}
.about-company p {
    font-size: 20px;
    line-height: 1.6;
    max-width: 800px;
    margin: 0 auto;
    font-family: 'Roboto', sans-serif;
    animation: slideIn 1s ease-in-out;
}


body.b3 {
    font-family: Arial, sans-serif;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    margin: 0;
    background-color: #f9f9f9;
}
.whyJback {
    background: linear-gradient(246.81deg, #000 19.52%, #8B0000 86.89%);
    padding-top: 20px;
    padding-left: 60px;
    padding-right: 60px;
    padding-bottom: 70px;
}
.whyJ {
    text-align: center;
    max-width: 1000px; 
    width: 100%;
    padding: 20px;
    margin: 0 auto;
}

.whyJ h1 {
    font-size: 30px;
    color: #FFFFFF;
    text-align: center;
    margin-top: 40px;
    margin-bottom: 40px;
    animation: slideIn 1s ease-in-out;
}

.advantages-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); /* Колонки адаптируются под размер */
    gap: 20px;
    margin-top: 20px;
    justify-content: center;
}

.advantage-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}
.advantage-item:hover {
    transform: scale(1.05);
}

.advantage-item .number {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    background-color: #e44a29;
    color: white;
    font-size: 18px;
    font-weight: bold;
    border-radius: 50%;
    margin-bottom: 10px;
}

.advantage-item .title {
    font-weight: bold;
    margin: 10px 0 5px;
}

.advantage-item .description {
    font-size: 14px;
    color: #555;
}

@media (max-width: 768px) {
    .advantages-grid {
        grid-template-columns: 1fr;
    }
}
.otz-about {
    border-top: 1px solid #fff;
    text-align: center;
    font-size: 20px;
    color: #fff;
    animation: slideIn 1s ease-in-out;
}
.otz-about img {
    background-color: #fff;
    border-radius: 50%;
    width: 100px;
    height: 100px;
    transition: transform 0.3s;
}
.otz-about img:hover {
    transform: scale(1.05);
}
.otz1 {
    margin-bottom: 80px;
}

footer {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    max-width: 1200px;
    margin: 0 auto;
}

.contact-info {
    flex: 1;
    padding: 20px;
    color: #ffffff;
}

footer {
    border-top: 1px solid #fff;
    color: #fff; 
    padding: 20px; 
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    align-items: flex-start;
    max-width: 1200px;
    margin: 0 auto;
    width: 100%; /* растягиваем футер на всю ширину экрана */
    position: relative;
}

.contact-info {
    flex: 1;
    padding-right: 20px;
    font-family: 'Times New Roman', sans-serif;
}

form {
    flex: 2;
    background-color: #2c3e50;
    padding: 20px;
    border-radius: 5px;
    border: 1px solid #fff;
}

input,
textarea {
    margin-bottom: 15px;
    width: 100%;
    border: 1px solid #34495e;
    padding: 10px;
}

button {
    padding: 10px 15px;
    border: none;
    cursor: pointer;
    color: #fff;
    background-color: #3498db;
    border-radius: 5px;
    margin-right: 10px;
    cursor: pointer;
    transition: transform 0.3s ease, background-color 0.3s ease;
}

button:hover {
    background-color: #45a049; /* змінює колір фону */
    transform: scale(1.1); /* збільшує кнопку */
}

button[type="reset"] {
    background-color: #e74c3c; /* Красная кнопка сброса */
}

button[type="reset"]:hover {
    background-color: #45a049; /* змінює колір фону */
    transform: scale(1.1); /* збільшує кнопку */
}

form h1 {
    padding: 10px;
    text-align: center;
    font-family: 'Georgia', sans-serif;
}

h3 {
    margin: 10px 0;
}

label {
    display: block;
    margin-bottom: 5px;
}

.pfp {
    text-align: center;
    color: #000;
    width: 100%;
    margin-top: 20px;
    font-size: 20px;
    font-family: 'Georgia', sans-serif;
    margin-bottom: 1px;
}

.footground {
    background-image: url('https://media.istockphoto.com/id/162542504/photo/earth-sunrise-in-space.jpg?s=612x612&w=0&k=20&c=yOz6xe894yVDOtt29uFDybMbNyKdpW_4vOUUEkAlaEI=');
    background-size: cover;
    background-position: center;
    padding-top: 20px;
    padding-left: 60px;
    padding-right: 60px;
    padding-bottom: 10px;
}
  </style>
</head>

<body class="b1">
    <div class="header">
        <div class="contact-info">
            <p>+38(066) <strong>212 78 78</strong></p>
            <p>+38(063) <strong>212 87 87</strong></p>
        </div>
        <img src="https://seeklogo.com/images/J/jagermeister-logo-8324CD30F6-seeklogo.com.png" alt="Jagermeister logo" />
        <h1>Jagermeister</h1>
    </div>
    <div class="nav">
        <a href="#">Главная</a>
        <a href="#">Услуги</a>
        <a href="#">Купить</a>
        <a href="#">Отзывы</a>
    </div>
    <div class="content">
        <div class="box">
            <div clav>
                <h2>Jagermeister - путь к свободе!</h2>
                <p>Удачное решение всего!</p>
            </div>
            <img src="https://cdn-icons-png.flaticon.com/512/2111/2111883.png" alt="logo jag" />
        </div>
        <div class="box">
            <div>
                <h2>Jagermeister - Juggernaut</h2>
                <p>Для Доты и в Доте</p>
            </div>
            <img src="https://cdn-icons-png.flaticon.com/512/588/588267.png" alt="Juggernaut icon" />
        </div>
    </div>
</body>
<body class="b2">
    <section class="main-page-text">
        <div class="container">
            <div class="item">
                <img src="D:\code projects\verstka\Без имени-1.png" alt="jag1" />
                <div class="title">1 факт</div>
                <div class="description">
                    Оригинальный рецепт остаётся неизменным с момента создания.
                </div>
            </div>
            <div class="item">
                <img src="D:\code projects\verstka\asdfasf.png" alt="jag2" />
                <div class="title">2 факт</div>
                <div class="description">
                    Сбалансированный вкус с горько-сладкими нотками.
                </div>
            </div>
        </div>
    </section>
    <div class="about-company">
        <h1>О напитке</h1>
        <p>Состоит из 56 различных трав, специй, кореньев и фруктов.<br>
            Фирменная тёмно-зелёная бутылка с винтажным дизайном и яркой этикеткой.<br>
            Дизайн отражает идею загадочного леса и природы, что подчеркивает натуральные ингредиенты напитка.
        </p>
    </div>    
</body>
<body class="b3">
    <div class="whyJback">
        <div class="whyJ">
            <h1>Почему именно Ягерь?</h1>
            <div class="advantages-grid">
                <div class="advantage-item">
                    <div class="number">1</div>
                    <div class="title">Преимущество 1</div>
                    <div class="description">Можно пить как в чистом виде, так и в составе коктейлей.</div>
                </div>
                <div class="advantage-item">
                    <div class="number">2</div>
                    <div class="title">Преимущество 2</div>
                    <div class="description">Это один из немногих ликеров, который сочетает сладость, горечь и пряные ноты</div>
                </div>
                <div class="advantage-item">
                    <div class="number">3</div>
                    <div class="title">Преимущество 3</div>
                    <div class="description">Его ценят как на вечеринках, так и в барах за его аутентичность и узнаваемость.</div>
                </div>
                <div class="advantage-item">
                    <div class="number">4</div>
                    <div class="title">Преимущество 4</div>
                    <div class="description">Бренд был создан в 1934 году в Германии и имеет богатую историю и наследие.</div>
                </div>
                <div class="advantage-item">
                    <div class="number">5</div>
                    <div class="title">Преимущество 5</div>
                    <div class="description">Особенный вкус, непохожий на другие напитки</div>
                </div>
                <div class="advantage-item">
                    <div class="number">6</div>
                    <div class="title">Преимущество 6</div>
                    <div class="description">Традиционно подают ледяным.</div>
                </div>
            </div>
        </div>
        <div class="otz-about">
            <h1>Отзывы наших клиентов</h1>
            <div class="otz1">
                <img src="https://cdn2.iconfinder.com/data/icons/icontober/64/Inkcontober_Mask_Juggernaut-512.png" alt="otzJ">
                <p><strong>"Jägermeister</strong> — это уникальный напиток, который действительно выделяется своим вкусом и стилем. Его насыщенный аромат и сложный вкус с нотами трав, кореньев и специй создают впечатление многослойности, которая раскрывается с каждым глотком. Особенно хорошо Jägermeister идет ледяным, как это и рекомендует производитель — холод усиливает его пряные ноты и делает вкус еще более освежающим."</p>
            </div>
            <div class="otz2">
                <img src="https://liquipedia.net/commons/images/thumb/3/3f/Natus_Vincere_2021_lightmode.png/600px-Natus_Vincere_2021_lightmode.png" alt="otzJ">
                <p>"Этот ликер не похож на другие крепкие напитки, и, возможно, поэтому у него такие преданные поклонники по всему миру. Он хорош как сам по себе, так и в составе коктейлей, добавляя глубину и необычность в каждый напиток. Приятно видеть, что <strong>Jägermeister</strong> продолжает сохранять свою аутентичность и качество, несмотря на свою популярность. Этот напиток идеально подходит для тех, кто ищет что-то оригинальное и смелое."</p>
            </div>
        </div>
    </div>   
    <div class="footground">
        <footer>
            <div class="contact-info">
                <h1>Наши контакты</h1>
                <h3 class="info"><strong>Телефон:</strong><br>
                    +38(066) 212 78 78</h3>
                <h3 class="info"><strong>Почта:</strong><br>
                    bagnenkojugger2024@gmail.com</h3>
            </div>
            <form>
                <label for="name">Имя</label><br>
                <input type="text" id="name"><br>
                <label for="name">Email</label><br>
                <input type="email" id="email"><br>
                <label for="message">Сообщение</label><br>
                <textarea id="message" rows="4" required></textarea><br>
                <button type="submit" id="button1">Отправить</button>
                <button type="reset" id="button2">Сбросить</button>
            </form>
            <p class="pfp">&copy; Jagermeister</p>
        </footer>    
    </div>
</body>
</html>
