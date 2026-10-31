```diff
+       ▄▄▄██████▄▄▄        +-------------------------------------------------------+
+     ▄██▀▀▀▀▀▀▀▀▀▀██▄      |                                                       |
+     ██▀▄▄▄▄▄▄▄▄▄▄▀██      |   █████  ██████   ██████ ██   ██ ██ ██    ██ ███████  |
+     █▌ ▀█▄    ▄█▀ ▐█      |  ██   ██ ██   ██ ██      ██   ██ ██ ██    ██ ██       |
+     █▌     ▐▌     ▐█      |  ███████ ██████  ██      ███████ ██ ██    ██ █████    |
+     ▀█▄   ▀▀▀▀   ▄█▀      |  ██   ██ ██   ██ ██      ██   ██ ██  ██  ██  ██       |
+   ▄▄▄▄██▀▀████▀▀██▄▄▄▄    |  ██   ██ ██   ██  ██████ ██   ██ ██   ████   ███████  |
+   ████▀▀▄ ▐██▌ ▄▀▀████    |                                                       |
+   █████▌  ▐██▌  ▐█████    |   OWNER  :: </tokenn>                                 |
+   █████▌  ▐██▌  ▐█████    |   GITHUB :: @TadejaMK                                 |
+   █████▌  ▐██▌  ▐█████    +-------------------------------------------------------+
```

