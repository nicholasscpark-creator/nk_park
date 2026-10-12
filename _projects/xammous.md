---
layout: page
title: XammouS
description: >-
  <span class="lang-ko">부하 계산으로 선정한 6축 액추에이터, 수중 스캐너 모듈, 주조·압출 구조재</span><span class="lang-en">Six load-sized actuator axes, an underwater scanner module, cast and extruded structures</span>
img: # assets/img/xammous.jpg 를 넣은 뒤 경로를 적으면 카드 썸네일로 표시됨
importance: 2
category: work
---

{% raw %}<!-- 그림 넣는 법: assets/img/ 에 파일을 두고 아래 형식으로 삽입
<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/xammous_1.png" title="" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
-->{% endraw %}

<div class="lang-ko" markdown="1">
<p class="post-description">2024.08 ~ 2025.12 / Aug 2024 – Dec 2025</p>

## 6축 액추에이터 - 가동 범위 정의에서 선정까지

| 축 | 모터 | 감속 | 전달 메커니즘 |
|---|---|---|---|
| C-arm 승강 | 서보 750 W | 웜 감속기 | 롤러 체인 2줄 견인, 가스 스프링 자중 보상 |
| C-arm 회전 ±180° | 서보 400 W | 중공축 웜 감속기 | 롤러 체인 오프셋 구동 |
| X-ray 튜브 암 각도 | 서보 400 W | 유성 감속기 | 리드 스크류 추력 |
| 디텍터 이동 | 서보 400 W | - | 타이밍 벨트 + 스크류 |
| 스캐너 센서 이송 | 서보 100 W | 웜 감속기 | 타이밍 벨트 |
| 압박부 승강 | 스테핑 서보 | 웜 휠 | 리드 스크류 |

[그림 자리: 정면도 + 축 콜아웃 6개]

## 케이블 경로와 구조

- ±180° 회전 중공축에 X-ray 고압·초음파·모터 케이블을 관통 - 회전 중심을 비워야 하므로 체인 오프셋 구동 선택
- 외팔보 C-arm 강성과 본체 전방 모멘트 계산으로 전복 안정성 확보
- 회전 베이스·암 프레임은 알루미늄 주조(AC4C), 본체 기둥은 압출(A6063) - MammouS 구조 공유

[그림 자리: 중공축 단면, 주조·압출 구조재]

## 결과

- 인증용 2대 제작, KCTL IEC 60601-1 시험을 거쳐 제조인증(2025.11), 기구 제작 부품 267종

</div>

<div class="lang-en" markdown="1">
<p class="post-description">2024.08 ~ 2025.12 / Aug 2024 – Dec 2025</p>

## Six actuator axes, from travel definition to sizing

| Axis | Motor | Reduction | Transmission |
|---|---|---|---|
| C-arm lift | 750 W servo | worm reducer | two roller chains, gas-spring gravity compensation |
| C-arm rotation ±180° | 400 W servo | hollow-shaft worm reducer | offset roller-chain drive |
| X-ray tube-arm tilt | 400 W servo | planetary reducer | lead-screw thrust |
| Detector shift | 400 W servo | - | timing belt + screw |
| Scanner sensor transport | 100 W servo | worm reducer | timing belt |
| Compression lift | stepping servo | worm wheel | lead screw |

[figure: front view with six axis call-outs]

## Cable routing and structure

- X-ray high-voltage, ultrasound and motor cables pass through the ±180° hollow rotating shaft; keeping the center open is why the rotation uses an offset chain drive
- Cantilever C-arm designed for stiffness; tip-over stability from the main-body forward-moment calculation
- Rotation base and arm frame as aluminium castings (AC4C), main-body column as an extrusion (A6063), shared with the MammouS structure

[figure: hollow-shaft section, cast and extruded parts]

## Result

- Two certification units built; manufacturing certification (Nov 2025) after IEC 60601-1 testing at KCTL; 267 fabricated mechanical parts

</div>
