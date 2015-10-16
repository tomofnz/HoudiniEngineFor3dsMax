# Houdini Engine for 3dsMax
## Requirements
- Visual Studio 2012(vc110)
- 3dsMax 2013/2014/2015/2016
- Houdini 15.0.244.16

## How to Build
Project files of Visual Studio is located in the build folder. To build it is necessary to set the environment variable, please refer to the following.

### Environment Variables
#### HOUDINI
##### HOUDINI_ROOT

    set HOUDINI_ROOT=[your houdini install path]
    example:
    set HOUDINI_ROOT=C:\Program Files\Side Effects Software\Houdini 15.0.244.16

#### 3DSMAX
##### ADSK_3DSMAX_SDK_2013
##### ADSK_3DSMAX_SDK_2014
##### ADSK_3DSMAX_SDK_2015
##### ADSK_3DSMAX_SDK_2016
    set ADSK_3DSMAX_SDK_2016=[your maxsdk path]
    example:
    set ADSK_3DSMAX_SDK_2016=D:\Program Files\Autodesk\3ds Max 2016 SDK\maxsdk

## Acknowledgement
In advancing this project I learned a lot from following:

- [HoudiniEngine for Maya](https://github.com/sideeffects/HoudiniEngineForMaya)
- [Exocortex Crate](https://github.com/Exocortex/ExocortexCrate)
- Maxsdk samples


HoudiniEngine team gave me to solve the following problems in HAPI2.0.

1. DLL collition issue between 3dsMax(2015 and 2016) and HoudiniEngine
2. Conflict tbb thread between 3dsMax(2013 and 2014) and HoudiniEngine
