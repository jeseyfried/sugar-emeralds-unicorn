---
title: Seyfried Research Story
layout: base
date: 2024-12-02
---
<div class="jumbotron" style="position: relative; overflow: hidden; width: 100%; height: 400px; margin-bottom: 2rem;">
  <video id="heroVideo"
         autoplay
         muted
         loop
         playsinline
         style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; object-fit: cover; z-index: 1;">
    <source src="{{site.baseurl}}/assets/sugar-emeralds-unicorn.mp4" type="video/mp4">
  </video>
  <div class="jumbotron-overlay" 
       style="position: relative; z-index: 2; color: white; text-shadow: 0 2px 10px black; display: flex; flex-direction: column; justify-content: center; align-items: center; height: 100%;">
    <h1>Sugar, Emeralds, and Unicorn Horn</h1>
    <h2>In Medieval Mediterranean Trade Networks</h2>
  </div>
</div>

<script>
window.addEventListener('scroll', function() {
  var video = document.getElementById('heroVideo');
  // Pause video if page is scrolled down, play if at top
  if (window.scrollY > 10) {
    video.pause();
  } else {
    video.play();
  }
});
</script>
#A Research Story by Jonathan Seyfried

## Why did Matha Armagnac drink pulverized gemstones?
Info about Matha

## The Research Question: How did medieval apothecaries and merchants construct medical knowledge?
Info about substances and medicine

## Three Commodities, Three Pathways to Medicine
Info about the pathways

For more on adding features to your pages, see the documentation under the `Page Components` tab.
