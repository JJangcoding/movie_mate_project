 제목: 무비메이트


 서비스 설명: 수많은 영화 콘텐츠 중 자신의 취향을 반영한 콘텐츠를 찾고싶어하는 유저들을 위한 웹페이지


 제작 목적: 2시간짜리 콘텐츠를 관람하기 위해 검색에 상당한 노력과 시간을 소비하는 사람들의 불편함을 해소하기 위해 제작


 제작 기간: 4월 10일 ~ 5월 15일


- 채민석 

1. 메인 화면 임의의 기준으로 인플루언서를 뽑아 추천한 영화 데이터 가져오기
2. 메인 화면 박스오피스 기준 영화 데이터 가져오기
3. 메인 화면 명작 영화 데이터 가져오기
4. 메인 화면 임의의 기준으로 배우를 뽑아 배우가 출연한 영화 데이터 가져오기
5. 평균별점 높은 기준 영화 데이터 가져오기
6. 메인 화면 장르 기반으로 추천한 영화 데이터 가져오기
7. 마이페이지
8. 로그인 카카오 open api


- 박성준

1. 메인 화면 Top10 기준 영화 데이터 가져오기
2. 마이 페이지 _> 상호작용리스트 댓글일 경우 내가 단 영화 리스트 출력
3. 마이 페이지 -> 상호작용리스트 내가 댓글 단 목록
4. 수정 페이지
5. 메인 화면 임의의 기준으로 감독을 뽑아 감독이 만든 영화 데이터 가져오기


- 장현상

1. 메인 화면 임의의 기준으로 인플루언서를 뽑아 추천한 영화 데이터 가져오기
2. 메인 화면 박스오피스 기준 영화 데이터 가져오기
3. 메인 화면 명작 영화 데이터 가져오기
4. 메인 화면 임의의 기준으로 배우를 뽑아 배우가 출연한 영화 데이터 가져오기
5. 마이 페이지
6. 로그인 네이버 open api
7. 더 보기 영화 모든 정보 출력
8. 로그인 화면 우리 자체 회원 기능 구현
9. 풋터(footer) 개발자 정보 담은 링크 배열 출력


- 김현준

1. 기본 SPRING 배포 버전 제작
2. 상호작용 리스트 - 좋아요, 댓글일 경우 리스트 출력, 더보기, 시간순 영화리스트 출력
3. 상호작용 리스트 - 별점일 경우, 드랍다운 구현, 별점별 영화출력 더보기 구현
4. 상호작용 리스트 - 별점일 경우 별점순, 각종 기준점 정하기
5. 메인화면 - 예상별점 높은 영화 데이터 추출
6. 메인화면 - 임의의 태그를 뽑아 태그가 포함된 영화 데이터 가져오기
7. 영화 선택 페이지 - 영화를 만든 제작진과 댓글달린 목록 출력
8. 영화 선택 페이지 - 선택한 영화정보 출력
9. 영화 선택 페이지 - 비슷한 작품 영화리스트 출력
10. 헤더 - 자체 회원가입 기능 구현
11. 대댓글 페이지 - 클린봇 기능 구현


- 고민지

1. 영화 선택 페이지 - 댓글 수정, 삭제, 좋아요, 댓글 수 기능 구현
2. 영화 선택 캐스트 페이지 - 캐스트 정보 출력 및 좋아요 증가 및 해당 캐스트의 작품 리스트 출력
3. 댓글 목록 페이지 - 댓글 클릭시 해당 댓글과 대댓글 목록 출력
4. 대댓글 페이지 - 댓글 수정, 삭제 , 좋아요, 댓글 수 기능 상호작용 가능하도록 데이터 가져오기
5. 대댓글 페이지 - 대댓글 등록, 수정, 삭제 기능 구현
6. 검색창 - 영화, 배우, 감독, 유저 검색 기능 구현
7. 검색창 - 내가 검색한 영화, 영화들을 만든 감독리스트, 출연한 배우리스트 출력하기
8. 헤더 - 홈키, 선택, 검색, 로그인, 회원가입, 버튼 추가
9. 헤더 - 다크모드 기능 구현

