# 👋 Moin, ich bin Mario

### Java Backend · Spring Boot · Python · Cloud · Softwarearchitektur

Ich studiere **Angewandte Informatik an der HAW Hamburg** und stehe kurz vor meinem Bachelorabschluss.

Parallel entwickle und betreue ich bei **one.O innerhalb der Otto Group** produktive Anwendungen und Webcrawler mit **Java, Spring und Spring Boot**. Dabei arbeite ich unter anderem mit bestehenden Codebasen, Schnittstellen, Cloud-Infrastruktur, Docker, Linux, CI/CD und Monitoring.

Mein beruflicher Schwerpunkt liegt auf **Backend-Entwicklung mit Java und Spring Boot**.  
In meinen eigenen Projekten beschäftige ich mich aktuell verstärkt mit **Python, Cloud-Architekturen, verteilten Systemen, Automatisierung und Softwarearchitektur**.

---

## 👨‍💻 Über mich

- 💼 Praktische Erfahrung mit produktiven **Java-/Spring-Boot-Anwendungen**
- ☁️ Berufliche Cloud-Praxis mit **Google Cloud Platform**
- 🐳 Erfahrung mit **Docker, Linux und CI/CD**
- 🐍 Aktuell vertiefe ich gezielt meine Kenntnisse in **Python und FastAPI**
- 🏗️ Interesse an **Softwarearchitektur, verteilten und event-getriebenen Systemen**
- 🔐 Bei eigenen Projekten spielen **Security und Privacy by Design** eine wichtige Rolle
- 🎓 B.Sc. Angewandte Informatik – Abschluss voraussichtlich 2026
- 📍 Hamburg

---

## 🛠️ Technologien

### Beruflicher Schwerpunkt

`Java` · `Spring` · `Spring Boot` · `REST APIs` · `JUnit`

### Cloud & DevOps

`GCP` · `Docker` · `Linux` · `GitLab CI/CD` · `Git` · `Maven`

### Daten & Monitoring

`SQL` · `Google BigQuery` · `Grafana` · `Cloud Logging` · `JSON` · `XML`

### Aktuell im Fokus

`Python` · `FastAPI` · `AWS` · `Terraform` · `Kafka` · `DynamoDB`

### Weitere Erfahrung

`TypeScript` · `JavaScript` · `Angular` · `GitHub` · `Jira` · `Confluence`

---

# 🚀 Projekte

Meine öffentlichen Projekte nutze ich vor allem, um Technologien und Architekturkonzepte außerhalb meines beruflichen Java-/Spring-Schwerpunkts praktisch umzusetzen.

## 🏠 HomeFlow

**Local-first Smart-Home-Gateway mit einer einheitlichen API für unterschiedliche Geräte und Hersteller.**

HomeFlow entstand aus der Idee, Geräte wie Pool, Beleuchtung, Lautsprecher, Türschloss oder Haushaltsgeräte nicht über zahlreiche Hersteller-Apps, sondern über eine gemeinsame Schnittstelle und Anwendung zu steuern.

### Schwerpunkte

- Python + FastAPI
- REST API und WebSockets
- Adapterbasierte Integration unterschiedlicher Geräte
- Local-first Architektur
- Security & Privacy by Design
- Authentifizierung und Autorisierung
- Auditierung und Rate Limiting
- Docker
- automatisierte Tests
- Architekturentscheidungen über ADRs dokumentiert

Die erste reale Geräteintegration steuert einen **Bestway AirJet Pool lokal über dessen Netzwerkprotokoll**. Weitere Geräte werden über eine einheitliche Domain- und Capability-Struktur abstrahiert.

**Technologien:**  
`Python` · `FastAPI` · `WebSockets` · `Docker` · `pytest` · `Pyright` · `Ruff`

[→ HomeFlow Repository](/mariohansen/homeflow)

---

## 🔎 JobRadar

**Event-getriebene Pipeline zur automatisierten Suche, Filterung und Verwaltung von Stellenanzeigen.**

JobRadar sammelt Stellenanzeigen aus mehreren Quellen, normalisiert und dedupliziert sie, bewertet sie anhand eines Fähigkeitsprofils und verschickt passende Ergebnisse automatisiert per E-Mail.

Zusätzlich verwaltet ein Tracker Bewerbungen und ermöglicht die spätere Auswertung der Ergebnisse.

### Architektur

```text
Stellenbörsen
     │
     ▼
 AWS Lambda
     │
     ▼
   Kafka
     │
     ▼
Filter & Deduplizierung
  │             │
  ▼             ▼
DynamoDB        S3
     │
     ▼
   Kafka
     │
     ▼
 Notifier
     │
     ▼
  AWS SES
```

## 🎯 Wohin ich mich entwickeln möchte

Für meinen Berufseinstieg möchte ich meinen Schwerpunkt auf **Backend- und Softwareentwicklung mit Java/Spring Boot** weiter ausbauen.

Besonders interessieren mich Systeme, bei denen Entwicklung nicht bei der Implementierung eines Features endet, sondern auch Themen wie

`Architektur` · `Cloud` · `Betrieb`

eine Rolle spielen.

Gleichzeitig baue ich **Python** aktuell gezielt als zweite Backend-Sprache aus.

---

## 📫 Kontakt

Für berufliche Anfragen oder Fragen zu meinen Projekten erreichst du mich gerne per E-Mail:

📧 **[mariohansen@live.de](mailto:mariohansen@live.de)**  
📍 Hamburg
