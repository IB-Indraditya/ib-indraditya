<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&height=340&text=INDRADITYA&fontSize=70&fontAlignY=40&animation=twinkling&fontColor=7DF9FF&desc=AI%20FinTech%20Developer%20•%20Real%20Time%20Systems%20Engineer&descAlignY=68&descSize=22&descColor=B6FFFF&stroke=00F5FF&strokeWidth=2.5&color=0:020617,15:031826,35:05293D,55:0B3B52,75:0EA5E9,90:38BDF8,100:7DF9FF"/>

<img src="https://readme-typing-svg.herokuapp.com?font=Orbitron&size=24&duration=1800&pause=700&color=7DF9FF&center=true&vCenter=true&width=950&lines=%E2%9A%A1+DARK+TEAL+CORE+ONLINE;%F0%9F%93%88+REAL+TIME+TRADING+SYSTEMS;%F0%9F%9A%80+AI+FINTECH+ENGINEER;%F0%9F%92%BB+FULL+STACK+INTELLIGENT+ARCHITECT" />

<img src="https://img.shields.io/badge/STATUS-ONLINE-00F5FF?style=for-the-badge&logo=icloud&logoColor=02131f"/>
<img src="https://img.shields.io/badge/AI-FINTECH-0EA5E9?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/CORE-ACTIVE-38BDF8?style=for-the-badge&logo=dependabot&logoColor=02131f"/>
<img src="https://img.shields.io/badge/SYSTEM-LIVE-7DF9FF?style=for-the-badge&logo=databricks&logoColor=02131f"/>

</div>

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Indraditya System Core</title>

<link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;500;700;800&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{

    height:100vh;

    display:flex;

    justify-content:center;

    align-items:center;

    overflow:hidden;

    background:#020617;

    font-family:'Orbitron',sans-serif;

    position:relative;

    color:#7DF9FF;
}

/* =========================
   LAVA ANIMATED BACKGROUND
========================= */

body::before{

    content:"";

    position:absolute;

    width:200%;

    height:200%;

    background:
    radial-gradient(circle at 20% 20%, rgba(0,245,255,0.25), transparent 25%),
    radial-gradient(circle at 80% 30%, rgba(14,165,233,0.25), transparent 25%),
    radial-gradient(circle at 40% 80%, rgba(56,189,248,0.25), transparent 30%),
    radial-gradient(circle at 70% 70%, rgba(125,249,255,0.18), transparent 30%);

    animation:lavaMove 18s ease infinite;

    filter:blur(80px);

    z-index:-2;
}

/* MOVING GRID */

body::after{

    content:"";

    position:absolute;

    inset:0;

    background-image:
    linear-gradient(rgba(255,255,255,0.03) 1px, transparent 1px),
    linear-gradient(90deg, rgba(255,255,255,0.03) 1px, transparent 1px);

    background-size:50px 50px;

    animation:gridMove 10s linear infinite;

    z-index:-1;
}

@keyframes lavaMove{

    0%{
        transform:translate(-10%,-10%) rotate(0deg);
    }

    50%{
        transform:translate(-5%,5%) rotate(180deg);
    }

    100%{
        transform:translate(-10%,-10%) rotate(360deg);
    }
}

@keyframes gridMove{

    from{
        transform:translateY(0);
    }

    to{
        transform:translateY(50px);
    }
}

/* =========================
   MAIN CORE
========================= */

.core-box{

    width:90%;

    max-width:900px;

    padding:40px;

    border-radius:28px;

    background:rgba(2,6,23,0.55);

    backdrop-filter:blur(20px);

    border:1px solid rgba(125,249,255,0.25);

    box-shadow:
    0 0 25px rgba(0,245,255,0.15),
    inset 0 0 25px rgba(0,245,255,0.08);

    position:relative;

    overflow:hidden;
}

/* GLOW BORDER */

