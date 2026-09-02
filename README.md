<div align="center">

<img src="docs/images/00-icon.png" width="88" alt="">

# 스크린샷 · ScreenCapture

**맥의 스크린샷을 윈도우에서 그대로.**
끌면 그 자리에서 바탕 화면에 PNG 가 떨어집니다.

한국어 · [English](README.en.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md)

### [⬇ ScreenCapture.exe 내려받기 (Windows 10 · 11 · 64비트)](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture.exe)

무료 · 설치 필요 없음 · 계정 없음 · 받아서 바로 실행

화면 기록까지 쓰려면 [`ffmpeg.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ffmpeg.exe) 도 받아 **같은 폴더**에 두세요.
([두 파일을 한 번에 받는 zip](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture-win64.zip))

<!-- Microsoft Store 등록이 끝나면 아래 두 줄의 주석을 풀고 URL 을 채우세요.
[<img src="https://get.microsoft.com/images/ko%20dark.svg" width="200" alt="Microsoft Store에서 받기">](https://apps.microsoft.com/detail/여기에-스토어-ID)
-->
**Microsoft Store** — 심사 준비 중입니다. 등록되면 이 자리에 배지가 붙습니다.

</div>

---

## 왜 만들었나

윈도우에도 캡처 도구가 있지만 **저장이 번거롭습니다.** 클립보드에 들어가고, 알림을
누르고, 편집기가 열리고, 저장 위치를 고릅니다. 맥은 영역을 끌면 그 자리에서 바탕
화면에 PNG 가 떨어집니다. 이 앱은 그 흐름을 윈도우로 옮긴 것입니다.

창은 없습니다. 실행하면 트레이에 들어가고, 단축키만 기억하면 됩니다.

## 무엇을 할 수 있나

### 끌면 끝 — `Ctrl+Shift+4`

![부분 캡처](docs/images/03-region.png)

크로스헤어로 영역을 끌고 놓는 순간 파일이 저장됩니다. 크기는 끄는 동안 계속 보이고,
`Ctrl` 을 누른 채 놓으면 파일 대신 클립보드로 갑니다.

### 맥과 같은 도구 툴바 — `Ctrl+Shift+5`

![스크린샷 도구](docs/images/02-toolbar.png)

전체 화면 · 창 · 부분 캡처, 전체 화면 기록 · 부분 기록. 선택 영역은 8방향 핸들로
조절하고, 안쪽을 끌어 옮깁니다.

### 저장 위치 · 타이머 · 마이크

![옵션](docs/images/04-options.png)

맥 스크린샷의 옵션 메뉴를 항목과 순서까지 옮겼습니다. 여기에 **언어** 항목이
하나 더 있습니다.

### 화면 기록 — 중간에 끊겨도 살아남습니다

![기록 중 표시](docs/images/05-recording.png)

기록 중에는 화면 위쪽에 경과 시간과 정지 버튼이 뜹니다. **이 표시는 녹화본에는
찍히지 않습니다.** 조각 단위로 디스크에 써 내려가기 때문에, 기록 도중 앱이 꺼져도
그때까지의 영상은 그대로 재생됩니다.

### 찍고 나면 우하단에 잠깐

![플로팅 썸네일](docs/images/06-thumbnail.png)

클릭하면 열리고, 끌어다 다른 앱에 놓을 수 있고, 우클릭하면 열기 · 폴더에서 보기 ·
복사 · 삭제가 나옵니다.

### 처음 켜면 사용법이 먼저

![시작 안내](docs/images/01-guide.png)

창 없는 앱이라 처음 켜면 무슨 일이 일어났는지 알기 어렵습니다. 화면 한가운데에
단축키를 5초간 보여 주고 사라집니다. 트레이 메뉴에서 언제든 다시 볼 수 있습니다.

## 단축키

맥의 `Cmd` 를 `Ctrl` 로 그대로 옮겼습니다.

| 맥 | 윈도우 | 동작 |
| --- | --- | --- |
| `Cmd+Shift+3` | `Ctrl+Shift+3` | 전체 화면 캡처 — 디스플레이마다 파일 하나 |
| `Cmd+Shift+4` | `Ctrl+Shift+4` | 끌어서 부분 캡처 |
| `Cmd+Shift+4` → `Space` | 같음 | 창 선택 모드 |
| `Cmd+Shift+5` | `Ctrl+Shift+5` | 스크린샷 도구 툴바 |
| `Cmd+Ctrl+Shift+3/4` | `Ctrl+Alt+Shift+3/4` | 파일 대신 클립보드로 |
| `Cmd+Ctrl+Esc` | `Ctrl+Alt+Esc` | 기록 정지 |

드래그 중에는 `Space`(위치 옮기기) · `Shift`(한 축만) · `Alt`(중심 대칭) ·
`Ctrl`(클립보드로) · `Esc`(취소) 가 맥과 똑같이 동작합니다.

## 설치

1. [`ScreenCapture.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ScreenCapture.exe) 를 받아 원하는 폴더에 둡니다.
2. 실행하면 트레이에 들어갑니다. **설치 과정도, 관리자 권한도 필요 없습니다.**
3. 화면 기록을 쓸 거라면 [`ffmpeg.exe`](https://github.com/develckm86/mac_shot/releases/latest/download/ffmpeg.exe) 를 받아 **같은 폴더**에 둡니다.
   캡처만 쓸 거면 없어도 됩니다 — 기록 기능만 조용히 비활성화됩니다.

지우고 싶으면 파일을 지우면 끝입니다. 설정만 `%APPDATA%\ScreenCapture` 에 남습니다.

> 서명되지 않은 실행 파일이라 처음 실행할 때 SmartScreen 이 한 번 물어볼 수 있습니다.
> **추가 정보 → 실행**을 누르면 됩니다.

## 언어

12개 언어로 뜹니다. 기본은 **윈도우 표시 언어**이고, 옵션 메뉴에서 직접 고를 수도
있습니다.

한국어 · English · 日本語 · 简体中文 · 繁體中文 · Español · Português ·
Français · Deutsch · Русский · Italiano · Tiếng Việt

언어별 사용 설명서는 [`docs/manual/`](docs/manual) 에 있습니다.

## 광고에 대해

이 앱은 무료이고 광고로 운영됩니다. **캡처가 끝난 뒤에만**, 우하단 작업 표시줄 위에
사각 배너가 9초간 떴다 사라집니다.

![광고 배너](docs/images/08-ad.png)

- 위쪽 띠에 **광고 표시와 ✕** 가 늘 붙어 있습니다.
- 캡처가 시작되면 배너부터 치웁니다 — **결과물이나 녹화본에는 찍히지 않습니다.**
- 캡처를 방해하지 않습니다. 인터넷이 안 되면 빈 배너만 뜨고 캡처는 그대로 됩니다.
- 광고 이미지를 받아 오는 것 말고는 **아무 데이터도 수집·전송하지 않습니다.**
  찍은 이미지와 영상은 지정한 폴더에만 저장되고 앱 밖으로 나가지 않습니다.

## 요구 사항

| | |
| --- | --- |
| 운영 체제 | Windows 10 버전 2004 이상 / Windows 11 (64비트) |
| 권한 | 관리자 권한 필요 없음 |
| 디스크 | 약 170MB (앱 + ffmpeg) |

## 라이선스와 재배포

**누구나 그대로 퍼뜨려도 됩니다.** 웹사이트, 블로그, USB, 사내 배포 모두 허락을
따로 받을 필요가 없습니다. 다만 광고를 없애거나 광고 링크를 다른 것으로 바꾼 사본은
배포할 수 없습니다 — 그게 이 앱을 무료로 유지하는 방법입니다. 자세한 조건은
[LICENSE](LICENSE) 에 있습니다.

함께 배포하는 `ffmpeg.exe` 는 FFmpeg 자체의 라이선스(LGPL/GPL)를 따릅니다.

---

<div align="center">
문제가 있거나 원하는 기능이 있으면 <a href="https://github.com/develckm86/mac_shot/issues">이슈</a>로 알려 주세요.
</div>
