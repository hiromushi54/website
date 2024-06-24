<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>農産物販売ページ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f8f8;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        header, footer {
            text-align: center;
            padding: 10px 0;
            background-color: #4CAF50;
            color: white;
        }
        h1 {
            color: #333;
        }
        .product-list {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }
        .product {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 10px;
            margin: 10px;
            width: calc(33% - 40px);
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            border-bottom: 1px solid #ddd;
            margin-bottom: 10px;
        }
        .product h2 {
            font-size: 1.2em;
            color: #4CAF50;
        }
        .product p {
            color: #555;
        }
        .contact, .order {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>農産物販売ページ</h1>
    </header>
    <div class="container">
        <section class="product-list">
            <div class="product">
                <img src="apple.jpg" alt="リンゴ">
                <h2>リンゴ</h2>
                <p>新鮮なリンゴ、1kg ¥500</p>
            </div>
            <div class="product">
                <img src="carrot.jpg" alt="にんじん">
                <h2>にんじん</h2>
                <p>有機栽培のにんじん、1kg ¥300</p>
            </div>
            <!-- 他の商品をここに追加 -->
        </section>
        <section class="order">
            <h2>購入方法</h2>
            <p>オンライン注文、またはお電話でご注文ください。</p>
            <p>支払い方法：クレジットカード、銀行振込</p>
        </section>
        <section class="contact">
            <h2>お問い合わせ</h2>
            <p>電話番号: 123-456-7890</p>
            <p>メール: info@example.com</p>
            <p>所在地: 〒123-4567 東京都渋谷区</p>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 農産物販売</p>
    </footer>
</body>
</html>
