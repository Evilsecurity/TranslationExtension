# TranslationExtension
Here’s a simplified guide for installing your translation extension on Google Chrome without the code.

### Steps to Install:

#### 1. **Prepare Your Files:**
   Ensure your project folder contains the following files:
   - `popup.html`: The user interface of your extension.
   - `popup.js`: The script file that handles the translation logic.
   - `manifest.json`: A configuration file that defines the extension's name, version, permissions, and more.
   - Icons (16x16, 48x48, and 128x128 pixels).

#### 2. **Organize Your Folder:**
   Place all the files in one folder. The structure should look like this:

   ```
   my-translator-extension/
   ├── icon16.png
   ├── icon48.png
   ├── icon128.png
   ├── popup.html
   ├── popup.js
   └── manifest.json
   ```

#### 3. **Enable Developer Mode:**

1. Open **Google Chrome**.
2. In the address bar, type `chrome://extensions/` and press **Enter**.
3. Toggle **Developer Mode** on (it’s at the top-right of the Extensions page).

#### 4. **Install the Extension:**

1. Click **Load unpacked**.
2. Select the folder where your extension files are stored (the folder containing `manifest.json`).
3. The extension will now be installed, and its icon will appear in the browser toolbar.

#### 5. **Test the Extension:**

1. Click the extension icon in the toolbar to open it.
2. Enter text into the input field, select the language, and click the button to translate.
3. Test the **Copy** and **Paste** buttons to ensure they work as expected.

#### 6. **Update the Extension:**

   If you make changes to the extension (e.g., in `popup.js` or `popup.html`), you can update it:
   1. Return to `chrome://extensions/`.
   2. Click **Update** to reload the extension with the latest changes.

#### 7. **Troubleshooting:**

   If you encounter issues:
   - Chrome will display error messages on the Extensions page. Read them to identify the issue (often related to `manifest.json` or file paths).
   - Ensure your icons are correctly sized (16x16, 48x48, 128x128 pixels) and located in the right folder.

By following these steps, you’ll successfully install and test your Chrome extension! Let me know if you need any further help.
