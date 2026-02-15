<p align="center">
  <img src="images/app_icon.png" alt="Octo Terminal" width="128" height="128">
</p>

<h1 align="center">Octo Terminal</h1>

<p align="center">
  <strong>AI와 함께하는 코딩 터미널!</strong><br>
  <strong>A coding terminal so easy, even elementary kids can use it!</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/version-0.1.1-blue" alt="Version">
  <img src="https://img.shields.io/badge/Built%20with-Rust-orange?logo=rust" alt="Rust">
  <img src="https://img.shields.io/badge/Framework-Tauri%202-blue?logo=tauri" alt="Tauri">
  <img src="https://img.shields.io/badge/Frontend-React%2019-61dafb?logo=react" alt="React">
</p>

---

## 목차

1. [Octo Terminal이 뭐예요?](#octo-terminal이-뭐예요)
2. [주요 기능](#주요-기능)
   - [AI 친구들](#1--ai-친구들)
   - [여러 화면 분할](#2-️-여러-화면-분할)
   - [3단계 뷰 모드](#3--3단계-뷰-모드)
   - [파일 탐색기](#4--파일-탐색기)
   - [코드 에디터](#5-️-코드-에디터)
   - [마크다운 노트](#6--마크다운-노트)
   - [AI 문서 생성](#7--ai-문서-생성)
   - [스케줄러](#8-️-스케줄러)
   - [노트 템플릿](#9--노트-템플릿)
   - [테마와 폰트](#10--테마와-폰트)
   - [키보드 단축키](#11-️-키보드-단축키)
   - [볼트 (비밀 저장소)](#12--볼트)
   - [히스토리](#13--히스토리)
   - [음성 입력 (Whisper)](#14--음성-입력-whisper)
   - [텔레그램 연동](#15--텔레그램-연동)
   - [스크린샷 / 이미지 붙여넣기](#16--스크린샷--이미지-붙여넣기)
   - [Octo Commands](#17--octo-commands)
   - [명령 팔레트](#18--명령-팔레트)
   - [CJK 입력 (한/중/일)](#19-️-cjk-입력)
3. [설치 방법](#설치-방법)
4. [사용 방법](#사용-방법)
5. [문제 해결](#문제-해결)

---

## Octo Terminal이 뭐예요?

### 한국어

**Octo Terminal**은 문어(Octopus)처럼 여러 개의 팔(터미널)을 가진 프로그램이에요!

컴퓨터로 코딩할 때 쓰는 도구인데, 터미널 + 에디터 + 노트 + AI를 한 화면에서 쓸 수 있어요.

### English

**Octo Terminal** is like an octopus with many arms (terminals)!

It's an all-in-one coding tool: terminal + editor + notes + AI in a single window.

### 왜 만들었나요?

| 문제 | 해결 |
|------|------|
| 터미널이 너무 어려워요 | 예쁜 색상과 쉬운 버튼 |
| 여러 창을 왔다갔다 해야 해요 | 한 화면에 모두 보여요 |
| AI를 쓰기 어려워요 | 한 클릭으로 AI 실행! |
| 메모를 따로 관리해야 해요 | 내장 마크다운 노트 |
| 반복 작업이 귀찮아요 | 스케줄러로 자동 실행 |

---

## 주요 기능

### 1. AI 친구들

클로드(Claude), 코덱스(Codex), 오픈코드(OpenCode), 키미(Kimi), 올라마(Ollama) 같은 AI를 터미널에서 바로 실행할 수 있어요.

**사용 방법:**
1. 터미널 헤더의 "+" 버튼 클릭
2. Claude, Codex, OpenCode, Kimi, Ollama 중 선택
3. AI에게 코딩을 시키거나 질문하기

**AI 모드:**

| 모드 | 설명 |
|------|------|
| 안전 모드 | 매번 확인 후 진행 |
| 자동 모드 | 작은 변경은 자동 |
| 전체 자동 | 모든 것을 자동으로 |

**설정 경로:** 설정 > Agent 탭에서 각 AI별 모드와 옵션 설정

---

### 2. 여러 화면 분할

8가지 화면 분할 모드를 지원합니다.

| 모드 | 설명 |
|------|------|
| **탭** | 탭으로 전환 (기본) |
| **가로 분할** | 좌우로 나란히 |
| **세로 분할** | 상하로 나란히 |
| **트리** | tmux 스타일 자유 분할 |
| **타일 (좌/우)** | 메인 + 사이드 스택 |
| **타일 (상/하)** | 메인 + 하단 스택 |
| **그리드** | 2x2 격자 |
| **믹스** | 모든 프로젝트 터미널을 하나의 그리드에 표시 |

**트리 모드 분할:**
- `Cmd + D`: 오른쪽으로 분할
- `Cmd + Shift + D`: 아래로 분할
- 분할선을 드래그하여 크기 조절

**믹스 모드:**
- 모든 프로젝트의 터미널을 한 화면에 표시
- 각 터미널에 프로젝트 아이콘과 이름 표시
- 행/열 리사이즈 핸들로 크기 조절

---

### 3. 3단계 뷰 모드

상단 왼쪽의 토글 버튼으로 화면 구성을 3단계로 전환합니다.

| 모드 | 보이는 영역 | 아이콘 |
|------|------------|--------|
| **에디터** | 사이드바 + 에디터만 | 세로 분할 사각형 |
| **전체** (기본) | 사이드바 + 에디터 + 터미널 | 사각형 안에 L자 분할 |
| **터미널** | 터미널만 (전체화면) | 프롬프트(>_) |

- 클릭할 때마다 에디터 → 전체 → 터미널 순으로 순환
- `Cmd + Shift + F` 단축키로도 전환 가능
- 전체 모드에서는 에디터와 터미널 사이의 분할선을 드래그하여 비율 조절

---

### 4. 파일 탐색기

왼쪽 사이드바에서 프로젝트 파일을 탐색합니다.

**기능:**
- 파일/폴더 트리 뷰 (펼치기/접기)
- 파일 클릭으로 에디터에서 열기
- 이미지 파일 미리보기 (PNG, JPG, SVG 등)
- 새 파일/폴더 생성 (인라인 입력)
- 이름 변경 (`F2`)
- 복사/잘라내기/붙여넣기 (`Cmd+C / Cmd+X / Cmd+V`)
- 멀티 선택 (Cmd+클릭, Shift+클릭)
- 드래그 앤 드롭으로 파일 이동
- 오른쪽 클릭 컨텍스트 메뉴
- 시스템 파일 탐색기에서 열기

**사이드바 탭:**
- **파일**: 프로젝트 파일 트리
- **메모**: 마크다운 노트 시스템

---

### 5. 코드 에디터

파일을 클릭하면 상단 에디터 영역에서 열립니다.

**일반 코드 파일 (Monaco Editor):**
- 구문 강조 (Syntax Highlighting)
- 자동 완성
- 미니맵
- 줄바꿈 토글
- Vim 모드 지원
- Emmet 지원

**마크다운 파일 (CodeMirror 6):**
- 마크다운 구문 강조
- 줄 번호, 코드 접기
- AI 내용 추가 기능 (아래 참조)

**에디터 설정:** 설정 > 에디터 탭
- 글자 크기 (8~32px)
- 줄바꿈 ON/OFF
- 미니맵 ON/OFF
- 공백 표시
- Vim 모드
- Emmet

---

### 6. 마크다운 노트

사이드바 "메모" 탭에서 마크다운 노트를 관리합니다.

**구성:**
- **전체 노트**: `~/Documents/octo-notes/` 디렉토리의 글로벌 노트
- **프로젝트 문서**: 각 프로젝트의 `docs/` 폴더와 루트 `.md` 파일

**기능:**
- 새 노트/폴더 생성 (인라인 입력)
- AI로 노트 자동 생성 (주제 입력하면 마크다운 생성)
- 노트 검색 (`Cmd + P`)
- 데일리 노트 (`Cmd + Alt + D`)
- 프로젝트 간 노트 복사/이동
- 멀티 선택 및 일괄 삭제
- 드래그 앤 드롭 파일 이동

**AI 노트 생성:**
1. 메모 탭에서 폴더를 선택 (또는 아무것도 선택 안 하면 루트)
2. Sparkles 버튼 클릭
3. 주제 입력 (예: "React hooks 정리")
4. AI가 마크다운 문서를 자동으로 생성하여 파일로 저장
5. 하위 폴더에서도 동일하게 동작

**AI 프로바이더:** 설정 > 노트 탭에서 선택
- Ollama (로컬)
- Claude
- Codex
- Kimi

---

### 7. AI 문서 생성

마크다운 에디터 안에서 AI를 호출하여 현재 문서에 내용을 추가합니다.

**사용 방법:**
1. `.md` 파일을 에디터에서 열기
2. 에디터 툴바의 Sparkles 버튼 클릭
3. 상단에서 드롭다운 입력 바가 나타남
4. 추가할 내용을 설명 (예: "테스트 계획 섹션 추가")
5. Enter 또는 전송 버튼 클릭
6. AI가 생성한 내용이 커서 위치에 삽입
7. 생성 완료 후 입력 바 자동 닫힘

**특징:**
- 현재 문서 내용을 컨텍스트로 활용
- 커서 위치에 정확히 삽입 (CodeMirror EditorView 연동)
- 에러 발생 시 입력 바 아래에 에러 메시지 표시
- Esc 키로 닫기

---

### 8. 스케줄러

CLI 명령어를 정해진 간격으로 자동 실행합니다.

**사용 방법:**
1. 상단 바의 시계 아이콘 클릭
2. 프로젝트 선택
3. 작업 이름과 CLI 명령어 입력
4. 반복 주기 설정 (분 단위, 1~10080분)
5. "추가" 버튼 클릭
6. 토글 스위치로 활성화/비활성화

**기능:**
- 프로젝트별 CLI 명령어 스케줄링
- 분 단위 반복 간격 (60분 이상이면 "X시간 Y분 마다" 표시)
- 마지막 실행 시간 및 출력 결과 확인
- 작업별 활성화/비활성화 토글
- 실행 결과 최근 500자 저장
- 활성 작업 수 배지 표시

**예시:**
```
명령어: git pull && npm run build
반복: 60분 마다
프로젝트: 내 웹사이트
```

---

### 9. 노트 템플릿

새 노트 생성 시 사용할 마크다운 템플릿을 관리합니다.

**템플릿 설정:** 설정 > 노트 탭 > 노트 템플릿 섹션

**기능:**
- 템플릿 생성/수정/삭제
- 템플릿 이름과 마크다운 내용 설정
- `{{title}}` 플레이스홀더 지원 (파일 이름으로 자동 치환)
- 노트 툴바에서 템플릿 선택 드롭다운

**사용 방법:**
1. 설정 > 노트 탭에서 템플릿 추가
2. 노트 사이드바 툴바에서 템플릿 선택
3. 새 파일 생성 시 선택된 템플릿 내용이 자동 적용

**예시 템플릿:**
```markdown
# {{title}}

## 요약

## 상세 내용

## 참고 자료

---
작성일:
```

---

### 10. 테마와 폰트

프로젝트마다 다른 색상 테마와 폰트를 설정할 수 있습니다.

**다크 테마 (45개):** Ocean, Forest, Sunset, Dracula, Nord, Tokyo Night 등
**라이트 테마 (30개):** Light, Light Warm, Paper 등

**폰트:** Fira Code, JetBrains Mono, SF Mono, Consolas, D2Coding 등

**변경 방법:**
1. 설정 > 테마 탭
2. 원하는 색상 클릭
3. 폰트 선택
4. 프로젝트별로 개별 설정 가능

---

### 11. 키보드 단축키

> Mac은 `Cmd`, Windows/Linux는 `Ctrl`을 사용합니다.

**터미널:**

| 단축키 | 설명 |
|--------|------|
| `Cmd + T` | 새 터미널 |
| `Cmd + W` | 현재 터미널 닫기 |
| `Cmd + Shift + W` | 모든 터미널 닫기 |
| `Cmd + ]` / `Cmd + [` | 다음/이전 터미널 |
| `Cmd + 1~9` | 터미널 탭 이동 |
| `Cmd + =` / `Cmd + -` | 글자 크기 조절 |

**화면 분할:**

| 단축키 | 설명 |
|--------|------|
| `Cmd + D` | 오른쪽 분할 |
| `Cmd + Shift + D` | 아래 분할 |
| `Cmd + Alt + 방향키` | 패널 포커스 이동 |

**프로젝트:**

| 단축키 | 설명 |
|--------|------|
| `Cmd + N` | 새 프로젝트 |
| `Cmd + Shift + ]` / `[` | 다음/이전 프로젝트 |
| `Ctrl + 1~9` (Mac) / `Alt + 1~9` (Win) | 프로젝트 이동 |

**뷰 모드:**

| 단축키 | 설명 |
|--------|------|
| `Cmd + Shift + F` | 뷰 모드 전환 (에디터 → 전체 → 터미널 → 에디터) |

**노트 & 파일:**

| 단축키 | 설명 |
|--------|------|
| `Cmd + P` | 노트 검색 |
| `Cmd + Shift + N` | 새 노트 |
| `Cmd + Alt + D` | 데일리 노트 |
| `Cmd + Shift + E` | 파일 탐색기 토글 |
| `Cmd + S` | 저장 |
| `F2` | 이름 바꾸기 |
| `Cmd + C / X / V` | 파일 복사/잘라내기/붙여넣기 |
| `Delete` | 파일 삭제 |

**기타:**

| 단축키 | 설명 |
|--------|------|
| `Cmd + Shift + P` | 명령 팔레트 |
| `Cmd + ,` | 설정 |

**프리셋:** 설정 > 단축키 탭
- Octo (기본)
- VSCode 스타일
- IntelliJ 스타일

---

### 12. 볼트

비밀번호, API 키, 자주 쓰는 코드 조각을 안전하게 보관합니다.

**사용 방법:**
1. 상단 바의 자물쇠 아이콘 클릭
2. 비밀번호를 설정하여 잠금
3. "+" 버튼으로 항목 추가 (이름 + 내용)
4. 복사 버튼으로 클립보드에 복사

---

### 13. 히스토리

터미널에서 실행한 명령어 기록을 검색하고 재실행합니다.

**사용 방법:**
1. 상단 바의 히스토리 아이콘 클릭
2. 검색창에서 이전 명령어 검색
3. 클릭하여 터미널에 입력

---

### 14. 음성 입력 (Whisper)

OpenAI Whisper API를 사용하여 음성을 텍스트로 변환합니다.

**설정:** 설정 > Agent 탭 > Whisper 섹션
1. OpenAI API 키 입력
2. 언어 선택 (한국어, 영어, 일본어 등)
3. 마이크 선택
4. 모델 선택 (whisper-1, gpt-4o-transcribe)

**사용:** 오른쪽 Alt 키를 누른 상태에서 말하기 > 키를 떼면 텍스트로 변환

**옵션:**
- 자동 전송 (변환 후 Enter)
- 무음 감지 필터
- 최소 녹음 시간 설정

---

### 15. 텔레그램 연동

텔레그램으로 터미널을 원격 모니터링하고 명령어를 보냅니다.

**설정:**
1. 텔레그램 @BotFather에서 봇 생성
2. 봇 토큰을 설정 > Agent > Telegram에 입력
3. 각 터미널 탭에서 텔레그램 아이콘 클릭하여 Chat ID 연결

**기능:**
- 명령어 미러링: 터미널 입력을 텔레그램으로 전송
- 출력 미러링: 터미널 결과를 텔레그램으로 전송
- 원격 제어: 텔레그램에서 터미널로 명령어 전송
- 터미널별 개별 Chat ID 설정

---

### 16. 스크린샷 / 이미지 붙여넣기

**스크린샷:**
- 각 터미널의 카메라 아이콘 클릭
- 전체 화면 캡처 후 파일로 저장
- 파일 경로가 클립보드에 복사됨

**이미지 붙여넣기:**
- 이미지를 클립보드에 복사 (`Cmd+C`)
- 터미널에 `Cmd+V`로 붙여넣기
- 자동으로 파일 저장 후 경로 입력

---

### 17. Octo Commands

`:`로 시작하는 Octo Terminal 전용 명령어입니다.

```bash
# 도움말
:help

# HTTP 요청
:http GET https://api.example.com

# Ollama
:ollama models              # 모델 목록
:ollama chat llama3 "안녕"  # 대화
:ollama pull llama3         # 모델 다운로드

# Gemini
:gemini models
:gemini chat "안녕하세요"

# MiniMax
:minimax models
:minimax chat "안녕"
```

---

### 18. 명령 팔레트

`Cmd + Shift + P`로 빠르게 명령을 검색하고 실행합니다.

**기능:**
- 명령어 퍼지 검색
- 최근 사용 명령어 우선 표시
- 키보드로 빠른 탐색 (방향키 + Enter)
- 등록된 모든 명령과 단축키 확인

---

### 19. CJK 입력

한국어, 중국어, 일본어 입력을 네이티브 IME로 지원합니다.

**방식:**
- OS 기본 IME를 그대로 사용
- 조합 중인 글자는 커서 위치에 오버레이로 표시
- 조합 완료 시에만 PTY로 전송 (깜빡임 없음)
- macOS, Windows, Linux 동일 방식

**설정:** 설정 > Terminal > Input mode
- **Direct**: 바로 입력
- **IME**: 입력 도우미 (CJK 사용 시 권장)

---

## 설치 방법

### Mac

**준비물:**
- macOS 10.15 이상
- 100MB 이상의 여유 공간

**Step 1: 내 맥 칩 확인**

사과 아이콘 > "이 Mac에 관하여"에서 칩 정보 확인:

| 칩 | 파일 |
|-----|------|
| M1/M2/M3/M4 | `aarch64.dmg` |
| Intel | `x64.dmg` |

**Step 2: 다운로드**

[GitHub Releases](https://github.com/johunsang/octo-terminal-releases/releases) 에서 최신 버전 다운로드

**Step 3: 설치**

1. `.dmg` 파일 더블클릭
2. Octo Terminal 아이콘을 Applications 폴더로 드래그

**Step 4: 보안 설정**

앱이 "손상되었다"는 경고가 나타나면 터미널에서 아래 명령어를 실행:

```bash
xattr -cr "/Applications/Octo Terminal.app"
```

> Apple 개발자 인증서 없이 배포된 앱은 macOS Gatekeeper에 의해 차단됩니다.

**Step 5: 실행**

Launchpad 또는 Spotlight(`Cmd + Space` > "octo")에서 실행

---

### Windows

**준비물:**
- Windows 10 또는 11 (64비트)
- 100MB 이상의 여유 공간

**Step 1: 다운로드**

[GitHub Releases](https://github.com/johunsang/octo-terminal-releases/releases) 에서 `.msi` 파일 다운로드

**Step 2: 설치**

1. `.msi` 파일 더블클릭
2. SmartScreen 경고 시: "추가 정보" > "실행" 클릭
3. 설치 마법사를 따라 진행
4. 완료 후 자동 실행

**Step 3: 실행**

시작 메뉴에서 "Octo Terminal" 검색하여 실행

---

### Linux

**준비물:**
- Ubuntu 22.04+ 또는 호환 배포판 (x86_64)
- WebKit2GTK 4.0, GTK3, libayatana-appindicator3

**Ubuntu/Debian (.deb):**

```bash
# 다운로드 후 설치
sudo dpkg -i octo-terminal_*.deb

# 의존성이 빠져있으면 자동 설치
sudo apt-get install -f
```

**AppImage (모든 배포판):**

```bash
# 실행 권한 부여
chmod +x Octo.Terminal_*.AppImage

# 실행
./Octo.Terminal_*.AppImage
```

[GitHub Releases](https://github.com/johunsang/octo-terminal-releases/releases) 에서 `.deb` 또는 `.AppImage` 파일 다운로드

---

## 사용 방법

### 화면 구성

```
+--------------------------------------------------+
| [뷰] [프로젝트1] [프로젝트2] [+]  [메모][AI][설정] |  <- 프로젝트 탭 바
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

- **[뷰]**: 3단계 뷰 모드 토글 (에디터 / 전체 / 터미널)

### 기본 워크플로우

1. **프로젝트 열기**: "+" 버튼으로 작업 폴더 선택
2. **파일 탐색**: 왼쪽 사이드바에서 파일 클릭
3. **코드 편집**: 상단 에디터에서 수정, `Cmd+S` 저장
4. **터미널 사용**: 하단 터미널에서 명령어 실행
5. **AI 활용**: Claude/Codex/Kimi/Ollama 터미널로 AI 코딩
6. **노트 작성**: 사이드바 "메모" 탭에서 마크다운 노트 관리

### 뷰 모드 전환

왼쪽 상단 토글 버튼 또는 `Cmd + Shift + F`:

- **에디터 모드**: 코드 편집에 집중할 때 (터미널 숨김)
- **전체 모드** (기본): 에디터 + 터미널 동시 사용
- **터미널 모드**: 터미널 작업에 집중할 때 (에디터/사이드바 숨김)

---

## 문제 해결

### FAQ

**Q: "파일이 손상되었다"고 떠요 (Mac)**
```bash
xattr -cr "/Applications/Octo Terminal.app"
```

**Q: 한글이 안 쳐져요**
```
설정 > Terminal > Input mode를 "IME"로 변경
```

**Q: 단축키가 안 먹어요**
```
설정 > Shortcuts에서 프리셋 확인
Mac: Cmd, Windows: Ctrl
```

**Q: AI가 응답이 없어요**
```
1. 인터넷 연결 확인
2. API 키 확인 (Claude/Kimi는 API 키 필요)
3. Ollama 사용 시 로컬 서버 실행 확인 (ollama serve)
```

**Q: 스케줄러가 에러가 나요**
```
설정에서 스케줄러 작업의 프로젝트가 올바르게 선택되었는지 확인
CLI 명령어가 해당 프로젝트 경로에서 실행 가능한지 확인
```

**Q: 노트 AI 생성이 안 돼요**
```
설정 > 노트 탭에서 AI 프로바이더 확인
Ollama: 로컬 서버 실행 필요 (ollama serve)
Claude/Kimi: API 키 설정 필요
```

**Q: Linux에서 실행이 안 돼요**
```bash
# 필요한 의존성 설치
sudo apt-get install -y libwebkit2gtk-4.0-dev libssl-dev libgtk-3-dev libayatana-appindicator3-dev librsvg2-dev

# AppImage의 경우 실행 권한 확인
chmod +x Octo.Terminal_*.AppImage
```

### 연락처

- 버그 신고: [GitHub Issues](https://github.com/johunsang/octo-terminal-releases/issues)
- 문의: johunsang@gmail.com

---

## 기술 스택

| 레이어 | 기술 |
|--------|------|
| 백엔드 | Tauri v2, Rust, portable-pty, tokio |
| 프론트엔드 | React 19, TypeScript, xterm.js |
| 코드 에디터 | Monaco Editor (코드), CodeMirror 6 (마크다운) |
| 터미널 | xterm.js + WebGL 렌더러 |
| 번들러 | Vite 7 |
| 빌드/배포 | GitHub Actions (macOS, Windows, Linux) |

---

## 용어 설명

| 용어 | 설명 |
|------|------|
| 터미널 | 명령어를 입력하는 검은 화면 |
| 프로젝트 | 작업 폴더 하나 |
| 테마 | 색깔 조합 (Ocean, Forest 등) |
| PTY | Pseudo Terminal, 가상 터미널 |
| 스케줄러 | 정해진 시간마다 명령어 자동 실행 |
| 볼트 | 비밀번호로 보호되는 저장소 |
| 명령 팔레트 | 키보드로 명령을 검색하는 창 |
| 뷰 모드 | 에디터/전체/터미널 3단계 화면 전환 |

---

<p align="center">
  <strong>Octo Terminal</strong><br>
  <em>작지만 강한, 당신의 코딩 친구</em><br>
  <em>Small but mighty, your coding friend</em><br><br>
  Made with love by <a href="https://github.com/johunsang">johunsang</a>
</p>
