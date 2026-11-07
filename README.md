# Master Euregio Cup

Sito web ufficiale della **Master Euregio Cup** – il nuovo meeting transfrontaliero di atletica leggera per la categoria Master (17.04.2027, Innsbruck · Bolzano · Trento).

Sito statico bilingue **italiano / tedesco**: nessuna build richiesta.

- `index.html` – pagina principale
- `assets/css/style.css` – stile (font Barlow Condensed / Barlow da Google Fonts)
- `assets/js/main.js` – traduzioni IT/DE, countdown, ticker, file .ics "Segna la data"
- `assets/img/logo.svg`, `assets/img/runner.svg` – logo estratto dal one-pager

Per vederlo in locale basta aprire `index.html` nel browser. La lingua segue quella del browser: italiano per i browser in italiano, tedesco per quelli in tedesco (Germania, Austria, Svizzera…); per le altre lingue si apre l'italiano. Il selettore IT/DE cambia lingua per la visita in corso; `?lang=it` o `?lang=de` nell'indirizzo forzano una lingua.
Per pubblicarlo è sufficiente GitHub Pages (Settings → Pages → branch).
