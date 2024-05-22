Je kunt de `gap` eigenschap van de `wrap` class in `style.css` gebruiken om een horizontale en/of verticale opening te maken tussen omwikkelde items. Dit kan handig zijn als je randen of schaduwen gebruikt.

**Opmerking:** De `gap` eigenschap wordt niet ondersteund door oudere webbrowsers.

![Twee rijen van drie gekleurde dozen met gaten tussen de rijen en kolommen.](images/flex-gap.png){:width="400px"}


--- code ---
---
language: css
filename: style.css
line_numbers: false
line_number_start: 1
line_highlights: 10
---
/* Stijlen alleen voor de .wrap-class */

.wrap {
  /* Laat inhoud over meerdere rijen lopen */
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  box-sizing: border-box;
  gap: 1rem 1rem; /* horizontale en verticale opening */
}

--- /code ---
