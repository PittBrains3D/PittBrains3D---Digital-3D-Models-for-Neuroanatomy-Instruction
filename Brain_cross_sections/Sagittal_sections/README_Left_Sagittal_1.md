# Physical Measurements

## Object Name: Left Sagittal Slab 1

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 24,823.72        |
| Height (Y) | 148,738.86       |
| Depth (Z)  | 114,928.76       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | -70,846.53   | -46,022.82   |
| Y    | -71,716.10   | 77,022.76    |
| Z    | -61,437.44   | 53,491.32    |

### Volume:
138,195,202,239,914.69 mm³

## Analysis Results

| Parameter           | Result                             |
|---------------------|------------------------------------|
| Overhangs Detected  | 1,244,749                          |
| Thin Walls Detected | 3                                  |
| Center of Mass (mm) | (-50,960.85, -4,452.97, -3,492.76) |
| Connected Parts     | 4                                  |

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
