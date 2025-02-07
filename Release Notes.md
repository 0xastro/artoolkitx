# artoolkitX Release Notes
--------------------------

## Version 1.0.0
### 2018-03-26

This is the first release of the new artoolkitX SDK.

As well as a brand-new 2D texture tracker developed by the project team and using OpenCV primitives, artoolkitX includes the square tracker and NFT texture tracker from the LGPL-v3 ARToolKit v5, and the external API will be familiar to users transitioning from older versions of ARToolKit.

The component libraries in artoolkitX are combined together into a single dynamic library, or static library, or framework, depending on the platform. Both the lower-level C-API to each component library and the higher-level abstractions in the C++ class structure are available for users to target.

In addition, there is a complete Java library (ARXJ) which interfaces via JNI, and a complete C# library in the separate artoolkitX for Unity project, whichg interfaces via P/Invoke.
