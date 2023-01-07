# VR Gantry Crane

## 📌 프로젝트 목표
+ **VR 크레인 체험**을 통해 중장비를 다루는 직업에 종사하고자 하는 사람들에게 조작 기술을 습득하기 위한 진입 장벽을 낮춰준다.
+ 중장비를 다루는 직업의 종사자에게 비용, 공간 등의 제약이 없는 **연습 공간**을 제공해 안전사고를 미연에 방지한다.

## 📣 프로젝트 계기
+ 요즘 건설 현장, 항구, 그리고 각종 공사 현장에서는 다양한 종류의 **크레인**과 같은 **중장비**가 사용되고 있다. 이 장비들에 대한 숙련도와 안전사고는 지속적으로 제기되고 있는 사회 안전 문제이며 4차 산업 시대에 맞추어 각종 중장비를 무인화하거나 원격 조정하려는 시도도 계속되고 있다. 현실 세계에서 중장비들에 대한 숙련도를 높이기 위해서는 장비 자체의 높은 가격과 실습 공간을 확보하기 어렵다는 점, 그리고 안전사고 위험이라는 문제에 직면하게 된다. **VR 기술**은 이런 현실적 문제점을 모두 극복하여 마치 실제 중장비를 현실 세계에서 다루는 것과 같은 가상 환경을 체험할 수 있고 장비 조작의 개념적인 파악을 제공할 수 있어 탁월한 해결책이 될 수 있다.

## ⏲ 프로젝트 기간
+ 2019.10~2019.12
+ 도전학기제 II : 팀 프로젝트
+ 구성원 : 4명

## ✏ 프로젝트 기획
+ 크레인을 어떠한 **용도**로 사용하는지 조사
+ 실제로 크레인이 어떠한 **물리적 원리**를 가지고 작동하는지 조사
+ 크레인의 조작법을 익힌 후 이를 그대로 반영할 수 있도록 **동작 알고리즘**(엔진)을 개발
+ 실제 조작 환경에 가깝도록 특정 버튼을 활용한 **크레인 조정 인터페이스** 구현
+ 사용자의 조작에 따라 움직임을 제어하는 HMD와 컨트롤러로 **실제 장비 수준의 몰입감**을 줄 수 있도록 개발
+ 본 프로그램의 조작법을 쉽게 숙지할 수 있도록 **튜토리얼**을 따로 제작

## ⚙ 개발 환경
+ 개발 툴 : `Unity 2019.2.0f1`
+ VR Headset : `Samsung HMD Odyssey`
+ 3D 모델링 수정 : `3ds Max`
+ 텍스처 수정 : `Adobe Photoshop`
+ 오디오 제작 : `GoldWave`
+ Version Control : `Tortoise SVN`

## 📋 개발 내용
+ 크레인의 각 버튼들이 실제 VR 컨트롤러와 어떤 부분과 매칭이 되는지 **조사**
+ 크레인 오브젝트에 **Blend Tree** 애니메이션을 추가하여 Cargo Hook의 움직임을 구현
+ **Cargo Hook**이 컨테이너를 감지하기 위해, RigidBody 컴포넌트를 추가하여 **충돌을 감지**하는 방법을 사용
+ 컨테이너를 잡았을 때는 컨테이너가 Cargo Hook의 자식으로 설정
+ SteamVR 및 Windows Mixed Reality 활용하여 **Samsung HMD Odyssey** 연동
+ 크레인 조종석에 있는 조이스틱이 **컨트롤러**와 상호작용하여 움직일 수 있도록 구현
+ Asset Store를 통해 **항구 배경** 배치
+ **트럭 오브젝트**를 추가하여 컨테이너를 옮길 위치를 지정
+ 크레인 조작을 배울 수 있도록 **튜토리얼** Scene 작성

## ✔ 프로젝트 평가
- 포크레인 같은 장비에 비해 상대적으로 접근성이 낮다고 생각될 수 있는 항만용 크레인 중장비에 대한 인식을 바꿀 수 있는 프로젝트이며, 평소 중장비에 관심이 있었으나 접하기가 힘들어 쉽사리 배우지 못하던 분들에게 도움이 될 수 있는 프로그램을 만들었다. 아직 중장비의 모든 기능은 구현하지 못하였지만, 필수적인 기능들은 구현해두어 체험에 큰 지장은 없을 것으로 판단된다. 본 프로그램은 VR을 활용하여 실제 크레인을 타고 있는 것과 같은 환경을 세팅함으로써 현실감과 생동감까지 구현해냈다고 생각한다.
- 아쉬웠던 점은 사전지식과 대중 자료가 거의 없는 분야였기 때문에 주먹구구식으로 모든 수를 다 시도해보면서 진행했다는 것이다. 또한, 이번 프로젝트의 기간이 충분하지 않아 항만용 크레인 하나를 대상으로 프로그램을 구현하였지만, 우리가 잘 모르는 진입장벽이 높은 중장비들이 공사 현장에는 더 많다는 것이다. 진입장벽이 높은 중장비들에 대한 진입장벽을 낮추는 프로그램을 만들고자 한다면 충분한 사전 조사와 충분한 개발 기간이 주어져야 할 것이다.

<div align="center">
  <table border="0">
    <tr>
      <td align="center" colspan="2">
        <img width="75%" height="75%" src="https://user-images.githubusercontent.com/60832219/211150593-6c960cfa-c6fd-47e4-8f32-dd14e62cb663.png"/>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        항구의 모습
      </td>
    </tr>
    <tr>
      <td align="center">
        <img width="100%" height="100%" src="https://user-images.githubusercontent.com/60832219/211150595-1c51f969-dae7-4c72-bb53-7dd1a362c46a.gif"/>
      </td>
      <td align="center">
        <img width="100%" height="100%" src="https://user-images.githubusercontent.com/60832219/211150603-f170f264-1d1d-4a42-968f-7dd18fa34e09.gif"/>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        움직이는 크레인의 모습
      </td>
    </tr>
    <tr>
      <td align="center">
        <img width="100%" height="100%" src="https://user-images.githubusercontent.com/60832219/211150599-f9c440a3-577e-42f2-91a9-ddc71f5a73f7.gif"/>
      </td>
      <td align="center">
        <img width="100%" height="100%" src="https://user-images.githubusercontent.com/60832219/211150606-c0d02495-dc8d-4598-bea9-f6d9ac18e7bd.gif"/>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        컨테이너를 잡는 모습
      </td>
    </tr>
    <tr>
      <td align="center">
        <img width="100%" height="100%" src="https://user-images.githubusercontent.com/60832219/211150600-35d7c5cf-8c7f-435d-bf33-4d280f6e0b91.gif"/>
      </td>
      <td align="center">
        <img width="100%" height="100%" src="https://user-images.githubusercontent.com/60832219/211150611-f99562c0-451b-493a-b773-9f0a709fc0ba.gif"/>
      </td>
    </tr>
    <tr>
      <td align="center" colspan="2">
        컨테이너를 놓는 모습
      </td>
    </tr>
  </table>
</div>
