<p align="center">
  <img src="assets/app_icon.png" width="128" alt="Octo Terminal — The Ultimate Vibe Coding Terminal with AI" />
</p>

<h1 align="center">Octo Terminal</h1>
<h3 align="center">The Ultimate Vibe Coding Terminal</h3>

<p align="center">
  <strong>AI-powered all-in-one terminal for vibe coding.</strong><br/>
  Multi-project, multi-terminal — switch freely between projects and terminals like a pro.<br/>
  Built-in Claude, Codex, Ollama, Kimi — terminal + editor + notes + browser + AI image studio in a single app.<br/>
  <em>The best AI coding terminal for developers who vibe code.</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-0.1.42-blue" alt="Version" />
  <img src="https://img.shields.io/badge/platform-macOS%20(Apple%20Silicon)-black?logo=apple" alt="macOS" />
  <img src="https://img.shields.io/badge/platform-macOS%20(Intel)-gray?logo=apple" alt="macOS Intel" />
  <img src="https://img.shields.io/badge/platform-Windows%2010%2F11-blue?logo=windows" alt="Windows" />
  <img src="https://img.shields.io/badge/Built%20with-Rust-orange?logo=rust" alt="Rust" />
  <img src="https://img.shields.io/badge/Framework-Tauri%202-blue?logo=tauri" alt="Tauri" />
  <img src="https://img.shields.io/badge/Frontend-React%2019-61dafb?logo=react" alt="React" />
</p>

<!--
SEO Keywords: vibe coding, vibe coding terminal, ai terminal, ai coding terminal, ai ide,
best coding terminal, ultimate coding terminal, claude terminal, codex terminal, ollama terminal,
ai developer tools, ai pair programming, ai code editor, terminal emulator, tauri terminal,
rust terminal, react terminal, xterm terminal, ssh terminal, mcp server, ai agent terminal,
vibe code, coding with ai, ai-powered ide, desktop terminal app, macos terminal, windows terminal,
developer productivity, ai coding assistant, multi ai terminal, ai orchestration,
multi project terminal, multi tab terminal, ai image generator, nanobanana, gemini image studio,
marketing banner generator, logo generator, app icon generator, ai design tool
-->

---

## What is Octo Terminal?

**Octo Terminal** is the ultimate vibe coding terminal — like an octopus with many arms (terminals)!

**The killer feature: Multi-Project + Multi-Terminal.** Open dozens of projects simultaneously, each with its own set of terminals, themes, and settings. Switch between projects instantly with tabs. Split terminals horizontally, vertically, in grids — run Claude in one pane, your dev server in another, and Codex in a third, all within the same project. Seamlessly jump between projects and terminals like a multitasking octopus.

It's an all-in-one AI-powered coding tool: terminal + editor + notes + AI + image studio in a single window. Run Claude, Codex, Ollama, and Kimi side by side. It also supports various document viewers (PowerPoint, Word, Excel, PDF, EPUB), a Kanban board, and NanoBanana AI image generation.

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
| Multilingual | 8 languages: English, Korean, Japanese, Chinese, French, German, Italian, Spanish |

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
| NanoBanana | AI design studio — 16 services: banners, logos, dev images, art, fashion models, outfits, influencer photos, ad packs, ad videos, cartoons, interior, pets, 360° rotation, smart store, web builder (Gemini/Imagen/Veo) |

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

## Skills System

Skills are reusable AI prompt templates that you can execute with one click. They support model selection, parameter input, and gallery view.

### How to Set Up Skills

1. **Open Skills Panel** — Click the "Skills" tab in the sidebar or use the command palette
2. **Browse Skills** — Browse built-in skills or import from external sources
3. **Configure a Skill**:
   - **Name**: Display name for the skill
   - **Prompt Template**: The AI prompt with `{{variable}}` placeholders
   - **Model**: Select which AI model to use (Claude, Codex, Ollama, etc.)
   - **Parameters**: Define input fields that fill template variables
4. **Run a Skill** — Click "Run" or use the keyboard shortcut. Results appear in the terminal or gallery view.

### Skills Hub

Browse and install community skills from the Skills Hub:

1. Go to Settings > **Skills Hub**
2. Browse featured skill packs or paste a GitHub repository URL
3. Click "Install" to add skills to your local collection

### Custom Skill Files

