

---

# FEM Analysis of the Power Skiving Gear Machining Process

Finite Element Method (FEM) simulation of the **Power Skiving gear machining process** using **ANSYS**.
The project investigates the **mechanical behavior of a cutting tool during gear machining**, focusing on **stress distribution and deformation under different cutting conditions**.

The analysis evaluates how **chip geometry and cutting position influence the mechanical loads on the cutting tool**.

---

# Project Highlights

* Finite Element simulation of the **Power Skiving machining process**
* **3D modeling of cutting tool and chip geometry**
* Static structural analysis using **ANSYS**
* Evaluation of **Von Mises stresses and tool deformation**
* Simulation across **9 different cutting positions**
* Identification of **critical stress locations along the cutting edge**

---

# Background

Gears are essential mechanical components used in **power transmission systems**.
Among modern gear manufacturing technologies, **Power Skiving** has gained significant attention due to its **high productivity and flexibility**.

Power Skiving combines characteristics of:

* **Gear Hobbing**
* **Gear Shaping**

Advantages of Power Skiving include:

* High machining speed
* Excellent surface quality
* Ability to machine **internal and external gears**
* Reduced production time
* High flexibility for different gear geometries

Understanding the **mechanical loads acting on the cutting tool** during this process is critical for improving **tool life, machining efficiency, and gear quality**.

---

# Methodology

The study uses the **Finite Element Method (FEM)** to simulate the interaction between the **cutting tool and the workpiece chip** during machining.

The simulation evaluates:

* Stress distribution on the cutting tool
* Tool deformation
* Effects of chip geometry on tool loading

The analysis was performed using **ANSYS Static Structural simulation**.

---

# Simulation Workflow

1. **Geometry creation** of the cutting tool and chip using ANSYS SpaceClaim
2. Definition of **material properties**
3. Generation of **finite element mesh**
4. Application of **boundary conditions and loads**
5. Execution of **static structural FEM simulation**
6. Post-processing of **stress and deformation results**

---

# Simulation Setup

| Parameter             | Value                  |
| --------------------- | ---------------------- |
| Simulation Software   | ANSYS 2025 R2          |
| Geometry Modeling     | ANSYS SpaceClaim       |
| Analysis Type         | Static Structural      |
| Tool Material         | High Speed Steel (HSS) |
| Workpiece Material    | 16MnCr5 Steel          |
| Applied Pressure      | 1500 N/mm²             |
| Number of Simulations | 9 cutting positions    |

---

# Geometry Modeling

The cutting tool geometry was created in **ANSYS SpaceClaim**.

Steps:

1. Creation of a **2D tooth profile**
2. Conversion to **3D geometry**
3. Application of a **3° cutting angle**
4. Generation of chip geometries representing **different cutting stages**

Nine different chip geometries were modeled to represent **different cutting positions during machining**.

---

# Meshing

The geometry was discretized into **finite elements** to enable numerical analysis.

Key characteristics:

* Higher mesh density near the **cutting edge**
* Variable mesh refinement depending on chip geometry
* Maximum node limitation: **128,000 nodes**

Fine mesh regions were applied where **stress gradients were highest**.

---

# Boundary Conditions

### Tool Fixation

The base of the cutting tool was **fully constrained**, preventing:

* Translation
* Rotation

This represents the **realistic mounting of the tool in a machine tool holder**.

---

### Applied Load

A pressure load was applied to the chip:

**Pressure:**
1500 N/mm²

Location:

* Applied near the **cutting edge**
* Perpendicular to the cutting surface

---

# Cutting Positions Analyzed

The simulation was performed for **nine cutting positions**:

30°
35°
40°
45°
50°
55°
60°
65°
70°

Each position corresponds to a **different chip geometry and cutting depth**.

---

# Results

The FEM simulations produced:

* **Von Mises stress distributions**
* **Tool deformation values**
* Stress distribution along the **cutting edge**

---

## Maximum Stress

The highest stress occurred at:

**Cutting Position: 70**

Maximum Von Mises Stress:

6725.1 N/mm²

---

## Maximum Deformation

Maximum tool deformation observed:

0.1975 mm

The deformation increases **almost linearly as the cutting depth increases**.

---

# Key Observations

* The **highest stresses occur near the cutting edge**
* Chip geometry significantly affects the stress distribution
* Tool deformation increases progressively during machining
* Deeper cutting positions generate **higher mechanical loads**

These findings provide insights for **optimizing tool design and machining parameters** in Power Skiving processes.

---



---

# Technologies Used

* ANSYS 2025 R2
* ANSYS SpaceClaim
* Finite Element Method (FEM)

---

# References

* Shigley, J.E. – *Mechanical Engineering Design*
* Norton, R.L. – *Machine Component Design*
* AGMA Gear Design Standards
* Antoniadis, Vidakis, Bilalis – Gear hobbing FEM analysis
* Tapoglou – Power Skiving chip geometry modeling

---

