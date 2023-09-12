## Øvelse: Omdan en HTML Todo Liste til en React App

LØSNING: 
* [App.js](https://github.com/ITAKEA/solution_todo_html_to_react_ex/blob/master/src/App.js)
* [original.html](https://github.com/ITAKEA/solution_todo_html_to_react_ex/blob/master/public/original.html)

### Mål:
I denne øvelse skal du omdanne en eksisterende [HTML Todo Liste](https://itakea.github.io/todo_html_to_react_ex/) til en React App. Dette indebærer arbejde med _components_, _props_, _state_, _events_ og _form_ elementer.

### Materialer:
- Startkode: [En simpel Todo Liste skrevet i HTML, CSS (Bootstrap) og JavaScript](https://github.com/ITAKEA/todo_html_to_react_ex/blob/master/index.html). 

### Instruktioner:

1. **Oprettelse af en ny React App**
   - Brug Create React App til at oprette en ny React app med kommandoen `npx create-react-app react-todo-list`.
   - Gå ind i din nye app-mappe med kommandoen `cd react-todo-list`.

2. **Installation af Bootstrap**
(Hvis du fortrækker et andet framework, eller fortrækker at lave alt css selv er det helt fint. Bootstrap er bare et eksempel.)    

   - Installer Bootstrap i din React app med kommandoen `npm install bootstrap`.
   - Inkluder Bootstrap i din app ved at tilføje følgende linje i `src/index.css`: `@import '~bootstrap/dist/css/bootstrap.min.css';`.

3. **Oprettelse af TodoList Komponent**
   - Opret en ny fil `TodoList.js` i `src` mappen.
   - I `TodoList.js`, opret en funktionel komponent `TodoList` der returnerer en JSX repræsentation af den oprindelige HTML-struktur (du kan tage udgangspunkt i den HTML-struktur, der blev leveret i startkoden).

4. **Tilføjelse af State og Funktioner**
   - Brug `useState` hook til at oprette state variabler for din todo liste og input-feltet.
   - Implementer funktionerne `addTodo`, `toggleDone` og `removeTodo` for at håndtere henholdsvis tilføjelse af nye todos, markering af todos som fuldført, og fjernelse af todos.

5. **Rendering af Todo Liste**
   - Brug `map` funktionen til at gennemgå alle todos og vise dem i en liste med en checkbox og en "fjern" knap for hver todo.
   - Tilføj en `key` prop til hvert element i listen for at hjælpe React med at identificere hvilke elementer der har ændret sig.

6. **Test din App**
   - Kør din app med kommandoen `npm start` og test funktionaliteten i din browser.
   - Sørg for at din app fungerer som forventet og ligner den oprindelige HTML-version.


### Bonus opgave:
- Tilføj yderligere funktionaliteter eller forbedringer til din app, såsom muligheden for at redigere todos, en "markér alle som fuldført" knap, eller en måde at filtrere og vise kun fuldførte eller ufuldførte todos.
