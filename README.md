# 🧹 Task 7: Identify and Remove Suspicious Browser Extensions

## 📌 Objective
To identify, evaluate, and remove potentially harmful or unnecessary browser extensions, improving browser security and learning about extension-based attack vectors.

## 🛠️ Tools Used
- Google Chrome (via `chrome://extensions/`)
- Mozilla Firefox (via `about:addons`)

---

## 🔍 Steps Performed

### 1. **Opened Extension Manager**
- Used browser-specific pages to list all installed extensions.

### 2. **Reviewed Installed Extensions**
- Analyzed each extension’s purpose, publisher, permissions, and web reviews.
- Verified whether each extension was intentionally installed.

### 3. **Identified Suspicious or Unused Extensions**
Extensions flagged for removal if they:
- Requested unnecessary or sensitive permissions (like clipboard/file access).
- Came from unknown or unverified publishers.
- Had poor or no reviews.

### 4. **Removed Unnecessary Extensions**
- Used the browser's built-in options to safely uninstall the identified extensions.

### 5. **Restarted the Browser**
- Restarted to apply changes and validate performance/security improvements.

---

## 🔐 Removed Extensions

| Extension Name             | Reason for Removal                                                |
|----------------------------|-------------------------------------------------------------------|
| Hola VPN                  | Logs user data and sells bandwidth to third parties               |
| SuperZoom                | Contained hidden tracking code and removed from Chrome Store       |
| DataSaver Pro            | Excessive permissions and access to all website data               |
| Flash Video Downloader   | Silent data collection and external script injection               |

---

## 📖 Key Learnings

- Browser extensions can become security risks if not properly managed.
- Reviewing extension permissions and publisher credibility is essential.
- Unused or suspicious extensions should be regularly removed.
- Browser security hygiene is a key part of personal cybersecurity.

---

## ❓ Interview Preparation Q&A

1. **How can browser extensions pose security risks?**  
   They can access sensitive data, inject scripts, or track user behavior.

2. **What permissions should raise suspicion?**  
   Clipboard, file access, tab monitoring, and unrestricted content script permissions.

3. **How to safely install browser extensions?**  
   Only install from official stores, verify the developer, and read user reviews.

4. **What is extension sandboxing?**  
   A security method to limit an extension’s access to system or browser internals.

5. **Can extensions steal passwords?**  
   Yes, if they have access to form data or credential fields.

6. **How to update extensions securely?**  
   Enable auto-updates via browser settings or manually update from trusted sources.

7. **Difference between extensions and plugins?**  
   Extensions are browser-based enhancements. Plugins are external software modules.

8. **How to report malicious extensions?**  
   Use “Report Abuse” in Chrome Web Store or Firefox Add-ons platform.


---

✅ **Completed by:** *Vimal kumar r*  
"""
