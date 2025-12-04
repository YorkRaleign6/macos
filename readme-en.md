
# macOS - EN
---------

[中文文档](https://github.com/YorkRaleign6/macos/blob/main/readme.md) | [English README](https://github.com/YorkRaleign6/macos/blob/main/readme-en.md)

--------

### 📖 Introduction
Welcome to my macOS application repository. This repository primarily serves as an index for various macOS applications I have personally collected and shared.

> **⚠️ Disclaimer:**
> All resources in this repository are collected from the internet and are for **educational and research purposes only**.
> If you find the software useful, please **purchase the official version** to support the developers.
> If there is any infringing content, please contact me for removal.

### 📥 How to Download
1. Find the software you need in the **[App Index](#-app-index)** below.
2. Click the **[Download]** link to jump to the **Releases** page.
3. Download the corresponding `.dmg` or `.zip` file from the **Assets** section.

### 🛠 Troubleshooting (Must Read: Fix "App is Damaged")
MacOS has strict restrictions on unsigned applications. If you see the message **"App is damaged and can't be opened"** or **"Cannot verify developer"** when opening software, please follow these steps:

#### 1. Enable "Anywhere"
Open **Terminal**, enter the following command, and press Enter (you will need to type your login password):
```bash
sudo spctl --master-disable
````

Once done, go to **System Settings** -\> **Privacy & Security**, and ensure "Allow apps downloaded from" is selected as **"Anywhere"**.

#### 2\. Bypass Notarization (Fix Damaged/Crash Issues)

If the app still won't open, this is the most effective fix. Run the following command in Terminal:

```bash
sudo xattr -rd com.apple.quarantine /Applications/YourAppName.app
```

*Tip: You can type ` sudo xattr -rd com.apple.quarantine  ` (note the space at the end) first, then drag the application from Finder into the Terminal window to automatically fill in the path.*

#### 3\. Ad-hoc Signing (Backup Solution)

If the above methods fail, try manually signing the app:

```bash
sudo codesign --force --deep --sign - /Applications/YourAppName.app
```

### 📂 App Index

| Application Name | Version | Description | Download Link |
| :--- | :--- | :--- | :--- |
| **Typora** | v1.12.4 | A minimalist Markdown editor providing a seamless "What You See Is What You Get" writing experience. | [down](https://github.com/YorkRaleign6/macos/blob/main/typora/1.12.4/Typora_1.12.4.dmg) |
| **iShot\_Pro** | v2.6.5 | Excellent screen capture, recording, OCR text recognition, and annotation tool for Mac. | [down](https://github.com/YorkRaleign6/macos/blob/main/iShot_Pro/2.6.5/iShot%20Pro_2.6.5.dmg) |
| **Xmind** | v26.01.07145 | Full-featured mind mapping and brainstorming software to inspire creativity. | [down](https://github.com/YorkRaleign6/macos/blob/main/Xmind/26.01/Xmind_26.01.07145.dmg) |
| **ScreenFlow** | v10.5.1 | Professional screen recording and video editing software for creating high-quality demo videos. | [down](https://github.com/YorkRaleign6/macos/blob/main/ScreenFlow/10.5.1/ScreenFlow_10.5.1.dmg) |
| **Navicat\_Premium** | v17.3.5 | Powerful multi-connection database development tool supporting MySQL, Redis, PostgreSQL, and more. | [down](https://github.com/YorkRaleign6/macos/blob/main/Navicat_Premium/17.3.5/Navicat_Premium_17.3.5.dmg) |

```
```
