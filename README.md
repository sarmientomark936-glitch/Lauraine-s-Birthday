<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Birthday 💗</title>
<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Serif+Display&family=Great+Vibes&family=Poppins:wght@400;500;600;700&display=swap');

*{box-sizing:border-box;margin:0;padding:0}
html{scroll-behavior:smooth}
body{
  font-family:Poppins,sans-serif;
  color:#8d2854;
  background:
    radial-gradient(circle at 10% 20%,rgba(255,255,255,.8),transparent 20%),
    radial-gradient(circle at 90% 10%,rgba(255,180,210,.55),transparent 25%),
    linear-gradient(135deg,#ffe5ef,#ffd0e1 45%,#fff0f5);
  overflow-x:hidden;
}
body:before{
  content:"";
  position:fixed;inset:0;pointer-events:none;z-index:0;
  background-image:radial-gradient(rgba(190,65,110,.15) .7px,transparent .7px);
  background-size:8px 8px;opacity:.25;
}
nav{
  position:fixed;top:0;left:0;right:0;z-index:50;
  display:flex;justify-content:center;gap:36px;
  padding:20px 12px;
  background:rgba(255,236,244,.72);
  backdrop-filter:blur(14px);
  border-bottom:1px solid rgba(255,255,255,.6);
}
nav a{color:#b93868;text-decoration:none;font-weight:600}
nav a:hover{color:#f04f88}
.hero{
  min-height:100vh;position:relative;z-index:1;
  display:grid;grid-template-columns:1fr 1.35fr 1fr;
  align-items:center;gap:22px;padding:95px 5vw 50px;
  max-width:1500px;margin:auto;
}
.hero:before{
  content:"";position:absolute;inset:5% 12%;z-index:-1;
  background:rgba(255,255,255,.38);filter:blur(2px);border-radius:50%;
}
.center{text-align:center}
.badge{display:inline-block;padding:8px 18px;border-radius:30px;background:#fff;color:#d83d72;font-size:.85rem;box-shadow:0 8px 25px #d45b8525}
h1{
  font-family:"Great Vibes",cursive;font-size:clamp(4rem,8vw,8rem);
  line-height:.82;color:#ed4f88;
  text-shadow:3px 4px 0 #fff,0 12px 30px #c43f6a30;
  margin:18px 0;
}
.kicker{font-family:"DM Serif Display";font-size:1.5rem;color:#a53660}
.lead{max-width:600px;margin:15px auto;color:#a75b78}
.photo{
  width:100%;aspect-ratio:4/5;object-fit:cover;
  border:12px solid #fff;border-radius:5px;
  box-shadow:0 20px 45px rgba(137,45,79,.18);
  transition:.45s;
}
.photo:hover{transform:rotate(0deg) scale(1.03)}
.left .photo:nth-child(1){transform:rotate(-5deg)}
.left .photo:nth-child(2){transform:rotate(4deg);margin-top:-40px}
.right .photo:nth-child(1){transform:rotate(5deg)}
.right .photo:nth-child(2){transform:rotate(-4deg);margin-top:-35px}
.left,.right{display:flex;flex-direction:column;gap:10px}
.note{
  display:inline-block;background:#ffd9e7;padding:14px 20px;
  font-family:"Great Vibes";font-size:1.55rem;transform:rotate(-3deg);
  box-shadow:0 8px 20px #b83e6520;margin:8px;
}
.btn{
  display:inline-flex;align-items:center;gap:10px;
  border:0;cursor:pointer;color:white;font-weight:700;font-size:1rem;
  padding:16px 34px;border-radius:999px;
  background:linear-gradient(135deg,#ff78a8,#e93470);
  box-shadow:0 12px 30px #e9347050;transition:.3s;
}
.btn:hover{transform:translateY(-3px) scale(1.03)}
section{position:relative;z-index:1;padding:90px 6vw}
.section-title{text-align:center;font-family:"Great Vibes";font-size:4rem;color:#e94c83;margin-bottom:35px}
.message-card{
  max-width:850px;margin:auto;background:rgba(255,255,255,.88);
  border-radius:32px;padding:45px;text-align:center;
  box-shadow:0 20px 55px #ad426020;border:2px solid #fff;
}
.message-card p{line-height:1.9;color:#87536b}
.message-card strong{color:#e43d77}
.gallery{
  max-width:1100px;margin:auto;display:grid;
  grid-template-columns:repeat(3,1fr);gap:22px;
}
.gallery .photo{aspect-ratio:1/1}
.gallery .photo:nth-child(2){transform:rotate(3deg)}
.gallery .photo:nth-child(3){transform:rotate(-3deg)}
.gallery .photo:nth-child(4){transform:rotate(2deg)}
.gallery .photo:nth-child(5){transform:rotate(-4deg)}
.gallery .photo:nth-child(6){transform:rotate(3deg)}
.wishes{
  max-width:900px;margin:auto;display:grid;grid-template-columns:repeat(3,1fr);gap:18px;
}
.wish{background:#fff;padding:25px;border-radius:25px;text-align:center;box-shadow:0 12px 30px #b9436a20}
.wish .emoji{font-size:2rem}.wish h3{color:#df3e75;margin:8px}
footer{text-align:center;padding:50px;color:#a44a6d}
.float{
  position:fixed;z-index:0;pointer-events:none;font-size:25px;
  animation:rise linear infinite;opacity:.7;
}
@keyframes rise{
  from{transform:translateY(110vh) rotate(0);opacity:0}
  15%{opacity:.8}to{transform:translateY(-20vh) rotate(360deg);opacity:0}
}
#surprise{display:none;margin-top:25px;animation:pop .7s ease}
@keyframes pop{from{opacity:0;transform:scale(.8)}to{opacity:1;transform:scale(1)}}
@media(max-width:900px){
  .hero{grid-template-columns:1fr;padding-top:110px}
  .left,.right{display:grid;grid-template-columns:1fr 1fr}
  .left .photo:nth-child(2),.right .photo:nth-child(2){margin-top:0}
  .gallery,.wishes{grid-template-columns:1fr 1fr}
}
@media(max-width:560px){
  nav{gap:14px;font-size:.78rem;overflow:auto;justify-content:flex-start}
  .left,.right,.gallery,.wishes{grid-template-columns:1fr}
  .hero{padding-left:20px;padding-right:20px}
  .message-card{padding:28px 20px}
  .section-title{font-size:3.2rem}
}
</style>
</head>
<body>

<nav>
  <a href="#home">Home</a>
  <a href="#message">Message</a>
  <a href="#photos">Photos</a>
  <a href="#wishes">Wishes</a>
</nav>

<main id="home" class="hero">
  <div class="left">
    <img class="photo" src="photo9.jpg" alt="Birthday photo">
    <img class="photo" src="photo2.jpg" alt="Friends photo">
    <span class="note">Good Friends 💕</span>
  </div>

  <div class="center">
    <span class="badge">🎀 A little birthday surprise 🎀</span>
    <div class="kicker">To Someone Special</div>
    <h1>Happy<br>Birthday<br>Lauraine!</h1>
    <p class="lead">May your day be filled with happiness, love, laughter, and unforgettable memories. Keep being the amazing person that you are! 💗</p>
    <button class="btn" onclick="openSurprise()">💗 Open Your Surprise</button>
    <div id="surprise">
      <p class="note">You are so special! ✨</p>
      <p class="note">Keep Smiling! 🌸</p>
    </div>
  </div>

  <div class="right">
    <img class="photo" src="photo4.jpg" alt="Birthday photo">
    <img class="photo" src="photo3.jpg" alt="Birthday photo">
    <span class="note">Stay Cute 💗</span>
  </div>
</main>

<section id="message">
  <h2 class="section-title">A Special Message</h2>
  <div class="message-card">
    <p>
      Happy Birthday Lauraine! 🎂💗<br><br>
      I just want to say how thankful I am to have a friend like you.
Thank you for all the laughs, random conversations, unforgettable memories, and for always being there whenever we need someone to talk to. 🤝
<br><br>
I hope you enjoy your special day and get everything you’ve been wishing for. Wishing you good health, happiness, success, and more blessings in life. And don’t pressure yourself too much, especially about the things that haven’t come yet. Take your time, enjoy every moment, and trust God’s timing. Sometimes, things don’t happen when we expect them to, but God has a plan for everything. Just keep doing your best, keep praying, and trust that He will give you what’s meant for you at the right time. 🤍
<br><br>
Stay the same crazy, funny, and amazing person that you are! More memories, gala, tawanan, at kalokohan together! HAHAHA. Happy Birthday, Chi! Enjoy your day! 🎉
      <br><br>
      <strong>Enjoy your birthday and always remember that you are special! 🎀</strong>
    </p>
  </div>
</section>

<section id="photos">
  <h2 class="section-title">Our Little Memories</h2>
  <div class="gallery">
    <img class="photo" src="photo1.jpg" alt="Memory">
    <img class="photo" src="photo2.jpg" alt="Memory">
    <img class="photo" src="photo3.jpg" alt="Memory">
    <img class="photo" src="photo8.jpg" alt="Memory">
    <img class="photo" src="photo9.jpg" alt="Memory">
    <img class="photo" src="photo10.jpg" alt="Memory">
  </div>
</section>

<section id="wishes">
  <h2 class="section-title">Birthday Wishes</h2>
  <div class="wishes">
    <div class="wish"><div class="emoji">🌸</div><h3>Happiness</h3><p>May your days be filled with genuine smiles and beautiful moments.</p></div>
    <div class="wish"><div class="emoji">🙏</div><h3>More Blessings</h3><p>May God continue to guide you and bless every step of your journey.</p></div>
    <div class="wish"><div class="emoji">✨</div><h3>Your Dreams</h3><p>May the dreams in your heart slowly become beautiful realities.</p></div>
  </div>
</section>

<footer>
  Made with 💗 just for you • Happy Birthday! 🎂
</footer>

<script>
function openSurprise(){
  const s=document.getElementById("surprise");
  s.style.display="block";
  for(let i=0;i<35;i++){
    const h=document.createElement("div");
    h.className="float";
    h.textContent=["💗","💕","🌸","✨","🎀"][Math.floor(Math.random()*5)];
    h.style.left=Math.random()*100+"vw";
    h.style.animationDuration=(3+Math.random()*4)+"s";
    h.style.animationDelay=(Math.random()*1)+"s";
    document.body.appendChild(h);
    setTimeout(()=>h.remove(),8000);
  }
}
</script>
</body>
</html>
