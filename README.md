# The Digital Rat Software from the Hartmann Group
The Digital Rat is software from the Hartmann group that aims to enable morphologically and mechanically accurate modelling of the rat head and vibrissal (whisker) array. Our long-term goal is to develop a simulation environment that can be used to model the spatiotemporal patterns of mechanical input to vibrissae during the rat's tactile exploratory behaviors. Development of The Digital Rat was supported by the National Science Foundation under Grant Numbers 0446391, 0818414, and 0846088. Any opinions, findings, and conclusions or recommendations expressed in this material are those of the authors and do not necessarily reflect the views of the National Science Foundation.

## RatMap
A morphologically accurate 3D model of the rat head and vibrissal array. The mystacial pad is modeled as an ellipsoid, and all vibrissa parameters are provided as functions of the (row, column) position of the vibrissa in the array.

### Manuscript
Towal RB, Quist BW, Gopal V, Solomon JH and Hartmann MJZ (2011) [The morphology of the rat vibrissal array: a model for quantifying spatiotemporal patterns of whisker-object contact](towal_plos_2011.pdf). PLoS Computational Biology 7:e1001120. 

### Code
[MATLAB code v1.2](RatMapToolbox_v1_1.zip). This code now includes PuppetMaster.m

## Elastica2D/Elastica3D
A 2D/3D elastic beam model that can be used to model quasistatic bending of the vibrissa to compute forces and bending moments at the base.

### Manuscript
**Elastica3D** was released with this publication: Huet LA, Emnett HM, Hartmann MJZ (2022) [Demonstration of three-dimensional contact point determination and contour reconstruction during active whisking behavior of an awake rat.](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1007763) PLoS Comput Biol 18(9): e1007763.

The first version of **Elastica3D** was written by Lucie Huet for this publication: Huet LA, Schroeder CL, and Hartmann MJZ (2015) [Tactile signals transmitted by the vibrissa during active whisking behavior.](https://journals.physiology.org/doi/full/10.1152/jn.00011.2015) Journal of Neurophysiology 113:3511-3518.

**Elastica3D** was also used for this publication: Huet LA, Rudnicki JW, Hartmann MJZ (2017) [Tactile sensing with whiskers of various shapes: Determining the three-dimensional location of object contact based on mechanical signals at the whisker base.](https://www.liebertpub.com/doi/abs/10.1089/soro.2016.0028) Soft Robotics 4(2):88-102.

The first version of **Elastica2D** was written by Joe Solomon for this publication: Solomon JH and Hartmann MJ (2006) [Robotic whiskers used to sense features](solomon_nature_2006.pdf). Nature 443:525. 

Brian Quist made several improvements to **Elastica2D** in this publication: Quist BW and Hartmann MJZ (2012) [Mechanical signals at the base of a rat vibrissa: the effect of intrinsic vibrissa curvature and implications for tactile exploration](quist_jneurophys_2012.pdf). Journal of Neurophysiology 107:2298-2312. 

### Code
[E3D - MATLAB code v1.1](elastica3D_v1.m) Initial release of Elastica3D. Please rename the file to "elastica3D.m" for use.

[E2D - MATLAB code v1.2](elastica2D.zip) This code now includes a guide to elastica2D.m


## RatHead Trimesh
Trimesh of the rat's head that complements the model. This trimesh of the head can be added to simulations to develop intuition for the coupling of head and vibrissal movements.

### Manuscript
No associated manuscript. Authors are Quist BW, Faruqui RA, and Hartmann MJZ.

### Code
[MATLAB code](RatMap_Head.zip)

## Previous Releases
[RatMap v1.1 MATLAB code](RatMap_Toolbox.zip)

[Elastica2D v1.1 MATLAB code](elastica2D_v1_1.m)
