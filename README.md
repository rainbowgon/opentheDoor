<img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/banner.jpg?raw=true">

## 🍇 프로젝트 바로가기

📌 <a href="https://github.com/rainbowgon/opentheDoor-frontend">프론트엔드 바로가기</a>
<br>
📌 <a href="https://github.com/rainbowgon/opentheDoor-backend">백엔드 바로가기</a>
<br>
📌 <a href="https://github.com/rainbowgon/opentheDoor-crawling">크롤링 서버 바로가기</a>
<br>
📌 <a href="https://github.com/rainbowgon/opentheDoor-reserving">예약 서버 바로가기</a>

## 🍇 프로젝트 소개

**방탈출 카페 정보 제공 및 예약 플랫폼, 오픈더도어**

방탈출 예약을 해본 적이 있으신가요? 방탈출 시장은 점점 커지고 있지만 현재 방탈출 플랫폼은 필요한 기능을 제공하지 못하고 있습니다. `오픈더도어`는 사용자들에게 편리한 검색, 예약 대기 및 빈자리 알림, 플랫폼 내에서의 예약을 제공합니다. 방탈출 플랫폼을 통해 방탈출 업체와 사용자들 모두에게 도움이 되고자 합니다.

**기획 배경**

- 방탈출 검색 결과를 지도에서 볼 수 없어서 지도 앱을 번갈아 가면서 사용해야 함
- 플랫폼에 예약 기능이 없어서 각기 다른 자체 사이트에서 예약을 진행해야 함
- 자체 사이트들은 제대로 된 예약 시스템을 갖추고 있지 않아 티켓팅을 놓친다면 빈자리가 났는지 수시로 들어가서 확인해야 함

**서비스 의도**

- 방탈출 플랫폼 최초로 예약 기능 제공. 사용자가 방탈출 검색부터 예약까지의 모든 시퀀스를 플랫폼 안에서 할 수 있도록 함. 방탈출 내역 관리 및 개인화된 추천을 제공할 수 있음.
- 예약 대기 및 빈자리 알림 기능을 제공. 사용자들은 티켓팅을 놓쳐도 이후에 예약할 수 있으며 방탈출 업체들은 공실로 인한 피해를 줄일 수 있음

**진행 일정**

- 개발 기간 : 2023.10.10 ~ 2023.11.19
- 배포 기간 : 2023.11.06 ~ 2023.11.27

## 🍇 프로젝트 주요 기능

### 메인 화면

> 메인 화면에서는 검색, 주차별 테마 랭킹, 내 주변 테마 정보, 북마크 한 테마 정보를 확인할 수 있습니다.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/main.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/main_search.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/main_kakao_login.gif?raw=true" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <span>메인 화면</span>
    </td>
    <td align="center">
      <span>메인 화면 검색</span>
    </td>
    <td align="center">
      <span>카카오 로그인</span>
    </td>
  </tr>
</table>

### 인기 테마

> 주차별 인기 테마를 확인할 수 있습니다. <br>
> 인기 테마 순위는 한 주 간의 조회수, 북마크 수, 리뷰 수, 평점을 고려하여 산정됩니다.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/poppular_theme.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/poppular_theme_detail.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/dummy.gif?raw=true" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <span>인기 테마 둘러보기</span>
    </td>
    <td align="center">
      <span>인기 테마 상세 보기</span>
    </td>
    <td align="center">
      <span>-</span>
    </td>
  </tr>
</table>

### 검색 및 지도

> 사용자가 입력한 검색어가 방탈출카페 지점명, 테마명, 지명, 장르, 테마 설명에 포함된 테마들이 검색 결과로 보여집니다. <br>
> 검색 결과에 대해 테마 권장 인원과 지역으로 필터링 할 수 있고, 추천순, 북마크 많은 순, 리뷰 많은 순, 가까운 순, 예약 시간 빠른 순으로 정렬할 수 있습니다. <br>
> 검색 결과는 리스트와 지도로 확인할 수 있습니다.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/search_map_nearby.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/search_map_detail.gif?raw=true" />
    </td>
     <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/search_infinity_scroll.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/search_filtering.gif?raw=true" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <span>지도에서 현재 위치 주변 검색</span>
    </td>
    <td align="center">
      <span>지도에서 디테일 확인</span>
    </td>
    <td align="center">
      <span>리스트 보기</span>
    </td>
    <td align="center">
      <span>검색 필터링</span>
    </td>
  </tr>
