# LooseGoose 🚀

- 행동 데이터를 기반으로 사용자의 상태를 해석하고 상태를 실제로 변화시키는 Decision Engine을 구축한다  
- A behavior-driven decision engine that interprets user state and drives state transitions through optimal interventions

---

## 🔥 What I build

단순 CRUD가 아니라 사용자의 행동 데이터를 기반으로 상태공간(State Space)을 구성하고  
상태의 변화 방향을 분석하여 개입하는 시스템을 만든다.

- goosage-api → 상태 판단 및 전이 엔진 (Prediction / NextAction)
- goosage-recovery → 중독 행동 상태 전이 및 회복 엔진
- goosage-scripts → 행동 시뮬레이션 및 실험 자동화
- video-behavior-lab → 영상 기반 행동 패턴 분석

---

## 🧠 How it works

GooSage는 다음 흐름으로 동작한다.

행동(Event) → 상태벡터(State Vector) → 패턴(Pattern) → 개입(NextAction) → 상태변화(Transition)

- 이벤트는 행동 로그로 누적
- 상태를 벡터 형태로 압축
- 벡터 기반 패턴 해석
- NextAction을 통해 상태 이동 유도
- 행동 이후 상태 변화(Δstate) 추적

---

## 🎯 Goal

- 행동 데이터를 기반으로 상태공간을 구성하고 패턴을 해석  
- 위험 상태를 조기에 감지하고 붕괴를 방지  
- 최소 행동 개입을 통해 상태를 개선  
- 학습, 중독, 소비, 운동 등 다양한 도메인의 공통 패턴을 추출  

👉 인간 행동의 상태전이(State Transition)를 이해하고, 그 흐름을 제어하는 
인간보다 더 인간다운 LooseGoose 엔진을 구축한다

---

## ⚙️ Tech

- Java / Spring Boot
- MySQL / Docker
- Event-driven + Vector-based State Transition Engine
