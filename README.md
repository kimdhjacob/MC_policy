# MODOOCLASS. GUIDE

#### **노하우** 를 배우고 나누는 클래스 마켓 

#### 언제 어디서나 함께 하는 즐거움. 





## **개 요**

>  **모두의 클래스**는 누구나 코치(선생님)가 될 수 있는 온라인 클래스 플랫폼(웹/앱) 서비스로 
>  클래스 완강을 위한 사람과 사람의 연결 | 동기부여에 가치를 두고 있다. 
>
>  해당 문서는 내부 가이드 문서로서 팀원간 원활한 소통과 서비스 정책을 공유 하기 위함이다.
>
>  *총 4개의 문서로 구성*
>
>  - [#1.서비스](## #1.서비스) - `개발팀`
>  - [#2.컨텐츠](contents) - `컨텐츠팀`
>  - [#3.마케팅](marketing) - `마케팅팀`
>  - [#4.정책문서](policy) - `전체관리`
>
>  각 문서는 팀별로 관리 되며, 모든 진행사항은 공유된다.



## **#1.  SERVICE **



> 서비스는 7장 - 각 화면단으로 분리
>
> 각 화면단은 `구성|기능|디자인|작업자 `  로  되어 있으며,
>
> 추가 개선사항과  Configuration 문서로 연결관리한다. 



###  1장. 사용자단  `web`

모두의 클래스의 얼굴 - 3전략 (보다 싸게, 많은 클래스, 최적화된 클래스 찾아주는 것. )  
해당 장의 유저 목표는 기분 좋은 클래스 경험과 결제 전환율을 높이는 것이다. 

**핵심지표 : 전환율(결제/알림/신청)**

- [홈 : 기획문서](service/ch1_home)  => [`web`](https://www.modooclass.net/ : target="_blank") 

- [검색 : 기획문서](service/ch1_home/search) => 미완료 (기획단계)

- [로그인 : 기획문서](service/ch1_home/login)   =>   [`web`](https://www.modooclass.net/modoo/login)

- [상세 (알림|1:1코칭|무료|선결제|환급일반|일반) : 기획문서](service/ch1_home/detail)   =>  [`web`](https://www.modooclass.net/class/classDetail/483)

- [패키지 : 기획문서 ](service/ch1_home/package)   =>  [`web`](https://www.modooclass.net/class/pay/package/488)

- [결제 : 기획문서 ](service/ch1_home/pay)   =>  [`web`](https://www.modooclass.net/class/pay/payinfo/488/214)

- [결제완료 : 기획문서 ](service/ch1_home/pay/confirm)   =>   [`web`](https://www.modooclass.net/class/group/436)

- [알림페이지 : 기획문서 ](service/ch1_home/pay/alram)   =>  [`web`](https://www.modooclass.net/class/confirm/alarm/646/member/140019?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJodHRwczpcL1wvYXBpLmVuZml0Lm5ldFwvYXBpXC92M1wvb3BlbmNhbGxcLzY0NiIsImlhdCI6MTU2MjcxNDczNSwiZXhwIjoxNTYzOTI0MzM1LCJuYmYiOjE1NjI3MTQ3MzUsImp0aSI6IlY4cUZlNVdUZVppbk9YYzYiLCJzdWIiOjE0MDAxOSwicHJ2IjoiOTYyYTE0ZDQ4YzQyOWUzYTZhYWIzNjEwYzAzNTJiZmJiNDVlZmM1OCJ9.42H7yjucquFfqHzDn5Xoo_Rf9qqEs16Oa50c3iO0T-g)

- [추가개선 : QA 문서](service/ch1_home/upgrade)

- [사용자단 - configuration ](service/ch7_configuration/home)

  

  [작업자] 기획 - `@김대형` `@신민수`  | 디자인 - `@김보라`  | 개발 - `@안지환` `@김혜진`  + `@노육민`



###  2장. 마이페이지  `web` 

마이페이지에서 참여/운영/관심 있는 클래스 및 이웃과의 허브 역활을 한다.   

가장 많이 이용하는 지점을 찾아 유저가 다른 클래스 | 회원과 연결점을 잘 찾을 수 있게 하는 것이 목표. (해당페이지의 이탈율 최소가 페이지의 목표)  

**핵심지표 : 이동페이지경로 및 이탈율**

- [마이페이지(클래스)](service/ch2_my_class)  => [`web`](https://www.modooclass.net/class/user/mypage) 

- 팔로워/팔로윙

- 프로필수정

- 포인트내역 | 결제내역

- 내가남긴리뷰

- 이벤트 | 문의하기 | 자주묻는질문

- 이용약관 | 개인정보처리방침

- 추가개선 :  QA문서

- 마이페이지 - configuration

  
  
  
  [작업자] 기획 - `@김대형` `@신민수`  | 디자인 - `@김보라` | 개발 - `@안지환` `@노육민` `@박정희`
  
  



###  3장. 클래스 개설  `web`

누구나 코치가 될 수 있도록 한다. 코치가이드 화면을 거쳐 쉽게 영상 업로드후 정보 입력 하면 수익화 할 수 있는 클래스를 가질 수 있는 사용성에 초점을 두고 개발한다. 

쉽고 편한 사용성 중심의  UI/UX 에 기반한 빠르게 영상업로드 한번으로 끝내도록 한다.

**핵심지표 : 페이지 이탈율**

- 코치가이드

- 코치정보입력

- 클래스개요

- 커리큘럼

- 패키지정보

- 알림정보

- 추가개선 :  QA문서

- 클래스개설 - configuration


  [작업자] 기획 - `@김대형` `@신민수` | 디자인 - `@김보라` | 개발 - `@안지환` `@노육민` `@박정희`





###  4장. 클래스 관리  `web`





###  5장. 클래스 참여  `app`





### 6장. CMS 최종 관리자단  `web`





###  7장. Configuration  `git-text`

- 서버구성
- DB구성
- Config





##  **#2. CONTENTS** 





## **#3. MARKETING**





## **#4. POLICY**

- 개인정보 및 이용약관

- 포인트 정책

- 클래스 참여 정책

- 클래스 관리 정책

  







![](assets/image/logo1024.png)

-----------------------------------------------------------------------------------------------------------------------------------



##  **CONTRIBUTOR** 

#### [서비스 제작 참여]

- 기획 => `@김대형` `@신민수`

- 디자인 => `@김보라` `@신미소`

- 개발 => `@안지환` `@노육민` `@박정희` `@김혜진` `@이대준` `@조현민`

- 제품 참여 => `@강승권` `@김재환` `@콘텐츠팀` `@코치진` `@사제이기하` `@대교인베스트김재엽`

  