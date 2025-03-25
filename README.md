# infra-configs
프로젝트의 공통 인프라 설정 및 배포 관련 파일들을 관리하는 레포입니다.

## 디렉토리 구조
- `docker/` : 여러 마이크로 서비스를 한 번에 실행 할 수 있도록 docker-compose 파일을 모아둔 디렉토리
- `env/` : 개발 및 운영 환경 변수 설정
- `jenkins/` : Jenkins 배포 스크립트 및 파이프라인 템플릿
- `github-actions/` : 재사용 가능한 GitHub Actions 워크플로우