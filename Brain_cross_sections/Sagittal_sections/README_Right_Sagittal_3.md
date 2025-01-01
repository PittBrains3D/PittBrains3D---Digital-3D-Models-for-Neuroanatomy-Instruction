
# Physical Measurements

## Object Name: Right Sagittal Section 3

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 13,337.18        |
| Height (Y) | 186,953.46       |
| Depth (Z)  | 135,294.68       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | 17,613.60    | 30,950.78    |
| Y    | -89,740.87   | 97,212.59    |
| Z    | -69,289.38   | 66,005.31    |

### Volume:
159,765,636,051,819.50 mm³

## Analysis Results

| Parameter           | Result                            |
|---------------------|-----------------------------------|
| Overhangs Detected  | 646,097                           |
| Thin Walls Detected | 1                                 |
| Center of Mass (mm) | (23,974.12, -3,457.75, -2,310.77) |
| Connected Parts     | 3                                 |

### Optimal Orientation:
- For optimal printing of sagittal sections, plan to print three to four sections simultaneously. Space them 20–30 mm apart (adjust as needed for section size), and orient each section vertically, with the long axis perpendicular to the build plate and the sagittal surfaces facing outward. This orientation minimizes layer lines on critical faces, preserving fine details. If necessary, slightly tilt each model to maximize the base on the build plate, improving adhesion and reducing the risk of warping or detachment.

## General Settings

### Layer Height:
- **For high detail:** 0.1 mm
- **For standard detail:** 0.2 mm

### Print Speed:
- **Complex features and overhangs:** 40-60 mm/s
- **General:** 60-80 mm/s

### Infill Settings
- **Infill Percentage:**
  - For structural integrity: 15-20%
  - For reduced weight: 10-15%
- **Infill Pattern:**
  - Gyroid (recommended for strong and lightweight builds)
  - Grid or Triangles (for structural consistency)

### Wall Settings
- **Wall Thickness:**
  - Minimum: 1.2 mm (3 perimeter lines for 0.4 mm nozzle)
  - For durability: 1.6-2.0 mm
- **Wall Line Count:**  
  - Standard: 3-4 lines  
  - For complex geometry or overhangs: 4-5 lines  

### Overhang Considerations
- **Support Structures:**  
  - Use tree supports or custom supports to minimize material waste.  
  - Overhang angle threshold: 50-60°.
- **Bridging Settings:**  
  - Lower speed during bridging (20-30 mm/s).  
  - Enable cooling fan for bridging areas.

### Additional Settings
- **Build Plate Adhesion:**  
  - Use a brim or raft to improve adhesion due to the model's size and overhangs.
- **Cooling:**  
  - Enable cooling fans for overhangs and detailed sections.  
  - Set fan speed to 100% after the first few layers.
