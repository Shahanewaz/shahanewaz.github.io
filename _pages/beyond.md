---
title:        "Who I Am Outside the Lab"
permalink:    /beyond/
layout:       single
author_profile: true
classes:      wide
---

<style>
.outside-row {
  display: flex;
  flex-wrap: wrap;
  align-items: flex-start;
  gap: 1.5rem;
  margin-bottom: 2.5rem;
}
.outside-row .text {
  flex: 1 1 60%;
}
.outside-row img {
  max-width: 100px;
  height: auto;
  object-fit: contain;
  border-radius: 6px;
}
  
</style>

<div class="outside-row">
  <div class="text">
    <h3>🌍 A Passion for Exploration</h3>
    <p>I have always loved exploring new places, and to date, I have traveled through more than 25 U.S. states. Many of those trips have taken me to national parks, scenic byways, and hidden natural gems across the country. Living in Chattanooga, Tennessee has been a perfect match for that passion. It is surrounded by beautiful landscapes and has been officially recognized as the nation's first <a href="https://chattanooga.gov/stay-informed/latest-news/its-official-chattanooga-becomes-first-national-park-city-north-america"><strong>National Park City</strong></a>, celebrating its commitment to nature, accessibility, and outdoor living.</p>
  </div>
</div>

<div class="outside-row">
  <div class="text">
    <h3>⚽ Soccer, the Beautiful Game</h3>
    <p>I am a big fan of the English Premier League, and I have been proudly supporting <strong>Arsenal</strong> for years. From thrilling comebacks to heartbreak finishes, the highs and lows of following the Gunners are part of my weekly rhythm. <strong>COYG!</strong> <em>(Come On You Gunners!)</em></p>
  </div>
</div>

<div class="outside-row">
  <div class="text">
    <h3>🏸 Active on and off the field</h3>
    <p>In addition to watching soccer, I enjoy playing both soccer and badminton. It is mostly badminton these days. I have taken part in several local tournaments and find it to be a fun and energizing way to stay active.</p>
  </div>
</div>

## 📸 Snapshots from Life

<div class="slideshow-container">

  <div class="mySlides fade">
    <img src="{{ '/images/chattanooga.jpg' | relative_url }}" alt="Chattanooga">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/florida.jpg' | relative_url }}" alt="Florida">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/workshop.jpg' | relative_url }}" alt="Workshop">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/office_view.jpg' | relative_url }}" alt="Office View">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/las_vegas.jpg' | relative_url }}" alt="Las vegas">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/arizona.jpg' | relative_url }}" alt="Arizona">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/badminton_2.jpg' | relative_url }}" alt="Badminton Group">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/phd.jpg' | relative_url }}" alt="Major Prof">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/ga_aqua.jpg' | relative_url }}" alt="GA aquarium">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/fnf.jpeg' | relative_url }}" alt="Family and Friends">
  </div>

  <div class="mySlides fade">
    <img src="{{ '/images/soccer.jpeg' | relative_url }}" alt="Soccer Group">
  </div>

  <!-- Arrows -->
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  <!-- Dots -->
  <div class="dots-container">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
    <span class="dot" onclick="currentSlide(4)"></span>
    <span class="dot" onclick="currentSlide(5)"></span>
    <span class="dot" onclick="currentSlide(6)"></span>
    <span class="dot" onclick="currentSlide(7)"></span>
    <span class="dot" onclick="currentSlide(8)"></span>
    <span class="dot" onclick="currentSlide(9)"></span>
    <span class="dot" onclick="currentSlide(10)"></span>
    <span class="dot" onclick="currentSlide(11)"></span>
  </div>

</div>

<style>
.slideshow-container {
  position: relative;
  max-width: 800px;
  margin: 2rem auto;
  border-radius: 12px;
  overflow: hidden;
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
}

.mySlides {
  display: none;
}

.mySlides img {
  width: 100%;
  height: 420px;
  object-fit: cover;
  display: block;
}

.prev, .next {
  cursor: pointer;
  position: absolute;
  top: 50%;
  padding: 16px;
  color: white;
  font-weight: bold;
  font-size: 24px;
  transition: 0.3s ease;
  border-radius: 0 3px 3px 0;
  user-select: none;
  z-index: 10;
}

.next {
  right: 0;
  border-radius: 3px 0 0 3px;
}

.prev:hover, .next:hover {
  background-color: rgba(0, 0, 0, 0.5);
}

.dots-container {
  text-align: center;
  background: #fff;
  padding: 10px 0;
}

.dot {
  height: 12px;
  width: 12px;
  margin: 0 6px;
  background-color: #bbb;
  border-radius: 50%;
  display: inline-block;
  cursor: pointer;
  transition: background-color 0.3s;
}

.dot.active {
  background-color: #007bff;
}

@media (max-width: 600px) {
  .mySlides img {
    height: 250px;
  }
  .prev, .next {
    font-size: 18px;
    padding: 10px;
  }
}
</style>

<script>
let slideIndex = 1;
let slideTimer;

function showSlides(n) {
  const slides = document.getElementsByClassName("mySlides");
  const dots = document.getElementsByClassName("dot");
  if (n > slides.length) { slideIndex = 1; }
  if (n < 1) { slideIndex = slides.length; }
  for (let slide of slides) {
    slide.style.display = "none";
  }
  for (let dot of dots) {
    dot.classList.remove("active");
  }
  slides[slideIndex - 1].style.display = "block";
  dots[slideIndex - 1].classList.add("active");

  clearTimeout(slideTimer);
  slideTimer = setTimeout(() => plusSlides(1), 5000);
}

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

document.addEventListener("DOMContentLoaded", () => {
  showSlides(slideIndex);
});
</script>
