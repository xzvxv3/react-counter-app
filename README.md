# Simple Counter App (State Lifting Practice)

React의 핵심 개념인 `State Lifting(상태 끌어올리기)`과 `단방향 데이터 흐름`을 학습하기 위해 제작한 간단한 카운터 앱

## 🛠 주요 학습 포인트
- **State Lifting**: 서로 형제 관계인 `Viewer`와 `Controller`가 데이터를 공유할 수 있도록 공통 부모인 `App`으로 상태를 이동시켜 관리
- **Props Handling**: 부모 컴포넌트에서 자식 컴포넌트로 데이터와 함수를 전달하는 방식
- **Re-rendering**: 부모의 상태가 변경될 때 자식 컴포넌트들이 어떻게 반응하고 업데이트되는지 실습

## 🏗 프로젝트 구조
- `App.jsx`: 메인 상태(`count`) 관리 및 함수 정의
- `Viewer.jsx`: 전달받은 상태값을 화면에 출력
- `Controller.jsx`: 사용자 입력을 받아 상태 변경 함수 호출

## 

<img width="680" height="691" alt="스크린샷 2026-02-18 오후 9 36 59" src="https://github.com/user-attachments/assets/c0ac60de-e844-41f1-87a5-193bf0cf7c81" />
