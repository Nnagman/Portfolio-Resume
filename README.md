# 이창호

### 기본 정보

- 이메일: nnagman@gmail.com
- Github: https://github.com/nnagman
- Velog: https://velog.io/@nnagman
- Blog: https://blog.naver.com/ckdgh930314
    
### 기술 스택
- 백엔드
    - JAVA(SPRING) : MVC 패턴 프로젝트 경험, BOOT를 사용한 API SERVER 프로젝트 경험
    - PHP : 카카오i오픈빌더 기능을 구현하기 위한 프로젝트 경험
    - MYSQL : 간단한 쿼리 작성 및 성능 테스트, 튜닝 경험
    - PYTHON : 웹페이지 파싱 기능을 위해 selenium, beautiful soup4 라이브러리 사용 경험
    - MONGODB : SPRING BOOT를 사용한 API SEVER 프로젝트에서 저장, 읽기 기능 구현
    - PRISMA : Node 개발 환경에서 graphql를 활용하여 DB 데이터를 CRUD하는 기능 구현 경험

- 프론트엔드
    - React: 간단한 페이지 개발 및 클라이언트와 협업 경험
    - APOLLO : 백엔드와 데이터를 주고 받기 위한 프론트엔드 서버 생성 경험
    - GRAPHQL : 데이터를 주고 받을 때 구조를 간편하게 명시하기 위해 사용 경험
    
- 기타
    - JENKINS : GITHUB WEBHOOK을 활용한 자동배포 경험
    - 클라우드서비스 : NCLOUD, AWS, GCP 경험 및 서버 구축 경험
    - NGINX : 로드밸런싱을 위한 설정 구현. 프록시 설정 구현
    - ARTILLERY, JMETER : 부하테스트를 설정 구현 및 사용 경험

### 주요 프로젝트
- [링북](https://cat-tungsten-c56.notion.site/LINKBOOK-73c460ea18504013b84b7b850c1215f5)
    - 북마크 저장 및 관리 서비스 백엔드 개발
    - 담당: 백엔드 API 개발 및 AWS EC2 인프라 구축
    - 기술스택: SpringBoot, JPA, MySQL, AWS
    - 기간: 2022/07 ~ 2022/08
    - 인원: 5명

- 라플로우
    - 배송대행 웹 서비스
    - 담당: 인프라구축, 프론트엔드 & 백엔드 개발
    - 기술스택: Node.js, React, RDBMS(Postgresql), Linux, AWS
    - 기간: 2021/07 ~ 2022/02
    - 인원: 1명
    - 설명
        - 사용자들이 배송을 요청, 배송내역을 확인 할 수 있는 웹 서비스.
        - 관리자들이 사용자 관리, 배송 상태를 관리할 수 있는 기능 구현.
        - 웹캠으로 배송 상품 캡처 기능 구현

- [상인정보통](https://pf.kakao.com/_VxhNixb)
    - 소상공인진흥공단 챗봇
    - 담당: 챗봇 개발 & 유지보수 및 기능 추가 작업, 고도화 작업
    - 기술스택: HTML, CSS, JS, PYTHON, PHP, MYSQL, APACHE2, SPRING BOOT, MONGODB, NGINX
    - 기간: 2020/03 ~ 2020/04 ( 기존 작업), 2021/01 ~ 2020/04 ( 고도화 작업 )
    - 인원: 1명 ( ~2020/12 ) -> 3명
    - 설명
        - 사용자들에게 맞춤형 지원사업을 추천 및 검색할 수 있게 해주는 챗봇
        - 지원사업 정보를 가져오기 위해서 기업마당에서 제공하는 RSS 데이터를 PYTHON으로 요청하고 DB(MYSQL)에 저장 & crontab 스케줄러를 통해 특정 간격마다 새로운 지원사업 업로드 확인
        - 추천 정확도를 높이기 위해 사용자들의 개인설정을 하기 위한 웹페이지 제작
        - 이벤트API를 사용여 특정시간에 원하는 정보를 알림형태로 사용자들에게 보내기 위해서 crontab 스케줄러를 통해 카카오 서버측으로 요청을 보내는 기능 구현
        - 기존 전임자가 작성한 쿼리 성능을 개선
        - 챗봇에서 사용자들의 행동(블록이동, 버튼클릭)들을 수집, 이를 바탕으로 서비스 개선
    - 고도화
        -   SPRING BOOT로 다른 챗봇들도 지원가능한 API 서버를 구축
        -   서비스 특성상 구조가 자주 바뀌는 데이터들이 많아 MONGODB로 변경
        -   일반사용자, 관계자, 관리자 별 인증 추가 및 사용 범위 제한

- [지원사업알리미챗봇](https://pf.kakao.com/_DbxgnC)
    - 맞춤 지원사업 추천 및 알림 챗봇
    - 담당: 챗봇 유지보수 및 기능 추가 작업
    - 기술스택: HTML, CSS, JS, PYTHON, PHP, MYSQL, APACHE2
    - 기간: 2019/11 ~ 2021/04 (유지보수 기간)
    - 인원: 1명 ( ~2020/11 ) -> 2명
    - 설명
        - 사용자들에게 맞춤형 지원사업을 추천 및 검색할 수 있게 해주는 챗봇
        - 지원사업 정보를 가져오기 위해서 기업마당에서 제공하는 RSS 데이터를 PYTHON으로 요청하고 DB(MYSQL)에 저장 & crontab 스케줄러를 통해 특정 간격마다 새로운 지원사업 업로드 확인
        - 추천 정확도를 높이기 위해 사용자들의 개인설정을 하기 위한 웹페이지 제작
        - 이벤트API를 사용하여 특정시간에 원하는 정보를 알림형태로 사용자들에게 보내기 위해서 crontab 스케줄러를 통해 카카오 서버측으로 요청을 보내는 기능 구현
        - 기존 전임자가 작성한 쿼리 성능을 개선 
        - 챗봇에서 사용자들의 행동(블록이동, 버튼클릭)들을 수집, 이를 바탕으로 서비스 개선

- [수성아동병원챗봇&관리자페이지](https://pf.kakao.com/_ljXaC)
    - 병원 예약 
    - 담당: 챗봇 개발 & 유지보수 및 기능 추가 작업
    - 기술스택: HTML, CSS, JS, PYTHON, PHP, MYSQL, APACHE2
    - 기간: 2020/03 ~ 2020/04
    - 인원: 1명
    - 설명
        - 사용자들에게 병원진료 예약을 도와주는 챗봇
        - 진료표를 가져오기 위해 PYTHON의 Beautiful Soup4 라이브러리로 병원 진료 스케줄 웹페이지를 파싱 후 DB(MYSQL)에 저장
        - 병원 직원들이 예약 관리를 할 수 있도록 예약 관리 웹페이지 작성 ( Jquery의 Ajax로 서버에 요청 )

### 학력
- [영진전문대학교](http://yjp.ac.kr) 2012/03 ~ 2021/02 컴퓨터정보과 졸업(전문학사학위취득 -> 심화과정수료 -> 학사학위취득)
