---
layout: page
name: Advanced 3D Rendering Engine
tools: [Graphics, OpenGL, C++, GLFW, Custom Engine, 3D]
image: "/assets/soloprojects/Advanced3DRenderingEngine/Title.png"
---

# Advanced 3D Rendering Engine

<br>
{% include elements/video.html id="4FegpsqSGNI" %}

## 간략 설명
- ###### 기초적인 렌더링 엔진을 넘어서, 고급 렌더링 기법을 적용하여 실시간 렌더링 엔진을 개발하였습니다. 다양한 셰이더를 사용하여 렌더링 성능을 최적화하고, 비주얼 품질을 높였습니다.
- ###### 그림자, PBR(Physically Based Rendering), IBL(Image-Based Lighting), 앰비언트 오클루전(Ambient Occlusion) 등의 현대적인 렌더링 기법을 엔진에 통합하여 사실감 있는 시각적 표현을 구현하였습니다.
- ###### Compute Shader를 이용해 다양한 후처리(Post Processing) 효과를 구현하였으며, 렌더링 성능을 고려한 최적화도 함께 진행하였습니다.


## 정보
- ##### **Github**: 
[Link](https://github.com/JinhyunChoi-DEV/Advanced-Real-time-Rendering)
- ##### **엔진**: 
커스텀 렌더링 엔진 - Custom Rendering Engine
- ##### **언어**: 
C++
- ##### **도구**:
 OpenGL, ImGui, GLFW, RenderDoc, Assimp


## 기여 내용
 - ###### 기본적인 Deferred Shading을 구현하고, 많은 수의 라이트를 처리하기 위해 OpenGL의 SSBO(Shader Storage Buffer Object)를 활용하여 동적 라이트 갯수 증가 기능을 구현하였습니다.
 - ###### Compute Shader를 사용하여 블러 효과와 Irradiance Map 생성 기능을 구현하였고, 이를 통해 렌더링 품질을 향상시켰습니다.
 - ###### Compute Shader로 Momenet Shadow Map과 앰비언트 오클루전(Ambient Occlusion)을 구현하여 사실감 있는 그림자 효과와 환경적 그림자 처리를 추가하였습니다.
 - ###### 물리 기반 조명(PBR)을 구현하여 사실적인 재료 상호작용을 제공하고, 이미지 기반 조명(IBL)을 적용하여 향상된 환경 반사를 구현하여 시각적 충실도를 크게 향상시켰습니다.
 - ###### Sobel Kernel 필터를 사용한 컨볼루션으로 윤곽선 검출 기능을 구현하고, 버텍스 쉐이더 내에서 버텍스 노이즈 기능을 적용하여 비사실적인 렌더링 기법을 구현하였습니다.

 <br>
## Photo
{% capture carousel_images %}
/assets/soloprojects/Advanced3DRenderingEngine/1.png
/assets/soloprojects/Advanced3DRenderingEngine/2.png
/assets/soloprojects/Advanced3DRenderingEngine/3.png
/assets/soloprojects/Advanced3DRenderingEngine/4.png
/assets/soloprojects/Advanced3DRenderingEngine/5.png
/assets/soloprojects/Advanced3DRenderingEngine/6.png
/assets/soloprojects/Advanced3DRenderingEngine/7.png
/assets/soloprojects/Advanced3DRenderingEngine/8.png
/assets/soloprojects/Advanced3DRenderingEngine/9.png
/assets/soloprojects/Advanced3DRenderingEngine/10.png
{% endcapture %}
{% include elements/carousel.html %}