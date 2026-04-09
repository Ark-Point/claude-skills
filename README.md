# ARK Point Claude Code Skills

ARK Point 팀이 사용하는 Claude Code 커스텀 스킬 모음.

## 설치

```bash
# token-diet 스킬 설치
curl -fsSL https://raw.githubusercontent.com/Ark-Point/claude-skills/main/commands/token-diet.md \
  -o ~/.claude/commands/token-diet.md
```

## 스킬 목록

### /token-diet

주간 토큰 ROI 점검. 환경 진단 + 유령 스킬 탐지 + 모델 라우팅 확인.

```
/token-diet          # 전체 점검
/token-diet quick    # 2분 퀵체크
/token-diet fix      # 진단 + 자동 수정 제안
```

**설계 원칙**: 토큰을 덜 쓰는 게 아니라 잘 쓰는 게 목적. 쓰는 도구는 건드리지 않고, 2주간 안 쓴 유령 스킬만 정리 권장.
