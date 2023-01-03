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

### 3D Printing using TPU filament

---

#### Hardware requirements 

1. Use a **Direct drive extruder** (DDE): 
    - TPU filaments with a shore hardness in the range of **75A-85A** are physically like rubber bands in layman's terms. 
    - By using a DDE, one is guiding the filament straight down into the nozzle.
    - _Caveat_: TPU **95A** is flexible yet rigid enough to be used by an FFF printer (Ultimaker S5) with a **Bowden tube extruder**. 
    - [Direct drive :versus: Bowden tube](https://www.3djake.com/info/guide/direct-drive-extruder-vs-bowden-extruder) 

### Vendor list TPU (as of 2 Jan. 2022)

--- 

:heavy_check_mark: = Easy to print. Can use the material profile from this repo as a boilerplate. 

:warning: = Difficult to print

|Difficulty          | Filament Name  | Shore Hardness | 
|:---:               | :---:          | :---:          |     
| :heavy_check_mark: | [NinjaFlex](https://ninjatek.com/shop/ninjaflex/)      | 85A            |     
| :heavy_check_mark: | [Ultimaker-TPU](https://www.matterhackers.com/store/l/ultimaker-tpu-filament/sk/M5ZFDTT3)      | 95A            |    
| :warning:| [Chinchilla](https://ninjatek.com/shop/chinchilla/)      | 75A            |     