
<html lang="ar">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>محمد نقوان</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 20px;
            background-color:#eaeaffa2 ;
        }

        h1 {
            color: #2c3e50;
            text-align: center;
            border-bottom: 2px solid #3498db;
            padding-bottom: 10px;
        }
 
           .marquee-container {
            overflow: hidden;
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            margin: 20px auto;
            position: relative;
            direction: ltr; 
        }

        .marquee-content {
            display: inline-block;
            white-space: nowrap;
            animation: marquee 15s linear infinite;
            padding-right: 100%; 
        }

        @keyframes marquee {
            0% { transform: translateX(-100%); }
            100% { transform: translateX(100%); }
        }

        nav ul {
            list-style: none;
            padding: 0;
            display: flex;
            justify-content: center;
            gap: 30px;
            background-color: #3498db;
            padding: 15px;
            border-radius: 5px;
        }

        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav a:hover {
            color: #f1c40f;
        }

       
        .avatar {
            display: block;
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 20px auto;
            border: 3px solid #3498db;
        }
    </style>
</head>
<body>
    <h1>الطالب محمد أنس نقوان</h1>

    <img src="/storage/emulated/0/اعطني صورة مكتب لمبرمج عليها لوحة مكتوب عليها المهندس محمد نقوان_20250419_233846_٠٠٠٠.jpg" alt="صورتي الشخصية" class="avatar">

    <div class="marquee-container">
        <div class="marquee-content">
                                                                                  طالب هندسة معلوماتية احب مجالي واحب التصميم وأعشق الابداع ولدي شغف بذالك     
        </div>
    </div>

    <nav>
        <ul>
            <li><a href="#">من أنا</a></li>
            <li><a href="#">استفسار</a></li>
            <li><a href="#">الرئيسية</a></li>
        </ul>
    </nav>
</body>
</html>
