# Physical Measurements

## Object Name: Left Sagittal Section 3

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 9,495.01         |
| Height (Y) | 182,340.97       |
| Depth (Z)  | 132,074.19       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | -33,433.48   | -23,938.47   |
| Y    | -87,903.98   | 94,437.00    |
| Z    | -68,585.88   | 63,488.31    |

### Volume:
114,599,866,315,947.77 mm³

## Analysis Results

| Parameter           | Result                             |
|---------------------|------------------------------------|
| Overhangs Detected  | 571,797                            |
| Thin Walls Detected | 0                                  |
| Center of Mass (mm) | (-28,759.11, -2,142.32, -2,004.74) |
| Connected Parts     | 2                                  |

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
