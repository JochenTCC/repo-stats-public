# repo-stats-public

Enthaelt ausschliesslich aggregierte, oeffentliche GitHub-Traffic-Statistiken
(Clones/Views pro Tag) fuer die Repos [Earnie](https://github.com/JochenTCC/Earnie)
und [ha-addon-earnie](https://github.com/JochenTCC/ha-addon-earnie), verwendet
von [earnie-hems.com](https://earnie-hems.com).

Die Datei [`stats/summary.json`](stats/summary.json) wird automatisch von
einer GitHub-Actions-Pipeline im Earnie-Hauptrepo aktualisiert (Branch
`stats-raw`, Workflow `traffic-aggregate-publish.yml`).

Enthalten sind nur Tagessummen (Clones/Views, gesamt und unique). Keine
Referrer, keine Pfade, keine Rohdaten, keine Tokens.
