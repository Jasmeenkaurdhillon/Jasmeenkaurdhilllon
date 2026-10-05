# Setup checklist

Open this folder in VS Code (File → Open Folder → `mobile-app-study-kit`). VS Code will offer to install the recommended extensions from `.vscode/extensions.json`; click **Install All**.

## 1. Programs (outside VS Code)

| Done | Program | Why | When |
| --- | --- | --- | --- |
| [ ] | VS Code | Your editor | Now |
| [ ] | Node.js (LTS) from nodejs.org | Runs the app (`npm install`, start, build) | Now |
| [ ] | Python 3 from python.org (Windows: tick **"Add python.exe to PATH"**) | Runs the Jupyter notebooks | Now |
| [ ] | Google Chrome | Shows the app; DevTools previews it at phone size | Now |
| [ ] | Android Studio | Building the Android app (chapter 7) | At the end, optional |
| [ ] | Xcode (Mac only) | Building the iOS app (chapter 7) | At the end, optional |

Free accounts:

- [ ] Google account (for Firebase)
- [ ] Figma account (for the UX exercises)

## 2. VS Code extensions

Open Extensions with `Ctrl+Shift+X` (Mac: `Cmd+Shift+X`) and search for each name.

| Done | Priority | Extension (publisher) | Needed for |
| --- | --- | --- | --- |
| [ ] | ⭐ Must | Python (Microsoft) | Running the notebooks |
| [ ] | ⭐ Must | Jupyter (Microsoft) | Opening `.ipynb` files |
| [ ] | ⭐ Must | Ionic (Ionic) | Ionic commands and component help |
| [ ] | ⭐ Must | Angular Language Service (Angular) | Autocomplete and error checking in HTML/TypeScript |
| [ ] | Recommended | Angular Snippets (John Papa) | Shortcuts for common Angular code |
| [ ] | Recommended | Auto Rename Tag (Jun Han) | Renames the matching closing HTML tag |
| [ ] | Recommended | Prettier – Code formatter | Tidy formatting |
| [ ] | Recommended | Markdown All in One (Yu Zhang) | Study notes: preview and checkboxes |
| [ ] | Recommended | Draw.io Integration (Henning Dieterichs) | Opening the BPMN `.drawio` file |
| [ ] | Optional | Code Spell Checker | Typos |
| [ ] | Optional | GitHub Pull Requests | Saving your work on GitHub |

## 3. Quick check

Open the VS Code terminal (`` Ctrl+` ``) and run:

```bash
node -v
python --version    # Mac: python3 --version
```

- [ ] Both print a version number
- [ ] `01_Mobile_App_Development.ipynb`: Step 0 and Step 1 show ✅

### If something fails

- **`node` / `python` is not recognized**: close and reopen VS Code (or restart the computer) so it picks up the new PATH. On Windows, if Python still isn't found, run the installer again, choose **Modify**, and tick "Add Python to environment variables".
- **Notebook asks for a kernel**: click **Select Kernel** (top right) → **Python Environments** → pick Python 3.
- **Notebook asks to install `ipykernel`**: click **Install**.
