<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F5A0,50:00C6FF,100:7B2FFF&height=180&section=header&text=ShellScrap&fontSize=55&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Terminal-Style%20Local-First%20Notes&descAlignY=58&descSize=18"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=2800&pause=800&color=00F5A0&center=true&vCenter=true&width=700&lines=Capture+%E2%80%A2+Organize+%E2%80%A2+Search+%E2%80%A2+Export;Terminal+Experience+%E2%9A%A1+Local-First+%E2%9A%A1+Fast;Your+Notes.+Your+Browser.+Your+Data."/>

<br>

<a href="https://shellscrap.netlify.app/">
<img src="https://img.shields.io/badge/%F0%9F%9A%80%20LIVE%20PREVIEW-ShellScrap-00C6FF?style=for-the-badge&logo=netlify&logoColor=white"/>
</a>

<a href="https://github.com/MUdevelops/ShellScrap">
<img src="https://img.shields.io/badge/%F0%9F%92%BB%20SOURCE%20CODE-GitHub-181717?style=for-the-badge&logo=github"/>
</a>

<br><br>

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square\&logo=html5\&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square\&logo=css3\&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square\&logo=javascript\&logoColor=black)
![IndexedDB](https://img.shields.io/badge/IndexedDB-7B2FFF?style=flat-square)
![MIT](https://img.shields.io/badge/License-MIT-00C6FF?style=flat-square)

<br>

### 🖥️ Local-First • Terminal-Style • Zero Backend

</div>

---

## ⚡ About

**ShellScrap** is a lightweight browser-based notes manager with a retro terminal interface.

Create, organize, search, tag, edit, delete and export your notes — directly from the terminal.

```text
> new Build my AI project #AI #Development
> ls
> find AI
> tags
> export
```

---

## ✨ Features

|     | Feature               |                              |
| --- | --------------------- | ---------------------------- |
| 📝  | **Create & Edit**     | Manage notes quickly         |
| 🔎  | **Search**            | Find notes instantly         |
| 🏷️ | **Tags**              | Organize with `#tags`        |
| 💾  | **IndexedDB**         | Persistent browser storage   |
| 📦  | **JSON Export**       | Backup your notes            |
| ⌨️  | **Keyboard Controls** | Vim-inspired workflow        |
| 🖥️ | **Terminal UI**       | Retro CRT experience         |
| ⚡   | **No Backend**        | Runs directly in the browser |

---

## ⌨️ Commands

```text
new <text>          Create a note
ls                  Display all notes
ls #tag             Filter by tag
show <id>           Display a note
find <query>        Search notes
edit <id> <text>    Edit a note
tag <id> +tag       Add a tag
tag <id> -tag       Remove a tag
rm <id>             Delete a note
tags                Show all tags
export              Export notes as JSON
clear               Clear terminal
help                Show commands
```

---

## 🎮 Keyboard Navigation

```text
i       → INSERT mode
Esc     → NORMAL mode
j / k   → Move down / up
gg      → Jump to top
G       → Jump to bottom
Enter   → Open selected note
dd      → Delete selected note
/       → Search
```

---

## 💾 Local-First Architecture

```text
              ┌───────────────┐
              │  ShellScrap   │
              │  Terminal UI  │
              └───────┬───────┘
                      ↓
              ┌───────────────┐
              │  JavaScript   │
              └───────┬───────┘
                      ↓
              ┌───────────────┐
              │   IndexedDB   │
              └───────┬───────┘
                      ↓
               Browser Storage
```

No server-side database is required.

---

# 📸 Screenshots

<div align="center">

### 🖥️ Main Interface

<img src="./Screenshots/main%20interface.png" width="90%" alt="ShellScrap Main Interface"/>

<br><br>

### 📋 Display Notes

<table>
<tr>
<td width="50%" align="center">

<img src="./Screenshots/Display%20all%20notes.png" width="100%" alt="Display All Notes"/>

**Display All Notes**

</td>

<td width="50%" align="center">

<img src="./Screenshots/Display%20one%20by%20one.png" width="100%" alt="Display One by One"/>

**Display One by One**

</td>
</tr>
</table>

### 💾 Saved Notes

<table>
<tr>
<td width="50%" align="center">

<img src="./Screenshots/Saved%203%20Notes.png" width="100%" alt="Saved 3 Notes"/>

**Saved Notes**

</td>

<td width="50%" align="center">

<img src="./Screenshots/after%20clear%20command.png" width="100%" alt="After Clear Command"/>

**Clear Command**

</td>
</tr>
</table>

### 🔎 Search & Tags

<table>
<tr>
<td width="50%" align="center">

<img src="./Screenshots/Use%20find%20command.png" width="100%" alt="Find Command"/>

**Find Command**

</td>

<td width="50%" align="center">

<img src="./Screenshots/tags%20command.png" width="100%" alt="Tags Command"/>

**Tags Command**

</td>
</tr>

<tr>
<td width="50%" align="center">

<img src="./Screenshots/tag%20and%20untag.png" width="100%" alt="Tag and Untag"/>

**Tag / Untag**

</td>

<td width="50%" align="center">

<img src="./Screenshots/help.png" width="100%" alt="Help Command"/>

**Help Command**

</td>
</tr>
</table>

### 📦 Export & Data

<table>
<tr>
<td width="50%" align="center">

<img src="./Screenshots/Export%20Command.png" width="100%" alt="Export Command"/>

**Export Command**

</td>

<td width="50%" align="center">

<img src="./Screenshots/json%20file.png" width="100%" alt="JSON File"/>

**JSON Export**

</td>
</tr>
</table>

### 🗑️ Delete

<div align="center">

<img src="./Screenshots/Delete%20all%20notes.png" width="70%" alt="Delete All Notes"/>

**Delete All Notes**

</div>

</div>

---

## 🛠️ Tech Stack

```text
HTML5
CSS3
JavaScript
IndexedDB
JSON
```

Built without a frontend framework or backend server.

---

## 🚀 Live Preview

<div align="center">

### Try ShellScrap directly in your browser

<a href="https://shellscrap.netlify.app/">

<img src="https://img.shields.io/badge/%F0%9F%9A%80%20OPEN%20SHELLSCRAP-Live%20Demo-00F5A0?style=for-the-badge&logo=netlify&logoColor=white"/>

</a>

<br><br>

**No installation required. Just open and start writing.**

</div>

---

## 📂 Project Structure

```text
ShellScrap/
│
├── Screenshots/
│   ├── Delete all notes.png
│   ├── Display all notes.png
│   ├── Display one by one.png
│   ├── Export Command.png
│   ├── Saved 3 Notes.png
│   ├── Use find command.png
│   ├── after clear command.png
│   ├── help.png
│   ├── json file.png
│   ├── main interface.png
│   ├── tag and untag.png
│   └── tags command.png
│
├── index.html
├── LICENSE
└── README.md
```

> `desktop.ini` is a Windows system file and does not need to be displayed as a project screenshot.

---

## 👨‍💻 Developer

<div align="center">

### Muhammad Umar Jamal

**MUdevelops**

Software Developer • AI Enthusiast • Full-Stack Developer

<br>

<a href="https://github.com/MUdevelops">
<img src="https://img.shields.io/badge/GitHub-MUdevelops-181717?style=for-the-badge&logo=github"/>
</a>

<a href="https://m-umar-jamal.netlify.app/">
<img src="https://img.shields.io/badge/Portfolio-Visit-00C7B7?style=for-the-badge&logo=netlify&logoColor=white"/>
</a>

</div>

---

<div align="center">

### ⭐ ShellScrap

**Capture it. Tag it. Search it. Ship it.**

```text
> help
> create something awesome
```

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F5A0,50:00C6FF,100:7B2FFF&height=100&section=footer"/>

</div>
