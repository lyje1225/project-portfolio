# 이윤제 포트폴리오

## 1. SAP KDT 심화 2기 - RAP 개인 프로젝트

| 구분    | 내용                                                              |
| ----- | --------------------------------------------------------------- |
| 개발기간  | 2026.07 ~ 2026.09                                               |
| 프로젝트명 | S-Mobile 구매 프로세스 구축 프로젝트 (자재·공급업체·PIR·구매오더·FI계정·회계결정)             |
| 개발환경  | SAP BTP ABAP Environment, RAP(Managed, V2/V4 OData), CDS View, Fiori Elements |
| 개발인원  | 개인 프로젝트                                                         |
| 담당역할  | 6개 프로그램 설계 및 구현 - DB Table / CDS View / RAP Behavior / Fiori Elements 화면 |

### 담당 기능

* 자재관리(Material Master) 프로그램 개발 - 자재유형별 기준정보 및 다국어 자재명 관리
* 공급업체관리(Vendor Master) 프로그램 개발 - 벤더분류·매입채무 조정계정 관리
* 구매정보레코드관리(Purchasing Info Record) 프로그램 개발 - 공급업체별 구매조건 사전관리
* 구매오더관리(Purchase Order) 프로그램 개발 - PIR 연계 발주 생성 및 삭제 상태 관리
* FI 계정관리(Account Master) 프로그램 개발 - 계정유형별 G/L 계정 마스터 관리
* 회계계정결정관리(Account Determination) 프로그램 개발 - 이동유형·거래키 기준 계정결정 규칙 관리
* 전 프로그램 공통 다국어(EN ↔ KO) 처리 적용

### 주요 구현 내용

* 6개 프로그램 전체에 동일한 설계 원칙을 통일성 있게 적용 (CDS 기반 Draft/비Draft 시나리오 구현)
* Text 테이블(SPRAS) + $session.system_language 기반 자재명·계정명 다국어 자동 조회
* 삭제 지시자(Lvorm/Loevm/Loekz) 체크 시 나머지 입력 가능 필드를 모두 Read-only 처리
* LINK를 활용해 상위 엔티티의 삭제·비활성 상태를 하위 엔티티까지 실시간 전파 (Feature Control)
* Number Range·Early Numbering을 활용한 자동 채번 (자재·공급업체·PIR·계정·구매오더)
* Side Effects로 저장 없이 즉시 필드 상태를 재평가하는 사용자 경험 구현
* Fiori Elements Value Help(F4 CDS) 연계로 플랜트·저장위치·자재유형 등 입력 편의성 확보
* PIR → PO 등 프로그램 간 참조 연계 로직 및 필수값·참조무결성 검증 로직 구현

---

## 2. SAP CODE 아카데미 ERP 프로젝트

| 구분    | 내용                                                            |
| ----- | ------------------------------------------------------------- |
| 개발기간  | 2026.05 ~ 2026.07                                             |
| 프로젝트명 | F&B 유통 ERP 구축 프로젝트                                            |
| 개발환경  | SAP GUI, ABAP, CDS View, Gateway/OData, Fiori/UI5, JavaScript |
| 개발인원  | 팀 프로젝트                                                        |
| 담당역할  | MM 모듈 ABAP 개발, SD 영역 Fiori/UI5 화면 개발                          |

### 담당 기능

* 포장재 자동발주 프로그램 개발
* 구매오더 프로그램 개발
* 통합 결재 프로그램 개발
* 자재 유통기한 조회 및 폐기 프로그램 개발
* 입고 프로그램 개발
* 배송 관리 프로그램 개발
* 모바일 배송기사 앱 개발
* 고객 주문 프로그램 개발

### 주요 구현 내용

* 구매오더 생성 및 후속 입고 프로세스 연계
* 구매오더, 생산오더, 재고이전오더 유형별 입고 처리
* 배치번호, 입고 이력, 재고 상태, 오더 상태 반영
* CDS View 생성 및 데이터 조회 연계
* Gateway/OData 기반 Fiori/UI5 화면 연동
* 배송 상태 조회, 품목별 인계, 전체 배송 완료 처리 화면 구현

---

## 3. Calogram - 영양분석 식단관리 애플리케이션

| 구분    | 내용                                                |
| ----- | ------------------------------------------------- |
| 개발기간  | 2022.03 ~ 2022.05                                 |
| 프로젝트명 | 칼로그램                                              |
| 개발환경  | Android Studio, Java, Firebase, OpenCV, Tesseract |
| 개발인원  | 4명                                                |
| 담당역할  | 운동 화면 및 칼로리 계산 기능 개발                              |

### 담당 기능

* 운동 화면 개발
* 남은 칼로리 및 태운 칼로리 출력
* METS 공식을 활용한 운동 칼로리 자동 계산 기능 구현
* 섭취 칼로리와 운동 칼로리를 비교할 수 있는 그래프 개발

---

## 4. Budget Management Work(BMW)

| 구분    | 내용                                                  |
| ----- | --------------------------------------------------- |
| 개발기간  | 2021.03.09 ~ 2021.07.01                             |
| 프로젝트명 | Budget Management Work                              |
| 개발환경  | Android Studio, Java, SQLite, Jira Software, GitHub |
| 개발인원  | 4명                                                  |
| 담당역할  | 로그인/회원가입 및 데이터베이스 관리                                |

### 담당 기능

* 로그인 기능 구현
* 회원가입 기능 구현
* SQLite를 활용한 사용자 데이터 관리

---

## 5. 다이어리 프로젝트

| 구분    | 내용                    |
| ----- | --------------------- |
| 개발기간  | 2021.03 ~ 2021.06     |
| 프로젝트명 | 다이어리 프로젝트             |
| 개발환경  | Eclipse, Java, GitHub |
| 개발인원  | 3명                    |
| 담당역할  | 로그인 및 검색/수정 기능 개발     |

### 담당 기능

* 로그인 화면 구현
* 회원가입 기능 구현
* 암호변경 기능 구현
* 검색 및 수정 기능 일부 구현

---

## 6. 부루마블 게임

| 구분    | 내용                |
| ----- | ----------------- |
| 개발기간  | 2020.03 ~ 2020.06 |
| 프로젝트명 | 부루마블 게임           |
| 개발환경  | Visual Studio, C  |
| 개발인원  | 4명                |
| 담당역할  | 게임 진행 관련 기능 개발    |

### 담당 기능

* 플레이어 이름 설정
* 현재 턴 표시
* 주사위 굴리기 기능
* 플레이어 차례 표시
* 주사위 진행 결과에 따른 시나리오 출력

---

## 사용 기술 요약

### SAP

* ABAP
* RAP (Managed, V2/V4 OData)
* CDS View
* Gateway/OData
* Fiori/UI5, Fiori Elements

### Web/App

* Java
* JavaScript
* SQL
* Android Studio
* Firebase
* SQLite

### Tool

* SAP GUI
* SAP BTP ABAP Environment
* VS Code
* Eclipse
* Visual Studio
* GitHub
