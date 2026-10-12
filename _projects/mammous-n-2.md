---
layout: page
title: MammouS N · 2
description: >-
  <span class="lang-ko">리프트·회전 축 액추에이터와 메커니즘, 축 제한 설계, 주조·압출 구조재</span><span class="lang-en">Lift and rotation actuators and mechanisms, axis-limiting design, cast and extruded structures</span>
img: # assets/img/mammous-n-2.jpg 를 넣은 뒤 경로를 적으면 카드 썸네일로 표시됨
importance: 4
category: work
---

{% raw %}<!-- 그림 넣는 법: assets/img/ 에 파일을 두고 아래 형식으로 삽입
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/mammous-n-2_1.png" title="" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
-->{% endraw %}

<div class="lang-ko" markdown="1">
<p class="post-description">2021.11 ~ 2024.07 / Nov 2021 – Jul 2024</p>

## 축 제한 설계에서 액추에이터 선정으로

- 리프트·회전 축의 가동 범위·정지 조건·동력 상실 시 거동을 정하고, 기계적·전기기계적 제한 장치와 소프트 축 제한 세 층으로 배분
- 그 조건의 요구 토크로 서보 모터와 웜 감속기를 선정 - 웜의 자기잠금으로 동력 상실 시 위치 유지, 정전 유지력 시험으로 확인

[그림 자리: 구동부 구성도 - A1 리프트, A2 체인 견인 승강, A3 L-arm 회전]

## 메커니즘

- 리프트: 본체 상·하단 스프로킷에 건 롤러 체인 2줄이 캐리지를 견인, 모터는 본체 하단, 가스 스프링으로 자중 보상
- 회전: 중공 회전 중심으로 L-arm 배선을 통과시키고 롤러 체인 오프셋으로 구동 - L-arm 외력 모멘트에서 회전 방향 유격 최소화
- 끼임·충돌 시 모터 출력으로 체인·축·감속기 강도 계산

## 구조재

- 회전 베이스·L-arm 프레임을 알루미늄 주조(AC4C)로 일체화 - 중량 대비 강성, 부품 통합
- 본체 기둥을 압출(A6063)로 설계 - 배선 통로 확보
- 주조 프레임 정적 해석, 안전율은 IEC 60601-1 인장 강도 기준

[그림 자리: 주조·압출 구조재 사진]

## 결과

- 초도 N 10대·2세대 10대 양산 이관, 기구 제작 부품 298종, 등록특허 KR102801989B1(스캐닝 모듈, 공동발명)

</div>

<div class="lang-en" markdown="1">
<p class="post-description">2021.11 ~ 2024.07 / Nov 2021 – Jul 2024</p>

## From axis-limiting design to actuator sizing

- Defined travel, stop conditions and power-loss behavior of the lift and rotation axes and allocated them across three layers: mechanical and electro-mechanical limiting devices and soft axis limits
- Sized servo motors and worm reducers from the torque required under those conditions; worm self-locking holds position on power loss, verified by a power-off holding test

[figure: drive layout - A1 lift, A2 chain-pulled lift, A3 L-arm rotation]

## Mechanisms

- Lift: two roller chains over upper and lower sprockets pull the carriage, motor at the base, gas springs compensate gravity
- Rotation: a hollow rotation center passes the L-arm cables and an offset roller chain drives the arm, minimizing rotational backlash under L-arm external moment
- Chain, shaft and reducer strength calculated from motor output under pinch and collision conditions

## Structures

- Rotation base and L-arm frame integrated as aluminium castings (AC4C) for stiffness-to-weight and part consolidation
- Main-body column as an aluminium extrusion (A6063) providing the cable channel
- Static FEA of the cast frame; safety factors per IEC 60601-1 tensile-strength requirements

[figure: cast and extruded structural parts]

## Result

- First lots of 10 MammouS N and 10 MammouS 2 transferred to production; 298 fabricated mechanical parts; registered patent KR102801989B1 (scanning module, co-inventor)

</div>
