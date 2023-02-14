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
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About the Project

[![Block Diagram][block-diagram]]()
<!-- [![Bottom of PCB][product-bottom]]() -->

About the Project

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

The pcb and schematic were designed in KiCad and ordered on OSHPark

* [KiCad](https://www.kicad.org/)
* [OSHPark]()

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- Component List -->
## Component List

Name | Symbol | Footprint | Purchase Link
--- | --- | --- | ---
Red LED | Device:LED | LED_THT:LED_D5.0mm | [LINK](https://www.digikey.com/en/products/detail/rohm-semiconductor/SLR-56VC3F/636991)
10Ω | Device:R | 10Ω | [LINK](https://www.digikey.com/en/products/detail/ohmite/43F10R/257947)
18Ω | Device:R | 18Ω | [LINK](https://www.digikey.com/en/products/detail/ohmite/42J18R/4295971)
180KΩ | Device:R | 180KΩ | [LINK](https://www.digikey.com/en/products/detail/te-connectivity-passive-product/ROX3SJ180K/2390251)
3.7V Lipo Battery Connector | Connector:Conn_01x02_Female | JST_PH_S2B-PH-K_02x2.00mm_Angled | [LINK](https://www.digikey.com/en/products/detail/jst-sales-america-inc/S2B-PH-K-S-LF-SN/926626) [LINK](https://www.digikey.com/en/products/detail/jst-sales-america-inc/PHR-2/608607)
1N5817 Diode | SlimeVRMotherBoard-cache:Diode_1N5817 | Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal | [LINK](https://www.digikey.com/en/products/detail/stmicroelectronics/1N5817/770971)
1N5817 Diode | SlimeVRMotherBoard-cache:Diode_1N5817 | Diode_THT:D_DO-41_SOD81_P10.16mm_Horizontal | [LINK](https://www.digikey.com/en/products/detail/stmicroelectronics/1N5817/770971)
TP4056 Type-C | SlimeVRLibrary:4056Board | 4056Board | [LINK](https://www.amazon.com/gp/product/B07PZ6V937/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
Switch | SlimeVRLibrary:SlideSwitch | Wowoone_Slide_Switch_5mm | [LINK](https://www.amazon.com/gp/product/B07XSJYYYB/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
D1 mini | wemos_mini:WeMos_D1_mini | wemos-d1-mini-with-pin-header-and-connector | [LINK](https://www.amazon.com/gp/product/B081PX9YFV/ref=ppx_yo_dt_b_asin_title_o02_s00?ie=UTF8&th=1)
BNO085 Sensor | BNO085:4754 | BNO085 | [LINK](https://www.digikey.com/en/products/detail/adafruit-industries-llc/4754/13426653)
BNO085 AUX Sensor Connector | Connector:Conn_01x05_Female | JST_XH_S05B-XH-A_05x2.50mm_Angled | [LINK](https://www.digikey.com/en/products/detail/jst-sales-america-inc./S5B-XH-A-1(LF)(SN)/9961924) [LINK](https://www.digikey.com/en/products/detail/jst-sales-america-inc/XHP-5/1125486)
Status Rail Connector | Connector:Conn_01x05_Female | fivePinConn | ---


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

1. Angela Hudak
    a. email: ach2414@rit.edu
2. Corey S


Project Link: [https://github.com/MSD-RIT-NASA](https://github.com/MSD-RIT-NASA)

PCB Dimensions: 71.394mm x 41.148mm


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->

[block-diagram]: images/schematic.png
