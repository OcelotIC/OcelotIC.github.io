# OcelotIC.github.io

Personal website of Idriss CHELIKH — Robotics & Control Engineer.

## Structure

```
├── index.html        ← main page (HTML + CSS + JS, single file)
├── content/          ← .md files loaded dynamically by the site
│   ├── project-*.md  ← projects (type: project)
│   └── paper-*.md    ← publications (type: paper)
├── papers/           ← PDF files for your publications
│   └── (drop your PDFs here)
├── assets/           ← images (profile photo, etc.)
│   └── photo.jpg
└── README.md
```

## How to add content

### Add a publication
1. Drop your PDF in `papers/`
2. Create a `.md` file in `content/`:

```markdown
---
type: paper
title: "Your Paper Title"
authors: I. Chelikh, A. Coauthor
venue: Conference or Journal Name
year: 2024
pdf: papers/your-file.pdf
doi: https://doi.org/10.xxxx/xxxxx
hal: https://hal.science/hal-xxxxxxx
arxiv: https://arxiv.org/abs/xxxx.xxxxx
---
```

### Add a project
Create a `.md` file in `content/`:

```markdown
---
type: project
title: Project Name
description: Short description of the project.
techs: Python, MATLAB, ROS
repo: https://github.com/OcelotIC/repo-name
order: 1
---
```

The `order` field controls the display order (lowest first).

## Deploy

Push to `main` branch → live at `https://OcelotIC.github.io`
