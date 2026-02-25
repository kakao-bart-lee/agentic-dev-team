# Agentic Dev Team

AI 에이전트 개발팀 설정 및 프롬프트 관리 레포지토리.

## 구조

```
haruna/              # Arkana 프로젝트 전담팀
  ├── config.json    # 팀 설정 (모델, webhook, repos)
  ├── prompts/       # 역할별 프롬프트
  ├── learnings.jsonl # 학습 기록
  └── sentinel-state.json
shared/              # 팀 간 공용 리소스
  └── templates/     # 공용 프롬프트 템플릿
```

## Teams

### Haruna Dev Team
- **프로젝트**: Arkana (사주/운세 서비스)
- **Discord**: #haruna-dev
- **Roles**: PO, Architect, BE, FE, Reviewer, Sentinel, Researcher, Retrospective

## 문서
- [팀 설계](../docs/HARUNA_DEV_TEAM.md) — 아키텍처, 워크플로우, 비용 추정
- [Anthropic 에이전트 가이드](https://www.anthropic.com/engineering/building-effective-agents)
