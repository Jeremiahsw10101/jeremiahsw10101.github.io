---
title: "Generative Design"
excerpt: "Generative Design SLS Truck Hanger + Motor Mount"
header:
  image: /assets/img/generative design/1 intial.jpg
  teaser: /assets/img/generative design/1 intial.jpg

---

## Introduction

Generative design is an innovative approach to creating designs using computational algorithms and artificial intelligence. Instead of manually creating a single design, generative design systems explore a vast range of potential solutions based on input parameters and goals. These algorithms generate multiple design alternatives, often producing highly complex and optimized designs that might not be immediately obvious to a human designer.

##### Input parameters includes:

###### Preserves:
These are the placeholders (objects) in the design that must remain in place at all times. All preserves should be connected via a mesh to one another without passing through any obstacles.
###### Obstacles:
These are areas that the designer wants to keep empty and untouched by the mesh that the algorithm will create.

[6](assets/img/generative design/6 obstacle and reserve.jpg)

###### Mechanical constraints: 
These are parts of the preserves that the algorithm should build to create the model.
###### Static loads:
These are the constant loads and forces that the model must withstand under all conditions.

[7](assets/img/generative design/7 static load and constraints.jpg)

These are the static loads and constraints of the skateboard trucks 

The algorithm uses these input parameters to perform evaluation and optimization of the model it is designing. The engineer then should then select the best solution that the algorithm provides after a sequence of iterations.


## Purpose of generative modeling:

•	Generative design is highly useful for creating customized and optimized designs that are complex and advanced, often challenging for engineers to achieve.

•	It encourages engineers to practice innovation and out-of-the-box thinking in modeling and design.

•	Additionally, it provides designers with accurate matches for desired weight and strength requirements while optimizing material usage efficiently.

•	This approach saves time and money spent on designing smart, lightweight, yet durable models.

## Drawbacks of Generative Design:

1.	**Algorithm Dependency** : The algorithms depend highly on the parameters the designer provides. A suboptimal algorithms or any mistakes in the defined constraints can produce an unreliable design  
2.	**Expertise and Training** : Designers have to be well-trained to interpret the results and make the best of use of the generative design.
3.	**Computational Resources** : Generative design may be expensive as it needs computational resources, including high-performance computing clusters or cloud-based services.
4.	**Integration Challenges** : If only a part of the model is designed using generative modeling, the engineer may face challenges in assembling the whole model together. Human Oversight and Validation: the designs created by the algorithm is not fully reliable and the designer still needs to validate them.


## Generative design applications:

1.	**Aerospace and automotive** : Such as chassis, suspension systems, and engine parts
2.	**Product Design and Manufacturing** : Such as consumer goods, electronics, and industrial equipment.
3.	**Architecture and Construction** : Helps in creating complex building structures, facades, and interior layouts.
4.	**Healthcare and Biotechnology** : Such as customized medical devices, prosthetics, and implants.
5.	**Art and Creative Industries** : Generating unique visualizations, sculptures, and digital artworks.

##  Powder bed fusion (PBF) and generative design 

The combination of powder bed fusion (PBF) and generative design allows for the merging of advanced manufacturing and computational design, enabling the creation of complex, customized, and optimized components with exceptional efficiency and functionality.

1.	**Design Freedom** : Combining Generative design with PBF allows for the creation of complex and organic shapes alongside with intricate geometries layer by layer.
2.	**Optimized Structures** : Generative design algorithms optimize designs for specific performance criteria like strength-to-weight ratios and material usage efficiency. When combined with PBF's precise material distribution control, this results in minimal material waste and lighter, more efficient structures.
3.	**Customization and Personalization** : PBF is adept at producing customized components without the need for specialized tooling or molds. When paired with generative design, which tailor’s designs to individual preferences, this combination is particularly powerful in industries like aerospace, automotive, and healthcare, where personalized components are increasingly needed.
4.	**Iterative Design Process** : Generative design's iterative nature complements PBF's manufacturing process. Designers iterate through multiple designs, use PBF to create prototypes, test them, and refine based on results. This iterative loop accelerates optimization, delivering improved final designs in less time.
5.	**Material Flexibility** : PBF supports a wide range of materials, including metals, polymers, and ceramics while generative design can optimize designs for specific material properties.


The unique pairing of powder bed fusion (PBF) and generative design presents significant advantages in the aerospace industry:

1. **Lightweight Structures** : Generative design can optimize aerospace components for weight reduction while maintaining structural integrity and performance. PBF allows for the fabrication of complex and lightweight structures, ideal for aerospace applications where weight savings directly impact fuel efficiency and payload capacity.
2. **Complex Geometry** : Aerospace components often require intricate and complex geometries to achieve optimal aerodynamic performance. PBF's ability to produce such geometries layer by layer complements generative design's capability to generate these complex shapes, leading to more efficient and aerodynamically optimized parts.
3. **Customization and Optimization** : Generative design enables the creation of customized components tailored to specific aerospace applications and requirements. standards.

Here is a stress analysis of the trucks’ design using aluminum vs Nylon








Base model with generative Nylon12 design weight about 108 Grams


[2](assets/img/generative design/2 base model.jpg)


stress analysis:


[5](assets/img/generative design/5 nylon design.jpg)



Base Model with generative AlSi10Mg aluminium design ( weight about 222 Grams )

[3](assets/img/generative design/3 base model 2.jpg)


stress analysis:

[4](assets/img/generative design/4 alum design.jpg)



Base Model Fully assembled 

[1](assets/img/generative design/1 intial.jpg)