.core-box::before{

    content:"";

    position:absolute;

    inset:-2px;

    border-radius:30px;

    padding:2px;

    background:linear-gradient(
        130deg,
        #00F5FF,
        #0EA5E9,
        #38BDF8,
        #7DF9FF,
        #00F5FF
    );

    background-size:400% 400%;

    animation:borderGlow 6s linear infinite;

    -webkit-mask:
        linear-gradient(#fff 0 0) content-box,
        linear-gradient(#fff 0 0);

    -webkit-mask-composite:xor;

    mask-composite:exclude;
}

@keyframes borderGlow{

    0%{
        background-position:0% 50%;
    }

    100%{
        background-position:400% 50%;
    }
}

/* TITLE */

.title{

    text-align:center;

    font-size:42px;

    font-weight:800;

    letter-spacing:6px;

    margin-bottom:30px;

    color:#7DF9FF;

    text-shadow:
    0 0 10px #00F5FF,
    0 0 25px #00F5FF;
}

/* TERMINAL BOX */

.terminal{

    background:rgba(0,0,0,0.45);

    border-radius:18px;

    padding:28px;

    border:1px solid rgba(125,249,255,0.18);

    box-shadow:
    inset 0 0 20px rgba(0,245,255,0.06);
}

/* TEXT */

.line{

    display:flex;

    margin-bottom:18px;

    font-size:15px;

    letter-spacing:1px;

    align-items:center;
}

.key{

    width:180px;

    color:#38BDF8;

    font-weight:700;
}

.value{

    color:#E0FFFF;
}

/* FOCUS */

.focus-title{

    margin-top:25px;

    margin-bottom:15px;

    color:#7DF9FF;

    font-size:18px;

    letter-spacing:2px;
}

.focus-list{

    list-style:none;
}

.focus-list li{

    margin-bottom:12px;

    color:#dbeafe;

    position:relative;

    padding-left:28px;

    letter-spacing:1px;
}

.focus-list li::before{

    content:"◉";

    position:absolute;

    left:0;

    color:#00F5FF;

    text-shadow:0 0 10px #00F5FF;
}

/* STATUS */

.status{

    margin-top:30px;

    text-align:center;

    font-size:15px;

    color:#7DF9FF;

    letter-spacing:3px;

    animation:pulse 2s infinite;
}

@keyframes pulse{

    0%,100%{
        opacity:1;
    }

    50%{
        opacity:0.5;
    }
}

/* MOBILE */

@media(max-width:768px){

    .title{
        font-size:28px;
        letter-spacing:3px;
    }

    .line{
        flex-direction:column;
        align-items:flex-start;
        gap:5px;
    }

    .key{
        width:auto;
    }

    .core-box{
        padding:25px;
    }
}

</style>
</head>

<body>

<div class="core-box">

    <div class="title">
        SYSTEM CORE
    </div>

    <div class="terminal">

        <div class="line">
            <div class="key">USER</div>
            <div class="value">INDRADITYA</div>
        </div>

        <div class="line">
            <div class="key">ROLE</div>
            <div class="value">AI • FINTECH • FULL STACK ENGINEER</div>
        </div>

        <div class="line">
            <div class="key">FRAMEWORK</div>
            <div class="value">REAL TIME ANALYTICS ENGINE</div>
        </div>

        <div class="line">
            <div class="key">STATUS</div>
            <div class="value">ACTIVE</div>
        </div>

        <div class="line">
            <div class="key">NETWORK</div>
            <div class="value">CLOUD CONNECTED</div>
        </div>

        <div class="line">
            <div class="key">SECURITY</div>
            <div class="value">ENCRYPTED</div>
        </div>

        <div class="focus-title">
            PRIMARY MODULES
        </div>

        <ul class="focus-list">

            <li>AI STOCK DASHBOARDS</li>

            <li>LIVE MARKET SYSTEMS</li>

            <li>FINANCIAL UI / UX</li>

            <li>CLOUD APPLICATIONS</li>

            <li>AUTOMATED ANALYTICS</li>

            <li>REAL TIME DATA VISUALIZATION</li>

        </ul>

        <div class="status">
            ◉ REAL TIME FINANCIAL CORE ONLINE ◉
        </div>

    </div>

</div>

</body>
</html>
<div align="center"> <img src="https://skillicons.dev/icons?i=python,flask,react,js,html,css,firebase,php,laravel,mysql,aws,linux" /> </div>
<div align="center"> <img width="49%" src="https://github-readme-stats.vercel.app/api?username=ib-indraditya&show_icons=true&theme=tokyonight&hide_border=true&bg_color=00000000&title_color=7DF9FF&icon_color=00F5FF&text_color=FFFFFF"/> <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=ib-indraditya&theme=tokyonight&hide_border=true&background=00000000&ring=00F5FF&fire=38BDF8&currStreakLabel=7DF9FF"/> </div>
<div align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=ib-indraditya&bg_color=00000000&color=7DF9FF&line=00F5FF&point=FFFFFF&hide_border=true"/> </div>
<div align="center"> <img width="100%" src="https://capsule-render.vercel.app/api?type=transparent&height=180&text=%20&animation=fadeIn&color=0:ff6b6b,20:ff8e53,40:ff9966,60:ff5e62,80:38BDF8,100:7DF9FF"/> </div> <div align="center"> <h3> ⚡ Thank You For Visiting My Profile ⚡ </h3> </div>
