# To Become a Better Programmer
## 설명
Description에도 써있다시피 jwasham의 Coding Interview University에서 영감을 받아 시작하게 되었다.
물론 해당 저장소에도 [한국어로 번역된 판](https://github.com/jwasham/coding-interview-university/blob/master/translations/README-ko.md)이 존재하지만
막상 뚜껑을 열어보면 안내만 한글일 뿐이지 그가 걸어놓은 링크나 자료 모두 영어로 구성돼있단 걸 알 수 있을 것이다.
물론 영어에 능숙하면 그가 올려놓은 양질의 자료를 쉽고 빠르게 탐독할 수 있겠지만 나는 영어에 능숙하지 않은 프로그래머들이 한국에 많이 있다는 걸 안다.
나 또한 그 중 하나이다. 

그런 의미로 여기에서 한국판 Coding Interview University를 작성하려 한다.
약간의 차이가 있다면 Interview University라는 이름과는 달리 코딩 면접을 위한 프로젝트는 아니라는 점이다.
그냥 스스로도 더 나은 프로그래머가 되고 싶어서, 또 한글로 된 양질의 자료도 많은데 파편화돼있는 게 아쉬워서 시작하게 됐다.
그래서 저장소의 이름 자체도 To Become a Better Programmer(더 나은 프로그래머 되기)로 정하였다.


되도록이면 한글로 된 자료 중에 쉽고 알아보기 쉬운 자료를 차용할 것이며, 직접 코드를 써야할 경우에는
비전공자들도 쉽게 알아볼 수 있는 python3으로 작성할 예정이다.
목차나 내용은 jwasham의 Coding Interview University을 참고할 것이나 완전히 같지는 않을 것이며, 정렬은 123->abc->가나다 순서대로 할 것이다.
그리고 [내 블로그](https://this-programmer.tistory.com/)에 있는 글들도 이용할 예정이다.

## 목차
- [강의(Lecture)](#강의)
- [네트워크(Network)](#네트워크)
- [데이터베이스(Database)](#데이터베이스)
- [디자인패턴(Design Pattern)](#디자인패턴)
- [생산성 향상 도구들(Utilities)](#생산성-향상-도구들)
- [소프트웨어 공학(Software engineering)](#소프트웨어-공학)
- [소프트웨어 인프라(Software infrastructure)](#소프트웨어-인프라)
- [알고리즘(Algorithm)](#알고리즘)
- [인공지능(Artificial Intelligence)](#인공지능)
- [언어와 프레임워크(Language and Framework)](#언어와-프레임워크)
- [운영체제(Operating System)](#운영체제)
- [자료구조(Data Structure)](#자료구조)
- [좋은 글들(Wellmade Posts)](#좋은-글들)
- [컴퓨터 공학(Computer engineering)](#컴퓨터-공학)  
- [유용한 사이트 & 블로그(Good sites & blogs)](#유용한-사이트-&-블로그)

## 강의
- [gRPC 와 python 을 활용한 Microservice 개발기 - 송지형 - PyCon.KR 2019](https://www.youtube.com/watch?v=KGAernd-42M)
- InfluxDB
  - [인플럭스DB(InfluxDB) #1 - 개요 및 특징](https://andro-jinu.tistory.com/14)
- k8s
  - [도커와 쿠버네티스 시작하기](https://gurumee92.tistory.com/254?category=957852)
  
## 기타등등
- [Base64 인코딩이란?](https://effectivesquid.tistory.com/entry/Base64-%EC%9D%B8%EC%BD%94%EB%94%A9%EC%9D%B4%EB%9E%80)
- [Base64이란 무엇일까? / Base64 사용 이유와 인코딩과 디코딩](https://devuna.tistory.com/41)
- [NVIDIA-SMI 확인방법 및 활용하기](https://kyumdoctor.co.kr/10)

## 네트워크
- [AB(Apache http server Benchmarking tool)를 활용한 벤치마킹 테스트](https://sysops.tistory.com/77)
- [[Firebase] FCM에 대해서 알아보자. 🔔](https://donghun.dev/Firebase-Cloud-Messaging)
- [GET과 POST의 차이](https://hongsii.github.io/2017/08/02/what-is-the-difference-get-and-post/)
- [HTTP와 HTTPS의 차이점](https://dany-it.tistory.com/96)
- [HTTP Protocols](https://ko.wikipedia.org/wiki/HTTP)
- [JWT(Json Web Token)란?](https://mangkyu.tistory.com/56)
- [JSON이란?](https://ko.wikipedia.org/wiki/JSON)
- [OAuth란? 그리고 OAuth1, OAuth2](https://minwan1.github.io/2018/02/24/2018-02-24-OAuth/)
- [OAuth2를 이용한 SSO 환경 구축 (1/2)](http://www.nextree.co.kr/oauth-2reul-iyonghan-sso-hwangyeong-gucug-1-2/)
- [OAuth2를 이용한 SSO 환경 구축 (2/2)](http://www.nextree.co.kr/oauth-2reul-iyonghan-sso-hwangyeong-gucug-2-2/)
- [SSO(Single Sign-On)이란?](https://toma0912.tistory.com/75)
- [TCP/IP의 이해](https://m.blog.naver.com/jhc9639/221411218450?referrerCode=1)
- [TLS (Transport Layer Security)](https://brownbears.tistory.com/402)
- [브라우저의 렌더링 과정](https://medium.com/%EA%B0%9C%EB%B0%9C%EC%9E%90%EC%9D%98%ED%92%88%EA%B2%A9/%EB%B8%8C%EB%9D%BC%EC%9A%B0%EC%A0%80%EC%9D%98-%EB%A0%8C%EB%8D%94%EB%A7%81-%EA%B3%BC%EC%A0%95-5c01c4158ce)
- [실시간 스트리밍 프로토콜-RTSP(Real Time Streaming Protocol)란?](https://mingtrace.tistory.com/442)
- [웹 브라우저에 URL을 입력하면 어떤 일이 일어날까?](https://owlgwang.tistory.com/1)
- [웹의 동작 원리](https://velog.io/@wonhee010/%EC%9B%B9%EC%9D%98-%EB%8F%99%EC%9E%91-%EC%9B%90%EB%A6%AC)
- [쿠키와 세션의 차이](https://jeong-pro.tistory.com/80)
- [토근 기반 인증에서 bearer는 무엇일까?](https://velog.io/@cada/%ED%86%A0%EA%B7%BC-%EA%B8%B0%EB%B0%98-%EC%9D%B8%EC%A6%9D%EC%97%90%EC%84%9C-bearer%EB%8A%94-%EB%AC%B4%EC%97%87%EC%9D%BC%EA%B9%8C)
- GraphQL
  - [GraphQL 개념잡기](https://tech.kakao.com/2019/08/01/graphql-basic/)
  - [GraphQL이란 무엇인가요?](https://www.redhat.com/ko/topics/api/what-is-graphql)
- gRPC
  - [Google Protobuf 정리 내용 및 사용방법](https://jins-dev.tistory.com/entry/Google-Protobuf-%EC%A0%95%EB%A6%AC-%EB%82%B4%EC%9A%A9-%EB%B0%8F-%EC%82%AC%EC%9A%A9%EB%B0%A9%EB%B2%95)
  - [gRPC 1 - gRPC란?](https://chacha95.github.io/2020-06-15-gRPC1/)
  - [python 에서 gRPC 테스트 해보기](https://kim-daeyong.github.io/2021-07-23-grpc_python/)
- RestAPI
  - [REST API 제대로 알고 사용하기](https://meetup.toast.com/posts/92)
  - [그놈의 RESTful API. 한 줄로 정의하자면](https://this-programmer.tistory.com/entry/%EA%B7%B8%EB%86%88%EC%9D%98-RESTful-API-%ED%95%9C-%EC%A4%84%EB%A1%9C-%EC%A0%95%EC%9D%98%ED%95%98%EC%9E%90%EB%A9%B4)
- 로드밸런싱(Load Balancing)
  - [로드 밸런서(Load Balancer)란?](https://nesoy.github.io/articles/2018-06/Load-Balancer)
  - [로드밸런싱방식 종류](https://medium.com/@pakss328/%EB%A1%9C%EB%93%9C%EB%B0%B8%EB%9F%B0%EC%84%9C%EB%9E%80-l4-l7-501fd904cf05)
- 프록시 서버(Proxy Server)
  - [프록시 서버란?(1)](https://brownbears.tistory.com/191)
  - [프록시 서버란?(2)](https://soul0.tistory.com/230)

## 데이터베이스
- [Clustering vs Replication vs Sharding](https://jordy-torvalds.tistory.com/94)
- [DB 트랜잭션 (Transaction)의 ACID 속성과 분산시스템 BASE 속성](https://velog.io/@issac/DB-%ED%8A%B8%EB%9E%9C%EC%9E%AD%EC%85%98-Transaction%EC%9D%98-ACID-%EC%86%8D%EC%84%B1%EA%B3%BC-%EB%B6%84%EC%82%B0%EC%8B%9C%EC%8A%A4%ED%85%9C-BASE-%EC%86%8D%EC%84%B1)
- [Inner Join과 Outer Join 차이점](https://server-engineer.tistory.com/306)
- [Lock에 대해서 알아보자 - 기본편](https://sabarada.tistory.com/121)
- [MongoDB의 Transaction과 session문제](https://crmrelease.tistory.com/138)
- [ORM이란](https://gmlwjd9405.github.io/2019/02/01/orm.html)
- [TICK Stack(Telegraf + InfluxDB + Chronograf + Kapacitor)](https://notemusic.tistory.com/67)
- [데이터베이스 튜닝 (DB Tuning)](http://blog.skby.net/%EB%8D%B0%EC%9D%B4%ED%84%B0%EB%B2%A0%EC%9D%B4%EC%8A%A4-%ED%8A%9C%EB%8B%9D-db-tuning/)
- [왜 데이터베이스(DB) 튜닝을 해야할까?](https://travislife.tistory.com/25)
- [인덱스(index)란?](https://mangkyu.tistory.com/96)
- [저장 프로시저](https://ko.wikipedia.org/wiki/%EC%A0%80%EC%9E%A5_%ED%94%84%EB%A1%9C%EC%8B%9C%EC%A0%80)
- [정규화(Normalization)](https://mangkyu.tistory.com/28?category=761304)
- [클러스터링 vs 리플리케이션 vs 샤딩](https://velog.io/@gkskaks1004/%ED%81%B4%EB%9F%AC%EC%8A%A4%ED%84%B0%EB%A7%81-vs-%EB%A6%AC%ED%94%8C%EB%A6%AC%EC%BC%80%EC%9D%B4%EC%85%98-vs-%EC%83%A4%EB%94%A9)
- [트랜잭션 격리 수준(Transaction Isolation Level)](https://dar0m.tistory.com/225)
- [트랜잭션이란? (Transaction)](https://limkydev.tistory.com/100?category=974039)
- [트랜잭션과 격리성](https://sabarada.tistory.com/117)
- [트랜잭션(transaction)이란?(1)](https://mommoo.tistory.com/62)
- [트랜잭션(transaction)이란?(2)](https://devuna.tistory.com/30)
- [트리거(Trigger)란?](https://limkydev.tistory.com/154)
- [효과적인 DB index 설정하기](https://velog.io/@jwpark06/%ED%9A%A8%EA%B3%BC%EC%A0%81%EC%9D%B8-DB-index-%EC%84%A4%EC%A0%95%ED%95%98%EA%B8%B0)
- MySQL
  - [How to bind MySQL server to more than one IP address?](https://serverfault.com/questions/139323/how-to-bind-mysql-server-to-more-than-one-ip-address)
- Telegraf
  - [How to Use Custom Telemetry From Telegraf in New Relic One](https://newrelic.com/blog/how-to-relic/how-to-collect-telegraf-metrics)
  - [Telegraf input plugins](https://docs.influxdata.com/telegraf/v1.9/plugins/inputs/)

## 디자인패턴
- [Design Patterns on python](https://brownbears.tistory.com/category/%EA%B3%B5%EB%B6%80/%EB%94%94%EC%9E%90%EC%9D%B8%20%ED%8C%A8%ED%84%B4)
- [Monorepo? Yarn Workspace!](https://medium.com/@deptno/monorepo-yarn-workspace-e81e3e078100)
- [MVC패턴이란](https://m.blog.naver.com/jhc9639/220967034588)
    
## 생산성 향상 도구들
- [Python용 AWS SDK(Boto3)](https://aws.amazon.com/ko/sdk-for-python/)
- [ERD CLOUD](https://www.erdcloud.com/)
- [gitstar-ranking(깃허브 별 개수 랭킹 알려주는 사이트)](https://gitstar-ranking.com)
- [Graphviz 소개](https://narusas.github.io/2019/01/25/Graphviz.html)
- [POSTMAN과 JSON Placeholder(JSON을 테스트하는 가장 좋은 방법)](https://this-programmer.tistory.com/entry/JSON%EC%9D%84-%ED%85%8C%EC%8A%A4%ED%8A%B8%ED%95%98%EB%8A%94-%EA%B0%80%EC%9E%A5-%EC%A2%8B%EC%9D%80-%EB%B0%A9%EB%B2%95-POSTMAN%EA%B3%BC-JSON-Placeholder?category=767889)
- [regex101.com(정규식 짤 때 도움되는 사이트)](https://this-programmer.tistory.com/entry/%EC%A0%95%EA%B7%9C%EC%8B%9D-%EC%A7%A4-%EB%95%8C-%EC%97%84%EC%B2%AD%EB%82%98%EA%B2%8C-%EB%8F%84%EC%9B%80%EC%9D%B4-%EB%90%98%EB%8A%94-%EC%82%AC%EC%9D%B4%ED%8A%B8-regex101com?category=772368)
- [[Telegraf + influxDB + Grafana]10분만에 데브옵스를 위한 모니터링 시스템 구축하기](https://blog.voidmainvoid.net/91])
- [Wappalyzer(웹사이트 구성요소를 볼 수 있는 크롬 확장 프로그램)](https://this-programmer.tistory.com/entry/%EC%9B%B9%EC%82%AC%EC%9D%B4%ED%8A%B8%EB%A5%BC-%EB%AD%98%EB%A1%9C-%EB%A7%8C%EB%93%A4%EC%97%88%EB%8A%94%EC%A7%80-%EC%95%8C-%EC%88%98-%EC%9E%88%EA%B2%8C-%ED%95%B4%EC%A3%BC%EB%8A%94-%ED%81%AC%EB%A1%AC-%ED%99%95%EC%9E%A5-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%A8-Wappalyzer?category=772368)
- [무료 DB Tool (DBeaver)](https://m.blog.naver.com/skykbc/221426494422)

## 소프트웨어 공학
- [계층구조(Hierarchy)](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=sipack7297&logNo=220427434575)
- [데몬 (컴퓨팅)](https://ko.wikipedia.org/wiki/%EB%8D%B0%EB%AA%AC_(%EC%BB%B4%ED%93%A8%ED%8C%85))
- [Active Record VS Data Mapper](https://velog.io/@hyob/Active-Record-VS-Data-Mapper)
- [Call by Value와 Call by Reference](https://re-build.tistory.com/3)
- [Coroutine과 Subroutine의 차이](https://kotlinworld.com/214)
- [Coroutine은 어떻게 스레드 작업을 최적화 하는가?](https://kotlinworld.com/139)
- [Coroutine 기초](https://medium.com/@sunminlee89/%EC%BD%94%ED%8B%80%EB%A6%B0-%EC%BD%94%EB%A3%A8%ED%8B%B4-coroutine-%EA%B8%B0%EC%B4%88-1342ae6916ce)
- [IoC, DI, DIP 개념 잡기](https://vagabond95.me/posts/about-ioc-dip-di/)
- [고가용성](https://ko.wikipedia.org/wiki/%EA%B3%A0%EA%B0%80%EC%9A%A9%EC%84%B1)
- [객체지향 설계 5원칙 - SOLID란 무엇일까?](https://devlog-wjdrbs96.tistory.com/380)
- [장애 허용 시스템](https://ko.wikipedia.org/wiki/%EC%9E%A5%EC%95%A0_%ED%97%88%EC%9A%A9_%EC%8B%9C%EC%8A%A4%ED%85%9C)
- [프로그램과 프로세스와 스레드의 차이](https://velog.io/@raejoonee/%ED%94%84%EB%A1%9C%EC%84%B8%EC%8A%A4%EC%99%80-%EC%8A%A4%EB%A0%88%EB%93%9C%EC%9D%98-%EC%B0%A8%EC%9D%B4)
- [프로세스 격리란 무엇입니까?](https://www.netinbag.com/ko/internet/what-is-process-isolation.html)
- [함수(function)와 메소드(method)의 차이](https://this-programmer.tistory.com/entry/%ED%95%A8%EC%88%98Function%EC%99%80-%EB%A9%94%EC%86%8C%EB%93%9CMethod%EC%9D%98-%EC%B0%A8%EC%9D%B4)

## 소프트웨어 인프라
- [datadog integrations](https://docs.datadoghq.com/integrations/#all)
- [devops란 - from aws](https://aws.amazon.com/ko/devops/what-is-devops/)
- [Failover, 페일오버란 무엇인가](https://m.blog.naver.com/on21life/221221178100)
- [Sentry.io 에러 로깅](https://woolbro.tistory.com/93)
- [데이터 파이프라인이란 무엇인가?](https://blog.voidmainvoid.net/265)
- [마이크로서비스 인증/인가 패턴](https://engineering-skcc.github.io/microservice%20outer%20achitecture/outer-arch-Auth/)
- [배포 방법 정리 (고정/롤링/블루-그린/카나리 릴리즈 배포)](https://devpouch.tistory.com/136)
- [안정적인 운영을 완성하는 모니터링, 프로메테우스와 그라파나](https://velog.io/@moey920/%EC%95%88%EC%A0%95%EC%A0%81%EC%9D%B8-%EC%9A%B4%EC%98%81%EC%9D%84-%EC%99%84%EC%84%B1%ED%95%98%EB%8A%94-%EB%AA%A8%EB%8B%88%ED%84%B0%EB%A7%81.-%ED%94%84%EB%A1%9C%EB%A9%94%ED%85%8C%EC%9A%B0%EC%8A%A4%EC%99%80-%EA%B7%B8%EB%9D%BC%ED%8C%8C%EB%82%98)
- [오케스트레이션(Orchestration)이란?](https://www.redhat.com/ko/topics/automation/what-is-orchestration)
- [코드 작성 없이 데이터 파이프라인 운영하기](https://blog.mathpresso.com/%EC%BD%94%EB%93%9C-%EC%9E%91%EC%84%B1-%EC%97%86%EC%9D%B4-%EB%B0%B0%EC%B9%98-%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8-%EC%9A%B4%EC%98%81%ED%95%98%EA%B8%B0-84769d598674)
- [코드형 인프라(IaC)란?](https://www.redhat.com/ko/topics/automation/what-is-infrastructure-as-code-iac)
- [프로비저닝(Provisioning)이란? 개념, 종류, 자동화 방법](https://www.redhat.com/ko/topics/automation/what-is-provisioning)
- [현기증나는 인프라, 배포 용어들(IaC, 오케스트레이션, CI/CD, DEVOPS, 프로비저닝 등등) 정리](https://this-programmer.tistory.com/447)
- Airflow
  - [Airflow와 함께한 데이터 환경 구축기(feat. Airflow on Kubernetes)](https://tech.socarcorp.kr/data/2021/06/01/data-engineering-with-airflow.html)
  - [Airflow란?](https://velog.io/@jjongbumeee/Airflow1)
  - [Airflow vs. Kubeflow](https://velog.io/@rhee519/airflow-vs-kubeflow)
  - [[Airflow] 에어플로우 시작하기: 개념 및 설치](https://data-engineer-tech.tistory.com/30)
  - [Apache 에어플로우(Airflow) 시작하기 - Airflow란?](https://lsjsj92.tistory.com/631)
  - [DAG가 뭔가요?](https://bossm0n5t3r.github.io/posts/71/)
  - [Helm Chart for Apache Airflow](https://airflow.apache.org/docs/helm-chart/stable/index.html)
  - [Kubeflow vs Airflow – Which is Better For Your Business: 4 Critical Differences](https://hevodata.com/learn/kubeflow-vs-airflow/)
- AWS
  - [aws 프리티어 계속 쓰기 (with gmail)](https://this-programmer.tistory.com/472)
  - [Mac OS에 AWS Cli 설정하기](https://longtermsad.tistory.com/13)
- CircleCI
  - [CircleCI 맛보기](https://velog.io/@priveate/CircleCI-%EB%A7%9B%EB%B3%B4%EA%B8%B0)
- Docker
  - [Docker container가 localhost를 볼 수 있게 하는 방법](https://this-programmer.tistory.com/494)
  - [docker, cronjob 하는 container 만들기 + supervisor, 환경변수 적용하기](https://this-programmer.tistory.com/488)
  - [Podman 소개](https://dejavuhyo.github.io/posts/podman/)
  - [도커 컨테이너는 가상머신인가요? 프로세스인가요?](https://www.44bits.io/ko/post/is-docker-container-a-virtual-machine-or-a-process)
  - [도커(Docker)로 CentOS 이미지 systemctl 사용하기](https://this-programmer.tistory.com/entry/%EB%8F%84%EC%BB%A4Docker%EB%A1%9C-CentOS-%EC%9D%B4%EB%AF%B8%EC%A7%80-systemctl-%EC%82%AC%EC%9A%A9%ED%95%98%EA%B8%B0-2-failed-to-get-DBus-connection-Operation-not-permitted)
  - [초보를 위한 도커 안내서 - 도커란 무엇인가?](https://subicura.com/2017/01/19/docker-guide-for-beginners-1.html)
- ElasticSearch
  - [CRUD - 입력, 조회, 수정, 삭제](https://esbook.kimjmin.net/04-data/4.2-crud)
  - [EFK Stack 구성](http://www.iorchard.net/2019/06/17/efk_stack_%EA%B5%AC%EC%84%B1.html)
  - [[ELK] ELK Stack 이란? 소개, 정의](https://velog.io/@holidenty/ELK-ELK-Stack-%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%BC%EA%B9%8C)
  - [Elasticsearch-Kibana를 이용한 로그 모니터링 (1)](https://gintrie.tistory.com/45?category=389204)
  - [Elasticsearch에 fluentd를 얹은 EFK stack 구축하기(with kubernetes)](https://nangman14.tistory.com/68)
  - [ELK 스택](https://aws.amazon.com/ko/opensearch-service/the-elk-stack/)
  - [Elasticsearch란? (개념 및 종류, RDBMS와 차이)](https://choseongho93.tistory.com/231)
  - [Using ElasticSearch, Fluentd and Kibana (for log aggregation)](https://technology.amis.nl/continuous-delivery/containers/using-elasticsearch-fluentd-and-kibana-for-log-aggregation/)
  - [macOS에서 ELK stack 구성하기 (elasticksearch)](https://this-programmer.tistory.com/476)
  - [엘라스틱서치로 파이썬(Python) 어플의 구조화 로깅(Structured Logging) 구현하기 (1)](https://blog.naver.com/olpaemi/221967869387)
- FluentD
  - [Fluentd(td-agent) 설치 및 실행 방법](https://jangseongwoo.github.io/fluentd/fluentd_install/)
  - [Fluentd + Elasticsearch + Kibana EFK Stack 구축하기](https://smoh.tistory.com/415)
  - [Fluentd(td-agent) output plugin](https://jangseongwoo.github.io/fluentd/fluentd_output_plugin_operation_check/)
  - [[Fluentd] 로그 수집 패턴, Fluentd 개념 정리](https://nyyang.tistory.com/120)
  - [[FluentD] FluentD 설치 및 실행 방법](https://jinseongsoft.tistory.com/339)
  - [Fluentd란?](https://velog.io/@seho100/Fluentd%EB%9E%80)
  - [[Fluentd]를 이용한 로그 수집 -1.Fluentd란?](https://dev-life.tistory.com/2)
  - [Fluentd 와 LogStash 비교](https://grip.news/archives/1340)
  - [Fluentd 의 활용. ElasticSearch, Kibana 을 사용한 Nginx Log 수집](https://grip.news/archives/1344)
  - [Kuberentes 에서 fluentd + elasticsearch 연동하기](https://ksr930.tistory.com/146)
- Git
  - [django로 github actions찍먹해보기](https://this-programmer.tistory.com/474) 
  - [Github Action 사용법 정리](https://zzsza.github.io/development/2020/06/06/github-action/)
  - [github actions로 자동 1일 1커밋 봇 만들기](https://this-programmer.tistory.com/490)
  - [Github Action을 마켓에 등록해보자](https://medium.com/jung-han/github-action%EC%9D%84-%EB%A7%88%EC%BC%93%EC%97%90-%EB%93%B1%EB%A1%9D%ED%95%B4%EB%B3%B4%EC%9E%90-7a181a0b4a8f)
  - [Github Action을 이용한 CI/CD 개발 주기 자동화](https://velog.io/@youngerjesus/Github-Action%EC%9D%84-%EC%9D%B4%EC%9A%A9%ED%95%9C-CICD-%EA%B0%9C%EB%B0%9C-%EC%A3%BC%EA%B8%B0-%EC%9E%90%EB%8F%99%ED%99%94)
  - [Git Rebase & Squash](https://velog.io/@ppl8709/git-rebase)
  - [Github Action 빠르게 시작하기](https://jonnung.dev/devops/2020/01/31/github_action_getting_started/)
  - [Github Action에 대한 소개와 사용법](https://velog.io/@ggong/Github-Action%EC%97%90-%EB%8C%80%ED%95%9C-%EC%86%8C%EA%B0%9C%EC%99%80-%EC%82%AC%EC%9A%A9%EB%B2%95)
  - [Github에 잘못 올라간 파일 삭제하기](https://gmlwjd9405.github.io/2018/05/17/git-delete-incorrect-files.html)
  - [pre-commit 도구로 Git Hook 사용하기](https://www.daleseo.com/pre-commit/)
  - [맥북에서 GitHub 계정 여러개 사용하는 방법!](https://somjang.tistory.com/entry/%EB%A7%A5%EB%B6%81%EC%97%90%EC%84%9C-GitHub-%EA%B3%84%EC%A0%95-%EC%97%AC%EB%9F%AC%EA%B0%9C-%EC%82%AC%EC%9A%A9%ED%95%98%EB%8A%94-%EB%B0%A9%EB%B2%95)
  - [초심자를 위한 Github 협업 튜토리얼 (with 토끼와 거북이)](https://milooy.wordpress.com/2017/06/21/working-together-with-github-tutorial/)
  - [훅으로 Git에 훅 들어가기](https://techblog.woowahan.com/2530/)
- Gitops
  - [GitOps and Kubernetes](https://kangwoo.kr/2019/12/18/gitops-and-kubernetes/)
  - [GitOps란?](https://www.redhat.com/ko/topics/devops/what-is-gitops)
  - [GipOps와 ArgoCD란?](https://gruuuuu.github.io/cloud/argocd-gitops/)
- Jenkins
  - [[Jenkins]Git 연동하기(Git Token 발급 + Jenkins Credential 등록)](https://velog.io/@zzarbttoo/JenkinsGit-%EC%97%B0https://velog.io/@jay2u8809/Crontab%ED%81%AC%EB%A1%A0%ED%83%AD-%EC%8B%9C%EA%B0%84-%EC%84%A4%EC%A0%95%EB%8F%99%ED%95%98%EA%B8%B0Git-Token-%EB%B0%9C%EA%B8%89-Jenkins-Credential-%EB%93%B1%EB%A1%9D)
  - [[Jenkins] 젠킨스란 무엇인가](https://ict-nroo.tistory.com/31)
  - [[Jenkins] Git과 연동하기](https://yeonyeon.tistory.com/58)
  - [[Jenkins] [github] Jenkins와 github 연동하기](https://goddaehee.tistory.com/258)
  - [[Jenkins] Jenkins와 Github로 CI 구성하기(Blue Ocean)](https://velog.io/@solchan/Jenkins-Jenkins%EC%99%80-Github%EB%A1%9C-CI-%EA%B5%AC%EC%84%B1%ED%95%98%EA%B8%B0)
  - [Mac 에서 Jenkins 설치하기](https://wan-blog.tistory.com/74)
- Kafka
  - [[Apache kafka 조금 아는 척하기] 카프카란?](https://freedeveloper.tistory.com/396)
  - [Introducing ksqlDB](https://devidea.tistory.com/73)
  - [KSQL](https://www.confluent.io/ko-kr/product/ksql/)
  - [Kafka란?](https://galid1.tistory.com/793)
  - [Kafka 스트림 처리 : ksqlDB로 양말 분류](https://ichi.pro/ko/kafka-seuteulim-cheoli-ksqldblo-yangmal-bunlyu-250788691961603)
- Kubeflow
  - [Airflow vs. Kubeflow](https://velog.io/@rhee519/airflow-vs-kubeflow)
  - [Kubeflow vs Airflow – Which is Better For Your Business: 4 Critical Differences](https://hevodata.com/learn/kubeflow-vs-airflow/)
- Kubernetes, k8s
  - [Affinity & NodeSelector 사용하기](https://aws-diary.tistory.com/123)
  - [AWS에 kops로 쿠버네티스 클러스터 구축하기](https://twofootdog.tistory.com/43#:~:text=1.%20kops%EB%9E%80%20%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80,%EC%82%AD%EC%A0%9C%ED%95%A0%20%EC%88%98%20%EC%9E%88%EB%8F%84%EB%A1%9D%20%EC%A7%80%EC%9B%90%ED%95%9C%EB%8B%A4.)
  - [Calico CNI 동작원리 이해하기](https://velog.io/@200ok/Kubernetes-Calico-CNI-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0)
  - [Hello Minikube](https://kubernetes.io/ko/docs/tutorials/hello-minikube/)
  - [Helm 이란?](https://tech.ktcloud.com/51)
  - [Istio란 무엇인가?](https://twofootdog.tistory.com/78)
  - [Istio 아키텍처와 기능 이해하기](https://velog.io/@beryl/Istio-%EA%B0%9C%EB%85%90)
  - [Job/CronJob](https://kimjingo.tistory.com/135)
  - [[K8S] Kubernetes의 HPA를 활용한 오토스케일링(Auto Scaling)](https://medium.com/dtevangelist/k8s-kubernetes%EC%9D%98-hpa%EB%A5%BC-%ED%99%9C%EC%9A%A9%ED%95%9C-%EC%98%A4%ED%86%A0%EC%8A%A4%EC%BC%80%EC%9D%BC%EB%A7%81-auto-scaling-2fc6aca61c26)
  - [kubectl 개요](https://kubernetes.io/ko/docs/reference/kubectl/overview/)
  - [[Kubernetes] ArgoCD 정리 (1) - GitOps Repo 구성과 ArgoCD 설치](https://asuraiv.tistory.com/20)
  - [Kubernetes : Local에 설치하기](https://velog.io/@sixhustle/k8s-started-1)
  - [Kubernetes 좀 더 잘 이해하기](https://suhwan.dev/2019/04/22/understanding-kubernetes-design/)
  - [Kubernetes 환경에 affinity, anti-affinity 적용하기](https://malgogi-developer.tistory.com/32)
  - [Pod 스케쥴링 #2 Affinity](https://bcho.tistory.com/1346)
  - [쿠버네티스 교육과 인증(공식)](https://kubernetes.io/ko/training/)
  - [쿠버네티스 문서(공식)](https://kubernetes.io/ko/docs/home/)
  - [쿠버네티스 컴포넌트](https://kubernetes.io/ko/docs/concepts/overview/components/)
  - [쿠버네티스 Ingress 개념 및 적용방법](https://twofootdog.tistory.com/23)
  - [쿠버네티스 - 매니페스트, YAML파일, 파드(manifest, YAML 파일, pod)](https://blog.naver.com/PostView.naver?blogId=ghdalswl77&logNo=222388293445&parentCategoryNo=&categoryNo=90&viewDate=&isShowPopularPosts=true&from=search)
  - [파드 라이프사이클](https://kubernetes.io/ko/docs/concepts/workloads/pods/pod-lifecycle/)
  - [프라이빗 레지스트리에서 이미지 받아오기](https://kubernetes.io/ko/docs/tasks/configure-pod-container/pull-image-private-registry/)
- Prometheus
  - [MySQL 데이터 모니터링 – Prometheus MySQL Expoter](http://mysqldbadmtech.blogspot.com/2016/12/pmm-180-mysql-prometheus-mysql-exporter.html)
  - [Prometheus란?](https://medium.com/finda-tech/prometheus%EB%9E%80-cf52c9a8785f)
  - [Prometheus란 무엇인가](https://gurumee92.tistory.com/220)
  - [Prometheus and Grafana setup in Minikube](https://blog.marcnuri.com/prometheus-grafana-setup-minikube)

## 알고리즘
- [DFS와 BFS](https://this-programmer.tistory.com/entry/%EB%B0%B1%EC%A4%801260%ED%8C%8C%EC%9D%B4%EC%8D%AC-DFS%EC%99%80-BFS)
- [FizzBuzz 문제](https://bryan.wiki/260)
- [Lock Free 알고리즘(Non-Blocking 알고리즘)](https://effectivesquid.tistory.com/entry/Lock-Free-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98Non-Blocking-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98)
- [RAFT ALGORITHM](https://dinonotes.com/archives/909#:~:text=RAFT%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EC%9D%80%20Consensus%20Algorithm,%ED%95%A9%EC%9D%98%EB%A5%BC%20%ED%95%98%EB%8A%94%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98%EC%9D%B4%EB%8B%A4.)
- [논 블로킹 알고리즘(Non-blocking Algorithms)](https://parkcheolu.tistory.com/33)
- [동적 계획법(Dynamic Programming)](https://ko.wikipedia.org/wiki/%EB%8F%99%EC%A0%81_%EA%B3%84%ED%9A%8D%EB%B2%95)
- [브루트 포스(Brute Force)](https://steemit.com/kr-dev/@gyeryak/easyalgo-2-bruteforce)
- [빅오 표기법(Big-O Notation), 시간 복잡도, 공간 복잡도](https://cjh5414.github.io/big-o-notation/)
- [에라토스테네스의 체(Sieve of Eratosthenes)](https://ko.wikipedia.org/wiki/%EC%97%90%EB%9D%BC%ED%86%A0%EC%8A%A4%ED%85%8C%EB%84%A4%EC%8A%A4%EC%9D%98_%EC%B2%B4)
- [이진탐색](https://namu.wiki/w/%EC%9D%B4%EC%A7%84%20%ED%83%90%EC%83%89)
- [정렬 알고리즘](https://namu.wiki/w/%EC%A0%95%EB%A0%AC%20%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98)
- [정렬 알고리즘 비교](https://ratsgo.github.io/data%20structure&algorithm/2017/10/19/sort/)
- [탐욕법(Greedy Algorithm)과 그 종류](https://janghw.tistory.com/entry/%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98-Greedy-Algorithm-%ED%83%90%EC%9A%95-%EC%95%8C%EA%B3%A0%EB%A6%AC%EC%A6%98)
- [피보나치 수열을 구하는 세 가지 방법. (재귀, 동적 계획법, 반복)](https://makefortune2.tistory.com/60)
- [해시 함수](https://ko.wikipedia.org/wiki/%ED%95%B4%EC%8B%9C_%ED%95%A8%EC%88%98)

## 자료구조
- [B-Tree, B+ Tree](https://ssup2.github.io/theory_analysis/B_Tree_B+_Tree/)
- [Hash, Hashing, Hash Table(해시, 해싱 해시테이블) 자료구조의 이해](https://velog.io/@cyranocoding/Hash-Hashing-Hash-Table%ED%95%B4%EC%8B%9C-%ED%95%B4%EC%8B%B1-%ED%95%B4%EC%8B%9C%ED%85%8C%EC%9D%B4%EB%B8%94-%EC%9E%90%EB%A3%8C%EA%B5%AC%EC%A1%B0%EC%9D%98-%EC%9D%B4%ED%95%B4-6ijyonph6o)
- [Linked list (연결 리스트) 란 무엇인가?](https://supermemi.tistory.com/67)
- [Rope](https://en.wikipedia.org/wiki/Rope_(data_structure))
- [배열(Array)과 리스트(List)](https://wayhome25.github.io/cs/2017/04/17/cs-18-1/)
- [이진 트리(Binary Tree)의 종류](https://hsc-tech.tistory.com/7)
- [이진 트리](https://thebook.io/007031/part01/ch03/07/01/)
- [이진탐색트리(Binary Search Tree)](https://ratsgo.github.io/data%20structure&algorithm/2017/10/22/bst/)
- [자료구조와 시간복잡도](https://daelumgi.postype.com/post/5270208)
- [해시맵 (HashMap) / 맵 (Map)](https://hapbbying.tistory.com/81)
- [효율적인 긴 문자열 연산을 위한 Rope 자료구조](http://www.secmem.org/blog/2019/03/09/rope/)
- [힙(heap)이란](https://gmlwjd9405.github.io/2018/05/10/data-structure-heap.html)

## 언어와 프레임워크
- 고(go)
  - [Go언어로 나만의 Query Exporter 만들어보기!](https://gywn.net/2021/07/make-own-query-exporter-with-go/)
  - [Go CLI - Go Developer Road Map](https://earntrust.tistory.com/entry/gdrm-go-cli)
  - [Go: flag 패키지로 CLI 도구 만들기](https://pronist.dev/97)
- 쉘 스크립트(shell script)
  - [Bash 실행결과를 변수에 담기](https://zetawiki.com/wiki/Bash_%EC%8B%A4%ED%96%89%EA%B2%B0%EA%B3%BC%EB%A5%BC_%EB%B3%80%EC%88%98%EC%97%90_%EB%8B%B4%EA%B8%B0)
- 자바(Java)
  - [코드로 알아보는 java의 Hashmap](https://sabarada.tistory.com/57)
- 자바스크립트(Javascript)
  - [var, let, const 차이점](https://velog.io/@bathingape/JavaScript-var-let-const-%EC%B0%A8%EC%9D%B4%EC%A0%90)
  - [자바스크립트의 변수범위와 호이스팅](http://chanlee.github.io/2013/12/10/javascript-variable-scope-and-hoisting/)
  - Node.js
    - [로우 레벨로 살펴보는 Node.js 이벤트 루프](https://evan-moon.github.io/2019/08/01/nodejs-event-loop-workflow/)
  - 타입스크립트(TypeScript)
    - [타입스크립트 모노레포](https://deptno.github.io/posts/2018/typescript-monorepo/) 
- 파이썬(Python)
  - [A guide to logging in Python](https://www.bloomberg.com/company/stories/guide-logging-python/)
  - [How to Flatten a Dictionary in Python in 4 Different Ways](https://www.freecodecamp.org/news/how-to-flatten-a-dictionary-in-python-in-4-different-ways/)
  - [How to set up HTTPHandler for python logging](https://stackoverflow.com/questions/51525237/how-to-set-up-httphandler-for-python-logging)
  - [[Python] asyncio 파헤치기](https://brownbears.tistory.com/540)
  - [Python logging json formatter](https://everythingtech.dev/2021/03/python-logging-with-json-formatter/)
  - [Python multiprocessing's Pool process limit](https://stackoverflow.com/questions/20039659/python-multiprocessings-pool-process-limit)
  - [[Python] 튜플(tuple), 리스트(list), 셋(set), 딕셔너리(dict) 비교](https://specialscene.tistory.com/142#:~:text=%EB%A6%AC%EC%8A%A4%ED%8A%B8%EC%99%80%20%EB%B9%84%EA%B5%90%EA%B0%80%20%EB%A7%8E%EC%9D%B4,%ED%95%98%EA%B1%B0%EB%82%98%20%EB%B3%80%EA%B2%BD%ED%95%A0%20%EC%88%98%20%EC%97%86%EB%8B%A4%EB%8A%94%20%EA%B2%83.)
  - [python pool.map() and shared array variable](https://stackoverflow.com/questions/56585130/python-pool-map-and-shared-array-variable)
  - [Pytorch weight 저장에 대해 우리가 알아야하는 모든 것](https://comlini8-8.tistory.com/50)
  - [데코레이터(decorator)란?](https://hello-bryan.tistory.com/214)
  - [제네레이터(generator)란?(1)](https://bluese05.tistory.com/56)
  - [제네레이터(generator)란?(2)](https://wikidocs.net/16069)
  - [조금 더 체계적인 Python Logging](https://hwangheek.github.io/2019/python-logging/)
  - [파이썬의 대표적인 네 자료형(리스트, 셋, 튜플, 딕셔너리) 특성 알아보기](https://this-programmer.tistory.com/445)
  - 장고(Django)
    - [APIView, Mixins, generics APIView, ViewSet을 알아보자](https://ssungkang.tistory.com/entry/Django-APIView-Mixins-generics-APIView-ViewSet%EC%9D%84-%EC%95%8C%EC%95%84%EB%B3%B4%EC%9E%90?category=366160)
    - [ViewSet 과 Router](https://ssungkang.tistory.com/entry/Django-ViewSet-%EA%B3%BC-Router)
  - FastAPI
    - [FastAPI Schema를 제대로 다루는 방법](https://this-programmer.tistory.com/471)

## 인공지능
- [MLOps 란 무엇일까?](https://medium.com/daria-blog/mlops-%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%BC%EA%B9%8C-7ba8d9aae221)
- [딥러닝이란 무엇인가](https://tensorflow.blog/%EC%BC%80%EB%9D%BC%EC%8A%A4-%EB%94%A5%EB%9F%AC%EB%8B%9D/1-%EB%94%A5%EB%9F%AC%EB%8B%9D%EC%9D%B4%EB%9E%80-%EB%AC%B4%EC%97%87%EC%9D%B8%EA%B0%80/)

## 운영체제
- [Deadlock 개념이란? 그에 대한 해결책/회피책](https://jwprogramming.tistory.com/12)
- [데드락(Deadlock, 교착 상태)이란?](https://chanhuiseok.github.io/posts/cs-2/)
- [운영 체제(위키)](https://ko.wikipedia.org/wiki/%EC%9A%B4%EC%98%81_%EC%B2%B4%EC%A0%9C)
- 리눅스(Linux) / 유닉스(Unix)
  - [cgroup 이란?](https://sonseungha.tistory.com/535)
  - [[Linux] supervisor를 사용하여 지속적으로 실행해야 하는 프로세스 관리하기](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=shino1025&logNo=221472860840)
  - [Linux - Namespace 란?](https://galid1.tistory.com/442)
  - [NFS서버란 무엇인가?](https://jhnyang.tistory.com/279)
  - [리눅스(Linux)와 유닉스(Unix)의 차이](https://this-programmer.tistory.com/entry/%EB%A6%AC%EB%88%85%EC%8A%A4Linux%EC%99%80-%EC%9C%A0%EB%8B%89%EC%8A%A4Unix%EC%9D%98-%EC%B0%A8%EC%9D%B4)
  - [리눅스 네임스페이스(Linux Namespace)란?](https://www.44bits.io/ko/keyword/linux-namespace)
  - [리눅스 리다이렉션 & 파이프(Linux redirection & pipe)](https://jdm.kr/blog/74)
  - [리눅스, 유닉스 백그라운드프로세스 방법 정리 (&, bg, nohup, screen)](https://this-programmer.tistory.com/468)

## 좋은 글들
- [APM (Application Performance management)](https://blog.daum.net/ossogood/8435674)
- [CRM이란 무엇인가요?](https://www.oracle.com/kr/cx/what-is-crm/)
- [IT직군에서 많이 쓰이는 SI, SM, SE, PG 등 용어의 의미](https://this-programmer.tistory.com/entry/IT%EC%A7%81%EA%B5%B0%EC%97%90%EC%84%9C-%EB%A7%8E%EC%9D%B4-%EC%93%B0%EC%9D%B4%EB%8A%94-SI-SM-SE-PG-%EB%93%B1-%EC%9A%A9%EC%96%B4%EC%9D%98-%EC%9D%98%EB%AF%B8)
- [OKR이란?](https://experience.dropbox.com/ko-kr/resources/what-is-an-okr)
- [POC (Proof Of Concept)란?](https://m.blog.naver.com/pmw9440/221763425946)
- [네이버 메인 페이지의 트래픽 처리](https://d2.naver.com/helloworld/6070967)
- [소프트웨어, 실무형 인재의 신화](https://sangminpark.blog/2011/08/26/%EC%86%8C%ED%94%84%ED%8A%B8%EC%9B%A8%EC%96%B4-%EC%8B%A4%EB%AC%B4%ED%98%95-%EC%9D%B8%EC%9E%AC%EC%9D%98-%EC%8B%A0%ED%99%94/)
- [통합관제 EMS(종합관제)](http://hamonsoft.co.kr/solution/integrated-control/integrated-management/netis-ems/)

## 컴퓨터 공학
- [10분 Actor Model 정리](https://hyojabal.tistory.com/1)
- [컴퓨터가 1+1을 하는 과정](https://brunch.co.kr/@lqju/8)
- [메모리의 구조 (코드, 데이터, 힙, 스택 영역)](https://all-young.tistory.com/17)
- [행위자 모델](https://ko.wikipedia.org/wiki/%ED%96%89%EC%9C%84%EC%9E%90_%EB%AA%A8%EB%8D%B8)

## 유용한 사이트 & 블로그
- [netlify로 사이트 배포하기](https://goddino.tistory.com/190)
- [Tech At Bloomberg](https://www.bloomberg.com/company/stories/category/tech-at-bloomberg/)
- [VULTR](https://www.vultr.com/products/cloud-compute/)
- [구르미의 개발 이야기](https://gurumee92.tistory.com/)
- [SK(주) C&C’s TECH BLOG](https://engineering-skcc.github.io/)
