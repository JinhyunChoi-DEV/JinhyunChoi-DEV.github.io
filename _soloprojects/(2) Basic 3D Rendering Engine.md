---
layout: page
name: Basic 3D Rendering Engine
tools: [Graphics, OpenGL, C++, GLFW, Custom Engine, 3D]
image: "/assets/soloprojects/3DBasicRenderingEngine/Title.png"
---

# Basic 3D Rendering Engine

<br>
{% include elements/video.html id="PyVOPWtsB9o" %}

## 간략 설명
- ###### 최신 GPU 아키텍처에 대한 이해를 갖추고 있습니다.
- ###### 최신 GPU(그래픽 처리 장치) 아키텍처 개요와 OpenGL을 포함한 일반적인 그래픽 API를 다루었습니다.
- ###### 텍스처링, 조명 모델, 투명도, 셰이딩 알고리즘, 매핑 기술(범프 매핑, 환경/반사 매핑 등), 그림자 처리 등의 렌더링 기술을 다루었습니다.

## 정보
- ##### **Github**: 
[Link](https://github.com/JinhyunChoi-DEV/Digipen_CS300_Assignment)
- ##### **엔진**: 
커스텀 렌더링 엔진 - Custom Rendering Engine
- ##### **언어**: 
C++
- ##### **도구**: 
OpenGL, ImGui, GLFW, RenderDoc


## 기여 내용
 - ###### 프로그래머블 셰이더를 통해 GPU에서 셰이딩 알고리즘을 구현했습니다.
 - ###### Assimp를 사용하지 않고 자체 3D 객체 로더를 제작하여 그래픽 파이프라인에 에셋을 임포트했습니다.
 - ###### 포인트, 방향, 스포트라이트 조명을 구현했습니다.
 - ###### CPU/GPU를 통한 UV 계산으로 텍스처 및 재질 시스템을 구현했습니다.
 - ###### 스카이박스와 환경 맵핑을 구현하고, 이를 Phong 셰이딩과 결합했습니다(모든 기능은 OpenGL 함수를 사용하지 않고 구현했습니다).
 - ###### FBO 기능을 사용하여 6개의 텍스처 타겟/부착물로 구성된 FBO를 만들어 환경 맵핑을 구현했습니다.


<br>
## Photo
{% capture carousel_images %}
/assets/soloprojects/3DBasicRenderingEngine/3d_rendering_engine_1.png
/assets/soloprojects/3DBasicRenderingEngine/3d_rendering_engine_2.png
/assets/soloprojects/3DBasicRenderingEngine/3d_rendering_engine_3.png
/assets/soloprojects/3DBasicRenderingEngine/3d_rendering_engine_4.png
{% endcapture %}
{% include elements/carousel.html %}