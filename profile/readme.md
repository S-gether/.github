
# Sgether with AI ( AI 감독 스터디 플랫폼 )

  

<p  align="center">
<img  width="1000px"  height = "175px"  src="https://user-images.githubusercontent.com/111236793/212054463-d4fd811f-6622-4b2b-8393-8bdbb8897077.png"/>
</p>

 <p  align="center"><b>AI 감독관을 활용한 비대면 스터디 플랫폼</b></p>


저희 팀은 비대면 스터디 플랫폼의 단점을 AI 기술을 사용해 해결하는 Sgether team입니다.
 
##### 효과 

AI 비대면 학습 감독관을 도입해 아이들의 집중도를 평가하고 지적하는 기능을 통해 비대면 스터디의 단점을 보완해 더욱 효과적인 학습 관리와 학습이 가능합니다.
 

## 📄 개요

제 3국가에는 거리가 멀어서 수업을 듣기 어려운 학생들이 있습니다. 이 학생들의 교육권을 보장하기 위해 비대면 교육 시스템 플랫폼이 필요합니다. ( 교육 불평등 해결 )  
  
하지만 감독관의 부재와 학생의 집중도 등을 현장에서 만큼 확인할 수 없기 때문에 교육의 질이 떨어질 수 밖에 없습니다.  
  
이에 따라 AI 감독관 + 화상회의 스터디를 합친 AI 캠스터디로 해당 문제 상황을 해결하고자 하였습니다.
  
## 📄 UN SDG
### Quality Education
### Reduce Inequality

##### target
지리적, 환경적 문제로 인해 일정 수준 이상의 교육을 받을 수 없는 아이들
##### problem
대면 수업이 어려운 부분으로 비대면 수업을 진행해야 하지만 학생들의 집중도를 확인하기 어려운 부분이 존재
##### resolve
AI 감독관을 도입해 문제를 해결

## 🛣 아키텍처
<p  align="center">
<img src="https://user-images.githubusercontent.com/76484900/227689141-1e988c8d-0582-4692-a86a-808ac9d31f1a.jpg"/>
</p>


## 📚 프로젝트 개요
<p  align="center">
<img width = "250px" height = "500px" src="https://user-images.githubusercontent.com/76484900/227690312-6296bc19-ab94-418b-ac83-76dc9fdfb836.png"/>
<img width = "250px" height = "500px" src="https://user-images.githubusercontent.com/76484900/227690317-f8f6294e-3d75-4ba4-8a95-1464a2609397.png"/>
<img width = "250px" height = "500px" src="https://user-images.githubusercontent.com/76484900/227690318-78d17535-1bae-4940-bb0f-5b8bda74ab26.png"/>
</p>


##  👍 프로젝트의 확장성
자습 감독을 넘어서 다른 대형 교육 플랫폼과 협업을 통해 학습 컨텐츠 또한 제공할 것이다.  
그렇다면 더 많은 사용자들이 유입될 것이고 우리 프로젝트의 기술을 통해 더 효율적이고 효과적인 학습이 이루어질 것이다.  

또한 AWS의 EC2 클라우드 서비스를 사용해 배포를 진행하고 있다. 따라서 유저의 규모에 따른 스케일 업이 자유롭게 진행될 수 있고 수요에 따라 유동적으로 서버 증설을 통해 확장에 대비할 수 있다.



 

## ⚙️ 기술 스택


### 🚏 `Server - APP(BE)`

|service|version|
|--|--|
|**NodeJS**|v16.x|
|**EXPRESS**|v4.x|
|**REDIS**|v3.0.x|
|**MySQL**|5.7.x|

  

### 📱 `FE - APP`

|service|version|
|--|--|
|**Android Studio**|v4.2|
|**Figma**|web_service|
|**webRTC**|google_service|

  

### 💻 `ML - embedded`

|service|version|
|--|--|
|**python**|v3.11.2|

  


## 👪 팀 정보
- 반영환 (lopahn2@gmail.com), Github Id: lopahn2 (Server, Database)
- 김강민 (rkdals0203@gmail.com), Github Id: rkdals0203 (APP Frontend)
- 채홍무 (hongmuchae@gmail.com), Github Id: Hong-Mu (APP Frontend)
- 방재훈 (dev.appendCBangJ@gmail.com), Github Id: devappendCBangJ (Deep Learning)
