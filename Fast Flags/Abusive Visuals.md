---
order: -8
---

### Semi Fullbright
```json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True"
}
```
### Fullbright 1
> [!IMPORTANT]
> **use in games with massive or games with lots of clouds, make sure the game is daytime or has daytime.**

> [!NOTE]
> **fullbright 1 and 2 will let you noclip a bit inside a wall, be-aware.**

> [!TIP]
> **change the DFIntDebugFRMQualityLevelOverride fflag to 0 when you dont want quality 1 and wanna change it in game, best to hide ur fullbright while someone is watching.**
```json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FFlagRenderFixFog": "True",
    "FFlagDisablePostFx": "True"
}
```
### Fullbright 2
> [!IMPORTANT]
> **use in games with massive or games with lots of clouds, make sure the game is daytime or has daytime.**

> [!NOTE]
> **same stuff needed as fullbright but its better, fullbright 1 and 2 will let you noclip a bit inside a wall, be-aware.**

> [!TIP]
> **change the DFIntDebugFRMQualityLevelOverride fflag to 0 when you dont want quality 1 and wanna change it in game, best to hide ur fullbright while someone is watching.**

> [!TIP]
> **for expirenced people, add opengl and remove ur old rendering mode, remove the shaders with a fflag for less shadows.**
```json
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True",
    "DFIntDebugFRMQualityLevelOverride": "1",
    "DFFlagDebugRenderForceTechnologyVoxel": "True",
    "FFlagRenderFixFog": "True",
    "FFlagDisablePostFx": "True"
}
```
### Draws a circle under avatars
```json
{
    "FFlagDebugAvatarChatVisualization": "True",
    "FFlagEnableInGameMenuChromeABTest2": "False"
}
```
### Humanoid Outline
> [!NOTE]
> **Draws an outline around every part and every humanoid**
```json
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```
### fflag above but more complex
> [!NOTE]
> **Draws an outline around every body part**
```json
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```
### Buggy ZPlane Camera ✨
```json
{
    "FIntCameraFarZPlane": "1"
}
```
### Adds an UI in game, which highlights any part player touches (like ground, Meshes etc.). It's a non-functioning UI too. Also adds a blue circle to your humanoid.
```json
{
    "FFlagDebugHumanoidRendering": "True"
}
```
### Xray ✨
###### @tyetonix
```json
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
```