</table>

### 테마 상세 및 리뷰 기능

> 테마 상세 화면에서는 테마에 대한 기본적인 정보(지점명, 테마명, 위치, 장르, 테마 설명, 금액 등)가 제공됩니다. <br>
> 예약 가능한 날짜와 실시간 시간 정보를 볼 수 있고, 테마(지점) 위치를 지도로 확인할 수 있습니다. <br>
> 리뷰에서는 사용자들이 남긴 평점, 탈출 여부, 사용한 힌트 수, 방탈출 한 날짜/시간/인원 정보, 주관적 난이도 등을 확인할 수 있습니다. <br>
> 비회원인 경우에는 리뷰가 1개만 보여지고, 회원인 경우 전체 리뷰를 볼 수 있습니다.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/theme_detail.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/review_member.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/review_not_member.gif?raw=true" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <span>테마 상세 보기</span>
    </td>
    <td align="center">
      <span>회원 리뷰 보기</span>
    </td>
    <td align="center">
      <span>비회원 리뷰 보기</span>
    </td>
  </tr>
</table>

### 예약 기능

> 서비스 내에서 원하는 날짜와 시간, 인원을 선택하여 방탈출을 예약할 수 있습니다. <br>
> 회원인 경우에는 회원 가입 시 입력한 이름, 전화번호로 예약이 진행되며, 비회원인 경우에는 직접 입력한 이름과 인증받은 전화번호로 예약이 진행됩니다. <br>
> 예약 완료 시, 앱 푸시 알림을 통해 예약 성공을 확인할 수 있습니다. <br>
> 다른 사용자가 먼저 예약해서 예약이 불가한 테마에 예약 대기를 걸어두면, 빈자리가 났을 때 빈자리 알림을 받아볼 수 있습니다. <br>
> 또한, 북마크해둔 테마 예약이 오픈되기 10분 전에 알림이 전송됩니다.

<table>
  <tr>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/reservation.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/reservation_fcm.gif?raw=true" />
    </td>
    <td align="center">
      <img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/gif/reservation_alarm_list.gif?raw=true" />
    </td>
  </tr>
  <tr>
    <td align="center">
      <span>예약 시간 확인하기</span>
    </td>
    <td align="center">
      <span>예약하기</span>
    </td>
    <td align="center">
      <span>알림 리스트</span>
    </td>
  </tr>
</table>

## 🍇 폴더 트리

- Frontend

