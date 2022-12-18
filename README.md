# 군자스마트고등학교

## (특수학생 교육 및 설문 프로그램)

---

- 2022년 12월 18일 ~

---

## 목차

1️⃣ 개요

2️⃣ 기술스택

3️⃣ 설계 / 개발

4️⃣ 시연

5️⃣ 개발자

6️⃣ 회고

---

### 1️⃣개요

#### 프로젝트명 정하기

- 군자스마트고등학교
  
  - 특수학생 교육 및 설문 프로그램

#### 팀명정하기

- #### 

#### 그라운드룰

- 목표
  
  - 참고자료
    
    - [같이 카페 갈래요?](https://storyplay.com/share/story/HloepoopSIlyolyapr)
  
  - 특수학생을 대상으로한 교육 프로그램 개발
    
    - 진행 - 참고자료와 같은 형식
    1. 사회성 함량을 위한 에피소드 형식의 교육프로그램
       
       - 채팅형식으로 대화 과정을 통해 학습
    
    2. 선택 값에 따라 스토리 진행
    
    3. 프로필 페이지에서 사용자의 문답 중 오답을 확인
    
    4. 추후 다양한 에피소드 형식으로 개발
    - 결과
    1. 선택 데이터 추출하여 그래프와 표 형식으로 관리자에게 제공

- 규칙
  
  - 

---

### 2️⃣🔸Tech Stack

<span>
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white">
<img src="https://img.shields.io/badge/Django-000000?style=for-the-badge&logo=Django&logoColor=white">
</span>
<br>
<span>
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white">
<img src="https://img.shields.io/badge/Node.js-339939?style=for-the-badge&logo=Node.js&logoColor=white">
</span>
<br>
<span>
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
<img src="https://img.shields.io/badge/css3-1572B6?style=for-the-badge&logo=css3&logoColor=white">
<img src="https://img.shields.io/badge/bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white">
</span>
<br>
<span>
<img src="https://img.shields.io/badge/GitLab-FCA121?style=for-the-badge&logo=GitLab&logoColor=white">
<img src="https://img.shields.io/badge/Mattermost-0058CC?style=for-the-badge&logo=Mattermost&logoColor=white">
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
</span>
<br>
<span>
<img src="https://img.shields.io/badge/visual studio code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white">
</span>

#### 🔸사전 설치 코드(Command)

```Vue.js
# Vue
npm i
npm run serve
```

```django
# Django
python -m venv venv
source venv/Scripts/activate
pip install -r requirments.txt
python manage.py makemigrations
python manage.py migrate
python manage.py runserver
```

---

### 3️⃣설계 / 개발

### 🔸설계

#### 아이템 논의

- 로그인(카카오 로그인 활용하면 좋음)

- 프로필 - 결과 확인 
  
  - 오답노트 느낌으로 질문과 답만 나오는 것이 아닌 진행상황에 있는 그 대화 전체와 사진이 캡쳐형식으로 제공되었으면 함

- 진행 - 참고자료랑 같은 형식 
  
  - 채팅형식의 진행사항을 원함(대화를 읽어주는 기능은 추가했으면 하나 시간이 부족하면 생략 가능)
  
  - 채팅형식의 이름은 참고자료처럼 사용자 프로필 이름으로 진행되는 것을 원함
  
  - 객관식 형태의 결과 선택(중간에 메뉴 선택은 단어를 입력하면 인식하는 느낌으로 구현하면 좋지만 어려우면 생략하고 객관식 형태로 대체 가능)
    
    - 선택지마다 경험치(점수) 부여
      
      - 사회성 증가 / 노력 필요 등의 방법으로 점수를 부여하여
      
      - 교육 종료 시 커트라인 이상 이하 점수로 통과 / 노력 필요 등의 결과 제공
    
    - 단어 입력을 원하는 이유는 학생들의 오타를 어느 부분에서 내는지 확인하고 싶어서
    
    - (선택사항(결과와 연관) : 질문이 나온 후부터 결과를 선택할 때까지 시간도 구현하면 좋지만 없어도 무방함)
  
  - 문항과 사진은 내일 중으로 정리하여 제공해 줌
  
  - 문항은 참고자료에서 필수 내용만 추출하는 것으로 협의

- 결과
  
  - 사용자의 선택문항이 표로 제공되었으면 함(그래프까지 제공되었으면함)

#### 확정아이템 및 MVP

#### ERD

#### Vue router

#### Component

#### 🔸개발

#### 프로젝트 상세 일정

| 날짜       | 일정                 |
| -------- | ------------------ |
| 22/12/18 | 프로젝트 구성 및 진행 방향 설정 |
|          |                    |
|          |                    |
|          |                    |
|          |                    |
|          |                    |
|          |                    |
|          |                    |
|          |                    |
|          |                    |
|          |                    |

---

### 4️⃣시연

시연 영상 및 사진

#### 💻구현기능

- ⚙️데이터
  
  - 

- ⚙️알고리즘
  
  - 

- ⚙️API
  
  - 

- ⚙️기타
  
  - 

---

### 5️⃣ 개발자

| 이름         | 파트    | 경험하고 싶은 것 |
| ---------- | ----- | --------- |
| 👩<br/>이현지 | front |           |
| 👨<br/>김영식 | back  |           |

---

### 6️⃣ 회고

#### 4L 회고

- 😍 좋았던 것(Liked)
  
  1. 

- 📚 배운 것(Learned)
  
  1. 

- 💦 부족했던 것(Lacked)
  
  1. 

- 🕯 바라는 것(Longed for)
  
  1. 

- 무엇이 어려웠는지, **그걸 어떻게 해결하였는지**
  
  - !
