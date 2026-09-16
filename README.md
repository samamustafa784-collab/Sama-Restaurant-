<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sama Restaurant - مطعم سما</title>
    <style>
        /* إعدادات الخطوط والألوان الأساسية */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f9f9f9; /* خلفية هادئة مريحة للعين */
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            padding: 20px;
        }

        /* كارت الموقع الرئيسي */
        .container {
            background-color: #ffffff;
            width: 100%;
            max-width: 450px; /* مقاس مثالي لشاشات الموبايل والتابلت */
            border-radius: 15px;
            box-shadow: 0 8px 24px rgba(0, 0, 0, 0.1); /* ظل خفيف يعطي احترافية */
            overflow: hidden;
            border-top: 8px solid #6f42c1; /* لمسة باللون البنفسجي المفضل عندك */
        }

        /* الهيدر (العنوان الرئيسي) */
        .header {
            background-color: #f1f0ff;
            padding: 25px;
            text-align: center;
            border-bottom: 2px solid #e2e0ff;
        }

        .header h1 {
            color: #6f42c1;
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 5px;
        }

        /* محتوى الصفحة الرئيسي */
        .content {
            padding: 25px;
        }

        .welcome-text {
            font-size: 18px;
            color: #555;
            text-align: center;
            margin-bottom: 25px;
            line-height: 1.6;
        }

        /* قائمة الطعام (المنيو) */
        .menu-section {
            margin-bottom: 25px;
        }

        .menu-title {
            font-size: 16px;
            color: #6f42c1;
            margin-bottom: 12px;
            font-weight: 600;
        }

        .menu-list {
            list-style: none;
        }

        .menu-item {
            background-color: #f8f9fa;
            padding: 12px 15px;
            margin-bottom: 8px;
            border-radius: 8px;
            border-right: 4px solid #e11d48; /* لون وردي/أحمر مميز للمنيو */
            display: flex;
            justify-content: space-between;
            font-weight: 500;
        }

        /* زر الطلب والتواصل والتواصل الاجتماعي */
        .order-section {
            text-align: center;
            margin-top: 15px;
            padding-top: 15px;
            border-top: 1px dashed #ddd;
        }

        .order-text {
            font-size: 14px;
            color: #666;
            margin-bottom: 12px;
        }

        /* تحويل الحساب لزرار تفاعلي احترافي */
        .btn-order {
            display: inline-block;
            background-color: #6f42c1;
            color: #ffffff;
            text-decoration: none;
            padding: 12px 25px;
            border-radius: 25px;
            font-weight: bold;
            font-size: 15px;
            transition: all 0.3s ease;
            box-shadow: 0 4px 12px rgba(111, 66, 193, 0.3);
        }

        /* تأثير عند تحريك الماوس أو اللمس */
        .btn-order:hover {
            background-color: #5a32a3;
            transform: translateY(-2px);
            box-shadow: 0 6px 15px rgba(111, 66, 193, 0.4);
        }

        /* قسم معلومات إضافية بدل الكلام العشوائي */
        .footer-info {
            margin-top: 20px;
            font-size: 12px;
            color: #888;
            text-align: center;
            line-height: 1.5;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- الهيدر -->
        <div class="header">
            <h1>Sama Restaurant</h1>
        </div>

        <!-- المحتوى الرئيسي -->
        <div class="content">
            <p class="welcome-text">مرحباً بكم في مطعم سما! يسعدنا تقديم أشهى المأكولات والحلويات المصنوعة بكل حب وتفاني لتنال إعجابكم.</p>

            <!-- المنيو -->
            <div class="menu-section">
                <h3 class="menu-title">تصفح قائمة الطعام المتميزة:</h3>
                <ul class="menu-list">
                    <li class="menu-item">
                        <span>وجبات باردة (Cold Meals)</span>
                        <span style="color: #6f42c1;">★</span>
                    </li>
                    <li class="menu-item">
                        <span>حلويات فاخرة (Desserts)</span>
                        <span style="color: #6f42c1;">★</span>
                    </li>
                </ul>
            </div>

            <!-- قسم الطلبات وتحويل الرابط لزرار -->
            <div class="order-section">
                <p class="order-text">يمكنكم طلب جميع المأكولات والوجبات بسهولة من هنا:</p>
                <a href="#" class="btn-order">@Sama Restaurant</a>
            </div>

            <!-- معلومات حقيقية بديلة للكلام العشوائي القديم -->
            <div class="footer-info">
                <p>📍 العنوان: مريوطية الهرم - بجوار معهد الفراعنة</p>
                <p>⏰ مواعيد العمل: يومياً من 12 ظهراً حتى 12 منتصف الليل</p>
                <p>مرحباً بكم في أي وقت!</p>
            </div>
        </div>
    </div>

</body>
</html>

