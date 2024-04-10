---
title: "Print-in-place plier"
excerpt: "This is a print-in-place plier that can be used to hold components"
header:
  image: /assets/img/plier/11 FINAL DESIGN.jpeg
  teaser: /assets/img/plier/11 FINAL DESIGN.jpeg

---
## Introduction

Print-in-place models are designs for tools or multi-component structures that are printed using a 3D printer and can be immediately utilized without the need for additional cleaning or assembly. These designs must be meticulously crafted, taking into account various movements and stresses the model will encounter to ensure it functions as intended. However, despite careful design considerations, such models may still face challenges from external factors beyond the initial modeling and design phase. Typically, a combination of both flexible and rigid parts is incorporated into the modeling of these designs.

## Print-in-Place Application
Print-in-place 3D models have significantly simplified access to essential tools on demand and may even reduce costs. They have also found application in critical areas, such as prosthetics.
This technology has revolutionized the creation of prosthetics, enhancing efficiency in their production process and providing greater flexibility in customization. If any issues arise with the modeled design, adjustments can be easily made by editing the CAD files, allowing for swift recreation of the prosthetic.

![3D print in place hand prosthetic](/assets/img/plier/1 HAND PROSTHETIC.jpeg)

3D print in place hand prosthetic

Another significant application is the production of implantable parts. Components such as heart valves, tooth implants, and knee replacements can all be designed, 3D printed, and immediately utilized by doctors without requiring modification. This expedites patient treatment significantly, as they no longer need to endure extended waiting periods for the fabrication and manufacturing of their implants.

![3D print in place tooth implant](/assets/img/plier/2 tooth implant.jpeg)

3D print in place tooth implant

## 3D Printing Materials

There are various materials suitable for use in 3D printers for print-in-place designs. However, three of the most popular options are APS, Flexible, and PLA.
APS, an abbreviation for Acrylonitrile Propylene Styrene, is a cost-effective filament known for its ability to produce durable, rugged, and high-temperature-resistant parts.

![APS](/assets/img/plier/3 APS.jpeg)
APS printed design



PLA (Polylactic Acid) is primarily utilized when high accuracy is paramount for prints, in addition to its affordability and ease of use.

![PLA](/assets/img/plier/4 pla.jpeg)


PLA printed design


Flexible filament, often referred to as TPU (Thermoplastic Polyurethane) or TBE (Thermoplastic Elastomer), is ideal for printing elastic parts due to its flexibility and resilience.


![TPU](/assets/img/plier/5 TBU.jpeg)

TPU printed design

Indeed, there are numerous other filaments available, such as metal-filled, wood-filled, nylon, and carbon fiber-filled filaments.

## Plier Modeling and Spring effect

![6](/assets/img/plier/6 first outline.jpeg)


The jaw and handles of the pliers were initially designed based on the necessary dimensions for the functions the pliers will perform. They were crafted to be rigid and ergonomic for comfortable handling. The handles were shaped to provide users with a secure grip while applying pressure.

![6.1](/assets/img/plier/6.1 extrusion.jpeg)


An outer shell  was then extruded 

![7](/assets/img/plier/7 piler outline mesh.jpeg)

A mesh sketch was then reinforced 
 
![8](/assets/img/plier/8 web like mesh component.jpeg)


The WEB feature was subsequently employed to generate the support mesh based on the previously created sketch.


![9](/assets/img/plier/9 old center part.jpeg)
 


The center part is created to link the handles with the jaw, using TBU material to impart a spring-like effect to the structure.

![10](/assets/img/plier/10 adjusted centre part.jpeg)

After a failed print attempt, the mesh was adjusted to incorporate stiffer connectors. This modification was necessary as the middle part was prone to detachment due to weak joints 

![11](/assets/img/plier/11 FINAL DESIGN.jpeg)


The final design of the pliers, which are now fully functional, features strengthened connectors in the mesh, resolving previous issues of detachment during printing. 

![12](/assets/img/plier/12 jaw grip.jpeg)

A gripping structure has been incorporated into the nose of the pliers to enhance grip on components.

![13](/assets/img/plier/13 DIMENSION.jpeg)



## Specifications for the pliers:
*	Total length from the end of the handle to the tip of the jaw: 152.64 mm
*	Total width between the 2 handles: 44.64 mm
*	Jaw capacity: 6.45 mm, designed to accommodate most types of components
*	Jaw length: 42.8 mm

 


# CAD model:
<iframe src="https://vanderbilt643.autodesk360.com/shares/public/SH512d4QTec90decfa6ee21638c1c79354f1?mode=embed" width="800" height="600" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true"  frameborder="0"></iframe>

{% include gallery caption="This is a sample gallery to go along with this case study." %}
