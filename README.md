# Offline Document Editor & E-Signature Tool

A lightweight, purely local web-based document editor. It functions similarly to Microsoft Word, allowing you to edit text, upload PDFs/DOCX files, insert signatures, resize images, and format documents—all without requiring a database or a backend server.

## 🚀 Features

*   **100% Offline & Local**: No database, no PHP, no server required. Everything runs directly in your web browser.
*   **Local Storage Memory**: Documents you create are automatically saved into your browser's local cache. If you close the tab and return later, your documents will still be in the sidebar.
*   **Rich Text Editor**: Full ribbon UI with options for fonts, sizing, bold, italic, highlights, text alignment, lists, tables, etc.
*   **E-Signatures**: Click on a signature block to digitally draw or upload a signature directly onto the document.
*   **Drag & Drop Objects**: Freely drag, drop, resize, and overlay images, text boxes, and signature blocks anywhere on the page.
*   **File Import**: Upload `.docx` and `.pdf` files. The app converts them into editable HTML layers.
*   **Data Export/Import (Offline Sharing)**: Since there is no server to send "Share Links," you can click **Export Data (.json)** to download your document file. Send this `.json` file to another person (via email, USB, etc.), and they can use the **Load Data (.json)** button to open it and add their own signature.
*   **PDF & DOCX Export**: Download the finished document as a standard `.pdf` or `.docx` file.

## 📥 Installation & Usage

1. **Download**: Download the `index.html` file to your computer.
2. **Open**: Double-click the `index.html` file. It will automatically open in your default web browser (Chrome, Edge, Firefox, or Safari are recommended).
3. **No Setup Required**: Because there is no database, you do not need XAMPP, WAMP, or MySQL. 

## 💡 How to Use

1. **Start a Document**: Open the app and begin typing on the A4 canvas, or select a template from the left setup menu.
2. **Importing existing files**: Click **Upload PDF/Word** on the left menu to overlay text and signatures on top of your existing files.
3. **Signing**: Click any "Click to Sign" area to open the signature pad. Draw your signature and click Confirm.
4. **Saving**: Click **Save Locally** on the left menu. Your document will now appear under the "Local Documents" list.
5. **Collaborating**: To have someone else sign the document on a *different* computer:
    * Click **Options & Export** -> **Export Data (.json)**.
    * Send the downloaded file to the other person.
    * They open `index.html` on their machine, click **Load Data (.json)**, select the file, sign it, and export it back to you or as a final PDF!
6. **Focus Mode**: Click the 'Expand Arrows' icon on the top right to hide the menus. Click the floating document name on the top left to restore the menus.

## ⚠️ Important Limitations
* **Storage Limit**: Because this relies on Browser LocalStorage, you are limited to around 5MB to 10MB of saved document data per browser. If you reach this limit, you can delete old documents from the "Local Documents" sidebar list.
* **Cache Clearing**: If you clear your browser's cache/history completely, your "Local Documents" will be deleted. Always export important documents as PDFs or `.json` backups!