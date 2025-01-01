
# Physical Measurements

## Object Name: Right Sagittal Section 2

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 11,703.95        |
| Height (Y) | 175,228.29       |
| Depth (Z)  | 129,723.72       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | 32,778.05    | 44,481.99    |
| Y    | -68,998.96   | 106,229.32   |
| Z    | -64,230.17   | 65,493.56    |

### Volume:
124,661,377,669,615.48 mm³

## Analysis Results

| Parameter           | Result                        |
|---------------------|-------------------------------|
| Overhangs Detected  | 618,842                       |
| Thin Walls Detected | 1                             |
| Center of Mass (mm) | (38,600.28, 12,942.86, 134.79) |
| Connected Parts     | 6                             |

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
