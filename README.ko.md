[English](README.md) | [한국어](README.ko.md) | [日本語](README.ja.md) | [中文](README.zh.md)

# oc-skill-creator

검증된 패턴과 예제를 갖춘 OpenClaw 네이티브 스킬 크리에이터.

## 설치

```bash
openclaw skills install oc-skill-creator
```

## 차별점

- **OpenClaw 네이티브 패턴**: Phase 0 분석, sub-agent 컨텍스트 주입, Style Guide 우선 접근법
- **5가지 검증된 유형**: pipeline, single-task, tool-integration, code-generation, doc-conversion
- **Codex 포팅 체크리스트**: 기존 Codex 스킬을 OpenClaw 패턴으로 마이그레이션
- **다국어 지원**: EN/KO/JA/ZH 키워드 및 참고 문서

## 빠른 시작

다음과 같이 말해보세요:
- "환율 변환 스킬 만들어줘"
- "웹 페이지 요약 스킬 만들어줘"
- "프로젝트 스캐폴드 생성 스킬 만들어줘"

skill-creator가 5단계 프로세스를 안내합니다:
1. 좋은 결과와 실패 사례 분석
2. Style Guide 작성 (판단 기준)
3. 워크플로우 구조화 (Phase 0 → 실행 → 검증)
4. 필요시 참고 자료 분리
5. oc-skill-audit로 검증

## 링크

- **ClawHub**: https://clawhub.ai/haseo-ai/oc-skill-creator
- **GitHub**: https://github.com/haseo-ai/skill-creator
- **라이선스**: MIT-0
