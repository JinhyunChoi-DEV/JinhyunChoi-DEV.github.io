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

## 간략 설명
- ###### 기본과 고급 레이 트레이싱 기법을 탐구하며 교차점 계산, 로컬 조명 모델(micro-facet BRDF), 글로벌 조명 모델(몬테카를로 방법을 이용한 조명 방정식 해결)을 다루었습니다.
- ###### 차세대 이벤트 예측을 포함한 경로 추적(Path Tracing) 알고리즘을 구현하여, 전통적인 실시간 그래픽스에서는 보기 힘든 독창적인 조명과 모델링 기법을 활용한 이미지 생성에 성공했습니다.
- ###### 고급 렌더링 알고리즘에 대한 숙련된 기술을 입증했습니다.


## 정보
- ##### **Github**: 
[Link](https://github.com/JinhyunChoi-DEV/CS500)
- ##### **엔진**: 
커스텀 렌더링 엔진 - Custom Rendering Engine
- ##### **언어**: 
C++
- ##### **도구**:
 OpenMP, GLM, bvh library, Assimp, RNGen


## 기여 내용
 - ######  다양한 표면 유형(explicit, implicit, procedural, fractal, …)에 대한 광선-표면 교차 계산을 구현했습니다.
 - ###### Modern micro-facet BRDFs, 반사, 굴절, 그림자 효과를 포함한 로컬 조명 계산을 수행했습니다.
 - ###### 간접 조명을 위한 적분 조명 방정식을 통한 글로벌 조명 계산을 구현했습니다.
 - ###### 다중 중요도 샘플링과 다양한 성능 최적화 기법을 포함한 적분 조명 방정식의 몬테카를로 솔루션을 적용했습니다.