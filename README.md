# 🏚 동굴 탈출 게임 (한글)

브라우저에서 바로 실행되는 동굴 탐험 게임입니다.  
프레임워크나 외부 라이브러리 없이 `cave_game.html` 파일 하나만 열면 플레이할 수 있습니다.

## 게임 방법

- 매 갈림길마다 **왼쪽 / 가운데 / 오른쪽** 중 하나를 선택합니다
- **5번 연속** 통과하면 동굴 탈출 성공!
- 함정 확률은 **30%** — 함정 종류는 네 가지:
  - 🏹 화살 함정
  - 🔥 화염 함정
  - 🕳️ 낭떠러지
  - 🪨 굴러오는 돌
- 함정에 걸리면 처음부터 다시 시작

## 실행 방법

별도 설치 없이 파일을 브라우저로 열면 됩니다.

```
cave_game.html 파일을 더블클릭 → 브라우저에서 바로 실행
```

## 파일 구조

```
cave-escape-game/
├── cave_game.html   # 게임 본체 (단일 파일)
└── README.md
```

## 기술 스택

- **렌더링** : HTML5 Canvas (벽돌/아치 절차적 드로잉)
- **스타일** : Vanilla CSS (CSS 변수, 애니메이션)
- **로직**   : Vanilla JavaScript (빌드 과정 없음)

## 데모

> GitHub Pages로 배포 후 아래 주소로 접근 가능:  
> `https://<깃허브 유저명>.github.io/cave-escape-game/`

---

*단일 HTML 파일 게임 실험 프로젝트.*

# 🏚 Cave Escape Game (English)

A browser-based cave exploration game built with vanilla HTML/CSS/JavaScript.  
No frameworks, no dependencies — open `cave_game.html` directly in any browser.

## Gameplay

- Choose from **3 paths** (Left / Center / Right) at each fork
- Successfully pass **5 consecutive forks** to escape the cave
- Traps appear with **30% probability** — four trap types:
  - 🏹 Arrow trap
  - 🔥 Fire trap
  - 🕳️ Pitfall
  - 🪨 Rolling boulder
- Hitting a trap resets progress to the beginning

## Getting Started

```bash
# No installation required
# Simply open the file in a browser
open cave_game.html        # macOS
start cave_game.html       # Windows
```

## Project Structure

```
cave-escape-game/
├── cave_game.html   # Game entry point (self-contained)
└── README.md
```

## Tech Stack

- **Rendering** : HTML5 Canvas (procedural brick/arch drawing)
- **Styling**   : Vanilla CSS (CSS variables, animations)
- **Logic**     : Vanilla JavaScript (no build step)

## Live Demo

> Deployed via GitHub Pages:  
> `https://<your-username>.github.io/cave-escape-game/`

---

*Built as a single-file HTML game experiment.*
