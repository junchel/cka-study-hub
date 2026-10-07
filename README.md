# CKA Retake Master & Study Hub

CKA(Certified Kubernetes Administrator) 2회차 재시험 합격을 위한 개인 맞춤형 모바일/웹 학습 애플리케이션입니다.

## 주요 기능
1. **취약 3대 도메인 클리닉 (배점 75% 집중 정복)**:
   - Troubleshooting (30%): kube-apiserver Static Pod 복구, Node NotReady, crictl, Logging Sidecar
   - Cluster Architecture (25%): etcd 백업/복원, kubeadm 업그레이드 5단계, CRD vs RBAC Subjects vs CSR, Helm 버전 고정
   - Services & Networking (20%): Pod DNS (`<ip-dash>.<ns>.pod.cluster.local`), Endpoint 디버깅, Ingress v1, NetworkPolicy AND/OR
2. **1회차 시험 복기 6대 문제 연습 (exam-01)**:
   - 실제 1회차 시험에서 막혔던 문제 요구사항, 1/2차 힌트 토글, 5단계 정답 및 YAML/CLI 원클릭 복사
3. **출퇴근 1초 모바일 플래시카드**:
   - 스마트폰 세로 화면 터치 친화적 3D 플립 카드 UI (OX 및 핵심 단골 함정 암기)
4. **시험장 속도전 치트시트**:
   - `alias k=kubectl`, `export do="--dry-run=client -o yaml"` 등 원라이너 모음

## 로컬 실행
```bash
node server.js
# 또는
npm start
```
웹 브라우저에서 `http://localhost:3000` 접속

## Vercel 배포
`vercel.json`이 포함되어 있어 Vercel 대시보드에서 GitHub 레포지토리를 Import하거나 `vercel deploy`로 즉시 호스팅 가능합니다.
