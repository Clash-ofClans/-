<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>مولد حسابات كلاش السري</title>
    <!-- تحميل Tailwind CSS لتحقيق تصميم عصري وجذاب -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* تطبيق خط Tajawal مع خلفية ذات طابع حجري/ملكي */
        @import url('https://fonts.googleapis.com/css2?family=Tajawal:wght@400;700;800;900&display=swap');
        body {
            font-family: 'Tajawal', sans-serif;
            /* خلفية داكنة ذات طابع حجري (بديل للصورة) */
            background-color: #282421; 
            background-image: linear-gradient(145deg, #333 10%, #1a1a1a 90%);
        }
        .clash-card {
            background-color: #424242; /* لون داكن كالدرع */
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.5), 0 0 10px #FFD700; /* ظل ذهبي */
            border: 4px solid #FFD700; /* إطار ذهبي */
        }
        /* تم تغيير لون الزر الأساسي إلى الأزرق الرسمي */
        .clash-button {
            background-color: #2563eb; /* أزرق رسمي - Blue-600 */
            box-shadow: 0 4px #1e40af; /* ظل أزرق داكن */
            transition: all 0.2s ease-in-out;
        }
        .clash-button:hover {
            background-color: #3b82f6; /* أزرق أفتح عند التحويم */
            box-shadow: 0 2px #1e40af;
            transform: translateY(-2px);
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen p-4">

    <!-- الحاوية الرئيسية والبطاقة بتصميم كلاش -->
    <div class="w-full max-w-lg p-8 clash-card">

        <!-- الأيقونة الملكية (كلاش) -->
        <div class="text-center mb-6">
            <span class="text-6xl" role="img" aria-label="Crown and Sword" style="filter: drop-shadow(0 0 5px #FFD700);">👑⚔️</span>
        </div>

        <!-- العنوان الرئيسي -->
        <h1 class="text-3xl font-black text-center text-yellow-300 mb-2 border-b-2 border-yellow-500 pb-3">
            🔥 بوابة الدخول لحسابات Clash المجانية 🔥
        </h1>
        <p class="text-center text-gray-300 mb-8 font-medium">
            اضغط على الزر الناري للانتقال فوراً لصفحة الحصول على الموارد والحسابات!
        </p>

        <!-- منطقة الزر لإنشاء الحساب (الذي يعمل كرابط مباشر) -->
        <div id="action-area" class="relative group transition duration-500">
            <!-- الزر الآن هو رابط مباشر (<a>) -->
            <a 
                id="direct-access-link"
                href="https://www.cloudskillsboost.google/focuses/86501?catalog_rank=%7B%22rank%22%3A2%2C%22num_filters%22%3A0%2C%22has_search%22%3Atrue%7D&parent=catalog&search_id=53728432" 
                target="_blank" 
                rel="noopener noreferrer" 
                class="w-full block text-center p-6 text-white font-extrabold text-2xl rounded-xl transition clash-button transform hover:-translate-y-1 hover:shadow-2xl"
            >
                <span class="mr-2">💥</span> انقر للدخول إلى منطقة الحسابات السرية!
            </a>
        </div>
        
        <!-- صندوق إرشادات الدخول (يشرح "كيف يشتغل الحساب") -->
        <div id="instruction-area" class="mt-10 p-5 bg-red-900/40 rounded-xl border-2 border-red-500">
            <h2 class="text-xl font-black text-center text-yellow-300 mb-3 flex items-center justify-center">
                <span class="mr-2 text-3xl">📜</span> كيفية الحصول على الحساب الشغال 100%
            </h2>
            <ul class="list-none space-y-3 text-gray-200">
                <li class="flex items-start">
                    <span class="text-green-400 font-bold ml-2 mt-1">1.</span>
                    <p>بعد الضغط على الزر، سيتم توجيهك إلى **مركز التدريب** (مركز الموارد). هذا هو المكان الذي يقوم بـ "توليد الحسابات" بالفعل.</p>
                </li>
                <li class="flex items-start">
                    <span class="text-green-400 font-bold ml-2 mt-1">2.</span>
                    <p>في تلك الصفحة، ابحث عن زر **"بدء المعمل"** (أو Start Lab). عند الضغط عليه، ستقوم المنصة بتوفير **حساب مستخدم وكلمة مرور مؤقتين وشغالين 100%**.</p>
                </li>
                <li class="flex items-start">
                    <span class="text-green-400 font-bold ml-2 mt-1">3.</span>
                    <p>استخدم بيانات الدخول المؤقتة هذه للوصول إلى بيئة اللعب (أو المعمل) المخصصة لك. هذه البيانات هي الحساب "المجاني" الذي تبحث عنه.</p>
                </li>
            </ul>
        </div>
        
    </div>
</body>
</html>
