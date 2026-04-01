<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/Thaleon5_Logo_RGB_weiss.png">
    <source media="(prefers-color-scheme: light)" srcset="assets/Thaleon5_Logo_RGB_schwarz.png">
    <img alt="Thaleon5 Logo" src="assets/Thaleon5_Logo_RGB_schwarz_auf_weiss.jpg" width="400">
  </picture>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Sprache-Deutsch-blue" alt="Sprache: Deutsch">
  <img src="https://img.shields.io/badge/Status-Aktiv-brightgreen" alt="Status: Aktiv">
  <img src="https://img.shields.io/badge/Zielgruppe-Makler_%2F_Web--Entwickler-orange" alt="Zielgruppe: Makler / Web-Entwickler">
</p>

# Widget – Einbindungsanleitung

Das **Thaleon5-Widget** ist ein interaktives Online-Formular für den Selbstabschluss der Reiseversicherung. Es wird von der Thaleon5 bereitgestellt und kann von Maklern mit wenigen Handgriffen in jede Website eingebunden werden.

Diese Anleitung richtet sich an Sie als Makler und erklärt, was mit dem Widget-Code zu tun ist, den Sie per E-Mail erhalten haben.

> [!TIP]
> Falls Sie keinen eigenen Zugang zu Ihrer Website haben oder sich mit HTML nicht auskennen, leiten Sie diese Anleitung einfach an Ihren Website-Entwickler weiter. Die Einbindung dauert erfahrungsgemäß nur wenige Minuten.

> [!WARNING]
> **Kein Support durch die Thaleon5:** Die technische Einbindung des Widgets auf Ihrer Website wird von der Thaleon5 **nicht supportet**. Bei Fragen zur Umsetzung wenden Sie sich bitte an Ihren Website-Entwickler.

---

## Inhaltsverzeichnis

- [Was haben Sie erhalten?](#was-haben-sie-erhalten)
- [Was Ihr Website-Entwickler tun muss](#was-ihr-website-entwickler-tun-muss)
  - [Schritt 1 – Ziel-Bereich festlegen](#schritt-1--ziel-bereich-auf-der-website-festlegen)
  - [Schritt 2 – Widget-Code einfügen](#schritt-2--widget-code-aus-der-e-mail-einfügen)
- [Wichtige Hinweise](#wichtige-hinweise)

---

## Was haben Sie erhalten?

In Ihrer E-Mail von der Thaleon5 befindet sich ein **personalisierter Widget-Code**, der bereits vollständig auf Sie als Makler zugeschnitten ist. Dieser Code muss lediglich an der richtigen Stelle in Ihre Website eingefügt werden.

Das Widget selbst ist ein interaktives Online-Formular für den Selbstabschluss der Reiseversicherung. Es wird direkt vom Server geladen und aktuell gehalten – Sie müssen sich um nichts weiter kümmern.

---

## Was Ihr Website-Entwickler tun muss

Leiten Sie diese Anleitung zusammen mit dem Widget-Code aus Ihrer E-Mail an Ihren Entwickler weiter. Die Einbindung besteht aus zwei einfachen Schritten:

### Schritt 1 – Ziel-Bereich auf der Website festlegen

Auf der Seite, auf der das Widget erscheinen soll, muss an der gewünschten Stelle folgender Container eingefügt werden:

```html
<div id="my_widget_div">
    <!-- Hier kommt der Widget-Code aus der E-Mail -->
</div>
```

### Schritt 2 – Widget-Code aus der E-Mail einfügen

Den vollständigen Widget-Code aus der E-Mail **unverändert** innerhalb dieses Containers einfügen. Das war es – das Widget lädt sich danach automatisch.

> [!CAUTION]
> Der Widget-Code darf nicht verändert werden. Er ist personalisiert und eindeutig Ihrem Makler-Konto zugeordnet. Ein Austausch oder eine Weitergabe an andere Personen ist nicht zulässig.

---

## Wichtige Hinweise

- Das Widget funktioniert nur mit dem **original Code aus der E-Mail** – eigene Anpassungen am Code können zu Fehlfunktionen führen.
- Updates und Änderungen am Formular werden automatisch von der Thaleon5 eingespielt, ohne dass Ihre Website angefasst werden muss.
- Die **technische Einbindung wird von der Thaleon5 nicht supportet**. Für Unterstützung wenden Sie sich an Ihren Website-Entwickler oder eine Webdesign-Agentur.
