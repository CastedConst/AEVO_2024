

# Administratorisches

Der Prüfungstermin ist am 10.07.2024
Uhrzeit ist 9:30. Um 10:00 bin ich "Azubi" von Dennis

Die Generalprobe ist am 24.06.2024

# Zielgruppe

Auszubildender im ersten Lehrjahr, 2. Monat

Früherer zerspanungsmechaniker, anfang dreißig.

Weitere Ausbildung als Fachinformatiker, da er aufgrund einer Verletzung an der Hand nicht mehr als Mechaniker arbeiten kann.

Der Auszubildende ist sehr interessiert und engagiert. Er ist ein eher Visueller Lerntyp.


# Ausbildungsziel

## Richtlernziel
Konzipieren und Umsetzen von kundenspezifischen Softwareanwendungen (§4, Absatz 3, Nummer 1)

## Groblernziel
Vorgehensmodelle und -methoden sowie Entwicklungsumgebungen und -bibliotheken auswählen und einsetzen

## Feinlernziel

Der Auszubildende kennt die Rolle "Product Owner" aus dem vorgehensmodel "Scrum". Er kann die Rolle im Unternehmen verorten und kennt die ihm zugrundelegende Philosophie.

## Ablauf

### Begrüßung

- Hi Dennis
- Wie gehts dir?
  - `Du hast mir ja erzählt, dass du Fußball schauen wolltest`

### Kontext

- Nachdem du im ersten Monat ja viele Schulungen hattest, hast du ja jetzt schon ein bisschen Abteilungs-Luft geschnuppert und kleine Programmieraufgaben übernommen.
- Was ist dein Eindruck bisher? [`aktivieren`]
  - Hat's gut funktioniert?
  - Hat's spaß gemacht?
- Habe von Dirk deinem fachlichen Betreuer auch gehört, dass das sehr gut funktioniert hat, und du starkes analytisches Denken hast. Reskpekt
- Erinnerst du dich daran, dass wir im Bewerbungsgespräch darüber gesprochen haben, dass programmieren nur ein kleiner teil des Berufs ist?
- Mit dem Einblick den du jetzt bekommen hast würde ich dir gerne noch mehr Theoretisches Handwerkszeug geben, damit du nicht nur weißt wie etwas als Fachinformatiker gemacht wird, sonder auch **warum** es in der Form gemacht wird.

### Hinleitung

- Hast du dich schonmal gefragt woher Dirk weiß, was ihr programmieren sollt? [`Kartenabfrage?`] [`Kohle kommt von extern (Purpose)`]
  - Denkt er sich das selber aus?
  - Was könnten denn Quellen sein die wir verwenden können?
    - "Innovation"
      - Startup
      - Selten
    - Marktanalyse
      - Konkurrenten-Analyse
      - Kundenanforderungen
      - Partner-Unternehmen
    - Portfolio-Management
- Start: Die Firma als "Black Box"
  - Wo verortest du die einzelnen Punkte?
  - Innovation:
    - Kundenmeldungen?
    - Experten f. deutsches Steuersystem?
    - OAuth, CI/CD, ... [`outlook`]
    - Wenn du ne coole Idee für einen Button hast, meldest du dich bei der Planungs-Abteilung?
      - Hat ja keine Impact für die strategische Ausrichtung des Produkts.
      - Hat eine großen Impact für die qualität des Produkts, aber nicht für die strategische Ausrichtung.
      - Selber einbauen! Lokal in der Abteilung
      - Übrigens: Eine der Sachen die ich an der SW-Entwicklung so Mega finde: Man hat impact und gestalltungsfreiraum [`Motivation`]

### Hauptteil

- So, jetzt prasseln von 10 verschiedene stellen Anforderungen auf die Abteilung ein. Ich hab hier mal ein paar mitgebracht
  
  - After a task completes, the results are displayed only after 20 minutes delay
  - Link for navigating from screen A to screen B is broken
  - There should be a task management which allows the user to control the utilization of the system. The user should be able to display, pause, stop and resume tasks
  - We may write an email integration, so that if a task fails, the user gets notified imediately

- Wie entscheiden wir jetzt was wir als nächstes machen? [`Brainstorming`]

  - Link is broken? -> Bug ("funktional") [`outlook`]
    - Sofort! Prio "very high"
  - 20 Minuten Delay? -> Bug ("non-functional")[`outlook`]
    - Sofort! Prio "high"
  - Task Management
    - "Hier Dennis mach mal"
    - UX, API, Stop, Pause? [`Brainstorming`?]
    - Zu groß. Das ist ein "Epic", oder "Initiative"
    - 2 Wichtige Dinge: Herunterbrechen & Spezifieren "refine" [`outlook`]
    - Erster Annäherung:
      - Display Tasks (High prio)
      - Stop Tasks
      - ...
  - Email notification
    - Nette geschichte, aber wichtig? ("Medium")

Das Ergebnis: "Backlog"

Macht Klaus das alleine?
- Nö, redet mit vielen
  - Program Management
  - Entwicklern
  - Nachbarabteilungen und Teams

Was macht er noch?
- Yay or Nay: Abnahme
  - Kontrolliert die Produkt-Standards
- Kontrolliert die strategische Ausrichtung des Produkts

Wichtiger: Was macht er nicht?
- Sagen **wie** etwas gemacht wird (technologie kein impact auf webseite)
- Personen zuweisen ("Die wichtigen Sachen macht sibylle") förderung
- Timelines vorgeben
  - Magisches Dreieck
    - Zeit, Funktionen, Resourcen
    - "alles, und zwar gleich" - bulls statement [`Praxistransfer`]
    - Agile Methode
  - Das Team gibt das Commitment über die Zeit ab!

### Phase-out

Was für Fragen hast du noch zur Rolle des PO?


Ok, dann hab ne Frage: Zusammenfassend, was ist die Rolle eines POs? [`Lernerfolgskontrolle`]

* Managed Anforderungen
  * Rafiniert und Priorisiert sie
* Verantwortet das Backlog
* Abnahme von entwickelten Funktionen

Nicht:
* Wie etwas gemacht wird
* Bis wann etwas gemacht wird
* Personen zuweisen

### Schluss

Mega!
Super wie du das abgerufen hast.

Schreib das bitte in dein Berichtsheft `Lernerfolgssicherung`, ich werd dass dann bei unserem nächsten Treffen am Montag unterschreiben.

Wir werden uns noch ein paar mal mit dem Thema beschäftigen, welche anderen Rollen es gibt und wie man das Ding als ganzes nennt, welche alternativen es gibt etc. `Lernerfolgssicherung`

Du kannst gerne noch tiefer gehend im Internet reherchieren, aber mir ist es wichtiger, dass du dir die Kernpunkte über die wir geredet haben einprägst und live beobachtest wie das in der Fachabteilung gelebt wird.

Es ist wichtig zu wissen welche Rollen es gibt und wo sie aufhören, damit man konfliktfrei und effizient miteinander arbeiten kann ... was dann in Summe auch mehr Spaß macht.

Ich muss jetzt leider weiter, ich hab noch ein Meeting mit der IHK, ich wünsch dir frohes schaffen! `Exit strategie`

