🚀 CI/CD 파이프라인

이 레포지토리는 codify 서비스를 위한 GitHub Actions 기반 CI/CD 파이프라인을 포함합니다.

✅ CI (Continuous Integration)
- main 브랜치에 코드 푸시 시 자동 실행
- Gradle로 프로젝트 빌드 수행
- GitHub Run ID로 Docker 이미지 태깅
- Docker Hub에 이미지 푸시

✅ CD (Continuous Deployment)
- Kubernetes deployment.yaml의 이미지 태그 자동 갱신
- 변경된 매니페스트를 별도 GitHub repo(k8s-manifests)에 푸시
- ArgoCD가 변경 사항을 감지하고 자동 배포 수행

<img width="1920" height="1080" alt="Image" src="https://github.com/user-attachments/assets/cdc5735b-dbb6-4a00-8025-ccbe1e6c4c45" />


⸻


