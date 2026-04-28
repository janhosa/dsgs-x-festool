# DSGS × Festool — Pitch Landing Page

## Struktur

```
index.html
assets/
  logo-round.png
media/
  jan-philipp.png
  story-jigsaw.jpg
  kurs-bohrer.jpg
  kurs-saege.jpg
  kurs-schleifer.jpg
  festool-systainer.jpg
  festool-oberfraese.jpg
  teamworkshop-verbund.mp4    ← bitte selbst hochladen
  kids-sommercamp.mp4         ← bitte selbst hochladen
```

## Videos

Die zwei MP4-Dateien (Teamworkshop Verbund + Kids Sommercamp) gehören in
`/media/` — die Dateinamen müssen exakt sein:

- `media/teamworkshop-verbund.mp4`
- `media/kids-sommercamp.mp4`

Solange die Videos noch nicht hochgeladen sind, zeigen die Browser ein
Poster-Bild als Fallback — die Seite ist also nie broken.

## Deployment

Funktioniert direkt auf GitHub Pages, Netlify, Vercel etc. — keine Build-Tools nötig.
