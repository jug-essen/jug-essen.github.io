---
event_date: 2017-11-14
title: "Orchestrierung von Microservices"
type: Vortrag
speakers:
- bernd.ruecker
location: opitzconsulting
meetup_id: 243167834
material_url:
---
Der Trend geht klar zu (Micro-)services und komplexen verteilten Systemen. Aber wie kann aus einem Haufen Services ein technisch funktionierender "Flow" entstehen, der einen übergreifenden fachlichen Geschäftsprozess abbildet? Welche Probleme bringen rein event-getriebene Systeme mit sich? Welche Art der Kollaboration zwischen den Services ist erwünscht? Wie können besonders lang laufende Prozesse berücksichtigt werden? Wie kann ich fachliche Transaktionen ohne Two-Phase-Commit – aber mit dem Saga Pattern umsetzen? Was bedeutet all dies für uns, die Entwickler?

In diesem Vortrag werden ich anhand einer Beispielanwendung (verfügbar auf GitHub) und Live-Hacking zeigen, wie eine sinnvolle Architektur aufgebaut werden kann. Dazu verwende ich Java, Spring Boot, Apache Kafka und Camunda. Ich zeige Limitierungen rein ereignisbasierter Architekturen auf und diskutiere Kopplung. Ich beschreiben die Auswirkung verschiedener Lösungsvarianten auf die Änderbarkeit des Gesamtsystems. Außerdem zeige ich warum die Einführung einer leichtgewichtigen Zustandsmaschine keinesfalls zentrale Steuerung bedeuten muss. Der Vortrag ist gespickt mit Praxiserfahrungen aus realen Kundenprojekten.