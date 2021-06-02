# List with floating section headings

Creates a list with floating headings for each section.

- Use overflow-y: auto to allow the list container to overflow vertically.
- Use display: grid on the inner container (```<dl>```) to create a layout with two columns.
- Set headings (```<dt>```) to grid-column: 1 and content (```<dd>```) to grid-column: 2
- Finally, apply position: sticky and top: 0.5rem to headings to create a floating effect.