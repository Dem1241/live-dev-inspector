# 🕵️‍♂️ live-dev-inspector

> Inspect your local development environment for secrets, misconfigurations, and open ports — before you ship.

![Status](https://img.shields.io/badge/status-WIP-orange)
![License](https://img.shields.io/github/license/Dem1241/live-dev-inspector)
![Issues](https://img.shields.io/github/issues/Dem1241/live-dev-inspector)
![Stars](https://img.shields.io/github/stars/Dem1241/live-dev-inspector?style=social)

---

## 🚀 What is it?

`live-dev-inspector` is a CLI + (optional) web dashboard tool that helps developers **audit their local dev environment** for potential risks like:

- 🔐 Exposed secrets in `.env` files  
- 🌐 Weak CORS configurations  
- 🎧 Open ports and running services  
- 🧠 Forgotten debug settings or dangerous environment variables  
- 📄 Auto-generated security report (Markdown/HTML)

---

## ✨ Planned Features

| Feature                    | Description                                       | Status       |
|---------------------------|---------------------------------------------------|--------------|
| `.env` secret scanner     | Detect common secrets or sensitive keys           | 🔜 In progress |
| Port checker              | Find open ports & listening services              | 🔜 Planned     |
| CORS misconfig detector   | Warn if CORS headers allow `*`                    | 🔜 Planned     |
| Process analyzer          | Show active local dev processes (e.g., Node)      | 🔜 Planned     |
| Report generation         | Save results as Markdown or HTML                  | 🔜 Planned     |
| Optional web dashboard    | Live view of findings via Express/WebSocket UI    | 🔜 Planned     |

---

## 📦 Installation (Coming Soon)

```bash
npx live-dev-inspector
````

Or clone manually:

```bash
git clone https://github.com/yourusername/live-dev-inspector.git
cd live-dev-inspector
npm install
npm run inspect
```

---

## 🧪 Usage

```bash
npx live-dev-inspector
```

> Run the tool in the root of your dev project.
> Output will be printed in your terminal, and optionally saved to a report file.

---

## 📅 Roadmap

* [ ] Build `.env` scanner ✅ **(Next Step)**
* [ ] Add open port detection
* [ ] CORS inspection module
* [ ] Web dashboard (Express + Socket.io)
* [ ] Report builder (Markdown + HTML)
* [ ] CLI polish with flags and interactive prompts
* [ ] Plugin system (future)
* [ ] VS Code extension? 🤔

---

## 🤝 Contributing

Not open for PRs yet, but feel free to:

* ⭐ Star the project
* 📥 Open issues
* 🧠 Suggest ideas
* 🧪 Follow progress!

---

## 📝 License

[MIT](LICENSE)

---

## 📣 Stay Updated

Follow me on [GitHub](https://github.com/yourusername) or [LinkedIn](https://www.linkedin.com/in/your-link/) for updates!



---

### ✅ Instructions

1. Replace all instances of `yourusername` with your actual GitHub username.
2. Swap the LinkedIn URL at the bottom if you want.
3. Add it as your `README.md` file.
4. Commit and push.

---

