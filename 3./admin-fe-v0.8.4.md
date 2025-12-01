<style>
@import url('https://cdn.jsdelivr.net/gh/orioncactus/pretendard/dist/web/static/pretendard.css');

* {
  font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, sans-serif;
}
</style>

# ADMIN-FE v0.8.4

> **버전:** ADMIN-FE v0.8.4  
> **배포일:** 2025년 12월 1일  
> **GitHub:** [브랜치 보기](https://github.com/didim365/didimAIStudio_Front_Admin/tree/release/admin-fe/0.8.4)

---

### 커밋 내용

**[FE] 에이전트 관리페이지 제작작**

- 에이전트 목록/상세 UI 레이아웃 구축
- 목록 조회 API 연동(useQuery), 생성/수정/삭제 기능(useMutation)
- AgentForm 컴포넌트 분리 및 Validation 로직 추가
- 로딩 스켈레톤 및 성공/에러 토스트 적용
- shadcn/ui 기반 스타일 적용 및 반응형 대응
- 타입 정의(Agent, ModelConfig) 추가 및 폴더 구조 정리

---

## 에이전트 관리 페이지 제작

이번 업데이트에서는 에이전트 관리 페이지를 새롭게 제작하여 사용자분들이 더욱 편리하게 에이전트를 관리할 수 있도록 했습니다. 다양한 기능을 통해 에이전트의 생성, 수정, 삭제를 손쉽게 할 수 있는 환경을 제공하게 되었습니다.

### 주요 변경 사항

**에이전트 목록 및 상세 UI 레이아웃**이 구축되어, 사용자는 전체 에이전트를 한눈에 확인하고 각 에이전트의 상세 정보도 쉽게 조회할 수 있습니다. 

또한, 목록 조회 API와의 연동을 통해 데이터가 실시간으로 반영되도록 했습니다. 에이전트의 생성, 수정, 삭제 기능도 추가되어 사용자가 필요에 따라 자유롭게 에이전트를 관리할 수 있게 되었습니다. 

**AgentForm 컴포넌트**가 분리되어, 각종 Validation 로직이 추가되었습니다. 이를 통해 양식 입력 시 더욱 정확한 데이터 처리가 가능합니다.

### UI/UX 개선

사용자 경험을 개선하기 위해 **로딩 스켈레톤**과 성공/실패에 대한 알림을 **토스트 메시지**로 적용했습니다. 이렇게 함으로써, 사용자에게 보다 매끄러운 피드백을 제공할 수 있게 되었습니다.

마지막으로, **shadcn/ui** 기반의 스타일을 적용하여 디자인을 일관되게 유지하고, 반응형 디자인을 통해 다양한 화면 크기에 맞춰 자동으로 레이아웃이 조정되도록 했습니다. 이를 통해 모든 사용자에게 쾌적한 환경을 제공하기 위해 노력했습니다.

## 버전: ADMIN-FE v0.8.4

---

*자동 생성된 패치노트입니다.*
