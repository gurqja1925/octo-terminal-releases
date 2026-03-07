<p align="center">
  <img src="public/icons/app_icon.png" width="128" alt="Octo Terminal" />
</p>

<h1 align="center">Octo Terminal</h1>

<p align="center">
  <strong>A coding terminal powered by AI!</strong><br/>
  <strong>A coding terminal so easy, even elementary kids can use it!</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-0.1.41-blue" alt="Version" />
  <img src="https://img.shields.io/badge/platform-macOS%20(Apple%20Silicon)-black?logo=apple" alt="macOS" />
  <img src="https://img.shields.io/badge/platform-macOS%20(Intel)-gray?logo=apple" alt="macOS Intel" />
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-blue?logo=windows" alt="Windows" />
  <img src="https://img.shields.io/badge/Built%20with-Rust-orange?logo=rust" alt="Rust" />
  <img src="https://img.shields.io/badge/Framework-Tauri%202-blue?logo=tauri" alt="Tauri" />
  <img src="https://img.shields.io/badge/Frontend-React%2019-61dafb?logo=react" alt="React" />
</p>

---

## What is Octo Terminal?

**Octo Terminal** is like an octopus with many arms (terminals)! It's an all-in-one coding tool: terminal + editor + notes + AI in a single window. It also supports various document viewers (PowerPoint, Word, Excel, PDF, EPUB) and a Kanban board.

---

## Key Features

> See the Feature Details Guide for in-depth descriptions of each feature.

### AI & Terminal

| Feature | Description |
| --- | --- |
| AI Friends | Run Claude, Codex, OpenCode, Kimi, Ollama directly in the terminal |
| Orchestra | Multi-AI agent orchestration system |
| Skills | Reusable AI commands (model selection, gallery, one-click execution) |
| Voice Input | Speech-to-text conversion via Whisper API |
| CJK Input | Native IME support for Korean/Chinese/Japanese |

### Editor & Files

| Feature | Description |
| --- | --- |
| Code Editor | Monaco Editor + Vim mode + Emmet + Prettier |
| File Explorer | Tree view, drag & drop, multi-select, context menu |
| Markdown Notes | Global notes + project docs + AI auto-generation + tag/wikilink auto-organization |
| Note Graph View | Note connection visualization (4 layouts, minimap, glow effects) |
| EPUB Reader | EPUB e-book viewer (chapter navigation, table of contents, font size adjustment) |
| MD to EPUB | Export Markdown files as EPUB e-books |

### Layout & UI

| Feature | Description |
| --- | --- |
| Split View | 8 layouts (tabs, horizontal/vertical, tree, tile, grid, mix) |
| View Modes | Editor / Full / Side / Terminal / Browser / Kanban / PM2 / Hub — 8 modes |
| Themes | 75 themes + various coding fonts |
| Shortcuts | Octo / VSCode / IntelliJ presets |
| Kanban Board | Per-project Kanban board (To Do / In Progress / In Review / Done, drag & drop, tags) |

### Server & Remote

| Feature | Description |
| --- | --- |
| SSH Remote | Work on remote server projects via SSH as if they were local |
| SSH Config Integration | Auto-reads `~/.ssh/config`, host dropdown selection when creating projects |
| PM2 Server Monitoring | Real-time CPU/memory/disk monitoring with 3D gauges + spark charts |
| PM2 Multi-Project | SSH project selection tabs + drag-resize for at-a-glance server overview |
| PM2 Log Viewer | Full/selected process toggle, AI anomaly detection (Ollama) |
| Scheduler | Automatically run CLI commands at set intervals |

### Integrations

| Feature | Description |
| --- | --- |
| Hub Unified Feed | View Linear/Slack/GitHub issues in one place + pagination |
| Per-Project Integration | Individual GitHub repository and Slack channel settings per project |
| Telegram | Remote terminal monitoring + command sending (per-project chat mapping) |
| Discord | Remote control + mirroring via Discord Bot (same as Telegram) |
| Slack | Remote control + mirroring via Slack Bot (same as Telegram/Discord) |
| Built-in Browser | Browser panel + MCP integration for CLI-based browser control |
| MCP Server | MCP server management + auto-integration with Claude/Codex CLI |
| Vault | Password-protected storage for API keys / code snippets |

