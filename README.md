# Portfolio
## About me 
### 이름(닉네임) : 강형민(HyungMinKang, 히데) 
안녕하세요! 신입 안드로이드 앱 개발자 히데입니다.
항상 **최신 기술에 관심**을 가지고, 이를 프로젝트에 적용해보며 **흥미를 느낍니다.**
최근에는 **클린 코드** 작성, **코드 리팩토링**에 대하여 매번 고민해보고 있습니다.

**새로운 것을 꾸준히 익히고 배움에 있어 두려움을 가지지 않는 것이 제 장점**이라고 생각합니다.
또한, **원하는 결과가 눈에 보일 때까지 삽질하고 매달리는 끈기와 열정**또한 **누구보다 자신**있습니다  


### 기술블로그 링크: [TechBlog](https://medium.com/@ramkid91)  

***********************************************************

## My Skill
 -	아키텍처 패턴 
    -	MVP, MVVM
 -	네트워크 처리
    -	Retrofit, Okhttp3 
 -	JSON 직렬화, 역직렬화
    -	Gson
    -	Moshi
 -	이미지 로딩 라이브러리
    -	Glide, Coil,  Picasso, Fresco 
 -	비동기 프로그래밍
    -	Coroutine,  Coroutine Exception Handling  
    -	Flow 
-	UI
    -	ViewPager2
    -	Jetpack Compose
    -	Jetpack Navigation
    - Recycler View, List View
-	Dependency Injection
    -	Koin,  Hilt
-	DB 
    -	SQLite 
    - Room



***********************************************************

# 대표프로젝트
## 반찬 주문 서비스 프로젝트
#### 프로젝트 기간:  2022/04/18- 2022/04/29 
#### [프로젝트 소개& 저장소](https://github.com/HyungMinKang/sidedish)

## 🖥 주요 화면
<img src="https://user-images.githubusercontent.com/58967292/165438941-767c870e-e5d2-455e-965b-150f9d91fe7c.gif" width="400" height="500">

## 역할 
  -  의존성 주입 구현 
  -  서버 API 연동 후 네트워크 응답구조 설계
  -  이미지 스와이프 뷰 처리  
  -  비동기 예외 처리
  -  다운로드 이미지 캐싱 처리 
  -  로그인 구현 


## 기술 
  - LiveData 
  - DI framework : Hilt 
  - Glide 
  - Google Auth
  - LRU Cache
  - ViewPager2
  - Internal Storage , Cache Direcotry

## 배웠던점
  - Viewtype으로 리사이클러뷰의 헤더와 아이템(콘텐츠) 를 분리해서 표현하는 법
  - 이미지 로딩 라이브러리의 캐싱 로직
  - 메모리캐시, 디스크 캐시의 차이&  직접 구현하는 방법
  - 서버없이 로그인 과정을 진행하는 방법

## 아쉬웠던 점
  - 커스텀하게 구현한 캐싱로직을 앱의 모든 이미지 로딩 로직에는 적용하지 못한점
  - 서버를 통한 OAuth 로그인 과정을 진행하지 못한점
  - 다양한 기기별 UI 테스트를 진행하지 못한점 

***********************************************************
## 에어비앤비 클론 프로젝트
#### 프로젝트 기간 : 2022/05/23 ~ 2022/06/10 
#### [프로젝트 소개&저장소](https://github.com/HyungMinKang/airbnb)

## 🖥 주요 화면

![res2-min](https://user-images.githubusercontent.com/58967292/173248788-d0448987-7796-4463-9fc1-b9f98a4defcb.gif)

## 역할
-  의존성 주입 구현 
-  서버 API 연동 후 네트워크 응답구조 설계
-  화면 이동 구조 설계
-  커스텀 달력 구현 
-  Xml + Jetpack Compose 혼합하는 형태의 UI 구현 
-  로그인 기능 구현
-  화면간 데이터 공유 설계
-  커스텀 마커 구현 
-  가격 선택 범위 그래프 구현 
-  지도뷰 구현
-  무한 스크롤 구현 
-  숙소의 주소 정보를 위치정보로 변환해 지도에 마커 형태로 표현 
-  협업
  -  브랜치 전략 수립,  깃헙 이슈를 통해 작업 분할  

## 기술 
-  LiveData, Flow 
-  DI framework : Koin 
-  Glide
-  SharedViewModel
    -  Custom View 
    -  Jetpack Compose , State hoisting 
    -  WebView

## 배웠던 점
 - MVVM에서 UI Layer에서만 다루는 데이터에 대한 처리
 - Activity+ 여러 Fragments로 화면 구성시 SharedViewModel에서 처리할 데이터와 각 Fragment별 ViewModel에서 처리해야 할 데이터에 대한 고민
 - 라이브러리 없이 커스텀하게 리사이클러뷰의 무한 스크롤을 정의하는 법
 - 중복되는 UI 구조를 가진 화면에 대해 기존 화면을 재활용할지 새로운 화면을 만들고 View만 재활용한지에 대한 고민

## 아쉬웠던 점
 - 불충분한 네트워크 예외처리
 - 지도 뷰에서 화면 이동시 보여주는 데이터도 갱신되는 로직을 적용하지 못한점 
 - API 완성 기간의 문제로 API를 적용하지 못한 화면이 많음 

***********************************************************
## 스타벅스 클론 프로젝트
#### 프로젝트 기간 : 2022/05/9 ~ 2022/05/20 
#### [프로젝트 소개&저장소](https://github.com/HyungMinKang/kotlin-starbucks)

## 🖥 주요 화면
![image](https://user-images.githubusercontent.com/58967292/174077518-204bd678-5311-48ca-b8e1-13584cbd8fb5.png)
![image](https://user-images.githubusercontent.com/58967292/174077609-d181886c-e3d3-44f9-8a8c-7cd081334012.png)
![image](https://user-images.githubusercontent.com/58967292/174077678-d773699b-2750-49c0-aa53-b8f20209ec10.png)
![image](https://user-images.githubusercontent.com/58967292/174077732-7b421bf3-f591-4c1e-9f75-398ab97225fe.png)
![image](https://user-images.githubusercontent.com/58967292/174077830-a77f61fd-60bc-4e0f-abcc-7042d9a90866.png)
![i![image](https://user-images.githubusercontent.com/58967292/174078169-bc1580b9-519d-4f06-9d5e-1da2314018fd.png)

## 역할
-  기술 이전 담당 : UI 관련 데이터를 LiveData에서 Flow로 전환 
-  의존성 주입 구현 
-  로컬 저장소에 즐겨찾기 메뉴 데이터 저장 구현
-  서버 API 연동 후 네트워크 응답구조 설계
-  화면 이동 구조 설계
-  주문 알림 처리 구현 
-  즐겨찾기 버튼 이벤트 핸들링 구현 

## 기술 
- LiveData, Flow 
- DI framework : Koin 
- Coil
    - Room Database, Shared Preference
    - Alrarm Manger, Notification


## 배웠던 점
 - Android Studio의 Profiler을 통해 이미지 로딩 라이브러리별 메모리 사용량 차이 비교와 라이브러리 선택 기준 
 - 로컬저장소에 데이터를 저장,관리하는 법 학습
 - Android Background Task처리에 대한 방법 학습
 
## 아쉬웠던 점
 - ML+Vision API를 이용한 지폐인식 화면 구현하지 못한 점
 - AlarmManager을 통한 주문처리 과정에서 PendingIntent을 통해 주문완료 화면으로 이동하는 로직을 구현하지 못한점


