---
layout: splash
title: "Projects"
excerpt: Active and Past Projects.
permalink: /portfolio/
author_profile: false
header: 
  overlay_color: #0a0a0a
  overlay_filter: rgba(240, 240, 240, 0.4)
  overlay_image: /images/portfolio/windings/bp5_stator.jpg

feature_row:
- #url: https://github.com/wchan29/motor_winding_helper/tree/develop
  image_path: /images/covers/pcb_render.png
  title: Overactuated PCB Axial Flux Motor
  excerpt: Printed circuit board (PCB) axial flux machine with overactuation control. Controllable axial force in quadrants with injected d-axis current.

feature_row2:
- url: /portfolio/wempec_eturbo/
  image_path: /images/covers/Turbocharger_nasa.png
  title: Bearingless Machines (BSPM) for Aerial E-Turbocharger Application
  excerpt: Army Research Laboratory (ARL) and UW’s ERC & Severson Research Group to explore using bearingless motor technology to create a new generation of electric turbochargers for aerial vehicles.

- url: /portfolio/wempec_additive_housing/
  image_path: /images/covers/add_housing_cover.JPG
  title: AlSi10Mg Additively Manufactured Generator Housing with Integrated Cooling Channels
  excerpt: Department of Energy Project on High Efficiency Combined Heat and Power (CHP) Generation. 

- url: https://github.com/Severson-Group/eMach
  image_path: /images/covers/eMach.png
  title: eMach
  excerpt: An open-source electric machine modeling, evaluation, and optimization framework developed in Python.

- url: /portfolio/wempec_mini_dyne/
  image_path: /images/covers/wempec_mini_dyne_front.jpg
  title: 10N-m Mini Dynamometer Prototype
  excerpt: A small-scale dynamometer prototype used for characterizing small form factor rotatry electric machines. Capable of torque measurement of up to 10Nm and speed of 3000RPM.

- url: /portfolio/wempec_linear_fixture/
  image_path: /images/covers/wempec_linear_fixture_1.jpeg
  title: Linear Electric Machine Test Fixture
  excerpt: A test fixture designed and built for conducting force measurement on a linear electric machine with a HAAS CNC TM-1 mill.

- url: /portfolio/wempec_induction_3d/
  image_path: /images/covers/induction_machine_main.JPG
  title: Compact Induction Machine with 3D Printed Housing
  excerpt: UW-Madison Mechanical Engineering senior design project for the Grainger Engineering Design Innovation Lab.

- url: /portfolio/stirling_engine/
  image_path: /images/covers/stirling_engine_cover1.jpeg
  title: Stirling Engine Build and Redesign
  excerpt: A semester long project to build and redesign of a thermo-mechanical device (Stirling Engine).

- url: /portfolio/cherry_walnut_board/
  image_path: /images/covers/walnut_board_cover.jpeg
  title: Maple-Walnut Cutting Board
  excerpt: An edge-grain cutting board made out of cherry and walnut, a graduation gift for a friend.

---

<style>
  #show_bg {
    background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0.6)),
    url('/images/covers/photo_gallery.png');
    width: 100%;
    height: 300px;
    background-size: cover;
    color: white;
    padding:100px
  }

  /* Container holding the image and the text */
  .container {
  position: relative;
  text-align: center;
  }

  /* Bottom right text */
  .text-block {
    position: absolute;
    top: 50%;
    left: 50%;
    background-color: black;
    opacity: 0.7;
    color: white;
    transform: translate(-50%, -50%);
    padding:40px;
    border-radius: 10px;
  }

  .container .btn {
  /* position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%); */
  background-color: #00BFFF;
  color: white;
  font-size: 16px;
  padding: 12px 24px;
  border: none;
  cursor: pointer;
  border-radius: 5px;
  }

  .container .btn:hover {
    background-color: #48D1CC;
  }

  /* Clickable project cards */
  /* equal-height cards per row once the theme floats them side by side */
  @media (min-width: 37.5em) {
    .feature__wrapper {
      display: flex;
      flex-wrap: wrap;
    }

    .feature__wrapper::after {
      display: none;
    }

    .feature__item {
      display: flex;
      margin-bottom: 1em;
    }

    .feature__item .feature__card-link {
      display: flex;
      flex: 1;
    }

    .feature__card {
      flex: 1;
    }
  }

  .feature__card-link {
    display: block;
    color: inherit;
    text-decoration: none;
  }

  /* override theme's `.page__content a:not(.btn):hover` underline and img shadow */
  .page__content a.feature__card-link:visited,
  .page__content a.feature__card-link:hover,
  .page__content a.feature__card-link:focus {
    color: inherit;
    text-decoration: none;
  }

  .page__content a.feature__card-link:hover img {
    box-shadow: none;
  }

  .feature__card {
    padding-bottom: 1em;
    border-radius: 12px;
    overflow: hidden;
    transition: transform 0.25s ease, box-shadow 0.25s ease, margin 0.25s ease, padding 0.25s ease;
  }

  .feature__card .archive__item-teaser {
    border-radius: 0;
    transition: border-radius 0.25s ease;
  }

  .feature__card .archive__item-teaser img {
    transition: transform 0.4s ease;
  }

  .feature__card-link:hover .feature__card,
  .feature__card-link:focus-visible .feature__card {
    transform: translateY(-6px);
    box-shadow: 0 12px 24px rgba(0, 0, 0, 0.15);
    /* grow outward so content stays put while the card gains side padding */
    margin: -12px -12px 0;
    padding: 12px 12px 1em;
  }

  .feature__card-link:hover .archive__item-teaser,
  .feature__card-link:focus-visible .archive__item-teaser {
    border-radius: 8px;
  }

  .feature__card-link:hover .archive__item-teaser img,
  .feature__card-link:focus-visible .archive__item-teaser img {
    transform: scale(1.05);
  }

  .feature__card-link:hover .archive__item-title,
  .feature__card-link:focus-visible .archive__item-title {
    text-decoration: underline;
  }

  @media (prefers-reduced-motion: reduce) {
    .feature__card,
    .feature__card .archive__item-teaser img {
      transition: none;
    }
  }

    
</style>
# Active Projects
{: .text-center}
<br/>

{% include feature_row %} 


# Past Projects
{: .text-center}
<br/>

{% include feature_row id="feature_row2"%}


<div class="container">
  <div id='show_bg'>
    <div class="text-block">
      <h1 style="color: white;">Interested in seeing more?</h1>
      <p>Check my photo gallery in Google Photos!</p>
      <a href="https://photos.app.goo.gl/nLpJnqviTFK3v8zf9"><button class="btn"><u>View Here</u></button></a>
    </div>
  </div>
</div>

<br/>