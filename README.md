[LIESMICH.txt](https://github.com/user-attachments/files/32701124/LIESMICH.txt)
RAID & RESCUE – Operation Nachtfalke (Browser-Edition)
======================================================

Spielen
-------
index.html per Doppelklick im Browser öffnen (Chrome, Edge, Firefox, Safari).
Keine Installation nötig. Ton startet nach dem ersten Klick.

Online-Duell (Stufe 4)
----------------------
1. Beide Spieler öffnen das Spiel (Datei oder gehostete Seite).
2. Spieler 1: Hauptmenü → "Duell zu zweit" → "Raum erstellen". Es erscheint ein
   vierstelliger Code.
3. Spieler 2: "Duell zu zweit" → Code eingeben → "Beitreten".
4. Sobald Spieler 1 "Mitspieler ist da" sieht: "Duell starten".
Die Verbindung läuft direkt zwischen den Browsern (WebRTC über den freien
PeerJS-Vermittlungsdienst). Beide brauchen Internet. In sehr restriktiven
Firmennetzen kann WebRTC blockiert sein.
"Lokal in zwei Tabs testen" verbindet zwei Tabs desselben Browsers (ohne Internet,
funktioniert zuverlässig über eine gehostete Seite, nicht immer per Doppelklick).

Auf einen statischen Hoster laden
---------------------------------
Den Ordner (index.html + diese Datei) z. B. bei Netlify (Drag & Drop auf
app.netlify.com/drop) oder GitHub Pages hochladen – fertig.

Steuerung
---------
Pfeiltasten / Maus: fliegen · J / linke Maustaste: MG · I, V / rechte Maustaste: Bombe
B, K, Strg / mittlere Maustaste: Lenkrakete · F, L, Shift / Mausrad: wenden
Leertaste: absetzen / Fallschirm · 1–0 bzw. T A M E D U P R G H: kaufen · Esc: Pause
