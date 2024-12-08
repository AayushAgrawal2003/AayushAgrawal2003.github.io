---
title: "Bolt - Autonomous Institute Shuttle"
excerpt: "Level 5 autonomous shuttle for IIT Madras, integrating cutting-edge perception and planning algorithms for real-world campus deployment.<br/><img src='/images/500x300.png'>"
collection: portfolio
---

This is an item in your portfolio. It can be have images or nice text. If you name the file .md, it will be parsed as markdown. If you name the file .html, it will be parsed as HTML. 
---
title: "Bolt - Autonomous Institute Shuttle"
excerpt: "Level 5 autonomous shuttle for IIT Madras, integrating cutting-edge perception and planning algorithms for real-world campus deployment."
collection: portfolio
---

This is an item in your portfolio. It can have images or nice text. 

<div class="slideshow-container">
  <div class="slide">
    <img src="/images/500x300_1.png" style="width:100%">
  </div>
  <div class="slide">
    <img src="/images/500x300_2.png" style="width:100%">
  </div>
</div>

<style>
.slideshow-container {
  position: relative;
  width: 100%;
  max-width: 500px;
  margin: auto;
  overflow: hidden;
}

.slide {
  display: none;
}

.slide:first-child {
  display: block;
}
</style>

<script>
document.addEventListener("DOMContentLoaded", function () {
  let slides = document.querySelectorAll(".slide");
  let currentIndex = 0;

  setInterval(() => {
    slides[currentIndex].style.display = "none";
    currentIndex = (currentIndex + 1) % slides.length;
    slides[currentIndex].style.display = "block";
  }, 3000); // Change slide every 3 seconds
});
</script>
