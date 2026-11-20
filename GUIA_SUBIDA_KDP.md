# Guía para subir un volumen a KDP (tapa blanda)

Sirve para los volúmenes 2 y 3 de *Large Print Puzzle Book for Adults*. Reemplaza `N` por el número del volumen.
Regla general: **si el volumen 1 tiene un dato distinto al sugerido aquí, usa el del volumen 1**, para que la serie sea coherente.

## 0. Antes de empezar
- Descarga los dos PDF del volumen (desde GitHub `main` → `LIBRO AMAZON KDP/VolN/` o desde Drive «LIBRO AMAZON KDP»):
  - `Interior_LargePrintPuzzleBook_VolN.pdf`
  - `Cover_LargePrintPuzzleBook_VolN.pdf`
- Entra a kdp.amazon.com → **Bookshelf** → **+ Create** → **Paperback** → **Create paperback**.

## 1. Paperback Details (Detalles)
| Campo | Qué poner |
|---|---|
| Language | English |
| Book Title | `Large Print Puzzle Book for Adults` (igual que el Vol. 1) |
| Subtitle | `100 Word Search, Sudoku and Maze Puzzles – Easy to Medium – Every Answer Included` (el de la página de título del libro; si el Vol. 1 usa otro, copia ese) |
| Series | **Add series details** → **Select existing series** → la serie del Vol. 1 → número `N`. Si el Vol. 1 no tiene serie, créala al terminar este libro desde Bookshelf y añade los dos. |
| Edition number | 1 |
| Author | Exactamente como en el Vol. 1 (en la portada dice `Sergio A. Rodriguez`) |
| Contributors | vacío |
| Description | Ver texto abajo |
| Publishing rights | I own the copyright and I hold the necessary publishing rights |
| Primary audience | Sexually explicit: **No**. Reading age: déjalo vacío o igual al Vol. 1 |
| Primary marketplace | Amazon.com |
| Categories | Hasta 3: Books › Humor & Entertainment › Puzzles & Games › **Word Search** / **Sudoku** / **Mazes** (o las mismas del Vol. 1) |
| Keywords (7) | Ver lista abajo (o las mismas del Vol. 1) |
| Release date | Release my book for sale now |

**Descripción sugerida**

```
Volume N of the Large Print Puzzle Book for Adults series: 100 brand-new puzzles, none repeated from earlier volumes.

Three kinds of puzzle, mixed page after page, so you never settle into the same rhythm for long:
• 40 word search puzzles, a new theme every page
• 40 sudoku, each with exactly one answer and no guessing
• 20 mazes, from gentle to genuinely winding
• 100 full solutions, grouped at the back of the book
• A puzzle log to tick off everything you finish

Big grids and clear type on 8.5 x 11 inch pages. Puzzles grow gradually harder from the first page to the last, so you can start anywhere and still find your own level.

A relaxing gift for parents, grandparents and anyone who enjoys a quiet puzzle break.
```

**Palabras clave sugeridas** (una por casilla)
1. large print puzzle books for seniors
2. word search sudoku maze mix
3. activity book for adults large print
4. brain games for seniors
5. easy sudoku large print
6. word find puzzles for adults
7. puzzle gift for grandparents

→ **Save and Continue**

## 2. Paperback Content (Contenido)
| Campo | Qué poner |
|---|---|
| Print ISBN | **Get a free KDP ISBN** (o el mismo tipo que usaste en el Vol. 1) |
| Publication date | vacío |
| Print options | Interior: **Black & white** · Paper: **White** (obligatorio: la portada está calculada para papel blanco) · Trim size: **8.5 x 11 in** · Bleed: **No Bleed** · Cover finish: igual que el Vol. 1 (Matte o Glossy) |
| Low-content book | Igual que el Vol. 1 (un libro de puzzles con soluciones normalmente **no** se marca como low-content) |
| Large print | Marca la casilla si la marcaste en el Vol. 1 |
| Manuscript | Upload → `Interior_LargePrintPuzzleBook_VolN.pdf` |
| Book cover | **Upload a cover you already have** → `Cover_LargePrintPuzzleBook_VolN.pdf` |
| AI-Generated Content | Responde con la verdad sobre cómo se hicieron texto, imágenes y puzzles (igual que respondiste en el Vol. 1) |
| Book preview | **Launch Previewer** → revisa que no haya avisos; luego **Approve** |

Debe salir: 130 páginas, 8.5 x 11, sin errores. Si el previewer marca error de tamaño de portada, revisa que el papel sea **White**.

→ **Save and Continue**

## 3. Paperback Rights & Pricing (Derechos y precio)
| Campo | Qué poner |
|---|---|
| Territories | All territories (worldwide rights) |
| Primary marketplace | Amazon.com |
| Price | **USD 9.99** (KDP calcula los demás mercados; puedes dejarlos automáticos) |
| Expanded distribution | Igual que el Vol. 1 |

Regalía aproximada en Amazon.com: 60 % × 9.99 − costo de impresión (~USD 2.56 para 130 págs. B/N) ≈ **USD 3.40 por libro**. KDP muestra el valor exacto en esa pantalla.

→ **Publish Your Paperback Book**

## 4. Después
- KDP revisa en hasta 72 horas. Estado en Bookshelf: *In review* → *Live*.
- Avisar a Claude para actualizar `CATALOGO.md`: «En revisión», luego ASIN y fecha.
- Cuando esté *Live*, comprobar que aparece en la página de la serie junto al Vol. 1.
