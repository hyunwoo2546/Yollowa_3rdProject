# 3rd Project - Yollowa

### 욜로와(Yollowa) 소개
-----
+ Yollowa는 숙박 / 액티비티 연계 예약 서비스입니다.
+ 업소의 주소 위도, 경도 비교를 통해 상대적으로 업소를 추천해주는 장점을 가지고 있습니다. (숙박은 액티비티 추천, 액티비티는 숙박업소 추천)

### 구현기능
-----
> 사용자 편의
+ 회원가입(네이버, 카카오를 통한 회원가입)
+ 정규식을 통한 회원가입(보안)
+ 메인페이지 액티비티/숙박의 인기 순 추천
+ 지역 & 종류 & 관련도순 필터
+ 업소 등록 시 주소 검색 및 좌표 계산
+ 리뷰 기능
+ 찜목록 및 장바구니 담기 기능
+ 숙박 - 체크인/체크아웃 설정에 따라 성수기/비성수기 가격의 정확한 가격 변동 구현
+ 액티비티 - 해당 업소의 옵션 선택에 따른 결제금액 및 수량 동적 구현
+ 위도, 경도 0.04 기준(차량 20~30분) 으로 추천 알고리즘 구현
+ 대표사진 캐러셀(숙박&액티비티) 및 방 사진 캐러셀(숙박)

+ 마이페이지
  + 예약현황 - 체크아웃 시점이 지나기 전 목록 출력 (해당 페이지로 이동 가능)
  + 구매내역 - 체크아웃 시점이 지난 후의 예약 목록 출력 (리뷰쓰기 가능 1회만)
  + 장바구니 - 사용자 장바구니 목록 출력 (결제 페이지로 바로 이동 가능)
  + 찜 목록 - 사용자 찜 목록 출력
  + 내가 쓴 리뷰 - 자신이 작성한 리뷰들만 모아 보여줌
  + 내가 쓴 Q&A - 자신이 등록한 Q&A를 모아 보여줌(답변 확인 및 댓글 작성 가능)
  + 사업자 신청하기 - 사업자 번호와 유형 및 업소명 입력 후 신청 (관리자의 승인 후 권한 부여)
  + 사업자 페이지 - 사업자 권한을 가지고 있을 경우 사업자 페이지 이동 가능

> 호스트 편의
+ 호스트 권한에 따른 사업자 페이지 버튼 활성화
+ 본인이 사업자번호로 등록한 업체가 있어야만 글 등록이 가능 (관리자 승인으로 권한 부여)
+ 본인이 등록 한 업소의 사진 및 해시태그 등 정보 보기 및 수정
+ 옵션/방 등록 현황에서 해당 업소에 등록 된 옵션/방 확인, 수정 및 삭제
+ 옵션/방 추가 기능
+ 등록 사진 서버에 업로드 기능
+ 주소 검색을 통한 위치 검색 등록
+ 주소 등록에서 자동 좌표 변환 저장
+ 해시태그, 사장님한마디, 공지사항, 기본정보, 인원 추가정보, 편의시설 및 서비스 등록, 취소 및 환불 규정을 태그를 동적 추가하여 한줄 씩 등록 가능


> 관리자
+ 관리자 로그인 시 활성화
+ 사업자 승인 - 사업자 신청확인 후 승인 및 권한 부여
+ 게시글 관리 - 호스트의 업소 등록을 검토하고 승인 여부 결정 (결정 시 리스트 페이지에 등록)
+ 매니저 관리 - 등록된 매니저들의 권한 및 아이디, 비밀번호 수정 및 삭제 가능

### 사용 기술
-----
Front-End: HTML5, CSS, Javascript, Jquery, jspServlet, BootStrap
Back-End: Spring, MySql, Mybatis, commons-dbcp, Jackson, jstl, junit4, log4j, maven, aspectj, log4j2
Open Api: 네이버 로그인 api, 카카오 로그인 api, sweetalert, date picker, oauth2
Tool: sts, workbench, git, chrome
