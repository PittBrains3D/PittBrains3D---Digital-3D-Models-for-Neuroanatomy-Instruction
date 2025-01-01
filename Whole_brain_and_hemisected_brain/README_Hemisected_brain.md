
# Physical Measurements

## Object Name: Hemisected Brain

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 76,686.74        |
| Height (Y) | 197,154.51       |
| Depth (Z)  | 156,407.84       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | 535.72       | 77,222.46    |
| Y    | -98,576.17   | 98,578.34    |
| Z    | -78,203.27   | 78,204.56    |

### Volume:
991,197,059,612,831.38 mm³

## Analysis Results

| Parameter           | Result                         |
|---------------------|--------------------------------|
| Overhangs Detected  | 1,505,140                      |
| Thin Walls Detected | 0                              |
| Center of Mass (mm) | (30,319.67, 7,914.49, -255.22) |
| Connected Parts     | 2                              |

### Best Printing Orientation for Hemisected Brain

**Orientation:**  
Scenario A: Posterior Pole Down (Vertical Orientation)

Position the hemisphere so that the posterior pole (occipital region) is seated on the build platform, with the flat/medial cut standing vertically.
This orientation aligns the gyri and sulci on the medial and ventral surfaces away from direct contact with the build plate and support structures.

#### Technical Advantages
- **Preservation of Detail:** Supports primarily contact less critical areas, thus preserving fine anatomical details on the medial and ventral surfaces.
- **Reduced Scarring on Delicate Features:** Minimizes the contact area between supports and the most intricate regions (gyri, sulci).

#### Technical Disadvantages
- **Higher Risk of Detachment:** The narrow base can compromise bed adhesion, especially for taller prints or if the print speed is high.
- **Increased Support Volume:** The structure requires more extensive support scaffolding, which can raise material usage and print time.

#### Key Considerations
- **Bed Adhesion Aids:** Use techniques such as a brim or raft to stabilize the narrow contact area.
- **Filament/Post-Processing Compatibility:** If the selected filament (e.g., PLA, PETG) tolerates sanding, you can smooth support-interface marks on the posterior pole after printing.
- **Printer Calibration:** Ensure your printer’s first-layer calibration and retraction settings are optimized to mitigate stringing and lift-off issues in tall prints.

**Scenario B: Flat Side Down (Horizontal Orientation)**

Position the hemisected face (flat cut) directly on the build plate, with the convex (rounded) outer surface facing upward.
This orientation maximizes the contact area between the model and the platform.

#### Technical Advantages
- **Enhanced Bed Adhesion:** A large, flat surface improves mechanical grip on the build plate, reducing the likelihood of print failures.
- **Reduced Print Complexity:** Requires fewer supports, as most overhangs are limited to smaller internal structures or minor overhanging regions on the ventral surface.

#### Technical Disadvantages
- **Potential Surface Artifacts:** The medial and ventral sides may require supports that could affect surface quality, necessitating additional post-processing.
- **Lower Preservation of Fine Details:** Prolonged support contact on curved or detailed sections can obscure anatomical features.

#### Key Considerations
- **Support Settings:** Adjust support density, interface layers, and placement to minimize scarring on delicate areas.
- **Anatomical Priorities:** If achieving detailed representation of the medial and ventral anatomy is less critical than overall print reliability, this orientation is advantageous.
- **Finishing Techniques:** Post-processing with careful support removal and light sanding (if filament permits) may be required to restore anatomical fidelity.

## Recommended Print Settings for PLA/FDM

### Layer Height:
- Use a fine layer height of 0.1 mm to capture detailed textures on the brain's surface.

### Print Speed:
- Set a slow print speed of 40–50 mm/s for high-resolution printing.

### Infill:
- **Infill Percentage:**  
  - Use 15–20% infill with a grid or gyroid pattern for sufficient internal support without adding excessive weight.

### Supports:
- Enable supports only for overhangs beyond 60°.  
- Use a tree support structure to minimize material usage and ease removal.

### Build Plate Adhesion:
- Use a brim for additional adhesion to prevent warping.

### Material Settings:
- **Nozzle Temperature:** 200–210°C  
- **Bed Temperature:** 60°C  

### Cooling:
- Turn on part cooling fans at 100% after the first few layers to maintain sharp details.

### Post-Processing:
- After printing, gently remove supports and consider light sanding for any areas with artifacts, followed by optional painting or coating for a polished finish.
