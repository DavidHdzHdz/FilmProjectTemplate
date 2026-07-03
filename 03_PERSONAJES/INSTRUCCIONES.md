# 03_PERSONAJES — Instrucciones

## ¿Qué es esta carpeta?

El sistema completo de personajes del proyecto. Está organizada por tipo de personaje, y dentro de cada tipo hay una carpeta `_template/` con archivos en blanco y carpetas de ejemplo del universo **Bad Request / Return Void** como referencia.

---

## Estructura general

```
03_PERSONAJES/
  Personajes.md          ← índice general de todos los personajes
  Relaciones.md          ← mapa de relaciones entre personajes
  Protagonistas/
    _template/           ← copia esto para crear un nuevo protagonista
    BadRequest/          ← ejemplo de referencia (no editar)
  Antagonistas/
    _template/           ← copia esto para crear un nuevo antagonista
    ValeriaCodec/        ← ejemplo de referencia (no editar)
  Secundarios/
    _template/           ← copia esto para cada secundario
    RigoMortiz/          ← ejemplo 3D (no editar)
    GaboElCyborg/        ← ejemplo 2D (no editar)
  Terciarios/
    _template/           ← copia esto para cada terciario
    TerciarioEjemplo/    ← ejemplo con 1D y 2D (no editar)
```

---

## Cómo crear un personaje nuevo

1. Ve a la carpeta del tipo que corresponda (`Protagonistas/`, `Antagonistas/`, etc.)
2. Copia la carpeta `_template/` completa
3. Renombra la copia con el nombre del personaje (ej: `MariaSoledad/`)
4. Llena los archivos en el orden indicado en el `INSTRUCCIONES.md` de esa subcarpeta

---

## Sistema de dimensionalidad

Cada personaje tiene una dimensionalidad que determina qué archivos y secciones llenar:

| Tipo | Dimensionalidad | Archivos a llenar |
|---|---|---|
| Protagonista | Siempre 3D | Todos |
| Antagonista | 3D o 2D | Según selector al inicio de cada archivo |
| Secundario | 3D o 2D | 3D: todos los archivos / 2D: Ficha + Motivacion |
| Terciario | 1D o 2D | Solo Ficha.md |

Las secciones marcadas con `[3D]` en los templates solo se llenan para personajes tridimensionales. Las marcadas `[2D · 3D]` aplican siempre.

---

## Orden de llenado general

```
1. Personajes.md          ← lista inicial de todos los personajes
2. Protagonistas/         ← empieza siempre aquí
3. Antagonistas/
4. Secundarios/           ← de mayor a menor importancia dramática
5. Terciarios/
6. Relaciones.md          ← al final, cuando ya conoces a todos
```

---

## Tips

- Empieza con el protagonista. Todo lo demás se define en relación a él.
- El antagonista se desarrolla mejor después del protagonista — el mejor antagonista es un espejo del protagonista que tomó un camino diferente.
- No crees más secundarios de los que la historia necesita. Cada secundario debe existir por una razón dramática que ningún otro personaje puede cumplir.
- Los terciarios se llenan último — muchos emergen durante la escritura, no en el desarrollo previo.
- `Relaciones.md` es el archivo que más cambia durante el desarrollo. Llénatelo al final pero actualízalo cuando descubras algo nuevo.

---
