# dimmer-ext

MV3 extension playground: page reading-time estimator

Built for my own use; public in case it helps someone.

## How to use

```bash
# click the toolbar icon to see today's reading time
```

## What it does

- Popup shows today's total focus time
- Per-tab time persisted to chrome.storage
- Manifest V3, service worker based
- No remote calls, everything stays local

## Install

```bash
# no build step needed
# chrome://extensions -> load unpacked -> select this folder
```

## Project structure

```text
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── bug_report.md
│   ├── dependabot.yml
│   └── pull_request_template.md
├── docs/
│   ├── configuration.md
│   ├── development.md
│   ├── roadmap.md
│   └── usage.md
├── examples/
│   └── quickstart.md
├── scripts/
│   └── dev.sh
├── src/
│   └── config.js
├── .editorconfig
├── .gitignore
├── CHANGELOG.md
├── CONTRIBUTING.md
├── SECURITY.md
├── background.js
├── manifest.json
├── popup.html
└── popup.js
```

## Development

```bash
npm install
npm test
```

## 说明

个人练习项目, 谨慎用于生产环境。

## License

MIT licensed, see LICENSE.
