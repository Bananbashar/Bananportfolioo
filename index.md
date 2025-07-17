---
layout: default
title: Welcome !
---
<style>
body::before {
  content: "";
  position: fixed;
  top: 0; left: 0;
  width: 100%; height: 100%;
  background: rgba(0, 0, 0, 0.4); /* شفافية سوداء */
  z-index: -1;
}
body {
  background-image: url("assets/images/6.jpg");
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  background-position: center;
  color: white;
}
</style>


<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; gap: 40px; margin-top: 80px;">

  <a href="/about" style="text-align: center; text-decoration: none; color: black;">
    <img src="/assets/images/icon-about.png" alt="About Me" style="width: 100px;">
    <div style="margin-top: 10px;">About Me</div>
  </a>

  <a href="/work" style="text-align: center; text-decoration: none; color: black;">
    <img src="/assets/images/icon-work.png" alt="Work" style="width: 100px;">
    <div style="margin-top: 10px;">Work</div>
  </a>

  <a href="/projects" style="text-align: center; text-decoration: none; color: black;">
    <img src="/assets/images/icon-projects.png" alt="Projects" style="width: 100px;">
    <div style="margin-top: 10px;">Projects</div>
  </a>

  <a href="/contact" style="text-align: center; text-decoration: none; color: black;">
    <img src="/assets/images/icon-contact.png" alt="Contact Me" style="width: 100px;">
    <div style="margin-top: 10px;">Contact Me</div>
  </a>

</div>
