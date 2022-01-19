---
description: This page is under construction.
---

# Open Source Recycling

## Introduction

**The goal of this project is to democratize the knowledge and empower individuals to remove plastics from their community waste stream and transform them through the below described processes into long lived, durable goods that can again be recycled at the end of their usefulness.**

## Statement of Problem

Typical plastic waste is often bulky, of unknown composition, and potentially contaminated with food waste or dirt. It is not in the scope of this project to solve the plastic sorting and cleaning problem, but to focus on breaking down bulky plastic into uniform pieces **of a desired size** that can then be used as new feed stock. This is done traditionally with an industrial shredder. Since such machines are not suited for home use, our scope of work is to design an Open Source Hardware plastic shredder. **The shredder needs to be relatively quiet and be able to handle the recyclable plastic seen in modern society.**

## Recyclable Plastics

Recycle codes, listed in order

1. &#x20;PET polyethylene terephthalate&#x20;
2. &#x20;HDPE polyethylene, high density
3. PVC poly(vinyl chloride)
4. &#x20;LDPE polyethylene, low density
5. PP polypropylene

Plastics used in 3D printing are not often seen in consumer goods, as most consumer goods are injection molded. Injection molding plastics do not necessarily make for good 3D printing filament and vice versa. To name a few: PLA, ABS, Nylon, PETG, and PP.

In addition, plastics can have fillers, contamination, or be damaged from UV, thermal, or mechanical stress that change their initial properties. In these cases, mixing in additive plastics can help mitigate the damage and restore some of the materials initial properties. Additive plastics can be freshly manufactured plastic or plastics with complementary properties.

## Existing Options

On the market, there are several commercial shredder options designed for dedicated spaces and high volume plastic shredding. Unfortunately, these machines and techniques do not meet the above goal of being usable by a single individual. A cooperative community recycling center would be ideal for one of these high volume machines.

The best documented and supported DIY plastic shredder would be the Precious Plastics Shredder. However, the current bill of materials (BOM) lists the price as $2,234.17, which is an amazing 5x lower price difference from commercial shredders and is competitive with equivalent commercial shredders from Asian markets. This doesn’t include labor and overhead plus reinvestment profits.

## Challenges

**To realize a further reduction of price and complexity, a shredder designed from the ground up to be sustainable and accessible needs to be developed. By designing mechanical components capable of being made on a 3D printer, we potentially can use the very plastic material shredded in the creation of new shredders, as well as expand the list of useful machines buildable with a 3D printer. When considering a shredder built of plastic designed to shred plastic, we will both need to create a community, collaborate with an existing community, or reinvigorate an inactive community as it is unlikely that our initial efforts will be sufficient to solve low cost waste processing. Community activity can’t only be limited to technical work. Cultural and social norms around recycling need to be addressed and both trust and accountability need to be earned. We can leverage an Open Source Hardware project and a call to action, along with organizational resources such as documentation management, official builds, development resources, and coordination of efforts.**

## Design Overview

Currently the design of the shredder is envisioned to be a single shaft shredder, which is a simple but robust design that uses a pusher lever to feed material against rotating knives along a single stationary blade. A screen acts as a filter to only let material of a certain shape through. These machines use low speed, high torque gearboxes to process a high variety of materials.

![https://en.wikipedia.org/wiki/File:How\_industrial\_shredder\_works.jpg](https://upload.wikimedia.org/wikipedia/commons/b/b1/How\_industrial\_shredder\_works.jpg)

To accomplish this with a 3D printed shredder, it is envisioned that the central shaft will be 3D printed and like with commercial units, steel or carbide inserts will make up the cutting knife edges, and plastic will provide backing and support. To provide high torque, a cycloidal gearbox will be coupled to the shaft on both sides to provide support and the required force.

Future work includes using the shredded material in a variety of applications, some of which are demonstrated by Precious Plastics, such as building materials and consumer goods. A further goal would be to use the shredded plastic for 3D printing as either feed stock for a filament extruder or directly with a pellet extruder 3D printing head.

## Links

Cycloidal gears https://www.tec-scien"ce.com/mechanical-power-transmission/planetary-gear/construction-of-the-cycloidal-disc/

3D printed high torque gearbox https://reprapltd.com/cycloidal-gearboxes/

Open source pellet extruder https://3dprint.com/270286/open-source-grinding-machine-cuts-cost-of-pellet-3d-printing/ https://hackaday.com/2020/07/09/open-source-grinder-makes-compression-screws-for-plastic-extruders-easy/

Open source plastic grinder https://www.instructables.com/50-Plastic-Shredder-Grinder-Recycler/

https://youtu.be/IN2g572FZOo

Open source filament maker https://youtu.be/MRQKmRvfZMI

Ceramic grinding elements with progressive https://www.aliexpress.com/item/1005001287533366.html Open source plastic type detector https://hackaday.com/2021/12/13/an-open-source-detector-for-identifying-plastics/

Difficulties in recycling https://youtu.be/Dwlr2yKlq6w

Clay stabilized oil, mixed with plastic to make a new kind of material https://www.sciencedirect.com/science/article/abs/pii/S0169131721002702 https://www.stoneflower3d.com/projects/clay-extruder-prototype/

Overview of current recycling of plastics https://onlinelibrary.wiley.com/doi/full/10.1002/pol.20190261

Pellet extrusion 3D printer heads https://bitfab.io/blog/pellet-extruders-3d-printing/ https://escholarship.org/content/qt5142579v/qt5142579v\_noSplash\_b328ae52af8f1c58067cf23b2abdda11.pdf

High Volume selective nozzle for continuous single tool head multi extrusion profile heads. https://jubilee3d.com/index.php?title=Baby\_Bullet\_Extruder https://hackaday.com/2019/11/14/jubilee-a-toolchanging-homage-to-3d-printer-hackers-everywhere/

Open source 3D printed high torque compact gear boxes https://youtu.be/Emvo3bLT-Z4

Recyclable plastics https://en.wikipedia.org/wiki/Recycling\_codes

Single Shaft Shredder http://www.solidswiki.com/index.php?title=Single\_Shaft\_Shredders
