[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=FFFFFF&background=000000&random=false&width=800&lines=Pick+Your+Best+Outfit%2C+OutPick)](https://git.io/typing-svg)

![OutPick_logo](https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/113917104/b4fe368b-e161-4ff1-a600-be6e5171eb8b)

</br>

## 목차(수정 필_마지막)
[1. 프로젝트 개요](#1-프로젝트-개요)</br></br>
[2. API 명세서](#2-API-명세서)</br></br>
[3. 팀 소개](#3-팀-소개)</br></br>
[4. 기술 스택](#4-기술-스택)</br></br>
[5. 시스템 아키텍쳐](#5-시스템-아키텍쳐)</br></br>
[6. 빌드 과정 및 배포 문서](#6-빌드-과정-및-배포-문서)</br></br>
[7. 기능 테스트](#7-기능-테스트)</br></br>

<br/>
<br/>
   
>## 1. 프로젝트 개요
>프로젝트 기획서 : 
https://docs.google.com/document/d/17gZVJZlVhoHPrqbLCWg0UObO26iusi56/edit?usp=sharing&ouid=103966248639438099916&rtpof=true&sd=true

<details>
<summary>프로젝트 개요</summary>
<div markdown="1">
<div>
</br>
   2024년 현재, 기업 운영의 범위는 더욱 광범위해지고 규모가 커져가고있다. 이러한 상황에서 넓은 범위의 분야를 포괄하고, 가장 중요시되는 것이 '영업관리'이다. 기업 운영에서 중요하게 여겨지는 영업관리이지만, 기존 영업 관리 시스템은 사용자 친화적이지 않다. 따라서 기존보다 효율적이며 유연성 있는 영업관리 시스템이 필요하다. 이 부분이 영업관리 주제를 선택한 이유이자, 앞으로 프로젝트를 진행하면서 중점적으로 개선하여 개발할 부분이다.<br/>
많은 분야의 기업 영업관리가 있지만, 그 중 선택한 분야는 의류 브랜드이다. 의류 브랜드 영업관리를 선택한 이유에는 몇가지가 있다.
   <br/>
   <br/>
<center>
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/113917104/f6aada09-9e75-4b81-acd7-119bd069fd02" width="80%" height="80%"/>
</center>

    "올해 한국 패션시장규모 5.2% 성장해 49.5조" 나지현 기자 Ktnews
</br>
첫번째, 시장의 수요이다. 인간이 살아가면서 가장 중요하고 필요한 요소들 중 하나가 바로 의류이다. 인간이 현존하는 동안에는 의류 산업은 필수적이다. 또한 인류 사회가 발전함에 따라 의류는 단순한 옷, 그 자체가 아닌 자신의 개성을 드러낼 수 있는 패션 수단으로써 시장의 규모가 더욱 커지고있다.<br/><br/>
두번째, 트렌드의 영향이다. 위에서 말했듯이 의류는 개성을 드러내는 패션 수단으로 발전했다. 이에 따라서 의류 산업은 트렌드의 영향을 많이 받게되는 산업 중 하나인데, 이러한 트렌드에 맞춰서 효율적이고 유연성 있게 영업을 관리할 수 있는 시스템이 필요하다고 판단했다.<br/><br/>
세번째, 경쟁력이다. 유연하고 효율적인 영업 관리를 한다면 빠르게 대응해야하는 의류 브랜드 산업에서는 큰 경쟁력을 가질 수 있게 될 것이다. 기존보다 더 효율적이고 친화적인 UI, 트렌드에 빠른 대응을 할 수 있도록 돕는 트렌드에 대한 정보 제공 등을 활용한다면 다른 영업관리 시스템에 비해서 더욱 경쟁력을 가진 영업관리 시스템이 될 것이라고 생각했다.<br/><br/>
위와 같은 내용을 바탕으로 '의류 브랜드 산업 영업 관리 시스템'을 최종 주제로 선정하였다. 해당 프로젝트는 영업관리의 중 재고, 유통 관리 일부분을 구현하였고, 배포하는 과정의 내용을 중점적으로 다루었다.
</div>
</details>
<br/>
<br/>

>## 2. 팀 소개
<p align="center">

|<img src="https://avatars.githubusercontent.com/u/83454423?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/134581020?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/113917104?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/137466623?v=4" width="150" height="150"/>|<img src="https://avatars.githubusercontent.com/u/134200142?v=4" width="150" height="150"/>|
|:-:|:-:|:-:|:-:|:-:|
|박혜경<br/>[@BakHyegyeong](https://github.com/BakHyegyeong)|여경원<br/>[@kyungwon2won2](https://github.com/kyungwon2won2)|이영원<br/>[@nbbb9](https://github.com/nbbb9)|정설화<br/>[@Noononda](https://github.com/Noononda)|백승호<br/>[@sttoend](https://github.com/sttoend)|

</p>

<br/>
</br>

>## 3. WBS
</br>
<p align="center">
<img src="https://github.com/beyond-sw-camp/be05-fin-team06-OutPick/assets/113917104/596cebe7-840f-477f-a5f8-30ed01dcbdcb" width="100%" height="100%"/>
</p>

    Jira를 사용한 WBS
<br/>
<br/>

>## 4. 요구사항 명세서
>요구사항 명세서 : https://docs.google.com/spreadsheets/d/1gCxWgb2HCPqeUkymqBYCLILEuOzy5x106LlM4JyODRA/edit?usp=sharing

</br>
<p align="center">
<img src="https://github.com/beyond-sw-camp/be05-fin-team06-OutPick/assets/113917104/d5866800-5d8d-4317-b962-2636ced6e6f5" width="50%" height="50%"/>
</p>

<br/>
<br/>

>## 5. 화면설계서
>Figma : https://www.figma.com/design/wi8ajLQUWntGToZKFLz77M/Untitled?node-id=0%3A1&t=s3S2rUalCspQz62l-1

</br>
<p align="center">
<img src="https://github.com/beyond-sw-camp/be05-fin-team06-OutPick/assets/113917104/ba883540-7131-448c-861c-a3f6b9ec0d50" width="80%" height="80%"/>
</p>

    Figma를 통한 화면설계서

<br/>
<br/>

>## 6. ERD(사진 수정 필)

</br>
<p align="center">
<img src="https://github.com/beyond-sw-camp/be05-fin-team06-OutPick/assets/113917104/4a3c3c34-9ef5-44ca-b381-bc6e205586ae" width="=100%" height="100%"/>
</p>


    ERD Cloud를 통한 ERD 제작

<br/>
<br/>

>## 7. API 명세서(수정 필)
>API 명세서 : https://docs.google.com/spreadsheets/d/1gCxWgb2HCPqeUkymqBYCLILEuOzy5x106LlM4JyODRA/edit?usp=sharing

<API 명세서 사진 첨부>

<br/>
<br/>

>## 8. 기술 스택(수정 필)
* **Database :**
<img src="https://img.shields.io/badge/mariadb-003545?style=for-the-badge&logo=mariadb&logoColor=white"><br/>
* **Backend   :** <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"><br/>
* **Frontend :** <img src="https://img.shields.io/badge/vue-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white"><br/>
* **CI/CD :** <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/dockerhub-2496ED?style=for-the-badge&logo=dockerhub&logoColor=white"> <img src="https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">

<br/>
<br/>

>## 9. 시스템 아키텍쳐(수정 필 _ 프론트, 백엔드 나눠서_ 상의 필요)

<p align="center">
<img src="https://github.com/beyond-sw-camp/be05-fin-team06-OutPick/assets/113917104/707b43ca-984a-41c9-bdb0-5d57b0cbd44d" width="100%" height="100%"/>
</p>

    백엔드 아키텍쳐

    프론트엔드 아키텍쳐

<br/>

>## 10. 빌드 과정 및 배포 문서(수정 필)
### 1. jar파일 생성 <br/>
`명령어를 통해 jar파일을 생성합니다.`
```
./gradlew clean build
```
<center>
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/558aeae4-f3e0-4492-98ad-fd6037522a85">
</center>
<br/>
<br/>

### 2. Dockerfile<br/>

```dockerfile
FROM openjdk:17-alpine

# 외부 환경요소 : jar이 위치할 공간을 지정
ARG JAR_FILE=build/libs/*.jar

# JAR_FILE을 아래의 이름으로 COPY하겠다.
COPY ${JAR_FILE} backend.jar

# env, java는 CMD가 아니라 jar를 실행시키기 위해 entrypoint
ENTRYPOINT ["java", "-jar", "/backend.jar"]
```
<br/>

### 3. Docker-compose<br/>
<details>
<summary>Code</summary>
<div markdown="1">

```yaml
version: "3"

services:
  app:
    container_name: OutPick_Backend
    build: .
    image: lywon/outpick_backend:latest
    depends_on:
      - database
    ports:
      - "8972:8080"
    environment:
      SPRING_DATASOURCE_URL: jdbc:mariadb://database:3306/outpick?useUnicode=true
      SPRING_DATASOURCE_USERNAME: root
      SPRING_DATASOURCE_PASSWORD: 123456789
    restart: always
    links:
      - database
    # platform: linux/arm64

  database:
    image: mariadb:10.6.16
    container_name: OutPick_Backend_DB
    environment:
      MARIADB_ROOT_PASSWORD: 123456789
      MARIADB_DATABASE: outpick
    volumes:
      - ./src/main/resources/db_config/initdb.d:/docker-entrypoint-initdb.d
    ports:
      - "6033:3306"
```
</div>
</details>

<br/>

### 4. Webhook<br/>

`프론트엔드와 백엔드 깃허브 repository에서 WebHook 설정`
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/3e2a9c90-29ca-4dac-9b26-41b5f55e7d4e">
<br/>
<br/>

### 5. Jenkins Credentials<br/>
`프론트엔드, 백엔드의 git repository와 docker hub에 접근하기 위한 설정`
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/6f620db9-d8d1-492f-a5cc-3575e12752b7">
<br/>
<br/>

### 6. Jenkins Item 생성<br/>
`프론트엔드와 백엔드 item 생성`
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/60a83c86-adb4-4409-982c-0be848ff327b">

<br/>

### 7. Jenkins Item General<br/>
   - **Jenkins item_git 연결**<br/>
   `각 item에 git hub repository url 입력을 통한 연결 `
   <img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/079283a1-ace9-428b-b19c-1a7e17dd1227">
   
   - **Jenkins item_build Triggers 설정**<br/>
   `GitHub hook trigger for GITScm polling 체크`
   <img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/3d48675c-0ee2-422c-9fca-cc7caec21018">
   
   - **Jenkins item_Pipeline**<br/>
<details>
<summary>Frontend Pipeline</summary>
<div markdown="1">
    
```pipeline
pipeline {
    agent any
    // 변수 정의
    environment{
        GIT_HUB_CREDENTIALS = credentials('OutPick_Frontend')
        DOCKER_HUB_CREDENTIALS =credentials('OutPick_Docker')
        DOCKER_IMAGE_NAME = 'lywon/outpick_frontend'
        DOCKER_IMAGE_TAG = '1.0'
    }
    stages{
        stage('Build'){
            steps{
                // Build 영역 : Git 연동
                git branch : 'main', // 후에 각각의 branch로 설정
                    credentialsId : "${GIT_HUB_CREDENTIALS}",
                    url : 'https://github.com/kyungwon2won2/OutPick_Frontend.git'
            }
        }
        // 라이브러리 다운로드 - 이미 dockerfile에서 정의해두었기 때문에
        // 오류가 날 경우에만 정의
        stage('Install Dependency'){
            steps{
                bat 'npm install'
            }
        }
        // npm build
        stage('Npm build'){
            steps{
                bat 'npm run build'
            }
        }
        // 이미지 생성
        stage('Build Docker Image'){
            steps{
                script{
                    docker.build("${DOCKER_IMAGE_NAME}:${DOCKER_IMAGE_TAG}", '-f Dockerfile .')
                    // compose가 아닌 Dockerfile로 생성할 때는 -f 옵션을 주어야 한다.
                }
            }
        }
        // Docker Hub에 Push
        stage('Push To Docker Hub'){
            steps{
                script{
                    docker.withRegistry('https://registry.hub.docker.com','OutPick_Docker'){
                        docker.image("${DOCKER_IMAGE_NAME}:${DOCKER_IMAGE_TAG}").push()
                    }
                }
            }
        }
        // container 생성과 실행
        stage('Run Container'){
            steps{
                script{
                	// 기존의 Container를 삭제
                    bat 'docker ps -a'
                    bat 'docker stop OutPick_Frontend || exit 0'
                    bat 'docker rm OutPick_Frontend || exit 0'
                   	docker.withRegistry('https://registry.hub.docker.com','OutPick_Docker'){
                        docker.image("${DOCKER_IMAGE_NAME}:${DOCKER_IMAGE_TAG}").run('-d -p 8080:8080 --name OutPick_Frontend')
                    }
                }
            }
        }
    }
}
```
</div>
</details>

<details>
<summary>Backend Pipeline</summary>
<div markdown="1">

```pipeline
pipeline {
    agent any
    stages{
        stage('Build'){
            steps{
                // Build 영역 : Git 연동
                git branch : 'main', // 후에 각각의 branch로 설정
                    credentialsId : 'OutPick_Backend',
                    url : 'https://github.com/nbbb9/OutPick_Backend.git'
                bat './gradlew.bat build bootJAR'
            }
        }
        stage('Jar Clean'){
            steps{
                bat './gradlew.bat clean bootJAR'
            }
        }
        stage('Build Docker Image'){
            steps{
                script{
                    docker.build('lywon/outpick_backend')
                }
            }
        }
        // Docker hub에 push 추가
        stage('Push to Docker Hub'){
            steps{
                script{
                    docker.withRegistry('https://registry.hub.docker.com','OutPick_Docker'){
                        docker.image('lywon/outpick_backend').push()
                    }
                }
            }
        }
        stage('Deploy with Docker Compose'){
            steps{
                script{
                    // docker compose 다운로드
                    // 실행 파일 다운로드
                    bat "curl -L https://github.com/docker/compose/releases/download/2.24.6/docker-compose-Linux-x86_64 -o docker-compose"	
                    // docker compose 설치
                    bat "icacls docker-compose /grant Playdata:RX"
                    // docker compose up
                    bat ".\\docker-compose build"
                    bat ".\\docker-compose up -d"
                }
            }
        }
    }
}
```

</div>
</details>

<br/>

### 8. Build 결과<br/>
- **OutPick_Frontend**
  <img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/480b5963-bb31-4258-b7e1-e2396f595be4">
<br/>
<br/>

- **OutPick_Backend**
  <img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/e99092ee-b56f-4d80-934c-64866e7829fe">
<br/>

### 9. Docker Hub Images 생성<br/>
` Jenkins를 통한 Docker Hub Image 자동 생성`
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/613e3759-3bfa-4ddd-a6c2-47aac14e1477">

<br/>

### 10. Docker Container 생성<br/>
 `Jenkins를 통한 Docker Container 자동 생성`
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/6e0169aa-6eed-41b9-a1ef-16ce499e609e">

<br/>

>## 11. 기능 테스트
### 상품 리스트, 상세 정보
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/04dcd06d-e91d-4fe5-a7dd-89f5353397a3">
<br/>

### 상품 등록
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/c95abb30-3e9e-4e86-b0a3-18bdc4f7d497">
<br/>

### 상품 수정
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/f9504df0-b381-4b1b-a114-157e81429b14">
<br/>

### 상품 검색
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/7ee3da78-fafe-478d-8ebe-55a67ba21692">
<br/>

### 상품 삭제
<img src="https://github.com/beyond-sw-camp/be05-4th-6team-OutPick/assets/137466623/2d0ff134-73b5-41c6-b859-4a48e281f349">
<br/>
