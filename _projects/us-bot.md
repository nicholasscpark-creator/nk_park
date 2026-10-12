---
layout: page
title: US-Bot
description: >-
  <span class="lang-ko">구매 협동로봇 암을 품는 이동형 본체, 엔드이펙터, 젤 디스펜서 액추에이터</span><span class="lang-en">A mobile main body around a purchased cobot arm, the end effector, and a gel-dispenser actuator</span>
img: # assets/img/us-bot.jpg 를 넣은 뒤 경로를 적으면 카드 썸네일로 표시됨
importance: 3
category: work
---

{% raw %}<!-- 그림 넣는 법: assets/img/ 에 파일을 두고 아래 형식으로 삽입
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/us-bot_1.png" title="" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
-->{% endraw %}

<div class="lang-ko" markdown="1">
<p class="post-description">2025.01 ~ 2025.11 / Jan 2025 – Nov 2025</p>

## 시스템 구성과 본인 설계 범위

| 구성품 | 사양 | 설계 |
|---|---|---|
| 협동로봇 암 | payload 3 kg (레인보우로보틱스 RB3-1200E) | 구매품, 장착부 설계 |
| 3D 카메라 | Mech-Mind Mech-Eye NANO | 구매품, 엔드이펙터 배치 |
| 초음파 진단기·프로브 | 구매품 | 프로브 홀더·브라켓 설계 |
| 젤 디스펜서 | 스테핑 서보 모터·감속기·플런저 직접 가압 | 액추에이터 통합 설계 |
| 이동형 본체 | 프레임·외장 커버, 약 234 kg, 캐스터 수동 이송 | 구조 설계 |

[그림 자리: 전체 사진 + 콜아웃 4개]

## 설계 판단

- 젤 디스펜서는 카트리지 2개 교대 토출, 공기 인입을 막는 조건으로 플런저 직접 가압 선택
- 엔드이펙터는 3D 카메라 작동 거리·시야 기준으로 카메라·프로브·노즐을 배치해 시야 간섭 회피
- 제어기 판금부의 열 배출 에어플로를 설계하고 팬을 선정해 인증 온도 기준 통과

[그림 자리: 젤 디스펜서 단면, 엔드이펙터]

## 결과

- KCTL IEC 60601-1 시험을 거쳐 제조인증(2026.05), 기구 제작 부품 100종

</div>

<div class="lang-en" markdown="1">
<p class="post-description">2025.01 ~ 2025.11 / Jan 2025 – Nov 2025</p>

## System configuration and my design scope

| Component | Specification | Design |
|---|---|---|
| Collaborative robot arm | 3 kg payload (Rainbow Robotics RB3-1200E) | purchased; mounting designed |
| 3D camera | Mech-Mind Mech-Eye NANO | purchased; end-effector placement |
| Ultrasound scanner and probe | purchased | probe holder and bracket designed |
| Gel dispenser | stepping servo motor, reducer, direct-pressure plunger | integrated actuator design |
| Mobile main body | frame and exterior covers, approx. 234 kg, manual casters | structural design |

[figure: overall view with four call-outs]

## Design decisions

- Gel dispenser: two cartridges discharge alternately; direct plunger pressure chosen to keep air from entering
- End effector: camera, probe and nozzle placed from the 3D camera's working distance and field of view to avoid view interference
- Controller sheet-metal enclosure with designed heat-exhaust airflow and fan selection, passing the certification temperature limits

[figure: gel-dispenser section, end effector]

## Result

- Manufacturing certification (May 2026) after IEC 60601-1 testing at KCTL; 100 fabricated mechanical parts

</div>
