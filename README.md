# recipe-note

Hong Company의 ver 1.0 버전 recipe를 기록할 수 있는 노트앱 입니다.

`ver 1.0 기획 요구사항`

* 레시피 등록
    * 해당 레시피의 재료를 등록
        * (선택사항 1) 재료의 양과 단위에 대해 계산기와 같은 UI를 제공한다.
            * 기본 단위에 대해서는 제공
            * 기본 단위 외에도 입력이 가능하게끔 제공
    * 조리 순서(page)에 대한 세부 내용 저장 (사진, 설명, 조리시간 등...)
 
* 레시피 조회
    * 등록한 레시피에 대해서 조회
    
* 레시피 시뮬레이션
    *  (선택사항 1) 재료를 준비했을 경우 체크박스와 같은 UI로 표시 가능
    * 해당 page에서 입력된 조리시간이 있을 경우 타이머 기능 제공
        * 타이머 기능 : 해당 시간이 경과했을 경우 알림 메시지 혹은 소리로서 제공
        
* 레시피 수정/삭제

## Installation

`Clone project` :

    git clone https://github.com/BrendenHJH/recipe-note.git

`현재 위치로 이동` :

    cd recipe-note
    

## 프로젝트 제약사항

* `Back-end 요구사항`
    * 필수사항
        * java 8
        * springboot 2.0
        * spring data JPA
        * H2
        * gradle, lombok
    * 선택사항
        * multi module project
        * QueryDSL
        * Spring REST Docs
        * Spring Security
        * TDD, DDD 
    * 검색사항
        * spring-data-rest       
        
* `Front-end 요구사항`

* `배포 요구사항`

## 개발 요구사항

* github를 통한 이슈 관리
    1. 이슈를 등록 (작은 기능단위로 진행)
    2. 해당 이슈번호를 넣어 브런치를 만든다.
        * ex) 쪼갠 이슈에 대한 명명 - #1(이슈번호)
    3. commit은 틈틈히! 설명은 자세히!
    4. PR 후 서로 확인 후 merge를 원칙으로 한다.
    
* branch, commit 작성에 대한 세부 룰은 정하고 시작한다.
    1. 동사(Add, Update, Fix, Refactor 등...)로 시작한다. 등등... 일관된 형식으로 작성한다.   
        

## 일정

## 기타사항 (memo)
* 도메인 설계, ERD 등의 자료는 문서화한다.
* 개발 중 발생한 이슈사항에 대해 블로그에 정리하고 해당 PR에 자세하게 작성한다.
* 큰 일정에서는 개인의 스케줄에 맞춰 잡고 공유한다.

