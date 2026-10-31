# Mathe-Schreck

Eine kleine, datensparsame GitHub-Pages-Seite zum Rendern von LaTeX-Matheaufgaben im Browser.

## Unterstützte Inhalte

- Formeln, Brüche, Integrale, Matrizen und Umformungen über MathJax
- 2D-Funktionsgraphen aus häufigem PGFPlots-Code mit `\\addplot`
- vollständige PGFPlots-Dokumente mit Präambel, mehreren `\\addplot3`-Elementen und parametrischen Geraden
- Beispiele für Matrix, Parabel und 3D-Ebenen mit Schnittgerade im Auswahlmenü

Bei TikZ/PGFPlots-Code wird die Grafik direkt an ihrer Stelle im Lösungstext angezeigt. Präambel, Kommentare und Dokument-Umgebungen werden beim Darstellen automatisch ignoriert. Mehrere 3D-Flächen, parametrische Geraden und einfache `\\node`-Beschriftungen werden gemeinsam dargestellt. Die Eingabe selbst bleibt unverändert und kann weiterhin als Link geteilt werden.

## Lokal testen

Die Datei `index.html` kann direkt geöffnet werden. Für den vollständigen Betrieb ist eine Internetverbindung nötig, weil MathJax und Plotly von jsDelivr bzw. cdn.plot.ly geladen werden.

## GitHub Pages

1. Repository auf GitHub anlegen und diese Dateien hochladen.
2. Unter **Settings → Pages** die Veröffentlichung aus dem Branch `main` und dem Verzeichnis `/ (root)` aktivieren.
3. Die von GitHub angezeigte Pages-Adresse an Schüler weitergeben.

Es werden keine Eingaben an einen Server gesendet. Entwürfe werden nur lokal im Browser gespeichert. Ein über „Link kopieren“ erzeugter Link enthält den LaTeX-Code in seinem Fragment (`#...`).
