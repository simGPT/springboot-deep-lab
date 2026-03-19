# springboot-deep-lab
백엔드 핵심 기술과 아키텍처를 깊이 있게 탐구하고 클라우드 환경에서의 배포, 동시성 제어, 부하분산, 오토스케일링, 성능 테스트 등을 학습하는 Spring Boot 기반 엔지니어링 레포지토리

## Tech
- **Framework**: Spring Boot
- **Database**: postgreSQL + Redis (캐시/인증용)
- **Cloud**: Azure VM (Auto scaling), Azure Database for PostgreSQL, LoadBalancer
- **DevOps**: Docker,  GitHub Actions, Kubernetes

## ERD
<img width="1462" height="679" alt="image" src="https://github.com/user-attachments/assets/e9bde81c-254e-4357-8306-b07eb7835820" />



## **🎯 Git Convention**

- 🎉 **Start:** Start New Project [:tada:]
- ✨ **Feat:** 새로운 기능을 추가 [:sparkles:]
- 🐛 **Fix:** 버그 수정 [:bug:]
- 🎨 **Design:** CSS 등 사용자 UI 디자인 변경 [:art:]
- ♻️ **Refactor:** 코드 리팩토링 [:recycle:]
- 🔧 **Settings:** Changing configuration files [:wrench:]
- 🗃️ **Comment:** 필요한 주석 추가 및 변경 [:card_file_box:]
- ➕ **Dependency/Plugin:** Add a dependency/plugin [:heavy_plus_sign:]
- 📝 **Docs:** 문서 수정 [:memo:]
- 🔀 **Merge:** Merge branches [:twisted_rightwards_arrows:]
- 🚀 **Deploy:** Deploying stuff [:rocket:]
- 🚚 **Rename:** 파일 혹은 폴더명을 수정하거나 옮기는 작업만인 경우 [:truck:]
- 🔥 **Remove:** 파일을 삭제하는 작업만 수행한 경우 [:fire:]
- ⏪️ **Revert:** 전 버전으로 롤백 [:rewind:]

**🪴 Branch Convention (GitHub Flow)**

- `main`: 배포 가능한 브랜치, 항상 배포 가능한 상태를 유지
- `feature/{description}`: 새로운 기능을 개발하는 브랜치
    - 예: `feature/social-login`