Skills are stored as JSON in your project's `.octo/skills/` directory:

```json
{
  "name": "Generate README",
  "prompt": "Generate a README.md for {{project_name}} with features: {{features}}",
  "model": "claude",
  "parameters": [
    { "name": "project_name", "label": "Project Name", "type": "text" },
    { "name": "features", "label": "Key Features", "type": "textarea" }
  ]
}
```

### External Skill Packs

You can import skill packs from GitHub repositories. The app supports:
- **Direct JSON manifests** — URL pointing to a JSON skill manifest file
- **GitHub repositories** — Paste a repo URL, and Octo Terminal will crawl for `SKILL.md` files automatically
- **Local manifests** — Pre-bundled famous skill packs (2.3MB+ of curated skills)

---

## NanoBanana — AI Image & Design Studio

NanoBanana is Octo Terminal's built-in AI design studio powered by Google Gemini (Gemini 3 Pro, Gemini 3.1 Flash, Imagen 4, Veo 3.1). Generate marketing banners, logos, app icons, fashion model photos, AI art, ad packages, web pages, and more — all without leaving the terminal.

### Services (16 total)

| Service | Description |
| --- | --- |
| **Dev Image** | App icons, favicons, OG images, splash screens, store screenshots, badges, error/success/loading illustrations — 20+ developer image types |
| **Banner** | AI marketing banner generation with mood, color scheme, background type, logo upload, multi-draft support |
| **Logo** | AI logo design — 10 types (symbol, wordmark, combined, stacked, emblem, lettermark, mascot, abstract, negative space, motion-ready) with 18 styles and font options |
| **Art** | AI art generation/style transfer — 26 art styles (Van Gogh, Monet, Picasso, watercolor, oil painting, ink wash, etc.) with 3 modes (transform, create, reference) |
| **Model** | AI fashion model photo generation — gender, age, ethnicity, body type, pose, background, lighting, camera angle presets |
| **Outfit** | Virtual try-on — upload model photo + clothing items, AI composites the outfit with studio/outdoor/lifestyle backgrounds |
| **Influencer** | AI influencer photo — reference person + product images + 60+ background scenes (9 categories), mood, pose, lighting presets |
| **Board** | Poster template generation |
| **Ad Pack** | Full ad package — product detail pages + promotional images, 8 styles, 8 color schemes |
| **Ad Video** | AI ad video generation (Veo model) — 8 video styles (cinematic, action, emotional, minimal, luxury, trendy, tutorial, before/after), shorts/reels support |
| **Cartoon** | AI webtoon/manga/comic — 26 art styles (webtoon, manga, anime, chibi, pixel, Ghibli, Disney, Marvel, etc.) |
| **Interior** | AI interior design — 6 room types, 7+ styles (modern, Nordic, minimal, industrial, natural, luxury, Japanese) |
| **Pet** | AI pet photo generation + pet outfit try-on — dogs (10+ breeds) and cats |
| **Rebuild** | Existing product page AI enhancement — layout, typography, color, quality improvement |
| **360 Rotate** | 360° product rotation view — 4/8-direction generation from single product image, optional rotation video via Veo |
| **Smart Store** | Naver Smart Store branding package — store logo, product thumbnails, detail pages, banners for 19 categories |
| **Web Builder** | AI website generator — 14 site types (landing, portfolio, blog, shop, etc.), generates complete single-page HTML with preview |

### Setup

