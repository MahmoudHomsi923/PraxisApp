# PraxisApp

Projektbeschreibung: Offline-fähige Dokumentations-App für Praxen und Hausbesuche

Dieses Projekt wurde im Rahmen eines UX-Design-Zertifizierungskurses von Google auf der Coursera-Plattform entwickelt. Das Ziel war es, eine benutzerzentrierte Anwendung zu entwerfen und zu implementieren, die es medizinischem Fachpersonal ermöglicht, Patientendaten sowohl offline als auch online zu dokumentieren – insbesondere in Umgebungen mit instabiler oder fehlender Internetverbindung, wie z. B. bei Hausbesuchen.
Projektumfang

Das Projekt wurde von Grund auf selbstständig entwickelt, einschließlich der Idee, des Designs und der Implementierung. Die folgenden UX-Design-Phasen und -Artefakte wurden erstellt:

- Nutzerforschung: Interviews mit potenziellen Nutzern, um deren Bedürfnisse und Herausforderungen zu verstehen.

- User Journeys & User Stories: Detaillierte Beschreibungen der Nutzererfahrungen und Anwendungsfälle.

- Personas: Repräsentative Nutzerprofile, um die Zielgruppe besser zu verstehen.

- Problem Statement & Hypothesis: Klare Definition des Problems und Hypothesen zur Lösung.

- Storyboard: Visuelle Darstellung des Nutzerflusses.

- Wireframes & Prototypen: Low- und High-Fidelity-Prototypen zur Visualisierung des Designs.

- Mockups: Hochwertige Design-Vorlagen für die finale Benutzeroberfläche.

Technische Umsetzung

Die Anwendung wurde als Blazor Hybrid Desktop Application entwickelt, um eine responsive Design-Erfahrung zu gewährleisten. Die Wahl von Blazor Hybrid ermöglicht es, eine plattformübergreifende Anwendung zu erstellen, die sowohl auf Desktop- als auch auf mobilen Geräten läuft. Die Vorteile von Blazor Hybrid liegen in der Nutzung von Webtechnologien (HTML, CSS, C#) für eine einheitliche Codebase, die gleichzeitig native Funktionen unterstützt.

Für die Offline-Datenspeicherung wurde SQLite verwendet, um eine zuverlässige lokale Speicherung der Daten zu gewährleisten. Für die Online-Synchronisation und Datenspeicherung wurde eine REST-API mit einer zentralen Datenbank entwickelt. Der Quellcode für die API und die Datenbank ist ebenfalls in der Repository PraxisWebApi verfügbar.

Funktionen

- Offline-Dokumentation: Ermöglicht die Datenerfassung auch ohne Internetverbindung.

- Online-Synchronisation: Automatische Synchronisation der Daten, sobald eine Internetverbindung verfügbar ist.

- Responsive Design: Optimierte Benutzeroberfläche für verschiedene Bildschirmgrößen.

- Benutzerfreundlichkeit: Intuitive Navigation und klare Struktur für eine effiziente Nutzung.

Warum Blazor Hybrid?

Blazor Hybrid bietet die Möglichkeit, moderne Webtechnologien mit nativen Desktop-Funktionen zu kombinieren. Dies ermöglicht:

- Einheitliche Codebase: Reduzierung des Entwicklungsaufwands durch Wiederverwendung von Code.

- Plattformübergreifende Kompatibilität: Unterstützung für Windows, macOS und mobile Geräte.

- Native Leistung: Direkter Zugriff auf native APIs und Hardware-Funktionen.

Repository-Inhalt
