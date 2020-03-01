---
title: "HF Radio Pre-Operations"
categories:
  - Blog
  - Equipment
tags:
  - Equipment
  - Operations
  - Standard
gallery:
  - url: /assets/images/gallery-003/MILITARY J-37 KEY and j-45 LEG CLAMP-01-600x.jpg
    image_path: /assets/images/gallery-003/MILITARY J-37 KEY and j-45 LEG CLAMP-01-600x.jpg
    alt: "Military Leg Key"
    title: "MILITARY J-37 and J-45 LEG CLAMP"
  - url: /assets/images/gallery-003/MILITARY J-37 KEY and j-45 LEG CLAMP-02-600x.jpg
    image_path: /assets/images/gallery-003/MILITARY J-37 KEY and j-45 LEG CLAMP-02-600x.jpg
    alt: "Military Leg Key"
    title: "MILITARY J-37 and J-45 LEG CLAMP"
gallery2:
  - url: /assets/images/gallery-003/Astron RS-35M-AP-powersupply-install-01-800x.jpg
    image_path: /assets/images/gallery-003/Astron RS-35M-AP-powersupply-install-01-800x.jpg
    alt: "ASTRON RS-35M Power Supply - Close View"
    title: "ASTRON RS-35M Power Supply - Close View"
  - url: /assets/images/gallery-003/Astron RS-35M-AP-powersupply-install-03-Anotated-800x.jpg
    image_path: /assets/images/gallery-003/Astron RS-35M-AP-powersupply-install-03-Anotated-800x.jpg
    alt: "ASTRON RS-35M Power Supply - Annotated  View"
    title: "ASTRON RS-35M Power Supply - Annotated  View"
gallery3:
  - url: /assets/images/gallery-003/ANTENNA-02-Anotations-800x.jpg
    image_path: /assets/images/gallery-003/ANTENNA-02-Anotations-800x.jpg
    alt: "Antenna Installation - "
    title: "Antenna Installation - "
  - url: /assets/images/gallery-003/ANTENNA-03-Anotations-800x.jpg
    image_path: /assets/images/gallery-003/ANTENNA-03-Anotations-800x.jpg
    alt: "Antenna Installation - "
    title: "Antenna Installation - "
  - url: /assets/images/gallery-003/ANTENNA-04-Anotations-800x.jpg
    image_path: /assets/images/gallery-003/ANTENNA-04-Anotations-800x.jpg
    alt: "Antenna Installation - "
    title: "Antenna Installation - "
  - url: /assets/images/gallery-003/ANTENNA-01-Anotations-800x.jpg
    image_path: /assets/images/gallery-003/ANTENNA-01-Anotations-800x.jpg
    alt: "Antenna Installation - "
    title: "Antenna Installation - "
---
`231833Z FEB 20`
---
The *sooner-than-expected* acquisition of the HF Transceiver [(Yeasu FT-891)][1] initiated a flurry of activity and new new equipment purchases to put it in operation.  

1. The already acquired [EFHW-8010 Antenna][2] needed to be installed.
2. A straight key was needed for CW (Morse Code)
3. An upgraded DC power source (See "Power Supply Workings" below).  A replacement to the two Lead-Acid batteries that powered the [Yeasu FT-7900][3].  

At max power (100W), the Yeasu FT-891 was close to maxing the amperage available on the largest of the two batteries.
{: .notice--warning}

The Morse Code key arrived first.  The familiar F-37 attached to F-45 Leg Clamp arrived (EBay)

<figure>
{% include gallery id="gallery" caption="Military Leg Key" %}
</figure>

**Power Supply Workings**

**Yeasu FT-891 - Current draw (Actual)**

**Recieve= 1.03a**

**Transmit:**

| WATTS |  AMPS |
|:-----:|:-----:|
|   5w  |  5.7a |
|  10w  |  6.9a |
|  20w  |  8.3a |
|  30w  |  9.3a |
|  40w  | 10.4a |
|  50w  | 11.5a |
|  60w  | 12.2a |
|  70w  | 12.0a |
|  80w  | 13.7a |
|  90w  | 14.4a |
|  100w | 15.2a |


A new power supply was purchased off the local market (Ham Radio Outlet).  This is the ASTRON RS-35M-AP.  The "AP" standing for Anderson Power Poles.  Having no Anderson Power Poles, or means to attach them, these were acquired through Amazon.

<figure>
{% include gallery id="gallery2" caption="ASTRON RS-35M-AP Power Supply" %}
</figure>

With fair weather for the weekend the antenna was installed.  The full 130 feet of antenna wire was stretched out horizontally and oriented NE/SW.

<figure>
{% include gallery id="gallery3" caption="EFHW 8010 Antenna Installation" %}
</figure>

The Yeasu FT-891 was powered on for the first time at:  **232345Z FEB 20**  No transmissions were attempted while a study is made to determine the initial settings and not damage the radio. Reception from the new antenna was incredible. The FT-891 has a great sound.

Reception was tested on the [SDR RSP1A][4].  A huge increase in signals was noted as compared to the discone antenna.
{: .notice--success}

[1]: https://www.yaesu.com/indexVS.cfm?cmd=DisplayProducts&ProdCatID=102&encProdID=DF4DB262968932E999EAF928B5B6A1A7&DivisionID=65&isArchived=0
[2]: https://myantennas.com/wp/product/efhw-8010/
[3]: https://www.yaesu.com/indexVS.cfm?cmd=DisplayProducts&ProdCatID=106&encProdID=2804F70E1A8F3C4B638CB8E0F201158C&DivisionID=65&isArchived=0
[4]: https://www.sdrplay.com/rsp1a/