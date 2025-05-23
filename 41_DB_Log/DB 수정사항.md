05_22 업데이트

- DB수정 및 엔티티수정
	 - DB -> HeidiSQL 접속 -> 테이블
	 - Img테이블 -> size -> Bigint(Entity 기준 Long)로 변경
	 - Img테이블 -> data -> blob(Entity 기준 byte[])로 변경
	 - itemimg 테이블-> imgsize -> Bigint로 변경
	  itemimg 테이블 -> data -> blob(Entity 기준 byte[])로 변경
	엔티티 
	- Img엔티티 ->
	- data -> private byte[] data; 
	- size -> private Long size;
	- ItemImg엔티티 ->
	- imgdata -> private byte[] imgdata;
	- imgsize -> private Long imgsize;

05_23 업데이트

	member 테이블 닉네임 칼럼 추가
				 newpassword 임시 비밀번호 추가
	 board 테이블에 임시 썸네일 url 추가
	 
	 