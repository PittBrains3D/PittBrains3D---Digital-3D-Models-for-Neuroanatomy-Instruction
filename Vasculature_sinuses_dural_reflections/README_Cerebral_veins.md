
# Physical Measurements

## Object Name: Cerebral Veins

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 79,102.14        |
| Height (Y) | 186,310.88       |
| Depth (Z)  | 108,819.53       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | -4,271.96    | 74,830.18    |
| Y    | -99,816.71   | 86,494.17    |
| Z    | -18,906.98   | 89,912.54    |

### Volume:
31,362,191,702,750.89 mm³

## Analysis Results

| Parameter           | Result                            |
|---------------------|-----------------------------------|
| Overhangs Detected  | 103,840                           |
| Thin Walls Detected | 1                                 |
| Center of Mass (mm) | (19,991.32, 13,761.18, 40,209.03) |
| Connected Parts     | 2                                 |

### Best Printing Orientation

**Optimal Position:**  
- Position the model such that the flattest and most stable part of the veins is in contact with the build plate.  
- Orient the model so that intricate, overhanging vein structures are minimized to reduce the need for supports.  
- Rotate the model slightly to allow vertical growth of branches rather than horizontal spans to improve strength and detail.  
- Use the central vein structure (e.g., straight sinus) as the anchoring axis.  

## Recommended Print Settings

### General Settings:
- **Printer Type:** SLA (resin) printing is recommended for intricate models like this due to its ability to capture fine details. FDM may struggle with the small vein structures.

### Layer Height:
- **SLA:** 0.025–0.05 mm for high detail.  
- **FDM:** 0.1 mm for balance between detail and print time.  

### Infill:
- **SLA:** Not applicable.  
- **FDM:** 15–20% infill with a lightweight pattern (e.g., gyroid) to support delicate structures.  

### Supports:
- **SLA:** Add light supports on overhanging branches. Avoid placing supports on thin, fragile veins.  
- **FDM:** Use tree supports to minimize contact points and protect details.  

### Resin-Specific Settings:
- **Exposure Time:** Adjust to resin type; for standard resins, start with 8–12 seconds per layer.  
- **Base Layers:** Use 5–8 base layers for better adhesion.  
- **Build Plate Adhesion:** Add a raft or larger support base to prevent detachment.  

### FDM-Specific Settings:
- **Nozzle Size:** Use a smaller nozzle size (e.g., 0.2–0.3 mm) to capture fine details.  
- **Print Speed:** Reduce speed to 30–40 mm/s for better accuracy.  
- **Cooling:** Increase cooling fan speed for better overhang performance.  
- **Retraction Settings:** Fine-tune retraction (e.g., 2–4 mm) to prevent stringing between thin branches.  

