# Darttrainer

Dagelijkse darttraining met als doel Q-School: dagplan op je zwakste punt, Just Darts-oefeningen (Erik Clarys), Q-School-metingen, wedstrijden, statistieken en een coach.

## Op GitHub Pages zetten

1. Maak een repository (bijvoorbeeld `darttrainer`) of open je bestaande.
2. Zet alle bestanden uit deze map in de hoofdmap van de repository (ook de map `fonts`).
3. Ga naar **Settings → Pages**, kies **Deploy from a branch**, branch `main`, map `/ (root)`, en bewaar.
4. Na een minuut staat de app op `https://<jouw-naam>.github.io/darttrainer/`.
5. Open die link in Safari en kies **Deel → Zet op beginscherm**.

Een nieuwe versie zetten: vervang `index.html` en verhoog `VERSION` in `sw.js`.

## Je scores meenemen

- **Vanuit de Claude-versie:** Cijfers → *Back-up kopiëren*, en op de GitHub-versie *Plakken en samenvoegen*.
- **Tussen toestellen:** Vandaag → *Toestellen koppelen* (via een GitHub-sleutel met `gist`-rechten). Je coachgesprekken gaan mee.

## De coach

De coach zit in de app zelf: geen AI, geen API-sleutel, geen kosten, en hij werkt zonder internet. Hij rekent met jouw resultaten en beantwoordt onder meer:

- wat je vandaag of morgen traint, en waarom (met meetbare doelen)
- een weekplan dat je zwakste punt het vaakst traint
- hoe ver je van Q-School bent, met je tempo per week en een verwachting
- dubbels (ook een specifieke dubbel, zoals D16), scoren en uitgooien
- finish-routes ("hoe gooi ik 87 uit?") en bogey-getallen
- vastzitten, vooruitgang, techniek, zenuwen, wedstrijden en rust

Elke dag staat bovenaan een kort "Coach zegt". Vragen en antwoorden worden bewaard en gaan mee met het koppelen van toestellen.
