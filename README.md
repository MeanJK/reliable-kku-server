# Project-든붕이
카페 미리주문 어플


## 목차
  - [프로젝트 소개](#프로젝트_소개)
  - [개요](#개요)
  - [프로젝트 설명](#프로젝트설명)

## 프로젝트 소개
'스타벅스 사이렌 오더'와 비슷한 카페 미리주문 어플입니다.

## 개요
- 프로젝트 이름: 든붕이
- 프로젝트 지속기간: 2023.09-2023.11
- 개발 엔진 및 언어: Server(Spring Boot, Java, JPA) | Client(React Native, Typescript)
- 멤버(김민진, 박재완, 정경주, 김선규)
  
- Server
- 팀장(박재완) - 사용자(Spring 시큐리티 구성, git 연결, 로그인, 회원가입, 자동 로그인, PW 찾기, 현장접수 로직, 주문 로직, sse, fcm, 메인화면 남은시간), 관리자(주문 대기&접수&완료별 리스트, 대기 주문 조리시간, 관리자 영업 시작&
종료 로직, 관리자 로그인&로그아웃, 회원관리, 메뉴별 품절&품절취소, docker 배포)
- 팀원(김민진) - Cloud를 이용한 서버 구축 및 배포, 저장소 구축, DB설계, 사용자(결제 구현,  결제 시 도장 체크, 마이페이지, 과거주문내역, PW변경, 회원탈퇴), 관리자(메뉴 수정, 주문 취소 및 환불, 매출관리 엑셀로 구현,
매출관리 달력으로 구현, 메뉴 주문&대기&완료 개수)

  
- Client
- 팀원(정경주) - 사용자
- 팀원(김선규) - 관리자

## 프로젝트설명

**든붕이** 는 건국대학교 글로컬캠퍼스 학생들이 이용하는 **든든하쿠** 라는 카페에서 사용할 수 있는 어플입니다.

현재 카페에서는 음료/붕어빵/와플/탕후루 등을 판매중이며 **든붕이** 라는 어플에서 메뉴들을 미리 주문할 수 있습니다.

**든든하쿠**의 주고객은 학생들이며, 학생들이 어떻게 하면 더 좋고 편리하게 가게를 이용할 수 있을지에 초점을 맞추고, 발전해 나가려 항상 노력하고있습니다.

작년부터 카페에서 붕어빵을 판매하기 시작하였는데, 붕어빵 대기시간이 길어져 추운 겨울, 1시간 반 가까이 밖에서 웨이팅하게 해드렸던 점이 죄송하고, 어떻게 하면 손님들이 기다리시지 않을까? 혹은 어떻게 하면 편하게 주문하실 수 있을까? 하는 고민을 하다가 이 문제점을 해결하기 위해 붕어빵을 미리 주문하고, 결제할 수 있는 **든붕이** 라는 어플을 만들게 되었습니다. 또한 수업시간 전 음료를 주문하기 위해 줄을 서 대기하는 고객들의 불편함을 줄이고자 붕어빵과 같은 디저트 뿐만 아니라 음료 메뉴들도 주문할 수 있도록 관리자 어플에서 메뉴 수정 기능을 추가하였습니다.

### 사용자/관리자

**든붕이** 어플은 **사용자/관리자** 어플로 총 2개의 어플입니다.

**사용자 어플**은 메뉴를 미리 주문하고, 토스페이먼츠 전자결제를 활용하여 미리 결제까지 할 수 있도록 구현하였습니다. 또한 현재 예상 소요시간을 확인할 수 있고, 주문현황을 확인할 수 있도록 구현하였습니다.

**관리자 어플**은 사용자가 어플로 주문한 주문에 대한 상태 및 매출 등을 확인/처리 할 수 있고, 현장 주문 접수도 가능하도록 구현하였습니다.

  - 사용자 화면
    
  <img src="https://i.esdrop.com/d/f/pDyqiY4YnX/WLGKnbuiPG.png" alt="메인화면" width="200" height="450"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/tkThg0o5yb.png" alt="주문화면" width="200" height="450"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/BZKRCiX8W6.png" alt="과거주문내역" width="200" height="450"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/gcMArCnHIi.png" alt="마이페이지" width="200" height="450">

  - 관리자 화면

  <img src="https://i.esdrop.com/d/f/pDyqiY4YnX/xOTrNxVX7s.png" alt="로그인" width="240" height="170"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/Dm2ExjPvDz.png" alt="대기화면" width="240" height="170"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/U8bmt91JHT.png" alt="접수화면" width="240" height="170"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/sLjV8P5Qij.png" alt="완료화면" width="240" height="170">
  
  <img src="https://i.esdrop.com/d/f/pDyqiY4YnX/FkN0EJuoVA.png" alt="영업관리" width="240" height="170"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/LeqsHwplN7.png" alt="메뉴관리" width="240" height="170"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/dzKbjZez5w.png" alt="메뉴수정" width="240" height="170"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/fhXFWdEbtM.png" alt="회원관리" width="240" height="170">
  
  <img src="https://i.esdrop.com/d/f/pDyqiY4YnX/2bxXPLKY7X.png" alt="매출관리1" width="480" height="320"><img src="https://i.esdrop.com/d/f/pDyqiY4YnX/K561yFnwDn.png" alt="매출관리2" width="480" height="320">
  
  


