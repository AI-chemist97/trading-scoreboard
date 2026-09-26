# 📟 Trading Scoreboard

- **[KR]** 자동매매 봇 3개(국내 / ISA / 스윙)의 누적 수익률을 퍼센트로만 공개하는 전광판입니다.
- **[EN]** A public scoreboard showing only the cumulative return (%) of three live trading bots (KR / ISA / Swing).

[![Trading Scoreboard](https://raw.githubusercontent.com/AI-chemist97/trading-scoreboard/main/card.svg)](https://ai-chemist97.github.io/trading-scoreboard/)

![국내](https://img.shields.io/endpoint?style=for-the-badge&url=https://raw.githubusercontent.com/AI-chemist97/trading-scoreboard/main/badge/kr.json)
![ISA](https://img.shields.io/endpoint?style=for-the-badge&url=https://raw.githubusercontent.com/AI-chemist97/trading-scoreboard/main/badge/isa.json)
![스윙](https://img.shields.io/endpoint?style=for-the-badge&url=https://raw.githubusercontent.com/AI-chemist97/trading-scoreboard/main/badge/swing.json)

**🔗 Live page:** https://ai-chemist97.github.io/trading-scoreboard/

## 무엇이 들어 있나 (What's Inside)

- **[KR]** 이 저장소에는 매매 코드가 없습니다. 봇이 장 마감 후 계산한 숫자만 커밋합니다. 종목·금액·계좌 정보는 올리지 않습니다.
- **[EN]** No trading code lives here. Bots commit only the numbers computed after market close; no holdings, amounts, or account data.

| Path | 내용 (Content) |
|---|---|
| `data/<bot>.json` | 누적·일간 수익률과 갱신 시각 (cumulative & daily return, timestamp) |
| `badge/<bot>.json` | README 배지용 shields.io endpoint 파일 (badge file) |
| `card.svg` | README에 붙이는 카드 이미지 (image card for READMEs) |
| `index.html` | 전광판 페이지 (scoreboard page) |

- **[KR]** 오르면 빨강, 내리면 파랑입니다 (국내 증시 관례).
- **[EN]** Red means up and blue means down, following the Korean market convention.
