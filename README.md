![Image](https://github.com/user-attachments/assets/3698ce22-63ca-4d64-a106-a8aae9b9b36a)

## 🖋 요약

#### 1. **주제**

- 사용자가 자신의 하루 계획을 설정하고 실천하기 위해 목표 달성과 습관 형성을 자연스럽게 유도하는 공간 제공

#### 2. **목표**

- 다양한 연령층을 고려하여 사용자 중심의 직관적인 UX 제공
- 매일 목표에 집중할 수 있도록 간편하게 일정 등록과 확인을 할 수 있는 구조

#### 3. **개발 환경**

- Front-End : Flutter, Dart, GetX
- Back-End : hive(로컬처리)

#### 4. **기간 및 인원**

- 2025-06-01 ~ 2025-06-02 : 기획 및 디자인
- 2025-06-03 ~ 2025-06-09 : 개발 및 테스트 기간

총 9일, 1인


## 🔗 배포 URL

- http://schedule-mauve.vercel.app


## 📌 주요 기능

- 비회원 사용 ➡ 로그인 없이 앱 전체 기능 이용 가능
- 캘린더 ➡ 일정을 쉽게 추가하고 확인할 수 있는 기능
- 리스트 ➡ 등록한 일정을 리스트 형태로 정리하여 전체 리스트를 한눈에 확인 가능
- 검색 ➡ 키워드를 입력하여 일정을 쉽게 찾아볼 수 있는 기능


## 💼 프로젝트 폴더 구조

```
📦schedule                           # schedule ( Front-End )
 ┣ 📂assets                          # svg, gif 등 이미지 폴더
 ┣ 📂build                           # Flutter가 빌드한 결과물
 ┃ ┣ 📂web
 ┃ ┃ ┗ 📜index.html
 ┣ 📂lib
 ┃ ┣ 📂controller                    # 컴포넌트 폴더
 ┃ ┃ ┗ 📜calendar_controller.dart    # GetX 컨트롤러 (ViewModel)
 ┃ ┣ 📂screen                        # 화면 단위 위젯 (각 페이지별 UI 구성)
 ┃ ┃ ┗ 📜calendar_page.dart
 ┃ ┃ ┗ 📜list_page.dart
 ┃ ┃ ┗ 📜search_page.dart
 ┃ ┗ 📜main.dart                     # 앱 실행 진입점, 전체 라우팅 및 초기 설정
 ┗ 📜README.md
```

## 🛠️ 사용 기술

### 1. Frond-End

| 사용기술 | 설명 |Badge |
| :---:| :---: | :---: |
| **Flutter** | **크로스 플랫폼 앱 개발 프레임워크** |![flutter](https://img.shields.io/badge/flutter-02569B?style=flat-square&logo=flutter&logoColor=white)|
| **Dart** | **Flutter 전용 프로그래밍 언어** |![dart](https://img.shields.io/badge/dart-0175C2?style=flat-square&logo=dart&logoColor=white)|
| **GetX** | **상태 관리** |![getx](https://img.shields.io/badge/getx-8A2BE2?style=flat-square&logo=getx&logoColor=white)|

### 2. Back-End

| 사용기술 | 설명 | Badge |
| :---:| :---: | :---: |
| **Hive** | **로컬 저장** |![hive](https://img.shields.io/badge/Hive-using%20Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)|

### 3. 개발 도구

|사용기술 | 설명 | Badge | 
|:---:| :---: |:---: |
| **Visual Studio Code<br>(VS Code)** | **코드 편집기( 에디터 )** |![VSCode](https://img.shields.io/badge/VSCode-007ACC?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMzIiIGhlaWdodD0iMzIiIHZpZXdCb3g9IjAgMCAzMiAzMiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPHBhdGggZD0iTTI0LjAwMyAyTDEyIDEzLjMwM0w0Ljg0IDhMMiAxMEw4Ljc3MiAxNkwyIDIyTDQuODQgMjRMMTIgMTguNzAyTDI0LjAwMyAzMEwzMCAyNy4wODdWNC45MTNMMjQuMDAzIDJaTTI0IDkuNDM0VjIyLjU2NkwxNS4yODkgMTZMMjQgOS40MzRaIiBmaWxsPSJ3aGl0ZSIvPgo8L3N2Zz4K&logoColor=white) |
| **GitHub** | **버전 관리** |![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white)| 
| **Vercel** | **서버리스 플랫폼** |![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)|
| **Figma** | **디자인 & UI/UX**|![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=Figma&logoColor=white) |
| **Notion** | **문서 & 관리** |![notion](https://img.shields.io/badge/Notion-000000?style=flat-square&logo=notion&logoColor=white)| 


## 📚 프로젝트 문서 자료

| 문서종류 | 파일명 | 설명 |
| :---:| :---: | :---: |
| 화면설계 | [화면설계.pdf](https://github.com/yeonhee001/schedule/blob/main/work/%EC%9D%BC%EC%A0%95%EA%B4%80%EB%A6%AC_%ED%94%8C%EB%9E%9C%EC%9E%87_01%EC%99%80%EC%9D%B4%EC%96%B4%ED%94%84%EB%A0%88%EC%9E%84.pdf) | 주요 페이지의 화면 구성, 사용자 흐름 등 와이어프레임 기반 설계 자료 |
| 디자인 | [디자인.pdf](https://github.com/yeonhee001/schedule/blob/main/work/%EC%9D%BC%EC%A0%95%EA%B4%80%EB%A6%AC_%ED%94%8C%EB%9E%9C%EC%9E%87_02%EB%94%94%EC%9E%90%EC%9D%B8.pdf) | Figma로 작업한 디자인 시안. 색상, 폰트, UI 요소 등 자료 |
| 발표자료 | [발표자료.pdf](https://github.com/yeonhee001/schedule/blob/main/work/%EC%9D%BC%EC%A0%95%EA%B4%80%EB%A6%AC_%ED%94%8C%EB%9E%9C%EC%9E%87_03PPT.pdf) | 프로젝트 발표용 슬라이드 자료 |


## 💥 트러블슈팅

### 📌 calendar_page.dart

 1. 일정을 등록한 후, 다른 날짜를 클릭했을 때 이전에 등록한 일정이 사라지고, 새로고침하면 나타나는 이슈 발생

    *저장이 완료되기 전, 날짜가 이동되면서 저장되지 않은 상태의 데이터를 화면에 반영 <br>
    
    ⇒ **해결방법**: 이를 해결하기 위해 saveSchedule 함수와 addSchedule 함수에서 저장이 완료될 때까지 대기한 후 일정 목록을 다시 불러오도록 async, await를 사용하여 처리


### 📌 list_page.dart

 2. 일정을 삭제한 후, 리스트를 확인해보면 내용은 없지만 해당 날짜는 그대로 남아있는 이슈 발생

    *값이 비어있는지만 확인하여 빈 문자열도 포함되어 있었음 <br>
    
    ⇒ **해결방법**: content가 비어있는 항목들은 리스트에서 제외되도록 수정

