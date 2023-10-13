# boot-up1-team2

# FKREAM

리셀 서비스 KREAM을 클론한 프로젝트입니다.

## 기술 스택

* Java 11
* Spring Boot 2.7.0
* Gradle
* MyBatis
* Redis
* Docker
* MySQL
* MongoDB
* Elasticsearch
* Kibana
* Kafka
* Jenkins
* Naver Cloud Platform
* Pinpoint
* NGrinder

## 프로젝트 구조

├── api
│   ├── application
│   │   ├── config
│   │   │   ├── application.yml
│   │   │   └── database.yml
│   │   ├── controller
│   │   ├── exception
│   │   ├── mapper
│   │   ├── model
│   │   └── service
│   └── resources
│       ├── application.properties
│       └── static
│           └── images
│               └── ...
├── batch
│   └── ...
└── common
└── ...

프로젝트 목표
객체 지향 원리를 토대로 올바른 코드 작성
대용량 트래픽 처리를 고려하여 서비스 기능 구현
병목 지점 파악
응답속도 성능 개선
새로운 기술을 학습하고 프로젝트 적재적소에 적용
기술적 이슈 및 고도화
매 시간 갱신되는 실시간 검색 순위 구현: 엘라스틱서치와 카프카 사용
상품 시세 그래프를 위한 통계 작업: 카프카
엘라스틱 서치를 사용한 상품 검색 기능 구현
분산 환경에서 동시성 문제를 어떻게 해결할까?
DB 커넥션 풀 사이즈에 따른 성능 차이
자동완성 기능 성능 개선: Trie 알고리즘
가용성과 확장성 관점에서의 NoSQL과 SQL 비교
분산처리를 위한 DB Sharding
고가용성을 위한 DB replication
DB 실행 계획 분석을 통한 SQL 성능 튜닝
ngrinder 성능 테스트: 사용자 행동을 시뮬레이션한 시나리오 성능 테스트
글로벌 캐시: 분산 환경일 때 캐시는 어디에 저장될까?
로드밸런싱: 분산 환경일 때 트래픽을 어떻게 분산할까?
세션 스토리지 분리: 분산 환경일 때 세션은 어디에 저장될까?
Scale-Out 적용: 가용성, 확장성, 성능을 어떻게 개선할까?
CI/CD 환경 구성: Jenkins
푸시 알림 메세지 기능: FCM을 사용한 비동기 처리
AOP를 이용한 로직 분리
주요 기능
상품 검색
상품 등록
상품 구매
상품 판매
배송
결제
회원 관리
알림
공통사항
코드 컨벤션
Google code Style 준수
브랜치 전략
GitHub Flow를 사용하여 브랜치를 관리합니다.
Main 브랜치로부터 새로운 Feature 브랜치를 생성하고 Pull Request에 코드 리뷰를 진행한 후 Jenkins를 통한 테스트 이후 Main 브랜치로 merge 됩니다.
프로토타입
Home
[이미지]
검색
[이미지]
SHOP
[이미지]
상세 페이지
[이미지]
보유 상품 추가
[이미지]
구매, 배송, 결제
[이미지]
판매, 주문, 정산
[이미지]
MY 페이지
[이미지]
설정 상세
[이미지]
DB Diagram
[FKREAM Diagram (1)]
