# <img src="https://github.com/user-attachments/assets/9d2778e5-2eac-4528-8b65-8fd5a9df6eb8" width="45" height="45" align='center' /> WorkCheck 자영업자를 위한 직원 관리 플랫폼
![토이2썸네일](https://github.com/user-attachments/assets/a4b38fab-d7b7-4191-8fc1-64918ba533ae)

<div align=center>

## 👋 P2R (Path to Resolution) 👋
"P2R(Path to Resolution)" 은 갈등과 문제를 해결하는 데 초점을 맞춘 팀입니다.<br/>
우리의 목표는 다양한 도전 과제를 분석하고, 협력을 통해 창의적이고 실용적인 해결책을 찾아내는 것입니다.<br/>
우리는 커뮤니케이션, 협상, 전략적 사고를 통해 긍정적인 변화를 추구합니다.
|[<img src="https://avatars.githubusercontent.com/u/107895537?v=4" width="150" height="150"/>](https://github.com/HSjjs98)|[<img src="https://avatars.githubusercontent.com/u/169154369?v=4" width="150" height="150"/>](https://github.com/ssumanlife)|[<img src="https://avatars.githubusercontent.com/u/170381378?s=88&v=4" width="150" height="150"/>](https://github.com/miniseung)|[<img src="https://avatars.githubusercontent.com/u/170402797?v=4" width="150" height="150"/>](https://github.com/dyeongg)|
|:-:|:-:|:-:|:-:|
|🐯양해석<br/>[@HSjjs98](https://github.com/HSjjs98)<br/> 역할: 홈, 로그인, DB|🐰김수민<br/>[@ssumanlife](https://github.com/ssumanlife)<br/> 역할: 직원급여내역|🐶김승민<br/>[@miniseung](https://github.com/miniseung)<br/> 역할: 일정관리페이지|🐱임효정<br/>[@dyeongg](https://github.com/dyeongg)<br/> 역할: 직원리스트, 디자인|
<br/>
</div>

![토이2pr](https://github.com/user-attachments/assets/f4b5f49d-d180-4436-8c23-2fc7b9d98c7c)




---
<br/>

## 목차
<img src="https://github.com/user-attachments/assets/9d2778e5-2eac-4528-8b65-8fd5a9df6eb8" width="15" height="15" align='center'/>&nbsp; Workcheck
- [❓ 프로젝트 소개  ](#-프로젝트-소개)
  - [ 목적  ](#목적)
  - [ 배경  ](#배경)
    - [1. 필요성  ](#1-필요성)
    - [2. 목표 및 기대 효과  ](#2-목표-달성-기대-효과)
- [🕖 프로젝트 타임라인 ](#-프로젝트-타임라인)
  - [ 기획  ](#기획)
  - [ 🧑‍💻 Tech Stack  ](#-Tech-Stack)
  - [ 프로젝트 구조  ](#구조)
  - [ 컨벤션  ](#컨벤션)
- [📷 프로젝트 예시  ](#-프로젝트-예시)
  - [🔎 로그인 및 회원가입  ](#-로그인)
  - [🔎 사용자 화면  ](#-사용자-화면)
- [🛠 시작하기](#-시작하기)
  - [설치](#설치)
  - [실행](#실행)
  - [배포](#배포)
  - [문서](#문서)
<br/>

## ❓ 프로젝트 소개


## 목적
이 프로젝트의 목적은 사장님들과 직원들 모두에게 편리하고 효율적인 급여 관리 및 스케줄 관리를 제공하는 것입니다.<br/>
직원들의 급여를 확인하고 캘린더를 통한 스케줄 관리를 할 수 있습니다.<br/>
이를 통해 사장님은 직원과 원활한 소통과 업무 관리를 경험할 수 있습니다.

## 배경

### 1. 필요성

![토이2-2](https://github.com/user-attachments/assets/76e8c2ef-2f59-45b4-a4b5-40df903d14f1)<br/>
김현수는 20년 전 치킨집을 시작했다. 처음에는 작은 가게에서 시작했지만, 열정과 성실함으로 가게를 점점 키워 현재는 지역에서 유명한 치킨집 사장이 되었다.<br/>
그는 고객 서비스와 맛의 일관성을 최우선으로 생각하며, 손님들이 언제나 만족할 수 있도록 노력하고 있다.

#### 고충과 도전:

- **시간 관리:** 가게 운영으로 인해 개인 시간과 가족과의 시간을 조율하는 것이 어렵다.
- **직원 관리:** 직원들의 교육과 복지에 신경을 쓰지만, 이로 인해 추가적인 스트레스를 받는다.
- **경쟁:** 치열한 외식업계에서 살아남기 위해 끊임없이 새로운 아이디어와 전략이 필요하다.

### 2. 목표 달성 기대 효과
김현수는 급여 및 스케줄 관리 플랫폼을 통해 직원들의 근무 일정을 효율적으로 관리하고, 급여 계산을 자동화하여 시간과 노력을 절약할 수 있다.<br/>
이 플랫폼을 통해 직원들의 출퇴근 시간을 정확히 기록하고, 근무 시간에 따른 급여를 쉽게 계산할 수 있다.<br/>
또한 직원들의 요청사항이나 스케줄 변경 사항도 쉽게 처리할 수 있다.

<br/>


## 🕖 프로젝트 타임라인


## 기획

### 공통 기능
- 로그인
  - 사장님 계정 생성 시 매장 코드 부여
  - 매장 코드를 활용하여 여러 매장에 대한 서비스 제공 가능
- 캘린더를 통한 일정 관리: 등록, 수정 삭제

### 사장님 기능
  - 직원 리스트 관리 (CRUD)
  - 직원 정보 생성, 읽기, 수정, 삭제
  - 급여 기간 등록
  - 직원 급여 관리
  - 급여 내역 (금액, 정산 내역) 등록 및 수정

### 직원 기능
  - 급여 내역 확인
  - 급여 정정 신청
  - 캘린더를 통한 일정 관리

<br/>

<div align=center>

## 🧑‍💻 Tech Stack


![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![typescript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![redux](https://img.shields.io/badge/Redux-593D88?style=for-the-badge&logo=redux&logoColor=white)

#### 💻 Database 💻
![Firebase](https://img.shields.io/badge/Firebase-039BE5?style=for-the-badge&logo=Firebase&logoColor=white)

#### 🛠 Tools 🛠
![styled-components](https://img.shields.io/badge/styled--components-DB7093?style=for-the-badge&logo=styled-components&logoColor=white)
![eslint](https://img.shields.io/badge/eslint-3A33D1?style=for-the-badge&logo=eslint&logoColor=white)
![prettier](https://img.shields.io/badge/prettier-1A2C34?style=for-the-badge&logo=prettier&logoColor=F7BA3E)
</div>

---
## 📄 프로젝트 구조
```
📦Toy_Project_II_team2
 ┣ 📂Public
 ┃ ┣ 📂images
 ┃ ┣ 📂icons
 ┃ ┗ 📂favicon
 ┣ 📂Server
 ┃ ┣ 📜index.js
 ┣ 📂src
 ┃ ┣ 📂API
 ┃ ┣ 📂Components
 ┃ ┣ 📂Pages
 ┃ ┣ 📂Reducers
 ┃ ┣ 📂Utils
 ┗ 📜README.md
```

### 컨벤션

- 커밋 컨벤션
    - 예시) feat: 홈페이지 스타일링 (#이슈번호)
    - `feat` : 새로운 기능 추가
    - `fix` : 버그 수정
    - `docs` : 문서 수정
    - `style` : 코드 포맷팅, 세미콜론 누락, 코드 변경이 없는 경우
    - `refactor` : 코드 리펙토링
    - `test` : 테스트 코드, 리펙토링 테스트 코드 추가
    - `chore` : 빌드 업무 수정, 패키지 매니저 수정
- 브랜치 컨벤션
    - 이슈 브랜치명 예시: feat/login-signup-148
    - 이슈 브랜치에서 PR 올리면 검토 후 dev 브랜치로 병합
    - 일주일마다 dev 브랜치를 main 브랜치로 병합
    - PR, Issue template 추가하기
    - MileStone 사용해서 일정 확인 및 관리하기
- css 컨벤션
    - ESLint: [eslint-config-Airbnb-base](https://github.com/airbnb/javascript/tree/master/packages/eslint-config-airbnb-base)
    - Prettier
    - !important 사용 금지
    - id 선택자로 스타일링 지양
    - 스타일링을 위해 요소에 클래스 명 지정할 때 페이지명+요소를 나타내는 ….
        - 예시: loginWrapper , navWrapper, headerWrapper
- 함수 또는 클래스 이름 컨벤션
    - 본인만 아는 이름 사용 x
    - 함수, 변수 이름: Camel Case (ex: userName, handleOnclick)
    - 클래스 컴포넌트 이름: Title Case (ex: Button)

## 📷 프로젝트 예시

### 🔎 [로그인]
![image](https://github.com/user-attachments/assets/358a0d73-c239-4d78-b985-e1a226e9c6d7)


<br>

### 🔎 [사용자 화면]
#### 일정 관리 화면
![image](https://github.com/user-attachments/assets/581f4adc-afe4-41f0-9bca-0eab04bb358d)
#### 급여 관리 화면
![image](https://github.com/user-attachments/assets/090471bd-f002-4f23-b07a-47f873cb738c)


---

## 🛠 시작하기
### 설치

Workcheck 서비스는 서버와 클라이언트 시스템으로 구성되며 react 와 vite 기반으로 구성되어있습니다.<br>
프로젝트 저장소를 다음 설명에 따라 개발자 컴퓨터에 복사하고 설치 명령을 입력하여 설치를 할 수 있습니다.



```bash
git clone https://github.com/Dev-FE-1/Toy_Project_II_team2.git

cd my-project

npm install
```

### 실행

개발자 로컬 환경에서 개발 모드로 실행하기 위해선 프로젝트 루트 디렉토리에서 다음의 명령을 실행하세요.

```bash
npm run dev 
```

### 배포

프로젝트의 배포 버전을 생성하기 위해 빌드 스크립트를 실행합니다.

```bash
npm run build:production
```

개발 환경 배포 빌드는 build:develop 스크립트를 사용해주세요. 
운영 환경 빌드는 build:production 스크립트를 사용해주세요.


### 문서

프로젝트 설계 문서는 design 디렉토리에 마크다운 파일로 기록되어있습니다.
각각의 설계 문서는 다음과 같습니다.

* 요구사항 정의서 
  * 제품이 제공해야되는 기능 요구 정의서입니다.
  * 요구사항 정의서에 기술된 기능은 최소 기능 요구사항이며 추상적일 수 있으며 기능의 구체화는 제품 구현 단계에서 이루어집니다.
* 프로젝트 정의서
  * 요구사항 정의서를 기반으로 프로젝트를 설계합니다.
* 기능 정의서
  * 사용자 스토리 기반으로 세부 기능을 정의합니다.
---

