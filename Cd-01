<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy New Year Namrata</title>

<link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    background:linear-gradient(to bottom,#24243e,#302b63,#0f0c29);
    color:white;
    overflow:hidden;
    height:100vh;
}

/* ---------- BACKGROUND ---------- */
#fireworksCanvas{
    position:absolute;
    inset:0;
    z-index:0;
    pointer-events:none;
}

/* ---------- SLIDER ---------- */
.slider-container{
    position:relative;
    width:100%;
    height:100%;
    display:flex;
    justify-content:center;
    align-items:center;
    z-index:10;
    touch-action:pan-y;
}

.slide{
    position:absolute;
    width:80%;
    max-width:600px;
    height:80%;
    background:rgba(255,255,255,0.1);
    backdrop-filter:blur(10px);
    border-radius:20px;
    padding:40px;
    text-align:center;
    display:flex;
    flex-direction:column;
    justify-content:center;
    align-items:center;
    opacity:0;
    transform:scale(0.8);
    transition:all 0.8s cubic-bezier(0.175,0.885,0.32,1.275);
    box-shadow:0 15px 35px rgba(0,0,0,0.5);
}

.slide.active{
    opacity:1;
    transform:scale(1);
}

/* ---------- TEXT ---------- */
h1{
    font-family:'Dancing Script',cursive;
    font-size:4rem;
    color:#ff4d6d;
    margin-bottom:20px;
}

h2{
    font-family:'Dancing Script',cursive;
    font-size:2.5rem;
    color:#ffd700;
    margin-bottom:15px;
}

p{
    font-size:1.1rem;
    line-height:1.8;
    color:#e0e0e0;
    margin-bottom:30px;
}

/* ---------- CONTENT ANIMATION ---------- */
.slide h1,
.slide h2,
.slide p,
.slide .btn{
    opacity:0;
    transform:translateY(20px);
    transition:all 0.6s ease;
}

.slide.active h1{transition-delay:0.2s;opacity:1;transform:none;}
.slide.active h2{transition-delay:0.25s;opacity:1;transform:none;}
.slide.active p{transition-delay:0.4s;opacity:1;transform:none;}
.slide.active .btn{transition-delay:0.6s;opacity:1;transform:none;}

