---
title: Versionshinweise
description: Versionshinweise zu und bekannte Probleme von  [!DNL Assets Essentials]
role: User,Leader,Admin,Architect,Developer
contentOwner: AG
source-git-commit: cbeb6f6f59da164115af52dfdbb97023b84bc1d1
workflow-type: tm+mt
source-wordcount: '280'
ht-degree: 48%

---


# Versionshinweise zu [!DNL Assets Essentials] {#release-notes}

Die aktuelle Version ist die erste öffentliche Version von [!DNL Assets Essentials], die ab 21. Juni 2021 verfügbar ist. [!DNL Assets Essentials] bietet einfache Asset-Management-Funktionen und die erste Version, die die folgenden Hauptfunktionen und CRUD-Vorgänge (Erstellen, Lesen, Aktualisieren und Löschen) unterstützt:

* Hochladen und Hinzufügen von Assets, einschließlich verschachtelter Ordner. Vorschau der Assets und Versionen anzeigen.
* Volltextsuche, erweiterte Suchfilter und gespeicherte Suchen für schnelles Finden von Assets.
* Grundlegende Asset-Management-Vorgänge wie Aktualisierung, Löschen, Download und Verwalten von Metadaten.
* Integration mit [[!DNL Adobe Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html?lang=de).

Derzeit ist [!DNL Assets Essentials] für [[!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer.html?lang=de)-Kunden verfügbar.

Weitere Informationen zur Lösung finden Sie in der [Einführung zu  [!DNL Assets Essentials]](introduction.md). Informationen zu den ersten Schritten mit den Funktionen finden Sie unter [Erste Schritte](/help/get-started.md).

## Aktuelle Version {#release-notes-current}

Die aktuelle Version von Assets Essentials ist 2021.7.0, die am 29. Juli 2021 veröffentlicht wurde und folgende Aktualisierungen enthält:

* Sie können benutzerdefinierte Metadatenformulare erstellen und verwalten, die für die Anzeige von Metadateneigenschaften für Benutzer im Detailbildschirm des Assets unter der Option [!UICONTROL Metadaten-Forms] unter [!DNL Settings] verwendet werden. Siehe [Metadatenformulare](metadata.md#metadata-forms).
* Verschiedene Fehlerbehebungen und Produktverbesserungen, einschließlich einer besseren Leistung beim Hochladen eines verschachtelten Ordners mit vielen Unterordnern.

## Bekannte Probleme {#known-issues}

Die Liste der bekannten Probleme des Angebots [!DNL Assets Essentials] wird laufend überarbeitet und aktualisiert:

* Wenn Sie einen oder mehrere Ordner oder Assets hochladen möchten, werden die Elemente automatisch in einen der Unterordner hochgeladen, wenn Sie sie in einen Ordner mit Unterordnern im Repository ziehen. Um dieses Problem zu umgehen, klicken Sie auf die Option [!DNL Upload assets] und ziehen Sie sie in das Dialogfeld. <!-- CQ-4327753 -->
* Nach dem Hochladen von Ordnern werden neue Ordner in der linken Leiste manchmal falsch angezeigt, anstatt in der Baumansicht angezeigt zu werden. Die Lösung besteht darin, den Browser zu aktualisieren. <!-- CQ-4323534 -->

<!--
* Use assets that do not have whitespace in the file names. The replies to comments do not work for such assets.
-->

Wenn Sie auf Probleme stoßen oder sogar Verbesserungsanfragen haben, können Sie dem Team [Feedback senden](#provide-feedback).
