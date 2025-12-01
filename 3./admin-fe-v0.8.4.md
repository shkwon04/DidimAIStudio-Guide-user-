# ADMIN-FE v0.8.4

> **버전:** ADMIN-FE v0.8.4  
> **배포일:** 2025년 12월 1일  
> **GitHub:** [브랜치 보기](https://github.com/didim365/didimAIStudio_Front_Admin/tree/release/admin-fe/0.8.4)

---

### 커밋 내용

| 내용 |
|------|
| DID-1093: MetricCard 컴포넌트를 공용 컴포넌트에서 대시보드 전용으로 이동 |
| MetricCard 컴포넌트를 src/shared/components/dashboard/에서 src/feature/dashboard/components/로 이동 |
| 대시보드 페이지의 import 경로를 상대 경로로 업데이트 |
| 공용 컴포넌트 위치의 기존 파일 삭제 |
| Merge pull request #130 from didim365/feature/scenarios |
| DID-1093: MetricCard 컴포넌트를 공용 컴포넌트에서 대시보드 전용으로 이동 |
| Merge pull request #131 from didim365/develop |
| Develop |

---

## MetricCard 컴포넌트 대시보드 전용으로 이동

이번 업데이트에서는 MetricCard 컴포넌트의 위치를 변경하여 대시보드에서의 활용도를 높였습니다. 이로 인해 대시보드 페이지에서 더욱 원활하게 MetricCard를 사용할 수 있게 되었습니다.

### 주요 변경 사항

**MetricCard 컴포넌트**가 공용 컴포넌트에서 대시보드 전용으로 이동되었습니다. 
이제 이 컴포넌트는 `src/feature/dashboard/components/`에서 관리되며,
대시보드 페이지에서의 import 경로도 상대 경로로 업데이트되었습니다. 

또한, 이전 위치인 `src/shared/components/dashboard/`에서의 기존 파일은 삭제되어,
조직적인 구조를 유지할 수 있게 되었습니다.

이번 변경은 대시보드의 코드 관리 효율성을 높이고,
보다 명확한 컴포넌트 사용을 가능하게 합니다.

## 버전: ADMIN-FE v0.8.4

---

*자동 생성된 패치노트입니다.*
