---
title: "291915Z FEB 20"
categories:
  - Blog
  - Equipment
tags:
  - Testing
  - Equipment
gallery:
  - url: /assets/images/gallery-004/EFHW-8010-DL-100ft-RG8X-inband-e1459571195823.jpg
    image_path: /assets/images/gallery-004/EFHW-8010-DL-100ft-RG8X-inband-e1459571195823.jpg
    alt: "MyAntennas.com advertised resonance for EFHW-8010"
    title: "MyAntennas.com advertised resonance for EFHW-8010"
  - url: /assets/images/gallery-004/NanoVNA-Sharp-001.JPG
    image_path: /assets/images/gallery-004/NanoVNA-Sharp-001.JPG
    alt: "NanoVNA analysis of EFHW-8010"
    title: "NanoVNA analysis of EFHW-8010"
gallery2:
  - url: /assets/images/gallery-004/NanoVNA-Sharp-10M.JPG
    image_path: /assets/images/gallery-004/NanoVNA-Sharp-10M.JPG
    alt: "10 Meter Band"
    title: "10 Meter Band"
  - url: /assets/images/gallery-004/NanoVNA-Sharp-20M.JPG
    image_path: /assets/images/gallery-004/NanoVNA-Sharp-20M.JPG
    alt: "20 Meter Band"
    title: "20 Meter Band"
  - url: /assets/images/gallery-004/NanoVNA-Sharp-40M.JPG
    image_path: /assets/images/gallery-004/NanoVNA-Sharp-40M.JPG
    alt: "40 Meter Band"
    title: "40 Meter Band"
  - url: /assets/images/gallery-004/NanoVNA-Sharp-80M.JPG
    image_path: /assets/images/gallery-004/NanoVNA-Sharp-80M.JPG
    alt: "80 Meter Band"
    title: "80 Meter Band"
gallery3:
  - url: /assets/images/gallery-004/NanoVNA-Sharp-80M.JPG
    image_path: /assets/images/gallery-004/NanoVNA-Sharp-80M.JPG
    alt: "80 Meter band before tuning with the MFJ-945E"
    title: "80 Meter band before tuning with the MFJ-945E"
  - url: /assets/images/gallery-004/NanoVNA-Sharp-80M-TUNED.JPG
    image_path: /assets/images/gallery-004/NanoVNA-Sharp-80M-TUNED.JPG
    alt: "80 Meter band AFTER tuning with the MFJ-945E"
    title: "80 Meter band AFTER tuning with the MFJ-945E"
---
`MFJ-945E and NanoVNA Acquired`
---

Cautious about damaging the new **Yeasu FT-891** the Pineland Radio Club wanted a means to analyze antennas.  Hence, a new manual antenna tuner [(MFJ-945E)][1] and [Vector Network Analyzer][2] were procured.

The [MyAntennas.com EFHW-8010][3] was advertised to be resonant on  the 80/40/30/20/17/15/12/10m bands as shown in the graphic from their website (below).  Needing to verify this, the Vector Network Analyzer aka NanoVNA was used to measure SWR between 1.7 Mhz (160 Meter band) and 29.7 Mhz (10 Meter band).

<figure>
{% include gallery id="gallery" caption="Resonance Charts" %}
</figure>

The results were as expected yet the SWR in the 80 meter band was worrisome and, still using the NanoVNA, each band was scutinized for SWR.

![Meter Band Analysis](/assets/images/gallery-004/NanoVNA-Sharp-003.jpg "Meter Band Analysis")

<figure>
{% include gallery id="gallery2" caption="Resonance Charts for Interested Bands" %}
</figure>

PRC staff are not mentally gifted and many hours of training were needed to grasp how to use a manual antenna tuner.  After-hours "remedial training" was mandated but there were no quitters.  The first positive results were gained only after grasping whether or not the tuner was in **By-Pass mode** and figuring out the use of the "Inductance" knob.  Specifically how it relates to noise levels.  Example of tuning out the SWR in the 80 Meter band are below and are a proud achievement of the PRC.

<figure>
{% include gallery id="gallery3" caption="Manual Tuning Results" %}
</figure>

[1]: https://www.mfjenterprises.com/Product.php?productid=MFJ-945E
[2]: https://www.amazon.com/gp/product/B07Z5VY7B6/ref=ppx_yo_dt_b_asin_title_o03_s01?ie=UTF8&psc=1
[3]: https://myantennas.com/wp/product/efhw-8010/
[4]: https://drive.google.com/drive/folders/1IZEtx2YdqchaTO8Aa9QbhQ8g_Pr5iNhr


**Success Notice:** A valuable and likely perishable skill (using a manual antenna tuner) was learned on this date. [Leap Day](#) Ditto with using the NanoVNA and the software NanoVNA Sharp.  The later software from [questionable sources on the internet][4].
{: .notice--success}
