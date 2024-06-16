# Argo-rollouts으로 배포 테스트
Argo Rollouts의 Blue/Green 배포 기능을 통해 Argo CD에서 관리의 안정성 테스트.


## 목차

- [소개](#소개)
- [설치](#설치)
- [사용법](#사용법)


## 소개

Argo Rollouts는 Blue/Green, Canary 등의 고급 배포 기능을 지원하는 Kubernetes controller이자 CRDs 세트이며 자동 롤백 및 수동 판단 등을 가능하게 해줍니다.

## 설치

kubectl create namespace argo-rollouts

kubectl apply -n argo-rollouts -f https://github.com/argoproj/argo-rollouts/releases/latest/download/install.yaml

mv ./kubectl-argo-rollouts-linux-amd64 /usr/local/bin/kubectl-argo-rollouts

kubectl argo rollouts version

![스크린샷 2024-06-04 225333](https://github.com/wndudwns0028/rollout-k8s/assets/121155356/edf088ba-1a5e-4639-a6f1-871bc6abb04f)

![스크린샷 2024-05-26 002717](https://github.com/wndudwns0028/rollout-k8s/assets/121155356/35485d11-544a-48f5-bdab-d5932ab66efb)

![스크린샷 2024-06-04 225406](https://github.com/wndudwns0028/rollout-k8s/assets/121155356/42f7d36e-a3d8-4947-9f4a-0fb2519f80a1)

![스크린샷 2024-06-04 225303](https://github.com/wndudwns0028/rollout-k8s/assets/121155356/5e62cb68-8e0c-47a3-a899-11dae17902fe)
