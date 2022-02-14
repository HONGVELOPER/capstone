# Capstone Design - Hanyang University ERICA

## 💡 Introduction
---
1. 컨테이너 클러스터 환경 구성
	단일노드 minikube로 쿠버네티스 클러스터 구성
2. 서버리스 구축
	OpenFaas 설치, 운영 모니터링 도구 설치
3. 데이터 수집 서버 구축
	공공데이터 API를 활용하여 구성
4. Function 개발
	OpenFaas 기반 Function 개발하여 서버리스 컴퓨팅 구성

## ⚙️  Setup
---
### DB password
### Deployment
'''shell
kubectl apply -f k8s
'''
### Ingress Nginx Controller
'''shell
minikube addons enable ingress
minikube tunnel
kubectl get pods -n ingress-nginx
'''

