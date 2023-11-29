# KAMINARI

## Team Members (구성원)
<table>
  <tbody>
    <tr>
     <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/suzzang98">
       <img src="https://avatars.githubusercontent.com/u/114126053?v=4" width="100px;" alt="이수현"/>
       <br />
         <sub>
           <b>이수현</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
     </td>
    <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/jakkujakku">
       <img src="https://avatars.githubusercontent.com/u/89556301?v=4" width="100px;" alt="김준우"/>
       <br />
         <sub>
           <b>김준우</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
     </td>
      <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/KangJiHun1028">
       <img src="https://avatars.githubusercontent.com/u/136081642?v=4" width="100px;" alt="강지훈"/>
       <br />
         <sub>
           <b>강지훈</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
     </td>
      <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/BoKyeongee/">
       <img src="https://avatars.githubusercontent.com/u/124825477?v=4" width="100px;" alt="남보경"/>
       <br />
         <sub>
           <b>남보경</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
     </td>
     <td align="center" valign="top" width="14.28%">
       <a href="https://github.com/YoungDuck1592">
       <img src="https://avatars.githubusercontent.com/u/139099626?v=4" width="100px;" alt="서영덕"/>
       <br />
         <sub>
           <b>서영덕</b>
         </sub>
       </a>
       <br />
       <sub>
           <b>iOS Developer</b>
       </sub>
       <br />
     </td>
  </tbody>
</table>

## 프로젝트 기간 
- 2023.09.25 - 2023.10.06 (2주간)

## 프로젝트 소개
"Kaminari 앱 만들기"<p> 
이 프로젝트는 Swift 언어를 사용하여 Xcode에서 개발한 애플리케이션입니다. <br>
이 앱은 WeatherKit을 활용하여 만든 날씨 애플리케이션입니다. 사용자는 현재 날씨 및 시간/주간/전국 날씨를 조 할 수 있으며, 다양한 기능과 사용자 경험을 제공합니다.
1. **현재 날시 화면**: 현재 위치의 도시와 온도 및 12시간 동안의 날씨 예보와 다양한 상세정보를 확인 할 수 있습니다.
2. **주간 날씨 화면**: 지금 현재 위치의 최저/최고 온도를 알 수 있습니다.
3. **지역 검색 화면**: 지역명으로 검색하여, 다른 지역의 날씨를 확인할 수 있습니다.
4. **전국 날씨 화면**: 전국의 날씨를 확인할 수 있습니다.
5. **상세 화면**: 주간 날씨페이지에서 해당 요일의 날씨정보를 확인할 수 있습니다.
<br>