```
 📂android
 ┣ 📂app
 ┃ ┣ 📂src
 ┃ ┃ ┣ 📂debug
 ┃ ┃ ┣ 📂main
 ┃ ┃ ┃ ┣ 📂assets
 ┃ ┃ ┃ ┣ 📂java
 ┃ ┃ ┃ ┣ 📂res
 ┃ ┃ ┗ 📂release
 ┗ 📂gradle
 📂apis
 📂assets
 ┣ 📂icons
 ┗ 📂images
 📂components
 ┣ 📂BarGraph
 ┃ ┣ 📂components
 ┃ ┃ ┗ 📂BarGraphItem
 ┣ 📂BottomNavigator
 ┣ 📂Button
 ┣ 📂Calendar
 ┣ 📂CheckBox
 ┣ 📂Dropdown
 ┣ 📂EscapeInfo
 ┣ 📂Fab
 ┣ 📂GeolocationAPI
 ┣ 📂Header
 ┣ 📂InfoCard
 ┣ 📂Input
 ┣ 📂ListItem
 ┣ 📂Maps
 ┃ ┣ 📂MyLocationMarker
 ┣ 📂MiniInfoCard
 ┣ 📂Review
 ┣ 📂StarRating
 ┗ 📂_admin
 ┃ ┣ 📂_AdminAxiosTestBox
 ┃ ┗ 📂_AdminRightNavigation
 📂constants
 📂ios
 ┣ 📂OpenTheDoor
 ┃ ┗ 📂Images.xcassets
 ┣ 📂OpenTheDoor.xcodeproj
 ┗ 📂OpenTheDoorTests
 📂recoil
 ┣ 📂alarm
 ┣ 📂map
 ┣ 📂member
 ┣ 📂reservation
 ┣ 📂review
 ┣ 📂search
 ┣ 📂selector
 ┣ 📂state
 ┗ 📂theme
 📂screens
 ┣ 📂AlarmScreen
 ┣ 📂BookmarkListScreen
 ┣ 📂CompareThemeScreen
 ┣ 📂HomeScreen
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📂BookmarkedTheme
 ┃ ┃ ┣ 📂HomeTitle
 ┃ ┃ ┣ 📂InputHeadline
 ┃ ┃ ┣ 📂NearByTheme
 ┃ ┃ ┣ 📂RenderThemeItem
 ┃ ┃ ┗ 📂WeeklyTheme
 ┣ 📂KakaoLoginScreen
 ┣ 📂LoginScreen
 ┣ 📂MypageScreen
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📂MypageLogin
 ┃ ┃ ┣ 📂NonUserFeatureList
 ┃ ┃ ┣ 📂ReservationInfo
 ┃ ┃ ┣ 📂UserFeatureList
 ┃ ┃ ┗ 📂UserProfile
 ┣ 📂ProfileUpdateScreen
 ┣ 📂RankingScreen
 ┣ 📂RecordScreen
 ┣ 📂ReservationListScreen
 ┣ 📂ReservationScreen
 ┣ 📂ReservationWaitingScreen
 ┣ 📂ReviewScreen
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📂BackgroundImg
 ┃ ┃ ┣ 📂DifficultySlider
 ┃ ┃ ┣ 📂ReviewBody
 ┃ ┃ ┣ 📂ReviewContent
 ┃ ┃ ┣ 📂ReviewTitle
 ┃ ┃ ┗ 📂UseHint
 ┣ 📂SearchScreen
 ┃ ┣ 📂components
 ┃ ┃ ┗ 📂SearchScreenMap
 ┣ 📂SettingScreen
 ┣ 📂SignUpScreen
 ┣ 📂ThemeDetailScreen
 ┃ ┣ 📂components
 ┃ ┃ ┣ 📂EscapeInfoView
 ┃ ┃ ┃ ┣ 📂components
 ┃ ┃ ┃ ┃ ┗ 📂EscapeCharacterItem
 ┃ ┃ ┣ 📂MyReview
 ┃ ┃ ┣ 📂ThemeStarRate
 ┃ ┃ ┗ 📂ThemeTitleContent
 📂storage
 📂styles
 📜App.tsx
```

- Backend

```
📂apigateway-server
┣ 📂src
┃ ┣ 📂main
┃ ┃ ┣ 📂java
┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┗ 📂rainbowgon
┃ ┃ ┃ ┃ ┃ ┗ 📂apigatewayserver
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂config
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂error
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂filter
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂redis
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂security
📂config-server
┣ 📂src
┃ ┣ 📂main
┃ ┃ ┃ ┗ 📂java
┃ ┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┃ ┗ 📂rainbowgon
┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂configserver
┣ 📂eureka-server
┃ ┣ 📂src
┃ ┃ ┣ 📂main
┃ ┃ ┃ ┣ 📂java
┃ ┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┃ ┗ 📂rainbowgon
┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂eurekaserver
📂member-service
┣ 📂src
┃ ┣ 📂main
┃ ┃ ┣ 📂java
┃ ┃ ┃ ┣ 📂com
┃ ┃ ┃ ┃ ┗ 📂rainbowgon
┃ ┃ ┃ ┃ ┃ ┗ 📂memberservice
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂domain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂bookmark
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂controller
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂request
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂response
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂service
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂member
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂oauth
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂profile
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂review
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂global
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂client
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂input
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂output
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂config
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂entity
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂error
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂errorCode
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂exception
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂jwt
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂redis
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂response
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂util
📂notification-service
┣ 📂src
┃ ┣ 📂main
┃ ┃ ┣ 📂java
┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┗ 📂rainbowgon
┃ ┃ ┃ ┃ ┃ ┗ 📂notificationservice
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂domain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂kafka
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂dto
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂output
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂service
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂notification
┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂global
📂reservation-service
┣ 📂src
┃ ┣ 📂main
┃ ┃ ┣ 📂java
┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┗ 📂rainbowgon
┃ ┃ ┃ ┃ ┃ ┗ 📂reservationservice
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂domain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂reservation
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂timeline
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂waiting
┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂global
📂search-service
┣ 📂src
┃ ┣ 📂main
┃ ┃ ┣ 📂java
┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┗ 📂rainbowgon
┃ ┃ ┃ ┃ ┃ ┗ 📂searchservice
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂domain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂theme
┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂global
📂sender-server
┣ 📂src
┃ ┣ 📂main
┃ ┃ ┣ 📂java
┃ ┃ ┃ ┗ 📂com
┃ ┃ ┃ ┃ ┗ 📂rainbowgon
┃ ┃ ┃ ┃ ┃ ┗ 📂senderserver
┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂domain
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂fcm
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┣ 📂kafka
┃ ┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂sender
┃ ┃ ┃ ┃ ┃ ┃ ┗ 📂global
```

