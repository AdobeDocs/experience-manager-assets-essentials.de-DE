---
title: Versionshinweise
description: Versionshinweise zu und bekannte Probleme von  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AK
exl-id: a0e29eb6-336a-4f78-b7bd-ec1338c86775
source-git-commit: 7c6293bb99d5be8084e6998da966bb89be9c714e
workflow-type: tm+mt
source-wordcount: '889'
ht-degree: 86%

---

# Versionshinweise zu [!DNL Assets Essentials] {#release-notes}

Die aktuelle Version von [!DNL Assets Essentials] wird am 16. Juni 2022 veröffentlicht.

Was diese Version bietet:

**Asset-Statusverbesserungen**

* Mit Assets Essentials können Sie jetzt [Legen Sie ein Ablaufdatum für ein Asset fest.](manage-organize.md#set-asset-status). Darüber hinaus können Sie [Assets filtern](search.md#refine-search-results) basierend auf der `Expired` Asset-Status und ein Ablaufdatumsbereich.

* Sie können jetzt die Asset-Statusanzeige für alle im Papierkorb verfügbaren Assets anzeigen. Daher können Sie eine Entscheidung treffen, um ein Asset basierend auf seinem Status wiederherzustellen.

**Verbesserungen bei Suchfiltern**

* Mit Assets Essentials können Sie jetzt [Assets filtern](search.md#refine-search-results) mithilfe der `No Status` Asset-Status.

<!--

* Assets Essentials now supports [using a wildcard operator (*) while using custom filters](search.md#custom-filters) to enable Assets Essentials to display assets in the results that partially match the search criteria.

-->

**Verbesserungen bei Sammlungen**

<!--

* Assets Essentials now enables you to [create Private collections](manage-collections.md#create-collection).

-->

* Assets Essentials unterstützt jetzt [Herunterladen einer Sammlung](manage-collections.md).

* Sie können jetzt das Metadatenfeld Beschreibung für eine Sammlung bearbeiten.

**Dokumentationsverbesserungen**

* Eine neue Version der [Übersichtsdokumentation zu Assets Essentials](introduction.md) ist jetzt verfügbar.

**Verbesserungen auf der Basis von Kunden-Feedback**

* Verbesserungen und Fehlerkorrekturen basierend auf Kunden-Feedback.


## Bekannte Probleme {#known-issues}

Die Liste der bekannten Probleme mit [!DNL Assets Essentials]-Angeboten wird laufend überarbeitet und aktualisiert:

* Assets Essentials unterstützt nicht das Erstellen privater Sammlungen.

Wenn Sie auf Probleme stoßen oder Verbesserungsanfragen haben, können Sie dem Team [Feedback senden](#provide-feedback).

## Frühere Versionen {#past-release}

### 2022.4.0 {#april-2022}

Die aktuelle Version von [!DNL Assets Essentials] wurde am 12. Mai 2022 veröffentlicht. Was diese Version bietet:

* [!DNL Assets Essentials] unterstützt jetzt das [Erstellen von Sammlungen](manage-collections.md). Eine Sammlung ist ein Satz von Assets innerhalb von Experience Manager Assets Essentials. Anhand von Sammlungen können Assets von mehreren Benutzern gemeinsam verwendet werden. Im Gegensatz zu Ordnern kann eine Sammlung Assets von verschiedenen Speicherorten enthalten.

* Assets Essentials ermöglicht jetzt auch das [Hinzufügen benutzerdefinierter Filter](search.md#custom-filters) zur Benutzeroberfläche. Sie können diese benutzerdefinierten Filter dann zusätzlich zu den Standardfiltern anwenden, um Ihre Suchergebnisse zu verfeinern.

* Assets Essentials ermöglicht jetzt das [Festlegen eines Status](manage-organize.md#set-asset-status) für Assets, die im Repository verfügbar sind. Legen Sie einen Asset-Status fest, um die nachgelagerte Nutzung digitaler Assets besser steuern und verwalten zu können.

* Verbesserungen und Fehlerkorrekturen basierend auf Kunden-Feedback.

#### Inkognito-Modus in Chrome {#incognito-mode}

Mit dieser Version optimieren wir die Leistung der Benutzeroberfläche. Bestimmte Funktionen in Assets Essentials –- Kommentare zu Assets und zur Bildbearbeitung – hängen davon ab, dass der lokale Speicher des Browsers und Cookies von Drittanbietern aktiviert sind. Der Inkognito-Modus im Chrome-Webbrowser blockiert standardmäßig Cookies von Drittanbietern – die Nutzer haben eine Reihe von Optionen, um weiterhin auf alle Funktionen zugreifen zu können:

* Verwenden Sie Chrome-Profile anstelle des Inkognito-Modus, wenn der Benutzer Browser-Sitzungen trennen muss.

* Abschalten von `Block third-party cookies` im Bildschirm „Inkognito-Modus“ in Chrome

### 2022.2.0 {#march-2022}

[!DNL Assets Essentials] wurde am 9. März 2022 veröffentlicht und umfasst folgende Updates:

* Mit [!DNL Assets Essentials] können Sie jetzt [einen Link erstellen und Medienelemente für externe Beteiligte freigeben](share-links-for-assets.md), die keinen Zugriff auf das Programm [!DNL Assets Essentials] haben. Sie können ein Ablaufdatum für den Link definieren und ihn dann mithilfe Ihrer bevorzugten Kommunikationsmethode wie E-Mail oder Messaging-Services für andere freigeben. Empfänger des Links können eine Vorschau der Medienelemente anzeigen und sie herunterladen.

* [!DNL Assets Essentials] besitzt jetzt zusätzlich zu den bestehenden regulären und Privatkundenproduktprofilen in der Admin Console auch [ein Administratorproduktprofil](deploy-administer.md#add-users-to-essentials). Ein Administrator kann dem Administratorproduktprofil jetzt weitere Benutzer zuweisen.

* Assets Essentials ermöglicht es Administratoren jetzt, [die Zugriffsebenen für im Repository verfügbare Ordner zu verwalten](manage-permissions.md). Als Administrator können Sie Benutzergruppen erstellen und diesen Gruppen Berechtigungen zum Verwalten von Zugriffsebenen zuweisen. Sie können Benutzergruppen die Berechtigung zur Zugriffsberechtigungsverwaltung auch auf Ordnerebene zuweisen.

* Verbesserungen und Fehlerkorrekturen basierend auf Kunden-Feedback.

Außerdem wurde die [!DNL Adobe Asset Link]-Erweiterung für Creative Cloud (Photoshop, Illustrator und InDesign) in der [neuen Version 3.2](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html) veröffentlicht, die Leistungsverbesserungen bei der Bedienfeld-Startzeit und bei der Download-Geschwindigkeit aufweist.


### Version 2022.1.0 {#january-2022}

[!DNL Assets Essentials] wurde am Donnerstag, 3. Februar 2022 veröffentlicht und umfasst folgende Updates:

* Leistungsverbesserungen für den Vorgang [!UICONTROL Ordner erstellen]. <!-- CQ-4338818 -->

### Version 2021.11.0 {#november-2021}

[!DNL Assets Essentials] wurde am Donnerstag, 16. Dezember 2021 veröffentlicht und umfasst folgende Updates:

* Adobe stellt Assets Essentials nach Abschluss des Bereitstellungsprozesses automatisch bereit. Die Administratoren müssen keine zusätzlichen Schritte ausführen, um Assets Essentials mithilfe der [!DNL Cloud Manager]-Benutzeroberfläche bereitzustellen. Diese automatische Bereitstellung ist für Umgebungen verfügbar, die nach dem 6. Januar 2022 bereitgestellt werden.
* Neue Versionen von Creative Cloud-Plug-ins, die mit Assets Essentials funktionieren, sind auf Adobe Exchange verfügbar - [Adobe Asset Link für Adobe XD v 2.1.0](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9) und [Adobe Asset Link für Photoshop/InDesign/Illustrator 3.1.65](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html).
* Verschiedene Fehlerbehebungen und Produktverbesserungen, einschließlich vorheriger bekannter Probleme (Ordner werden nun nach dem Hochladen korrekt in der linken Navigationsstruktur angezeigt<!-- CQ-4337638 -->, Upload per Drag-and-Drop ermöglicht es dem Benutzer, beim Ablegen zum Hochladen entweder den aktuellen Ordner oder einen beliebigen Unterordner auszuwählen<!-- CQ-4327753 -->.)

### Version 2021.8.0 {#august2021}

[!DNL Assets Essentials] 2021.8.0 wurde am 30. Juli 2021 veröffentlicht und umfasst folgende Updates:

* Integrationen mit [!DNL Adobe Workfront], mit denen [!DNL Workfront]-Benutzer ihre digitalen Assets im Rahmen der Verwaltung ihrer Arbeit organisieren können. Weitere Informationen finden Sie unter [Integrationen mit anderen Adobe-Lösungen](/help/integration.md).

### Version 2021.7.0 {#july2021}

[!DNL Assets Essentials] 2021.7.0 wurde am 29. Juli 2021 veröffentlicht und umfasst folgende Updates:

* Sie können benutzerdefinierte Metadatenformulare erstellen und verwalten, die für die Anzeige von Metadateneigenschaften für Benutzer im Detailbildschirm des Assets unter der Option [!UICONTROL Metadatenformulare] unter [!DNL Settings] verwendet werden. Weitere Informationen finden Sie unter [Metadatenformulare](metadata.md#metadata-forms).
* Verschiedene Fehlerbehebungen und Produktverbesserungen, einschließlich einer besseren Leistung beim Hochladen eines verschachtelten Ordners mit vielen Unterordnern.

### Version 2021.6.0 {#june2021}

Die erste Version von [!DNL Assets Essentials], die am 21. Juni 2021 zur Verfügung gestellt wurde, bietet einfache Asset-Management-Funktionen. Sie unterstützt die folgenden Hauptfunktionen und CRUD-Vorgänge (Erstellen, Lesen, Aktualisieren und Löschen):

* Hochladen und Hinzufügen von Assets, einschließlich verschachtelter Ordner. Anzeigen einer Vorschau der Assets und Versionen.
* Volltextsuche, erweiterte Suchfilter und gespeicherte Suchen für schnelles Finden von Assets.
* Grundlegende Asset-Management-Vorgänge wie Aktualisierung, Löschen, Download und Verwalten von Metadaten.
* [!DNL Assets Essentials] steht [!DNL Adobe Journey Optimizer]-Benutzern zur Verwaltung der Assets beim Erstellen von Nachrichten zur Verfügung. Weitere Informationen finden Sie unter [Integrationen mit anderen Adobe-Lösungen](/help/integration.md).
