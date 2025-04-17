# 🏗️ Sheet Metal Design - SOLIDWORKS Chapter 18

This repository contains files and learning notes related to **Chapter 18: Sheet Metal Design** from the SOLIDWORKS course by Digital CADD Solutions.

---

## 🧠 Concept: What is Sheet Metal Design in SOLIDWORKS?

**Sheet Metal Design** in SOLIDWORKS is a specialized workflow that allows you to create parts that are manufactured by bending flat metal sheets. It focuses on features and tools that simulate real-world fabrication methods, such as bending, cutting, punching, and forming.

In traditional modeling, you'd model the entire solid. But in sheet metal, the goal is to design **bends, flanges, and cuts** in a way that the part can be flattened into a **2D pattern** (called the **flat pattern**) and later manufactured using tools like laser cutters or press brakes.

### 🛠️ Key Principles

- **Base Flange**: The starting point of any sheet metal part. It defines the initial flat sheet from which all other features grow.
- **Flanges and Bends**: Let you fold the sheet in different directions while accounting for real-world material behavior (like bend allowance and relief).
- **Flat Pattern**: A flattened view of the part used for manufacturing, allowing for proper tooling design.

---

## 🎯 Learning Outcomes

After completing this chapter, I was able to:

- Create base, edge, and miter flanges
- Understand the FeatureManager Design Tree of a sheet metal component
- Create tabs, closed corners, and hems
- Create sketched, lofted, and jogged bends
- Break corners of sheet metal components
- Create cuts on the flat faces of sheet metal components
- Create the flat pattern of sheet metal components
- Create swept flanges along a sheet metal component or sketch
- Create sheet metal components from a flat sheet and a flat part
- Create sheet metal components by designing it as a part
- Design sheet metal parts from a shelled solid model
- Create cuts in sheet metal components across the bends
- Create cylindrical and conical sheet metal components
- Generate the drawing views of the flat pattern of the sheet metal components
- Create new forming tools
- Edit forming tools

---

## 🧩 Feature Breakdown

### 📐 Base Flange
This is the first feature in most sheet metal models. It defines the base geometry using a sketch and assigns a thickness to it. It sets up the sheet metal parameters such as bend radius, relief type, and thickness.

### 📏 Edge, Miter, and Swept Flanges
These features are added onto edges of the base flange. Miter flanges allow for angular bends between connected flanges, and swept flanges follow a sketched path.

### ➕ Tabs, Hems, Closed Corners
Tabs add additional material. Hems are used to fold edges over to eliminate sharp corners or to strengthen. Closed corners help seal gaps between bends for better manufacturability.

### 🔄 Bends: Sketched, Lofted, Jogged
These allow creative bending of the sheet metal with sketched lines or between profiles (lofted). Jogged bends are used to create offset sections.

### ✂️ Cuts and Corner Relief
Cuts can be placed on flat or bent faces. Corner reliefs are essential to avoid material tearing during bending.

### 🧾 Flat Pattern View
This is the most essential output for fabrication. It converts the 3D part into a 2D layout used by tools like laser cutters or water jets.

### 🧰 Forming Tools
Used to create features like louvers or embosses using pre-defined or custom tools. These tools simulate punching and pressing actions.

---

## 🧩 Visual Reference

| Model View | Flat Pattern View |
|------------|-------------------|
| ![Figure 18-1](assets/Figure18-1.jpg) | ![Figure 18-2](assets/Figure18-2.jpg) |

---

## ✍️ Notes Summary

- Sheet metal parts are generally modeled in **Part mode**.
- The **Sheet Metal CommandManager** contains all tools used for sheet metal modeling.
- Important modeling practices include creating the base flange, then adding secondary features such as edge flanges, hems, jogs, and forming tools.
- Bends are automatically accounted for using standard bend allowances or custom tables.
- Sheet metal design can start from a solid or directly from a flat layout.
- Flattening is used not only for visualization but for downstream operations like CNC and laser cutting.

---

## 💼 Professional Contact

For technical consultation or educational partnerships:

- **Email**: [amir.souhail@gmail.com](mailto:amir.souhail@gmail.com)  
- **LinkedIn**: [Amir Souhail](https://www.linkedin.com/in/amir-souhail-3b939069/)  
- **GitHub**: [Amir-souhail](https://github.com/Amir-souhail)

