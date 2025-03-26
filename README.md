# 📌 봉장부 | AI OCR을 활용한 장부 작성 자동화 프로그램
### 더욱 투명하고 간편한 학생회비 관리, 봉장부로 시작하세요 !
![image](https://github.com/user-attachments/assets/87549994-4666-4de1-a91b-d194d686baa3)

## 1. 프로젝트 소개
> 본 프로젝트는 학생회 장부 관리의 비효율성을 해결하고자 시작되었습니다.
기존 수기 방식의 장부 작성을 AI OCR 기술과 금융 데이터 연동을 통해 자동화하여,
보다 정확하고 투명한 회계 관리를 가능하게 하는 시스템을 개발했습니다.
```
- AI OCR을 활용하여 영수증을 자동으로 인식하고 데이터화합니다.
- 금융결제원 API를 연동하여 실시간으로 계좌 거래 내역을 조회합니다.
- 학생회 역할(회장, 총무, 감사 등)에 따라 접근 권한을 다르게 설정합니다.
- 모든 장부 내역은 기록되어 감사 시 활용할 수 있습니다.
```
### 👥 팀원 구성
  | 정채원 | 강지원 | 이재훈 | 박기재 |
  | :--------: | :--------: | :--------: | :--------: |
  |<a href = "https://github.com/chaewonjeong"> <img width="200" src="https://github.com/user-attachments/assets/2386dc94-bdb2-451f-9771-71699fa214d2"></a>|<a href = "https://github.com/onegqueen"> <img width="200" src="https://github.com/user-attachments/assets/1ef89f28-6b5b-452a-93b1-241bebfb0437"></a>|||
  |   **@chaewonjeong**    |      **@onegqueen**      |**@**|**@**|

## 2. 개발 환경

- **Front** : 
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)

