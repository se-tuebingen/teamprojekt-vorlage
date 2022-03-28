# Anforderungen im Teamprojekt
In diesem Dokument beschreiben wir, was wir von Euch als TeilnehmerInnen des Teamprojektes erwarten.
Dieses Dokument ist aus der Sicht der universitären Betreuung (der TutorInnen / BetreuerInnen) geschrieben.

## Selbstorganisation

Das Teamprojekt ist wie ein Planspiel. Ihr seid ein Startup und das ist Euer
erstes Kundenprojekt. D.h. die allermeisten Entscheidungen liegen bei Euch.

Ihr habt die gemeinschaftliche Verantwortung dafür, dass das Projekt ein Erfolg wird.
D.h. Ihr trefft gemeinschaftlich Entscheidungen (z.B. was den Entwicklungsprozess betrifft).
Ihr habt aber auch Individualverantwortung: Aufgaben selbstständig zu bearbeiten, zu lernen und zu präsentieren.

## Anforderungen an das Produkt
Ihr seid dafür verantwortlich die Anforderungen an das Produkt im Gespräch mit uns und evtl. anderen Beteiligten selbst zu ermitteln. Anforderungen können anfangs unklar sein und sich evtl. im Verlauf ändern.

**Wichtig**: das "Produkt" hier ist sowohl eine ausführbare Datei, als auch der Source Code in entsprechender Qualität.

Euer Ziel ist es den Wert des Produktes für den Kunden (d.h. "uns", die univ. Betreuung) zu maximieren.

## Anforderungen an den Entwicklungsprozess
Die organisatorischen Rahmenbedingungen sind wie folgt.
Alle zwei Wochen findet ein Treffen aller Beteiligten statt (1,5-2h).
Dieses Treffen ist grob in drei Teile geteilt:

#### 1. Review (30min)
- ihr präsentiert das **Produkt**, welches in den vergangenen zwei Wochen entwickelt wurde
- nur fertige Features werden vorgestellt (siehe "Technische Prozessanforderungen")
- das Produkt kann potentielle "ausgeliefert" werden

#### 2. Retrospektive (30min)
- wir überlegen gemeinsam, wie ihr den Prozess verbessern könntet
- ihr entscheidet und haltet diese Entscheidungen fest

#### 3. Planning (30-45min)
- ihr plant, was die nächsten zwei Wochen entwickelt werden soll
- ihr legt ein konkretes Entwicklungsziel fest

### Was ist dem Team überlassen?
Das obige regelmäßige Treffen, sowie ein paar technische Anforderungen (unten) sind vorgegeben.
Die genaue Ausgestaltung des Projektes obliegt Euch. Als Entscheidungsgrundlage könnt Ihr die
SE Vorlesung, eigene Recherchen, Literatur zu Scrum, sowie Eure eigene Erfahrung nutzen.

Die verschiedenen Teams sind verschieden strukturiert (Größe, Anforderungen der Betreuung, etc.) --
das solltet Ihr natürlich dabei berücksichtigen.

Fragen, die Ihr Euch stellen könntet:
- **Rollenverteilung** (PO / SM / Dev / ...). Gibt es einen bestimmten Product Owner oder Scrum Master? Rotiert diese Rolle, ist sie fest, wird sie teilweise von der Betreuung übernommen? Unabhängig von der Rollenverteilung ist es notwendig zum Bestehen, dass _jede(r)_ TeilnehmerIn aktiv programmiert.
- **Arbeitsaufteilung**. Wie organisieren wir genau die Verteilung der Arbeit? Wer arbeitet wann an welchen Aufgaben?
- **Kommunikation**. Wie kommunizieren wir? Soll es zusätzliche Treffen geben? Wie sind diese Treffen strukturiert?


## Technische Prozessanforderungen
In der Arbeit am Teamprojekt fordern wir **Technische Professionalität**.
Während viele andere Details im Entwicklungsprozess von Euch entschieden werden können, haben wir als Kunden die folgenden Mindestanforderungen an die Entwicklung.

Im Laufe des Projektes können weitere technische Anforderungen hinzukommen. Es ist Eure Aufgabe diese festzuhalten und nicht zu vergessen.

#### Allgemeiner Prozess
- es wird git zur Versionsverwaltung verwendet
- die gemeinsame Entwicklung und der Austausch von Code findet über GitHub statt
- Aufgaben, die in den kommenden zwei Wochen erledigt werden sollen, werden als "Issues" auf GitHub festgehalten
- Aufgaben sind ausreichend dokumentiert, so dass *alle* Beteiligten genau wissen, was sie zu tun hätten
- im Rahmen der Planung (s.o.) wird ein Milestone auf GitHub erstellt; entsprechende Aufgaben werden zugeordnet


#### Einzelne Aufgaben
Es wird der Pullrequest-basierte [GitHub Flow](https://docs.github.com/en/get-started/quickstart/github-flow) verwendet. D.h. insbesondere es wird nicht direkt auf den `main` / `master` branch commmitted.

Eine Aufgabe (Issue) ist erst abgeschlossen, wenn

- es einen entsprechenden Pull Request gibt
- dieser von mindestens einer zweiten Person kontrolliert wurde (code review)
- dieser in `main` / `master` / `dev` (je nach Projekt) gemerged wurde

Abhängig vom Projekt kann das heißen, im Rahmen des Code Reviews muss eventuell ...

- überprüft werden, ob Coding Conventions eingehalten wurden
- getested werden, ob die Funktionalität wie erwartet implementiert ist und sonst keine Fehler eingeführt wurden
- ...

Code Reviews sollen als Kommentare auf GitHub nachvollziehbar dokumentiert werden.
