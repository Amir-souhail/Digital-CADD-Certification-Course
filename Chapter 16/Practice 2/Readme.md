

# 🧩 Bottle Surface Modeling Practice  
**By Amir Souhail**  
[![SOLIDWORKS Certified](https://img.shields.io/badge/SOLIDWORKS-Certification-blue?logo=solidworks&logoColor=white)](https://www.solidworks.com/certifications)

---

## 📘 About This Project

This project is a part of the **SOLIDWORKS Certification Course** offered by **Digital CADD Solutions**.  
I used advanced **Surface Modeling** tools to design a complex bottle shape using zero-thickness geometry, and then converted it into a solid model using the `Thicken` feature.

---

## 🎯 Learning Outcomes

By completing this model, I improved my ability to:
- Work with boundary and filled surfaces
- Use curves and planes to drive geometry
- Trim, extend, and knit surface bodies
- Convert surface bodies into solid parts
- Apply fillets and create mirror symmetry

---

## 🛠️ Feature Breakdown

Here’s a quick explanation of the features used, based on the feature tree:

- `Surface-Extrude1`: I started by creating a base surface using a 2D sketch extrusion.
- `Surface-Extrude2`: A secondary extrusion to add another section to the surface body.
- `Boundary-Surface1`: Created a smooth transition between two profiles using boundary surface.
- `Surface-Offset1`: Offset the original surface to generate thickness without making it solid yet.
- `Curve1` & `Curve2`: Used as guide curves to control boundary/loft features.
- `Surface-Trim1` & `Surface-Trim2`: Trimmed away extra surfaces to refine the outer profile.
- `Boundary-Surface2`: Used to close and shape part of the trimmed region.
- `Surface-Knit8`: Knit multiple trimmed and boundary surfaces into a single body.
- `Fillet1`: Applied fillets for a smooth transition between surfaces.
- `Mirror1`: Mirrored half of the body to create symmetry.
- `Surface-Radiate1`: Applied a radiated surface for curvature control.
- `Surface-Fill1`: Closed small gaps using the Fill Surface tool.
- `Surface-Knit9`: Final knitting of all surfaces before thickening.
- `Thicken1`: Converted the knitted surface into a solid model with defined wall thickness.

---

## 🖥 Software Used
- **SOLIDWORKS 2022 or later**
- Mode: `Part`
- Environment: `Surfaces CommandManager`

---

## 📂 Notes

- This model was done entirely using **Surface Modeling**, not solid features.
- Surface modeling helps me achieve complex and organic shapes more efficiently.
- Perfect practice for mastering tools like `Loft`, `Boundary`, `Trim`, and `Knit`.

---

## ✍️ Author

**Amir Souhail**  
R&D Engineer | EDGELab  
Passionate about CAD, AUV design, and mechanical modeling.

---

