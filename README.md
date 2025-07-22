# 🧱 TheStack_Project

> 타이밍을 맞춰 블록을 정확히 쌓아 올리는 2D 캐주얼 게임입니다.  
> Unity로 개발되었으며, 간단한 조작과 점점 높아지는 난이도를 통해  
> 집중력과 반사 신경을 시험하는 게임입니다.

## 🎮 게임 소개

TheStack은 단순한 규칙을 기반으로 반복 플레이가 가능한  
**아케이드 스타일의 스택 쌓기 게임**입니다.

- 좌우로 이동하는 블록을 타이밍 맞춰 멈추고
- 이전 블록과 겹치는 부분만 남기며 점점 높이 쌓는 것이 목표입니다.
- 정밀하게 멈출수록 다음 블록을 쌓기 쉽고,
- 반복될수록 블록이 작아지고 난이도가 올라갑니다.


## 🕹️ 플레이 방법

- 블록이 좌우로 움직입니다.
- [스페이스바] 또는 [마우스 클릭]을 누르면 블록이 멈춥니다.
- 이전 블록과 정확히 겹치지 않으면, **겹친 부분만 남고 나머지는 잘려나갑니다.**
- 블록이 완전히 벗어나면 **게임 오버**입니다.


## 🛠 사용 기술

- **Unity 2021 이상**
- **C#**
- Unity 2D Sprite 및 Physics 시스템
- Unity UI System (TextMeshPro, Slider)
- Git & GitHub for version control


## ✨ 주요 기능 요약

- ✅ 블록 자동 이동 및 정지
- ✅ 겹친 영역만 남기고 나머지 제거
- ✅ 스코어 증가 시스템
- ✅ 게임 오버 및 재시작
- ✅ UI 전환 (홈 / 게임 / 게임오버)
- 🔜 배경 사운드 및 효과음
- 🔜 난이도 증가 (속도/크기 조절)
- 🔜 최고 점수 저장 (PlayerPrefs 활용 예정)


## 🖼️ 게임 화면

> 아래는 실제 플레이 장면을 보여주는 예시 이미지입니다.  
![Animation2 (1)](https://github.com/user-attachments/assets/83f3075f-da35-40ab-a239-827ad67b7d64)


## 📂 프로젝트 폴더 구조

```plaintext
Assets/
├── Scripts/
│   ├── GameManager.cs
│   ├── Block.cs
│   ├── UI/
│   │   ├── UIManager.cs
│   │   ├── HomeUI.cs
│   │   ├── GameUI.cs
│   │   └── GameOverUI.cs
├── Prefabs/
├── Scenes/
├── Sprites/
├── Sounds/
├── Materials/
└── ...



---

## 👤 개발자

```markdown
## 👤 개발자

| 이름 | 역할 |
| 이재은 | Unity 개발 / 게임 로직 구현 / UI 구성 / 시스템 설계 등 전반 담당 |
> 개인 프로젝트로 전체 기능을 직접 구현하였습니다.