1. Get a **Google Gemini API key** from [Google AI Studio](https://aistudio.google.com/)
2. Go to Settings > **Agent** > NanoBanana > paste your Gemini API key
3. Open the NanoBanana panel from the sidebar

### Features

- **Prompt-based generation** — Describe what you want in natural language
- **Reference image upload** — Upload product/model/person photos for AI compositing
- **Aspect ratio selection** — 1:1, 16:9, 9:16, 4:3, 3:4
- **Multi-draft generation** — Generate multiple variations at once
- **Image crop editor** — Click any generated image to crop/resize/rotate/flip with aspect ratio presets
- **Auto-save** — Generated images are saved to `{project}/docs/img/`
- **AI models** — Gemini 3 Pro (high quality), Gemini 3.1 Flash (fast), Imagen 4 (photo-realistic), Veo 3.1 (video)

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
**멀티프로젝트 + 멀티터미널 — 프로젝트와 터미널을 자유자재로 넘나드는 문어 터미널!**\
**초등학생도 쓸 수 있을 만큼 쉬운 코딩 터미널!**

---

## Octo Terminal이 뭐예요?

**Octo Terminal**은 문어(Octopus)처럼 여러 개의 팔(터미널)을 가진 프로그램이에요!

**최대 장점: 멀티프로젝트 + 멀티터미널.** 수십 개의 프로젝트를 동시에 열고, 각 프로젝트마다 독립적인 터미널, 테마, 설정을 가질 수 있어요. 탭으로 프로젝트를 순식간에 전환하고, 터미널을 가로/세로/그리드로 분할해서 한 패널에서 Claude, 다른 패널에서 개발 서버, 또 다른 패널에서 Codex를 동시에 실행할 수 있어요. 문어처럼 멀티태스킹하면서 프로젝트와 터미널을 마구 넘나들 수 있습니다.

터미널 + 에디터 + 노트 + AI + 이미지 스튜디오를 한 화면에서 쓸 수 있어요. 파워포인트, 워드, 엑셀, PDF, EPUB 등 다양한 문서 뷰어와 칸반 보드, NanoBanana AI 이미지 생성도 지원해요.

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
| 다국어 | 8개 언어: 영어, 한국어, 일본어, 중국어, 프랑스어, 독일어, 이탈리아어, 스페인어 |

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
| NanoBanana | AI 디자인 스튜디오 — 16개 서비스: 배너, 로고, 개발 이미지, 아트, 패션 모델, 착장, 인플루언서, 광고 팩, 광고 영상, 카툰, 인테리어, 펫, 360도 회전, 스마트스토어, 웹 빌더 (Gemini/Imagen/Veo) |

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

## Skills 시스템

Skills는 재사용 가능한 AI 프롬프트 템플릿입니다. 원클릭으로 실행할 수 있고, 모델 선택과 파라미터 입력을 지원합니다.

### Skills 설정 방법

1. **Skills 패널 열기** — 사이드바에서 "Skills" 탭 클릭 또는 명령 팔레트 사용
2. **스킬 탐색** — 내장 스킬을 둘러보거나 외부 소스에서 가져오기
3. **스킬 구성**:
   - **이름**: 스킬 표시 이름
   - **프롬프트 템플릿**: `{{변수}}` 자리표시자가 포함된 AI 프롬프트
   - **모델**: 사용할 AI 모델 선택 (Claude, Codex, Ollama 등)
   - **파라미터**: 템플릿 변수를 채울 입력 필드 정의
4. **스킬 실행** — "실행" 클릭 또는 단축키 사용. 결과는 터미널이나 갤러리 뷰에 표시.

### Skills Hub

커뮤니티 스킬을 Skills Hub에서 탐색하고 설치할 수 있습니다:

1. 설정 > **Skills Hub** 이동
2. 추천 스킬 팩 탐색 또는 GitHub 저장소 URL 붙여넣기
3. "설치" 클릭으로 로컬 컬렉션에 추가

### 커스텀 스킬 파일

스킬은 프로젝트의 `.octo/skills/` 디렉토리에 JSON으로 저장됩니다:

```json
{
  "name": "README 생성",
  "prompt": "{{project_name}} 프로젝트의 README.md를 생성해줘. 주요 기능: {{features}}",
  "model": "claude",
  "parameters": [
    { "name": "project_name", "label": "프로젝트 이름", "type": "text" },
    { "name": "features", "label": "주요 기능", "type": "textarea" }
  ]
}
```

### 외부 스킬 팩

GitHub 저장소에서 스킬 팩을 가져올 수 있습니다:
- **JSON 매니페스트** — JSON 스킬 매니페스트 파일 URL
- **GitHub 저장소** — 저장소 URL을 붙여넣으면 `SKILL.md` 파일을 자동 크롤링
- **로컬 매니페스트** — 사전 번들된 유명 스킬 팩 (2.3MB+ 큐레이션된 스킬)

---

## NanoBanana — AI 이미지 & 디자인 스튜디오

NanoBanana는 Google Gemini (Gemini 3 Pro, Gemini 3.1 Flash, Imagen 4, Veo 3.1) 기반의 내장 AI 디자인 스튜디오입니다. 마케팅 배너, 로고, 앱 아이콘, 패션 모델 사진, AI 아트, 광고 패키지, 웹페이지 등을 터미널을 벗어나지 않고 생성할 수 있습니다.

### 서비스 목록 (총 16개)

| 서비스 | 설명 |
| --- | --- |
| **개발 이미지** | 앱 아이콘, 파비콘, OG 이미지, 스플래시, 스토어 스크린샷, 배지, 에러/성공/로딩 일러스트 — 20종 이상 |
| **배너** | AI 마케팅 배너 생성 — 분위기, 색상, 배경 타입, 로고 업로드, 멀티 시안 지원 |
| **로고** | AI 로고 디자인 — 10가지 타입 (심볼, 워드마크, 콤비네이션, 스택형, 엠블럼, 레터마크, 마스코트, 추상, 네거티브 스페이스, 모션 레디) + 18가지 스타일 |
| **아트** | AI 아트 생성/스타일 변환 — 26가지 화풍 (반 고흐, 모네, 피카소, 수채화, 유화, 수묵화 등) + 3가지 모드 (변환, 생성, 참조) |
| **모델** | AI 패션 모델 사진 — 성별, 나이대, 인종, 체형, 포즈, 배경, 조명, 카메라 앵글 프리셋 |
| **착장** | 가상 착장 — 모델 사진 + 의류 아이템 업로드, AI가 스튜디오/야외/라이프스타일 배경에 합성 |
| **인플루언서** | AI 인플루언서 사진 — 참조 인물 + 제품 이미지 + 60개 이상 배경 씬 (9개 카테고리), 분위기, 포즈, 조명 프리셋 |
| **포스터** | 포스터 템플릿 생성 |
| **광고 팩** | 풀 광고 패키지 — 상품 상세페이지 + 홍보 이미지, 8가지 스타일, 8가지 컬러 스킴 |
| **광고 영상** | AI 광고 영상 (Veo 모델) — 8가지 영상 스타일 (시네마틱, 액션, 감성, 미니멀, 럭셔리, 트렌디, 튜토리얼, 비포/애프터), 쇼츠/릴스 지원 |
| **카툰** | AI 웹툰/만화 — 26가지 아트 스타일 (웹툰, 망가, 애니메, 치비, 픽셀, 지브리, 디즈니, 마블 등) |
| **인테리어** | AI 인테리어 디자인 — 6가지 방 타입, 7가지 이상 스타일 (모던, 북유럽, 미니멀, 인더스트리얼, 내추럴, 럭셔리, 재패니즈) |
| **펫** | AI 반려동물 사진 + 펫 착장 합성 — 강아지 (10종 이상 견종) & 고양이 |
| **리빌드** | 기존 상품 상세페이지 AI 개선 — 레이아웃, 타이포그래피, 색감, 화질 향상 |
| **360 회전** | 360도 상품 회전 뷰 — 단일 상품 사진에서 4/8방향 생성, Veo로 회전 영상 옵션 |
| **스마트스토어** | 네이버 스마트스토어 브랜딩 패키지 — 스토어 로고, 상품 썸네일, 상세페이지, 배너 (19개 카테고리) |
| **웹 빌더** | AI 웹사이트 생성기 — 14가지 사이트 타입 (랜딩, 포트폴리오, 블로그, 쇼핑몰 등), 완전한 단일 HTML 페이지 생성 + 미리보기 |

### 설정 방법

1. [Google AI Studio](https://aistudio.google.com/)에서 **Google Gemini API 키** 발급
2. 설정 > **Agent** > NanoBanana > Gemini API 키 붙여넣기
3. 사이드바에서 NanoBanana 패널 열기

### 기능

- **프롬프트 기반 생성** — 원하는 이미지를 자연어로 설명
- **참조 이미지 업로드** — 제품/모델/인물 사진 업로드 후 AI 합성
- **비율 선택** — 1:1, 16:9, 9:16, 4:3, 3:4
- **멀티 시안 생성** — 한 번에 여러 변형 생성
- **이미지 크롭 에디터** — 생성된 이미지 클릭으로 크롭/리사이즈/회전/뒤집기 + 비율 프리셋
- **자동 저장** — 생성된 이미지는 `{프로젝트}/docs/img/`에 저장
- **AI 모델** — Gemini 3 Pro (고품질), Gemini 3.1 Flash (빠른), Imagen 4 (사실적), Veo 3.1 (영상)

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
