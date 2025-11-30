# GAME_PROGRAM-EX--1
# EXP:1 Implementing various effects in a material such as emissive, roughness and metallic properties in Unreal Engine
## NAME: KISHORE NARAYANAN S R
## REGISTER NUMBER: 212223110023
## Aim
To implement and demonstrate various material effects in Unreal Engine, including emissive, roughness, and metallic properties, using the Material Editor.

## Procedure

1. **Create a New Material:**
   - Open Unreal Engine.
   - In the Content Browser, right-click and select **Material**.
   - Name it `M_EffectsDemo`.

2. **Apply Base Color:**
   - Open the material.
   - Add a **Vector Parameter** or **Constant3Vector** node and connect it to the **Base Color** input.

3. **Add Emissive Effect:**
   - Add a **Multiply** node.
   - Connect a **Constant3Vector** (for emissive color) and a **Scalar Parameter** (for intensity).
   - Connect the result to the **Emissive Color** input.

4. **Control Roughness:**
   - Add a **Scalar Parameter** node and connect it to the **Roughness** input.
   - Lower values = shinier surface, higher values = rougher surface.

5. **Control Metallic Property:**
   - Add a **Scalar Parameter** node and connect it to the **Metallic** input.
   - 0 = non-metal, 1 = fully metallic.

6. **Save and Apply Material:**
   - Save the material.
   - Apply it to any mesh in the scene (like a sphere or cube) to preview the results.
  
     
## Output
<img width="449" height="427" alt="1" src="https://github.com/user-attachments/assets/18c853fa-12bb-479a-8492-3fb43a930145" />

<img width="1192" height="791" alt="2" src="https://github.com/user-attachments/assets/0b711c9a-4aae-4778-863e-543772fdc163" />



## Result
Successfully implemented a material in Unreal Engine showcasing:
- Emissive glow using emissive color and intensity.
- Variable surface roughness to simulate different textures.
- Metallic appearance adjustment to reflect light like real-world metals.

This setup enables dynamic, realistic materials suitable for use in environments, characters, and VFX in Unreal Engine projects.
