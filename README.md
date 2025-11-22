# node-pty-prebuilt-win64-v20

Prebuilt binaries of [node-pty](https://github.com/microsoft/node-pty) compiled for **Node.js v20.x (LTS)** on **Windows x64**.  
This repository provides ready-to-use builds so you can install `node-pty` without needing native build tools (`node-gyp`, Python, Visual Studio Build Tools, etc.).

---

## Installation

Install directly from GitHub:

```bash
npm install apricore/node-pty-prebuilt-win64-v20
```

Or add it to your `package.json`:

```json
"dependencies": {
  "node-pty": "apricore/node-pty-prebuilt-win64-v20"
}
```

---

## Why use this?

- No need for `node-gyp` or Visual Studio Build Tools
- Works out-of-the-box with Node.js **v20.x (LTS)**
- Simplifies setup in Windows environments (CI/CD, Docker, developer machines)

---

## Contents

- Precompiled `node-pty` binaries for **Windows x64**
- Target Node.js version: **Node.js v20.x (LTS)**

---

## Notes

- This repo is **not the official node-pty** project.  
- For source code and upstream updates, see [microsoft/node-pty](https://github.com/microsoft/node-pty).
- Only Windows x64 is supported here. For other platforms, build from source or use official releases.

---

## License

Same license as [node-pty](https://github.com/microsoft/node-pty) (MIT).