> Skills DB / Detached Window documentation: docs/SKILLS-DB-AND-STUDIO.md

---

## Screen Layout

```
+--------------------------------------------------+
| [View] [Project1] [Project2] [+]  [Menu▼] [Settings] |  <- Project tab bar
+----------+---------------------------------------+
|          |  Editor Area                          |
| File     |  (Code/Markdown editing)              |
| Explorer |                                       |
|   or     +---------------------------------------+
| Notes    |  Terminal Area                        |
| Sidebar  |  $ _                                  |
|          |  [Tab1] [Tab2] [+Claude] [+Codex]     |
+----------+---------------------------------------+
```

---

## Installation

Download the latest version from [GitHub Releases](https://github.com/johunsang/octo-terminal-releases/releases).

| Platform | File | Description |
| --- | --- | --- |
| macOS (Apple Silicon) | `Octo.Terminal_x.x.x_aarch64.dmg` | For M1/M2/M3/M4 Mac |
| macOS (Intel) | `Octo.Terminal_x.x.x_x64.dmg` | For Intel Mac |
| Windows | `Octo.Terminal_x.x.x_x64-setup.exe` | NSIS installer |
| Windows | `Octo.Terminal_x.x.x_x64_en-US.msi` | Windows Installer |

### macOS

1. Download the `.dmg` file matching your Mac from the table above
2. Double-click the `.dmg` file → drag to the Applications folder
3. Launch from Launchpad or Spotlight (`Cmd + Space` > "octo")

> Signed with Apple Developer ID — runs without Gatekeeper warnings.

### Windows

1. Download `.exe` or `.msi` from the table above (do not download `.dmg` — that's macOS only!)
2. Run the installer → follow the instructions
3. Launch "Octo Terminal" from the Start Menu or desktop

> On Windows, use `Ctrl` instead of `Cmd`.

---

## Quick Start

1. **Open a Project** — Click "+" to select a working folder
2. **Browse Files** — Click files in the left sidebar
3. **Edit Code** — Edit in the top editor area, `Cmd+S` to save
4. **Use Terminal** — Run commands in the bottom terminal
5. **Use AI** — Click "+" to launch a Claude/Codex/Kimi/Ollama terminal
6. **Take Notes** — Manage Markdown notes in the sidebar "Notes" tab
7. **Browser** — Open the built-in browser from the menu, control via MCP from CLI
8. **Voice Input** — Hold `Right Alt` and speak → release to convert to text (requires OpenAI API key in Settings > Agent > Whisper)
9. **PM2 Monitor** — Select PM2 in view mode for real-time server status per SSH project
10. **Hub** — Select Hub in view mode to view Linear/Slack/GitHub issues in one unified feed

---

## PM2 Server Monitoring

Monitor PM2 processes and server status of SSH projects in real time.

### Features

| Feature | Description |
| --- | --- |
| Process List | PM2 process status, CPU, memory, restart count |
| Log Viewer | Real-time log streaming for all/selected processes |
| AI Anomaly Detection | Automatic detection of abnormal log patterns via Ollama |
| Server Dashboard | CPU, memory, disk usage with 3D gauges + spark charts |
| Multi-Project | All/individual project tab selection, drag-to-resize panels |

### How to Use

1. Create an SSH project (you can select a host from `~/.ssh/config` in settings)
2. Select **PM2** in view mode
3. Select **All** or an individual project from the top tabs
4. Click a process on the left → view real-time logs in the right panel
5. Monitor CPU/memory/disk in the bottom server dashboard

---

## Hub Unified Feed

View Linear, Slack, and GitHub issues all in one place.

### Setup

1. Register API tokens for each service in Settings > Integrations
2. Optionally configure per-project GitHub repositories and Slack channels
3. Select **Hub** in view mode

### Features

- Color-coded source filters (Linear/Slack/GitHub)
- Click cards for detailed content
- Pagination (8 per page)
- Quick open (external browser)

---

## Built-in Browser + MCP Integration

Octo Terminal includes a built-in browser, allowing Claude/Codex CLI to directly control the browser.

### How to Use

1. Select browser mode from the menu
2. In Settings > **Browser** tab, select a project then:
   - **Install for Project** — Register MCP server in `.mcp.json`
   - **Install /browse** — Install the `/browse` slash command
3. Control the browser with natural language from CLI:
   - `/browse open https://google.com`
   - `/browse read page text`
   - `/browse take a screenshot`

### MCP Tools

| Tool | Description |
| --- | --- |
| `navigate` | Navigate to a URL |
| `get_page_text` | Extract page text |
| `get_page_html` | Get HTML source |
| `get_page_info` | Current URL, title, status |
| `javascript_eval` | Execute JavaScript |
| `screenshot` | Take a screenshot |
| `console_logs` | View console logs |
| `go_back` / `go_forward` / `reload` | Navigation |
| `list_tabs` / `new_tab` / `switch_tab` / `close_tab` | Tab management |

### Architecture

```
CLI (Claude/Codex) → MCP Server (stdio) → HTTP POST localhost:19980
  → Rust browser_bridge (axum) → Tauri event → BrowserPanel (React)
    → Result → invoke("browser_bridge_respond") → HTTP response → CLI
```

---

## Telegram Remote Control

Connect a Telegram bot to monitor terminal output and send commands from your smartphone while on the go.

### Initial Setup

1. **Create a Bot** — Search `@BotFather` on Telegram → `/newbot` → enter a bot name → copy the **bot token**
2. **Register Token** — Settings > Agent > Telegram > paste bot token → "Verify & Save"
3. **Link Chat** — Send any message to the bot → Settings > Agent > Telegram wizard > click "Detect Chat"
4. **Map Project** — Link the detected chat to your desired project

### Features

| Feature | Description |
| --- | --- |
| Output Mirroring | Automatically sends terminal screen changes to Telegram chat |
| Command Mirroring | Sends entered commands to Telegram (auto-masks passwords/API keys) |
| Remote Commands | Messages sent from Telegram are delivered to the project's active terminal |
| Per-Project Chat | Assign different Telegram chat IDs per project |

### Security

- Sensitive information like API keys, bot tokens, and passwords are automatically masked with `***` before sending
- Unnecessary output like `(thinking)` is automatically filtered
- Bot tokens are stored locally only (never sent to external servers)

---

## Discord Remote Control

Remote monitoring and control via Discord Bot, identical to Telegram.

### Setup

1. Create a Bot at the [Discord Developer Portal](https://discord.com/developers/applications)
2. Copy bot token → Settings > Agent > Discord > register bot token
3. Invite the bot to your server → map the channel ID to a project

---

## Slack Remote Control

Remote monitoring and control via Slack Bot, identical to Telegram/Discord.

### Setup

1. Create an app at [Slack API](https://api.slack.com/apps)
2. Add Bot Token Scopes: `chat:write`, `channels:history`, `channels:read`
3. Install the app to your workspace → copy the Bot User OAuth Token (`xoxb-...`)
4. Settings > Agent > Slack > register bot token
5. Invite the bot to a channel (`/invite @botname`) → map the channel ID to a project

---

## Troubleshooting

| Problem | Solution |
| --- | --- |
| "File is damaged" (Mac) | Automatically resolved in v0.1.6+. For older versions: `xattr -cr "/Applications/Octo Terminal.app"` |
| Korean/CJK input not working | Settings > Terminal > change Input mode to "IME" |
| Shortcuts not working | Check presets in Settings > Shortcuts, use Cmd key |
| AI not responding | Check internet / API keys / Ollama: run `ollama serve` |
| Browser MCP not working | Ensure browser mode is on. Install MCP in Settings > Browser |
| `/browse` not working | Click "Install /browse" in Settings > Browser, then restart CLI |
| Telegram not working | Verify bot token in Settings > Agent > Telegram. Send a message to the bot first, then click "Detect Chat" |
| Telegram messages not arriving | Check that a Chat ID is mapped to the project. Ensure mirroring options are enabled |
| PM2 not showing | Only available for SSH projects. PM2 must be installed on the remote server |

---

## Tech Stack

| Layer | Technology |
| --- | --- |
| Backend | Tauri v2, Rust, portable-pty, tokio, axum |
| Frontend | React 19, TypeScript, xterm.js |
| Code Editor | Monaco Editor (code), CodeMirror 6 (Markdown) |
| Terminal | xterm.js + WebGL renderer |
| Bundler | Vite 7 |
| Build/Deploy | GitHub Actions CI + GitHub Releases (macOS ARM/Intel, Windows) |

---

## Contact

- Bug Reports: [GitHub Issues](https://github.com/johunsang/octo-terminal-releases/issues)
- Email: johunsang@gmail.com

---

---

# Octo Terminal (Korean / 한국어)

**AI와 함께하는 코딩 터미널!**\
**초등학생도 쓸 수 있을 만큼 쉬운 코딩 터미널!**

---

## Octo Terminal이 뭐예요?

**Octo Terminal**은 문어(Octopus)처럼 여러 개의 팔(터미널)을 가진 프로그램이에요! 터미널 + 에디터 + 노트 + AI를 한 화면에서 쓸 수 있어요. 파워포인트, 워드, 엑셀, PDF, EPUB 등 다양한 문서 뷰어와 칸반 보드도 지원해요.

---

## 주요 기능

> 각 기능의 상세 설명은 기능 상세 가이드를 참고하세요.

### AI & 터미널

| 기능 | 설명 |
| --- | --- |
| AI 친구들 | Claude, Codex, OpenCode, Kimi, Ollama를 터미널에서 바로 실행 |
| Orchestra | 멀티 AI 에이전트 오케스트레이션 시스템 |
| Skills | 재사용 가능한 AI 명령어 (모델 선택, 갤러리, 원클릭 실행) |
| 음성 입력 | Whisper API로 음성 → 텍스트 변환 |
| CJK 입력 | 한국어/중국어/일본어 네이티브 IME 지원 |

### 에디터 & 파일

| 기능 | 설명 |
| --- | --- |
| 코드 에디터 | Monaco Editor + Vim 모드 + Emmet + Prettier |
| 파일 탐색기 | 트리 뷰, 드래그 앤 드롭, 멀티 선택, 컨텍스트 메뉴 |
| 마크다운 노트 | 글로벌 노트 + 프로젝트 문서 + AI 자동 생성 + 태그/위키링크 자동 정리 |
| 노트 그래프뷰 | 노트 연결 시각화 (4가지 레이아웃, 미니맵, 글로우 효과) |
| EPUB 리더 | EPUB 전자책 뷰어 (챕터 네비게이션, 목차, 글꼴 크기 조절) |
| MD → EPUB | 마크다운 파일을 EPUB 전자책으로 내보내기 |

### 레이아웃 & UI

| 기능 | 설명 |
| --- | --- |
| 화면 분할 | 8가지 레이아웃 (탭, 가로/세로, 트리, 타일, 그리드, 믹스) |
| 뷰 모드 | 에디터 / 전체 / 사이드 / 터미널 / 브라우저 / 칸반 / PM2 / Hub — 8단계 전환 |
| 테마 | 75개 테마 + 다양한 코딩 폰트 |
| 단축키 | Octo / VSCode / IntelliJ 프리셋 |
| 칸반 보드 | 프로젝트별 칸반 보드 (할 일/진행 중/검토 중/완료, 드래그 앤 드롭, 태그) |

### 서버 & 원격

| 기능 | 설명 |
| --- | --- |
| SSH 원격 | SSH로 원격 서버 프로젝트를 로컬처럼 작업 |
| SSH Config 연동 | `~/.ssh/config` 자동 읽기, 프로젝트 생성 시 호스트 드롭다운 선택 |
| PM2 서버 모니터링 | 3D 게이지 + 스파크 차트로 CPU/메모리/디스크 실시간 모니터링 |
| PM2 멀티 프로젝트 | SSH 프로젝트 선택 탭 + 드래그 리사이즈로 서버 한눈에 확인 |
| PM2 로그 뷰어 | 전체/선택 프로세스 토글, AI 이상 감지 (Ollama) |
| 스케줄러 | CLI 명령어를 정해진 간격으로 자동 실행 |

### 연동 & 통합

| 기능 | 설명 |
| --- | --- |
| Hub 통합 피드 | Linear/Slack/GitHub 이슈를 한 곳에서 조회 + 페이지네이션 |
| 프로젝트별 연동 | 프로젝트마다 GitHub 저장소, Slack 채널 개별 설정 |
| 텔레그램 | 터미널 원격 모니터링 + 명령어 전송 (프로젝트별 채팅 매핑) |
| 디스코드 | Discord Bot으로 원격 제어 + 미러링 (텔레그램과 동일) |
| 슬랙 | Slack Bot으로 원격 제어 + 미러링 (텔레그램/디스코드와 동일) |
| 내장 브라우저 | 브라우저 패널 + MCP 연동으로 CLI에서 브라우저 제어 |
| MCP 서버 | MCP 서버 관리 + Claude/Codex CLI 자동 연동 |
| 볼트 | 비밀번호로 보호되는 API 키 / 코드 조각 저장소 |

> Skills DB/분리창 운영 문서: docs/SKILLS-DB-AND-STUDIO.md

---

## 화면 구성

```
+--------------------------------------------------+
| [뷰] [프로젝트1] [프로젝트2] [+]    [메뉴▼] [설정] |  <- 프로젝트 탭 바
+----------+---------------------------------------+
|          |  에디터 영역                           |
| 파일     |  (코드/마크다운 편집)                  |
| 탐색기   |                                       |
|   또는   +---------------------------------------+
| 메모     |  터미널 영역                           |
| 사이드바 |  $ _                                   |
|          |  [탭1] [탭2] [+Claude] [+Codex]        |
+----------+---------------------------------------+
```

---

## 설치 방법

[GitHub Releases](https://github.com/johunsang/octo-terminal-releases/releases)에서 최신 버전을 다운로드하세요.

| 플랫폼 | 파일 | 설명 |
| --- | --- | --- |
| macOS (Apple Silicon) | `Octo.Terminal_x.x.x_aarch64.dmg` | M1/M2/M3/M4 Mac용 |
| macOS (Intel) | `Octo.Terminal_x.x.x_x64.dmg` | Intel Mac용 |
| Windows | `Octo.Terminal_x.x.x_x64-setup.exe` | NSIS 설치 프로그램 |
| Windows | `Octo.Terminal_x.x.x_x64_en-US.msi` | Windows Installer |

### macOS

1. 위 표에서 본인 Mac에 맞는 `.dmg` 다운로드
2. `.dmg` 파일 더블클릭 → Applications 폴더로 드래그
3. Launchpad 또는 Spotlight(`Cmd + Space` > "octo")에서 실행

> Apple Developer ID 코드 서명이 적용되어 Gatekeeper 경고 없이 바로 실행됩니다.

### Windows

1. 위 표에서 `.exe` 또는 `.msi` 다운로드 (`.dmg`는 macOS 전용이므로 받지 마세요!)
2. 설치 파일 실행 → 안내에 따라 설치
3. 시작 메뉴 또는 바탕화면에서 "Octo Terminal" 실행

> Windows에서는 `Cmd` 대신 `Ctrl` 키를 사용합니다.

---

## 빠른 시작

1. **프로젝트 열기** — "+" 버튼으로 작업 폴더 선택
2. **파일 탐색** — 왼쪽 사이드바에서 파일 클릭
3. **코드 편집** — 상단 에디터에서 수정, `Cmd+S` 저장
4. **터미널 사용** — 하단 터미널에서 명령어 실행
5. **AI 활용** — "+" 버튼으로 Claude/Codex/Kimi/Ollama 터미널 실행
6. **노트 작성** — 사이드바 "메모" 탭에서 마크다운 노트 관리
7. **브라우저** — 메뉴에서 내장 브라우저 열기, CLI에서 MCP로 제어
8. **음성 입력** — `Right Alt` 키를 길게 누르고 말하기 → 키를 떼면 텍스트로 변환 (설정 > Agent > Whisper에서 OpenAI API 키 설정 필요)
9. **PM2 모니터** — 뷰 모드에서 PM2 선택, SSH 프로젝트별 서버 상태 실시간 확인
10. **Hub** — 뷰 모드에서 Hub 선택, Linear/Slack/GitHub 이슈 통합 조회

---

## PM2 서버 모니터링

SSH 프로젝트의 PM2 프로세스와 서버 상태를 실시간으로 모니터링합니다.

### 기능

| 기능 | 설명 |
| --- | --- |
| 프로세스 목록 | PM2 프로세스 상태, CPU, 메모리, 재시작 횟수 |
| 로그 뷰어 | 전체/선택 프로세스 로그 실시간 스트리밍 |
| AI 이상 감지 | Ollama 연동으로 로그 이상 패턴 자동 감지 |
| 서버 대시보드 | CPU, 메모리, 디스크 사용량 3D 게이지 + 스파크 차트 |
| 멀티 프로젝트 | 전체/개별 프로젝트 탭 선택, 드래그로 패널 크기 조절 |

### 사용 방법

1. SSH 프로젝트를 생성 (설정에서 `~/.ssh/config` 호스트 선택 가능)
2. 뷰 모드에서 **PM2** 선택
3. 상단 탭에서 **전체** 또는 개별 프로젝트 선택
4. 좌측 프로세스 클릭 → 우측 로그 뷰어에서 실시간 확인
5. 하단 서버 대시보드에서 CPU/메모리/디스크 모니터링

---

## Hub 통합 피드

Linear, Slack, GitHub 이슈를 한 곳에서 확인합니다.

### 설정

1. 설정 > 연동에서 각 서비스 API 토큰 등록
2. 프로젝트별로 GitHub 저장소, Slack 채널 개별 설정 가능
3. 뷰 모드에서 **Hub** 선택

### 기능

- 소스별 컬러 필터 (Linear/Slack/GitHub)
- 카드 클릭으로 상세 내용 확인
- 페이지네이션 (8개씩)
- 바로 열기 (외부 브라우저)

---

## 내장 브라우저 + MCP 연동

Octo Terminal에는 내장 브라우저가 포함되어 있어, Claude/Codex CLI에서 브라우저를 직접 제어할 수 있습니다.

### 사용 방법

1. 메뉴에서 브라우저 모드 선택
2. 설정 > **브라우저** 탭에서 프로젝트 선택 후:
   - **프로젝트 설치** — `.mcp.json`에 MCP 서버 등록
   - **/browse 설치** — `/browse` 슬래시 커맨드 설치
3. CLI에서 자연어로 브라우저 제어:
   - `/browse https://google.com 열어줘`
   - `/browse 페이지 텍스트 읽어줘`
   - `/browse 스크린샷 찍어줘`

### MCP 도구 목록

| 도구 | 설명 |
| --- | --- |
| `navigate` | URL로 이동 |
| `get_page_text` | 페이지 텍스트 추출 |
| `get_page_html` | HTML 소스 |
| `get_page_info` | 현재 URL, 제목, 상태 |
| `javascript_eval` | JavaScript 실행 |
| `screenshot` | 스크린샷 촬영 |
| `console_logs` | 콘솔 로그 확인 |
| `go_back` / `go_forward` / `reload` | 탐색 |
| `list_tabs` / `new_tab` / `switch_tab` / `close_tab` | 탭 관리 |

### 아키텍처

```
CLI (Claude/Codex) → MCP Server (stdio) → HTTP POST localhost:19980
  → Rust browser_bridge (axum) → Tauri event → BrowserPanel (React)
    → 결과 → invoke("browser_bridge_respond") → HTTP response → CLI
```

---

## 텔레그램 원격 제어

Telegram 봇을 연결하면, 외출 중에도 스마트폰에서 터미널 출력을 확인하고 명령어를 보낼 수 있습니다.

### 초기 설정

1. **봇 만들기** — Telegram에서 `@BotFather` 검색 → `/newbot` → 봇 이름 입력 → **봇 토큰** 복사
2. **토큰 등록** — 설정 > Agent > Telegram > 봇 토큰 붙여넣기 → "확인 및 저장"
3. **채팅 연결** — 봇에게 아무 메시지 전송 → 설정 > Agent > Telegram 위자드에서 "채팅 감지" 클릭
4. **프로젝트 매핑** — 감지된 채팅을 원하는 프로젝트에 연결

### 기능

| 기능 | 설명 |
| --- | --- |
| 출력 미러링 | 터미널 화면 변경을 Telegram 채팅으로 자동 전송 |
| 명령어 미러링 | 입력한 명령어를 Telegram으로 전송 (비밀번호/API키 자동 마스킹) |
| 원격 명령어 | Telegram에서 보낸 메시지가 프로젝트의 활성 터미널로 전달 |
| 프로젝트별 채팅 | 프로젝트마다 다른 Telegram 채팅 ID 지정 가능 |

### 보안

- API 키, 봇 토큰, 비밀번호 등 민감한 정보는 전송 전 자동으로 `***`로 마스킹
- `(thinking)` 등 불필요한 출력은 자동 필터링
- 봇 토큰은 로컬에만 저장 (서버 전송 없음)

---

## 디스코드 원격 제어

텔레그램과 동일한 방식으로 Discord Bot을 통해 원격 모니터링/제어가 가능합니다.

### 설정 방법

1. [Discord Developer Portal](https://discord.com/developers/applications)에서 Bot 생성
2. 봇 토큰 복사 → 설정 > Agent > Discord > 봇 토큰 등록
3. 봇을 서버에 초대 → 채널 ID를 프로젝트에 매핑

---

## 슬랙 원격 제어

텔레그램/디스코드와 동일한 방식으로 Slack Bot을 통해 원격 모니터링/제어가 가능합니다.

### 설정 방법

1. [Slack API](https://api.slack.com/apps)에서 앱 생성
2. Bot Token Scopes 추가: `chat:write`, `channels:history`, `channels:read`
3. 워크스페이스에 설치 → Bot User OAuth Token (`xoxb-...`) 복사
4. 설정 > Agent > Slack > 봇 토큰 등록
5. 채널에 봇 초대 (`/invite @봇이름`) → 채널 ID를 프로젝트에 매핑

---

## 문제 해결

| 문제 | 해결 |
| --- | --- |
| "파일이 손상되었다"고 떠요 (Mac) | v0.1.6 이상은 자동 해결. 이전 버전: `xattr -cr "/Applications/Octo Terminal.app"` |
| 한글이 안 쳐져요 | 설정 > Terminal > Input mode를 "IME"로 변경 |
| 단축키가 안 먹어요 | 설정 > Shortcuts에서 프리셋 확인, Cmd 키 사용 |
| AI가 응답이 없어요 | 인터넷 확인 / API 키 확인 / Ollama: `ollama serve` 실행 |
| 브라우저 MCP가 안 돼요 | 브라우저 모드가 켜져 있는지 확인. 설정 > 브라우저에서 MCP 설치 |
| `/browse`가 안 먹어요 | 설정 > 브라우저 > `/browse 설치` 클릭 후 CLI 재시작 |
| 텔레그램이 안 돼요 | 설정 > Agent > Telegram에서 봇 토큰 확인. 봇에게 메시지를 먼저 보낸 후 "채팅 감지" 클릭 |
| 텔레그램 메시지가 안 와요 | 프로젝트에 Chat ID가 매핑되어 있는지 확인. 미러링 옵션 활성화 확인 |
| PM2가 안 뜨여요 | SSH 프로젝트에서만 사용 가능. 원격 서버에 PM2가 설치되어 있어야 합니다 |

---

## 기술 스택

| 레이어 | 기술 |
| --- | --- |
| 백엔드 | Tauri v2, Rust, portable-pty, tokio, axum |
| 프론트엔드 | React 19, TypeScript, xterm.js |
| 코드 에디터 | Monaco Editor (코드), CodeMirror 6 (마크다운) |
| 터미널 | xterm.js + WebGL 렌더러 |
| 번들러 | Vite 7 |
| 빌드/배포 | GitHub Actions CI + GitHub Releases (macOS ARM/Intel, Windows) |

---

## 연락처

- 버그 신고: [GitHub Issues](https://github.com/johunsang/octo-terminal-releases/issues)
- 문의: johunsang@gmail.com

---

**Octo Terminal**\
*Small but mighty, your coding friend*\
*작지만 강한, 당신의 코딩 친구*\
Made with love by [johunsang](https://github.com/johunsang)
