
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Shivam Shukla | Portfolio</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500;600;700&family=Space+Grotesk:wght@500;600;700&display=swap" rel="stylesheet">
<style>
:root{
 --bg:#080b1b;--card:#151a32;--muted:#a7aec7;
 --pink:#e85aa8;--purple:#9b55ed;--blue:#4659ef;
 --gradient:linear-gradient(110deg,#ed5ba7,#9d48d5,#4059ef);
}
*{box-sizing:border-box;scroll-behavior:smooth}
body{margin:0;background:var(--bg);color:white;font-family:'DM Sans',sans-serif}
a{text-decoration:none;color:inherit}
.layout{max-width:1500px;margin:auto;padding:15px;display:grid;grid-template-columns:230px 1fr;gap:15px}
aside,main{background:#0e1227;border:1px solid #ffffff12;border-radius:16px}
aside{padding:22px;position:sticky;top:15px;height:calc(100vh - 30px)}
.logo{font:700 21px 'Space Grotesk';margin-bottom:35px}
.logo span,.gradient{background:var(--gradient);background-clip:text;color:transparent}
nav{display:grid;gap:9px}
nav a{padding:12px;border-radius:9px;color:#c5c8dc;font-size:13px}
nav a:hover,.active{background:#362044;color:white}
.available{margin-top:35px;padding:17px;background:var(--gradient);border-radius:12px}
.available h3{font-size:16px}
.available p{font-size:12px;line-height:1.6}
.available a{display:inline-block;background:white;color:#6c36a7;padding:9px 15px;border-radius:7px;font-size:12px}
.social{margin-top:35px;color:#aab0ca;font-size:12px}
main{overflow:hidden}
.top{padding:23px 35px;text-align:right;border-bottom:1px solid #ffffff10}
.top a{margin-left:23px;font-size:12px}
section{padding:45px 40px;scroll-margin-top:15px}
.hero{display:grid;grid-template-columns:1.1fr .9fr;align-items:center;min-height:390px}
.small{color:#df72c1;letter-spacing:2px;font-size:10px;font-weight:bold}
h1{font:700 clamp(40px,5vw,65px)/1.1 'Space Grotesk';margin:15px 0}
h2{font:600 25px 'Space Grotesk'}
.hero h3{font-size:20px;font-weight:500;line-height:1.5}
p{color:var(--muted);font-size:13px;line-height:1.8}
.btn{display:inline-block;background:var(--gradient);padding:12px 18px;border-radius:8px;font-size:12px;font-weight:bold;margin:12px 8px 0 0}
.btn2{background:#222641}
.photo{width:260px;height:260px;border-radius:50%;background:radial-gradient(circle at 35% 30%,#ed5ba7,#7742bd,#4059ef);margin:auto;display:grid;place-items:center;box-shadow:0 0 75px #a34bd044}
.photo div{width:185px;height:220px;background:#11162c;border-radius:50% 50% 25% 25%;display:grid;place-items:center;font:700 65px 'Space Grotesk';color:#dc70ce;border:1px solid #ffffff25}
.experience{display:flex;justify-content:space-around;padding:25px;background:var(--gradient);border-radius:12px;margin:0 40px}
.experience div{text-align:center}
.experience strong{font:700 27px 'Space Grotesk';display:block}
.experience span{font-size:10px}
.heading{margin-bottom:23px}
.heading h2{margin:8px 0}
.cards{display:grid;grid-template-columns:repeat(4,1fr);gap:13px}
.card{background:linear-gradient(145deg,#1a1e3a,#12162c);border:1px solid #ffffff0c;border-radius:13px;padding:20px}
.card .icon{width:42px;height:42px;border-radius:50%;background:var(--gradient);display:grid;place-items:center;font-size:20px;margin-bottom:15px}
.card h3{font:600 15px 'Space Grotesk'}
.card p{font-size:11px}
.skills{display:flex;flex-wrap:wrap;gap:10px}
.skills span{padding:10px 14px;background:#171c36;border:1px solid #ffffff12;border-radius:8px;font-size:12px}
.job{padding:22px;background:#151a32;border:1px solid #ffffff12;border-radius:12px;margin-bottom:15px}
.job h3{margin:0 0 8px;font-size:17px}
.job small{color:#dc72c0}
.contact{display:grid;grid-template-columns:1fr 1.4fr;gap:15px}
.contact-info{background:var(--gradient);padding:25px;border-radius:13px}
form{background:#151a32;padding:20px;border-radius:13px;display:grid;gap:12px}
input,textarea{padding:13px;background:#0d1126;border:1px solid #ffffff15;border-radius:7px;color:white;font:13px 'DM Sans'}
textarea{min-height:110px}
button{background:var(--gradient);color:white;border:0;padding:12px;border-radius:8px;cursor:pointer}
footer{text-align:center;padding:22px;color:#8289a5;font-size:11px}
@media(max-width:900px){
 .layout{grid-template-columns:1fr}
 aside{position:relative;height:auto}
 aside nav{display:flex;overflow:auto}
 .available,.social{display:none}
 .cards{grid-template-columns:repeat(2,1fr)}
}
@media(max-width:600px){
 .top{display:none}
 section{padding:30px 20px}
 .hero{grid-template-columns:1fr;gap:35px}
 .photo{width:220px;height:220px}
 .photo div{width:155px;height:185px}
 .cards{grid-template-columns:1fr}
 .experience{margin:0 15px;display:grid;grid-template-columns:1fr 1fr;gap:20px}
 .contact{grid-template-columns:1fr}
}
</style>
</head>
<body>
<div class="layout">

<aside>
 <div class="logo"><span>◆</span> SHIVAM SHUKLA</div>
 <nav>
  <a class="active" href="#home">⌂ Home</a>
  <a href="#about">♙ About</a>
  <a href="#services">▣ Services</a>
  <a href="#skills">◇ Skills</a>
  <a href="#experience">▤ Experience</a>
  <a href="#contact">✉ Contact</a>
 </nav>
 <div class="available">
  <h3>Available for Opportunities</h3>
  <p>Let's connect and build something amazing together!</p>
  <a href="#contact">Hire Me →</a>
 </div>
 <div class="social">
  <p>DOWNLOAD RESUME</p>
  <a href="Shivam_Shukla_Resume.pdf" download>↓ Download CV</a>
  <p>FOLLOW ME</p>
  <a href="https://www.linkedin.com/" target="_blank">LinkedIn ↗</a>
 </div>
</aside>

<main>
 <div class="top">
  <a href="#home">Home</a>
  <a href="#about">About</a>
  <a href="#services">Services</a>
  <a href="#skills">Skills</a>
  <a href="#contact">Contact</a>
  <a class="btn" href="#contact">Let's Talk ↗</a>
 </div>

 <section class="hero" id="home">
  <div>
   <div class="small">HELLO, I'M</div>
   <h1>Shivam <span class="gradient">Shukla</span></h1>
   <h3>US IT Staffing & <span class="gradient">Bench Sales Recruiter</span></h3>
   <p>I'm a recruitment professional with 3+ years of experience in US IT Staffing, Bench Sales, OPT Recruiting, Vendor Management and Consultant Marketing.</p>
   <a class="btn" href="#experience">View My Experience ↗</a>
   <a class="btn btn2" href="#contact">Contact Me ▶</a>
  </div>
  <div class="photo"><div>SS</div></div>
 </section>

 <section id="about">
  <div class="heading">
   <div class="small">ABOUT ME</div>
   <h2>Professional Summary</h2>
  </div>
  <p>US IT Staffing and Bench Sales professional with 3+ years of experience marketing H1B, OPT, CPT, TN, Green Card and US Citizen consultants. Experienced in building vendor relationships, identifying opportunities, analyzing requirements, optimizing resumes, negotiating rates, coordinating interviews and supporting successful placements.</p>
 </section>

 <section id="services">
  <div class="heading">
   <div class="small">WHAT I DO</div>
   <h2>Services I Offer</h2>
  </div>
  <div class="cards">
   <div class="card">
    <div class="icon">✧</div>
    <h3>Bench Sales</h3>
    <p>Consultant marketing and profile submissions across US IT staffing markets.</p>
   </div>
   <div class="card">
    <div class="icon">⌘</div>
    <h3>Vendor Management</h3>
    <p>Building relationships with Tier-1 vendors, implementation partners and clients.</p>
   </div>
   <div class="card">
    <div class="icon">▤</div>
    <h3>Resume Optimization</h3>
    <p>Matching consultant profiles with job descriptions and client requirements.</p>
   </div>
   <div class="card">
    <div class="icon">🚀</div>
    <h3>Recruitment Coordination</h3>
    <p>Interview scheduling, follow-ups, rate negotiation and submission tracking.</p>
   </div>
  </div>
 </section>

 <section id="skills">
  <div class="heading">
   <div class="small">MY EXPERTISE</div>
   <h2>Skills & Tools</h2>
  </div>
  <div class="skills">
   <span>US IT Staffing</span><span>Bench Sales</span>
   <span>OPT Recruiting</span><span>H1B / CPT / TN / GC</span>
   <span>Vendor Management</span><span>Consultant Marketing</span>
   <span>Requirement Analysis</span><span>Resume Optimization</span>
   <span>Rate Negotiation</span><span>Interview Scheduling</span>
   <span>Dice</span><span>Monster</span><span>CareerBuilder</span>
   <span>LinkedIn Recruiter</span><span>TechFetch</span>
   <span>W2 / C2C / 1099</span>
  </div>
 </section>

 <section id="experience">
  <div class="heading">
   <div class="small">MY JOURNEY</div>
   <h2>Professional Experience</h2>
  </div>
  <div class="job">
   <small>Aug 2024 – Present</small>
   <h3>Bench Sales Recruiter & OPT Recruiter</h3>
   <small>TMT IT Solutions | United States, TX</small>
   <p>Managing end-to-end Bench Sales operations, consultant marketing, vendor relationships, requirement analysis, resume optimization, rate negotiation, interview coordination, submission tracking and placement activities.</p>
  </div>
  <div class="job">
   <small>Sep 2023 – Jul 2024</small>
   <h3>Sales Recruiter (Bench Sales / H1B Sales)</h3>
   <small>HighViz IT Solutions Inc. | Irving, Texas</small>
   <p>Supported US IT staffing operations through consultant marketing, vendor communication, sourcing, resume optimization, interview coordination and recruitment documentation.</p>
  </div>
 </section>

 <div class="experience">
  <div><strong>3+</strong><span>Years Experience</span></div>
  <div><strong>2</strong><span>Companies</span></div>
  <div><strong>US IT</strong><span>Staffing</span></div>
  <div><strong>360°</strong><span>Recruitment Support</span></div>
 </div>

 <section id="contact">
  <div class="heading">
   <div class="small">GET IN TOUCH</div>
   <h2>Let's Work Together!</h2>
  </div>
  <div class="contact">
   <div class="contact-info">
    <h2>Let's Connect!</h2>
    <p>Have an opportunity or want to discuss a professional collaboration?</p>
    <p>✉ shivamshuklash9090@gmail.com</p>
    <p>☎ +91 9990270466</p>
   </div>
   <form id="contactForm">
    <input id="name" placeholder="Your Name" required>
    <input id="email" type="email" placeholder="Your Email" required>
    <textarea id="message" placeholder="Your Message" required></textarea>
    <button type="submit">Send Message ↗</button>
   </form>
  </div>
 </section>
 <footer>© <span id="year"></span> Shivam Shukla. All Rights Reserved.</footer>
</main>
</div>

<script>
document.getElementById("year").textContent=new Date().getFullYear();

document.getElementById("contactForm").addEventListener("submit",function(e){
 e.preventDefault();
 const name=document.getElementById("name").value;
 const email=document.getElementById("email").value;
 const message=document.getElementById("message").value;
 const subject=encodeURIComponent("Portfolio enquiry from "+name);
 const body=encodeURIComponent("Name: "+name+"\nEmail: "+email+"\n\n"+message);
 window.location.href="mailto:shivamshuklash9090@gmail.com?subject="+subject+"&body="+body;
});
</script>
</body>
</html>
