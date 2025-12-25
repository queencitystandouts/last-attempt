---
layout: home
title: "Private Soccer Training in Charlotte, NC | Coach Adam & Coach Luca"
description: "One-on-one soccer training, small group sessions, and game analysis in Charlotte, NC. Improve your skills with expert coaching."
seo:
  keywords: "soccer training Charlotte, private soccer coach Charlotte NC, one-on-one soccer training, small group training, game analysis"
---

<!-- Inline CSS for Teal / White / Black Theme -->
<style>
body { font-family: "Helvetica Neue", Arial, sans-serif; color:#000000; background-color:#ffffff; }

/* Buttons */
.btn, .btn-primary { background-color: #008080; color: #ffffff; padding: 10px 20px; border-radius: 5px; font-weight:bold; text-decoration:none; display:inline-block; }
.btn:hover, .btn-primary:hover { background-color: #006666; color:#ffffff; }

/* Navbar / Header */
header, .navbar { background-color:#000000; }
header a, .navbar a { color:#ffffff; }
header a:hover, .navbar a:hover { color:#008080; }

/* Footer */
footer { background-color:#000000; color:#ffffff; padding: 20px 0; }
footer a { color:#ffffff; }
footer a:hover { color:#008080; }

/* Sections */
section { background-color:#ffffff; color:#000000; padding: 60px 20px; }

/* Hero */
#hero h1 { color:#008080; font-size: 48px; margin-bottom: 20px; }
#hero p { color:#000000; font-size: 20px; margin-bottom: 30px; }

/* Popup Modal */
.modal { display:none; position:fixed; z-index:9999; padding-top:15%; left:0; top:0; width:100%; height:100%; overflow:auto; background-color: rgba(0,0,0,0.7); }
.modal-content { background-color:#ffffff; margin:auto; padding:20px; border-radius:10px; width:80%; max-width:450px; text-align:center; }
.modal-content h2 { color:#008080; }
.modal-content p { color:#000000; }
.close { color:#000000; float:right; font-size:28px; font-weight:bold; cursor:pointer; }
.close:hover { color:#008080; }
</style>

<!-- Hero Section (Inline to guarantee display) -->
<section id="hero" style="background-image: url('/assets/img/header-private-soccer-training-charlotte.jpg'); background-size: cover; background-position: center; text-align:center; padding: 120px 20px;">
  <h1>{{ site.data.sitetext.en.header.title }}</h1>
  <p>{{ site.data.sitetext.en.header.text }}</p>
  <a href="{{ site.data.sitetext.en.header.buttonlink }}" class="btn btn-primary">{{ site.data.sitetext.en.header.button }}</a>
</section>

<!-- Services Section -->
<section id="services">
  <h2>{{ site.data.sitetext.en.services.title }}</h2>
  <p>{{ site.data.sitetext.en.services.text }}</p>

  {% for service in site.data.sitetext.en.services.list %}
  <div class="service">
    <h3>{{ service.title }}</h3>
    <p>{{ service.desc }}</p>
    <a href="https://calendly.com/your-link" target="_blank" class="btn btn-primary">Book Now</a>
  </div>
  {% endfor %}
</section>

<!-- Coaches Section -->
<section id="team">
  <h2>{{ site.data.sitetext.en.team.title }}</h2>
  <p>{{ site.data.sitetext.en.team.text }}</p>

  {% for person in site.data.sitetext.en.team.people %}
  <div class="coach">
    <img src="{{ person.image }}" alt="{{ person.name }} - {{ person.role }}">
    <h3>{{ person.name }}</h3>
    <p>{{ person.role }}</p>
  </div>
  {% endfor %}
</section>

<!-- Timeline / Story Section -->
<section id="timeline">
  <h2>{{ site.data.sitetext.en.timeline.title }}</h2>
  <p>{{ site.data.sitetext.en.timeline.text }}</p>

  {% for event in site.data.sitetext.en.timeline.events %}
  <div class="timeline-event">
    <h3>{{ event.title }}</h3>
    <span>{{ event.year }}</span>
    <p>{{ event.desc }}</p>
    <img src="{{ event.image }}" alt="{{ event.alt }}">
  </div>
  {% endfor %}
</section>

<!-- About Section -->
<section id="about">
  <h2>{{ site.data.sitetext.en.about.title }}</h2>
  <p>{{ site.data.sitetext.en.about.text }}</p>
  <div>{{ site.data.sitetext.en.about.body | markdownify }}</div>
</section>

<!-- Popup Modal -->
<div id="clinicModal" class="modal">
  <div class="modal-content">
    <span class="close">&times;</span>
    <h2>Join Our Free Soccer Clinic!</h2>
    <p>Every Sunday at noon — come see what it's all about.</p>
    <a href="https://calendly.com/your-link" target="_blank" class="btn btn-primary">Reserve Your Spot</a>
  </div>
</div>

<script>
var modal = document.getElementById("clinicModal");
var span = document.getElementsByClassName("close")[0];
window.onload = function() { modal.style.display = "block"; };
span.onclick = function() { modal.style.display = "none"; };
window.onclick = function(event) { if(event.target == modal){ modal.style.display = "none"; } };
</script>
