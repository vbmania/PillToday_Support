# Repository operating contract

<!-- PROJECT_HARNESS_ROUTER_START -->
## Project Harness 시작

1. `/Users/work/Develop/project-harness/bin/project-harness --repo . bootstrap --resume`으로 현재 프로젝트와 인계 상태를 확인합니다.
2. `continuity.status`, exact next action, blockers, dirty lineage를 먼저 확인합니다.
3. `STRUCTURE_READY` 또는 `STALE`이면 일반 `bootstrap`과 `check`로 원인을 확장 확인합니다.
4. `.project-harness/project.json`의 `source_of_truth`와 `agent_layers`를 따라 필요한 문서만 읽습니다.
5. 루트 `AGENTS.md`는 저장소 공통 계약을, 하위 `AGENTS.md`는 해당 디렉터리의 더 구체적인 계약을 소유합니다. 충돌하면 현재 작업 경로에서 가장 가까운 AGENTS.md를 우선합니다.
6. 활성 Task에 `execution_mode`가 있으면 `/Users/work/Develop/project-harness/skills/manage-agent-runs/SKILL.md`를 읽고 Assignment → Run → Handoff → Evidence → Coordinator acceptance 원장을 기록합니다.
7. 완료 전 `/Users/work/Develop/project-harness/bin/project-harness --repo . check`와 프로젝트 고유 검증을 각각 실행합니다.

Harness 검사는 저장소 지식 정합성만 증명하며 빌드·기기·콘솔·심사·공개 상태를 대신하지 않습니다.
<!-- PROJECT_HARNESS_ROUTER_END -->
