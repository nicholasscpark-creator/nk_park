---
layout: page
permalink: /cv/
title: CV
nav: true
nav_order: 1
description: >-
  <span class="lang-ko">경력·학력·교육. 각 프로젝트의 설계 내용은 Projects, 논문·특허는 Publications.</span><span class="lang-en">Experience, education and training. Design details are under Projects; papers and patents under Publications.</span>
toc:
  sidebar: left
---

<!-- CV PDF: assets/pdf/ 에 파일을 넣은 뒤 아래 주석을 풀면 내려받기 버튼이 생김
<p><a class="btn btn-sm z-depth-0" href="{{ '/assets/pdf/cv_nicholas_park.pdf' | relative_url }}" target="_blank" rel="noopener noreferrer">PDF</a></p>
-->

<div class="lang-ko" markdown="1">

## 요약

- 기구설계 9년(2017.05~), (주)메디칼파크 의료기기장비사업팀 차장
- 의료 영상·수술 장비 6종 기구설계, 4종 양산 이관(MammouS 1세대·N·2세대, Disealor)
- IEC 60601-1(의료용 전기기기 안전 국제규격) 공인시험·식약처 제조인증 대응 4건, 등록특허 3건
- 도구: Creo(3D·2D 도면), ANSYS(Modal·Harmonic·정적 구조), Creo Simulation(정적 구조), SolidWorks(석사), AutoCAD

## 경력

### (주)메디칼파크 - 2017.05 ~ 현재

의료 영상·수술 장비 개발·제조, 직원 107명. 주임(2017.05) → 대리(2018.02) → 과장(2021.03) → 차장(2026.03). 소속 MECA팀(2017~2025.11), 의료기기장비사업팀(2025.11~).

#### Disealor (2025.11 ~ 현재)

복강경용 초음파 수술기의 공진 이탈 불량 설계 변경·양산 이관 완료

- 초음파 진동계(티타늄 Blade·알루미늄 Horn)를 Modal·Harmonic 해석해 공진 이탈 원인 규명 및 개선
- 공차 누적으로 접촉하는 구조를 재설계, 관련 사출 금형 4벌 신규 제작
- 도면 공차 기준·작업지도서·품질 검사 기준 개정
- 성과: 개선 제품 대학병원 실사용 검증 100 EA 완료(~2026.08), 블레이드 손상(공진 이탈 증상) 재발 0건 / 공급 중단 없이 양산 이관(2026.09), 350 EA 생산 완료, 1,000 EA 후속 발주

#### XammouS (2024.08 ~ 2025.12)

X-ray·초음파 융합 촬영 장치(국책과제)의 시스템 구성·기구설계·과제 대응

- 6축의 가동 범위·정지 조건을 정하고 축별 부하를 계산해 서보 모터 5축(750 W·400 W·100 W)·압박부 스테핑 서보 모터 1축 용량·감속비 선정
- 본체 액추에이터·수중 동작 스캐너 모듈·축 제한은 MammouS 설계를 공유해 적용
- X-ray 튜브 암 각도 액추에이터 부하 계산으로 리드 스크류 선정, 그 추력으로 튜브 암 각도를 구동하는 메커니즘 설계
- 압박부 구조 재설계 - X-ray 디텍터 통합과 X-ray 투과 경로 간섭 회피
- 외팔보 C-arm 강성 설계, 본체 전방 모멘트 계산으로 전복 안정성 확보
- 액추에이터·지지 구조부 안전율 계산, 안전 관련부 정적 구조 해석
- ±180° 회전 중공축에 X-ray 고압 케이블·초음파·모터 케이블 관통 설계
- 기구부 제작 완료를 기준으로 F/W·H/W 통합 일정 수립, 시제품 동작 검증
- 기구 제작 부품 267종 설계(판금·용접·기계가공·압출)
- 성과: 인증용 2대 제작 / 공인시험기관 KCTL IEC 60601-1 시험을 거쳐 식약처 제조인증(2등급, 2025.11) / 국책과제 「기능 융합형 초음파 영상기기」(2020.09~2025.12, 총 141.9억 원) 인허가 목표 달성·최종평가 종결

#### US-Bot (2025.01 ~ 2025.11)

협동로봇 암(payload 3 kg)·3D 카메라·초음파 진단기 구매품을 이동형 본체와 일체형으로 통합하는 초음파 진단 장치 기구설계

