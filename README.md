 <div id="top"></div>

<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->

<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

  <h3 align="center">PLANETS PCB</h3>

  <p align="center">
    The pcb for the connector board. This is to negate the excess use of wires and fit snuggly into the case.
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li><a href="#Component List">Component List</a></li>
    <li><a href="#block-diagram">Block Diagram</a></li>
    <li><a href="#schematic">Schematic</a></li>
    <li><a href="#pcb-layout">PCB Layout</a></li>
    <li><a href="#dimensions">Dimensions</a></li>
    <li><a href="#order details">Order Details</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About the Project

Project Link: [https://github.com/MSD-RIT-NASA](https://github.com/MSD-RIT-NASA)

This PCB was created for the intention to be used with the Gamification and Performanced Based Monitoring of Sensorimotor Activities project with NASA. This project, also known as PLANETs, is being developed by a Multidiciplinary Team at RIT. The objective of the project is to train an astronauts sense of blance when they return from long suspended time in space or to adapt themselves to a new planet's gravity. The game was meant to be a fun and competitive way to train the balance and activly collect and calculate data on their performace. These sensors interface with the SlimeVR program to create a skeleton that configures a persons center of balance, and creates a score. Another sensor is used under a balance board to relay the rotation of the board to the game. The game reflects a position back to the player in order to encourage them to adjust the angle of the balance board according to the game. The game awards the adjusted balance with game points, and negates points when they do not accuratly move the board. 

[![Front of PCB][front-3dview]]()
[![Back of PCB][back-3dview]]()

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

The pcb and schematic were designed in KiCad and ordered on JLCPCB

* [KiCad](https://www.kicad.org/)
* [JLCPCB](https://jlcpcb.com/)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- Component List -->
## Component List

Name | Symbol | Footprint | Purchase Link
--- | --- | --- | ---
RGB LED | Device:LED_RGBK | LED_THT:LED_D5.0mm-4_RGB | [LINK](https://www.sparkfun.com/products/9264)
150Ω | Device:R | 150Ω | [LINK](https://www.amazon.com/BOJACK-Values-Resistor-Resistors-Assortment/dp/B08FD1XVL6/ref=sr_1_3?crid=376HQO3UGCP0Y&keywords=variety+of+resistors&qid=1677360743&sprefix=variety+of+resistors%2Caps%2C124&sr=8-3)
180KΩ | Device:R | 180KΩ | [LINK](https://www.digikey.com/en/products/detail/te-connectivity-passive-product/ROX3SJ180K/2390251)
3.7V Lipo Battery| --- | --- | [LINK](https://www.digikey.com/en/products/detail/jauch-quartz/LP503759JU-PCM-2-WIRES-70MM/9560991)
Battery Connector | Connector:Conn_01x02_Female | JST_PH_S2B-PH-K_02x2.00mm_Angled | [LINK](https://www.digikey.com/en/products/detail/jst-sales-america-inc/S2B-PH-K-S-LF-SN/926626) [LINK](https://www.digikey.com/en/products/detail/jst-sales-america-inc/PHR-2/608607)
1N5817 Diode | SlimeVRMotherBoard-cache:Diode_1N5817 | Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal | [LINK](https://www.digikey.com/en/products/detail/stmicroelectronics/1N5817/770971)
1N5817 Diode | SlimeVRMotherBoard-cache:Diode_1N5817 | Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal | [LINK](https://www.digikey.com/en/products/detail/stmicroelectronics/1N5817/770971)
TP4056 Type-C | SlimeVRLibrary:4056Board | 4056Board | [LINK](https://www.amazon.com/gp/product/B07PZ6V937/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
Switch | SlimeVRLibrary:SlideSwitch | Wowoone_Slide_Switch_5mm | [LINK](https://www.amazon.com/gp/product/B07XSJYYYB/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
D1 mini | wemos_mini:WeMos_D1_mini | wemos-d1-mini-with-pin-header-and-connector | [LINK](https://www.amazon.com/gp/product/B081PX9YFV/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&th=1)
BNO085 Sensor | BNO085:4754 | BNO085 | [LINK](https://www.digikey.com/en/products/detail/adafruit-industries-llc/4754/13426653)
BNO085 AUX Sensor Connector | Connector:Conn_01x05_Female | JST_XH_S05B-XH-A_05x2.50mm_Angled | [LINK](https://www.digikey.com/en/products/detail/jst-sales-america-inc./S5B-XH-A-1(LF)(SN)/9961924) [LINK](https://www.digikey.com/en/products/detail/jst-sales-america-inc/XHP-5/1125486)
Status Rail Connector | Connector:Conn_01x05_Female | fivePinConn | ---


<p align="right">(<a href="#top">back to top</a>)</p>


<!-- BLOCK DIAGRAM -->
## Block Diagram
[![Block Diagram][block-diagram]]()


<!-- SCHEMATIC -->
## Schematic
[![schematic][schematic]]()


<!-- PCB LAYOUT -->
## PCB Layout
[![pcb-layout][pcb-layout]]()


<!-- DIMENSIONS -->
## Dimensions

PCB Dimensions: 71.394mm x 41.148mm

<!-- Order Details -->
## Order Details
[![order1][order1]]()
[![order2][order2]]()

Note: A non-green (in this case, black) PCB takes shipping 2 days longer

<!-- CONTACT -->
## Contact
Name | Major | email | github | year
--- | --- | --- | --- | ---
Angela Hudak | CE | ach2414@rit.edu | angelahudak | 2023
Corey Sheridan | CE | cjs5445@rit.edu | cjs5445 | 2023



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[block-diagram]: images/block_diagram.png
[schematic]: images/schematic.png
[front-3dview]: images/front_v1.PNG
[back-3dview]: images/back_v1.PNG
[order1]: images/order.PNG
[order2]: images/order2.PNG
[pcb-layout]: images/pcb-layout.PNG
