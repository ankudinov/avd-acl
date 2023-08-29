---
marp: true
theme: default
# class: invert
author: Petr Ankudinov
# size 16:9 1280px 720px
size: 16:9
paginate: true
math: mathjax
# backgroundImage: "linear-gradient(to bottom, #1e3744, #301B29)"
style: |
    :root {
      background: linear-gradient(to right, #ece9e6, #ffffff);
    }
    img[alt~="custom"] {
      float: right;
    }
    .columns {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 1rem;
    }
    footer {
      font-size: 14px;
    }
    section::after {
      font-size: 14px;
    }
    img {
      background-color: transparent;
    }
---

# Demo

## ACL with AVD

<!-- Do not add page number on this slide -->
<!--
_paginate: false
-->

```text
How to Generate ACL Config Using AVD

Petr Ankudinov, 2023
```

![bg right fit](img/avd-logo.webp)

---

# Credits and References

<style scoped>section {font-size: 22px;}</style>

<!-- Add footer starting from this slide -->
<!--
footer: '![h:20](https://www.arista.com/assets/images/logo/Arista_Logo.png)'
-->

This repository is based on many awesome open source repositories and some free/commercial Github features:

- [VS Code](https://code.visualstudio.com/)
- [DevContainers](https://code.visualstudio.com/docs/remote/containers)
- [Marp](https://marp.app/)
- [Excalidraw VS Code Plugin](https://github.com/excalidraw/excalidraw-vscode)
- [Github Actions](https://github.com/features/actions)
- [Github Pages](https://pages.github.com/)
- [Github Codespaces](https://github.com/features/codespaces)
- [Carbon](https://carbon.now.sh/)
- And many more...

All photos are taken from [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/). Excellent free stock photos resources. It's not possible to reference every author individually, but their work is highly appreciated.