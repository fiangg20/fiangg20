<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:381E72,50:6750A4,100:D0BCFF&height=240&section=header&text=Bases&fontSize=64&fontColor=EADDFF&fontAlignY=36&desc=Reaching%20the%20base%20before%20the%20stack%20overflows.&descSize=20&descColor=EADDFF&descAlignY=58&animation=fadeIn" alt="Bases banner" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=B69DF8&center=true&vCenter=true&width=720&lines=Luau+scripter+%26+developer+tools+builder;Building+Superbase%3A+let+AI+debug+your+live+Roblox+game;Connecting+AI+assistants+to+Roblox+through+MCP;Reaching+the+base+before+the+stack+overflows)](https://github.com/fiangg20/superbase)

<br/>

![Followers](https://img.shields.io/github/followers/fiangg20?style=for-the-badge&logo=github&color=6750A4&labelColor=1C1B1F)
![Repos](https://img.shields.io/badge/Repositories-12-D0BCFF?style=for-the-badge&logo=gitbook&logoColor=1C1B1F&labelColor=1C1B1F)
![Location](https://img.shields.io/badge/Indonesia-%F0%9F%87%AE%F0%9F%87%A9-4F378B?style=for-the-badge&labelColor=1C1B1F)

</div>

---

## 👋 About Me

```lua
--!strict
local Bases = {
	location = "Indonesia 🇮🇩",
	language = "Luau",
	building = "Superbase, an MCP server that lets AI debug live Roblox games",
	focus    = { "Luau", "MCP servers", "developer tools", "debugging" },
	motto    = "Reaching the base before the stack overflows.",
}

return Bases
```

---

## 🛠️ Tech Stack

<div align="center">

![Luau](https://img.shields.io/badge/Luau-00A2FF?style=for-the-badge&logo=lua&logoColor=white)
![Roblox](https://img.shields.io/badge/Roblox-000000?style=for-the-badge&logo=roblox&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![MCP](https://img.shields.io/badge/MCP-6750A4?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

</div>

---

## ✨ Featured Project

<div align="center">

<a href="https://github.com/fiangg20/superbase">
  <img src="https://raw.githubusercontent.com/fiangg20/superbase/main/assets/icon.png" width="110" alt="Superbase icon" />
</a>

### [Superbase](https://github.com/fiangg20/superbase)

**Let an AI assistant debug your live Roblox game.**

<a href="https://github.com/fiangg20/superbase">
  <img src="https://github-readme-stats.vercel.app/api/pin/?username=fiangg20&repo=superbase&bg_color=1C1B1F&title_color=D0BCFF&text_color=E6E1E5&icon_color=D0BCFF&border_color=49454F" alt="superbase" />
</a>

</div>

Superbase is a local [Model Context Protocol](https://modelcontextprotocol.io) server that connects AI assistants to a running Roblox session. The AI can read the console and script errors, inspect the instance tree, read scripts and run Lua, and it always knows whether Roblox is actually connected.

- ⚡ **Zero configuration**: no token, no account, no copy and paste
- 🔌 **Connection aware**: every tool result starts with a live status line
- 🧰 **11 tools**: logs, errors, inspection, scripts, properties and code execution
- 🤝 **Works with any MCP client**: Claude Desktop, Claude Code, Cursor, Windsurf, VS Code, Codex CLI and more
- 🔒 **Local only**: everything listens on `127.0.0.1`

```mermaid
flowchart LR
    AI["AI client<br/>(Claude, Cursor, ...)"] -- "stdio (MCP)" --> MCP["MCP server"]
    MCP -- "HTTP, 127.0.0.1" --> Bridge["Bridge"]
    Client["In-game client<br/>(executor)"] -- "WebSocket, 127.0.0.1" --> Bridge
```

```bash
git clone https://github.com/fiangg20/superbase.git
cd superbase
npm install
npm start
```

> Built for debugging your own games. Only connect AI clients you trust.

---

## 📊 GitHub Stats

<div align="center">

<img height="180" src="https://github-readme-stats.vercel.app/api?username=fiangg20&show_icons=true&hide_border=true&count_private=true&bg_color=1C1B1F&title_color=D0BCFF&text_color=E6E1E5&icon_color=D0BCFF" alt="GitHub stats" />
<img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=fiangg20&layout=compact&hide_border=true&bg_color=1C1B1F&title_color=D0BCFF&text_color=E6E1E5" alt="Top languages" />

<br/>

<img src="https://streak-stats.demolab.com?user=fiangg20&hide_border=true&background=1C1B1F&ring=D0BCFF&fire=EADDFF&currStreakNum=E6E1E5&sideNums=E6E1E5&currStreakLabel=D0BCFF&sideLabels=CCC2DC&dates=938F99" alt="Streak stats" />

</div>

---

## 📫 Let's Connect

<div align="center">

[![YouTube](https://img.shields.io/badge/YouTube-%40fian__gg-FF0000?style=for-the-badge&logo=youtube&logoColor=white)](https://youtube.com/@fian_gg)
[![Email](https://img.shields.io/badge/Email-fiangaming005%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:fiangaming005@gmail.com)

<br/>

*⭐ If Superbase saves you a debugging session, a star on the repo goes a long way!*

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:381E72,50:6750A4,100:D0BCFF&height=120&section=footer" alt="footer" />

</div>
