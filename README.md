<div align="center">

<img src="images/icon.png" width="128" alt="Divee 아이콘">

# Divee

**Mac의 자잘한 설정을 메뉴바 하나에서, ⌥Space 한 번으로.**

팬·온도, 밝기, 배터리, 잠자기, 창 정리, 클립보드까지 한곳에 모은 무료 메뉴바 유틸리티입니다.<br>
메뉴바에는 작은 고양이가 삽니다.

[![Download](https://img.shields.io/badge/다운로드-Divee_1.0.0-3478F6?style=for-the-badge&logo=apple&logoColor=white)](https://github.com/dorkman43/divee/releases/latest/download/Divee-1.0.0.dmg)

![macOS](https://img.shields.io/badge/macOS-14%20Sonoma%2B-111?logo=apple)
![Apple Silicon](https://img.shields.io/badge/Apple%20Silicon-M1~M4-111)
![Notarized](https://img.shields.io/badge/Apple-공증%20완료-2ea44f)
![Languages](https://img.shields.io/badge/언어-한국어%20·%20English-555)

[English](#english) · [기능](#-기능) · [테마](#-테마) · [설치](#-설치) · [개인정보](#-개인정보)

<br>

<img src="images/hero-fan.png" width="820" alt="Divee 패널 — 팬 & 온도 펼침">

</div>

---

## ✨ 이런 앱이에요

- **⌥Space 한 번이면 끝.** 입력창 아래 한 줄짜리 목록에서 필요한 항목에 마우스를 올리거나 → 를 누르면, Windows 우클릭 메뉴처럼 **옆으로 펼쳐집니다.**
- **키보드만으로도 다 됩니다.** ↑↓ 이동, → 펼치기, ← 접기, Return 실행, ESC 닫기. 조절바는 ←/→로 움직입니다.
- **가볍습니다.** 패널이 닫혀 있을 때 CPU 약 0.6%, 열어 둬도 약 1%. 애니메이션은 macOS 기본 방식만 쓰고, 설정에서 끌 수 있습니다.
- **원하는 기능만 켭니다.** 24개 모듈 중 필요한 것만 켜고, 나머지는 아예 돌지 않습니다.

<div align="center">
<img src="images/cascade-tools.png" width="760" alt="작업 도구 펼침">
</div>

## 🧰 기능

| 분류 | 모듈 | 하는 일 |
|---|---|---|
| **시스템** | 팬 & 온도 | CPU·GPU 온도, 팬 회전수 확인, 팬 속도 직접 조절·최대·온도 연동 |
| | 디스플레이 | 내장·외장 모니터 밝기(외장은 DDC), 밝기 키로 외장 모니터 조절 |
| | 배터리 | 잔량·건강도·사이클·전력·어댑터 정보, 완충·부족 알림 |
| | 잠자기 관리 | 잠자기 방지(시간 지정), 덮개를 닫아도 켜 두는 닫힘 모드 |
| | 시스템 모니터링 | CPU·메모리·네트워크·디스크, 작은 그래프와 경고 기준 |
| | 빠른 토글 | 다크 모드, 마이크 음소거, 숨김 파일, 바탕화면 아이콘, 화면 잠금·끄기, 휴지통 비우기 |
| **작업 도구** | 클립보드 · 메모 · 컬러 픽커 · 특수문자 | 복사 기록, 빠른 메모, 화면 색 추출(⌥⌘C), 자주 쓰는 기호 |
| | 창 정리 · 스페이스 이름 | 앱 묶음으로 창 모으기·정렬, 데스크톱(스페이스)에 이름 붙이기 |
| | 일정 · 날씨 · 로컬 검색 | 오늘 일정과 미리 알림, 날씨, 앱·파일 빠른 검색 |
| **AI** | 검색하거나 말하기 | 입력창에 원하는 일을 쓰면 AI가 위 기능들을 대신 실행합니다. 이 Mac 안의 모델(Apple Intelligence·Ollama)을 우선 쓰고, 원하면 OpenAI 호환 서버도 연결할 수 있습니다 |
| | 화면 읽기 · 웹 검색 · AI 사용량 | 화면 글자 읽기, 웹 검색 결과 요약, ChatGPT·Codex 사용량 확인 |
| | 에이전트 세션 · 훅 | Claude Code·Codex 세션이 나를 기다리면 알려 주고, 정한 조건에 맞춰 자동으로 동작 |
| | 음성 입력 | ⌃⌥Space를 누르고 있는 동안만 말하기. 인식은 이 Mac 안에서 처리합니다 |
| **실험** | 모션 & 노크 · 수평계 · 힌지 폴드 · 카메라 보기 | 맥북 센서를 활용한 실험 기능. 설정에서 "실험 기능 보기"를 켜면 나타납니다 |

> **준비 중** — sillog 업로드와 DevDive 연동은 아직 준비 중이라 켤 수 없습니다.

<div align="center">
<img src="images/system-monitor.png" width="760" alt="시스템 모니터링 — 막대와 그래프">
</div>

## 🎨 테마

설정 › 일반 › **테마**에서 미리보기를 눌러 바로 바꿉니다. 패널, 펼침 칸, 플로팅 패널, 말풍선에 적용됩니다.

<div align="center">
<img src="images/themes.png" width="900" alt="기본 · Dracula · Nord · 레트로 그린">
</div>

기본 테마는 라이트 모드에서도 자연스럽게 보입니다.

<div align="center">
<img src="images/display-light.png" width="760" alt="라이트 모드 — 디스플레이 밝기 조절바">
</div>

## ⌨️ 단축키

| 단축키 | 동작 |
|---|---|
| **⌥Space** | Divee 패널 열기 (메뉴바 고양이를 클릭해도 됩니다) |
| **⌃⌥Space** | 누르는 동안 음성 입력 |
| ⌥⌘O | 플로팅 패널 접기·펼치기 |
| ⌥⌘C | 화면 색 추출 |
| ⌃⌥J | 빠른 메모 |
| 메뉴바 아이콘 우클릭 | 설정 · 플로팅 패널 고정 · 종료 |

모든 단축키는 설정 › 단축키에서 바꿀 수 있습니다.

## 📦 설치

1. [**Divee-1.0.0.dmg**](https://github.com/dorkman43/divee/releases/latest/download/Divee-1.0.0.dmg)를 내려받습니다.
2. DMG를 열고 **Divee**를 **응용 프로그램** 폴더로 끌어다 놓습니다.
3. Divee를 실행하면 메뉴바에 고양이 아이콘이 생기고, 처음 한 번 사용 안내가 나옵니다.

Apple 공증을 마친 앱이라 "확인되지 않은 개발자" 경고 없이 열립니다.

**요구 사항:** macOS 14 Sonoma 이상, Apple Silicon Mac (M1 이후)

### 권한

켜는 기능에 필요한 권한만, 이유와 함께 물어봅니다.

| 권한 | 쓰는 곳 |
|---|---|
| 손쉬운 사용 | 창 정리, 스페이스 전환 |
| 화면 기록 | 화면 읽기 |
| 캘린더 · 미리 알림 | 일정 확인·추가 |
| 마이크 · 음성 인식 | 음성 입력 (누르는 동안만) |
| 자동화 | 메모 앱, 다크 모드 전환·휴지통 비우기 |
| 관리자 암호 (1회) | 팬 속도 조절·닫힘 모드용 도우미 설치 |

### 지우기

팬 조절이나 닫힘 모드를 썼다면 설정 › 팬 & 온도에서 **도우미 제거**를 먼저 누르고, Divee를 종료한 뒤 앱을 휴지통으로 옮기면 됩니다.

## 🔒 개인정보

Divee는 기본적으로 **이 Mac 안에서만** 동작합니다. 다음 기능을 켰을 때만 밖으로 데이터가 나가며, 설정 › 정보에 지금 켜진 항목이 그대로 표시됩니다.

- **날씨**: 위치(도시) → open-meteo.com
- **웹 검색**: 검색어 → Bing
- **AI 사용량**: ChatGPT·Codex 서버에서 내 사용량 조회
- **원격 AI 백엔드**를 직접 고른 경우: 입력한 문장 → 그 서버

가속도계 값은 판정 직후 버리고, 키보드 입력은 수집하지 않습니다.

## 💬 피드백

버그나 제안은 [Issues](https://github.com/dorkman43/divee/issues)에 남겨 주세요.

---

<a id="english"></a>

<div align="center">

## English

**Everything you tweak on your Mac, in one menu bar app — one ⌥Space away.**

</div>

Divee is a free, lightweight menu bar utility for Apple Silicon Macs that gathers fans & temperature, brightness, battery, sleep, window arranging, clipboard history and more into a single cascading panel — with a little cat living in your menu bar.

<div align="center">
<img src="images/english-retro.png" width="760" alt="Divee in English with the Retro Green theme">
</div>

- **Cascading menu, just like a context menu.** Press **⌥Space**, hover or press → on a row, and its details slide out to the side. Fully keyboard-driven: ↑↓ move, → open, ← back, Return run, ESC close.
- **Lightweight.** ~0.6% CPU when closed, ~1% with the panel open. Native macOS animations only, and you can turn them off.
- **Turn on only what you need.** 24 modules: Fan & Temp, Display (external monitors via DDC), Battery, Sleep & Clamshell Mode, System monitor with sparklines, Quick Toggles, Clipboard, Notes, Color Picker, Symbols, Window Arrange, Space names, Calendar, Weather, Local search, and an AI assistant that runs on-device first (Apple Intelligence / Ollama) or on an OpenAI-compatible server of your choice.
- **Themes:** Default (follows your system), Dracula, Nord and Retro Green.
- **Private by default.** Nothing leaves your Mac unless you enable Weather (open-meteo.com), Web search (Bing), AI Usage, or a remote AI backend — Settings › About always lists what is currently on.

**Install:** download [Divee-1.0.0.dmg](https://github.com/dorkman43/divee/releases/latest/download/Divee-1.0.0.dmg), drag Divee to Applications and launch it. Notarized by Apple.<br>
**Requires:** macOS 14 Sonoma or later, Apple Silicon (M1 or later).<br>
**Shortcuts:** ⌥Space open panel · ⌃⌥Space hold to talk · ⌥⌘O floating panel · ⌥⌘C pick a screen color · right-click the menu bar icon for Settings / Quit.

Feedback and bug reports are welcome in [Issues](https://github.com/dorkman43/divee/issues).

<div align="center">
<sub>© 2026 dorkman43 · Divee is free to use.</sub>
</div>
