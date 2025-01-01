
# Physical Measurements

## Object Name: Brainstem + Arteries

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 50,035.86        |
| Height (Y) | 52,202.26        |
| Depth (Z)  | 72,361.19        |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | -24,500.61   | 25,535.24    |
| Y    | -27,730.75   | 24,471.52    |
| Z    | -33,343.29   | 39,017.90    |

### Volume:
44,612,827,396,325.55 mm³

## Analysis Results

| Parameter           | Result                        |
|---------------------|-------------------------------|
| Overhangs Detected  | 1,592,155                     |
| Thin Walls Detected | 462                           |
| Center of Mass (mm) | (593.94, -6,414.06, 8,474.16) |
| Connected Parts     | 20                            |

### Optimal Orientation:
- Position the smoothest and widest part of the model downward.
- Orient the vascular side upward to minimize unsupported overhang risks.
- Use slicer-generated supports for overhanging vascular areas, such as tree supports in Cura or PrusaSlicer.

## General Settings

### Layer Height:
- **For high detail:** 0.1 mm
- **For standard detail:** 0.15 mm

### Print Speed:
- **For intricate features and overhangs:** 40-60 mm/s
- **General:** 60-80 mm/s

### Infill Settings:
- **Infill Percentage:**
  - For structural integrity: 15-20%
  - For reduced weight: 10-15%
- **Infill Pattern:**
  - Gyroid (recommended for strong, lightweight builds)
  - Grid or Triangles (for structural consistency)

### Wall Settings:
- **Wall Thickness:**
  - Minimum: 1.2 mm (3 perimeter lines for 0.4 mm nozzle)
  - For durability: 1.6-2.0 mm
- **Wall Line Count:**
  - Standard: 3-4 lines
  - For complex geometry or overhangs: 4-5 lines

### Overhang Considerations:
- **Support Structures:**
  - Use tree supports or custom supports to minimize material waste.
  - Overhang angle threshold: 45°.
- **Bridging Settings:**
  - Lower speed during bridging (20-30 mm/s).
  - Enable cooling fan for bridging areas.

### Additional Settings:
- **Build Plate Adhesion:**
  - Use a brim or raft to improve adhesion due to the model’s size and overhangs.
- **Cooling:**
  - Enable cooling fans for overhangs and detailed sections.
  - Set fan speed to 100% after the first few layers.
