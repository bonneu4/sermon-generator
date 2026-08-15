---
description: 설교 자동 생성 루틴
---
## 이 저장소의 목적
매일 새벽 2시, sermon_queue.md에서 설교 본문을 하나 꺼내
sermon-generator 스킬로 설교문을 자동 생성하는 루틴을 위한 저장소입니다.

## 스킬
- 신학 기준 문서: `bonneu_theology_profile.md` 참조

## 루틴 실행 순서
1. sermon_queue.md에서 [ ] 항목 맨 위 하나 선택
2. 핵심 메시지 2~3문장 제안 (구속사적 흐름 고려)
3. sermon-generator 스킬로 설교문 완성 및 MD 출력
4. 처리한 항목을 [x]로 표시
5. 대기열이 비었으면 알림만 남기고 종료
