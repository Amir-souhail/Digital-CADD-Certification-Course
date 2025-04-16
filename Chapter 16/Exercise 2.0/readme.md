# Binoculars CAD Model - Surface Modeling Exercise  

---

## 📌 Overview  
This exercise guides you through creating **binoculars using surface modeling techniques**. The goal is to build a closed surface model, knit all surfaces together, and convert it into a solid.  

**Expected Completion Time:** 1 hour  

---

## 🛠️ Design Specifications  
### **Key Dimensions**  
- **Primary Radii:**  
  - R5, R12.5 (3x), R65, R115, R245, R300, R700  
- **Hole Features:**  
  - 2x Ø80 (lens cutouts)  
- **Distances:**  
  - 150mm, 200mm (reference planes)  
  - 230mm, 257mm, 375mm (section offsets)  
- **Fillets:**  
  - Default fillet radius: **5mm** (unless specified otherwise)  

### **Modeling Constraints**  
- Each loft section is offset from its parent by **10mm**.  
- Planes are used to define sections for the lofted surface.  
- Origin is the primary reference point.  

---

## 📝 Step-by-Step Instructions  

### **1. Surface Creation**  
- **Lofted Main Body:**  
  - Create sections on offset planes (10mm spacing).  
  - Use guide curves to maintain smooth transitions (refer to radii: R65, R115, R245).  
- **Lens Cutouts:**  
  - Add 2x Ø80 holes for lenses.  
- **Fillets:**  
  - Apply **5mm fillets** to edges (unless noted otherwise).  

### **2. Surface Knitting**  
- Combine all surfaces (`Surface-Knit`) into a single watertight body.  

### **3. Solid Conversion**  
- Thicken the surface to create a **solid model** (thickness not specified; assume uniform).  

### **4. Final Detailing**  
- Add remaining fillets (e.g., R12.5 in 3 locations).  
- Verify symmetry and dimensions against Figure 16-160.  

---

## 💻 Supported CAD Software  
This exercise can be completed in most **surface-modeling CAD tools**, including:  
- **SolidWorks** (recommended for this workflow)  
- Autodesk Inventor  
- CATIA  
- Siemens NX  

---

## 📌 Notes  
1. **Reference Planes:** Use the 150mm and 200mm dimensions to position critical sections.  
2. **Symmetry:** The binoculars are symmetrical; consider mirroring after completing one half.  
3. **Fillets:** Apply **R5 fillets** liberally for ergonomic edges.  

---

## 🎯 Learning Outcomes  
By completing this exercise, you will practice:  
✅ **Surface lofting** with offset sections  
✅ **Surface knitting** for watertight geometry  
✅ **Solid conversion** via thickening  
✅ **Fillet application** for realistic edges  

---

## 📂 Attachments  
- `Dimensions.jpg` → Detailed technical drawing (Figure 16-160).  
- `Exercise 2.jpg` → Problem statement and model reference (Figure 16-159).  

---

**Tip:** For efficiency, use **mirroring** after modeling one half of the binoculars!  

**Happy Modeling!** 🔧
