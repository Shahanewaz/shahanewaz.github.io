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
  
.photo-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(220px, 1fr));
  gap: 1.5rem;
  margin-bottom: 3rem;
}

.photo-item {
  border-radius: 10px;
  overflow: hidden;
  transition: box-shadow 0.3s ease, transform 0.3s ease;
}

.photo-item:hover {
  box-shadow: 0 0 0 4px rgba(0, 123, 255, 0.25); 
  transform: scale(1.03);
}

.photo-item img {
  width: 100%;
  height: 200px; 
  object-fit: cover;
  border-radius: 8px;
  display: block;
  transition: transform 0.3s ease;
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

<h3>📸 Snapshots from Life</h3>
<div class="photo-gallery">
  <div class="photo-item"><img src="{{ '/images/chattanooga.jpg' | relative_url }}" alt="Chattanooga"></div>
  <div class="photo-item"><img src="{{ '/images/florida.jpg' | relative_url }}" alt="Florida"></div>
  <div class="photo-item"><img src="{{ '/images/workshop.jpg' | relative_url }}" alt="Workshop"></div>
</div>
