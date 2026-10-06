# RR Coach

Trainings-App für die [Recommended Routine](https://www.reddit.com/r/bodyweightfitness/wiki/kb/recommended_routine) aus r/bodyweightfitness. Läuft als Progressive Web App direkt im Browser, lässt sich auf dem Smartphone installieren und funktioniert nach dem ersten Aufruf auch offline.

**Live:** https://voccawind.github.io/rrcoach/

## Dank

Die Recommended Routine stammt von der Community [r/bodyweightfitness](https://www.reddit.com/r/bodyweightfitness/), die sie frei und kostenlos für alle zugänglich macht. Besonderer Dank an [Antranik Kizirian](https://antranik.org/), der die Routine mit seinem ausführlichen Erklärvideo und [seiner Seite zur RR](https://antranik.org/rr/) für unzählige Menschen verständlich gemacht hat. Diese App ist ein unabhängiges Hobbyprojekt und steht in keiner Verbindung zu r/bodyweightfitness oder Antranik.

## Installation auf dem Smartphone

- **iPhone (Safari):** Seite öffnen, Teilen-Symbol, „Zum Home-Bildschirm“.
- **Android (Chrome):** Seite öffnen, Menü, „App installieren“ bzw. „Zum Startbildschirm hinzufügen“.

## Aufbau

Reine statische Seite ohne Build-Schritt:

| Datei | Zweck |
|---|---|
| `index.html` | Komplette App (HTML, CSS, JavaScript, eingebettete Schriften) |
| `sw.js` | Service Worker, network-first mit Offline-Fallback |
| `manifest.webmanifest` | PWA-Manifest |
| `*.png` | App-Icons |

## Lizenz

Der Quellcode dieses Projekts ist öffentlich einsehbar, aber **nicht Open Source** im Sinne der Open-Source-Definition. Er steht unter der [PolyForm Noncommercial License 1.0.0](LICENSE.md).

**Erlaubt** ist die nichtkommerzielle Nutzung, insbesondere:

- private Nutzung, Hobbyprojekte, Lernen und Forschung
- Anpassen, Verändern und Weitergeben des Codes, solange der Zweck nichtkommerziell bleibt
- Nutzung durch gemeinnützige Organisationen, Bildungseinrichtungen, öffentliche Forschungseinrichtungen und Behörden

**Nicht erlaubt** ist jede kommerzielle Nutzung, zum Beispiel der Einsatz in kostenpflichtigen Apps oder Diensten, in Coaching- oder Trainingsangeboten gegen Bezahlung oder als Bestandteil eines Produkts.

Wer den Code weitergibt, muss den Lizenztext (oder den Link darauf) sowie den folgenden Hinweis mitliefern:

```
Required Notice: Copyright (c) 2026 Benjamin Apel
```

**Kommerzielle Lizenz:** Für eine kommerzielle Nutzung kann eine separate Lizenz vereinbart werden. Anfragen bitte über ein [Issue](https://github.com/voccawind/rrcoach/issues) in diesem Repository.

### Inhalte Dritter

Folgende Bestandteile stammen nicht von mir und unterliegen ihren eigenen Lizenzen:

- **Schriftart Sora**, Copyright 2019 The Sora Project Authors, SIL Open Font License 1.1
- **Schriftart Manrope**, Copyright 2019 The Manrope Project Authors, SIL Open Font License 1.1

Beide Schriften sind in `index.html` eingebettet. Copyright-Hinweise und vollständiger Lizenztext stehen in [FONTS-LICENSE.txt](FONTS-LICENSE.txt). Verlinkte Videos und externe Seiten sind nicht Teil dieses Repositorys.

---

## License (English)

The source code of this project is publicly available but **not open source**. It is licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE.md).

Noncommercial use, modification and redistribution are permitted, including personal use, hobby projects, study, research and use by charitable, educational, public research and government organizations. Any commercial use is prohibited.

A separate commercial license is available on request via an [issue](https://github.com/voccawind/rrcoach/issues) in this repository.

The embedded fonts Sora and Manrope are licensed under the SIL Open Font License 1.1, see [FONTS-LICENSE.txt](FONTS-LICENSE.txt).
