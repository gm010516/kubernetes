# Kubernetes 학습 정리

쿠버네티스 관련 학습한 내용을 영역별로 정리한 문서입니다.

---

## 1. Cluster Installation & Configuration
- ETCD 백업 & 복구 
- Kubernetes Upgrade 
- ClusterRole 
- RoleBinding 

---

## 2. Service and Networking
- Kubernetes Network 동작 원리
- Service
- Network Policy
- Ingress
- DNS

---

## 3. Storage
- Kubernetes Storage
- emptyDir
- HostPath
- PV(Persistent Volume) & PVC(Persistent Volume Claim)

---

## 4. Workloads and Scheduling
- Pod
- Static Pod
- Multi container pod
- Streaming sidecar container
- Deployment
- Rolling Update & Roll back
- Node Management
- Pod Scheduling
- Configmap & Secret

---

## 5. Cluster Troubleshooting

---

## 6. Multi Cluster (multi_nhn_ncp.md)
- 멀티클러스터 환경 구성 (nhn, ncloud)
- Istio 멀티클러스터 서비스 메시 동작 원리
- ServiceEntry, DestinationRule, VirtualService 설정
- 클러스터 간 통신 테스트
- 
---

## 7. MySQL Backup (mysql_backup.md)
- MySQL 데이터베이스 백업 전략
- PV, PVC 생성
- configmap & secret 생성
- statefulset 배포 및 service 생성
- mysql 접속 테스트
- crontab 백업 파일 생성

---

## 8. Worker Node Add & Delete (worker_node_add_delete.md)
- 노드 삭제 절차 및 리소스 정리
- drain 및 cordon 사용법
- Node Lifecycle 관리
---
