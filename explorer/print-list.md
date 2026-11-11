# Print list

> ⚠️ Draft: print settings still to be confirmed.

Each part has an `.stl` for printing and a `.step` for editing in the same folder.
"Per robot" assumes 6 legs.

## Materials

**Any rigid filament works for the structural parts** (PETG, ASA, PLA+). The reference build uses PA12-CF for the legs for extra stiffness.

**Exceptions:**
- **Foot: TPU (required).** It needs to be flexible for grip.
- **Tibia cartridge: PETG (required).** Its bearing fit was tuned in PETG.

**Caveats:**
- **Fits were tuned on one printer with the reference materials.** The same CAD fits differently in PETG and PA12-CF. If bearings or rods bind or are loose, adjust the clearance in the STEP file or reprint in the reference material.
- **PLA is fine for testing, but use PETG or better for a robot you'll run for a long time.** PLA softens at around 55 °C. The ST3215 servos get warm under load, and they sit right next to the coxa and femur. At around 4 kg, the femurs also take the most stress.

## Body

| Part | File | Qty per robot | Recommended | Notes |
|---|---|---|---|---|
| Body | [body/body.stl](body/body.stl) | 1 | PETG | |
| Body lid | [body/body-lid.stl](body/body-lid.stl) | 1 | PETG | |
| Pi shelf | [body/pi-shelf.stl](body/pi-shelf.stl) | 1 | PETG | |

## Camera pod

| Part | File | Qty per robot | Recommended | Notes |
|---|---|---|---|---|
| Camera pod shell | [camera-pod/camera-pod-shell.stl](camera-pod/camera-pod-shell.stl) | 1 | PETG | |
| Camera pod plate | [camera-pod/camera-pod-plate.stl](camera-pod/camera-pod-plate.stl) | 1 | PETG | |

## Legs

| Part | File | Qty per leg | Qty per robot | Recommended | Notes |
|---|---|---|---|---|---|
| Leg mount | [legs/leg-mount.stl](legs/leg-mount.stl) | 1 | 6 | PETG or PA12-CF | |
| Leg mount cap | [legs/leg-mount-cap.stl](legs/leg-mount-cap.stl) | 1 | 6 | PETG or PA12-CF | |
| Coxa, half A | [legs/coxa-A.stl](legs/coxa-A.stl) | 1 | 6 | PETG or PA12-CF | |
| Coxa, half B | [legs/coxa-B.stl](legs/coxa-B.stl) | 1 | 6 | PETG or PA12-CF | |
| Coxa panel | [legs/coxa-panel.stl](legs/coxa-panel.stl) | 1 | 6 | PETG or PA12-CF | |
| Femur, half A | [legs/femur-A.stl](legs/femur-A.stl) | 1 | 6 | PETG or PA12-CF | Highest-stress part |
| Femur, half B | [legs/femur-B.stl](legs/femur-B.stl) | 1 | 6 | PETG or PA12-CF | Highest-stress part |
| Femur panel | [legs/femur-panel.stl](legs/femur-panel.stl) | 1 | 6 | PETG or PA12-CF | |
| Tibia | [legs/tibia.stl](legs/tibia.stl) | 1 | 6 | PETG or PA12-CF | |
| Tibia cartridge | [legs/tibia-cartridge.stl](legs/tibia-cartridge.stl) | 1 | 6 | **PETG (required)** | Bearing fit tuned in PETG |
| Shank | [legs/shank.stl](legs/shank.stl) | 1 | 6 | PETG (recommended) | Match the tibia cartridge: rod fits are tuned as a pair |
| Foot | [legs/foot.stl](legs/foot.stl) | 1 | 6 | **TPU (required)** | Flexible, for grip |
| Joint cap | [legs/joint-cap.stl](legs/joint-cap.stl) | 5 | 30 | PETG or PA12-CF | |

## Print settings

Layer height, walls, infill and orientation: TBD.
