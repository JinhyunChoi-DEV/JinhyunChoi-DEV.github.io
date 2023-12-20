---
layout: page
name: Static Ray Tracing 
tools: [Graphics, C++, Custom Engine, 3D]
image: "/assets/soloprojects/StaticRayTracing/Title.jpg"
---

# Static Ray Tracing 

<br>
{% capture carousel_images %}
/assets/soloprojects/StaticRayTracing/result_normal_color.jpg
/assets/soloprojects/StaticRayTracing/result_base_color.jpg
/assets/soloprojects/StaticRayTracing/result_t_value_color.jpg
/assets/soloprojects/StaticRayTracing/result_diffuse_color.jpg
/assets/soloprojects/StaticRayTracing/implicit_4096.jpg
/assets/soloprojects/StaticRayTracing/explicit_4096.jpg
/assets/soloprojects/StaticRayTracing/Beckman_pass_4096.jpg
/assets/soloprojects/StaticRayTracing/phong_pass_4096.jpg
/assets/soloprojects/StaticRayTracing/GGX_pass_4096.jpg
/assets/soloprojects/StaticRayTracing/Beckman_transmission.jpg
/assets/soloprojects/StaticRayTracing/GGX_transmission.jpg
/assets/soloprojects/StaticRayTracing/MISweights_pass_4096.jpg
/assets/soloprojects/StaticRayTracing/transmission_pass_4096.jpg
/assets/soloprojects/StaticRayTracing/result_pass_8196.jpg
{% endcapture %}
{% include elements/carousel.html %}

## Description
- ###### Explored fundamental and advanced ray tracing techniques, covering intersection calculations, local illumination models (micro-facet BRDF), and global illumination models (lighting equation solved using Monte Carlo methods) 
- ###### Culminated in implementing a path-tracing algorithm with next event estimation, capable of generating images showcasing unique lighting and modeling techniques not typically found in traditional real-time graphics
- ###### Demonstrated proficiency in advanced rendering algorithms


## Information
- ##### **Github**: 
[Link](https://github.com/JinhyunChoi-DEV/CS500)
- ##### **Engine**: 
Custom Engine
- ##### **Language**: 
C++
- ##### **Tools**:
 OpenMP, GLM, bvh library, Assimp, RNGen


## Contributions    
 - ###### Calculations for ray-surfaces intersection of many types of surfaces: explicit, implicit, procedural, fractal, …
 - ###### Local lighting calculations: Modern micro-facet BRDFs, reflection, refraction, shadowing
 - ###### Global lighting calculations: Indirect calculations via the integral lighting equation
 - ###### The Monte Carlo solution to the integral lighting equation including many importance sampling techniques, multiple-importance sampling and other performance enhancements