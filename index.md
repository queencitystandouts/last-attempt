---
layout: home
title: "Private Soccer Training in Charlotte, NC | Coach Adam & Coach Luca"
description: "One-on-one soccer training, small group sessions, and game analysis in Charlotte, NC. Improve your skills with expert coaching."
seo:
  keywords: "soccer training Charlotte, private soccer coach Charlotte NC, one-on-one soccer training, small group training, game analysis"
---

<!-- Inline CSS for Teal / White / Black Theme -->
<style>
/* Buttons */
.btn-primary, .btn-primary:visited { background-color: #008080 !important; color: #ffffff !important; }
.btn-primary:hover { background-color: #006666 !important; }

/* Navbar / Header */
.navbar, header { background-color: #000000 !important; }
.navbar a, header a { color: #ffffff !important; }
.navbar a:hover, header a:hover { color: #008080 !important; }

/* Footer */
footer { background-color: #000000 !important; color: #ffffff !important; }
footer a { color: #ffffff !important; }
footer a:hover { color: #008080 !important; }

/* Sections */
#hero, #services, #team, #timeline { background-color: #ffffff !important; color: #000000 !important; }

/* Links */
a { color: #008080 !important; }
a:hover { color: #006666 !important; }
</style>

<!-- Hero Section -->
<section id="hero">
  <h1>Charlotte Private Soccer Training</h1>
  <p>Improve your skills, game intelligence, and athleticism with Coach Adam and Coach Luca</p>
  <a href="#services" class="btn btn-primary">View Our Services</a>
</section>

<!-- Services Section -->
<section id="services">
  <h2>Soccer Training Services</h2>
  <p>One-on-one training, small group sessions, and game analysis to help players of all ages and levels improve.</p>

  <div class="service">
    <h3>One-on-One Private Training</h3>
    <p>Personalized coaching focusing on technical skills, speed, agility, and tactical understanding for individual players in Charlotte, NC.</p>
    <a href="https://calendly.com/your-link" target="_blank" class="btn btn-primary">Book Now</a>
  </div>

  <div class="service">
    <h3>Small Group Training</h3>
    <p>Small group sessions emphasizing teamwork, tactical awareness, and competitive play in a supportive environment.</p>
    <a href="https://calendly.com/your-link" target="_blank" class="btn btn-primary">Book Now</a>
  </div>

  <div class="service">
    <h3>Game Analysis</h3>
    <p>Video and on-field analysis to identify strengths and areas for improvement, helping players make smarter decisions during matches.</p>
    <a href="https://calendly.com/your-link" target="_blank" class="btn btn-primary">Book Now</a>
  </div>
</section>

<!-- Coaches Section -->
<section id="team">
  <h2>Meet Our Coaches</h2>
  <p>Expert coaching to help you reach your full potential</p>

  <div class="coach">
    <img src="/assets/img/team/coach-adam.jpg" alt="Coach Adam founder Charlotte soccer training">
    <h3>Coach Adam</h3>
    <p>Founder & Lead Coach. Expert in youth development and skill building for players in Charlotte, NC.</p>
  </div>

  <div class="coach">
    <img src="/assets/img/team/coach-luca.jpg" alt="Coach Luca head coach Charlotte soccer training">
    <h3>Coach Luca</h3>
    <p>Head Coach. Specializes in tactical analysis and advanced training techniques for elite soccer players.</p>
  </div>
</section>

<!-- Timeline / Story Section -->
<section id="timeline">
  <h2>Our Journey</h2>
  <p>How Charlotte Soccer Training was built to develop elite players</p>

  <div class="timeline-event">
    <h3>Founded by Coach Adam</h3>
    <span>2015</span>
    <p>Coach Adam started private soccer training sessions in Charlotte, NC with a focus on individual skill development.</p>
    <img src="/assets/img/timeline/founding.jpg" alt="Coach Adam founding Charlotte Soccer Training">
  </div>

  <div class="timeline-event">
    <h3>Coach Luca Joins</h3>
    <span>2018</span>
    <p>Coach Luca joined as Head Coach, bringing advanced game analysis and tactical expertise to our programs.</p>
    <img src="/assets/img/timeline/coach-luca.jpg" alt="Coach Luca head coach">
  </div>
</section>

<!-- Popup Modal -->
<div id="promoModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <h2>Book Your First Session!</h2>
    <p>Get 10% off your first one-on-one training session with Coach Adam or Coach Luca.</p>
    <a href="https://calendly.com/your-link" target="_blank" class="btn btn-primary">Book Now</a>
  </div>
</div>

<script>
var modal = document.getElementById("promoModal");
var span = document.getElementsByClassName("close")[0];
window.onload = function() { modal.style.display = "block"; };
span.onclick = function() { modal.style.display = "none"; };
window.onclick = function(event) { if(event.target == modal){ modal.style.display = "none"; } };
</script>
