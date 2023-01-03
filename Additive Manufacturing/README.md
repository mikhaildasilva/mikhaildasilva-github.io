## Additive Manufacturing 

### What is Shore Hardness?

---

[Shore hardness](https://www.smooth-on.com/page/durometer-shore-hardness-scale/) scales provides a point of reference when measuring the ***hardness*** of materials. 

![Shore Hardness chart](Images/durometer_chart.PNG)<div align="center">Figure 1: *Shore Hardness chart that delineates hardness of ubiquitous items*</div>

### Why use Thermoplastic Polyurethane (TPU) instead of Silicone?

---

"Typical" soft robots utilise [Silicone](https://www.smooth-on.com/products/ecoflex-00-30/) of eclectic Shore Hardness' to impart compliance. One of the critical requirements in this project was the speed of prototyping. This is where Additive Manufacturing (3D Printing) using TPU excels. TPU offers elasticity and flexibility whilst maintaining robustness.  

#### A few challenges that arise when using Silicone:

- Silicone takes a considerable amount of time to cure ([4](https://www.smooth-on.com/products/ecoflex-00-30/) hours - [16](https://www.smooth-on.com/products/dragon-skin-30/) hours). 
- Necessity of additional expensive equipment
    - Vacuum chamber and pump to remove air bubbles.
    - Inverse moulds of the end product are required to pour Silicone in them.
    - Weighing scales, gloves, eye protection gear, an apron and non-lather soap are necessary. 
- Accurate mixing ratio of Part A and Part B followed by slow stirring of the liquid rubber.
- A release agent spray for "easy" removal of the part from the mould.

### 3D Printing using TPU 

---

#### The following points are recommendations ascertained through _painful_ experiences 


:heavy_exclamation_mark: = important

:bangbang: = extremely important

:bangbang: TPU filaments need to be printed using [dual geared extruders](https://www.kywoo3d.com/blogs/3d-printer-news/should-i-upgrade-to-dual-geared-extruder) since the filament is flexible.

:heavy_exclamation_mark: TPU is hygroscopic. If not dried before printing creates 


| Pain Point | Possible Solution |
|:---: |:---:|
|Material not extruding evenly| Make sure dual geared extruder is being used. <br> TPU has to be dried|


### Vendor list TPU (as of 2 Jan. 2022)

--- 

:heavy_check_mark: = Easy to print. Can use the material profile from this repo as a boilerplate. 

:warning: = Difficult to print

|Difficulty          | Filament Name  | Shore Hardness | 
|:---:               | :---:          | :---:          |     
| :heavy_check_mark: | [NinjaFlex](https://ninjatek.com/shop/ninjaflex/)      | 85A            |     
| :heavy_check_mark: | [Ultimaker-TPU](https://www.matterhackers.com/store/l/ultimaker-tpu-filament/sk/M5ZFDTT3)      | 95A            |    
| :warning:| [Chinchilla](https://ninjatek.com/shop/chinchilla/)      | 75A            |     