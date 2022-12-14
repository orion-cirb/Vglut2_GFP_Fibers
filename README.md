# Vglut2_GFP_Fibers 

**Developed for:** Maëla

**Team:** Selimi

**Date:** October 2022

**Software:** Fiji

### Images description

3D images taken with a x60 objective

2 channels:
  1. *CSU_488:* GFP fibers (not mandatory)
  2. *CSU_488:* Vglut2 dots

With each image should be provided a *.roi* or *.zip* file containing one or multiple ROI(s).

### Plugin description

* If required, normalize images with quantile-based normalization

* Detect Vglut2 dots with DoG + Triangle threshold

* If GFP channel provided, detect GFP fibers with DoG + Triangle threshold and colocalize them with Vglut2 dots


### Dependencies

* **3DImageSuite** Fiji plugin

* **CLIJ** Fiji plugin
 

### Version history

Version 1 released on October 17, 2022.