![status](https://img.shields.io/badge/STATUS-LIVE-39ff6a?style=flat-square&labelColor=0a0f0a)
![host](https://img.shields.io/badge/HOST-NETLIFY-39ff6a?style=flat-square&labelColor=0a0f0a)
![build](https://img.shields.io/badge/BUILD-STATIC-39ff6a?style=flat-square&labelColor=0a0f0a)
![theme](https://img.shields.io/badge/THEME-DARK_/_LIGHT-39ff6a?style=flat-square&labelColor=0a0f0a)

```diff
+ ╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌

+ user@archive:~$ booting up...
+ [ OK ] initializing readme session...

+ user@archive:~$ whoami
+ > </tokenn>
+ > a personal archive, indexed like a system log.
+ > single page. static. no build step.

+ user@archive:~$ ls features/
+ [ OK ] boot-sequence intro
+ [ OK ] dark / light theme toggle
+ [ OK ] click-to-expand image cards
+ [ OK ] indexed sections with NODE_ and MODULE_ tags
+ [ OK ] responsive layout, desktop + mobile

+ user@archive:~$ cat sections.txt
+ [ 01 // Profiles ]    about
+ [ 02 // Curated  ]    favorite art
+ [ 03 // Original ]    personal works
+ [ PROJECTS       ]    web projects
+ [ 04 // Logged   ]    achievements
+ [ 05 // Toolset  ]    skills

+ user@archive:~$ cat toolset
+ PROFICIENT    ████████████  HTML · CSS
+ INTERMEDIATE  ████████░░░░  JavaScript
+ DEVELOPING    ████░░░░░░░░  Node.js · React · Vite · Tailwind · TS

+ ╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌
```

```diff
+ user@archive:~$ ls projects/
+ [ OK ] 5 projects found

+ [ 01 ] rchiveken        main profile website         CSS
+ [ 02 ] mytasuku         local-first task manager     JavaScript
+ [ 03 ] klikks           typing test + keyboard sounds  JavaScript
+ [ 04 ] ticketofomoide   memory ticket maker          CSS
+ [ 05 ] stampquest       daily photo stamps           HTML

+ user@archive:~$ open --details projects/*
```

| # | Project | About | Built with | Links |
|---|---------|-------|------------|-------|
| 01 | **rchiveken** | My main profile website, the archive itself. | CSS | [live](https://krchive.netlify.app/) · [repo](https://github.com/TadejaMK/rchiveken) |
| 02 | **mytasuku** | A simple, local-first task manager with a focus timer, history, achievements, and four color palettes. | JavaScript | [live](https://mytasuku.netlify.app/) · [repo](https://github.com/TadejaMK/mytasuku) |
| 03 | **klikks** | A minimal typing test with satisfying keyboard sounds, multiple test modes, and saved history. | JavaScript | [live](https://klikks.netlify.app/) · [repo](https://github.com/TadejaMK/klikks) |
| 04 | **ticketofomoide** | Turn a photo and a few details into a keepsake memory ticket, saved to your browser and downloadable as PNG. | CSS | [live](https://ticketofomoide.netlify.app/) · [repo](https://github.com/TadejaMK/ticketofomoide) |
| 05 | **stampquest** | Take one photo every day and turn it into your own digital stamp. | HTML | [live](https://stampquest.netlify.app/) · [repo](https://github.com/TadejaMK/stampquest) |

```diff
+ ╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌

+ user@archive:~$ git clone --mode
+ ( ) [ https ]   git clone https://github.com/TadejaMK/<your-repo>.git
+ ( ) [ ssh   ]   git clone git@github.com:TadejaMK/<your-repo>.git

+ user@archive:~$ cd <your-repo> && npx serve .
+ [ OK ] serving on http://localhost:3000

+ user@archive:~$ tree
+ .
+ ├── index.html
+ └── assets/
+     └── images/

+ user@archive:~$ deploy --host netlify
+ [ OK ] connect repo
+ [ OK ] build command: none
+ [ OK ] publish directory: /
+ [ OK ] site is live

+ ╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌

+ user@archive:~$ visit_archive
+ [ y / n ]
```

<p align="center">
  <a href="https://krchive.netlify.app/"><kbd>&nbsp;&nbsp;Submit&nbsp;&nbsp;</kbd></a>
</p>

```diff
+ user@archive:~$ exit
+ [ OK ] session closed.
+ © 2025 · all records reserved.
```

```diff
+ ╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌

+ user@archive:~$ ssh visitor@github.com
+ [ OK ] connection established

+ user@archive:~$ gh stats --user TadejaMK
+ [ OK ] fetching live data from github...
```

```diff
+ [ OK ] stats loaded
+ [ OK ] 4 modules online :: stats · languages · streak · graph

+ user@archive:~$ logout
+ [ OK ] connection closed.
+ ╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌╌
```


<div align="center">

<img alt="followers" src="https://img.shields.io/github/followers/TadejaMK?label=FOLLOWERS&style=flat-square&labelColor=0a0f0a&color=39ff6a" />

<br /><br />

<img alt="HTML" src="https://img.shields.io/badge/HTML-PROFICIENT-39ff6a?style=flat-square&labelColor=0a0f0a" />
<img alt="CSS" src="https://img.shields.io/badge/CSS-PROFICIENT-39ff6a?style=flat-square&labelColor=0a0f0a" />
<img alt="JavaScript" src="https://img.shields.io/badge/JAVASCRIPT-INTERMEDIATE-2bbf50?style=flat-square&labelColor=0a0f0a" />
<img alt="Node.js" src="https://img.shields.io/badge/NODE.JS-DEVELOPING-1d7a38?style=flat-square&labelColor=0a0f0a" />
<img alt="React" src="https://img.shields.io/badge/REACT-DEVELOPING-1d7a38?style=flat-square&labelColor=0a0f0a" />
<img alt="Vite" src="https://img.shields.io/badge/VITE-DEVELOPING-1d7a38?style=flat-square&labelColor=0a0f0a" />
<img alt="Tailwind" src="https://img.shields.io/badge/TAILWIND-DEVELOPING-1d7a38?style=flat-square&labelColor=0a0f0a" />
<img alt="TypeScript" src="https://img.shields.io/badge/TS-DEVELOPING-1d7a38?style=flat-square&labelColor=0a0f0a" />

<br /><br />

<img width="100%" alt="GitHub streak" src="https://streak-stats.demolab.com?user=TadejaMK&theme=dark&hide_border=true&background=0a0f0a&ring=39ff6a&fire=39ff6a&currStreakLabel=39ff6a" />

<br /><br />

<img width="100%" alt="Contribution graph" src="https://ghchart.rshah.org/39ff6a/TadejaMK" />

</div>
