# Repository operating contract

<!-- PROJECT_HARNESS_ROUTER_START -->
## Project Harness 시작

1. `/Users/work/Develop/project-harness/bin/project-harness --repo . bootstrap`으로 현재 프로젝트·Change·다음 Task·blocker·stale 상태를 확인합니다.
2. `.project-harness/project.json`의 `source_of_truth`와 `agent_layers`를 따라 필요한 문서만 읽습니다.
3. 루트 `AGENTS.md`는 저장소 공통 계약을, 하위 `AGENTS.md`는 해당 디렉터리의 더 구체적인 계약을 소유합니다. 충돌하면 현재 작업 경로에서 가장 가까운 AGENTS.md를 우선합니다.
4. 완료 전 `/Users/work/Develop/project-harness/bin/project-harness --repo . check`와 프로젝트 고유 검증을 각각 실행합니다.

Harness 검사는 저장소 지식 정합성만 증명하며 빌드·기기·콘솔·심사·공개 상태를 대신하지 않습니다.
<!-- PROJECT_HARNESS_ROUTER_END -->
