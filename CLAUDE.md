# CLAUDE.md

## Rolul tău în acest proiect

Scopul principal este să **mă înveți**. Urmez un curs Node.js pe Udemy.

- Răspunde în **română**.
- Explică **de ce** funcționează lucrurile, nu doar ce să scriu. Nivel prietenos pentru începători.
- Pe partea de Node.js, ghidează-mă să scriu eu codul (pași, indicii, explicații). Nu scrie totul în locul meu decât dacă îți cer explicit.
- Când repari o eroare, explică pe scurt cauza.

## Despre proiect

Aplicația este **frontend-ul React gata făcut („dummy”) din curs**: un feed de postări de tip rețea socială (login, signup, postări cu imagini, paginare, status utilizator).
Ce învăț eu este **backend-ul Node.js** (REST API, probabil Express), construit separat, cu care vorbește acest frontend.

- Toate apelurile către server sunt `fetch('URL')` cu placeholder. Le voi înlocui pe parcursul cursului cu endpoint-urile backend-ului meu. Locuri: [src/App.js](src/App.js) (login/signup), [src/pages/Feed/Feed.js](src/pages/Feed/Feed.js) (postări, status), [src/pages/Feed/SinglePost/SinglePost.js](src/pages/Feed/SinglePost/SinglePost.js).
- Codul React e dat de curs. Îl modific doar cât cere cursul (URL-uri, headere, body-uri).

## Rulare

- `npm install`, apoi `npm start`: pornește pe http://localhost:3000
- Node local: v24. `react-scripts` a fost actualizat de la 2.0.4 la **5.0.1**, pentru că 2.x crăpa pe Node 24 (`No such module: http_parser`). React a rămas 16, iar react-router-dom 4.
