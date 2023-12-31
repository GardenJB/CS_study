# CS_컴퓨터시스템구조_01

## Computer System Architecture

## 디지털 논리회로

### 디지털 컴퓨터
 : 이진 시스템을 사용하여 계산 수행 디지털 시스템
 : 비트 그룹 사용 숫자, 문자 및 기타 정보 표시 또는 처리

 * 컴퓨터 하드웨어
  - cpu : 중앙처리장치, 컴퓨터 그 자체 > 산술 논리 처리, 데이터 저장, 제어 기능 수행
  - 주변장치 : 메모리, 저장 장치, 입출력 장치

 * 컴퓨터 소프트웨어
  - 운영체제
  - 시스템프로그램 : OS에 포함 또는 연결 시스템 운영을 보조
  - 응용프로그램

### 논리 게이트
 - 0 / 1
 : 진리표로 동작 정의

### 부울 대수
 - 이진 변수와 논리 동작 취급 대수
 - AND, OR, NOT
 : 변수 사이의 진리표 관계를 대수적으로 표시
   논리도의 입출력 관계 대수적 표시
   같은 기능을 가진 더 간단한 회로 발견

### 맵의 간소화

### 조합 회로
: 입력과 출력을 가진 논리 게이트의 집합
  입력의 0,1 조합에 의해 결정되는 함수의 결과로 출력 값 표시
  n개의 입력 조합 > 2^n가지

* 조합 회로의 설계 절차
 1. 해결할 문제 제시
 2. 입력과 출력 변수에 문자 기호 부여
 3. 입력-출력 관계 정의 진리표 도출
 4. 각 출력에 대한 간소화된 부울 함수 도출
 5. 부울 함수에 대한 논리도 작성
 6. 논리도 바탕 회로 구현

 * 반가산기 Half adder
  : 2개의 비트값을 산술적으로 가산
 * 전가산기 Full adder
  : 캐리값을 포함하여 3 비트 가산

### 플립플롭
 : 1 비트 디지털 정보 저장하는 이진 셀 (디지털 메모리)
   동기식 순차회로의 기본적인 요소로 사용, 조합회로와 함께 순차회로를 구성
   입력의 상태가 변화하기 전까지 이전의 출력 상태를 그대로 유지

  * SR-플립플롭
  * D-플립플롭
  * JK-플립플롭
  * T-플립플롭

* 모서리-변이형 플립플롭
  * 상향 모서리 플립플록
  * 하향 모서리 플립플록

### 순차회로
 : 플립플롭과 게이트/조합회로 를 서로 연결한 회로
   클럭펄스에 의하여 동기화된 입력 순차에 의하여 제어