- 초음파 젤 디스펜서 액추에이터 통합 설계 - 고점도 젤 토출 압력 실측과 리드 스크류 토크·감속비 계산으로 스테핑 서보 모터·감속기 1/10 선정
- 플런저 직접 가압 토출 메커니즘 설계 - 카트리지 2개 교대 토출, 음압·기포 차단
- 엔드이펙터 설계 - 3D 카메라 작동 거리·시야 기준으로 카메라·초음파 프로브·젤 노즐 브라켓 배치, 시야 간섭 회피
- 이동형 본체 구조(프레임·외장 커버, 약 234 kg) 설계 - 전복 안정성·운송 포장 시험
- 제어기 판금부 설계, 열 배출 에어플로·팬 선정, 케이블 경로·배치 설계
- 기구 제작 부품 100종 설계, 도면·BOM 작성
- 성과: KCTL IEC 60601-1 시험을 거쳐 식약처 제조인증(2등급, 2026.05)

#### MammouS N·2세대 (2021.11 ~ 2024.07)

유방용 초음파 영상진단장치의 본체 구조·액추에이터·스캐너 모듈 기구설계(압박부·외장 커버는 선임 설계)

- 리프트·회전 축의 가동 범위·정지 조건·동력 상실 시 거동을 정해 기계적·전기기계적 제한 장치와 소프트 축 제한으로 배분
- 그 조건에서 요구 토크를 계산해 서보 모터 750 W·400 W와 웜감속기 1/80(리프트)·중공축 웜감속기 1/40(회전) 선정, 자기잠금으로 동력 상실 시 위치 유지(정전 유지력 시험)
- 리프트 축 메커니즘 설계 - 본체 상·하단 스프로킷에 건 롤러 체인 2줄 견인식 승강 구조, 하단 모터 구동, 자중 보상 가스 스프링 적용
- 회전 축 메커니즘 설계 - 중공 회전 중심(배선 통과)·롤러 체인 오프셋 구동, L-arm 외력 모멘트에서 회전 방향 유격 최소화
- 끼임·충돌 시 모터 출력으로 체인·축·감속기 강도 계산
- 액추에이터·지지 구조부 안전율을 IEC 60601-1 요구 기준(인장 강도)으로 산출, 주조 프레임 정적 해석
- 회전 베이스·L-arm 프레임을 알루미늄 주조(AC4C)로 일체화 - 중량 대비 강성과 부품 통합 / 본체 기둥을 압출(A6063) 구조로 설계 - 배선 통로 확보
- 기구 제작 부품 298종 설계
- 성과: 초도 N 10대·2세대 10대 양산 이관 / KCTL IEC 60601-1 시험을 거쳐 식약처 제조인증(2세대, 2025.06)·기존 인증에 모델 추가(N) / 등록특허 KR102801989B1(스캐닝 모듈, 공동발명)

#### MammouS 1세대 (2017.05 ~ 2021.10)

유방용 초음파 영상진단장치의 수중 동작 스캐너 모듈 기구설계

- 스캐너 모듈 신규 설계 - 메커니즘·전장부가 물속에서 동작, 센서 모듈 이송·방수 구조
- 초음파 센서 모듈 양단 캐터필러 궤도로 압박부 하중(최대 200 N)을 받는 상판 지지 구조 설계
- 스캔 축 액추에이터 통합 설계 - 서보 모터 100 W·웜감속기·타이밍벨트
- 본체·액추에이터 사양 정의, 외주 설계 검토·관리
- 성과: 초도 5대 양산 이관, 스캐너 모듈을 후속 3모델에 개선 적용 / Nemko·SGS IEC 60601-1 시험을 거쳐 식약처 제조인증(2등급, 2019.11)

### 한양대학교 C&R Lab - 2013.03 ~ 2014.12 (석사 과정)

#### 착용로봇 3종

하지 착용로봇 3종(하반신 마비 보행보조 수트·편마비 보행보조 로봇·무릎 재활로봇) 기구설계

- 인체 결합 구조 신규 설계 - 링크·커프 조절부로 인체 관절축과 로봇 관절축 정렬, 대퇴부-외골격 이격량 연구
- 힌지 걸림부로 관절 가동 범위 제한 - 균형을 잡기 어려운 사용자의 넘어짐 방지
- 근력 증강용 관절 구동 모듈·족관절을 하반신 마비용으로 기능 개선 - 보행 패턴 없는 사용자에 맞게 자유도 제한
- 관절 모듈 정지 자세 유지 - 프레임리스 모터(Maxon) 유지 토크와 하모닉 감속기 역구동 저항, 브레이크 없음
- 족관절 메커니즘 - 3자유도 수동 관절로 장비 중량을 지면에 분산, 입각기 충격 완화
- 무릎 재활로봇 신규 설계 - 4절 링크·수직 캠 메커니즘으로 접촉 패드를 구동, 보행 위상에 따라 입각기에만 교정 토크 인가
- 성과: 등록특허 2건 KR101693795B1·KR101641344B1(공동발명) / 한국정밀공학회 2014 춘계 논문 3편(제1저자 1편) / 석사 학위논문 「A Study on Lower-Limb Wearable Robot for Genu Varum Rehabilitation of Knee Osteoarthritis」(한양대학교, 2017.08)