![image](https://github.com/JJangcoding/movie_mate_project/assets/124780552/d27e47a7-44d5-4838-a23d-29d716e27e6a)


![image](https://github.com/JJangcoding/movie_mate_project/assets/124780552/c1711cf0-eaed-409f-a4c8-097e5d48e327)

![image](https://github.com/JJangcoding/movie_mate_project/assets/124780552/bbe1e575-16dd-4716-9983-201c34e63fe1)




1. 메인메뉴 - 영화목록

- 박스오피스 순위 : 특정 시점 기준 최신작 목록 출력
- 왓챠 top10 영화 : 평균 별점이 높은 최신작 목록 출력
- 무비메이트 명작 영화 : 특정 시점 이전의 평균 별점이 높은 작품 목록 출력
- 무비메이트 화제의 감독 : 해당되는 감독의 작품 목록 출력
- 무비메이트 이주의 배우 : 해당되는 배우의 작품 목록 출력
- 평균 별점이 높은 영화 : 평균 별점이 높은 작품 목록 출력
- 무비메이트 이주의 추천 장르 : 해당되는 장르의 작품 목록 출력
- 이주의 인플루언서 추천 영화 : 평균 별점이 높아 추천할 수 있는 작품 목록 출력


2. 선택한 영화 화면

- 코멘트 미리보기, 좋아요, 댓글수, 삭제하기 : 코멘트, 좋아요, 댓글 수 등 해당되는 영화의 정보들을 표시
- 댓글 작성 : 내가 작성한 댓글이 해당 영화에 표시
- 별점, 보고싶어요 : 내가 부여한 별점 및 보고싶어요가 DB에 반영 되도록 설정
- 제작진 정보 : 영화 api를 활용하여 해당 영화에 부합하는 제작진 정보 표시
- 기본 정보 더보기 : 원제, 개봉년도, 국가, 장르, 상영시간, 연령 등급, 내용 표시
- 비슷한 작품 : 해당 영화와 비슷한 장르를 가지는 작품 목록 출력
- 왓챠 광고 링크 : 왓챠 이벤트 광고를 링크에 연결


3. 코멘트 목록 화면

- 코멘트 내용 : 내가 작성한 코멘트 내용시
- 좋아요, 댓글수 : 해당 영화의 좋아요 및 댓글 수를 표시


4. 코멘트 자세히 보기

- 댓글 삭제 : 내가 작성한 댓글을 작성자만 삭제할 수 있게 기능 구현
- 대댓글 작성 : 댓글에 대한 댓글 작성 기능
- 대댓글 수정, 삭제 : 대댓글 수정, 삭제 기능
- 대댓글 좋아요 : 대댓글에 대한 좋아요 버튼 활성화
- 댓글을 작성한 유저 정보 : 댓글 작성자의 이름 표시
- 댓글을 작성한 영화 정보 : 댓글에 해당하는 영화 정보 표시
- 댓글 작성자의 별점 : 댓글 작성자의 별점 표시
- 악성 댓글 감지 클린봇 : 댓글에 비속어가 포함되어 있을 시 클린봇이 작동하여 필터링 하도록 구현


5. 로그인

- 카카오 로그인 : 카카오 로그인 api 이용해서 계정 연동하기
- 네이버 로그인 : 네이버 로긍인 api 이용해서 계정 연동하기


6. 회원가입

- 이름 중복 체크 : 중복된 이름이 가입되지 않도록 중복성 체크
- 유효성 체크 : 이름, 이메일 및 비밀번호가 유효성 체크 조건에 맞도록 검사
- 네이버 및 카카오 회원가입 : 네이버 & 카카오의 프로필 이미지, 이름 및 이메일 가져오기


7. 마이페이지

- 정보 수정 : 이미지 변경, 이름 변경, 비밀번호 변경, 뒤로가기, 변경된 이름 & 비밀번호 저장
- 취향 분석 : 내가 평가한 영화들의 평균 별점과 통계를 시각적으로 표현
- 평가한 영화 : 내가 평가한 영화 및 보고싶어요를 누른 영화들을 표시


8. 검색

- 유저검색 : 내가 입력한 검색어에 부합하는 유저 검색
- 배우, 영화 검색 : 내가 입력한 검색어에 부합하는 배우 및 영화 검색


9. 다크모드

- 어두운 스킨을 적용하여 css를 변경


10. 풋터

- 각종링크 (팝업) 풋터에 링크 연결하여 정보 창 띄우기
- 평가한 영화수 : DB에 연동하여 평가 및 코멘트 개수를 평가 개수 창에 띄우기
