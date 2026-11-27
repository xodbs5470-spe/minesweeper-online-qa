# Minesweeper Online QA

[minesweeper.online](https://minesweeper.online) 웹 지뢰찾기 게임을 대상으로 진행하는 QA 포트폴리오 프로젝트입니다.

## 테스트 대상
- 서비스: Minesweeper Online (https://minesweeper.online)
- 플랫폼: 웹 (PC 브라우저)

## 테스트 범위
- 게임 규칙: 칸 열기, 깃발, 코드(chord) 열기, 승리·패배 판정
- 난이도: 초급 / 중급 / 고급 / 사용자 지정
- UI: 타이머, 남은 지뢰 수, 리셋 버튼
- 범위 제외: 결제, 계정 보안, 서버 부하

## 진행 상황
| 단계 | 내용 | 산출물 | 상태 |
|---|---|---|---|
| 1단계 | 환경 정리, 규칙 정리, 탐색 플레이 | `docs/01~03` | 진행 중 |
| 2단계 | 테스트 계획 작성 | `docs/04_test-plan.md` | 예정 |
| 3단계 | 테스트 케이스 작성·실행 | `test-cases/test-cases.csv` | 예정 |

## 폴더 구조
```
minesweeper-online-qa/
├── README.md
├── docs/
│   ├── 01_test-environment.md   테스트 환경
│   ├── 02_spec-notes.md         도움말에서 정리한 규칙
│   ├── 03_exploratory-notes.md  탐색 플레이 메모
│   └── 04_test-plan.md          테스트 계획 (2단계)
├── test-cases/
│   └── test-cases.csv           테스트 케이스
└── screenshots/                 증거 스크린샷
```
