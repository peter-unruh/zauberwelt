# Zauberwelt – Spiel-App für kleine Kinder (Version 2)

Eine bunte Tipp-Spielwelt ohne Text, ohne Werbung, ohne Datensammlung. Alle Töne und die Musik werden live im Browser erzeugt (eigener kleiner Synthesizer mit Hall). Es werden keine Dateien nachgeladen. Nach dem ersten Aufruf funktioniert die App auch offline.

## Ausprobieren

Die `index.html` funktioniert auch ganz alleine – einfach doppelklicken und im Browser öffnen. Nur App-Installation, Offline-Modus und Kamera brauchen die veröffentlichte HTTPS-Version.

## Veröffentlichen

1. Den kompletten Ordner (`index.html`, `manifest.webmanifest`, `sw.js` und Ordner `icons/`) auf den Webspace hochladen, z. B. nach `https://deine-seite.de/zauberwelt/`.
2. Die Seite muss über **HTTPS** laufen – sonst funktionieren App-Installation, Offline-Modus und Kamera nicht.
3. Nach späteren Änderungen in `sw.js` die Versionsnummer erhöhen (`zauberwelt-v4` → `v5`), damit Geräte die neue Version laden.

## Als App installieren

- **Android / Chrome:** Seite öffnen → Menü → „App installieren“.
- **iPhone / iPad (Safari):** Teilen-Symbol → „Zum Home-Bildschirm“.

## Bedienung für Eltern

- **Haus-Knopf** oben links: zurück zur Startseite.
- **Vollbild-Knopf** oben rechts: Auf der Startseite einmal tippen, in den Welten **dreimal schnell tippen**. Schaltet Vollbild an bzw. aus.
- **Ton-Knopf** oben rechts: Auf der Startseite einmal tippen, in den Welten **dreimal schnell tippen** (damit Kinder ihn nicht aus Versehen auslösen). Er schaltet durch: *Musik + Effekte* → *nur Effekte* → *stumm*. Die Einstellung wird gespeichert.
- Jede Welt hat ihre eigene Hintergrundmusik und eigene Instrumente. Alle Töne, die man antippt, passen automatisch zu den Akkorden der Musik.
- Abends (ab 19 Uhr) wird die Startseite zur Nachtansicht mit Schlaflied-Musik. Je nach Jahreszeit fallen dort Schnee, Blüten oder Blätter.
- Tipp: **Bildschirmfixierung** (Android: „App anheften“, iOS: „Geführter Zugriff“), damit das Kind die App nicht verlässt.

## Datenschutz

Die Kamera wird nur durch bestimmte geheime Gesten eingeschaltet (siehe unten). Der Browser fragt dann vorher um Erlaubnis. Das Bild bleibt ausschließlich auf dem Gerät: Es wird nichts gespeichert oder verschickt. Sobald man die Welt verlässt, geht die Kamera aus.

---

## ⚠️ Spoiler: Alle Geheimnisse

Erst selbst entdecken, dann nachlesen!

**Überall**
- Ab und zu kommt ein Besucher vorbei: Glitzerstern, Einhorn (zieht einen Regenbogen) oder eine Entenfamilie. Antippen!
- **3 Finger gleichzeitig:** Jede Welt hat ihre eigene Überraschung.
- **4 Finger gleichzeitig** oder unten links → unten rechts → unten links → unten rechts tippen: **Disco!**
- Gerät **schütteln** löst in jeder Welt etwas aus.
- Gedrückt halten, Kreise malen und schnell wischen funktioniert fast überall.

**Startseite:** Kachel lange drücken = Vorschau-Drehung. Hintergrund 5× schnell tippen = Konfetti.

**Nacht & Feuerwerk**
- 10 verschiedene Feuerwerke mit eigenen Klängen.
- Himmel **gedrückt halten** = Mega-Rakete aufladen, beim Loslassen riesige Explosion.
- Kreis malen = großes Finale.
- Schnell wischen = eigene Sternschnuppe.
- Mond antippen = er zwinkert. Mond 5× schnell tippen = die Kuh springt über den Mond. Mond gedrückt halten = er schläft ein (antippen weckt ihn).
- Erleuchtete Fenster antippen = jemand schaut heraus.
- Eine Katze läuft manchmal über die Dächer.
- Nach vielen Feuerwerken erscheint ein **Polarlicht**.

**Meer**
- Fisch 3× schnell tippen = Kugelfisch. Qualle 3× tippen = sie teilt sich.
- Krake 5× tippen = Tintenwolke, er verschwindet. Krake gedrückt halten = Umarmung.
- Schatzkiste gedrückt halten = Schatz-Fontäne.
- Wasser gedrückt halten = **Strudel**, der Fische und Blasen einsaugt.
- Kreis malen = Fischschwarm. Schnell wischen = Delfin.
- Ganz oben an der Wasseroberfläche 3× tippen (oder 3 Finger) = **Tiefsee-Modus** mit Anglerfisch und Leuchtplankton.
- Wal 3× tippen = Regenbogen-Fontäne. U-Boot und Krebs sind auch antippbar.

