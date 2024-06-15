<!DOCTYPE html>
<html lang="zh-Hant">

<head>
    <title>Ramen Damn</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
    <link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Noto+Serif+JP|Sawarabi+Mincho&display=swap">
    <style>
        body {
            font-family: 'Sawarabi Mincho', serif;
            background-color: #FFE4C4;
            color: #333333;
        }
        
        h1,
        h2,
        h3,
        h4,
        h5,
        h6 {
            font-family: 'Noto Serif JP', serif;
        }
        
        .w3-bar {
            background-color: #FF4500;
        }
        
        .w3-bar a {
            color: #FFFFFF !important;
        }
        
        .w3-button {
            background-color: #FFD700;
            color: #333333;
        }
        
        .w3-button:hover {
            background-color: #FF4500;
            color: #FFFFFF !important;
        }
        
        .w3-section {
            background-color: #FFFFFF;
            margin-bottom: 16px;
        }
        
        .w3-container {
            background-color: #FFFFFF;
        }
        
        .menu-item {
            margin-bottom: 15px;
        }
    </style>
</head>

<body>

    <!-- Sidebar (hidden by default) -->
    <nav class="w3-sidebar w3-bar-block w3-card w3-top w3-xlarge w3-animate-left" style="display:none;z-index:2;width:40%;min-width:300px" id="mySidebar">
        <a href="javascript:void(0)" onclick="w3_close()" class="w3-bar-item w3-button">Close Menu</a>
        <a href="#food" onclick="w3_close()" class="w3-bar-item w3-button">菜單</a>
        <a href="#about" onclick="w3_close()" class="w3-bar-item w3-button">關於我們</a>
        <a href="#contact" onclick="w3_close()" class="w3-bar-item w3-button">聯絡我們</a>
    </nav>

    <!-- Top menu -->
    <div class="w3-top">
        <div class="w3-white w3-xlarge" style="max-width:1200px;margin:auto">
            <div class="w3-button w3-padding-16 w3-left" onclick="w3_open()">☰</div>
            <div class="w3-right w3-padding-16">麵山</div>
            <div class="w3-center w3-padding-16">Ramen Damn</div>
        </div>
    </div>

    <!-- !PAGE CONTENT! -->
    <div class="w3-main w3-content w3-padding" style="max-width:1200px;margin-top:100px">

        <!-- First Photo Grid-->
        <div class="w3-row-padding w3-padding-16 w3-center" id="food">
            <div class="w3-quarter">
                <img src="ramen_header.jpg" alt="豚骨拉麵" style="width:100%">
                <h3>豚骨拉麵</h3>
                <p>濃郁豚骨湯底搭配嫩滑豬肉片 $170元</p>
            </div>
            <div class="w3-quarter">
                <img src="醬油拉麵.webp" alt="醬油拉麵" style="width:100%">
                <h3>醬油拉麵</h3>
                <p>經典醬油湯底，口感清爽 $150元</p>
            </div>
            <div class="w3-quarter">
                <img src="味噌.jpg" alt="味噌拉麵" style="width:100%">
                <h3>味噌拉麵</h3>
                <p>香濃味噌湯底，營養豐富 $160元</p>
            </div>
            <div class="w3-quarter">
                <img src="鹽味.jpg" alt="鹽味拉麵" style="width:100%">
                <h3>鹽味拉麵</h3>
                <p>清淡鹽味湯底，適合夏天享用 $140元</p>
            </div>
        </div>

        <!-- Second Photo Grid-->
        <div class="w3-row-padding w3-padding-16 w3-center">
            <div class="w3-quarter">
                <img src="海鮮.jpg" alt="海鮮拉麵" style="width:100%">
                <h3>海鮮拉麵</h3>
                <p>豐富的海鮮配料，味美鮮香 $200元</p>
            </div>
            <div class="w3-quarter">
                <img src="玉子燒.jpg" alt="玉子燒" style="width:100%">
                <h3>玉子燒</h3>
                <p>日式煎蛋捲 $80元</p>
            </div>
            <div class="w3-quarter">
                <img src="糯米糰子.jpg" alt="糯米糰子" style="width:100%">
                <h3>糯米糰子</h3>
                <p>傳統日式糯米糰子 $50元</p>
            </div>
            <div class="w3-quarter">
                <img src="雞肉串.jpg" alt="雞肉串" style="width:100%">
                <h3>雞肉串</h3>
                <p>炭火燒烤雞肉串 $100元</p>
            </div>
        </div>

        <!-- Pagination -->


        <hr id="about">

        <!-- About Section -->
        <div class="w3-container w3-padding-32 w3-center">
            <h3>關於我們</h3><br>
            <img src="ramen_about.jpg" alt="拉麵師傅" class="w3-image" style="display:block;margin:auto" width="800" height="533">
            <div class="w3-padding-32">
                <h4><b>麵山</b></h4>
                <h6><i>對真正美食的激情</i></h6>
                <p>拉麵 Damn 自2005年以來一直致力於提供最地道的日式拉麵。我們選用最新鮮的食材，配以秘制湯底，帶給您無與倫比的味覺享受。歡迎光臨，品味我們的傳統和熱情。</p>
                <p>我們的拉麵店不僅提供經典的豚骨拉麵、醬油拉麵、味噌拉麵，還有各種創新的料理選擇，讓您每次光臨都有不同的驚喜。</p>
            </div>
        </div>
        <hr>

        <!-- Contact Section -->
        <div class="w3-container w3-padding-64" id="contact">
            <h1>聯絡我們</h1><br>
            <p>我們提供全方位的餐飲服務，無論大小活動。我們了解您的需求，並將根據
                <p>我們提供全方位的餐飲服務，無論大小活動。我們了解您的需求，並將根據您的喜好和預算提供最佳解決方案。請填寫以下表格，我們將盡快與您聯繫。</p>
                <form action="/submit_form" method="POST" class="w3-container">
                    <p><input class="w3-input" type="text" placeholder="姓名" required name="Name"></p>
                    <p><input class="w3-input" type="email" placeholder="電子郵件" required name="Email"></p>
                    <p><input class="w3-input" type="text" placeholder="主題" required name="Subject"></p>
                    <p><textarea class="w3-input" placeholder="訊息內容" required name="Message"></textarea></p>
                    <p><button class="w3-button w3-black" type="submit">發送訊息</button></p>
                </form>
        </div>

        <!-- Footer -->
        <footer class="w3-row-padding w3-padding-32">
            <div class="w3-third">
                <h3>聯絡資訊</h3>
                <p>地址：彰化縣福興鄉秀厝村福三路三段585號</p>
                <p>電話：+886 0932576899</p>
                <p>Email：zhenlinliang26@gmail.com</p>
            </div>

            <div class="w3-third">
                <h3>最新消息</h3>
                <ul class="w3-ul w3-hoverable">
                    <li class="w3-padding-16">

                        <span class="w3-large">拉麵 Damn 開業</span><br>
                        <span>歡迎光臨我們的新店！</span>
                    </li>
                    <li class="w3-padding-16">

                        <span class="w3-large">新鮮食材到貨</span><br>
                        <span>我們使用最新鮮的食材，為您提供最佳品質。</span>
                    </li>
                </ul>
            </div>

            <div class="w3-third">
                <h3>關注我們</h3>
                <p>
                    <a href="#" class="w3-bar-item w3-button"><i class="fa fa-facebook-official"></i> Facebook</a>
                    <a href="#" class="w3-bar-item w3-button"><i class="fa fa-instagram"></i> Instagram</a>
                    <a href="#" class="w3-bar-item w3-button"><i class="fa fa-twitter"></i> Twitter</a>
                </p>
            </div>
        </footer>

        <!-- End page content -->
    </div>

    <script>
        // Script to open and close sidebar
        function w3_open() {
            document.getElementById("mySidebar").style.display = "block";
        }

        function w3_close() {
            document.getElementById("mySidebar").style.display = "none";
        }
    </script>

</body>

</html>
