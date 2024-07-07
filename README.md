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

A. 게임 아이디를 검색하여 전적 검색 -- 빈 문자열 OR 아이디+태그라인으로 입력하지 않으면 오류 메세지 출력

B. 매 주 마다 변경되는 로테이션 챔피언들의 기본 정보와 스킬 정보 출력

C. 다양한 메뉴들로 이동 가능(랭킹, 듀오찾기,LOL-BTI,커뮤니티,마이페이지)

2. 전적 검색 

* 일반검색

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/search_1.PNG" width="500px" height="500px"> 

A. 최근 20개의 전적을 차례대로 출력하며 기본적인 데이터(게임 참가 아이디,챔피언,스펠,게임 진행 시간, 게임 승패여부등) 출력

* 세부정보

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/search_detail.PNG" width="500px" height="500px">

B. 일반 검색에서 화살표를 클릭하면 선택한 게임의 상세 정보(게임 내 1위 기록들, 라인정보, 아이템, KDA등) 출력

3. 랭킹

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/ranking_1.PNG" width="500px" height="500px"> 

A. 자유랭크/솔로랭크 별로 랭킹을 보여주며, 아이디 클릭 시 전적 검색으로 이동

B. 검색하고 싶은 닉네임 일부 입력 시 해당 관련 닉네임의 랭킹 출력

C. 티어 별로 랭킹 출력 가능


4. 듀오 찾기

* 듀오 정보

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/duo_1.PNG" width="500px" height="500px"> 

A. 게임 타입, 티어, 포지션 별로 듀오 구인글 확인 가능

B. 작성 시간, 만료 여부(작성 후 15분), 작성 내용, 닉네임, 티어, 포지션, 모스트 3 챔피언이 출력되며, 아이디 복사 버튼으로 쉽게 아이디+태그라인을 클립보드로 복사 가능


* 듀오 구인글 작성

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/duo_2.PNG" width="500px" height="500px"> 

A. 아이디+태그라인을 입력하여 아이디 확인 과정을 거쳐야 글 작성이 가능하게 설정(오류 시 확인 메세지 출력)

B. 게임 타입, 원하는 포지션을 선택하고 내용 작성 한 뒤 입력 완료 버튼을 누르면 업로드됨

5. 커뮤니티

* 커뮤니티 메인

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_1.PNG" width="500px" height="500px"> 

A. 커뮤니티 메인 페이지로서, 글 검색을 위한 드롭박스와 검색 창을 포함한 검색 기능

B. 글 번호,제목,댓글수,썸네일,작성자,작성 시간,조회수,추천수등을 출력하는 글 목록 출력 기능

* 글 작성

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_write.PNG" width="500px" height="500px"> 

A. 글 제목과 내용은 필수이며 작성 하지 않고 완료 버튼 클릭시 오류 메세지 출력

B. 이미지 파일 첨부 가능하며 다른 확장자 파일 첨부 시 오류 메세지 출력

* 글 수정/삭제

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_delete.PNG" width="500px" height="500px"> 

A. 작성자와 로그인 되어 있는 정보를 비교하여 일치할 경우만 수정/삭제 페이지로 이동 

B. 제목과 내용,첨부파일 등을 수정할 수 있고, 글을 삭제할 수도 있음

C. 해당 글 삭제시 해당 글에 달려 있는 댓글 전부 삭제

* 글 상세정보

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_details.PNG" width="500px" height="500px"> 

A. 글의 작성자,제목,내용,첨부사진,추천여부 등 글의 정보 출력

B. 로그인 되어 있다면 해당 글에 추천 가능

C. 해당 사진에 마우스 포인터가 올라가면 확대되어 사진 확인 가능

* 댓글

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/community_reply.PNG" width="500px" height="500px"> 

A. 로그인이 되어 있다면 해당 글에 댓글을 달 수 있고, 달려 있는 댓글에 대댓글도 작성 가능

B. 댓글 작성자와 로그인 되어 있는 정보가 일치하면 해당 댓글 수정/삭제 버튼 활성화 

6. 마이페이지

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/mypage.PNG" width="500px" height="500px"> 

A. 로그인 되어 있는 아이디의 기본 정보(닉네임,이메일,성별)을 보여주고 수정 버튼 활성화

B. 내가 쓴 게시글이나 댓글을 확인 할 수 있고, 삭제 버튼 활성화

C. 회원 탈퇴 버튼을 통해 회원 탈퇴 진행 가능

7. LOL-BTI

* 메인화면

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/lolbti_1.PNG" width="500px" height="500px"> 

A. LOL-BTI에 접근하면 가장 먼저 보여지는 페이지

* 질문과 선택지

<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/lolbti_2.PNG" width="500px" height="500px"> 

A. 총 10개의 질문에 대한 대답을 골라가며 진행한다.

* 결과
   
<img src="https://github.com/HHHHHjunhwa/goodgame.gg/blob/main/capture/lolbti_3.PNG" width="500px" height="500px"> 

A. 해당 답변들을 추합하여 가장 알맞는 라인과 추천하는 캐릭터를 보여준다.
