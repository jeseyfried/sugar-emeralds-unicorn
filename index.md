---
title: Medieval Pharmacology Research Story
layout: base
date: 2024-12-02
---


# Sugar, Emeralds, and Unicorn Horn

<div class="jumbotron" style="position: relative; overflow: hidden; height: 400px;">
  <video id="Sugar Emeralds Unicorn Horn" 
         autoplay 
         muted 
         loop 
         playsinline 
         style="width: 100%; height: 100%; object-fit: cover;">
    <source src="/assets/sugar-emeralds-unicorn.mp4" type="video/mp4">
  </video>
  <div class="jumbotron-overlay">
    <!-- Sugar Emeralds and Unicorn Horn -->
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


{% include figure.html
  class="right"
  width="33%"
  caption="Xanthan chemical structure"
  image-path="/assets/images/Xanthan.svg"
  source-url="https://commons.wikimedia.org/wiki/File:Xanthan.svg"
%}


This is your home page! It's the `index.md` file in your repository.

For more information about your site works, see the `Website Guides` tab.

For more on adding features to your pages, see the documentation under the `Page Components` tab.
