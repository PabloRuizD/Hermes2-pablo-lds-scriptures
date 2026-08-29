# pablo-lds-scriptures

> **Parte del set `Hermes2-` de [PabloRuizD](https://github.com/PabloRuizD).** Esta skill fue generada con asistencia de Hermes2 para uso del agente personal de Pablo Ruiz Danegger (Instituto Técnico UNT Tucumán).

📂 **Categoría:** 🔧 Ingeniería
🏷️ **Tipo:** Wrapper (fork simbólico)

## Descripción

Standard Works SUD en JSON estructurado (Book of Mormon, Doctrine & Covenants, Pearl of Great Price, KJV Bible). Use to read and parse LDS scriptures for analysis, comparison, or text mining. Triggers: 'book of mormon', 'D&C', 'doctrine and covenants', 'pearl of great price', 'Standard Works', 'BOM', 'LDS scriptures', 'Mormon text', 'Alma', 'Moroni', 'Joseph Smith', 'SUD'.

## Origen

- **Upstream:** https://github.com/bcbooks/scriptures-json
- **Autor del port:** Pablo Agustín Ruiz Danegger con Hermes2 (agosto 2026)
- **Propósito:** marcar y disponibilizar esta skill para el agente personal Hermes2, en una cuenta separada para evitar confusión con otros repos de Pablo.

## Instalación

### Opción A — Descarga directa

```bash
git clone https://github.com/PabloRuizD/Hermes2-pablo-lds-scriptures.git
mkdir -p ~/.hermes/skills/pablo-lds-scriptures
cp -r Hermes2-pablo-lds-scriptures/* ~/.hermes/skills/pablo-lds-scriptures/
```

### Opción B — Como submódulo

```bash
mkdir -p ~/.hermes/skills/pablo-lds-scriptures
git submodule add https://github.com/PabloRuizD/Hermes2-pablo-lds-scriptures.git ~/.hermes/skills/pablo-lds-scriptures/source
```

## Estructura

```
pablo-lds-scriptures/
├── SKILL.md           # Definición técnica (frontmatter YAML + cuerpo Markdown)
├── README.md          # Este archivo
├── LICENSE            # Licencia MIT
└── .gitignore
```

Si la skill incluye datos locales (textos, corpus, datasets), los encontrarás en subcarpetas dentro del repo según se defina en `SKILL.md`.

## Uso

Una vez instalada en `~/.hermes/skills/pablo-lds-scriptures/`, el agente Hermes2 carga automáticamente la skill y la activa cuando tu pedido contenga los triggers listados en `SKILL.md`.

Ejemplo:
```
Usuario: "<algún trigger de la skill>"
Hermes2: invoca la skill, carga references/, ejecuta scripts/ si aplica.
```

## Licencia

- **Código (SKILL.md, README.md, scripts propios):** MIT — ver `LICENSE`.
- **Datos del upstream (si aplica):** ver la sección "Origen" arriba; cada upstream mantiene su propia licencia (CC-BY, CC-BY-SA, ODbL, MIT, o Public Domain según el caso).

## Aviso

Esta skill fue generada con asistencia de IA. Verificar los outputs antes de uso en producción. Para correcciones o ampliaciones, abrir un issue en el repositorio.

---

*Generado: 2026-08-29 · Hermes2 para Pablo Ruiz Danegger*
