---
layout: page
name: Basic 3D Rendering Engine
tools: [Graphics, OpenGL, C++, GLFW, Custom Engine, 3D]
image: "/assets/soloprojects/3DBasicRenderingEngine/Title.png"
---

# Basic 3D Rendering Engine

<br>
{% include elements/video.html id="PyVOPWtsB9o" %}

## Description
- ###### Understand the modern GPU architecture
- ###### Deal with overview of modern GPU (graphics processor unit) architecture and the common graphics APIs used, including OpenGL
- ###### Rendering techniques covered include texturing, illumination models,transparency, shading algorithms, mapping techniques (bump mapping environment/reflection mapping, etc.), and shadows

## Information
- ##### **Github**: 
[Link](https://github.com/JinhyunChoi-DEV/Digipen_CS300_Assignment)
- ##### **Engine**: 
Custom Engine
- ##### **Language**: 
C++
- ##### **Tools**: 
OpenGL, ImGui, GLFW, RenderDoc


## Contributions
 - ###### Implement shading algorithms on the GPU through programmable shaders
 - ###### Making own a 3D object loader to import assets into a graphics pipeline(not using Assimp)
 - ###### Implement Lighting: Point, Directional, and Spotlights lighting
 - ###### Implement Texture & Material System with CPU/GPU calculation of UV
 - ###### Implement Sky box, Environment Mapping combine combine with Phong Shading(All features did not used OpenGL functions)
 - ###### Use the FBO functionality to construct an FBO with 6 render-to-texture targets/attachments for making Environment Mapping


<br>
## Photo
{% capture carousel_images %}
/assets/soloprojects/3DBasicRenderingEngine/3d_rendering_engine_1.png
/assets/soloprojects/3DBasicRenderingEngine/3d_rendering_engine_2.png
/assets/soloprojects/3DBasicRenderingEngine/3d_rendering_engine_3.png
/assets/soloprojects/3DBasicRenderingEngine/3d_rendering_engine_4.png
{% endcapture %}
{% include elements/carousel.html %}