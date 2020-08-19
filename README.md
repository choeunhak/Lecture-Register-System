# 수강신청 시스템
자바 콘솔창 이용(데이터는 txt 파일로 이용, GUI, SQL 없음)


## 구현한 기능
### 로그인 및 회원가입
* ID, PW 찾기
* 회원가입시 user마다 개인파일 생성 및 저장
* 회원가입 시에 이름, 아이디, 비밀번호 형식 지정(제한)

### 미리담기 및 수강신청
* 미리담기 및 수강신청 할 때 중복된 강좌 제외하기(오류메세지 출력하기)
* 최대수강신청학점 18학점으로 제한하기

### 마이페이지
* 마이페이지에서 미리담기, 수강신청한 과목보기
* 아이디 중복검사(중복된 아이디 제한하기)
* 미리담기한 과목 수강신청하기
* 미리담기 및 수강신청 취소하기
* 미리담기, 수강신청한 총 학점 보여주기
* 비밀번호 변경
* 로그아웃

## 코드 구조(UML, Enterprise Architect 사용, ValueObject(DAO는 제외))
![workflow](https://user-images.githubusercontent.com/59510736/90589250-a2ffff80-e218-11ea-9bb0-31c5a8da1552.jpg)
