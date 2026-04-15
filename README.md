# LooseGoose 🚀

행동 데이터를 기반으로 상태를 해석하고  
상태 전이를 설계하여 실제 변화를 유도하는 Decision Engine을 구축한다

A behavior-driven decision engine that interprets user state  
and actively drives state transitions through optimal interventions

---

## 🔥 What I build

단순 CRUD가 아니라  
행동 데이터를 상태공간(State Space)으로 변환하고  
상태 간 이동(Transition)을 설계하는 시스템을 만든다

- goosage-api → 상태 판단 및 전이 엔진 (Prediction / NextAction)
- goosage-recovery → 중독 행동 회복 및 relapse 제어 엔진
- goosage-spendcontrol → 소비 충동 제어 및 행동 교정 엔진
- goosage-scripts → 행동 시뮬레이션 및 검증 자동화
- goosage-brain → 공통 상태벡터 및 패턴 스코어링 엔진 (Core)

---

## 🧠 Core Architecture

LooseGoose는 다음 상태 전이 흐름으로 동작한다.

Event → State Vector → Pattern → Decision → NextAction → State Transition

- 행동(Event)을 데이터로 축적
- 상태를 벡터(State Vector)로 압축
- 패턴(Pattern)으로 상태 해석
- Decision Engine이 개입 전략 결정
- NextAction을 통해 상태 이동 유도
- ΔState를 기반으로 시스템이 학습

---

## 🧩 System Design Philosophy

- Rule-based + Vector-based Hybrid Engine
- 이벤트 기반 → 상태공간 기반 전환
- 도메인별 엔진 → 공통 상태축으로 통합
- 최소 개입으로 최대 상태 변화 유도
- 행동 데이터 → 상태 해석 → 개입 → 피드백 루프

---

## 🎯 Goal

- 행동 데이터를 상태공간으로 구조화
- 패턴을 통해 상태를 해석하고 예측
- 위험 상태를 조기에 감지하고 붕괴 방지
- 최소 행동 개입으로 상태를 개선
- 학습 / 중독 / 소비 / 운동 등 다양한 도메인의 공통 패턴 추출

👉 인간 행동의 상태전이(State Transition)를 이해하고  
그 흐름을 설계·제어하는 LooseGoose 엔진 구축

---

## ⚙️ Tech

- Java / Spring Boot
- MySQL / Docker
- Event-driven Architecture
- Vector-based State Modeling
- Simulation & Verification Pipeline
