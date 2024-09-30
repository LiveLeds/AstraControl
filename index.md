---
layout: home
---

{% assign cacheBust = site.time | date:'?v=%s' %}
[GitHub](https://github.com/alexanderp4580/astra-control-pcb)
[![CI](https://github.com/alexanderp4580/astra-control-pcb/actions/workflows/ci.yml/badge.svg)](https://github.com/alexanderp4580/astra-control-pcb/actions/workflows/ci.yml)
![Image]({{ "/images/AstraControl-3D_blender_top_angled.png" | relative_url | append: cacheBust }}){: width="400" }

ESP32-based control PCB uses WiFi with an external antenna and 5Mbps RS-485
for communication, supporting various sensors and HMI devices for high-power 
LED fixtures or strips. One device can act as master or all fixtures will receive 
data from a dedicated receiver.

## Table of contents

- [Table of contents](#table-of-contents)
  - [Render Top Angled](#render-top-angled)
  - [Render Top](#render-top)
  - [Render Bottom](#render-bottom)
  - [Interactive BOM](#interactive-bom)
  - [BOM](#bom)
  - [Schematic](#schematic)
    - [Dark](#dark)
    - [Monochromatic](#monochromatic)
    - [Light](#light)
  - [Assembly](#assembly)
    - [Dark](#dark-1)
    - [Light](#light-1)
  - [Downloads](#downloads)
    - [JLCPCB](#jlcpcb)
    - [Eurocircuits](#eurocircuits)
- [Report](#report)
    - [ERC](#erc)
    - [DRC](#drc)

### Render Top Angled

![Image]({{ "/images/AstraControl-3D_blender_top_angled.png" | relative_url | append: cacheBust }})

### Render Top

![Image]({{ "/images/AstraControl-3D_blender_top.png" | relative_url | append: cacheBust }})

### Render Bottom

![Image]({{ "/images/AstraControl-3D_blender_bottom.png" | relative_url | append: cacheBust }})

### Interactive BOM

Easily check component locations by hovering over a specific component.

[IBOM HTML]({{ "/export/AstraControl-ibom.html" | relative_url | append: cacheBust }})

### BOM

All components with Values, References, Sheetpath and Links to the datasheet.

[BOM HTML]({{ "/export/AstraControl-bom.html" | relative_url | append: cacheBust }})

### Schematic

#### Dark

- [Schematic Dark PDF]({{ "/documents/AstraControl-schematic-dark.pdf" | relative_url | append: cacheBust }})

#### Monochromatic

- [Schematic Monochromatic PDF]({{ "/documents/AstraControl-schematic-mono.pdf" | relative_url | append: cacheBust }})

#### Light

- [Schematic Light PDF]({{ "/documents/AstraControl-schematic-default.pdf" | relative_url | append: cacheBust }})

### Assembly

#### Dark

- [PCB Dark PDF]({{ "/documents/AstraControl-pcb-dark.pdf" | relative_url | append: cacheBust }})

#### Light

- [PCB Light PDF]({{ "/documents/AstraControl-pcb-light.pdf" | relative_url | append: cacheBust }})

### Downloads

#### JLCPCB

- [JLCPCB Zip]({{ "export/AstraControl-JLCPCB.zip" | relative_url | append: cacheBust }})
- [JLCPCB BOM CSV]({{ "export/AstraControl_bom_jlc.csv" | relative_url | append: cacheBust }})
- [JLCPCB CPL CSV]({{ "export/AstraControl_cpl_jlc.csv" | relative_url | append: cacheBust }})

#### Eurocircuits

- [Eurocircuits Zip]({{ "export/AstraControl-Eurocircuits.zip" | relative_url | append: cacheBust }})
- [Eurocircuits BOM CSV]({{ "export/AstraControl_bom_Eurocircuits.csv" | relative_url | append: cacheBust }})
- [Eurocircuits CPL CSV]({{ "export/AstraControl_cpl_Eurocircuits.csv" | relative_url | append: cacheBust }})
  
## Report

#### ERC

{% include_relative erc_validation.md %}

#### DRC

{% include_relative drc_validation.md %}

{% include_relative AstraControl-report.md %}
