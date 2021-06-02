# ERP-Project

전사적 자원 관리(ERP)는 회계, 구매, 리스크 관리 등 일상적인 비즈니스 프로세스를 하나로 묶고 이들 사이의 데이터 흐름을 가능하게 합니다. 오늘날 ERP 시스템은 모든 규모와 모든 산업에서 수많은 비즈니스를 관리하는데 유용하며 꼭 필요한 필수적 요소입니다. 이를 통해 다음과 같은 기대효과를 기대할 수 있습니다.
  1- 시스템 표준화를 통한 데이터 일관성 유지
  2- 영업, 회계 등 조직과 업무가 통합되어 실시간으로 동시에 정보 통합처리 가능
  3- IT 자원 기반 전산시스템 구축은 급변하는 시대에 있어 충분한 유연성과 확장성 보장 받을 수 있으며, 중장기적 관점에서 비용 절약 효과 기대


## Business Process
![캡처0](https://user-images.githubusercontent.com/68997381/120416642-73ca1180-c398-11eb-81a4-b38165f52d3b.PNG)


## ERD 다이어그램
![캡처1](https://user-images.githubusercontent.com/68997381/120416671-7cbae300-c398-11eb-8baf-fe1ab563d8be.PNG)


## 팀원

박승제, 곽은주, 성하빈, 신선애, 신성은, 이종웅, 인진석

## 개발기간 

- 기간: 2021.04.21 - 2021.05.31

## 적용기술

**Front-end**
- HTML5
- CSS3
- JavaScript
- jQuery
- Ajax
- Bootstrap
- Vue.js

**Back-end** 
- Java
- Spring
- Maven 
- Mybatis

**DBMS**
- MySQL

**Collaboration Tool**
- Notion
- Slack
- SVN
- exERD
- ERDcloud

## 구현 기능 및 개인 역할

**박승제**

- 근태 관리 : 근태신청자에 대한 조회, 승인/반려 처리기능
- 계정과목 관리 : 계정과목 조회, 계정과목 수정, 새 계정과목 등록 처리기능
- 미수금 관리 : 미수금 조회 및 입금 처리 기능, 입금 시 회계전표에 해당 미수금 등록 기능

**곽은주** 

- 인사 관리 : 신규사원 등록, 재직자/퇴직자 조회 기능, 사원정보 수정, 퇴직처리 기능
- 승진내역 관리 : 승진내역 조회 가능
- 근태현황 조회 : 근태종류, 결재상태, 신청자 현황 조회
- 급여 관리 : 급여지급이력 조회 기능, 급여지급처리 기능

**성하빈**

- 영업계획 : 신규 영업계획 등록 / 영업계획 조회,검색,작성,상세조회,,수정삭제
- 거래처 관리 : 신규거래처 등록 / 등록한 거래처 조회,검색,작성,상세조회,수정,삭제
- 수주 관리 : 등록된 견적서 수주서 발송 / 조회, 검색, 작성, 상세 조회
- 견적서 작성 및 조회 : 신규 견적서 작성 / 조회, 검색, 작성, 상세 조회

**신선애**

- 공지사항 : 공지사항 등록 기능 / 등록한 공지사항 검색, 수정, 삭제 기능
- 부서관리 : 부서관리 등록 기능 / 등록한 부서명 검색, 수정 기능

**신성은**

- 일별매출현황 : 일별 매출 및 손익통계, 매출목록 조회
- 월별매출현황 : 월별 손익통계 테이블 및 차트 조회
- 년별매출현황 : 집계 기준 별 손익통계 테이블 및 차트 조회

**이종웅**

- 지출결의서 신청 : 지출 사유(대분류, 상세분류)와 금액 사용 일자, 지출금액 등을 입력하여 지출결의서를 신청
- 지출결의서 조회 및 승인 : 신청된 지출결의서의 승인과 반려 처리를 할 수 있음
- 영업실적 조회
  - 임원 : 모든 영업사원 대상으로 일별 판매 목표 수량, 실적 수량 및 달성률을 조회할 수 있음
  - 영업사원 : 영업사원 본인의 일별, 판매 목표 수량, 실적수량을 조회할 수 있음

**인진석**

- 근태 신청 : 신청 내역 조회 기능 / 근태 신청 기능
- 급여 조회 : 월 단위 사용자 별 급여 내역 조회 기능
- 회계전표 조회 : 지출, 수입 내역 조회 기능 / 조회된 지출, 수입의 합계 확인 기능


## 매출 구현
### 일별매출현황
![캡처2](https://user-images.githubusercontent.com/68997381/120417996-c0aee780-c39a-11eb-8dc0-33c00ae6f19f.PNG)


### 월별매출현황
![캡처3](https://user-images.githubusercontent.com/68997381/120418040-d0c6c700-c39a-11eb-8775-d34ab7f25a23.PNG)


### 년도별매출현황
-콤보박스: 직접입력 클릭
![캡처4](https://user-images.githubusercontent.com/68997381/120418075-db815c00-c39a-11eb-8feb-0542ce9e0e5b.PNG)


-콤보박스: 1-4분기 클릭
![캡처5](https://user-images.githubusercontent.com/68997381/120418084-dd4b1f80-c39a-11eb-8d4f-d61c127bda3e.PNG)


콤보박스: 상/하반기 클릭
![캡처6](https://user-images.githubusercontent.com/68997381/120418088-df14e300-c39a-11eb-99a7-c04ccce41f10.PNG)





