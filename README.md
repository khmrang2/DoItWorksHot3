# DoItWorksHot3

> Git 워크플로우 학습 및 C 알고리즘 실습 레포지토리

---

## 프로젝트 개요

Git의 핵심 워크플로우(branch, merge, rebase, conflict resolution)를 학습하기 위한 실습 레포지토리입니다. 다양한 Git 시나리오를 직접 수행하며 브랜치 전략과 협업 워크플로우를 익혔습니다. 부가적으로 C 언어 기반의 알고리즘 문제 풀이를 포함합니다.

## 기술 스택

| 분류 | 기술 |
|------|------|
| 언어 | C |
| 버전관리 | Git (branch, merge, rebase, PR) |
| 빌드 | gcc |

## 학습 내용

### Git 워크플로우 실습
- **Branch 전략** — PC/노트북 간 동일 레포에서의 브랜치 기반 작업 흐름
- **Merge & Conflict** — develop 브랜치와 master 간 머지 및 충돌 해결
- **Rebase** — rebase를 통한 커밋 히스토리 정리 실습
- **Pull Request** — PR 기반 코드 리뷰 워크플로우

### C 알고리즘
- 등차수열 판별 알고리즘 구현 (`asd.c`)
- 3자리 숫자의 각 자릿수를 분리하여 등차 여부 판별

## 나의 역할 (커밋 로그 기반)

> 주 기여자 — 19 commits 중 17 commits (89%)

- 프로젝트 초기 설정 및 C 코드 작성
- Branch/Merge/Rebase 등 Git 워크플로우 전 과정 실습
- 좌우 이동 이벤트 처리 코드 작성
- README 및 문서 갱신
- PR(#2) 머지 워크플로우 수행

## 빌드 및 실행

```bash
gcc asd.c -o a.exe -lm
./a.exe
```
