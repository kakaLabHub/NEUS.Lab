---
layout: archive
title: "Contact Us"
permalink: /contact/
author_profile: true
author: neus_lab
---

{% include base_path %}

<style>
.greedy-nav .visible-links a::before { transform: scaleX(0); }
.greedy-nav .visible-links a:hover::before { transform: scaleX(1); }
@media (min-width: 925px) {
    .sidebar.sticky { top: 7.5rem; max-height: calc(100vh - 9rem); overflow-y: auto; }
}
.sidebar .author__name { text-align: center; }
.contact-image-wrap { position: relative; width: 90%; margin: 0 auto 1.5rem; }
.contact-image { display: block; width: 100%; height: auto; }
.contact-image-caption { position: absolute; top: 1.25rem; left: 1.5rem; margin: 0; color: #fff; font-size: clamp(1rem, 2.1vw, 1.6rem); font-weight: 700; line-height: 1.3; text-shadow: 0 2px 8px rgba(0,0,0,.75); }
.contact-address { margin: 0 auto; text-align: center; font-style: normal; font-weight: 700; line-height: 1.75; }
@media (max-width: 760px) {
    .contact-image-wrap { width: 100%; }
    .contact-image-caption { top: .85rem; left: 1rem; }
}
</style>

<div class="contact-image-wrap">
  <img class="contact-image" src="{{ base_path }}/images/university1.jpg" alt="Sun Yat-sen University campus">
  <p class="contact-image-caption">Welcome to Guangzhou, China, and Sun Yat-sen University</p>
</div>

<address class="contact-address">
  <a href="https://gp.sysu.edu.cn/teacher/4661" target="_blank" rel="noopener">School of Geography and Planning, Sun Yat-sen University<br>Panyu District, Guangzhou, China</a>
</address>
