
# Physical Measurements

## Object Name: Dural Sinuses and Reflections

### Dimensions (mm):
| Dimension  | Measurement (mm) |
|------------|------------------|
| Width (X)  | 143,805.94       |
| Height (Y) | 188,440.67       |
| Depth (Z)  | 187,806.52       |

### Bounding Box Ranges (mm):
| Axis | Minimum (mm) | Maximum (mm) |
|------|--------------|--------------|
| X    | -71,991.15   | 71,814.78    |
| Y    | -99,936.60   | 88,504.08    |
| Z    | -97,498.21   | 90,308.31    |

### Volume:
161,151,424,080,254.94 mm³

## Analysis Results

| Parameter           | Result                         |
|---------------------|--------------------------------|
| Overhangs Detected  | 326,409                        |
| Thin Walls Detected | 0                              |
| Center of Mass (mm) | (-112.84, 15,184.91, 5,688.68) |
| Connected Parts     | 1                              |

### Best Printing Orientation for Dural Sinuses and Reflections

**Optimal Orientation:**  
- **Vertical Orientation (Z-axis):**  
  - Place the central vertical spine upright along the Z-axis.  
  - Ensure that the curved sinuses/reflections face upward to reduce large overhangs.  
  - Tilt the model slightly (~10–15°) backward to reduce the need for supports in concave areas.  

**Key Considerations:**  
- Thin and fragile areas like the central spine must be well-supported to avoid warping.  
- Avoid orienting the model completely flat on the print bed to reduce layer lines and improve details.  
- Ensure that detailed sinuses are not directly on the print bed to prevent smudging of details during the initial layers.  

## Recommended Print Settings (PLA/FDM)

### Layer Height:
- 0.12 mm for a balance between speed and detail.  
- For even finer resolution, use 0.08 mm, but this will increase print time.  

### Infill:
- 20–25% grid infill:  
  - Balances strength while keeping the structure lightweight.  

### Supports:
- Use tree supports to avoid scarring and maintain clean details, especially under overhangs.  
- Focus supports under the curved sinuses and reflections but avoid excessive supports on detailed areas.  
- Use support overhang angle set to 60° to minimize support material in less critical areas.  

### Print Speed:
- **General Printing:** 30–40 mm/s to preserve fine details.  
- **Initial Layers:** Slow the first few layers to 20 mm/s to ensure good adhesion.  

### Temperature Settings:
- **Nozzle:** 200–210°C (adjust for your PLA type).  
- **Bed:** 60°C for optimal adhesion.  

### Adhesion:
- Use a brim (6–8 mm wide) to stabilize the tall and thin areas.  
- A raft can be used for additional stability but may slightly affect the surface finish of the base.  

### Cooling:
- 100% cooling fan after the first layer to prevent warping of thin parts.  

### Retraction:
- Enable retraction to avoid stringing on intricate areas:  
  - **Distance:** 4–6 mm.  
  - **Speed:** 25–40 mm/s.  