**Wiese**
- Sonne gedrückt halten = **Nacht** mit Glühwürmchen, Grillen und Eule. Mond gedrückt halten = wieder Tag.
- Wiese gedrückt halten = ein **Baum** wächst. Baum antippen = Äpfel fallen.
- Pusteblumen antippen oder drüberwischen.
- Blume 3× tippen = Riesenblume. Blumen singen beim Antippen.
- Wolke antippen = Regen, danach Regenbogen. Wolke 5× tippen = **Schnee**.
- Alle Büsche schnell nacheinander antippen = Tierparty.
- Im Himmel wischen = eine Biene folgt dem Finger. Kreis malen = Schmetterlingstanz. Wischen = Wind.

**Musik**
- Oben Mitte: Instrument wechseln (Xylophon, Klavier, Steeldrum, Marimba, Spieluhr, 8-Bit, Chor, Kalimba) und Rhythmus wechseln (6 Stile inkl. Disco und Marsch).
- Klangstab gedrückt halten = langer Ton, dabei über andere Stäbe gleiten.
- Trommel gedrückt halten = Trommelwirbel.
- Schnell über alle Stäbe wischen = Regenbogen-Glissando.
- **Kinderlieder erkennen:** Die ersten Töne spielen, und die App spielt das Lied zu Ende:
  - *Alle meine Entchen* (1 2 3 4 5 5)
  - *Hänschen klein* (5 3 3 4 2 2)
  - *Morgen kommt der Weihnachtsmann / Twinkle Twinkle* (1 1 5 5 6 6)
  - *Bruder Jakob* (1 2 3 1 1 2)
  - *Kuckuck* (5 3 5 3)
  - Tonleiter hoch = Rakete, Tonleiter runter = Blätterregen
  - (Zahlen = Klangstäbe von groß/links bzw. oben gezählt)
- Kreis malen = automatische Melodie.

**Malen**
- Jede Farbe klingt wie ein anderes Instrument.
- Werkzeuge: Pinsel, Stempel (mit Emojis), Zauberpinsel, **Kaleidoskop** (spiegelt alles 12-fach).
- Einen Kreis malen = er bekommt ein Gesicht.
- Gedrückt halten = Farbklecks wächst.
- 5× auf dieselbe Stelle tippen = gemaltes Feuerwerk. 3 Finger = Farbregen. Schütteln = löschen.
- Seifenblasen-Knopf gedrückt halten = **Neon-Modus** (schwarzes Papier, leuchtende Farben).
- Pinsel-Knopf gedrückt halten = **Selfie** mit Countdown, dann das eigene Foto anmalen.

**Ballons**
- Schnell hintereinander platzen lassen = die Töne steigen wie eine Tonleiter.
- Ballon **gedrückt halten** = er wird aufgepustet bis zum Mega-Knall. Vorher loslassen = er zischt pupsend davon.
- Goldballon = Münzen. Ballon mit Geschenk = ein Spielzeug springt heraus. Sternballon, Herzballon, Regenbogenballon (teilt sich).
- Heißluftballon antippen = Passagier winkt. Ein Vogel pikst manchmal Ballons.
- Wischen = Wind. 3 Finger = Ballonsturm.
- Kreis malen = **Selfie-Ballons** (das eigene Gesicht in den Ballons).

**Weltraum**
- Tippen = Sternbilder. Planeten klingen alle unterschiedlich.
- Leeren Weltraum gedrückt halten = **Schwarzes Loch**, beim Loslassen Urknall mit neuem Sternenhimmel.
- Rakete antippen und ziehen = selbst steuern.
- UFO 3× tippen = es entführt eine Kuh. Astronaut winkt beim Antippen.
- Wischen = Warp-Geschwindigkeit. Kreis malen = Galaxie. 3 Finger = Meteoritenschauer.
- Erde gedrückt halten = **dein Gesicht wird zur Erde** (Kamera).

**Hüpf-Formen**
- Zwei gleiche Formen stoßen zusammen = sie verschmelzen zu einer größeren. Beim dritten Mal: Krone. Danach Explosion!
- Form 5× schnell tippen = sie wird schwindelig.
- Leere Fläche gedrückt halten = **Schwerelosigkeit** an/aus.
- Kreis malen = Wirbelsturm. Wischen = Windstoß. 3 Finger = Trampolin-Boden.
- **Gerät kippen** = die Schwerkraft folgt (auf dem iPhone einmal Bewegungssensor erlauben). Schütteln = alle springen.
