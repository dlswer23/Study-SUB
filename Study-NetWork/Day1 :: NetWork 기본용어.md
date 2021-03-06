#### 네트워크 기초 용어



+ 시스템, 인터페이스, 전송 매체, 프로토콜, 네트워크, 인터넷, 표준화

  

  + 시스템 : 내부 규칙에 따라 능동적으로 동작하는 대상
  + 예 : 컴퓨터, 자동차, 커피 자판기, 마이크로 프로세서, 운영체제, 프로세서

  

  + 인터페이스 : 시스템과 전송 매체의 연결 지점에 대한 규격

  + 예 : USB

    

+ ###### 네트워크 : 전송 매체로 서로 연결된 시스템의 모음

  + 프로토콜을 사용하여 데이터를 교환하는 시스템의 집합을 통칭

  `

+ 인터넷 : 전세계의 네트워크가 유기적으로 연결되어 동작하는 통합 네트워크

  + 공통 기능 : IP(internet Protocol)

  

+ 표준화 : 서로 다른 시스템이 상호 연동해 동작하기 위해 통일된 연동 형식



#### 시스템 기초 용어

+ 시스템의 구분
  + 노드 : 인터넷에 연결된 시스템의 가장 일반적인 용어
  + 호스트 : 컴퓨팅 기능이 있는 시스템
  + 클라이언트 : 서비스를 요청하는 시스템
  + 서버 : 서비스를 제공하는 시스템





#### OSI 7계층



< 필수적으로 외워야 하는 !! >

![image](https://media.vlpt.us/images/xldksps4/post/980fe5d0-fcfe-4395-9148-0a110475ba26/image.png)





#### 각 계층의 역할



물리계층 : 물리적으로 데이터를 전송하는 역할을 수행

데이터 링크 계층 : 물리적 전송 오류를 해결 ( 오류 감지 / 재전송 기능)

네트웨크 계층 : 올바른 전송 경오를 선택(혼잡 제어 포함)

전송 계층 : 송수신 프로세스 사이의 연결 기능을 지원

세션 계층 : 대화 개념을 지원하는 상위 논리적 연결을 지원

표현 계층 : 데이터의 표현 방법

+ 압축 : 전송되는 데이터의 양

+ 암호화 : 전송되는 데이터의 의미

응용 계층 : 다양한 응용 환경을 지원 



#### 데이터의 단위

+ TPDA : 전송 계층의 데이터 단위 
  + 세그먼트 : TCP 프로토콜에서 사용
  + 데이터그램 : UPD 프로토콜에서 사용
+ NPCU : 네트워크 계층의 데이터 단위
  + 패킷
+ DPDU : 데이터 링크 계층의 데이터 단위 
  + 프레임



#### 컴퓨터 3대장 

CPU : 연산, 처리(두뇌 역할)

RAM : 주기억 장치

HDD : 보조기억장치



#### 인터네트워킹

- 게이트웨이 : 인터네트워킹 기능을 수행하는 시스템
  - 리피터 : 물리 계층을 지원(신호 증폭)
  - 브리지 : 물리 계층을 데이터 링크 계층을 지원
  - 라우터 : 물리계층, 데이터 링크 계층 , 네이워크 계층을
