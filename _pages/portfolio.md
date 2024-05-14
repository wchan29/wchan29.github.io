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

intro: 
  - excerpt: I am currently in the process of updating/adding new items to my portfolio, some pages here are not fully completed yet. I am hoping to have them done by the end of August.

feature_row:
- url: /portfolio/wempec_eturbo/
  image_path: /images/gallery_cover/Turbocharger_nasa.png
  title: Bearingless Machines (BSPM) for Aerial E-Turbocharger Application
  excerpt: Army Research Laboratory (ARL) and UW’s ERC & Severson Research Group to explore using bearingless motor technology to create a new generation of electric turbochargers for aerial vehicles.
  btn_class: btn--primary
  btn_label: "Read More"

- url: https://emach.readthedocs.io/en/latest/index.html
  image_path: /images/gallery_cover/eMach.png
  title: eMach
  excerpt: An open-source electric machine modeling, evaluation, and optimization framework developed in Python.
  btn_class: btn--primary
  btn_label: "Read More"

# - url: https://github.com/wchan29/motor_winding_helper/tree/develop
#   image_path: /images/gallery_cover/voltage_phasor_cover.JPG
#   title: Motor Winding Helper
#   excerpt: A small python project for plotting machine winding voltage phasor
#   btn_class: btn--primary
#   btn_label: "Read More"

feature_row2:
- url: /portfolio/wempec_additive_housing/
  image_path: /images/gallery_cover/add_housing_cover.JPG
  title: AlSi10Mg Additively Manufactured Generator Housing with Integrated Cooling Channels
  excerpt: Department of Energy Project on High Efficiency Combined Heat and Power (CHP) Generation. 
  btn_class: btn--primary
  btn_label: "Read More"

- url: /portfolio/wempec_mini_dyne/
  image_path: /images/gallery_cover/wempec_mini_dyne_front.jpg
  title: 10N-m Mini Dynamometer Prototype
  excerpt: A small-scale dynamometer prototype used for characterizing small form factor rotatry electric machines. Capable of torque measurement of up to 10Nm and speed of 3000RPM.
  btn_class: btn--primary
  btn_label: "Read More"

- url: /portfolio/wempec_linear_fixture/
  image_path: /images/gallery_cover/wempec_linear_fixture_1.jpeg
  title: Linear Electric Machine Test Fixture
  excerpt: A test fixture designed and built for conducting force measurement on a linear electric machine with a HAAS CNC TM-1 mill.
  btn_class: btn--primary
  btn_label: "Read More"

- url: /portfolio/wempec_induction_3d/
  image_path: /images/gallery_cover/induction_machine_main.JPG
  title: Compact Induction Machine with 3D Printed Housing
  excerpt: UW-Madison Mechanical Engineering senior design project for the Grainger Engineering Design Innovation Lab.
  btn_class: btn--primary
  btn_label: "Read More"

- url: /portfolio/stirling_engine/
  image_path: /images/gallery_cover/stirling_engine_cover1.jpeg
  title: Stirling Engine Build and Redesign
  excerpt: A semester long project to build and redesign of a thermo-mechanical device (Stirling Engine).
  btn_class: btn--primary
  btn_label: "Read More"

- url: /portfolio/cherry_walnut_board/
  image_path: /images/gallery_cover/walnut_board_cover.jpeg
  title: Maple-Walnut Cutting Board
  excerpt: An edge-grain cutting board made out of cherry and walnut, a graduation gift for a friend.
  btn_class: btn--primary
  btn_label: "Read More"

photo_gallery:
- url: https://photos.app.goo.gl/nLpJnqviTFK3v8zf9
  title: Photo Gallery
  excerpt: Photo album for various past projects.
  btn_label: View Here
  btn_class: btn--info
---

<style>
  #show_bg {
    background-image: linear-gradient(to bottom, rgba(255, 255, 255, 0.6), rgba(255, 255, 255, 0.6)),
    url('/images/gallery_cover/photo_gallery.png');
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

    
</style>

<!-- {% include feature_row id="intro" type="center"%} -->

# Active Projects
{: .text-center}
<br/>

{% include feature_row %}

# Past Projects
{: .text-center}
<br/>


{% include feature_row id="feature_row2"%}

<!-- {% include feature_row id="photo_gallery" type="center"%} -->

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