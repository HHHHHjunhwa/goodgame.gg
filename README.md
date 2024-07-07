# GOODGAME.GG

외부 오픈 API(RIOT API)를 활용한 데이터 통계 개인화 서비스 사이트

# 프로젝트 소개

[op.gg](https://OP.GG/)와 [lol.ps](https://lol.ps/)와 같은 롤 전적검색 사이트를 벤치마킹하여 제작한 서비스 사이트입니다


# 개발 기간

 + 2024-03-22~2024-04-05 : 주제 탐색,선정 및 프로젝트 구체화

 + 2024-04-06~2024-04-28 : 프로젝트 수행(개발 및 디버깅)

 + 2024-04-29~2024-05-02 : 프로젝트 마무리 


# 개발자 소개

| 구분 | 이름  | 담당 | github |
|----|-----|----|--------|
| 팀장 | 백사랑 | 커뮤니티 게시판  | [Arzro](https://github.com/Arzro/)      |
| 팀원 | 윤도영 | 전적검색/회원가입/로그인&로그아웃  | [dozero25](https://github.com/dozero25/)      |
| 팀원 | 홍준화 | 듀오찾기/LOL-BTI  | [HHHHHjunhwa](https://github.com/HHHHHjunhwa/)      |
| 팀원 | 남병선 | 랭킹/ 로테이션 챔피언  | [RedPanda0000](https://github.com/RedPanda0000/)      |
| 팀원 | 창미주 | 내 정보(마이페이지)/LOL-BTI  | [chis050](https://github.com/chis050/)      |


# 개발환경

* 협업툴  
   *<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/slack.PNG" width="50px" height="50px"> __Slack__
 <img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/github.PNG" width="50px" height="50px"> __GitHub__
  <img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/sourcetree.PNG" width="50px" height="50px"> __SourceTree__
   <img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/figma.PNG" width="50px" height="50px"> __Figma__
  <img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/swagger.PNG" width="50px" height="50px"> __Swagger__
   <img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/notion.PNG" width="50px" height="50px"> __Notion__
  <img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/spreadsheet.PNG" width="50px" height="50px"> __SpreadSheet__
               
 * Back-End  
   *<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/back_end_img/springboot.PNG" width="50px" height="50px"> __SpringBoot__
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/back_end_img/java.PNG" width="50px" height="50px"> __Java__
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/back_end_img/mybatis.PNG" width="50px" height="50px"> __MyBatis__
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/back_end_img/javascript.PNG" width="50px" height="50px"> __JavaScript__
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/back_end_img/maven.PNG" width="50px" height="50px"> __Maven__

 * Front-End  
   *<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/front_end_img/html.PNG" width="50px" height="50px"> __HTML__
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/front_end_img/css.PNG" width="50px" height="50px"> __CSS__
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/front_end_img/ajax.PNG" width="50px" height="50px"> __aJax__
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/front_end_img/jquery.PNG" width="50px" height="50px"> __jQuery__


 * Server  
   *<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/server_img/mysql.PNG" width="50px" height="50px"> __MySql__
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/server_img/ncp.PNG" width="50px" height="50px"> __NCP__


# 주요 기능

직접 수행하려면 RIOT 키가 필요한데 이를 보안상의 이유로 github에 업로드 되지 않도록 조치하였습니다.

아래 설명과 캡쳐 사진으로 대체합니다.

1. 홈 화면

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/hone_1.PNG" width="500px" height="500px">

* 게임 아이디를 검색하여 전적 검색 -- 빈 문자열 OR 아이디+태그라인으로 입력하지 않으면 오류 메세지 출력

* 매 주 마다 변경되는 로테이션 챔피언들의 기본 정보와 스킬 정보 출력

* 다양한 메뉴들로 이동 가능(랭킹, 듀오찾기,LOL-BTI,커뮤니티,마이페이지)

2. 전적 검색 

* 일반검색

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/search_1.PNG" width="500px" height="500px"> 

* 최근 20개의 전적을 차례대로 출력하며 기본적인 데이터(게임 참가 아이디,챔피언,스펠,게임 진행 시간, 게임 승패여부등) 출력

* 세부정보

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/search_detail.PNG" width="500px" height="500px"> __Maven__

* 일반 검색에서 화살표를 클릭하면 선택한 게임의 상세 정보(게임 내 1위 기록들, 라인정보, 아이템, KDA등) 출력


3. 랭킹

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/ranking_1.PNG" width="500px" height="500px"> __Maven__

4. 듀오 찾기

* 듀오 정보

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/duo_1.PNG" width="500px" height="500px"> __Maven__

* 듀오 구인글 작성

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/duo_2.PNG" width="500px" height="500px"> __Maven__

5. 커뮤니티

* 커뮤니티 메인

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_1.PNG" width="500px" height="500px"> __Maven__

* 글 작성

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_write.PNG" width="500px" height="500px"> __Maven__

* 글 수정/삭제

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_delete.PNG" width="500px" height="500px"> __Maven__

* 글 상세정보

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_details.PNG" width="500px" height="500px"> __Maven__

* 댓글

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_reply.PNG" width="500px" height="500px"> __Maven__

6. 마이페이지

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/mypage.PNG" width="500px" height="500px"> __Maven__

7. LOL-BTI

* 메인화면

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/lolbti_1.PNG" width="500px" height="500px"> __Maven__

* 질문과 선택지

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/lolbti_2.PNG" width="500px" height="500px"> __Maven__

* 결과
   
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/lolbti_3.PNG" width="500px" height="500px"> __Maven__


