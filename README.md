# Benji-Fit

Een fitness-app met Benji. Eén pagina, geen server nodig.

## Zetten op GitHub Pages
1. Maak op github.com een nieuwe **publieke** repository, bijvoorbeeld `benji-fit`.
2. Kies **Add file > Upload files** en sleep ALLE bestanden uit deze map erin (index.html, manifest.webmanifest, sw.js en de icon-bestanden). Klik op **Commit changes**.
3. Ga naar **Settings > Pages**. Kies bij Source: *Deploy from a branch*, branch `main`, map `/ (root)`. Opslaan.
4. Na een minuut staat de app op `https://JOUWNAAM.github.io/benji-fit/`.

## Op je telefoon
- iPhone: open de link in **Safari**, tik op Delen en kies **Zet op beginscherm**.
- Android: open de link in **Chrome**, tik op het menu (drie puntjes) en kies **App installeren** of **Toevoegen aan startscherm**.

## Goed om te weten
- Je trainingen en gegevens blijven in de browser van je telefoon. Ze worden niet naar GitHub gestuurd.
- Het vriendenbord werkt alleen in de versie binnen Claude.
- Wil je een nieuwe versie, vervang dan index.html in de repository. Verhoog in sw.js het nummer bij `V` (bijvoorbeeld `benji-fit-v4`), anders blijft je telefoon de oude versie tonen.