## 학력

- 한양대학교 대학원 메카트로닉스공학과 석사, 2013.03 ~ 2017.08 (지도교수 한창수, C&R Lab)
- 호서대학교 로봇공학과 학사, 2009.03 ~ 2013.02

## 교육

- Ansys Mechanical 동역학, 태성에스엔이, 2026.04 (2일)
- Ansys Mechanical 기본, 태성에스엔이, 2026.04 (3일)
- PyMechanical 기본, 태성에스엔이, 2026.09 (1일)

</div>

<div class="lang-en" markdown="1">

## Summary

- Mechanical design engineer, 9 years (since May 2017); Deputy General Manager, Medical Device Equipment Business Team, MedicalPark Co., Ltd.
- Mechanical design of six medical imaging and surgical devices; four transferred to production (MammouS Gen 1, MammouS N, MammouS 2, Disealor)
- Four devices through IEC 60601-1 (medical electrical equipment safety) third-party testing and MFDS (Korea) manufacturing certification; three registered patents
- Tools: Creo (3D and 2D drawings), ANSYS (modal, harmonic, static structural), Creo Simulation (static structural), SolidWorks (graduate work), AutoCAD

## Experience

### MedicalPark Co., Ltd. - May 2017 to present

Developer and manufacturer of medical imaging and surgical devices, 107 employees. Associate (2017) → Assistant Manager (2018) → Manager (2021) → Deputy General Manager (2026). MECA Team (2017–Nov 2025), Medical Device Equipment Business Team (Nov 2025–).

#### Disealor (Nov 2025 – present)

Design change and production transfer that resolved a resonance-detuning failure of a laparoscopic ultrasonic scalpel

- Identified and corrected the cause of resonance detuning by modal and harmonic analysis of the ultrasonic vibrating system (titanium blade, aluminium horn)
- Redesigned the structure whose tolerance stack-up caused contact; four new injection molds
- Revised drawing tolerance criteria, work instructions and quality inspection criteria
- Result: 100 improved units completed clinical use at university hospitals (through Aug 2026) with zero recurrence of blade damage (the symptom of detuning); transferred to production without supply interruption (Sep 2026), 350 units produced, 1,000-unit follow-on order

#### XammouS (Aug 2024 – Dec 2025)

System configuration, mechanical design and program reporting for a fused X-ray and ultrasound breast imaging system (government-funded program)

- Defined travel and stop conditions for six axes, calculated per-axis loads and sized five servo axes (750 W, 400 W, 100 W) plus a stepping-servo compression axis, including reduction ratios
- Reused the MammouS main-body actuators, underwater scanner module and axis-limiting design
- Sized a lead screw from the X-ray tube-arm tilt load and designed the thrust mechanism that drives the tube-arm angle
- Redesigned the compression unit to integrate the X-ray detector and clear the X-ray transmission path
- Designed the cantilever C-arm for stiffness; secured tip-over stability from the main-body forward-moment calculation
- Calculated safety factors of actuators and supporting structures; static FEA of safety-related parts
- Routed X-ray high-voltage, ultrasound and motor cables through a ±180° hollow rotating shaft
- Set the F/W and H/W integration schedule from mechanical completion; verified prototype operation
- Designed 267 fabricated mechanical parts (sheet metal, welding, machining, extrusion)
- Result: two certification units built / MFDS manufacturing certification (Class 2, Nov 2025) after IEC 60601-1 testing at KCTL / government program "Function-fused Ultrasound Imaging Device" (Sep 2020 – Dec 2025, KRW 14.19 billion) met its approval goal and closed with final evaluation

#### US-Bot (Jan 2025 – Nov 2025)

Mechanical design of an ultrasound scanning station integrating a purchased collaborative robot arm (3 kg payload), 3D camera and ultrasound scanner into a mobile main body

