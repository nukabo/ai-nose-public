# Privacy policy for AI Nose

**Effective Date:** June 2, 2026

## 1. Introduction
AI Nose ("the Extension") is a Chrome extension designed to help users identify structural and stylistic writing patterns within selected text. We take your privacy seriously and have built this extension from the ground up to operate entirely on your local machine.

## 2. Data Collection and Usage
**We do not collect, transmit, store, or share any of your personal data or text.** 

- **Local Processing Only:** When you highlight text and run the AI Nose extension, all text analysis is performed locally within your Chrome browser using JavaScript regular expressions. 
- **No Remote Servers:** The Extension does not send your selected text or browsing activity to any remote servers, APIs, or databases.
- **Local Storage:** The Extension uses Chrome's `chrome.storage.local` API exclusively to save your recent analysis history and user preferences locally on your device. We intentionally do not use `chrome.storage.sync`, meaning your data never touches Google's cloud sync infrastructure. When the extension is uninstalled, locally stored history and preferences are removed with the extension data.

## 3. Permissions Justification
To function properly, AI Nose requires the following Chrome permissions:
- **`contextMenus`**: Required to add the "Check AI smell" option to your right-click menu and safely receive selection text.
- **`sidePanel`**: Required to display the analysis results in the browser's side panel.
- **`storage`**: Required to save your analysis history and configuration preferences locally on your machine.

## 4. Third-Party Analytics
We do not use Google Analytics, tracking pixels, or any other third-party telemetry tools within the Extension. We have no way of knowing who you are, what pages you visit, or what text you analyze.

## 5. Changes to this Privacy Policy
If we make any material changes to how we handle user data in future versions of AI Nose, we will update this Privacy Policy and explicitly note the changes in the Chrome Web Store release notes.

## 6. Contact Us
If you have any questions or concerns regarding this Privacy Policy, please open an issue on our official GitHub repository.
