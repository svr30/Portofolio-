<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Srivarshini | UI/UX Designer</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;900&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">

<style>
*{margin:0;padding:0;box-sizing:border-box}

:root{
  --bg:#120a1f;
  --text:#fff0f6;
  --sub:#fbcfe8;
  --accent:#ff6ec7;
  --accent2:#c084fc;
  --glass:rgba(255,255,255,0.08);
  --border:rgba(255,255,255,0.2);
}

body{
  font-family:'Inter',sans-serif;
  background:radial-gradient(circle at top,#2a0f3d,#120a1f);
  color:var(--text);
  overflow-x:hidden;
}

/* INTRO */
.intro{
  position:fixed;
  inset:0;
  background:#120a1f;
  display:flex;
  align-items:center;
  justify-content:center;
  flex-direction:column;
  z-index:9999;
}

.intro h1{
  font-size:52px;
  background:linear-gradient(90deg,#ff9ecb,#c084fc);
  -webkit-background-clip:text;
  color:transparent;
  opacity:0;
  transform:translateY(40px);
  animation:fadeUp 1.5s forwards;
}

.intro p{
  margin-top:12px;
  color:var(--sub);
  opacity:0;
  animation:fadeIn 2s forwards;
  animation-delay:1s;
}

@keyframes fadeUp{
  to{opacity:1;transform:translateY(0)}
}
@keyframes fadeIn{
  to{opacity:1}
}

/* BACKGROUND */
.bg{
  position:fixed;
  inset:0;
  z-index:-1;
}
.orb{
  position:absolute;
  width:500px;height:500px;
  background:radial-gradient(circle,#ff6ec7,transparent);
  filter:blur(150px);
  opacity:0.3;
  animation:move 12s infinite alternate;
}
.orb:nth-child(2){
  right:0;
  background:radial-gradient(circle,#c084fc,transparent);
}

@keyframes move{
  from{transform:translateY(-80px)}
  to{transform:translateY(80px)}
}

/* CONTENT */
.container{
  max-width:1100px;
  margin:auto;
  padding:120px 20px;
}

h1{
  font-size:64px;
  background:linear-gradient(90deg,#ff9ecb,#c084fc);
  -webkit-background-clip:text;
  color:transparent;
}
h2{font-size:32px;margin-bottom:25px}
h3{margin-bottom:10px}
p{color:var(--sub);line-height:1.7}

/* CARDS */
.card{
  background:var(--glass);
  backdrop-filter:blur(30px);
  border:1px solid var(--border);
  border-radius:20px;
  padding:30px;
  margin-bottom:20px;
  transition:0.5s;
}
.card:hover{
  transform:translateY(-12px);
  box-shadow:0 20px 60px rgba(255,110,199,0.4);
}

/* CONTACT */
.contact-icons{
  display:flex;
  gap:18px;
  margin-top:30px;
}
.contact-icons a{
  width:60px;height:60px;
  display:flex;align-items:center;justify-content:center;
  border-radius:50%;
  background:var(--glass);
  border:1px solid var(--border);
  font-size:22px;
  color:white;
  transition:0.4s;
}
.contact-icons a:hover{
  transform:scale(1.2);
  background:linear-gradient(135deg,#ff6ec7,#c084fc);
}

/* REVEAL */
.reveal{
  opacity:0;
  transform:translateY(80px);
  transition:1s;
}
.reveal.active{
  opacity:1;
  transform:translateY(0);
}
</style>
</head>

<body>

<!-- INTRO -->
<div class="intro" id="intro">
  <h1>K.M. Srivarshini</h1>
  <p>UI/UX Designer & Frontend Developer</p>
</div>

<div class="bg">
  <div class="orb"></div>
  <div class="orb"></div>
</div>

<div class="container">

<!-- FULL CONTENT (UNCHANGED) -->

<section class="reveal">
<h1>K.M. Srivarshini</h1>
<p><strong>UI/UX Designer & Frontend Developer</strong></p>
<p>
K.M. Srivarshini is a professional UI/UX Designer and Frontend Developer known for modern, premium, and user-centered digital experiences. She specializes in mobile-first app design, interactive web designs, prototyping, and clean visual systems.
She has hands-on experience building real-world products, working as a UI/UX Intern in multiple companies, delivering high-quality designs, and contributing to impactful tech innovations.
</p>
</section>

<div class="section reveal">
<h2>Core Skills (UI/UX Design)</h2>
<div class="card">
<ul>
<li>UI/UX Design (Advanced)</li>
<li>Interactive Prototyping</li>
<li>Mobile-First Design</li>
<li>High-Fidelity Prototypes (Figma/Adobe XD)</li>
<li>Micro-Interactions & Animations</li>
<li>User Research & Wireframing</li>
<li>Visual Design & Branding</li>
<li>Color Theory & Typography</li>
<li>Design Systems & Components</li>
<li>Glassmorphism, Neumorphism, Soft UI, Minimal UI, 3D UI</li>
</ul>
</div>

<h2>Technical Skills</h2>
<div class="card">
<ul>
<li>HTML, CSS, JavaScript</li>
<li>Tailwind CSS</li>
<li>React (Basics)</li>
<li>Firebase (Auth, Firestore, Storage)</li>
<li>Git & GitHub</li>
<li>Responsive Web Development</li>
<li>UI Animations & Frontend Interactions</li>
</ul>
</div>
</div>

<div class="section reveal">
<h2>Projects</h2>

<div class="card">
<h3>Voxlog – Voice-Based Social Media Website</h3>
<p><strong>Problem:</strong> Traditional social media platforms rely heavily on text and visuals, limiting expressive communication.</p>
<p><strong>Solution:</strong> Designed a voice-first platform enabling users to share thoughts through audio.</p>
<p><strong>Role:</strong> UI/UX Design, Frontend Development, Firebase Integration</p>
</div>

<div class="card">
<h3>Smart Water Meter (IoT)</h3>
<p>
Developed the UI and frontend logic for monitoring and analyzing water usage.
This project was selected and showcased at IITMIC Build to Innovate – Rural & Agri Edition.
</p>
</div>
</div>

<div class="section reveal">
<h2>Internships</h2>

<div class="card"><h3>UI/UX Internship – Hitasoft Technology Solutions Pvt Ltd</h3><p>Jan 8, 2025 – Jan 24, 2025</p></div>
<div class="card"><h3>UI/UX Design Internship – Zen 1 Tech Park</h3><p>Jun 20, 2025 – Jul 20, 2025</p></div>
<div class="card"><h3>Web Development Internship – Octanet Services Pvt Ltd</h3><p>Jun 2024 – Jul 2024</p></div>
<div class="card"><h3>Web Development Virtual Internship – CodSoft</h3><p>May 2024 – Jun 2024</p></div>
<div class="card"><h3>AI Internship – Pantech Prolabs India Pvt Ltd</h3><p>Feb 2024</p></div>
<div class="card"><h3>Web Development Internship – Intrainz</h3><p>May 2024 – Jul 2024</p></div>

</div>

<div class="section reveal">
<h2>Certifications</h2>
<div class="card">
<ul>
<li>Foundations of User Experience (UX) Design – Google (Coursera) | Mar 2024</li>
<li>AI For Everyone – DeepLearning.AI (Coursera) | Feb 2024</li>
<li>Introduction to HTML5 – University of Michigan (Coursera) | Feb 2024</li>
<li>Programming for Everybody (Python) – University of Michigan (Coursera) | Apr 2023</li>
<li>Programming with Python Training – Internshala | Apr 2023</li>
<li>Database Programming with SQL – Oracle Academy | Jun 2024</li>
<li>Cyber Security Training – Skillvertex | Oct 2023</li>
</ul>
</div>
</div>

<div class="section reveal">
<h2>Achievements</h2>
<div class="card">
<p><strong>IITMIC Build to Innovate – Rural & Agri Edition (April 2024)</strong></p>
<p>
Received Certificate of Achievement for presenting innovation in Rural & Agriculture track,
recognized for impactful tech-based solutions.
</p>
</div>
</div>

<div class="section reveal">
<h2>Design Process</h2>
<p>Research → Define → Ideate → Design → Prototype → Test</p>
</div>

<div class="section reveal">
<h2>Contact</h2>

<div class="contact-icons">
<a href="tel:+919150484943"><i class="fa-solid fa-phone"></i></a>
<a href="mailto:srivarshinisvr3@gmail.com"><i class="fa-solid fa-envelope"></i></a>
<a href="https://github.com/svr30"><i class="fa-brands fa-github"></i></a>
<a href="https://www.linkedin.com/in/sri-varshini-a55115263"><i class="fa-brands fa-linkedin"></i></a>
<a href="https://www.instagram.com/_sv3._"><i class="fa-brands fa-instagram"></i></a>
</div>

</div>

</div>

<script>

/* reveal function */
function revealNow(){
  document.querySelectorAll('.reveal').forEach(el=>{
    el.classList.add('active');
  });
}

/* intro exit */
window.addEventListener("load",()=>{
  const intro=document.getElementById("intro");

  setTimeout(()=>{
    intro.style.opacity="0";
    intro.style.transition="1s";

    setTimeout(()=>{
      intro.style.display="none";
      revealNow(); // 👈 FIX: show content immediately
    },1000);

  },3000);
});

/* scroll reveal for later */
window.addEventListener('scroll',()=>{
  document.querySelectorAll('.reveal').forEach(el=>{
    if(el.getBoundingClientRect().top < window.innerHeight - 80){
      el.classList.add('active');
    }
  });
});

</script>

</body>
</html>
