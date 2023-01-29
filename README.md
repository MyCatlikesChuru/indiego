![indiego 배너](https://user-images.githubusercontent.com/80394894/215343325-a5fb83b1-567a-42fc-9d40-2b28f3159df9.jpg)


## 👥 개굴단 팀원 소개  

|김경배|김혜원|박연환|김정희|박성호|이재혁|
|:---:|:---:|:---:|:---:|:---:|:---:|
|<img alt="김경배" src="" height="150" width="150">|<img alt="김혜원" src="" height="100" width="100">|<img alt="박연환" src="" height="100" width="100">|<img alt="김정희" src="" height="100" width="100">|<img alt="박성호" src="https://user-images.githubusercontent.com/80394894/210201174-7972272f-9b5f-4bd2-b148-bc7269b907c2.jpg" height="100" width="100">|<img alt="이재혁" src="https://user-images.githubusercontent.com/95069395/215324198-c238be32-d721-4c18-8cea-e56f8ca35486.png" height="100" width="100">|
|**FE**|**FE**|**FE**|**BE**|**BE**|**BE**|
</br>

## 🔥 indiego 소개
- 홍대 버스킹, 혜화 연극 등 일부 지역에 국한되어 있는 문화 컨텐츠를 가까운 우리 동네에서 즐길 수는 없을까? 라는 질문에서 시작되었습니다.
- 가수 또는 배우를 꿈꾸는 사람들, 취미로 음악, 연극 등의 활동을 하는 사람들에게 자신들만의 무대를 구성하여 홍보하고, 활동할 수 있는 공간을 만들고 싶었습니다.
- 또한, 음악과 연극 등의 문화 생활을 즐기는 사람들에게 가까운 우리 동네에서도 즐길 수 있도록 편리함을 제공하고 싶었습니다.
- 이 모든 요구사항을 만족시키기 위해 개굴단 단원들이 함께 고민하고 다듬어낸 것이 바로 indiego 웹 서비스입니다.
</br>


## 🔥 indiego 목표
- 우리 주변에는 취미로 음악과 연극 등을 하거나 이를 꿈꾸는 사람들이 많으며, 이를 즐기는 사람들이 많습니다.
- 문화 컨텐츠를 즐길 수 있는 곳은 일부 지역으로 국한되어 있으며, 기회는 부족하고, 환경은 열악합니다.
- 공연을 꿈꾸는 사람들에게 인지도를 쌓을 수 있는 경험과 수익창출의 기회를 제공하고자 합니다.
- 문화 컨텐츠를 즐기는 사람들에게 잊지 못할 추억과 경험을 제공하고자 합니다.
- indiego 서비스는 부족한 지역 문화 컨텐츠를 증진시키고, 남녀노소 누구나 퍼포머가 되어 공연하고 이를 즐길 수 있는 플랫폼이 되는 것을 목표로 합니다.
- 마이너에서 메이저로! 자신만의 퍼포먼스를 발휘할 수 있는 곳이 바로 indiego입니다.
</br>



## 🗓️ 프로젝트 기간
- 2023.01.03 ~ 2023.02.03
</br>

## 📚 문서
- 
</br>

## 📌 기술 스택 및 아키텍처

![아키텍처](https://user-images.githubusercontent.com/80394894/215329355-ef124266-72e1-44b4-8af3-c90261fb987d.PNG)

</br>
</br>

## 📓 ERD

![인디고 erd 다이어그램](https://user-images.githubusercontent.com/80394894/215329542-fdfa3b2e-a627-4427-a68f-9cc50e2274dc.PNG)

</br>
</br>

## 📚 UserFlow
### 비회원(User)
<img width="1888" alt="userflow-User" src="https://user-images.githubusercontent.com/80394894/215343144-0cbd0ed3-e980-43b7-ad21-e0a4844a8794.png">

### 회원(Member)
<img width="2224" alt="userflow-Member" src="https://user-images.githubusercontent.com/80394894/215343162-e947cca2-b63a-4fd4-987e-98976c6b2fb1.png">

### 퍼포머(Performer)
<img width="2240" alt="userflow-Performer" src="https://user-images.githubusercontent.com/80394894/215343177-c9ce7969-88f3-47e1-b65f-f35cc09dedae.png">
</br>

## ✨ 서비스 구현
### 회원(User, Performer)
 - Create : 멤버 회원가입
 - Read : 회원은 프로필 조회 가능
 - Update : 회원은 프로필 수정 가능
 - Delete : 회원은 프로필 삭제 가능

### 게시글(Article)
 - Create : 회원은 질문 작성 가능
 - Read : 회원/비회원 질문 조회 가능 & 게시글 검색 가능
 - Update : 회원은 게시글 수정 가능
 - Delete : 회원은 게시글 삭제 가능

### 공연(Show)
 - Create : 회원은 답변 작성 가능
 - Read : 회원/비회원 답변 조회 가능
 - Update : 회원은 답변 수정 가능 & 질문 작성자는 답변 채택 가능
 - Delete : 회원은 답변 삭제 가능

</br>

## 🖥️ 서비스 화면

|||
|:---:|:---:|
|**메인 페이지**|**로그인 / 회원가입 페이지**|
|<img width="100%" src=""/>|<img width="100%" src=""/>|
|**구글 OAuth2 인증**|**프로필 관리**|
|<img width="100%" src=""/>|<img width="100%" src=""/>|
|**질문 게시글 작성**|**게시글 조회,답변**|
|<img width="100%" src=""/>|<img width="100%" src=""/>|
|**게시글 답변 투표(추천)기능**|**USER & TAG 페이지**|
|<img width="100%" src=""/>|<img width="100%" src=""/>|
