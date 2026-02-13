<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>إلى طمطم ❤️</title>
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;700&family=Amiri:ital@1&display=swap" rel="stylesheet">
    <style>
        :root { --main-pink: #fce4ec; --dark-pink: #ad1457; --accent-pink: #d81b60; }
        body { background-color: var(--main-pink); font-family: 'Cairo', sans-serif; margin: 0; display: flex; justify-content: center; align-items: center; min-height: 100vh; color: #4a4a4a; overflow-x: hidden; }
        
        #lock-screen { text-align: center; background: white; padding: 40px; border-radius: 30px; box-shadow: 0 10px 30px rgba(0,0,0,0.1); width: 85%; max-width: 350px; z-index: 1000; position: fixed; }
        .pass-input { width: 80%; padding: 12px; border: 2px solid var(--main-pink); border-radius: 15px; text-align: center; font-size: 1.2rem; outline: none; margin: 20px 0; }
        .unlock-btn { background: var(--accent-pink); color: white; border: none; padding: 10px 30px; border-radius: 20px; cursor: pointer; font-weight: bold; width: 100%; }

        #main-content { display: none; width: 100%; max-width: 500px; padding: 20px; animation: fadeIn 1.5s; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(20px); } to { opacity: 1; transform: translateY(0); } }

        .card { background: white; border-radius: 25px; padding: 20px; margin-bottom: 25px; box-shadow: 0 8px 15px rgba(0,0,0,0.05); border: 1px solid #f8bbd0; text-align: center; }
        h2 { color: var(--dark-pink); font-family: 'Amiri', serif; margin-bottom: 15px; }
        
        /* الصور تظهر كاملة بدون أي قص أو زووم */
        .special-photo { width: 100%; height: auto; border-radius: 10px; margin-bottom: 10px; border: 1px solid #eee; display: block; }
        .photo-caption { font-size: 1.1rem; color: var(--dark-pink); font-weight: bold; margin-bottom: 25px; display: block; }

        .timer-box { background: #fdf2f5; padding: 15px; border-radius: 15px; margin: 10px 0; border: 1px solid #fce4ec; }
        .timer-num { display: block; font-weight: bold; font-size: 2.5rem; color: var(--accent-pink); }

        .timeline-item { position: relative; padding-right: 25px; border-right: 3px solid #f8bbd0; margin-bottom: 25px; text-align: right; }
        .timeline-item::after { content: '🌸'; position: absolute; right: -13px; top: 0; background: var(--main-pink); border-radius: 50%; }

        .love-letter { line-height: 1.8; font-size: 1.1rem; text-align: center; white-space: pre-line; }
        .footer-btn { background: var(--accent-pink); color: white; border: none; padding: 15px 40px; border-radius: 30px; width: 100%; font-size: 1.1rem; margin-top: 20px; box-shadow: 0 5px 15px rgba(216, 27, 96, 0.3); font-weight: bold; }
        
        @keyframes beat { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.1); } }
    </style>
</head>
<body>

    <div id="player" style="display:none;"></div>

    <div id="lock-screen">
        <div style="font-size: 50px;">🔒</div>
        <h2 style="margin-top: 10px;">مكاننا الخاص</h2>
        <p>اكتبي تاريخ ميلادك عشان تدخلي ❤️</p>
        <input type="text" id="password" class="pass-input" placeholder="يوم/شهر">
        <br>
        <button class="unlock-btn" onclick="checkPassword()">فتح القفل</button>
        <p id="error-msg" style="color: red; font-size: 0.8rem; display: none; margin-top: 10px;">الباسوورد غلط يا طمطم ركزي 😉</p>
    </div>

    <div id="main-content">
        <div class="card">
            <div style="font-size: 40px; animation: beat 1s infinite;">❤️</div>
            <h2>إلى طمطم</h2>
            <p>كل ثانية معاكي هي بداية قصة حب جديدة</p>
        </div>

        <div class="card">
            <h3>⏱️ بقالنا مع بعض</h3>
            <div class="timer-box">
                <span class="timer-num">452</span>
                <span>يوم من الضحك والحب والسند</span>
            </div>
            <p style="font-size: 0.9rem; color: #888;">منذ: 17 نوفمبر 2024</p>
        </div>

        <div class="card">
            <h3>حكاياتنا بالصور 📸</h3>
            
            <img src="https://i.ibb.co/fdGpHH5q/image.jpg" class="special-photo">
            <span class="photo-caption">اول بحبك قولناها لبعض 🤗❤️</span>
            
            <hr style="border: 0.5px solid #fce4ec; margin: 25px 0;">

            <img src="https://i.ibb.co/8gspTrMC/image.jpg" class="special-photo">
            <span class="photo-caption">اول خناقة وصلح بينا 🤗❤️</span>
        </div>

        <div class="card">
            <h2>Love Letter 💌</h2>
            <div class="love-letter">
                عايز أقول ليكي كلمتين يا طمطم حاجة يمكن ما تتخيليهاش
                انتي اكتر إنسانة لمست قلبي من غير ما تحسي كل مرة بتكلم معاكي بحس إني بجري من تعب الدنيا كلها وأجي لصوتك هو المكان اللي برتاح فيه
                
                بحس إني لقيت نفسي فيكي في كل تفاصيلك بتخليني أصدق إن في حب حقيقي لسه قاعد
                
                🌸 ليكي انتي الأمان كله
                💖 بحبك لأنك بتفهميني من غير ما أتكلم
                🌸 بتطمنيني من غير ما أشرح
                💖 بحبك لأنك دايما السبب في ضحكتي
                🌸 علمتيني أحس من غير خوف وأحب وأنا مطمنة
            </div>
        </div>

        <div class="card">
            <h3>ذكرياتنا 📖</h3>
            <div class="timeline-item">
                <strong>أول يوم (17/11/2024)</strong>
                <p>البداية اللي خلت لحياتي طعم تاني خالص</p>
            </div>
            <div class="timeline-item">
                <strong>عيد ميلاد أغلى الناس (15/6)</strong>
                <p>يوم ميلاد طمطم اليوم اللي اتولدت فيه الضحكة اللي بتنور حياتي</p>
            </div>
            <div class="timeline-item">
                <strong>أول خروجة</strong>
                <p>عند عبير ساعتها كنت مش عاوز ابص لحاجة غير عينك 🥺❤️</p>
            </div>
        </div>

        <button class="footer-btn" onclick="alert('كل سنة وأنتي حبيبتي يا طمطم ❤️')">Happy Valentine My Queen 👑</button>
    </div>

    <script src="https://www.youtube.com/iframe_api"></script>
    <script>
        var player;
        function onYouTubeIframeAPIReady() {
            player = new YT.Player('player', {
                height: '0', width: '0', videoId: 'Sh24Dnb_Elw',
                playerVars: { 'autoplay': 0, 'controls': 0, 'enablejsapi': 1 },
            });
        }
        function checkPassword() {
            const pass = document.getElementById('password').value;
            if (pass === "15/6") {
                document.getElementById('lock-screen').style.display = 'none';
                document.getElementById('main-content').style.display = 'block';
                if (player && typeof player.playVideo === 'function') {
                    player.playVideo();
                }
            } else {
                document.getElementById('error-msg').style.display = 'block';
            }
        }
    </script>
</body>
</html>
