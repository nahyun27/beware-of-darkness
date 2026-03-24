# 🌑 Beware of Darkness

> *Your vision narrows. The coins glitter in the dark. Survive.*

![Beware of Darkness Gameplay](./demo.gif)

---

## 🎮 Overview

**Beware of Darkness** is a tense top-down maze escape game built with Unity.  
The longer you play, the darker it gets — your field of vision shrinks relentlessly as you scramble to collect coins and find a way out.

Simple mechanics. Mounting dread.

---

## ✨ Features

- 🔦 **Shrinking vision system** — field of view narrows in real time as the game progresses
- 💰 **Coin collection mechanic** — gather coins scattered across the maze to stave off the darkness
- 🧩 **Handcrafted level design** — carefully laid out maze with deliberate tension pacing
- 🎯 **Pure survival gameplay** — no tutorials, no hand-holding, just you and the dark

---

## 🛠 Tech Stack

| Engine | Unity |
|---|---|
| Language | C# |
| Design | Level Design |

---

## 🚀 How to Run

### Windows

1. 이 저장소를 클론하거나 ZIP으로 다운로드합니다.
2. `Release/` 폴더 안의 구조가 아래와 같이 유지되어야 합니다:

```
📁 Release/
├── 📁 Beware of Darkness_Data/
├── 📁 MonoBleedingEdge/
├── 🎮 Beware of Darkness.exe      ← 실행 파일
├── ⚙️  UnityCrashHandler32.exe
└── 📄 UnityPlayer.dll
```

3. `Release/` 폴더 안의 **`Beware of Darkness.exe`** 를 더블클릭하여 실행합니다.

> ⚠️ `.exe` 파일과 `Beware of Darkness_Data` 폴더는 **반드시 같은 디렉토리**에 있어야 합니다.  
> 단독으로 `.exe`만 다른 위치로 옮기면 실행되지 않습니다.

### Requirements

- OS: Windows 10 / 11
- DirectX 11 이상 지원 GPU
- 별도 설치 프로그램 없음 (standalone build)

---

## 🕹 Controls

| Key | Action |
|-----|--------|
| `↑ ← ↓ →` | 이동 |
| `ESC` | 일시정지 / 종료 |

---

## 📁 Project Structure

```
📁 beware-of-darkness/
├── 📁 Release/
│   ├── 📁 Beware of Darkness_Data/   # 게임 리소스 및 에셋 데이터
│   ├── 📁 MonoBleedingEdge/           # Mono 런타임 (Unity 내장)
│   ├── 🎮 Beware of Darkness.exe      # 게임 실행 파일
│   ├── ⚙️  UnityCrashHandler32.exe    # Unity 크래시 리포터
│   └── 📄 UnityPlayer.dll             # Unity 플레이어 런타임 DLL
├── 🖼️  demo.gif
└── 📄 README.md
```

---

<p align="center">
  Made with Unity &nbsp;·&nbsp; C# &nbsp;·&nbsp; 🖤 <br/>
  <sub>2020.08 &nbsp;·&nbsp; Team 영하나</sub>
</p>
