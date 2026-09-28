# Sprint Board

A lightweight Kanban board that enforces the delivery habits I use with engineering teams: **work-in-progress limits, tracked cycle time and a release gate.**

**Live demo:** _add your Netlify link here_

## Features

- Six-stage workflow: Backlog → In Progress → In Review → QA → Ready for Release → Done
- **WIP limits** on In Progress and In Review, with a visual warning when exceeded
- **Cycle time** calculated automatically from start to done
- **Release gate:** only tickets in *Ready for Release* can ship, and each release is logged
- Drag and drop or use the arrow buttons
- Auto-numbered ticket keys (`PROJ-107`) and priority tags
- Data saved in the browser (localStorage)

## Tech

HTML, CSS and vanilla JavaScript in a single file. No build step.

## Run it

Open `index.html` in a browser, or drag the folder onto Netlify to deploy.

## Why I built it

Predictable delivery comes from limiting work in progress, measuring how long work takes and gating releases. This app turns those ideas into something you can click through.

## Roadmap

- [ ] Express + MongoDB backend with user accounts
- [ ] Multiple sprints and burndown chart
- [ ] Export release notes as Markdown

Built with an AI-assisted workflow. I designed the workflow rules and reviewed and tested the result.
