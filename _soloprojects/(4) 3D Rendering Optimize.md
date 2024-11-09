---
layout: page
name: 3D Rendering Optimize
tools: [Graphics, OpenGL, C++, GLFW, Custom Engine, 3D]
image: "/assets/soloprojects/RenderingOptimize/Title.png"
---

# 3D Rendering Optimize

<br>
{% include elements/video.html id="2SOSclYiG1k" %}

## 간략 설명
- ###### CPU와 GPU 사용에서 병목 현상을 피하기 위해 복잡한 3D 장면을 효율적으로 표현하고 처리하는 방법을 다뤘습니다.
- ###### 다양한 공간 데이터 구조를 구현했습니다: 이진 공간 분할 트리, 옥트리, Kd-트리, 그리드 데이터 구조.
- ###### 충돌 감지 및 관련 기하학적 연산을 위한 바운딩 볼륨 및 그 계층 구조를 구축하고 사용했습니다.


## 정보
- ##### **Github**: 
[Link](https://github.com/JinhyunChoi-DEV/GraphicEngine)
- ##### **엔진**: 
커스텀 렌더링 엔진 - Custom Rendering Engine
- ##### **언어**: 
C++
- ##### **도구**: 
OpenGL, ImGui, GLFW, RenderDoc, Assimp


## 기여 내용
 - ###### 하이브리드 렌더링: 포워드 렌더링 및 디퍼드 렌더링(쉐이딩)
 - ###### 간단한 충돌 교차 및 디버그 드로잉 구현.
 - ###### 바운딩 볼륨: 축 정렬 바운딩 박스(AABB), Ritter's, Larsson's, PCA 기반 방법을 활용한 바운딩 구.
 - ###### 공간 분할: 적응형 옥트리, K-d 트리, BSP 트리.

<br>
## Photo
{% capture carousel_images %}
/assets/soloprojects/RenderingOptimize/renderingoptimize1.png
/assets/soloprojects/RenderingOptimize/renderingoptimize2.png
/assets/soloprojects/RenderingOptimize/renderingoptimize3.png
/assets/soloprojects/RenderingOptimize/renderingoptimize4.png
/assets/soloprojects/RenderingOptimize/renderingoptimize4.png
/assets/soloprojects/RenderingOptimize/renderingoptimize6.png
/assets/soloprojects/RenderingOptimize/renderingoptimize7.png
/assets/soloprojects/RenderingOptimize/renderingoptimize8.png
/assets/soloprojects/RenderingOptimize/renderingoptimize9.png
/assets/soloprojects/RenderingOptimize/renderingoptimize10.png
{% endcapture %}
{% include elements/carousel.html %}