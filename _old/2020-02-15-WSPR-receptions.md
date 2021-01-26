---
title: "151944Z FEB 20"
categories:
  - Blog
tags:
  - WSPR
  - Projects
  - DIY
  - Success
  - Operations
gallery:
  - url: /assets/images/gallery-002/first_WSPR_receive-001.JPG
    image_path: /assets/images/gallery-002/first_WSPR_receive-001.JPG
    alt: "First Reception Report"
    title: "First WSPR Reception Report - Map View"
  - url: /assets/images/gallery-002/first_WSPR_receive-002.JPG
    image_path: /assets/images/gallery-002/first_WSPR_receive-002.JPG
    alt: "First WSPR Reception Report - WSJT-X View"
    title: "First WSPR Reception Report - WSJT-X View"
  - url: /assets/images/gallery-002/first_WSPR_receive-003.JPG
    image_path: /assets/images/gallery-002/first_WSPR_receive-003.JPG
    alt: "More Reports . . . "
    title: "More Reports . . . "
  - url: /assets/images/gallery-002/first_WSPR_receive-004.JPG
    image_path: /assets/images/gallery-002/first_WSPR_receive-004.JPG
    alt: "More Reports . . . showing Texas! "
    title: "More Reports . . . showing Texas!"
  - url: /assets/images/gallery-002/first_WSPR_receive-006.JPG
    image_path: /assets/images/gallery-002/first_WSPR_receive-006.JPG
    alt: "More Reports . . . west coast USA!"
    title: "More Reports . . . west coast USA! "
  - url: /assets/images/gallery-002/first_WSPR_receive-007.JPG
    image_path: /assets/images/gallery-002/first_WSPR_receive-007.JPG
    alt: "More Reports . . . Europe and Africa!"
    title: "More Reports . . . Europe and Africa!"
  - url: /assets/images/gallery-002/first_WSPR_receive-009.JPG
    image_path: /assets/images/gallery-002/first_WSPR_receive-009.JPG
    alt: "More Reports . . . South America!"
    title: "More Reports . . . South America"
gallery2:
  - url: /assets/images/gallery-002/INSTA_Discone.jpg
    image_path: /assets/images/gallery-002/INSTA_Discone.jpg
    alt: "Discone Antenna at the PRC-TL-PF"
    title: "Discone Antenna at the PRC-TL-PF"
  - url: /assets/images/gallery-002/RSP1A-PRC-TL-PL.jpg
    image_path: /assets/images/gallery-002/RSP1A-PRC-TL-PL.jpg
    alt: "View showing the RSP1A"
    title: "View showing the RSP1A"
  - url: /assets/images/gallery-002/SDR-UNO+WSJT-X-WSPR.JPG
    image_path: /assets/images/gallery-002/SDR-UNO+WSJT-X-WSPR.JPG
    alt: "SDRUno software working with WSJT-X"
    title: "SDRUno software working with WSJT-X"
  - url: /assets/images/gallery-002/WSJT-X WSPR.JPG
    image_path: /assets/images/gallery-002/WSJT-X WSPR.JPG
    alt: "WSJT-X decoding WSPR Signals"
    title: "WSJT-X decoding WSPR Signals"
---
`WSPR Signal Reception and Decode`
---

Even with the failure of the WSPR QRPGuys kit build (see previous post) the PRC moves forward with configuring the receiving end of WSPR signals.  SDRUno and WSJT-X software were configured such that over a 24 hour test period, weak digital signals were decoded from all over the world as shown on the gallery maps. 
 
Reception reports were uploaded to [WSPRnet][7].  This website recieves the output from WSJT-X and plots it on a world map.  The 20 meter and 40 meter bands were the focus of the listening period although a brief listen on the 80 meter band yielding a couple successful reports.
 
<figure>
{% include gallery id="gallery" caption="WSPR Project 24 Hour Reception Test" %}
</figure>

The equipment and software involved were:
* Equipment -
  * Windows 10 workstation
  * Discone Antenna (Tram 1411 Broad Band)
  * [RSP1A (Radio Spectrum Processor)][1]
 
* Software -
  * [SDRUno (Software Defined Radio progarm)][2]
  * [WSJT-X][6]
  * [Virtual Audio Cable][5] 
 
Pineland Radio thanks the content creators of the YouTube channels:
* [SevenFortyOne] [3] 
* [SDRHamGuides] [4] 

Their educational videos were a great guide to getting the configuration portion ironed out.

<figure>
{% include gallery id="gallery2" caption="WSPR Project Equipment and Software" %}
</figure>

[1]: https://www.sdrplay.com/rsp1a/
[2]: https://www.sdrplay.com/downloads/
[3]: https://www.youtube.com/channel/UChintPJZoKbKUeaAOWpIOgg
[4]: https://www.youtube.com/channel/UCFqL7rX68aatRB0QESJLcqw
[5]: https://vac.muzychenko.net/en/
[6]: https://physics.princeton.edu/pulsar/K1JT/wsjtx.html
[7]: http://wsprnet.org/drupal/wsprnet/map