## 🍇 시스템 아키텍처

<img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/infra.jpg?raw=true">

## 🍇 ERD

<img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/erd.png?raw=true">

## 🍇 API 명세서

<img src="https://github.com/rainbowgon/opentheDoor/blob/main/upload/api.gif?raw=true">

## 🍇 기술 스택

<h3 align="center">Frontend</h3>
<p align="center">
    <img src="https://img.shields.io/badge/Yarn-2C8EBB?&logo=yarn&logoColor=white">
    <img src="https://img.shields.io/badge/TypeScript-3178C6?&logo=typescript&logoColor=white">
    <img src="https://img.shields.io/badge/Node.js-339933?&logo=nodedotjs&logoColor=white">
    <img src="https://img.shields.io/badge/React Native-61DAFB?&logo=react&logoColor=white">
    <img src="https://img.shields.io/badge/Android Studio-3DDC84?&logo=androidstudio&logoColor=white">
    <br>
    <img src="https://img.shields.io/badge/Recoil-3578E5?&logo=recoil&logoColor=white">
    <img src="https://img.shields.io/badge/axios-5A29E4?&logo=axios&logoColor=white">
    <img src="https://img.shields.io/badge/ESLint-4B32C3?&logo=eslint&logoColor=white">
    <img src="https://img.shields.io/badge/Prettier-F7B93E?&logo=prettier&logoColor=white">
    <img src="https://img.shields.io/badge/styledcomponents-DB7093?&logo=styledcomponents&logoColor=white">
    <img src="https://img.shields.io/badge/googlemaps-4285F4?&logo=googlemaps&logoColor=white">
</p>

<h3 align="center">Backend</h3>
<p align="center">
    <img src="https://img.shields.io/badge/Java-007396?&logo=java&logoColor=white">
    <img src="https://img.shields.io/badge/Spring Boot-6DB33F?&logo=springboot&logoColor=white">
    <img src="https://img.shields.io/badge/Spring Cloud-6DB33F?&logo=springboot&logoColor=white">
    <img src="https://img.shields.io/badge/Gradle-02303A?&logo=gradle&logoColor=white">
    <img src="https://img.shields.io/badge/Hibernate-59666C?&logo=hibernate&logoColor=white">
    <img src="https://img.shields.io/badge/Spring Security-6DB33F?&logo=springsecurity&logoColor=white">
    <img src="https://img.shields.io/badge/JWT-000000?&logo=jsonwebtokens&logoColor=white">
    <br>
    <img src="https://img.shields.io/badge/JavaScript-F7DF1E?&logo=javascript&logoColor=white">
    <img src="https://img.shields.io/badge/Node.js-339933?&logo=nodedotjs&logoColor=white">
    <img src="https://img.shields.io/badge/Express-000000?&logo=express&logoColor=white">
    <img src="https://img.shields.io/badge/Puppeteer-40B5A4?&logo=puppeteer&logoColor=white">
    <br>
    <img src="https://img.shields.io/badge/Firebase-FFCA28?&logo=firebase&logoColor=white">
    <img src="https://img.shields.io/badge/Apache Kafka-231F20?&logo=apachekafka&logoColor=white">
    <br>
    <img src="https://img.shields.io/badge/MySQL-4479A1?&logo=mysql&logoColor=white">
    <img src="https://img.shields.io/badge/H2-FF9900?&logo=h2&logoColor=white">
    <img src="https://img.shields.io/badge/Redis-DC382D?&logo=redis&logoColor=white">
    <img src="https://img.shields.io/badge/MongoDB-47A248?&logo=mongodb&logoColor=white">
    <img src="https://img.shields.io/badge/Elasticsearch-005571?&logo=elasticsearch&logoColor=white">
    <img src="https://img.shields.io/badge/Kibana-005571?&logo=kibana&logoColor=white">
