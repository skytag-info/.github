## 항공기 정보 제공 서비스 스카이태그 
- 개발 기간 : 2025.01.03 ~ 2025.01.31 (약 4주)
- 배포 URL : 

<br>


## 프로젝트 소개

- 항공편명을 통해 항공기의 사진, 모델명, 제작일자, 기령 등의 
- 항공기 정보를 제공하는 서비스 입니다.

<br>

## 팀원 구성👨‍👩‍👧‍👦
<div align="center">

| **이한빈** | **박종설** | **최대련** | **정유상** |
|:----------:|:----------:|:----------:|:----------:|
| [<img src="https://avatars.githubusercontent.com/u/99483558?s=96&v=4" height="80" width="80"> <br/> @LuKaBery](https://github.com/LuKaBery) | [<img src="https://avatars.githubusercontent.com/u/105614086?v=4&s=96" height="80" width="80"> <br/> @JongsoulPark](https://github.com/JongsoulPark) | [<img src="https://avatars.githubusercontent.com/u/21366358?v=4&s=96" height="80" width="80"> <br/> @yellowcowCDR](https://github.com/yellowcowCDR) | [<img src="https://avatars.githubusercontent.com/u/105181225?v=4&s=96" height="80" width="80"> <br/> @YusangJeong](https://github.com/YusangJeong) |
</div>

<br>


## 1. 개발 환경

- 개발도구: Intellij IDEA - Ultimate
- 언어: Java 21 LTS<br>
- 빌드도구: Maven
- 개발
    - Spring Framework: 5.3
    - Spring Boot: 3.3.18
    - Spring Cloud
        - Spring Cloud Gateway
        - Spring Cloud Netflex(Eureka)
        - Spring Cloud Config
    - Spring Data
        - Spring Data JPA
        - Spring Data Elasticsearch
        - Spring Data Redis
    - JPA
        - QueryDSL
- 테스트
    - Junit5
    - AssertJ
    - Mockito
    - SonarQube
- 데이터베이스
    - MySQL: 8.0.25
    - Redis
- 검색엔진
    - Elastic Search: 7.11.1
- ERD
    - ERDCloud
- 버전 및 이슈관리 : Github, Github Issues, Github Project

<br>

## 2. 프로젝트 규칙

### 1) 브랜치 전략🌴

- Git-flow 전략을 기반으로 main, develop 브랜치와 feature 보조 브랜치를 운용했습니다.
- main, develop, Feat 브랜치로 나누어 개발을 하였습니다.
    - **main** 브랜치는 배포 단계에서만 사용하는 브랜치입니다.
    - **develop** 브랜치는 개발 단계에서 git-flow의 master 역할을 하는 브랜치입니다.
    - **Feat** 브랜치는 기능 단위로 독립적인 개발 환경을 위하여 사용하고 merge 후 각 브랜치를 삭제해주었습니다.

<br>

## 3. 역할 분담
