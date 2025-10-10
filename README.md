# Order_System
2024 개인 프로젝트

https://www.songdoroadpizza.kr/

실제로 사용하기 위한 주문체계를 적용한 홈페이지, 프로그램, 앱 제작

# 홈페이지
REACT의 JSX를 사용하여 화면을 구성.

다양한 화면에서도 자연스럽도록 반응형 웹페이지로 제작.
#### - 메뉴페이지
<img width="3840" height="1286" alt="image" src="https://github.com/user-attachments/assets/3dd0e7f2-7394-4752-a658-c35fa29d60c9" />

#### - 주문페이지
<img width="961" height="598" alt="캡처" src="https://github.com/user-attachments/assets/03a13389-fda4-4e5e-b016-f3170ac8f06a" />

#### - 서버
Google Cloud Platform에서 가상머신으로 서버 생성.

Node.js로 Express 프레임워크를 사용하여 제작. 

결제 API를 통해 결제가 완료되면 주문정보를 PostgreSQL에 저장 및 주문 접수 프로그램 및 앱으로 정보 전송.

주문할 때 알림권한을 허용할 경우 토큰을 저장하고, FCM(Firebase Cloud Messaging)을 통해 알림 전송.

# - 프로그램
Python Qt5프레임워크를 사용하여 제작.

#### UI
<img width="878" height="531" alt="캡처2" src="https://github.com/user-attachments/assets/78a8015c-9253-430e-8026-7de0a198146e" />

<img width="835" height="584" alt="캡처3" src="https://github.com/user-attachments/assets/d03d266f-7d2c-4052-a908-e5d8b7eda27f" />

최소화할 경우 팝업 아이콘 및 시스템 트레이아이콘을 통해 접근성 개선.

pyupdater를 통해 서버를 활용한 버전관리.

Pooling 방식으로 주문 접수 확인.

# 앱
Android Studio에서 Kotlin으로 제작.

<img height="500" alt="캡처4" src="https://github.com/user-attachments/assets/86e28e33-6a30-46f7-a95b-8aac84d25aff" />


주문 접수 상태 제어 및 알림 관리 기능. 

# 결과 및 유지보수

실제 주문 접수를 받아 문제 없이 사용할 수 있었습니다. 

Pooling 방식을 SSE방식으로 바꿔서 HTTP overhead를 줄일 예정.

UI 및 디자인 개선 예정.

이미지 파일 로딩 속도 개선 예정.
