#### 작업예정 jQuery 케이쿼리 json데이터 파싱
-외부 Data.js파일에서 json데이터를 저장한후 에서 불러와서 파싱
-외부 사이트에서 제공하는 json데이터를 html에서불러와 파싱
RestAPI서버 중 코로나 19 확진자 데이터를 받아서 html에서 파싱(데이터를 분해해서 화면에 뿌려주는 작업)
-   reatAPI 서버주소(빅테이터):https://coroname.me/getdata

#### 20210512(목)작업내역
- 작업폴더를 나누는 이유:시청(관공서),대학,기업의 웹프로그램(사이트) 
제작할때,1년간 무상 유지보수 이후 2천만,리뉴얼 4천 비용이 책정
home폴더 기존 작업물,리뉴얼 home에 덮어쓰는 방식이 아니고,
리뉴얼할때 home2021 폴더에 작업을 하게된다
-제이쿼리 코어 다운받기: min버전(압축-속도UP),일반버전(개발-속도normal)
-jQuery 미처리 작업은 다음주부터,
-오늘은 모바일 메인 페이지 1개 만들에서 과제물로 제출->스프링에서 프로그램 입히는 소스로 사용하게 된다
-애니데스크: 팀뷰어
-html5.html,css.html , js.html여기까지
-jQuery기본구조만 실습했다//수요일작업확인


#### 20210512(수)작업내역
-git clone 으로 프로젝트를 가져온 경우 아래 내용을 추가해 주셔야합니다.
-git config --list확인에서 user.name,


#### 20210511(화) 작업내역
-로렘 입숨 한글 URL:http://guny.kr/stuff/klorem/#/table-html
-로렘 입숨 영어URL: https://loremipsum.io/generator/
-URL경로(parh):루트/test/html5.html
-서버(응답하는 프로그램=respons) 아파치, 톰캣서버
-클라이언트(요청하는 프로그램=request) 웹 브라우저
-HTML은 마크업이 태그로 구성.<의미있는 문자/>...</의미있는 문자>
-http://127.0.0.1:80(8080/9000/5500/6500)
p-c의 네트워크 내부주소(공통):127.0.0.1==localhost
고유주소: 도메인-IP주소  ex)yohoo.com-76.6.143.25=주민번호
-IP주소버전:IPV4,IPV6
-HTML도 버전:HTML5,HTML4.01(old)
#### 20210510(월) 작업내역
- 개발PC(html) 와 깃 저장소와 연결시킵니다. 초기에 연결시 아래와 같은 문제점이 나올 수 있습니다.
- 레포지토리(저장소) 초기화: git init 또는 VS code에서 레포지토리초기화 버튼 이후
- Git에서 'user.name' 및 'user.email'을 구성하라고 떠요!(해결책)
- git config --local user.name 이름
- git config --local user.email 이메일
브랜치(branch)가 없다며 구성하라고 떠요!(해결책 아래 1줄)
- git branch -M master
리모트(remote)가 없다며 구성하라고 떠요!(해결책 아래1줄)
- git git remote add origin https://github.com/사용자저장소/사용자저장소.git
- 작업결과는 .git 폴더안의 config 파일에 저장됩니다.
- 이후 VS code 프로그램에서 아래 처럼 작업 하시면 됩니다.
- 업로드절차: 1. 커밋(commi) 2. 푸시(push)
- 다운로드절차: 1. 풀(pull) : 교실에서 작업한 결과를 집에서 이어서 작업할 상황
- 주의) 다른 신규 PC에서 작업시 아래 명령어로 깃내용을 새로 가져옵니다.(아래)
- git clone https://github.com/학생저장소/학생저장소.github.io.git
- 안정된 이후 기존 사용자 폴더에서는 작업 시작전에
- git pull 로 어제 작업한 내용을 최신버전으로 업데이트 합니다.
- 포트의 역할이 트렌드로 많이 사용됩니다.
- 포트(port): 포트번호로 서비스를 만드는것이 트렌드
- 이전에는 80포트에 모든 서비스 묶어놓았습니다.
- 모든서비스를 개별로 분리하는 트렌드가 있습니다.: 마이크로서비스라고 합니다. == RestAPI로 구현이 됩니다.
- 도메인(예, https://naver.com:1451241/네이버 인증서비스 개발)
- 외부 인원(네이버직원아닌) 위 포트기준으로 제작한 서비스를 갖다가 사용
- html : Hyter Text MarkUp Language 태그를 사용하는 언어
- md : MarkDown Language 태그를 사용하지 않는 언어