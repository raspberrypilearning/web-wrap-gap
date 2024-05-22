Tu peux utiliser la propriété `gap` de la classe `wrap` dans `style.css` pour créer un espace horizontal et/ou vertical entre les éléments enveloppés. Cela peut être utile lorsque tu utilises des bordures ou des ombres.

**Remarque :** la propriété `gap` n'est pas prise en charge par les anciens navigateurs web.

![Deux rangées de trois cases colorées avec des espaces entre les rangées et les colonnes.](images/flex-gap.png){:width="400px"}

--- code ---
---
language: css
filename: style.css
line_numbers: false
line_number_start: 1
line_highlights: 10
---
/* Styles uniquement pour la classe .wrap */

.wrap {
  /* Faire en sorte que le contenu s'étende sur plusieurs lignes */
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  align-items: center;
  box-sizing: border-box;
  gap: 1rem 1rem; /* espace horizontal et vertical */
}

--- /code ---
