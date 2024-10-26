---
title: Abusive Game Specific Presets
order: -1
---

## Rivals
### [original video link](https://www.youtube.com/watch?v=jfHq5J0jHY4)
### Constant Hops/hip height (Change - Value)
``` json
{
"DFIntMaxAltitudePDStickHipHeightPercent": "-24"
}
```
### Wall Fling/Wallglide
``` json
{
    "DFIntUnstickForceAttackInTenths": "-4",
}
```
### Super Jumps/Possible super jump
``` json
{
    "DFIntNewRunningBaseGravityReductionFactorHundredth": "1425"
}
```
### Trowel Fling / Subspacemine Fling/Stick unanchored parts to you
``` json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
## Slap Battles & Ability Wars
### Anti Kb
> [!NOTE]
> **This automatically teleports all ragdolled players limbs (except torso) to the games 0,0,0 (very unreliable, only drags your torso to the 0,0,0)**
```Json
{
  "DFIntGameNetLocalSpaceMaxSendIndex":100000
}
```
