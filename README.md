# 음식 주문 배달 프로그램

# 프로그램 실행 화면
<초기 화면>
회원가입 또는 로그인 또는 프로그램 종료 중 동작 선택.

회원가입 선택시: ![image](https://github.com/Ninky0/foodDelivery/assets/113659622/2f4fdc02-c728-43b2-9aa4-37f281471ecb)

로그인 선택 시:　![image](https://github.com/Ninky0/foodDelivery/assets/113659622/71c30a36-895b-4d27-8310-d783d96464d0)

프로그램 종료 선택 시: ![image](https://github.com/Ninky0/foodDelivery/assets/113659622/764981a1-5b56-4f7c-b214-49ef554462c3)

<회원 가입 인터페이스>
고객인지 음식점인지 선택.
  <고객 회원 가입 인터페이스> 실행
  - 개인 기본 정보 >> 이름, 전화번호, 지역
  - 로그인 정보    >> 아이디, 비밀번호
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/a3387f5e-eb6e-48e2-8570-f5eb07003f2d)

예외 처리
- 아이디의 중복 여부를 확인.
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/ed8dc983-6120-42a1-b67d-d7b73c914dba)

- 전화번호의 중복 여부를 확인.
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/78dcdb25-95fd-45ce-8ed5-715289798379)

  <음식점 회원 가입 인터페이스> 실행
  - 업체 기본 정보 >> 이름, 전화번호, 지역
  - 로그인 정보    >> 아이디, 비밀번호
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/05c826c1-7cfe-495d-8444-086c824636be)

저장할 때 아이디 및 전화번호의 중복 여부를 확인.
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/e1eb8b41-3c88-4f99-bbe6-2fe19cd98c99)

중복되지 않았고, 올바르게 입력했다면 고객 및 음식점 객체 생성한 후 클래스에 추가. (회원 가입 완료)


<로그인 인터페이스>
고객 및 음식점이 로그인을 시도하였을 때, 클래스에 저장되어있는 정보임이 확인되면 로그인 성공
<고객>
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/cc3105dc-faf5-4f7b-95e4-6b4fe9df1025)

<음식점>
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/faea3174-0fed-41f0-ba7a-5d3059d74717)


클래스에 저장되어있지 않은 객체라면 로그인 실패
<고객>
- 비밀번호 잘못 입력했을 때
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/c5e6ebf8-5fbb-421c-b01b-6a5de59b8d63)
-  존재하지 않는 아이디를 입력했을 때
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/c73e893e-3cbd-44f6-ac4d-0e66e7ac6c62)

<음식점>
- 비밀번호 잘못 입력했을 때
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/77aff6d6-c460-4571-9625-47bf70bee89c)
-  존재하지 않는 아이디를 입력했을 때
![image](https://github.com/Ninky0/foodDelivery/assets/113659622/1c567d4c-f4bc-46d0-be30-4462a36c540a)
