# CyberFishTank
2025 산학프로젝트 

feat: 새로운 기능 추가
fix: 버그 수정
docs: 문서 수정 (README.md 등)
style: 코드 포맷 변경, 세미콜론 누락 등 (코드 로직 변경 없음)
refactor: 코드 리팩토링
test: 테스트 코드 추가 또는 수정
chore: 빌드 스크립트 수정, 패키지 매니저 설정 등 기타 변경사항


## 1. 프로젝트 개요

- 주제: 디지털 트윈 기반 스마트 어항
- 목표:
  - 물고기 1마리 기준 객체 탐지 및 추적
  - 비전 기반 이상 행동 감지 및 섭식/활동량 기반 건강 지표화
  - 수질 센서 + 시계열 모델(LSTM 등)을 통한 수질 이상 예측
  - 디지털 트윈(3D 어항) 상에서 실시간 상태 시각화
## 3. 폴더 구조

```bash
.
├── hardware/        # 센서, ESP32 코드, 회로도
├── edge_vision/     # YOLO, 추적, 이상행동 분석
├── backend/         # FastAPI, DB, Health Index 계산
├── digital_twin/    # Unity 또는 웹 3D
├── dashboard/       # 대시보드(UI)
└── docs/            # 설계, 발표자료, 아키텍처 문서
