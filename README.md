# GooSage Nexus 🚀

행동 데이터 기반 Decision Engine 플랫폼  
A behavior-driven decision engine that analyzes user activity and recommends next actions.

---

## 🔥 What I build

단순 CRUD가 아니라  
사용자의 행동 데이터를 기반으로 상태를 해석하고  
다음 행동을 추천하는 시스템을 만든다.

- goosage-api → 상태 판단 엔진 (Prediction / NextAction)
- goosage-scripts → 행동 시뮬레이션 및 실험 자동화
- video-behavior-lab → 영상 기반 행동 분석

---

## 🧠 How it works

GooSage는 다음 흐름으로 동작한다.

행동(Event) → 상태(Snapshot) → 판단(Prediction) → 행동 추천(NextAction)

- 이벤트는 study_events에 누적
- Snapshot으로 현재 상태 압축
- Rule 기반으로 위험도 판단
- 최소 행동(NextAction) 추천

---

## 🎯 Goal

- 사용자의 행동 데이터를 기반으로 현재 상태를 판단하고,  
위험 패턴을 조기에 감지하는 Decision Engine 구축  

- 이를 통해 금연·금주·도박 등 중독성 행동을 예방하고,  
사용자가 지속 가능한 행동을 선택할 수 있도록  
부담이 적고 효과적인 다음 행동을 제안하는 시스템 구현

---

## ⚙️ Tech

- Java / Spring Boot
- MySQL / Docker
- Event-driven + Rule-based Decision Engine
