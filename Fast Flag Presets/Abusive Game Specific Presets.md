---
title: Abusive Game Specific Presets
order: -1
---

<h1 align="center">Abusive Game Specific Presets</h1>

# Tsb
### Attack Nullifier
> [!NOTE]
> **This flag makes you invincible against:**
- Tatsumaki's mid-air attack 1
- Tatsumaki's ultimate 4
- Metal Bat's ultimate 1

It also allows you to use evasive maneuvers against Suiryu's first move (try dashing constantly).

It might also work against Genos' ultimate 1, but this needs to be tested.**
```json
{
    "DFIntGameNetPVHeaderLinearVelocityZeroCutoffExponent": "True"
}
```
# Rivals
### [original video link](https://www.youtube.com/watch?v=jfHq5J0jHY4)
### Constant Hops/hip height (Change - Value)
``` json
{
"DFIntMaxAltitudePDStickHipHeightPercent": "-24"
}
```
### original of above
> [!TIP]
> **Very controllable bounce, only works with negative values, 0 allows you to hover**
``` json

    {
        "DFIntMaxAltitudePDStickHipHeightPercent": "-200"
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
### original of above
``` json
{
    "DFIntNewRunningBaseGravityReductionFactorHundredth": "1500"
}
```
### Trowel Fling / Subspacemine Fling/Stick unanchored parts to you
``` json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```
### original of above
##### - = up, + = down
###### flings you a bit
``` json
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```

