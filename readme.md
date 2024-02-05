# Email-App

Dieser Code implementiert eine einfache E-Mail-Verwaltungsanwendung und besteht aus zwei Java-Klassen, Email und EmailApp.
Die Hauptfunktionen umfassen das Erstellen von E-Mail-Adressen für neue Mitarbeiter, das Festlegen von Abteilungen, das Generieren von zufälligen Passwörtern, das Verwalten von Postfachkapazitäten und das Festlegen alternativer E-Mails.
Der Code demonstriert grundlegende OOP-Prinzipien in Java, einschließlich Kapselung durch private Felder, Konstruktoren zur Initialisierung von Objekten, und Methoden zur Interaktion mit den Objekteigenschafte

# Email Klasse

- Konstruktor: Nimmt den Vor- und Nachnamen des Mitarbeiters entgegen und verwendet diese, um eine E-Mail-Adresse zu generieren.

- Abteilungswahl: Fragt den Benutzer nach einer Abteilung (Vertrieb, Entwicklung, Buchhaltung oder keine) und verwendet die Auswahl, um die E-Mail-Adresse zu vervollständigen.
- Passwortgenerierung: Generiert ein zufälliges Passwort mit einer vorgegebenen Länge.
- E-Mail-Generierung: Kombiniert den Namen des Mitarbeiters, die gewählte Abteilung und einen Firmensuffix, um eine E-Mail-Adresse zu erstellen.
  Postfachkapazität: Setzt und holt die Postfachkapazität.

- Alternative E-Mail: Ermöglicht das Setzen und Abrufen einer alternativen E-Mail-Adresse.

- Passwortänderung: Ermöglicht das Ändern des Passworts.

- Info anzeigen: Zeigt die Informationen des Mitarbeiters, einschließlich des Namens, der E-Mail-Adresse und der Postfachkapazität an.
