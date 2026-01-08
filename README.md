# Angular Micro‑Frontend Portfolio

[![Angular](https://img.shields.io/badge/Angular-21-DD0031?style=for-the-badge&logo=angular&logoColor=white)](https://angular.dev)[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178C6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org/)[![Webpack Module Federation](https://img.shields.io/badge/Webpack-Module%20Federation-1C78C0?style=for-the-badge&logo=webpack&logoColor=white)](https://module-federation.io)[![Status](https://img.shields.io/badge/Status-Work%20in%20Progress-yellow?style=for-the-badge)](#)

A personal developer portfolio built with Angular 21 and Webpack Module Federation, showcasing a micro‑frontend architecture with a shell application and independent feature remotes.

---

## ✨ Overview

This repository contains the source code for a **micro‑frontend based portfolio website**.  
The goal is to demonstrate modern frontend architecture using Angular, Module Federation, and clean separation between shell and feature modules.[web:64][web:66]

Current setup:

- **Shell app**: Hosts global layout, navigation, and the Home page.
- **About remote**: Separate Angular application exposing the About page via Module Federation.

---

## 🏗️ Project structure

```txt
.
├── portfolio-shell        # Host / shell Angular app (Home, layout, main routing)
└── portfolio-about-mfe    # Remote Angular app (About page as a federated module)
