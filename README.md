<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Untukmu Langitku</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,400&family=Montserrat:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * { box-sizing: border-box; }
        
        body {
            margin: 0; padding: 0;
            background-color: #010614;
            font-family: 'Montserrat', sans-serif;
            color: #ffffff;
            display: flex; justify-content: center;
            overflow-x: hidden;
            background-image: url('https://www.transparenttextures.com/patterns/dark-dotted.png');
        }

        .wrapper {
            width: 100%; max-width: 450px;
            background: rgba(2, 10, 30, 0.95);
            min-height: 100vh;
            position: relative;
            box-shadow: 0 0 40px rgba(0,0,0,0.5);
            padding-bottom: 120px;
        }

        .header {
            background: linear-gradient(180deg, #1a3a5f 0%, #010614 100%);
            padding: 60px 30px;
            position: relative;
            clip-path: polygon(0 0, 100% 0, 100% 88%, 85% 98%, 70% 88%, 55% 98%, 40% 88%, 25% 98%, 0 88%);
        }

        .header h1 { font-family: 'Playfair Display', serif; font-size: 28px; margin: 0; }
        .header p { font-family: 'Playfair Display', serif; font-style: italic; font-size: 18px; opacity: 0.9; margin: 5px 0 0 0; color: #b5ccf1; }

        .title-section { text-align: right; padding: 30px 30px 10px 30px; }
        .title-section h2 { font-family: 'Playfair Display', serif; font-size: 55px; line-height: 0.9; margin: 0; font-weight: bold; }

        .message-card {
            background: rgba(255, 255, 255, 0.08);
            margin: 0 25px 20px 25px;
            padding: 20px;
            border-radius: 15px;
            border: 1px solid rgba(255, 255, 255, 0.1);
        }

        .message-card h3 {
            font-size: 16px; font-weight: 600; color: #b5ccf1;
            margin-top: 0; margin-bottom: 10px;
            border-left: 4px solid #ffffff; padding-left: 10px;
            text-transform: uppercase; letter-spacing: 1px;
        }

        .message-card p { font-size: 13px; line-height: 1.6; margin: 0; text-align: justify; color: #f0f0f0; }

        .footer {
            background-color: #1a3a5f;
            padding: 50px 20px 30px 20px;
            text-align: center;
            position: absolute; bottom: 0; width: 100%;
            clip-path: polygon(0 20%, 15% 0%, 30% 20%, 45% 0%, 60% 20%, 75% 0%, 90% 20%, 100% 0%, 100% 100%, 0 100%);
        }

        .footer p { font-size: 14px; font-weight: 600; margin: 0; font-style: italic; }
        
        .fade-in { animation: fadeIn 2s ease-in; }
        @keyframes fadeIn { from { opacity: 0; } to { opacity: 1; } }
    </style>
</head>
<body>

    <div class="wrapper fade-in">
        <div class="header">
            <h1>Untukmu Langitku</h1>
            <p>Giselle Danisha Putri</p>
        </div>

        <div class="title-section">
            <h2>Happy<br>Birthday</h2>
        </div>

        <div class="message-card">
            <h3>Barakallah fii umrik</h3>
            <p>Hari ini, di hari bertambahnya usiamu, aku bersyukur kamu masih ada di sini. Maaf saja nggak akan pernah cukup untuk menghapus luka yang pernah aku buat, tapi aku berjanji untuk terus menebusnya dengan menjadi versi terbaikku.</p>
        </div>

        <div class="message-card">
            <h3>Kesadaran & Kesempatan</h3>
            <p>Aku sadar betapa buruknya kelakuanku dulu. Tapi kamu tetap memilih bertahan. Kesempatan ini nggak akan aku sia-siakan lagi. Kamu adalah amanah terindah yang akan aku jaga.</p>
        </div>

        <div class="message-card">
            <h3>Tentang Jarak & Kado</h3>
            <p>Maaf ya, di hari spesialmu ini aku belum bisa hadir secara langsung untuk memberikan kado atau sekadar merayakannya di sampingmu. Tapi percayalah, kado terbesarku saat ini adalah doa-doa yang tidak putus kusebut di setiap sujudku untuk kebahagiaanmu.</p>
        </div>

        <div class="message-card">
            <h3>Doa & Janji</h3>
            <p>Semoga Allah SWT selalu menjaga hatimu. Aku berjanji akan jadi laki-laki yang jujur dan setia, hingga tiba saatnya aku berdiri di depan orang tuamu dengan penuh integritas.</p>
        </div>

        <div class="message-card">
            <h3>Lahir Kembali</h3>
            <p>Momen ini bukan cuma soal umurmu, tapi soal hubungan kita yang lahir kembali. Aku berjanji pada diriku sendiri untuk terus membuktikan bahwa aku layak untukmu.</p>
        </div>

        <div class="message-card">
            <h3>Masa Depan</h3>
            <p>Aku memohon umur yang berkah, kesehatan, dan rezeki yang lancar agar aku bisa segera membawamu ke pelaminan. Aku ingin kita menua bersama dalam ketaatan. <i>I love you, Langitku.</i></p>
        </div>

        <div class="message-card">
            <h3>Terima Kasih</h3>
            <p>Terima kasih sudah lahir ke dunia dan terima kasih sudah memilih untuk tinggal. Aku tidak janji dunia akan selalu mudah, tapi aku janji kamu tidak akan pernah menghadapinya sendirian lagi.</p>
        </div>

        <div class="footer">
            <p>Happy birthday, my visionary girl.<br>I love you more than words can say.</p>
        </div>
    </div>

</body>
</html>