- Integrated actuator design of the ultrasound-gel dispenser: measured high-viscosity gel discharge pressure, calculated lead-screw torque and reduction ratio, selected a stepping servo motor with a 1/10 reducer
- Designed a direct-pressure plunger discharge mechanism: two cartridges alternating, negative pressure and air entrainment blocked
- Designed the end effector: placed the camera, ultrasound probe and gel-nozzle bracket from the 3D camera's working distance and field of view, avoiding view interference
- Designed the mobile main-body structure (frame and exterior covers, approx. 234 kg): tip-over stability and transport packaging tests
- Designed the controller sheet-metal enclosure, heat-exhaust airflow and fan selection, cable routing and layout
- Designed 100 fabricated mechanical parts; drawings and BOM
- Result: MFDS manufacturing certification (Class 2, May 2026) after IEC 60601-1 testing at KCTL

#### MammouS N and MammouS 2 (Nov 2021 – Jul 2024)

Mechanical design of the main structure, actuators and scanner module of an automated breast ultrasound system (compression unit and exterior covers designed by a senior engineer)

- Defined travel, stop conditions and power-loss behavior of the lift and rotation axes and allocated them to mechanical and electro-mechanical limiting devices and soft axis limits
- Calculated required torque under those conditions and selected 750 W and 400 W servo motors with a 1/80 worm reducer (lift) and a 1/40 hollow-shaft worm reducer (rotation); self-locking holds position on power loss (verified by power-off holding test)
- Lift-axis mechanism: two roller chains run over upper and lower sprockets in the main body and pull the carriage, driven by a motor at the base, with gas-spring gravity compensation
- Rotation-axis mechanism: hollow rotation center for cable pass-through, offset roller-chain drive, minimal rotational backlash under L-arm external moment
- Strength calculation of chains, shafts and reducers from motor output under pinch and collision conditions
- Safety factors of actuators and supporting structures per IEC 60601-1 tensile-strength requirements; static FEA of the cast frame
- Rotation base and L-arm frame integrated as aluminium castings (AC4C) for stiffness-to-weight and part consolidation; main-body column as an aluminium extrusion (A6063) providing the cable channel
- Designed 298 fabricated mechanical parts
- Result: first production lots of 10 MammouS N and 10 MammouS 2 transferred to production / MFDS manufacturing certification (MammouS 2, Jun 2025) and model addition to the existing certificate (N) after IEC 60601-1 testing at KCTL / registered patent KR102801989B1 (scanning module, co-inventor)

#### MammouS Gen 1 (May 2017 – Oct 2021)

Mechanical design of the underwater scanner module of an automated breast ultrasound system

- New scanner module: mechanism and electronics operate submerged in water; sensor-module transport and waterproof structure
- Top-plate support structure: caterpillar tracks on both ends of the ultrasound sensor module carry the compression load (up to 200 N)
- Integrated scan-axis actuator: 100 W servo motor, worm reducer, timing belt
- Defined main-body and actuator specifications; reviewed and managed outsourced design
- Result: first lot of five units transferred to production; scanner module carried into three successor models with improvements / MFDS manufacturing certification (Class 2, Nov 2019) after IEC 60601-1 testing at Nemko and SGS

### Hanyang University C&R Lab - Mar 2013 to Dec 2014 (master's program)

#### Three lower-limb wearable robots

Mechanical design of three lower-limb wearable robots (paraplegic walking-assist suit, hemiplegic walking-assist robot, knee rehabilitation robot)

- New human-attachment structure: link and cuff adjustment aligning human and robot joint axes; study of thigh-to-exoskeleton clearance
- Joint range of motion limited by hinge stops to prevent falls for users who cannot balance by themselves
- Adapted power-assist joint modules and ankle joints for paraplegic use: degrees of freedom restricted for users without a gait pattern
- Joint module holds a stopped posture by frameless-motor (Maxon) holding torque and harmonic-drive back-drive resistance, without a brake
- Ankle mechanism: a 3-DOF passive joint distributes device weight to the ground and cushions stance-phase impact
- New knee rehabilitation robot: four-bar linkage and vertical cam drive the contact pads, applying corrective torque only during stance phase according to gait phase
- Result: two registered patents, KR101693795B1 and KR101641344B1 (co-inventor) / three papers at the KSPE 2014 Spring Conference (one as first author) / M.S. thesis "A Study on Lower-Limb Wearable Robot for Genu Varum Rehabilitation of Knee Osteoarthritis" (Hanyang University, Aug 2017)

## Education

- M.S., Mechatronics Engineering, Hanyang University, Mar 2013 – Aug 2017 (advisor Prof. Changsoo Han, C&R Lab)
- B.S., Robotics Engineering, Hoseo University, Mar 2009 – Feb 2013

## Training

- Ansys Mechanical Dynamics, TSNE, Apr 2026 (2 days)
- Ansys Mechanical Basics, TSNE, Apr 2026 (3 days)
- PyMechanical Basics, TSNE, Sep 2026 (1 day)

</div>
