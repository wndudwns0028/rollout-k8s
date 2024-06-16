# Argo-rollouts

Argo Rollouts는 Blue/Green, Canary 등의 고급 배포 기능을 지원하는 Kubernetes controller이자 CRDs 세트이며 자동 롤백 및 수동 판단 등을 가능하게 해줍니다.

## 목차

- [소개](#소개)
- [설치](#설치)
- [사용법](#사용법)
- [기여](#기여)
- [라이선스](#라이선스)

## 소개

프로젝트의 목적과 기능에 대한 자세한 설명.

## 설치

kubectl create namespace argo-rollouts

kubectl apply -n argo-rollouts -f https://github.com/argoproj/argo-rollouts/releases/latest/download/install.yaml

mv ./kubectl-argo-rollouts-linux-amd64 /usr/local/bin/kubectl-argo-rollouts

kubectl argo rollouts version

![스크린샷 2024-05-26 002717](https://github.com/wndudwns0028/rollout-k8s/assets/121155356/35485d11-544a-48f5-bdab-d5932ab66efb)
