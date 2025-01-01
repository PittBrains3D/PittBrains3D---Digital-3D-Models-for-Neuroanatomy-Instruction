
# Physical Measurements

## Object Name: Horizontal Section 2

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 137,403.08       |
| Height (Y) | 17,582.91        |
| Depth (Z)  | 176,335.75       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | -68,774.90   | 68,628.17    |
| Y    | -4,350.77    | 13,232.15    |
| Z    | -63,737.74   | 112,598.02   |

### Volume:
240,598,273,960,690.56 mm³

## Analysis Results

| Parameter           | Result                        |
|---------------------|-------------------------------|
| Overhangs Detected  | 866,976                       |
| Thin Walls Detected | 0                             |
| Center of Mass (mm) | (527.44, 5,181.38, 21,326.95) |
| Connected Parts     | 6                             |

### Optimal Orientation:
- For optimal printing of horizontal sections, plan to print three to four sections simultaneously. Space them 20–30 mm apart (adjust as needed for section size), and orient each section vertically, with the long axis perpendicular to the build plate and the horizontal surfaces facing outward. This orientation minimizes layer lines on critical faces, preserving fine details. If necessary, slightly tilt each model to maximize the base on the build plate, improving adhesion and reducing the risk of warping or detachment.

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
