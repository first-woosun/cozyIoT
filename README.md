# 📱 CozyIot
**<국립한국교통대학교/컴퓨터공학과> 2025학년도 Team_Automatics 졸업작품**

**한 줄 소개: 식물 생장 최적화 스마트 창문 시스템**

## 📝 프로젝트 개요

**CozyIoT**는 바쁜 현대인들이 실내 식물을 보다 쉽게 키울 수 있도록 돕는 **IoT 기반 스마트 홈 가드닝 솔루션**입니다. 센서 데이터와 외부 기상 API를 결합한 지능형 자동 제어 시스템을 통해 식물 생장에 최적화된 환경을 유지하는 것을 목표로 합니다. 

- **진행 기간:** 2025.03 ~ 2025.11 (최종 보고 기준)

- **핵심 가치: 자동화**
    - 환경 변수(온습도, 공기질, 조도, 강우)에 따른 창문 자동 개폐

- **접근성:** 저비용·범용 부품을 활용한 누구나 설치 가능한 모듈형 제작

- **정밀도:** 센서 측정값과 공공 기상 데이터(OpenWeatherMap)의 가중치 연산을 통한 정밀 제어

## ✨ 주요 기능 (Key Features)

### 🤖 지능형 자동 제어
- **식물 맞춤 프리셋:** 선인장, 다육이 등 식물 종류에 맞는 최적 환경 프리셋 제공

- **환경 대응:** 실내 온습도 상승, 공기질 저하, 강우 감지 시 즉각적인 알림 및 창문 제어

- **데이터 동기화:** 모든 설정 및 센서값을 JSON 형태로 관리하여 앱과 장치 간 실시간 동기화 구현

### 📱 사용자 중심 모바일 어플리케이션
- **위치 기반 날씨:** 사용자 위치 설정을 통해 지역별 기상 데이터 획득

- **실시간 알람:** 가스 누출(MQ-135)이나 갑작스러운 우천 시 푸시 알림 발송

- **Wi-Fi 간편 설정:** 장치 버튼 조작을 통해 사용자 네트워크 정보를 손쉽게 변경/저장

## 🖼 스크린샷 및 데모 (Screenshots & Demo)

### 어플 화면

![로그인 페이지](https://drive.google.com/uc?=view&id=17jsQhAZaS3RQ9xXfH8IkCLw1y7J8E4c2)

## 🛠 기술 스택 (Tech Stack)

### Development

- Language: Java
- IDE: Android Studio
- Min SDK: 30 / Target SDK: 35

### Core Libraries & APIs
- IoT / Messaging: Eclipse Paho MQTT (mqttv3, android.service) - MQTT 프로토콜 기반 통신
- Location & Maps: Google Maps SDK, Google Play Services Location - 지도 표시 및 장치 위치 입력
- Data Parsing: Gson - JSON 데이터 직렬화 및 역직렬화
- Component Communication: LocalBroadcastManager - 앱 내 컴포넌트 간 로컬 브로드캐스트 통신

## ⚙️ 설치 및 실행 방법 (Getting Started)
프로젝트를 로컬에서 실행하기 위한 방법입니다.
#### 1. 저장소 클론

git clone [https://github.com/First-woosun/cozyIoT](https://github.com/First-woosun/cozyIoT)<사용자이름>/<저장소이름>.git

#### 2. Android Studio에서 실행
- Android Studio에서 프로젝트 폴더를 엽니다.
- Gradle Sync가 완료될 때까지 기다립니다.
- 에뮬레이터 또는 실제 기기를 연결하고 Run (Shift + F10) 버튼을 누릅니다.

## 👨‍💻 팀원 및 역할 (Team Members)
|이름|학번|역할|GitHub|
|---|---|---|---|
|유우선|2026098|팀장, 기획, 안드로이드 app 구현 (UI, 서버 통신)|@first-woosun|
|김정민|2026088|HW 설계, HW 제작, 서버 통신 구현|@sigjm|
|김현성|2026019|서버 개발, 데이터베이스 설계, 서버 통신 구현|@unluckid|
|김태겸|2026017|안드로이드 로직, API 연동, 서버 통신 구현|@taeden211|
