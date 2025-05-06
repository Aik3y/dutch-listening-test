# dutch-listening-test
README – Luistertoets uitbreiden

📁 Structuur:
- index.html            → De toetspagina
- opdrachten.js         → Bevat alle opdrachten (audio + vragen)
- audio/                → Map met alle mp3-bestanden
- luisterscripts.txt    → Alle scripts overzichtelijk op niveau

➕ Zelf een opdracht toevoegen:
1. Voeg een mp3 toe in de audio-map, bijvoorbeeld: audio/51_winkel.mp3
2. Voeg een blok toe aan opdrachten.js, bijvoorbeeld:

{
  audio: "audio/51_winkel.mp3",
  niveau: "makkelijk",  // of 'gemiddeld' of 'moeilijk'
  script: "Karin koopt brood bij de bakker.",
  vragen: [
    { vraag: "Wat koopt Karin?", antwoord: "brood" },
    { vraag: "Waar is Karin?", antwoord: "bakker" },
    { vraag: "Wat doet Karin?", antwoord: "kopen" }
  ]
}
