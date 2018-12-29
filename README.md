# Puzzler
Starter project for the Udacity [VR Developer Nanodegree](http://udacity.com/vr) program.

- Project: Puzzler-VR


### Versions Used
- [Unity 2018.3.0f2
- [GVR SDK for Unity v1.170.0]
- [iTween] v2.0.9


### Directory Structure
- The Unity project is the child directory of the repository and named according to the associated project.
- The Unity project is 'cleaned' and includes the `Assets` folder, the `ProjectSettings` folder, and the `UnityPackageManager` folder.


### GVR SDK for Unity
- `GoogleVR` > `Demos` is not included.
- `GoogleVR` > `GVRVideoPlayer.unitypackage` is included.
- The `Max Reticle Distance` value for the `GvrReticlePointer` used in the scene is set to `20` instead of the default `10`.
- Scripts applicable to the course have been updated to reflect Unity's API change from `UnityEngine.VR` to `UnityEngine.XR`.

>**Note:** If for any reason you remove and re-import GVR SDK for Unity v1.170.0, make sure you accept any API update pop-up prompts triggered by Unity.
