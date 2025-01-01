
# Physical Measurements

## Object Name: Horizontal Section 1

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 129,768.37       |
| Height (Y) | 36,160.03        |
| Depth (Z)  | 152,301.09       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | -64,838.00   | 64,930.37    |
| Y    | -18,079.88   | 18,080.15    |
| Z    | -61,796.11   | 90,504.98    |

### Volume:
254,363,132,146,701.88 mm³

## Analysis Results

| Parameter           | Result                           |
|---------------------|----------------------------------|
| Overhangs Detected  | 1,142,146                        |
| Thin Walls Detected | 0                                |
| Center of Mass (mm) | (-1,189.43, 8,098.98, 10,462.50) |
| Connected Parts     | 1                                |

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
