<img width="1652" height="1016" alt="image" src="https://github.com/user-attachments/assets/5be09788-16a7-4d4e-9d6a-47edb04da2ec" />

<img width="1652" height="1016" alt="image" src="https://github.com/user-attachments/assets/ca23eae6-94eb-401d-b0b3-1b4ad7f6c868" />

<img width="1652" height="962" alt="image" src="https://github.com/user-attachments/assets/6c39a3b6-4060-43ca-86c4-6df0bb480dca" />

<img width="1652" height="962" alt="image" src="https://github.com/user-attachments/assets/b466d385-93db-4896-b683-391f24121d4c" />

<img width="1652" height="962" alt="image" src="https://github.com/user-attachments/assets/d8f54712-f35a-4ff1-8c6a-f15244f3b5a8" />

<img width="1652" height="962" alt="image" src="https://github.com/user-attachments/assets/ea12381a-d1c7-4e42-b4b4-4ebe5350fccb" />


# Ai Browser Privy (Ver. 1.0.0)

[Korean](#korean) | [English](#english)

---

<a name="korean"></a>
## 🇰🇷 Korean

> **"Gemini in Chrome에서 영감을 받았으며, 무엇보다 로컬 보안과 개인 정보를 최우선으로 설계되었습니다."**

### 🕵️ Ai Browser Privy: 당신과 AI만을 위한 비밀 공간

**Ai Browser Privy**는 Electron 기반 로컬 AI 브라우저입니다. 로컬 LLM(예: Ollama, LM Studio, vLLM)과 연동하여, 사용자의 화면과 파일을 안전하게 분석하고 질문에 답변합니다. 클라우드 대신 내 컴퓨터 안에서만 작동하도록 설계되어 개인 정보 보호에 집중합니다.

### 🔧 주요 기능
- **로컬 AI 프로바이더 자동 감지**: Ollama, LM Studio, vLLM 중 실행 중인 서버를 자동으로 감지합니다.
- **웹 브라우저 내장**: Electron BrowserView를 이용한 브라우징과 URL 이동, 뒤로/앞으로, 새로고침을 지원합니다.
- **화면 공유**: 전체 화면, 창, 부분 화면 등의 화면 공유로 AI가 현재 보이는 화면을 분석할 수 있습니다.
- **웹캠 / 연속성 카메라**: 실시간 카메라 입력을 통해 AI에게 실제 물체나 상황을 보여줄 수 있습니다.
- **첨부 파일 분석**: PDF, Word(.docx), Excel(.xlsx), PowerPoint(.pptx), 텍스트(.txt), 마크다운(.md) 파일을 지원합니다.
- **자동·수동 캡처**: AI에게 전달할 화면을 자동으로 캡처하거나 수동으로 제어할 수 있습니다.
- **웹 검색 확장**: 원하는 경우 웹 검색을 함께 활용하여 최신 정보와 화면 분석을 결합합니다.
- **수학/마크다운 렌더링**: KaTeX와 marked.js 등으로 복잡한 수식과 문서 서식을 깔끔하게 표현합니다.
- **다운로드 관리**: 브라우저 내 다운로드 진행 상태 표시 및 다운로드 폴더 열기 기능 제공.
- **다국어 인터페이스**: 한국어와 영어를 모두 지원합니다.

### 📁 지원 문서 형식
- PDF
- Microsoft Word(.docx)
- Microsoft Excel(.xlsx)
- Microsoft PowerPoint(.pptx)
- 텍스트(.txt)
- 마크다운(.md)

### 🛡️ 보안 및 개인 정보
- 모델 요청과 화면 분석은 가능한 한 로컬 환경에서 처리됩니다.
- 외부 클라우드 서버 대신 사용자 컴퓨터 내부에 설치된 LLM과 통신합니다.
- 내부 서버는 macOS에서 Electron 앱과 함께 실행되며, 로컬 네트워크 통신만 사용합니다.

### 💻 시스템 요구 사항
- **macOS (권장)**: Intel, Apple Silicon(M1/M2/M3) 지원
- **Windows / Linux**: 빌드 설정에 따라 NSIS/ AppImage 설치 파일 가능


### 🧩 사용 예시
- 화면 공유를 시작한 뒤, 원하는 웹 페이지나 데스크톱 화면을 열고 AI에게 질문하세요.
- 파일 첨부 버튼을 사용하여 PDF, Word, Excel, PowerPoint, 텍스트, 마크다운 파일을 전송할 수 있습니다.
- 웹캠 버튼을 눌러 실시간 카메라 화면을 AI에게 보여주면, 사물 인식이나 상황 설명에 활용할 수 있습니다.
- 설정에서 자동 캡처 및 웹 검색을 켜면, 화면 분석과 외부 정보가 함께 제공됩니다.

### 🖼️ 스크린샷
아래는 앱 사용 화면 예시입니다. 실제 릴리스 문서 작성 시, 다음과 같은 화면을 스크린샷으로 추가하면 좋습니다.
- 메인 브라우저 인터페이스와 AI 채팅 화면
- 화면 공유 및 부분 화면 캡처 선택 화면
- 웹캠 / 연속성 카메라 입력 화면
- 첨부 파일 분석 결과와 수학/마크다운 렌더링 화면
- 설정 화면과 프로바이더 선택 화면

---

<a name="english"></a>
## 🇺🇸 English

> **"Inspired by Gemini in Chrome, designed with local security and privacy as the top priorities."**

### 🕵️ Ai Browser Privy: A private AI workspace for you

**Ai Browser Privy** is an Electron-based local AI browser. It integrates with local LLM providers such as Ollama, LM Studio, and vLLM to securely analyze your screen and files, then answer your questions. It is built to keep data inside your machine rather than sending it to external cloud services.

### 🔧 Key Features
- **Local AI provider auto-detection**: Automatically detects running Ollama, LM Studio, or vLLM servers.
- **Built-in browser**: Includes URL navigation, back/forward, refresh, and page loading inside Electron.
- **Screen sharing**: Supports full screen, window, and partial screen sharing so AI can analyze your visible content.
- **Webcam / Continuity Camera**: Share live camera input with the AI to show physical objects or environments.
- **File attachment analysis**: Supports PDF, Word(.docx), Excel(.xlsx), PowerPoint(.pptx), text(.txt), and Markdown(.md).
- **Auto/manual capture**: Let the app capture screens automatically or on demand.
- **Web search support**: Optionally combine web search with screen analysis for fresher information.
- **Math & markdown rendering**: Uses KaTeX and marked.js to display rich content neatly.
- **Download management**: Tracks download progress and opens the download folder.
- **Multilingual UI**: Supports both Korean and English.

### 📁 Supported document formats
- PDF
- Microsoft Word(.docx)
- Microsoft Excel(.xlsx)
- Microsoft PowerPoint(.pptx)
- Text(.txt)
- Markdown(.md)

### 🛡️ Privacy & Security
- Requests and screen analysis are handled locally when possible.
- Communicates with an LLM instance installed on your own device rather than a cloud AI service.
- The internal server runs alongside the Electron app on your machine, using local network communication only.

### 💻 System requirements
- **macOS (recommended)**: Intel and Apple Silicon (M1/M2/M3)
- **Windows / Linux**: Supported via NSIS/AppImage build targets in configuration


### 🧩 Usage examples
- Start screen sharing, open the page or desktop content you want, and ask the AI a question.
- Use the attachment button to send PDF, Word, Excel, PowerPoint, text, or Markdown files.
- Use the webcam button to show live camera input to the AI for object recognition or scene descriptions.
- Enable auto capture and web search in settings to combine screen analysis with external information.

### 🖼️ Screenshots
Add screenshots for the following app views in release or documentation materials:
- Main browser interface with AI chat
- Screen sharing and partial screen selection
- Webcam / Continuity Camera preview
- Attached file analysis and math/markdown rendering
- Settings and provider selection screens


---
**Developer**: CREATOR Joseph (크리에이터 요셉)  creatorjoseph@kakao.com
**Created**: 2026.5.5
