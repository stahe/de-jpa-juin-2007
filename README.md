# JPA – Einführung und Implementierung

🔗 **Verwandter Kurs:**
[https://stahe.github.io/de-jpa-juin-2007/](https://stahe.github.io/de-jpa-juin-2007/)

---

## Überblick

Dieses Dokument bietet eine Einführung in die grundlegenden Konzepte der **Datenpersistenz unter Verwendung der JPA (Java Persistence API)**.

Nach dem Studium und dem Ausprobieren der bereitgestellten Beispiele verfügt der Leser über die notwendigen Grundlagen, um JPA selbstständig anzuwenden.

JPA wurde mit **Java 5 (JDK 1.5)** eingeführt und ist Teil einer mehrschichtigen Softwarearchitektur.

---

## Mehrschichtige Architektur

Dieses Dokument basiert auf einer klassischen dreischichtigen Architektur:

* **[ui]** — Benutzeroberfläche (Swing, Konsole, Web)
* **[business]** — Geschäftslogik
* **[DAO]** — Zugriff auf persistente Daten
* **[JDBC]** — Low-Level-Datenbankzugriff

Das Ziel von JPA ist es, die **DAO**-Schicht zu standardisieren und zu vereinfachen.

---

## ORM und Standardisierung

Vor JPA boten Lösungen wie **Hibernate** oder **Toplink** ORM-Mechanismen (Object Relational Mapping) an.

JPA führt eine **Standardspezifikation** ein:

* Die DAO-Ebene kommuniziert über eine **JPA-Schnittstelle**
* Die Implementierung kann Hibernate, Toplink usw. sein.
* Die Geschäftslogik bleibt unabhängig vom ORM-Anbieter

---

## Behandelte Themen

Dieses Dokument behandelt die folgenden Themen:

### 1️⃣ Relationales/Objekt-Mapping

Konfiguration über Java 5-Annotationen zur Verwaltung von:

* **Eins-zu-Eins**-Beziehungen
* **Eins-zu-Viele**-Beziehungen
* **Viele-zu-Viele**-Beziehungen

---

### 2️⃣ Java SE-Umgebung

* Test-Konsolenanwendungen
* Direkte Manipulation der JPA-API
* Einführung in die wichtigsten Methoden (CRUD)
---
### 3️⃣ Erweiterte mehrschichtige Architektur
Integration von:
* **Spring**
* **JBoss EJB3**
Verwendung von:
* Verbindungspools
* Transaktionsmanager
* Abhängigkeitsinjektion
* Annotierte POJOs

---

### 4️⃣ Beispiel einer Webanwendung

Das Dokument schließt mit einer dreistufigen Webanwendung, die Folgendes integriert:

* Web
* Geschäftslogik
* DAO
* JPA
* ORM-Implementierung
* Spring Framework

---

## Lernziele

Dieses Material zielt darauf ab:

* Die Rolle von JPA in einer Unternehmensarchitektur zu verstehen
* Die relationale/objektorientierte Zuordnung zu beherrschen
* JPA in SE- und EE-Umgebungen zu verwenden
* Spring und EJB3 für die Verwaltung technischer Dienste zu vergleichen

---

## Zielgruppe

Java-Entwickler, die:

* die Grundlagen der Persistenz mit JPA verstehen möchten;
* eine mehrschichtige Architektur korrekt strukturieren möchten;
* sich darauf vorbereiten möchten, ihre Kenntnisse in Java EE zu vertiefen;

---

## Autor

**Serge Tahé** – Juni 2007;

---
