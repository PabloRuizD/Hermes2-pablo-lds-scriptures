---
name: pablo-lds-scriptures
description: Standard Works SUD en JSON estructurado (Book of Mormon, Doctrine & Covenants, Pearl of Great Price, KJV Bible). Use to read and parse LDS scriptures for analysis, comparison, or text mining. Triggers: 'book of mormon', 'D&C', 'doctrine and covenants', 'pearl of great price', 'Standard Works', 'BOM', 'LDS scriptures', 'Mormon text', 'Alma', 'Moroni', 'Joseph Smith', 'SUD'.
version: 0.1.0
author: Hermes2 para Pablo Ruiz Danegger (fork simbolico desde https://github.com/bcbooks/scriptures-json)
license: MIT (skill) + MIT (JSON structure) + text from The Church of Jesus Christ of Latter-day Saints (public domain) (upstream data)
platforms: [linux, macos, windows]
tags: [religion, hermes2, fork, wrapper]
---

# pablo-lds-scriptures

## Upstream
- **Repo original:** https://github.com/bcbooks/scriptures-json
- **Licencia del upstream:** MIT (JSON structure) + text from The Church of Jesus Christ of Latter-day Saints (public domain)

## Proposito
Wrapper del repositorio upstream - los datos estan en este repo bajo las subcarpetas del upstream. Esta skill es un marcador de instalacion para que Hermes reconozca el dataset como disponible localmente.

## Instalacion
```bash
cp -r pablo-lds-scriptures/ ~/.hermes/skills/pablo-lds-scriptures/
```

## Licencia dual
- **Codigo de la skill (SKILL.md):** MIT - Pablo Agustin Ruiz Danegger, 2026.
- **Datos / corpus del upstream:** MIT (JSON structure) + text from The Church of Jesus Christ of Latter-day Saints (public domain)
