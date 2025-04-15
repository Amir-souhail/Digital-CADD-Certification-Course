# 🍼 Bottle Surface Modeling (SOLIDWORKS)

![SolidWorks Badge](https://img.shields.io/badge/SOLIDWORKS-Certified-blue?logo=solidworks)

This repository contains my practice model for **Surface Modeling** using SOLIDWORKS as part of the certification course offered by **Digital CADD Solutions**. The model represents a complex bottle-like part built using various surface modeling techniques.

---

## 📚 Chapter 16: Surface Modeling

Surface modeling is a technique of creating zero-thickness planar or non-planar geometry. It's widely used in industrial design where aesthetics and curvature continuity matter. I used this method to model a complex bottle shape and then converted it into a solid.

---

## 🎯 Learning Outcomes

After completing this practice, I was able to:

- Create **Extruded, Revolved, and Swept** surfaces
- Generate **Lofted, Planar, and Boundary** surfaces
- Apply **Fill and Radiated** surface techniques
- Use **Trim, Untrim, and Extend** functions
- Offset, fillet, and knit multiple surfaces
- Create a **Mid-surface** and delete holes
- Replace or delete specific faces
- Move and copy surfaces
- Thicken a surface body
- Create surface-based cuts and thickened cuts

---

## 🔧 Feature Tree Explanation

### 🧩 Feature-by-Feature Breakdown

| 🔧 Feature Name       | 📝 Description |
|-----------------------|----------------|
| **Surface-Extrude1**  | I began by extruding a 2D sketch into a surface to form the initial base shape of the bottle. This gave me a planar foundation to build upon. |
| **Surface-Extrude2**  | I added a secondary surface extrusion to form another portion of the bottle’s body—likely to create a step or transition zone in the geometry. |
| **Boundary-Surface1** | I used the Boundary Surface tool to connect two curves/surfaces. This allowed for a smooth and controlled transition between shapes, especially useful in bottle design where curvature matters. |
| **Surface-Offset1**   | I offset an existing surface by a certain distance to begin forming the wall thickness without creating a solid yet. This offset was later used for trimming and knitting. |
| **Curve1** & **Curve2** | These were guide curves I created from sketches to help shape the complex contours of the bottle. They control how surfaces bend or follow paths during features like boundary or loft. |
| **Surface-Trim1**     | I trimmed unwanted portions of a surface using sketch profiles or other surfaces as cutting tools. This helped clean up the model and prepare it for knitting. |
| **Surface-Trim2**     | A second trim operation refined another region—possibly the neck or lower portion of the bottle. |
| **Boundary-Surface2** | I added another boundary surface, likely to fill in a trimmed area or to form the bottom/top closure of the bottle geometry. |
| **Surface-Knit8**     | I used this to join several trimmed and boundary surfaces into a single continuous surface body. This step was important before applying fillets or turning the model solid. |
| **Fillet1**           | I applied fillets to smooth sharp edges between surfaces. This gives a more realistic, manufacturable shape to the bottle. |
| **Mirror1**           | Since the bottle was symmetric, I modeled only half and then mirrored it to save time and maintain consistency. |
| **Surface-Radiate1**  | I used this feature to radiate a surface from an edge or face, adding curvature continuity to enhance the aesthetics or function of the design. |
| **Surface-Fill1**     | I filled a closed contour with a new surface. This is useful for patching small openings that couldn't be closed by boundary surfaces. |
| **Surface-Knit9**     | This was my final knitting operation where I brought all major surfaces together into a single watertight surface body. |
| **Thicken1**          | I converted the final knitted surface into a solid model by thickening it. This made the part ready for simulations or manufacturing. |

---

### 👤 Author
**Amir Souhail**

---

Feel free to explore the feature tree and learn how I approached modeling a bottle using advanced surface features in SOLIDWORKS!

