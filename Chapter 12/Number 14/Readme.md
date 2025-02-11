# Top-Down Assembly in SolidWorks

## Overview
This repository contains a **top-down assembly** created in **SolidWorks**, with corresponding **STEP files** for compatibility with other CAD software. The top-down assembly approach ensures that all components are designed within a single assembly file, maintaining parametric relationships between parts for better adaptability and modifications.

## What is a Top-Down Assembly?
A **top-down assembly** is a design method where individual parts are created within an assembly rather than being modeled separately. This approach allows for:
- Directly referencing other components
- Maintaining relationships between parts
- Simplifying design modifications
- Reducing errors in fit and alignment

### Key Features of This Assembly
- **Sketch-Based Components**: All parts are created within the assembly file, eliminating the need to import separate components.
- **Parametric Relations**: Components maintain dynamic constraints, ensuring proper fit when modifications are made.
- **Efficient Design Updates**: Any design changes automatically propagate across all related parts.
- **Exported STEP Files**: Allows compatibility with other CAD software.

## File Structure
- `/SolidWorks_Files/` → Contains the native SolidWorks assembly (`.SLDASM`) and part files (`.SLDPRT`)
- `/STEP_Files/` → Contains the exported STEP files (`.STEP` or `.STP`) for universal compatibility
- `README.md` → This documentation file

## How to Open the Assembly
1. Open **SolidWorks**.
2. Navigate to `File > Open` and select the `.SLDASM` file.
3. Ensure that all referenced part files (`.SLDPRT`) are in the same directory.
4. For non-SolidWorks users, open the `.STEP` file in any compatible CAD software (Fusion 360, Inventor, CATIA, etc.).

## How to Modify the Assembly
1. Open the assembly file (`.SLDASM`) in **SolidWorks**.
2. Right-click on any component and choose `Edit Part` to modify individual components within the assembly.
3. Use the **Feature Manager** to adjust sketches and constraints.
4. Save and rebuild the assembly to reflect changes.

## Usage
- This assembly is designed as a reference for learning and applying top-down design principles in **SolidWorks**.
- Can be used for engineering projects requiring high adaptability.
- Modify and extend as needed for your specific applications.

## Contributions
Feel free to contribute improvements or additional features to this assembly by submitting a **pull request**.

## License
This project is released under the **MIT License**. See `LICENSE` for more details.

---

For any questions or issues, please open an **issue** in this repository.

**Happy Designing!** 🎨✨

