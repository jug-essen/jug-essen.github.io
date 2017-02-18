---
event_date: 2017-04-26
title: "Datenbankzentrische­ Anwendungen mit Spring Boot und jOOQ "
type: Vortrag
speakers:
- michael.simons
location: opitzconsulting
meetup_id: 237310562
---
In diesem Vortrag wird eine Variante datenbankzentrischer Anwendungen mit einer modernen Architektur vorgestellt, die sowohl in einer klassischen Verteilung als auch "cloud native" genutzt werden kann und dabei eine sehr direkte Interaktion mit Datenbanken erlaubt. jOOQ ist eine von vielen Möglichkeiten, Datenbankzugriff in Java zu realisieren, aber weder eine Objektrelationale Abbildung (ORM) noch "Plain SQL", sondern eine typsichere Umsetzung aktueller SQL Standards in Java. jOOQ "schützt" den Entwickler nicht vor SQL Code, sondern unterstützt ihn dabei, typsicher Abfragen in Java zu schreiben. Spring Boot setzt seit 2 Jahren neue Standards im Bereich der Anwendungsentwicklung mit dem Spring Framework. Waren vor wenigen Jahren noch aufwändige XML Konfigurationen notwendig, ersetzen heute "opinionated defaults" manuelle Konfiguration. Eine vollständige Spring Boot Anwendung passt mittlerweile in einen Tweet. Der Autor setzt die Kombination beider Technologien erfolgreich zur Migration einer bestehenden, komplexen Oracle Forms Client Server Anwendung mit zahlreichen Tabellen und PL/SQL Stored Procedures hinzu einer modernen Architektur ein. Das Projekt profitiert sehr davon, die Datenbankstrukturen nicht in einen ORM "zu zwängen". Der Vortrag demonstriert, wie Spring Boot genutzt wird, um den Kontext für jOOQ vorzubereiten (Datenbankverbindung, Transaktionen etc.) und anschließend fortgeschrittene, analytische Abfragen als HTTP apis zu veröffentlichen. Auf dem Weg dorthin wird ebenfalls über Datenbankmigrationen gesprochen und wie auch an dieser Stelle die Magie von Spring Boot eingesetzt werden kann, um Entwicklungs-, Test- und Produktivdatenbanken synchron zu halten.  
