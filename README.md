## Design and Fabrication

---

<img src="Images/side.PNG" alt="Parts" width="500"/>

**Figure 1**: Components of a single module fish

<details open>
    <summary><b>Table 1</b>: Component and material used.</summary>
    <ol>
        <li>Component link takes you to <a href="https://gitlab.com/mikhaildasilva/fish/-/tree/main/CAD">CAD</a></li>
        <li>Material link take you to <a href="https://gitlab.com/mikhaildasilva/fish/-/tree/main/Additive%20Manufacturing/Material-Profile">Material-Profile</a></li>
    </ol>
</details>

|   [Rigid head](https://gitlab.com/mikhaildasilva/fish/-/tree/main/CAD/Head)  |   [Servo mount](https://gitlab.com/mikhaildasilva/fish/-/tree/main/CAD/Servo-Mount) | [Flexible body](https://gitlab.com/mikhaildasilva/fish/-/tree/main/CAD/Body) | [Caudal fin](https://gitlab.com/mikhaildasilva/fish/-/tree/main/CAD/Caudal-Fin) |
| :---:         | :---:         | :---:         |:---:      |
|[CPE](https://gitlab.com/mikhaildasilva/fish/-/tree/main/Additive%20Manufacturing/Material-Profile/CPE)        | [PETG](https://gitlab.com/mikhaildasilva/fish/-/tree/main/Additive%20Manufacturing/Material-Profile/PETG)      |  [TPU-95A](https://gitlab.com/mikhaildasilva/fish/-/tree/main/Additive%20Manufacturing/Material-Profile/TPU)      |[TPU-95A](https://gitlab.com/mikhaildasilva/fish/-/tree/main/Additive%20Manufacturing/Material-Profile/TPU)    |

---

:exclamation: A modular approach gives us the latitude to perform eclectic locomotion gaits by increasing the number of modules. For instance, 1 module can only perform an oscillatory pattern. Whereas a multi-module (3 and above) displays an undulatory motion. 

## Tendon-driven actuation 

---

<details open>
<summary>Actuation mechanism</summary>
    <img src="Images/cable.PNG" alt="Actuation" width="500"/>
</details>

**Figure 2**: Cable spool mechanism.

1. The tendon is wound around the servo while the servo motor is in its neutral position. 

2. When the servo motor is rotated in the clockwise direction the exercised tension on right hand side tendon bends the peduncle causing the caudal fin to move to position 1. Simultaneously a force is exerted on the other side of the line. 

3. Similarly when the servo motor moves in an anticlockwise direction the caudal fin moves to position  2.

![Working](Images/working.mp4)