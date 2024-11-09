---
layout: page
name: Character Controller
tools: [Game, C#, Unity Engine, 3D]
image: "/assets/soloprojects/CharacterController/Title.png"
---

# Character Controller

<br>
{% include elements/video.html id="t34nUN8Suhc" %}

## 간략 설명
- ###### 게임 내 프로그래밍 연습을 위한 물리 기반 캐릭터 컨트롤러 설계.
- ###### 다양한 상태를 구현하고, RPG 게임 캐릭터의 이동 기반을 바탕으로 확장 가능하고 재사용 가능한 코드베이스 작성.
- ###### IK 시스템을 사용하여 더 현실적인 이동 구현.


## 정보
- ##### **Github**: 
[Link](https://github.com/JinhyunChoi-DEV/GAM400)
- ##### **엔진**: 
Unity Engine
- ##### **언어**: 
C#
- ##### **레퍼런스**:
[Detail Material Link](https://docs.google.com/presentation/d/123cQtK5snVZp38f0YRpCceCZ-7gaeqUY4btSqM3J23E/edit?usp=sharing)

## 기여 내용
 - ###### 계층적 상태 기계(Hierarchical State Machine) 패턴을 사용하여 상태 기계 시스템 구현.
 - ###### 상태 기계에 다양한 상태를 쉽게 추가할 수 있도록 코드베이스 구조화.
 - ###### 캐릭터의 바닥 감지(IsGround) 및 계단, 경사로와 같은 다양한 기하학적 형태와의 충돌 문제를 해결하기 위해 Floating Capsule 방법 활용.
 - ###### Root Motion 및 Blend Animation 기능을 사용하여 더 동적인 캐릭터 애니메이션 구현.
 - ###### 기본 애니메이션을 넘어서는 절차적 이동을 위해 IK 시스템 적용.

<br>
## Photo
{% capture carousel_images %}
/assets/soloprojects/CharacterController/charactercontroller1.png
/assets/soloprojects/CharacterController/charactercontroller2.png
/assets/soloprojects/CharacterController/charactercontroller3.png
/assets/soloprojects/CharacterController/charactercontroller4.png
/assets/soloprojects/CharacterController/charactercontroller5.png
{% endcapture %}
{% include elements/carousel.html %}