</p>

<h3 align="center">Infra</h3>
<p align="center">
    <img src="https://img.shields.io/badge/GitHub Actions-2088FF?&logo=githubactions&logoColor=white">
    <img src="https://img.shields.io/badge/Jenkins-D24939?&logo=jenkins&logoColor=white">
    <img src="https://img.shields.io/badge/Docker-2496ED?&logo=docker&logoColor=white">
    <br>
    <img src="https://img.shields.io/badge/Ubuntu-E95420?&logo=ubuntu&logoColor=white">
    <img src="https://img.shields.io/badge/AWS EC2-FF9900?&logo=amazon ec2&logoColor=white">
    <img src="https://img.shields.io/badge/AWS CloudWatch-FF4F8B?&logo=amazoncloudwatch&logoColor=white">
    <img src="https://img.shields.io/badge/AWS RDS-527FFF?&logo=amazonrds&logoColor=white">
    <img src="https://img.shields.io/badge/AWS S3-569A31?&logo=amazons3&logoColor=white">
</p>

<h3 align="center">Co-work tool</h3>
<p align="center">
    <img src="https://img.shields.io/badge/GitHub-181717?&logo=github&logoColor=white">
    <img src="https://img.shields.io/badge/Notion-000000?&logo=Notion&logoColor=white">
    <img src="https://img.shields.io/badge/Jira-0052CC?&logo=Jira Software&logoColor=white">
    <img src="https://img.shields.io/badge/Postman-FF6C37?&logo=Postman&logoColor=white">
    <img src="https://img.shields.io/badge/Figma-F24E1E?&logo=Figma&logoColor=white">
    <img src="https://img.shields.io/badge/Mattermost-0058CC?&logo=Mattermost&logoColor=white">
    <img src="https://img.shields.io/badge/Discord-5865F2?&logo=discord&logoColor=white">
</p>

## 🍇 멤버

<table>
  <tr>
   <td align="center">
      <a href="https://github.com/Gobro-s">
        <img src="https://github.com/Gobro-s.png" width="400" alt="고세훈" />
      </a>
    </td>
     <td align="center">
      <a href="https://github.com/Byungul">
        <img src="https://github.com/Byungul.png" width="400" alt="변정원" />
      </a>
    </td>
     <td align="center">
      <a href="https://github.com/chogoal">
        <img src="https://github.com/chogoal.png" width="400" alt="최해미" />
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/usedupnote">
        <img src="https://github.com/usedupnote.png" width="400" alt="이정명" />
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/nutbrown">
        <img src="https://github.com/nutbrown.png" width="400" alt="전혜련" />
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/ng-lee">
        <img src="https://github.com/ng-lee.png" width="400" alt="이남곤" />
      </a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <a href="https://github.com/Gobro-s">
        <b>고세훈</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/Byungul">
        <b>변정원</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/chogoal">
        <b>최해미</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/usedupnote">
        <b>이정명</b>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/nutbrown">
        <b>전혜련</b>
      </a>
    </td>
     <td align="center">
      <a href="https://github.com/ng-lee">
        <b>이남곤</b>
      </a>
    </td>
  </tr>
    <td align="center">
      <span>Frontend</span>
    </td>
    <td align="center">
      <span>Backend<br>검색팀</span>
    </td>
    <td align="center">
      <span>Backend<br>회원팀</span>
    </td>
    <td align="center">
      <span>Frontend</span>
    </td>
    <td align="center">
      <span>Backend<br>알림팀</span>
    </td>
    <td align="center">
      <span>Backend<br>예약팀<br>INFRA</span>
    </td>
  </tr>
</table>
