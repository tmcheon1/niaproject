# 멀티 모달 영상 AI 데이터
* 100시간 분량의 멀티 모달 영상 데이터셋 구축
* AI 8종 임무유형을 고려한 의미정보 부착
* 감정, 성별, 연령대, 발화 스크립트, 개체 및 관계 정보, 상황 설명 정보, 발화별 대화 의도 및 대화 전략 정보

## Announcements
### 멀티 모달 영상 AI 데이터 셋 1차 공개
* 25시간 분량의 멀티 모달 영상 데이터셋 1차 공개
* 약 1200개 영상 클립
* AI 8종 임무유형을 고려한 의미정보 부착

## Download the Data
* AI 멀티모달 영상 데이터는 http://www.aihub.or.kr/ 에서 다운로드 가능합니다.

## Data Organization
* 데이터의 구조는 감정, 성별, 연령대, 발화 스크립트, 개체 및 관계 정보, 상황 설명 정보, 발화별 대화의도 및 대화전략 정보를 포함
* 각 구조 정보는 아래 그림 및 표와 같이 구성

<p align='center'>Figure 1: 데이터 구조도.</p>

![image](https://github.com/tmcheon1/niaproject/blob/master/데이터%20구조도.jpg)

 
<p align='center'>Figure 2: 데이터 항목 및 설명.</p>
 
![image](https://github.com/tmcheon1/niaproject/blob/master/데이터%20항목%20및%20설명.jpg)

 
 
<p align='center'>Figure 3: 데이터 구조.</p>

![image](https://github.com/tmcheon1/niaproject/blob/master/데이터%20구조.jpg)


## Dataset Statistics

### 1차 데이터셋 구축 정보
* 구축 데이터 총 러닝 타임 : 약 25시간
* 동영상 클립 수 : 1273개
* 대화 문장 수 : 16,048개

### 8종 감성 정보
* 텍스트, 이미지, 사운드, 멀티모달 별 8종 감성 분포

<p align='center'>Figure 4: 텍스트, 이미지, 사운드, 멀티모달 별 감성분석 분포 및 비중.</p>

![image](https://github.com/tmcheon1/niaproject/blob/master/감성분석%20분야별%20결과.jpg)


### 발화 의도 정보 (단위 : 문장)
* 명령/요청 : 831
* 약속 : 67
* 응대/답변 : 4,678
* 인사/부르기/환기 : 284
* 진술/주장 : 4,391
* 질문 : 4,612
* 표출 : 1,017
* 기타 : 168

### 대화 전략 정보 (단위 : 문장)
* 공감대화 (Reference to shared experience) : 3,773
* 비언어적대화 (Back channel) : 56
* 비윤리적대화 (Violation of social norms) : 517
* 완곡대화 (Indirectness) : 604
* 자기대화 (Self disclosure) : 6,208
* 질문대화 (Qustions to elicit self-disclosure) : 4,679
* 칭찬대화 (Praise) : 211

### 객체 정보
* 객체 종류 및 객체 별 노출 프레임 수

<p align='center'>Figure 5: 공개된 객체 종류 및 객체 별 노출 프레임 수.</p>

![image](https://github.com/tmcheon1/niaproject/blob/master/개체정보.jpg)


### 행동 관계 (단위 : 프레임)
* 잡다 : 587,765
* 먹다 / 마시다 : 14,505
* 따라가다 : 511
* 때리다 : 186
* 기대다 : 134,263
* 눕다 : 2,449
* 들다 : 244,557
* 밀다 / 당기다 : 2,398
* 앉다 : 4,093,374
* 사용하다 / 착용하다 : 203,136


### 위치 관계 (단위 : 프레임)
* ~앞에 있다 / ~뒤에 있다 : 2,463,914
* 가까이 있다 : 4,621,897
* ~옆에 있다 : 61,261
* ~위에 있다 / ~아래에 있다 : 2,155
* 닿아 있다 : 1,936,557

### 성별 및 연령대 정보
* 여성등장 수 : 1258(49.41%), 남성등장 수 : 1288(50.59)
* 영상 Clip 별 연령대 등장 정보

<p align='center'>Figure 6: 성별 비율 및 연령대 비율.</p>

![image](https://github.com/tmcheon1/niaproject/blob/master/연령대별%20Clip수%20및%20비중.jpg)

 
 
 
## Benchmarks
* 감정분석, 개체인식, 인물인식, 관계분석, 영상기반 질의응답, 대화처리, 음성인식, 영상 상황·의도 분석 등 AI 연구분야 및 서비스 개발에 활용 가능

<p align='center'>Figure 7: 8종 AI 연구분야 개요.</p>

![image](https://github.com/tmcheon1/niaproject/blob/master/%EC%A7%80%EC%8B%9D%EB%B2%A0%EC%9D%B4%EC%8A%A4%20%ED%99%9C%EC%9A%A9%20%EC%98%88.jpg)

 
 
 
### - 외부인 침입 감지 (개체인식, 인물인식)
사용자가 외출 시 시스템에 등록되지 않은 인물이 감지될 경우, 외부인 침입으로 간주하여 사용자에게 알리고 경찰에 신고- 침입자의 영상, 음성 정보를 분석하여 성별, 나이, 체형, 발걸음 등을 분석하여 수사에 도움

### - 스케쥴 분석 (대화처리, 음성인식)
사용자가 업무 혹은 여행 스케줄을 구두로 시스템에 전달하면 시스템은 음성을 분석하여 스케줄 등록, 스케줄 장소의 날씨와 교통편, 유의사항 등을 사용자에게 제공

### - 대화를 통한 감정 분석 (대화처리, 음성인식, 감정분석)
사용자와 일상 대화를 통해 얻어지는 영상과 음성을 분석하여 현재 사용자의 감정 상태를 파악- 감정 상태에 알맞은 음악, 여행, 요리, TV프로그램 등을 추천

### - 영상 상황 분석 후 정보 전달 (관계분석, 영상 상황·의도 분석, 음성인식, 대화처리)
사용자는 TV 프로그램을 시청하다가 영상 내의 특정 제품에 대해 질문- 시스템은 사용자의 질문 분석 후 영상에서 제품을 인식하여 관련정보를 사용자에게 제공

<p align='center'>Figure 8: 8종 AI를 활용한 서비스 예시.</p>

![image](https://github.com/tmcheon1/niaproject/blob/master/서비스%20활용%20예시.jpg)


