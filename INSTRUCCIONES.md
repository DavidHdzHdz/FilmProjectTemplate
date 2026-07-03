# Cinema Project Template — Instrucciones Generales

## ¿Qué es esto?

Un framework de desarrollo cinematográfico organizado en fases, desde la idea inicial hasta la postproducción. Está diseñado para ser usado solo o en equipo, y está basado en metodología del libro *Escribir Cine* de Alexander Steele y cursos de creación literaria.

Este template es la primera versión de lo que está pensado para convertirse en una aplicación SaaS para equipos de producción, estudios independientes y escuelas de cine. La metodología es fija e intencional — no está pensada para ser personalizada por el usuario, sino para ser seguida.

---

## Cómo está organizado

Cada carpeta representa una fase del desarrollo. El orden importa: algunas fases alimentan directamente a las siguientes.

| Carpeta | Fase | Cuándo llenarla |
|---|---|---|
| `01_CONCEPTO` | La idea: premisa, logline, sinopsis | Primera fase — empieza aquí |
| `00_PROJECT_OVERVIEW` | Visión general y cronograma | Después del concepto — necesita logline y premisa para llenarse |
| `02_MUNDO` | El universo narrativo | En paralelo con personajes |
| `03_PERSONAJES` | Todos los personajes por tipo | En paralelo con el mundo |
| `04_ESCRITURA` | Del brainstorm al guion final | Después de concepto y personajes |
| `05_VISUAL` | Lenguaje visual, referentes, paleta | En paralelo con la escritura |
| `06_PREPRODUCCION` | Storyboard, shotlist, plan de rodaje | Con guion cerrado |
| `07_PRODUCCION` | Diario de rodaje | Durante el rodaje |
| `08_POST` | Edición, sonido, música, color | Después del rodaje |

---

## Orden de llenado recomendado

```
01_CONCEPTO → 00_PROJECT_OVERVIEW → 02_MUNDO + 03_PERSONAJES (paralelo)
→ 04_ESCRITURA + 05_VISUAL (paralelo) → 06_PREPRODUCCION → 07_PRODUCCION → 08_POST
```

Cada carpeta tiene su propio archivo `INSTRUCCIONES.md` con el orden específico dentro de esa fase y tips de uso.

---

## Sobre los archivos de ejemplo

Dentro de `03_PERSONAJES` encontrarás dos tipos de carpetas por cada tipo de personaje:

- **`_template/`** — archivos en blanco para usar en tu proyecto. Cópialos en una carpeta nueva con el nombre de tu personaje.
- **Carpetas de ejemplo** — personajes del universo **Bad Request / Return Void**, un proyecto de ciencia ficción original usado como referencia de llenado. Están ahí para que veas cómo se ve un template lleno, no para ser editados.

| Carpeta ejemplo | Personaje | Tipo |
|---|---|---|
| `Protagonistas/BadRequest/` | Bad Request | Protagonista 3D |
| `Antagonistas/ValeriaCodec/` | Valeria Codec / La Curadora | Antagonista 3D inventada |
| `Secundarios/RigoMortiz/` | Rigo Mortiz | Secundario 3D |
| `Secundarios/GaboElCyborg/` | Gabo El Cyborg | Secundario 2D |
| `Terciarios/TerciarioEjemplo/` | 3 personajes terciarios | 1D y 2D |

---

## Tips generales

- **No esperes tener todo claro para empezar.** Los archivos están diseñados para ser llenados con incertidumbre y refinados con el tiempo.
- **El logline y la premisa se escriben mal la primera vez.** Eso es normal. Vuelve a ellos después de desarrollar los personajes.
- **El mundo y los personajes se alimentan entre sí.** Si defines una regla del mundo, pregúntate cómo afecta a cada personaje — y viceversa.
- **Los archivos de escritura (`04_ESCRITURA`) no deben tocarse hasta tener el concepto y los personajes principales definidos.** Empezar a escribir guion antes de eso es el error más común.
- **`07_PRODUCCION` y `08_POST` se llenan en tiempo real.** No son para planear — son para registrar.

---
