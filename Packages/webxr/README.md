# WebXR Export

You can [check the live demo here](https://de-panther.github.io/unity-webxr-export)

## Downloads

There are two options to import the package to a Unity project.

* Use OpenUPM [WebXR Export ![openupm](https://img.shields.io/npm/v/com.de-panther.webxr?label=openupm&registry_uri=https://package.openupm.com)](https://openupm.com/packages/com.de-panther.webxr/). It's the best option, as it is much more easier to update the package later.

* Use Git. It can let you use versions that are yet uploaded to OpenUPM - Mostly happens between releases.

### Using Git

To add the package to your Unity project using Git, open the Package Manager window, click on the + icon, "Add package from git URL..." and add the path URL

`https://github.com/De-Panther/unity-webxr-export.git?path=/Packages/webxr`

Then make sure to check `WebXR Export` in `Project Settings > XR Plug-in Management > WebGL > Plug-in Providers`.

To update the package, you'll have to manually remove the corresponding package section from the `packages-lock.json` file. For more info read about [Git dependencies](https://docs.unity3d.com/Manual/upm-git.html) in Unity's manual.

## WebXR Interactions

You might also want to add the WebXR Interactions package, as it has some Interaction Components and Samples.
You can get the WebXR Interactions package [here](../webxr-interactions/README.md) or at OpenUPM [WebXR Interactions ![openupm](https://img.shields.io/npm/v/com.de-panther.webxr-interactions?label=openupm&registry_uri=https://package.openupm.com)](https://openupm.com/packages/com.de-panther.webxr-interactions/).