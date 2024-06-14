---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://cover.sli.dev
# some information about your slides, markdown enabled
title: Welcome to Slidev
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# apply any unocss classes to the current slide
class: text-center
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

## Taller:

# Inmersión Open Source

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>

<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://github.com/slidevjs/slidev" target="_blank" alt="GitHub" title="Open in GitHub"
    class="text-xl slidev-icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>

<!--
The last comment block of each slide will be treated as slide notes. It will be visible and editable in Presenter Mode along with the slide. [Read more in the docs](https://sli.dev/guide/syntax.html#notes)
-->

---
transition: fade-out
layout: center
class: text-center
---

# Sesión 1:
# Open Source Essentials

---

# Open Source Essentials

Contenido

- **Introducción a Open Source**
- **Fundamentos de Git y GitHub**
- **Proyecto Práctico en Github (Repo Inicial)**

---

# Introducción a Open Source

- **Definición y breve historia**
- **Beneficios del Open Source**
- **Licencias Open Source**
- **Exploración de proyectos Open Source populares**

Descubrirás las ventajas del desarrollo Open Source, sus diferentes licencias y proyectos populares tales como Python, Docker o Postgres.

También, comprenderás la predominancia de la colaboración pública sobre el producto de software privativo.

---

# Fundamentos de Git y GitHub

Aprenderás los conceptos clave de Git (repositorio, commit, branch, merge), comandos básicos y la utilización de GitHub para gestionar y compartir código.

 **Git**
- **Instalación de Git**
- **Comandos básicos de Git**
- **GitHub**
- **Colaboración con otros desarrolladores**

---

# Proyecto Práctico en Github
# (Repo Inicial)

---

# Proyecto Práctico en Github

## Trabajo en equipo

Interaccionemos en Github: clone un repo, abrir un PR, hacer un commit a un proyecto grupal.

## Escojamos un proyecto

Issues for beginners:

- [1](https://github.com/brave/brave-browser/issues/18931)
- [2](https://github.com/Shahrayar123/Python-Projects)
- [3](https://github.com/hyperium/hyper/labels/E-easy)
- [4](https://github.com/cypress-io/cypress/issues?q=is%3Aopen+is%3Aissue+label%3A%22good+first+issue%22)


---
layout: center
class: text-center
---

# Sesión 2:
# Open Source & AI con Python

---

# Open Source & AI con Python

Contenido

- **Introducción a Python y LLMs**
- **Proyecto Final (Con LLMs y Python)**

---

# Introducción a Python y LLMs

- **Python, un lenguaje versátil para desarrollo**
- **LLMs (Large Language Models)**
- **Integración de LLMs con Python**

Aprenderás las ventajas de Python como lenguaje de programación y te familiarizarás con los LLMs (Large Language Models) y sus aplicaciones.

---

# Proyecto Final
# (Con LLMs y Python)

- **Idea de Proyecto**: Construyamos una aplicación práctica con Python, Ollama, Llama-3 8B y LangChain 
- **Ejemplos**: ChatBot, script para generar contenido creativo, programa de análisis de datos

¡Pon en práctica tus conocimientos construyendo un proyecto innovador que combine Python y una LLM (como Phi-3 mini) para desarrollar una aplicación práctica.

---
layout: center
class: text-center
---

# Learn More

[Documentations]() · [GitHub]() · [Showcases]()
