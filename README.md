# mc-depthmap
A simple Minecraft shader that produces a black and white depthmap as its output

## Installing
Download latest .zip from the [releases tab](https://github.com/KolibroidAmy/mc-depthmap/releases), and move it to  your shaderpack folder.
Alternatively, you can just clone this repo directly into the shaderpack folder.

## Screenshots
![Screenshot_20240707_215902](https://github.com/KolibroidAmy/mc-depthmap/assets/152735803/17b2215d-ac1d-4242-96b9-d6f07f096952)
The settings menu as seen using 1.21 / Iris. Both sliders travel from 0 to 255 blocks.

The "depth" of a point in the image could be defined in one of 2 ways - either the distance along the direction that the camera is facing, which is typical for a depth map, or the "true" distance between that point and the camera. Both modes are supported.
|![](https://github.com/KolibroidAmy/mc-depthmap/assets/152735803/acf1d706-f822-41e0-bb6a-8c2521275b35)|![](https://github.com/KolibroidAmy/mc-depthmap/assets/152735803/acb5b438-4531-4dfe-b00d-1dad17eea5a4)|
|:-:|:-:|
| Standard depth map | True distance |
