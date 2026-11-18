# 🩸 TAKEOWN — Interactive Terminal Website

\<div align="center">

\<img src="[https://capsule-render.vercel.app/api?type=venom&height=180&color=0:050505,50:350008,100\:e01e2d&text=TAKEOWN&fontColor=ffffff&fontSize=55&animation=fadeIn&fontAlignY=45&desc=INTERACTIVE%20TERMINAL%20EXPERIENCE&descSize=13&descAlignY=68](https://capsule-render.vercel.app/api?type=venom\&height=180\&color=0:050505,50:350008,100\:e01e2d\&text=TAKEOWN\&fontColor=ffffff\&fontSize=55\&animation=fadeIn\&fontAlignY=45\&desc=INTERACTIVE%20TERMINAL%20EXPERIENCE\&descSize=13\&descAlignY=68)" width="100%"/>

**A dark, interactive website inspired by Linux terminals and hacker aesthetics.**

\<img src="[https://img.shields.io/badge/HTML5-Website-e34f26?style=for-the-badge&logo=html5&logoColor=white](https://img.shields.io/badge/HTML5-Website-e34f26?style=for-the-badge\&logo=html5\&logoColor=white)"/>
\<img src="[https://img.shields.io/badge/CSS3-Design-1572b6?style=for-the-badge&logo=css3&logoColor=white](https://img.shields.io/badge/CSS3-Design-1572b6?style=for-the-badge\&logo=css3\&logoColor=white)"/>
\<img src="[https://img.shields.io/badge/JavaScript-Interactive-f7df1e?style=for-the-badge&logo=javascript&logoColor=black](https://img.shields.io/badge/JavaScript-Interactive-f7df1e?style=for-the-badge\&logo=javascript\&logoColor=black)"/>
\<img src="[https://img.shields.io/badge/License-Free%20Use-00c853?style=for-the-badge](https://img.shields.io/badge/License-Free%20Use-00c853?style=for-the-badge)"/>

\</div>

---

## `01` — About the Project

This project is a customizable interactive website featuring a dark terminal-inspired interface.

Designed with a minimalist hacker aesthetic, it combines ASCII art, animated typography, boot sequences and an interactive command-line interface.

The project was created by **takeown** and is available for anyone who wants to use, modify or personalize it.

## `02` — Features

- **Boot Animation:** Simulated Linux startup sequence.
- **Interactive Terminal:** Execute commands directly on the website.
- **ASCII Art:** Custom text-based artwork.
- **Animated Effects:** Glitch, blinking cursor and dripping text animations.
- **Background Customization:** Change the background image.
- **SoundCloud Integration:** Optional background music.
- **Visitor Information:** Displays available visitor location and browser hardware information.
- **Responsive Layout:** Adapted for desktop and mobile devices.

## `03` — Available Commands

| Command  | Description                  |
| :------- | :--------------------------- |
| `help`   | Display available commands   |
| `ls`     | List files and directories   |
| `cd`     | Navigate between directories |
| `cat`    | Read file contents           |
| `pwd`    | Display current directory    |
| `whoami` | Display current user         |
| `clear`  | Clear terminal output        |
| `mute`   | Disable music                |
| `unmute` | Enable music                 |

## `04` — Customization

You are free to edit and personalize the website.

Some things you can modify:

- Website name and ASCII artwork.
- Background image and colors.
- Terminal commands and directory structure.
- Contact information and social media.
- Startup animation and visual effects.
- SoundCloud music link.
- Fonts, layout and other design elements.

### Editing contacts

Open `index.html` and find the following section:

```javascript
var root = { t: "dir", c: {
  "contatos": { t: "dir", enter: "discord: takeown", c: {
    "discord.txt": { t: "file", v: "discord: takeown" }
  } },
  "redesocial": { t: "dir", enter: "instagram: @1h9u", c: {
    "instagram.txt": { t: "file", v: "instagram: @1h9u" }
  } }
} };
```

Change the contact information to your own.

### Changing the background

Find the CSS variable:

```css
--banner: url("YOUR_IMAGE_URL");
```

Replace the URL with your preferred image.

### Changing the music

Find:

```javascript
var SC_URL = "https://soundcloud.com/v6h/www";
```

Replace it with your preferred SoundCloud track.

## `05` — Installation

No frameworks or complicated installation required.

```bash
# Clone the repository
git clone https://github.com/pffl/takeown-terminal.git

# Enter the project folder
cd takeown-terminal
```

Open `index.html` in your browser.

Alternatively, upload the files to your preferred web hosting service.

## `06` — Permissions

\<details>
\<summary>\<strong>Free to use and customize\</strong>\</summary>

You are allowed to:

- Use this project for personal purposes.
- Modify the source code.
- Change the design and functionality.
- Use it as a base for your own website.
- Publish your modified version.

**Credits:** The original project was created by takeown. Please keep the original author attribution when redistributing the project.

\</details>

## `07` — Credits

\<div align="center">

**Developed with dedication by**

# `takeown`

\<a href="[https://github.com/pffl](https://github.com/pffl)"> \<img src="[https://img.shields.io/badge/GitHub-pffl-181717?style=for-the-badge&logo=github](https://img.shields.io/badge/GitHub-pffl-181717?style=for-the-badge\&logo=github)"/> \</a>

\<a href="[https://discord.com/users/](https://discord.com/users/)"> \<img src="[https://img.shields.io/badge/Discord-takeown-5865F2?style=for-the-badge&logo=discord](https://img.shields.io/badge/Discord-takeown-5865F2?style=for-the-badge\&logo=discord)"/> \</a>

---

*Feel free to explore, edit and make it your own.*

**Original project by takeown © 2026**

\<img src="[https://capsule-render.vercel.app/api?type=waving&color=0:050505,50:350008,100\:e01e2d&height=100&section=footer](https://capsule-render.vercel.app/api?type=waving\&color=0:050505,50:350008,100\:e01e2d\&height=100\&section=footer)" width="100%"/>

\</div>
