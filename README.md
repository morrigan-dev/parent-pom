<p align="center">
 <img src="https://raw.githubusercontent.com/morrigan-dev/parent-pom/main/images/Parent-POM.png">
</p>

<p align="center">
    <a href="https://github.com/morrigan-dev/parent-pom/actions/workflows/build-job.yml" title="Build Job"><img src="https://img.shields.io/github/workflow/status/morrigan-dev/parent-pom/Run%20snapshot%20build-job?logo=GitHub&style=plastic"></a>
    <a href="https://github.com/morrigan-dev/parent-pom/actions/workflows/quality-job.yml" title="Quality Job"><img src="https://img.shields.io/github/workflow/status/morrigan-dev/parent-pom/Run%20quality%20build-job?label=quality-build&logo=GitHub&style=plastic"></a>
    <a href="https://github.com/morrigan-dev/parent-pom/blob/main/LICENSE" title="License"><img src="https://img.shields.io/github/license/morrigan-dev/parent-pom?logo=GitHub&style=plastic"></a>
    <a href="https://github.com/morrigan-dev/parent-pom" title="Last Commit"><img src="https://img.shields.io/github/last-commit/morrigan-dev/parent-pom?logo=GitHub&style=plastic"></a>
    <br>
    <a href="https://sonarcloud.io/dashboard?id=morrigan-dev_parent-pom" title="Quality Gate"><img src="https://img.shields.io/sonar/quality_gate/morrigan-dev_parent-pom?logo=SonarCloud&server=https%3A%2F%2Fsonarcloud.io&style=plastic"></a>
</p>

<hr />
<p align="center">
    <a href="#über-dieses-projekt">Über dieses Projekt</a> • 
    <a href="#wer-bin-ich">Wer bin ich</a> •
    <a href="#lizenzierung">Lizenzierung</a>
</p>
<hr />

## Über dieses Projekt

Das parent-pom Projekt ist ein maven Projekt, welches als Parent-POM für alle meine hier veröffentlichten Java-Projekte 
genutzt wird. Es enthält die wichtigsten Konfigurationen für meine maven Projekte und meine Werkzeuge mit denen ich
ein CI/CD Entwicklungsprozess realisiere.

Hierfür werden folgende Technologien genutzt:
- [Maven](http://maven.apache.org/) (als Build & Dependency Werkzeug)
- [GitHub](https://github.com/morrigan-dev) (als SCM)
- [GitHub actions](https://docs.github.com/en/free-pro-team@latest/actions) (als CI/CD Pipeline)
- [Sonarcloud.io](https://sonarcloud.io/organizations/morrigan-dev/projects) (als Quality Werkzeug)
- [JFrog Artifactory](https://morrigan.jfrog.io/ui/packages) (als Artefakt Repository)

## Wer bin ich

Ich bin ein ausgebildeter Informatiker im Bereich Anwendungsentwicklung und habe bereits über 10 Jahre Berufserfahrung.
Die überwiegende Zeit wurde ich als Fullstack Java Entwickler eingesetzt. Dabei habe ich Java und Android Rich Clients 
erstellt mit den Technologien: Android, SWT, Swing, JavaFX<br />
Die meisten Anwendungen wurden in einer Client-Server Architektur betrieben, sodass ich auch für die Realisierung des
Backends verantwortlich war, welches ebenfalls in Java erstellt wurde. Hier kamen Technologien wie: Servlets, EJB, JPA,
Hibernate und viele mehr zum Einsatz.<br />
Natürlich wurden bei diesen Anwendungen auch Datenbanken genutzt. Hier bin ich vertraut mit: MySQL, MSSQL, Oracle, H2.

Ein weiterer großer Schwerpunkt in meiner täglichen Arbeit ist das automatisierte Testen. Hier habe ich Testansätze wie
test-driven-development (TDD) sowie behavior-driven-development (BDD) sehr schätzen gelernt und möchte auf diese Ansätze
nicht mehr verzichten.
In diesem Zusammenhang sind mir natürlich folgende Frameworks vertraut: JUnit, DBunit, XMLunit, Hamcrest, Cucumber

Im Jahr 2020 habe ich mich für ein Fernstudium an der Hochschule Trier entschieden, um den Master of Computer Science im Bereich Informatik zu erreichen. Es handelt sich hierbei um ein zertifikatsbasiertes Fernstudium, welches ich neben meiner normalen Betrufstätigkeit absolviere.

## Lizenzierung

Copyright (c) 2020 Thomas Gattinger.

Lizenziert unter **Apache-Lizenz, Version 2.0** (die "Lizenz"). Sie dürfen diese Datei ausschließlich im Einklang mit 
der Lizenz verwenden.

Eine Kopie der Lizenz erhalten Sie unter https://www.apache.org/licenses/LICENSE-2.0.

Sofern nicht durch anwendbares Recht gefordert oder schriftlich vereinbart, wird jede unter der Lizenz bereitgestellte 
Software „OHNE MÄNGELGEWÄHR“ UND OHNE AUSDRÜCKLICHE ODER STILLSCHWEIGENDE GARANTIE JEGLICHER ART bereitgestellt. 
Die genauen Angaben zu Genehmigungen und Einschränkungen unter der Lizenz finden Sie in der [LIZENZ](LICENSE).
