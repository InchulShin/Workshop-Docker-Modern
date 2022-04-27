# AWS 및 DOCKER를 사용한 애플리케이션 현대화

[원본](https://docker.awsworkshop.io)

![](images/docker-cloud-twitter-card.png)

어서 오십시오!

이 워크샵에서는 AWS 및 Docker와 협력하여 개발된 새로운 Docker Compose CLI 도구를 사용하여 Docker 및 Amazon ECS로 애플리케이션을 구축하고 배포하는 방법을 배웁니다. 또한 AWS Fargate에서 서버리스 컨테이너를 사용하여 보안 비밀, CI/CD 및 애플리케이션 배포와 같은 현대화 모범 사례에 대해서도 알아봅니다.

Docker는 애플리케이션을 개발, 배송 및 실행하기 위한 개방형 플랫폼입니다. Docker를 사용하면 애플리케이션을 인프라에서 분리할 수 있으므로 소프트웨어를 빠르게 제공할 수 있습니다. Docker를 사용하면 애플리케이션을 관리하는 것과 동일한 방식으로 인프라를 관리할 수 있습니다. 코드를 신속하게 배송, 테스트 및 배포하기 위한 Docker 방법론을 활용하면 코드 작성과 프로덕션 환경에서 실행하는 사이의 지연을 크게 줄일 수 있습니다.

## 학습 목표

Docker Compose ECS 통합을 사용하여 애플리케이션 배포 Docker Buildkit을 사용하여 고유한 이미지를 빌드하고 해당 이미지를 Amazon ECS에 배포하는 방법. AWS Secrets Manager를 사용한 컨테이너 보안 GitHub 작업용 Amazon ECS 플러그인을 사용하는 CI/CD AWS Fargate를 사용하는 서버리스 컨테이너

## 이 워크숍은 누가 수강해야 하나요?

* 개발자
* DevOps 엔지니어
* 솔루션 아키텍트
* 사이트 안정성 엔지니어(SRE)
* 컨테이너를 사랑하고 더 배우고 싶은 사람!

## 순서

* [워크샵 개요](readme/0\_introduction.md)
* [전제 조건](readme/10\_prerequisites.md)
* [DOCKER BUILDKIT 및 COMPOSE를 사용하여 컨테이너 이미지 빌드](readme/21\_build\_images.md)
* [DOCKER AMAZON ECS 플러그인을 사용하여 AWS에 애플리케이션 배포](readme/31\_docker\_ecs\_integration.md)
* [CODEBUILD, CODEPIPELINE 및 DOCKER COMPOSE가 포함된 CI/CD](readme/41\_codepipeline.md)
