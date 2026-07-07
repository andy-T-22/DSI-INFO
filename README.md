# DSI INFO — Guia de Uso

Repositorio de conocimiento completo de **Diseno de Sistemas de Informacion (DSI)** — UTN.
Todo el material de la cursada procesado y estructurado para consulta rapida con IA o estudio personal.

---

## Estructura del repositorio

```
dsi andy/
│
├── README.md                              <- Este archivo
│
├── knowledge_base/                        <- Base de conocimiento generada
│   ├── DSI_INFO_Completo.md              <- Navegador maestro (2.7 KB)
│   ├── INDEX.md                           <- 59 conceptos indexados con archivo exacto
│   ├── Casos_Practicos.md                 <- 15 PDFs · 1.59 MB
│   ├── Diapositivas_y_Teoricos.md         <- 7 PDFs  · 381 KB
│   ├── Parciales_y_Examenes.md            <- 4 PDFs  · 160 KB
│   ├── Resumenes.md                       <- 3 PDFs  · 45 KB
│
├── Casos Practicos/                       <- PDFs originales
├── Diapositivas y Teoricos/               <- PDFs originales
├── Parciales y Examenes/                  <- PDFs originales
└── Resumenes/                             <- PDFs originales
```

---

## Como usar con una IA local (Antigravity)

**Flujo recomendado:**

| Tipo de pregunta | Que hace la IA |
|---|---|
| Concepto puntual ("que es GRASP Creator") | Lee `knowledge_base/INDEX.md` → va a `Diapositivas_y_Teoricos.md` |
| Caso practico ("diagrama de clases del Peaje") | Lee la sección en `Casos_Practicos.md` y abre el PDF original directamente en la página indicada para ver el diagrama |
| Repaso general de un tema | Carga el archivo de categoría completo (ej: `Resumenes.md`, 45 KB) |
| Ver un diagrama especifico | Abre el PDF original que se encuentra enlazado y va a la página exacta |

**Prompt sugerido para iniciar sesion:**

```
Tengo el repositorio DSI INFO en: /ruta/a/tu/repositorio/

Base de conocimiento en knowledge_base/:
- INDEX.md                  → indice de 59 conceptos con archivo y seccion exacta
- DSI_INFO_Completo.md      → navegador maestro
- Casos_Practicos.md        → 15 casos practicos completos con referencias de pagina a los PDFs
- Diapositivas_y_Teoricos.md → 7 teoricos (GRASP, diagramas, etc.)
- Parciales_y_Examenes.md   → 4 ejercicios tipo parcial
- Resumenes.md              → 3 resumenes

Para responder sobre DSI:
1. Consulta INDEX.md para ubicar el tema
2. Lee la seccion en el archivo de categoria
3. Si hay diagramas, abre el PDF original enlazado en la pagina indicada
```

---

## Como usar con IA en la nube (Claude.ai, ChatGPT, etc.)

| Que necesitas | Que subir |
|---|---|
| Teoria y patrones | `knowledge_base/Diapositivas_y_Teoricos.md` |
| Casos practicos | `knowledge_base/Casos_Practicos.md` |
| Repaso para parcial | `knowledge_base/Parciales_y_Examenes.md` + `knowledge_base/Resumenes.md` |
| Ver diagrama especifico | El PDF original correspondiente |

> Los archivos Markdown contienen enlaces relativos a las páginas exactas de los PDFs originales. 
> Si usas una IA en la nube, sube el PDF del caso correspondiente para que pueda leer las imágenes de la página indicada.

---

*Repositorio DSI INFO — UTN*