- **Back-end** : 
![Spring](https://img.shields.io/badge/spring-%236DB33F.svg?style=for-the-badge&logo=spring&logoColor=white)
![IntelliJ IDEA](https://img.shields.io/badge/IntelliJIDEA-000000.svg?style=for-the-badge&logo=intellij-idea&logoColor=white)

- **DB** : 
![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white)

- **버전 및 이슈관리** : 
![Git](https://img.shields.io/badge/git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)

- **협업 툴** :
![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)
![Google Drive](https://img.shields.io/badge/Google%20Drive-4285F4?style=for-the-badge&logo=googledrive&logoColor=white)

- **서비스 배포 환경** :
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)

- **디자인** :
![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)

## 3. 채택한 개발 기술과 브랜치 전략
본 프로젝트는 DDD(Domain-Driven Design) 패턴을 적용하여, 도메인별로 컨트롤러, 서비스, 리포지토리 계층을 분리하고, 각 계층의 책임을 명확히 하여 코드의 유지보수성과 확장성을 강화했습니다.

#### 브랜치 전략
- Git-flow 전략을 기반으로 main 브랜치를 두고, 개발(develop) 브랜치를 운영했습니다.
- 기능별 이슈를 생성하고, 브랜치명은 feat/{이슈번호} 형식으로 관리했습니다.


## 4. ERD
<img width="1241" alt="image" src="https://github.com/user-attachments/assets/8d935d22-cf2f-43a8-b9a2-648b3237585a" />


## 5. 프로젝트 구조 및 아키텍처
<img width="1254" alt="image" src="https://github.com/user-attachments/assets/0f35cb9e-cf85-4a86-8706-dbb621b954a3" />


## 6. 역할 분담
- 외부 API 연동 (금융결제원 API)
- 학생회 역할 기반 권한 관리 시스템 설계
- 장부 자동화 로직 개발
- OCR 데이터 매칭 및 검증

## 7. 개발 기간
### 전체 개발 기간 | 2024-03 - 2024-11
- 설계 | 2024-03 - 2024-07
- 구현 | 2024-08 - 2024-11


## 8. 주요 기능 소개
### ✅ 학생회비 실시간 현황 조회
|화면|설명|
|:------|:---|
|<img width="232" alt="image" src="https://github.com/user-attachments/assets/494b5056-e576-416c-8e21-3e68c38320cf"/>| **사용자의 학적정보와 및 학생회비 사용현황을 한눈에 확인할 수 있음** <br><br>  - 본인 정보 조회 <br> - 학생회비 현재 잔액 조회 <br> - 최근 거래내역 조회|
|||

### ✅ 거래 내역 관리
|화면|설명|
|:------|:---|
|<img width="232" alt="image" src="https://github.com/user-attachments/assets/949c6085-7113-4636-855b-c4b3cff68385" /> <img width="232" alt="image" src="https://github.com/user-attachments/assets/01f276e2-afb0-4e5b-bf51-da6217175fa3" />| **금융결제원 인증을 통해 실계좌를 연결하고 실시간 거래내역을 받아올 수 있음** <br><br> - 실계좌 연결(핀테크 적용) <br> - 조회 기간 별 거내내역 조회 
|||
  
### ✅ 학생회비 납부자 관리
|화면|설명|
|:------|:---|
|<img width="232" alt="image" src="https://github.com/user-attachments/assets/bf53e8e3-5f13-4a3b-99ce-4745dc2e7ccb" />| **거래내역을 기반으로 학생회비 납부자 인증을 받은 사용자는 인증 마크를 얻을 수 있음** |
|||

### ✅ 영수증 OCR 처리

|화면|설명|
|:------|:---|
|<img width="227" alt="image" src="https://github.com/user-attachments/assets/b2370f8b-7bc9-485c-b8fb-183785be490a" />| **영수증을 찍어 업로드하면, OCR 처리된 데이터를 거래내역과 매칭하여 저장** |
|||

### ✅ 자동 장부 생성

|화면|설명|
|:------|:---|
|<img width="277" alt="image" src="https://github.com/user-attachments/assets/2d268fbf-da5d-44f5-8159-5efaa5953d0a" />| **매칭된 영수증과 거래내역을 기반으로 장부가 자동으로 만들어짐. 총무는 해당내용을 확인하고 수정하여 장부를 손쉽게 작성할 수 있음** |
|||

### ✅ 권한관리
> #### 감사
단과대학의 감사로 각 학과의 장부를 관리/감사할 수 있다.
  - 학과별 장부조회
  - 학과별 장부 감사
    - 장부 승인 / 반려
  - 역할 위임
    - 임기가 끝나면 해당 대학으로 가입된 학생에게 감사 역할을 위임할 수 있다.
  - 학과 회장 초대
    - 해당 단과대학으로 가입할 수 있는 초대코드를 생성할 수 있다.

> #### 회장
학과의 회장으로 학과 장부를 관리/감사할 수 있다.
  - 학생회비 계좌 잔액/거래내역 조회
  - 학과 장부 감사
    - 장부 승인 / 반려
  - 역할 위임
    -  임기가 끝나면 해당 학과로 가입된 학생에게 회장 역할을 위임할 수 있다.
  - 역할 임명
    - 총무와 부회장에 해당하는 역할을 해당 학과로 가입된 학생에게 임명할 수 있다.
  - 학생회비 납부자 관리
    - 학생회비 납부자를 조회하고 수동으로 납부/미납부 등록을 할 수 있다.
  - 학생 초대
    - 해당 학과로 가입할 수 있는 초대코드를 생성할 수 있다.
  
> #### 부회장
학과의 부회장으로 학과 장부를 관리/감사할 수 있다.
 - 학생회비 계좌 잔액/거래내역 조회
  - 학과 장부 감사
    - 장부 승인 / 반려
 - 학생회비 납부자 관리
    - 학생회비 납부자를 조회하고 수동으로 납부/미납부 등록을 할 수 있다.

> #### 총무
학과의 총무로 학과 장부를 작성/관리할 수 있다.
  - 학생회비 계좌 잔액/거래내역 조회
  - 영수증 등록
  - 장부 등록
  - 학생회비 납부자 관리
     - 학생회비 납부자를 조회하고 수동으로 납부/미납부 등록을 할 수 있다.

> #### 일반학생
학과의 소속학생으로 장부를 조회할 수 있다.
- 장부 조회
  - 모든 감사된 장부를 조회할 수 있다.


## 프로젝트 회고
🎀 강지원
실제 학생회 업무를 자동화하는 과정을 통해 엔터프라이즈 시스템 개발의 중요성을 배울 수 있었습니다.
API 연동과 데이터 처리 로직을 개선하며, 업무 자동화의 실질적인 효과를 경험한 것이 가장 큰 성과였습니다.