/* ---------- BUTTON ---------- */
.btn{
    padding:15px 40px;
    font-size:1.2rem;
    border:none;
    border-radius:50px;
    background:linear-gradient(45deg,#ff4d6d,#ff9a8b);
    color:white;
    cursor:pointer;
    box-shadow:0 5px 15px rgba(255,77,109,0.4);
}

/* ---------- HEARTS ---------- */
#heartsContainer,
.heart{
    pointer-events:none;
}

.heart{
    position:absolute;
    color:#ff4d6d;
    font-size:20px;
    animation:floatUp 4s linear infinite;
    opacity:0;
}

@keyframes floatUp{
    0%{transform:translateY(100vh) scale(0.5);opacity:0;}
    20%{opacity:1;}
    100%{transform:translateY(-10vh) scale(1.2);opacity:0;}
}

/* ---------- DOTS ---------- */
.nav-dots{
    position:absolute;
    bottom:30px;
    display:flex;
    gap:15px;
    z-index:20;
}

.dot{
    width:12px;
    height:12px;
    border-radius:50%;
    background:rgba(255,255,255,0.3);
    cursor:pointer;
}

.dot.active{
    background:#ff4d6d;
    transform:scale(1.2);
}
</style>
</head>

<body>

<canvas id="fireworksCanvas"></canvas>
<div id="heartsContainer"></div>

<div class="slider-container">

    <div class="slide active">
        <h1>Namrata</h1>
        <p>I have been waiting for this moment to tell you something special.</p>
        <button class="btn" onclick="nextSlide()">Start the Magic</button>
    </div>

    <div class="slide">
        <h1>Happy New Year 2025!</h1>
        <p>May this year bring you endless joy, peace, health, and happiness.</p>
        <div style="font-size:3rem">🎉✨🎊</div>
    </div>

    <div class="slide">
        <h2>My Love,</h2>
        <p>
            As the clock strikes twelve,<br>
            I want you to know how grateful I am for you.<br><br>
            You make my life brighter in ways you may never realize.
        </p>
    </div>

    <div class="slide">
        <h2>Always With You</h2>
        <p>
            No matter how hard life gets,<br>
            remember this —<br><br>
            You are never alone.<br>
            I will always stand by your side,
            through every smile and every tear.
        </p>
    </div>

    <div class="slide">
        <h2>You Are Strong</h2>
        <p>
            Even on the days you feel tired or unsure,<br>
            you keep moving forward.<br><br>
            That strength inspires me more than you know.
        </p>
    </div>

    <div class="slide">
        <h2>Believe in Yourself</h2>
        <p>
            I believe in you completely.<br><br>
            Your dreams matter.
            Your efforts matter.
            And I will always encourage you to chase what your heart desires.
        </p>
    </div>

    <div class="slide">
        <h2>Our Journey</h2>
        <p>
            Life may not always be perfect,<br>
            but I promise this —<br><br>
            We’ll face everything together,
            growing stronger with every step.
        </p>
    </div>

    <div class="slide">
        <h1>I Love You</h1>
        <p>Namrata, you are my greatest adventure.</p>
        <button class="btn" onclick="location.reload()">Replay ❤️</button>
    </div>

</div>

<div class="nav-dots">
    <div class="dot active" onclick="goToSlide(0)"></div>
    <div class="dot" onclick="goToSlide(1)"></div>
    <div class="dot" onclick="goToSlide(2)"></div>
    <div class="dot" onclick="goToSlide(3)"></div>
    <div class="dot" onclick="goToSlide(4)"></div>
    <div class="dot" onclick="goToSlide(5)"></div>
    <div class="dot" onclick="goToSlide(6)"></div>
    <div class="dot" onclick="goToSlide(7)"></div>
</div>

<script>
const canvas=document.getElementById("fireworksCanvas");
const ctx=canvas.getContext("2d");
canvas.width=innerWidth;
canvas.height=innerHeight;

let particles=[];

function random(min,max){return Math.random()*(max-min)+min;}

function createFirework(x,y){
    for(let i=0;i<30;i++){
        particles.push({
            x,y,
            speed:random(1,5),
            angle:random(0,Math.PI*2),
            size:random(2,4),
            color:`hsl(${random(0,360)},100%,50%)`
        });
    }
}

function updateFireworks(){
    ctx.clearRect(0,0,canvas.width,canvas.height);
    if(Math.random()<0.05){
        createFirework(random(0,canvas.width),random(0,canvas.height/2));
    }
    particles.forEach((p,i)=>{
        p.x+=Math.cos(p.angle)*p.speed;
        p.y+=Math.sin(p.angle)*p.speed;
        p.speed*=0.96;
        p.size*=0.95;
        ctx.fillStyle=p.color;
        ctx.beginPath();
        ctx.arc(p.x,p.y,p.size,0,Math.PI*2);
        ctx.fill();
        if(p.size<0.5)particles.splice(i,1);
    });
    requestAnimationFrame(updateFireworks);
}
updateFireworks();

function createHeart(){
    const h=document.createElement("div");
    h.className="heart";
    h.innerHTML="❤";
    h.style.left=Math.random()*100+"vw";
    h.style.animationDuration=3+Math.random()*2+"s";
    heartsContainer.appendChild(h);
    setTimeout(()=>h.remove(),5000);
}
setInterval(createHeart,300);

let currentSlide=0;
const slides=document.querySelectorAll(".slide");
const dots=document.querySelectorAll(".dot");

function showSlide(i){
    if(i<0||i>=slides.length)return;
    slides.forEach(s=>s.classList.remove("active"));
    dots.forEach(d=>d.classList.remove("active"));
    slides[i].classList.add("active");
    dots[i].classList.add("active");
    currentSlide=i;
}

function nextSlide(){showSlide(currentSlide+1);}
function goToSlide(i){showSlide(i);}

let startX=0,endX=0;
const slider=document.querySelector(".slider-container");

slider.addEventListener("touchstart",e=>{
    startX=e.changedTouches[0].screenX;
});
slider.addEventListener("touchend",e=>{
    endX=e.changedTouches[0].screenX;
    if(endX-startX>50)showSlide(currentSlide-1);
    if(startX-endX>50)showSlide(currentSlide+1);
});

window.onresize=()=>{
    canvas.width=innerWidth;
    canvas.height=innerHeight;
};
</script>

</body>
</html>
