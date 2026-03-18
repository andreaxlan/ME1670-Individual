# ME 1670 Individual Project

## Course Overview
ME 1670, Introduction to Engineering Graphics and Design, is a course taught at Georgia Tech that introduces students to sketching, line drawing, solid modeling, and drawing specifications. This course utilizes SOLIDWORKS software.

## Project Overview
The individual project is a culminatation of hand-sketching and SOLIDWORKS modeling techniques learned over the first half of the course. The goal for the project is to design a small object that will be printed on a commerical SLS 3D printer. I designed a _Spinning Fidget Duck_ toy constructed from two gears and a base plate. 


# Timeline

## Spinning Fidget Duck V2.0

<img src="https://github.com/andreaxlan/ME1670-Individual/blob/96b2c2d893538f79b3b92090d0bad9d38db5a05e/SOLIDWORKS%20FILES%20V2.0/V2.0%20ISOMETRIC.png" width="400">

### 3.18.2026
Minor adjustments were made to some parts. I made the base plate entirely solid to provide more structure and increased the diameter of the handle on the driving gear since the initial size was very small.

<img src="https://github.com/andreaxlan/ME1670-Individual/blob/96b2c2d893538f79b3b92090d0bad9d38db5a05e/SOLIDWORKS%20FILES%20V2.0/V2.0%20BASE%20PLATE.png" width="500">

The connector head was initially tapered on both ends. This would allow the gears to slide in and out. Since I wanted them to stay in place once the toy was assembled, I removed the bottom taper. (all units in inches)

<img src="https://github.com/andreaxlan/ME1670-Individual/blob/96b2c2d893538f79b3b92090d0bad9d38db5a05e/SOLIDWORKS%20FILES%20V2.0/V2.0%20TOP%20VIEW.png" width="500">

The connector hole diameter is slightly larger than the shaft hole diameter to prevent the gears from sliding out. The most important design consideration for the connectors was making sure the center gap was larger than double the spacing between the edge of the shaft hole and the edge of the widest part of the connector head. This ensures there is enough spacing for the connector plastically deform and clear the shaft hole.

<img src="https://github.com/andreaxlan/ME1670-Individual/blob/96b2c2d893538f79b3b92090d0bad9d38db5a05e/SOLIDWORKS%20FILES%20V2.0/V2.0%20CROSS%20SECTION.png" width="500">

Finally, a 0.01 inch tolerance was included between the shaft hole and connector.

## Spinning Fidget Duck V1.0

<img src="https://github.com/andreaxlan/ME1670-Individual/blob/26e62ac60bccacd1b5e7eb277e744ad0f574eed2/SOLIDWORKS%20FILES%20V1.0/ISOMETRIC%20VIEW.png?raw=true" width="400">

### 3.14.2026
The CAD model draft for the driven gear was completed. I had several issues using the shell feature to hollow out the duck figurine due to complex geometry. These issues were resolved by decreasing the fillet size between the head of the duck and the torso of the duck. I was also able to assemble all three of my parts in the SOLIDWORKS assembly. The move compontent tool can simulate physical dynamics, allowing me to test the gears working together. I ended up increasing the distance between the center of both gears by a fractional amount to provide more 3D printing tolerance.

### 3.10.2026
The CAD model drafts for the driving gear and base plate were completed. I designed the teeth of the driving gear using examples I found online.

### 3.2.2026
For my individual project, I decided to design gears to create moving parts. I drafted my individual project proposal and drew my concept sketches using Krita, an open source painting program. I also researched gear parameters to find the specifications I needed for my project.

$$Diametrical\text{ }Pitch\text{ }(DP) = \frac{Number\text{ }of\text{Teeth}\text{ }(N)}{Pitch\text{ }Diameter\text{ }(P)}$$

The diametrical pitch controls the strength and the number of teeth, where a lower diametrical pitch creates fewer, stronger, teeth. Two gears need the same diametrical pitch in order mesh together. 

$$Gear\text{ }Ratio=\frac{Number\text{ }Driven\text{ }Teeth}{Number\text{ }Driver\text{ }Teeth}$$
$$Gear\text{ }Ratio=\frac{24\text{ }T}{12\text{ }T}=2:1\text{ }Ratio$$

My driven gear would have 24 teeth, while my driving gear would have 12 teeth, giving me a 2:1 gear ratio. The exact dimensions of the gear teeth would be determined in the CAD model.