## 역할분담 및 프로젝트 주요기능 
* [TEAM S.A][https://www.notion.so/16-SIXTEEN-a3a97b10a62e4c668fa92e69d4403f31]
- 이수현 : 주말 예보 페이지
- 김준우 : 현재 날씨 페이지
- 강지훈 : 전국 날씨 페이지

  
   <img src="https://velog.velcdn.com/images/jakkujakku98/post/02898b8f-4bbd-4bc4-8622-6e23725d1858/image.png" width="20%"/>

   
  -현재 전국의 날씨를 심볼 및 기온으로 확인 할 수 있습니다.
- 남보경 : 검색 페이지
- 서영덕 : 상세 페이지


##  팀 규칙
```text
1. 아래의 Git Convention 지켜서 commit과 PR 요청하기! 
ex) git commit -m "[FEAT] : Hello_World"
2. 스크럼: 오전 9시 30분 / 오후 8시 30분
3. 자리비울 때 말해주기
4. 이슈 질문하기
```
## 구현 요구 사항
- 필수 구현 기능(필수)
    - [✅]  사용자 위치 지정
    - [✅]  날씨 데이터
    - [✅]  사용자 입력 (SearchPage)
    - [✅]  날씨 표시
    - [✅]  단위 변환 (SearchPage)
    - [✅]  사용자 친화적인 인터페이스
    - [✅]  데이터 새로 고침
    - [✅]  배경 이미지
    
- 추가 구현 기능(선택)
    - [✅]  알림
    - [✅]  예보 (1시간별, 9일)
    - [✅]  위치 서비스
    - [✅]  지도 통합
    - [✅]  검색 기록
    - [✅]  애니메이션
    - [❌]  디자인 패턴 (MVVM)
    
- **GIT**
    - [✅]  git add / commit / push 활용
    - [✅]  git 브랜치/ PR / merge 활용
    - [✅]  github pull request에서 Code review 활용

## 와이어프레임
  <table>
    <tr>
      <td>
        <img src="https://velog.velcdn.com/images/jakkujakku98/post/59efac5e-06ae-4c85-826e-18e781f9372e/image.png"/>
      </td>
      <td>
        <img src="https://velog.velcdn.com/images/jakkujakku98/post/d544c728-f940-4027-b8ea-1f15c7a107f6/image.png"/>
      </td>
      <td>
        <img src="https://velog.velcdn.com/images/jakkujakku98/post/13162af3-2427-412e-9570-403b556caff5/image.png"/>
      </td>
      <td>
        <img src="https://velog.velcdn.com/images/jakkujakku98/post/02898b8f-4bbd-4bc4-8622-6e23725d1858/image.png"/>
      </td>
      <td>
        <img src="https://velog.velcdn.com/images/jakkujakku98/post/6f67f440-619c-4138-8532-b9bce92c10bf/image.png"/>
      </td>
    </tr>
  </table>

## App Flow Chart
<table>
    <tr>
      <td>
        <img src="https://velog.velcdn.com/images/jakkujakku98/post/afda970e-a141-4b60-a131-b74fde84eef8/image.png"/>
      </td>
    </tr>
  </table>

## YOUTUBE 시연영상
<img src="https://velog.velcdn.com/images/jakkujakku98/post/40a456dd-63ab-4460-ba34-2190c62cbef0/image.png" width="20%">(https://youtu.be/Z4SgQ-Mw0s8)

## 사용한 Library
```text
WeatherKit
MapKit
Snapkit
MultiSliderBar
Gifu
Then
```

## 추후 보완하거나 시도해보고 싶은 Point
- 현재 날씨 페이지 : 섭씨 / 화씨 변경 버튼 추가
- 주간 날씨 페이지 : 새로고침 리로드 
- 전국 날씨 페이지 : AnnotationView 커스텀 추가
- 검색 페이지 
    - UI를 통일화 하는 작업
디테일 적인 아쉬움
지역 표시 기준이 달라서 화면마다 표시되는 값이 달라지는 부분이 종종 발생.
    - 화면 주기에 맞춰서 데이터 추가 후 UI가 바로 나타나게 해야하는데 SearchController로 들어갔다가 나올 때 해당 주기를 고려하기 어려워서 아쉬운 부분이 있음.
    - 레퍼런스 참고 혹은 과제 구현 조건 외에 사용자에게 필요할 기능을 고려해서 추가해보고 싶음.
화면이 그려지는 데 시간이 걸려서 뒤늦게 그려지는 부분이 종종 발견되는데 이를 개선하고 싶음.


## 구현하기 힘들었거나, 구현할 때 고민하였던 부분
- 현재 날씨 페이지 : UI 구성 고민
- 주간 날씨 페이지 : 날씨 업데이트 & 슬라이더바 그라데이션 
- 전국 날씨 페이지 : AnnotationView에 아이콘 & 심볼 표현
- 검색 페이지 
    - 지역명 자동 완성 시 초반에 도시명으로만 검색 가능하도록 설정한 경우 도시 내에서 서로 다른 날씨가 확인 불가능 했음. 특히 국내에서는 수도권은 시 단위보다는 구단위로 생활권이 많이 나뉘기 때문에 바꿔야한다는 생각이 컸음. 
    - placemark.locality 보다는 placemark.name을 활용해서 도시 보다는 구, 시, 도, 주, 국가 등 여러 단위를 사용할 수 있도록 변경함.
