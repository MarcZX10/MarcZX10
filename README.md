<!-- ═══════════════════════════ HEADER ═══════════════════════════ -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:1793D1,100:7aa2f7&height=200&section=header&text=Marc&fontSize=72&fontColor=ffffff&fontAlignY=36&desc=MarcZX10%20%C2%B7%20C%2B%2B%20%C2%B7%20Go%20%C2%B7%20TypeScript%20%C2%B7%20Linux&descAlignY=58&descSize=18&animation=fadeIn" alt="Marc" width="100%" />
</p>

---

## 👋 About me

```go
package main

type Dev struct {
	User    string
	Since   int
	Now     []string
	Stack   []string
	Desktop string
}

func main() {
	marc := Dev{
		User:    "MarcZX10", // formerly MarcZX100
		Since:   2019,
		Now:     []string{"AnyPS5", "MimOS", "MimOffice", "Manolo", "MapGarraf", "lmw"},
		Stack:   []string{"C++", "Go", "TypeScript", "JavaScript", "Python", "Lua"},
		Desktop: "MimOS (Arch + KDE Plasma)",
	}
	_ = marc
}
```

- 🎮 I contribute to **[AnyPS5](https://github.com/boykopovar/AnyPS5)**, a tool that ports PS5 executables to Linux and Windows without emulation.
- 🐧 I work on **[MimOS](https://mimoslinux.org)**, a desktop Linux distro based on Arch with KDE Plasma, made in Spain, and on **[MimOffice](https://github.com/MarcZX10/MimOffice)**, its office suite.
- 🚌 I like building tools for real-world problems, like **[MapGarraf](https://github.com/MarcZX10/MapGarraf)**, a community map for the Vilanova ↔ Tarragona bus.
- 🤖 I've been making things since 2019: Discord bots, tools for strategy games and the occasional crazy idea.

---

## 🔥 What I'm working on

<table>
<tr>
<td width="50%" valign="top">

### 🎮 AnyPS5
<a href="https://github.com/boykopovar/AnyPS5"><img src="https://github-readme-stats.vercel.app/api/pin/?username=boykopovar&repo=AnyPS5&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="AnyPS5" /></a>

A relinker that converts PS5 executables to the host system's native format, plus implementations of the system PRX libraries. **C++ · CMake · Vulkan/SPIR-V**.

My part: system libraries (`libkernel`, `libSceMouse`, AGC…), cross-platform fixes, tests and ASan builds.

</td>
<td width="50%" valign="top">

### 🐧 MimOS + MimOffice
<a href="https://github.com/MarcZX10/MimOffice"><img src="https://github-readme-stats.vercel.app/api/pin/?username=MarcZX10&repo=MimOffice&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="MimOffice" /></a>

**MimOS** is a desktop distro based on Arch with KDE Plasma. **MimOffice** is its office suite: a fork of **KDE Calligra** kept in sync with upstream, with Words, Sheets, Stage and Karbon.

My part: the rebrand with the MimOS theme, packages in 6 formats (Flatpak, .deb, .rpm, AppImage, Snap and tarball) and the CI that syncs with upstream.

<a href="https://mimoslinux.org"><img src="https://img.shields.io/badge/web-mimoslinux.org-1793D1?style=flat-square&logo=kde&logoColor=white" alt="mimoslinux.org" /></a>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚌 MapGarraf
<a href="https://github.com/MarcZX10/MapGarraf"><img src="https://github-readme-stats.vercel.app/api/pin/?username=MarcZX10&repo=MapGarraf&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="MapGarraf" /></a>

A community PWA for the Vilanova i la Geltrú ↔ Tarragona bus. Riders can choose to share their GPS, and the app estimates delays against the official timetable. It also draws *ghost buses* where each service should be.

**React · Vite · Leaflet · Express · Zod · SQLite · Docker**

</td>
<td width="50%" valign="top">

### 🦾 LinkedinMechaWarrior (`lmw`)
<a href="https://github.com/MarcZX10/LinkedinMechaWarrior"><img src="https://github-readme-stats.vercel.app/api/pin/?username=MarcZX10&repo=LinkedinMechaWarrior&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="LinkedinMechaWarrior" /></a>

A command-line client for your own LinkedIn account: profile, feed and publishing posts. It's a single static binary with no browser automation. It mimics Chromium's TLS/HTTP2 fingerprint (same JA4) and paces itself like a human.

**Go** · [📖 Docs](https://marczx10.github.io/LinkedinMechaWarrior/)

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🗺️ Manolo
<a href="https://nekokoneko.org/manolo"><img src="https://nekokoneko.org/banner.jpg" alt="Manolo" width="100%" /></a>

A Discord bot and website for Twin Harbor Interactive (formerly Bytro) strategy games: **Supremacy 1914**, **Call of War**, **Iron Order 1919** and **Conflict of Nations**. It renders game maps, makes videos of how matches unfold and tracks player and match stats. The bot and the site run together in a single Node.js process. I've been building it since 2023.

**Node.js · discord.js · Express · EJS · MongoDB · canvas · sharp · FFmpeg · Chart.js**

<a href="https://nekokoneko.org/manolo"><img src="https://img.shields.io/badge/web-nekokoneko.org%2Fmanolo-5865F2?style=flat-square&logo=discord&logoColor=white" alt="nekokoneko.org/manolo" /></a>
<img src="https://img.shields.io/badge/repo-private-30363d?style=flat-square&logo=github" alt="Private repo" />

</td>
</tr>
</table>

<details>
<summary><b>🗂️ More projects (and a few oldies)</b></summary>
<br />

| Project | What it is | Stack |
|---|---|---|
| [**cow-calc**](https://github.com/MarcZX10/cow-calc) | Battle calculator for *Call of War*: terrain, home defense, doctrines… | TypeScript · [web](https://cow-calc.vercel.app) |
| [**trash_classifier**](https://github.com/MarcZX10/trash_classifier) | In-browser waste classifier | HTML · JS |
| [**projecte-final-equip08**](https://github.com/MarcZX10/projecte-final-equip08-2) | Team final project | Node · EJS · [demo](https://projecte-final-equip08-2.vercel.app) |
| [**Pulposting**](https://github.com/MarcZX10/pulposting-publico) | My long-running Discord bot, 25+ versions since 2020 🐙 | discord.js |
| [**editorjsonpy**](https://github.com/MarcZX10/editorjsonpy) | JSON editor to practice Python | Python |
| [**mastermind**](https://github.com/MarcZX10/mastermind) | The classic Mastermind | Python |
| [**marczx100.github.io**](https://github.com/MarcZX10/marczx100.github.io) | My old personal website | HTML · CSS · JS |

</details>

---

## 🛠️ Stack

<p align="center">
  <b>Languages</b><br /><br />
  <img src="https://skillicons.dev/icons?i=cpp,c,go,ts,js,py,java,lua,bash&theme=dark" alt="Languages" />
</p>

<p align="center">
  <b>Web & backend</b><br /><br />
  <img src="https://skillicons.dev/icons?i=react,vite,nodejs,express,html,css,sqlite,mongodb,php&theme=dark" alt="Web" />
</p>

<p align="center">
  <b>Systems & tools</b><br /><br />
  <img src="https://skillicons.dev/icons?i=linux,arch,qt,cmake,docker,git,githubactions,vercel,vscode&theme=dark" alt="Tools" />
</p>

---

## 📊 Stats

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=MarcZX10&show_icons=true&include_all_commits=true&count_private=true&theme=tokyonight&hide_border=true&bg_color=0d1117&rank_icon=github" alt="MarcZX10's stats" />
  <img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MarcZX10&layout=compact&langs_count=8&theme=tokyonight&hide_border=true&bg_color=0d1117" alt="Top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=MarcZX10&theme=tokyonight&hide_border=true&background=0d1117" alt="Contribution streak" />
</p>

<p align="center">
  <a href="https://www.youtube.com/watch?v=plB0K0DROFs&ab_channel=MisterAce"><img src="https://trophy.ryglcloud.net/?username=MarcZX10&theme=tokyonight&no-frame=true&no-bg=true&margin-w=6&column=-1" alt="Trophies" /></a>
</p>

### 🏗️ Contributions (3D view)

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MarcZX10/MarcZX10/main/profile-3d-contrib/profile-night-green.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MarcZX10/MarcZX10/main/profile-3d-contrib/profile-green-animate.svg" />
    <img alt="3D contribution graph" src="https://raw.githubusercontent.com/MarcZX10/MarcZX10/main/profile-3d-contrib/profile-night-green.svg" />
  </picture>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/MarcZX10/MarcZX10/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/MarcZX10/MarcZX10/output/github-snake.svg" />
    <img alt="Snake eating my contributions" src="https://raw.githubusercontent.com/MarcZX10/MarcZX10/output/github-snake-dark.svg" />
  </picture>
</p>

---

<p align="center">
  <i>“Imagine not having a README.”</i>
</p>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:7aa2f7,50:1793D1,100:0d1117&height=120&section=footer" alt="" width="100%" />
