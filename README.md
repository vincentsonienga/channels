<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>

<title>LEGIThea Channels</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    background: linear-gradient(135deg,#020617,#0f172a,#111827);
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    padding:25px;
    color:white;
}

.container{
    width:100%;
    max-width:430px;
}

.header{
    text-align:center;
    margin-bottom:30px;
}

.header h1{
    font-size:34px;
    font-weight:700;
    background: linear-gradient(to right,#38bdf8,#22c55e);
    -webkit-background-clip:text;
    -webkit-text-fill-color:transparent;
}

.header p{
    color:#94a3b8;
    margin-top:8px;
    font-size:14px;
}

.card{
    position:relative;
    background: rgba(30,41,59,0.75);
    border:1px solid rgba(255,255,255,0.08);
    border-radius:24px;
    padding:25px 20px;
    margin-bottom:22px;
    backdrop-filter: blur(12px);
    overflow:hidden;
    transition:0.35s ease;
    box-shadow:0 10px 30px rgba(0,0,0,0.35);
    text-align:center;
}

.card:hover{
    transform:translateY(-6px);
    border-color:#38bdf8;
    box-shadow:0 15px 35px rgba(56,189,248,0.25);
}

.card::before{
    content:'';
    position:absolute;
    top:-50px;
    right:-50px;
    width:120px;
    height:120px;
    background:rgba(56,189,248,0.15);
    border-radius:50%;
}

.profile{
    width:95px;
    height:95px;
    border-radius:50%;
    object-fit:cover;
    border:4px solid rgba(255,255,255,0.12);
    margin-bottom:16px;
    box-shadow:0 0 20px rgba(56,189,248,0.35);
}

.card h2{
    font-size:22px;
    margin-bottom:10px;
}

.card p{
    color:#cbd5e1;
    font-size:14px;
    line-height:1.7;
}

.btn{
    display:inline-block;
    margin-top:18px;
    padding:12px 24px;
    border-radius:14px;
    text-decoration:none;
    color:white;
    font-weight:600;
    background: linear-gradient(to right,#06b6d4,#22c55e);
    transition:0.3s;
}

.btn:hover{
    transform:scale(1.06);
    opacity:0.92;
}

.footer{
    text-align:center;
    margin-top:18px;
    color:#64748b;
    font-size:13px;
}

</style>
</head>

<body>

<div class="container">

    <div class="header">
        <h1>📢 LEGIThea</h1>
        <p>Official Telegram Channels</p>
    </div>

    <!-- MAIN CHANNEL -->
    <div class="card">

        <img class="profile"
        src="https://t.me/i/userpic/320/LegitheaChannel.jpg"
        alt="Legithea Channel">

        <h2>📂 Legithea Channel</h2>

        <p>
            Official updates, latest files, announcements,
            drops, and exclusive LEGIThea content.
        </p>

        <a class="btn"
        href="https://t.me/LegitheaChannel"
        target="_blank">
        Join Channel
        </a>

    </div>

    <!-- MARKET -->
    <div class="card">

        <img class="profile"
        src="https://t.me/i/userpic/320/theamarketchannel.jpg"
        alt="Thea Market">

        <h2>🛒 Thea Market</h2>

        <p>
            Buy & sell accounts, gaming services,
            and trusted market offers.
        </p>

        <a class="btn"
        href="https://t.me/theamarketchannel"
        target="_blank">
        Visit Market
        </a>

    </div>

    <!-- VOUCHES -->
    <div class="card">

        <img class="profile"
        src="https://t.me/i/userpic/320/althealangmagandaaavouches.jpg"
        alt="Vouches">

        <h2>⭐ Vouches</h2>

        <p>
            Trusted customer feedbacks,
            successful transactions,
            and proof of legitimacy.
        </p>

        <a class="btn"
        href="https://t.me/althealangmagandaaavouches"
        target="_blank">
        View Vouches
        </a>

    </div>

    <div class="footer">
        © 2026 LEGIThea Community
    </div>

</div>

</body>
</html>
