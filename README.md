# Mani Kouchakian

Informatikstudent an der Frankfurt UAS.

Mich interessiert, wie Geld erfasst und bewegt wird und was dabei mit sensiblen Daten passiert: Zahlungsverkehr, Buchhaltung, Bankinfrastruktur. In diesem Bereich baue ich Backend Systeme.

**Ich suche:** eine Werkstudentenstelle im Bereich Backend / IT in Frankfurt am Main.

---

### Aktuell: Runa

[Runa](https://github.com/manikouchakian/runa) (Java 17) sitzt zwischen Mitarbeitenden und einem Sprachmodell. Namen, E-Mail Adressen, IBANs und Telefonnummern werden durch Platzhalter wie `[IBAN_1]` ersetzt, bevor das Modell den Text sieht. Die Antwort wird danach lokal zurückübersetzt. Ist Runa unsicher, geht nichts raus.

Noch in Arbeit. Die Erkennung steht, gerade kommt der Teil, der die Daten ersetzt.

### Kontor

Eine Projektreihe rund um Geldbewegungen.

| Projekt | Sprache | Inhalt |
|---|---|---|
| [kontor-budget](https://github.com/manikouchakian/kontor-budget) | Python | Budgetverwaltung, Sparquote, Monatsvergleich · `Decimal` statt Fließkomma · 67 Tests, CI |
| [kontor-zins](https://github.com/manikouchakian/kontor-zins) | Java 17 | Tilgungsrechner · `BigDecimal` mit explizitem `RoundingMode` · JUnit 5, CI |
| [kontor-kurs](https://github.com/manikouchakian/kontor-kurs) | Python | EZB Wechselkurse aus CSV importieren, in SQLite speichern, umrechnen |

Außerdem: [Django-Auction-Site](https://github.com/manikouchakian/Django-Auction-Site), eine Auktionsplattform aus dem CS50 Web Kurs. Nach der Abgabe habe ich sie noch einmal überarbeitet: Decimal statt float, Tests für die Fehlerfälle, CI.

*Als Nächstes:* Runa fertig bauen, danach Spring Boot.

### Wie ich arbeite

Bei Geldbeträgen `Decimal` bzw. `BigDecimal`, nie Fließkomma. Unveränderliche Datenmodelle. Berechnung, Validierung und Speicherung getrennt. Tests und CI von Anfang an.

Bei Unsicherheit lieber blockieren als etwas durchrutschen lassen.

Claude Code nutze ich beim Programmieren. Committet wird nur, was ich selbst erklären kann.

### Stack

- **Sprachen:** Java · Python · SQL
- **Werkzeuge:** Git · Maven · JUnit 5 · pytest · GitHub Actions · SQLite · Django
- **Im Aufbau:** Spring Boot, PostgreSQL

### Kontakt

[LinkedIn](https://www.linkedin.com/in/mani-kouchakian) · Manikouchakian@gmail.com

---

<details>
<summary>English</summary>

Computer Science student at Frankfurt UAS.

I'm interested in how money is recorded and moved, and what happens to sensitive data along the way: payments, accounting, banking infrastructure. I build backend systems in that space.

**Currently:** Runa, a Java tool that swaps names, IBANs and phone numbers for placeholders before an AI model sees the text, and sends nothing if it isn't sure.

**Looking for:** a working student position in backend / IT in Frankfurt am Main.

</details>
