---
layout: home
---

{% assign cacheBust = site.time | date:'?v=%s' %}

#### Table of contents
[Render Top Angled](#Render Top Angled)
[Render Top](#Render Top)
[Render Bottom](#Render Bottom)
[Interactive BOM](#Interactive BOM)
[PCB properties](#pcb)

##### Render Top Angled
![Image]({{ "/images/AstraControl-3D_blender_top_angled.png" | relative_url | append: cacheBust }})

##### Render Top
![Image]({{ "/images/AstraControl-3D_blender_top.png" | relative_url | append: cacheBust }})

##### Render Bottom
![Image]({{ "/images/AstraControl-3D_blender_bottom.png" | relative_url | append: cacheBust }})

##### Interactive BOM
Easily check component locations by hovering.
[IBOM]({{ "/export/AstraControl-ibom.html" | relative_url | append: cacheBust }})

##### BOM
All components with Values, References, Sheetpath and Links to the datasheet.
[BOM]({{ "/export/AstraControl-bom.html" | relative_url | append: cacheBust }})

#### Schematic
##### Dark
[Schematic Dark]({{ "/documents/AstraControl-schematic-dark.pdf" | relative_url | append: cacheBust }})

##### Monochromatic
[Schematic Mono]({{ "/documents/AstraControl-schematic-mono.pdf" | relative_url | append: cacheBust }})

##### Light
[Schematic Light]({{ "/documents/AstraControl-schematic-default.pdf" | relative_url | append: cacheBust }})


#### PCB
[PCB Dark]({{ "/documents/AstraControl-pcb-dark.pdf" | relative_url | append: cacheBust }})

[PCB Light]({{ "/documents/AstraControl-pcb-light.pdf" | relative_url | append: cacheBust }})

#### ERC

{% include_relative erc_validation.md %}

#### DRC

{% include_relative drc_validation.md %}

#### Report

{% include_relative AstraControl-report.md %}
