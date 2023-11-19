# Udemy extension

### For Chrome: <a name="chrome"></a>

1. Run:
    - Dev: `pnpm dev` or `npm run dev`
    - Prod: `pnpm build` or `npm run build`
2. Open in browser - `chrome://extensions`
3. Check - `Developer mode`
4. Find and Click - `Load unpacked extension`
5. Select - `dist` folder

### For Firefox: <a name="firefox"></a>

1. Run:
    - Dev: `pnpm dev:firefox` or `npm run dev:firefox`
    - Prod: `pnpm build:firefox` or `npm run build:firefox`
2. Open in browser - `about:debugging#/runtime/this-firefox`
3. Find and Click - `Load Temporary Add-on...`
4. Select - `manifest.json` from `dist` folder

### <i>Remember in firefox you add plugin in temporary mode, that's mean it's disappear after close browser, you must do it again, on next launch.</i>

## Pages <a name="pages"></a>

### New Tab <a name="newtab"></a>

[Override Chrome pages](https://developer.chrome.com/docs/extensions/mv3/override/)<br/>`chrome_url_overrides.newtab` in manifest.json

### Popup <a name="popup"></a>

[Browser actions](https://developer.chrome.com/docs/extensions/reference/browserAction/)<br/>`action.default_pupup` in manifest.json

### Devtools <a name="devtools"></a>

[Devtools](https://developer.chrome.com/docs/extensions/mv3/devtools/#creating)<br/>`devtools_page` in manifest.json

### Background <a name="background"></a>

[Background](https://developer.chrome.com/docs/extensions/mv3/background_pages/)<br/>`background.service_worker` in manifest.json

### ContentScript <a name="contentscript"></a>

[Content Script](https://developer.chrome.com/docs/extensions/mv3/content_scripts/)<br/>`content_scripts[0]` in manifest.json

### Options <a name="options"></a>

[Options](https://developer.chrome.com/docs/extensions/mv3/options/)<br/>`options_page` in manifest.json

### SidePanel (Chrome 144+) <a name="sidepanel"></a>

[SidePanel](https://developer.chrome.com/docs/extensions/reference/sidePanel/)<br/>`side_panel.default_path` in manifest.json


## Screenshots <a name="screenshots"></a>

### New Tab <a name="newtab"></a>

<img width="800" alt="newtab" src="https://github.com/Jonghakseo/chrome-extension-boilerplate-react-vite/assets/53500778/3e782e41-b605-4956-90e2-20cc48252820">

### Popup <a name="popup"></a>

| Black | White |
|--------|--------|
| <img width="300" alt="black" src="https://github.com/Jonghakseo/chrome-extension-boilerplate-react-vite/assets/53500778/35423617-e6f5-4f65-adb3-03f068236648"> | <img width="300" alt="white" src="https://github.com/Jonghakseo/chrome-extension-boilerplate-react-vite/assets/53500778/99886d92-b6f0-4e41-b70e-5afc6d2f7eab"> |

### Devtools <a name="devtools"></a>

<img width="450" alt="devtools" src="https://github.com/Jonghakseo/chrome-extension-boilerplate-react-vite/assets/53500778/467d719d-a7db-4f77-8504-cd5ce7567793">

## Examples <a name="examples"></a>

- https://github.com/Jonghakseo/drag-gpt-extension
- https://github.com/Jonghakseo/pr-commit-noti
- https://github.com/ariburaco/chatgpt-file-uploader-extended

## Documents <a name="documents"></a>

- [Vite Plugin](https://vitejs.dev/guide/api-plugin.html)
- [ChromeExtension](https://developer.chrome.com/docs/extensions/mv3/)
- [Rollup](https://rollupjs.org/guide/en/)
- [Rollup-plugin-chrome-extension](https://www.extend-chrome.dev/rollup-plugin)
