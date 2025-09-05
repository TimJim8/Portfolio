---
    title: 'My First Blog'
    date: 2025-09-04T13:03:04-04:00
    tags: ['robotics','blog','bobrov']
    image: 'OrgoRoboShelf.webp'
---

# My first blog
The shop had a very productive start to the year. I finally orginized the Robotics Team shelf with Ibrahim. In adition to this I also cleared out my box and made a new label to replace the old one. After a few days of orginizing I started working with Jonas to set up the Tormach mills. So far we have refilled the oil, restarted the system, and cleaned the vices of rust.     
<br>
<div style="align-contents: center; text-align: center;">
    <br>
    <img 
        onclick="window.location.href=this.src;" 
        style="display: block; margin-left: auto; margin-right: auto; width: 45%;" 
        src="/posts/first-post/IMG_9762.webp"
        alt="Unable to load image. Please refresh.">
    </img>
    <sub>Robotics Team Shelf.</sub>
    <br>
</div>
<br>
<br>
<div style="align-contents: center; text-align: center;">
    <br>
    <img 
        onclick="window.location.href=this.src;" 
        style="display: block; margin-left: auto; margin-right: auto; width: 45%;" 
        src="/posts/first-post/OrgoBox.webp"
        alt="Unable to load image. Please refresh.">
    </img>
    <sub>Cleaned Out Box.</sub>
    <br>
</div>
<br>
<div style="align-contents: center; text-align: center;">
    <br>
    <img 
        onclick="window.location.href=this.src;" 
        style="display: block; margin-left: auto; margin-right: auto; width: 45%;" 
        src="/posts/first-post/IMG_9766.webp"
        alt="Unable to load image. Please refresh.">
    </img>
    <sub>Tormach Oil Well.</sub>
    <br>
</div>
<br>
<br>
<div style="align-contents: center; text-align: center;">
    <br>
    <img 
        onclick="window.location.href=this.src;" 
        style="display: block; margin-left: auto; margin-right: auto; width: 45%;" 
        src="/posts/first-post/IMG_9767.webp"
        alt="Unable to load image. Please refresh.">
    </img>
    <sub>Mill Vices.</sub>
    <br>
</div>
<br>
I spent a large portion of the week performing reaserch for BOB ROV. I found these to be important aspects of the design:

Seamless Tube Manufacturing (Part Sourcing)
It is highly beneficial for the tube to be seamless (not welded together). This is because buckling often occurs at imperfections, dents, and seams. It is very difficult to account for these imperfections with an imperfect stock piece. To make up for this shortcoming the tube’s thickness would have to greatly exceed what it would otherwise necessitate with a seamless tube.

Weldability 
The ability to weld the tube without compromising its integrity drastically reduces possible points of failure in the sealing system. The only feasible alternative to a welded flange design is a split collar. Bolting the two part flange around the tube, using its compression to join primary components. Successfully connecting the flange this way without damaging the tube would require careful calculations and extra design considerations. A single overtightening could destroy the tube, necessitating excess time and cost for replacement. Therefore it is absolutely essential that the chosen material be weldable. 


<br>
<div style="align-contents: center; text-align: center;">
    <br>
    <img 
        onclick="window.location.href=this.src;" 
        style="display: block; margin-left: auto; margin-right: auto; width: 45%;" 
        src="/posts/first-post/TubeMatSel.webp"
        alt="Unable to load image. Please refresh.">
    </img>
    <sub>Material selection table.</sub>
    <br>
</div>
<br>



<br>
I also designed the external frame for BOB ROV. I decided to use 4 tubes running parallel to the central electronics tube. These tubes serve as handles, modular mounting points, and cable channels. Each tube is conected to the each flange with a custom split collar design. To increase friction for the split collar, and to improve grip the tubes will be knurled.     
<br>
<div style="align-contents: center; text-align: center;">
    <br>
    <img 
        onclick="window.location.href=this.src;" 
        style="display: block; margin-left: auto; margin-right: auto; width: 45%;" 
        src="/posts/first-post/\BOBV18.webp"
        alt="Unable to load image. Please refresh.">
    </img>
    <sub>Current Cad Model.</sub>
    <br>
</div>
<br>

I also spent significant time researching the geometry required to securley weld the flanges to the tube. One of the main requirements for this geometry was to prevent the washers and nuts for the seal interfering with the weld bead. To achieve the required clearence I had to implement a larger bolt circle. In order to maintain the seal on the gasket I had to change the thickness of the end cap and the flange. This was because a bolt clamping a joint applies pressure in a shape that can be approximated as a truncated cone. The angle that this cone expands is called the pressure angle. They expand as they move through material. Both the bolt and nut have force cones originating at their effective radius, typically the radius of the fasteners mating surface. These cones should meet at the gasket to assure even spread of force across the gasket. Where the gasket intersects the force cones, they should connect on the gasket ensuring no low pressure areas on the gasket where leakage might occur. I increased the radius at the mating surface by increasing the thickness of material the truncated cone travels through. 
 

