# gittoTrae
깃을 트레에 넣어보세요 just let git dive into Trae

# 🚀 Portable Codespace Connector

A lightweight, portable tool to automate SSH configuration for GitHub Codespaces.  
Connect your local IDE (VS Code, Trae, JetBrains) to your Codespace instantly, from anywhere.

> **Security Note:** This tool operates on a strict **'Check-and-Act'** basis. It uses the official GitHub CLI (`gh.exe`) to verify your session and configure local SSH files. **No credentials are sent to external servers.**

---

## 🛠️ How It Works
This tool simplifies the connection process into a single executable:
1.  **Auto-Detection:** Automatically locates `gh.exe` (embedded or local).
2.  **Authentication:** Checks your login status and initiates a secure browser login if needed.
3.  **Safety First:** Backs up your existing `.ssh/config` file before making changes.
4.  **Instant Setup:** Fetches your active Codespaces and generates the necessary SSH configuration.

## 📥 Download & Usage
1.  Download the latest `Hayes_Connector.exe` from the [Releases](#) page.
2.  Run the executable.
    * *Note: If Windows SmartScreen appears, click **'More info'** → **'Run anyway'**. This happens because the app is open-source and unsigned.*
3.  Follow the on-screen instructions to select your Codespace.
4.  Open your IDE (e.g., Trae, VS Code) and connect to the host!

## 🛡️ VirusTotal Scan
To ensure transparency, you can check the scan results of the executable here:
* [Link to VirusTotal Scan Result] *(Please upload your .exe to VirusTotal and paste the link here)*

---

## 🇰🇷 (Korean) 한국어 설명

**"다른 컴퓨터에서 코딩하려고 세팅하다가 시간 다 보내본 적 있나요?"**

저도 그랬습니다. PC방, 카페, 친구 집... 장소를 옮길 때마다 SSH 키 설정하고, Config 파일 수정하고, 경로 잡다가 진이 다 빠져서 정작 코딩은 시작도 못 했죠. 그래서 만들었습니다.

**이 툴은 USB 하나로 끝냅니다.**
더블 클릭 한 번이면, **낯선 컴퓨터가 1분 만에 내 작업실이 됩니다.**

### 3줄 요약
1.  실행하면 알아서 로그인 체크하고 GitHub랑 연결해 줍니다.
2.  혹시 모르니 기존 설정 파일은 안전하게 백업해 둡니다.
3.  **Trae**나 **VS Code** 켜고 바로 접속하면 끝!

> **참고:** 윈도우 보안 경고(파란 화면)가 뜨면 당황하지 말고 **'추가 정보' → '실행'**을 눌러주세요. 제가 돈이 없어서(...) 마이크로소프트 유료 인증서를 못 샀을 뿐, 코드는 100% 안전합니다. (소스 코드 까보셔도 됩니다!)

---

### 📜 License
This project is licensed under the MIT License - see the LICENSE file for details.

**Created by Hayes Han**
