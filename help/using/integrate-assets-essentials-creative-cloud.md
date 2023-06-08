---
title: Integrieren von Assets Essentials mit Creative Cloud-Programmen
description: Integrieren Sie Assets Essentials in Creative Cloud-Programmen, damit Sie innerhalb der unterstützten Desktop-Programme von  [!DNL Adobe Creative Cloud]  über das Bedienfeld „Adobe Asset Link“ direkt im Programm eine Verbindung zum  [!DNL Assets Essentials] -Repository herstellen können.
exl-id: 611fd958-3fd3-4c46-bee9-8b866b7dc208
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: ht
source-wordcount: '854'
ht-degree: 100%

---

# Integrieren von Assets Essentials mit Creative Cloud-Programmen {#integrate-assets-essentials-creative-cloud-applications}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-creative-cloud.png)

## Die bisherige Entwicklung

Nach der [Konfiguration von Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) in diesem Tutorial können Sie auf den Erfahrungen aufbauen, um die Creative Cloud-Programme mit Assets Essentials zu integrieren.

## Ziel

* **Zielgruppe**: Creative Cloud-Administratoren

* **Ziel**: Integrieren von Assets Essentials in Creative Cloud-Programmen, damit Ihre Kreativanwender innerhalb der unterstützten Desktop-Programme von [!DNL Adobe Creative Cloud] über das Bedienfeld „Adobe Asset Link“ direkt im Programm eine Verbindung zum [!DNL Assets Essentials]-Repository herstellen können.

## Übersicht

[Mit dem programminternen Bedienfeld für Adobe Asset Link](https://www.adobe.com/de/creativecloud/business/enterprise/adobe-asset-link.html) können Kreativprofis aus den unterstützten [!DNL Assets Essentials]-Desktop-Programmen heraus eine Verbindung zum [!DNL Adobe Creative Cloud]-Repository herstellen. Das Bedienfeld ist für [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] und [!DNL Adobe XD] verfügbar. Dadurch wird der Zugriff auf Assets optimiert, was wiederum dazu beiträgt, die Content Velocity zu erhöhen.

Anwender von Creative Cloud-Programmen können das Bedienfeld „Adobe Asset Link“ nur verwenden, wenn Sie die Creative Cloud-Programme in das Repository von Experience Manager Assets Essentials integrieren.

Führen Sie die folgenden Schritte aus, um Assets Essentials in Creative Cloud-Programmen zu integrieren:

* [Erstellen einer vertrauenswürdigen Verzeichnisstruktur zwischen der Admin Console von Creative Cloud und Experience Cloud](#directory-trusting-cc-assets-essentials-consoles)

* [Hinzufügen von Creative Cloud-Benutzern zu Assets Essentials-Produktprofilen](#add-cc-users-assets-essentials-product-profiles)

* [Installieren von Adobe Asset Link](#install-asset-link)

* [Verwenden von Adobe Asset Link](#use-asset-link)

## Herstellen von Verzeichnisvertrauen zwischen der Admin Console von Creative Cloud und Experience Cloud {#directory-trusting-cc-assets-essentials-consoles}

Wenn Ihre Creative Cloud in einer anderen Adobe Admin Console als der mit Assets Essentials (Experience Cloud-Lösung) bereitgestellt wird, müssen Sie eine Vertrauensbeziehung zwischen den beiden Konsolen hinzufügen.

Um Creative Cloud- und Assets Essentials-Programme zu integrieren, müssen die Benutzer, die in der Admin Console für Creative Cloud verfügbar sind, auch in der Admin Console für Experience Cloud verfügbar gemacht werden. Wenn Creative Cloud und Assets Essentials in separaten Admin Consoles bereitgestellt werden, ist eine Vertrauensbeziehung zwischen ihnen erforderlich, um dies zu aktivieren.

Klicken Sie in der Admin Console von Experience Cloud auf **[!UICONTROL Einstellungen]** und verwenden Sie die Registerkarte **[!UICONTROL Verzeichnisse]**, um ein Verzeichnis zu erstellen, sodass ein [Verzeichnisvertrauen](https://helpx.adobe.com/de/enterprise/using/set-up-identity.html#directory-trusting) zwischen den beiden Admin Consoles hergestellt wird.

## Hinzufügen von Creative Cloud-Benutzern zu Assets Essentials-Produktprofilen {#add-cc-users-assets-essentials-product-profiles}

Nachdem Sie das Verzeichnisvertrauen zwischen der Admin Console für Creative Cloud und der Admin Console für Experience Cloud eingerichtet haben, weisen Sie die Creative Cloud-Benutzer dem Produktprofil **[!DNL Assets Essentials]Benutzer** unter der [!DNL Assets Essentials]-Produktkarte in der Admin Console für Experience Cloud zu. Dadurch können Creative Cloud-Benutzer über ihr Plug-in-Bedienfeld „Adobe Asset Link“ auf Assets Essentials zugreifen. Darüber hinaus erhalten sie Zugriff auf die vollständige Web-Benutzeroberfläche von Assets Essentials zum Hochladen, Organisieren, Kennzeichnen und Suchen digitaler Assets über einen Webbrowser.

Andere Assets Essentials-Produktprofile, wie **[!DNL Assets Essentials]-Administratoren** und **[!DNL Assets Essentials]-Verbraucherbenutzer**, werden für verschiedene Benutzerberechtigungen verwendet (Programmadministratoren und Anwender, die über Experience Cloud-Integrationen auf Assets Essentials zugreifen).

Weitere Informationen zum Zuweisen von Benutzern zu Assets Essentials-Produktprofilen finden Sie unter [Zuweisen von Benutzern zu Assets Essentials-Produktprofilen](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Installieren von Adobe Asset Link {#install-asset-link}

Das Plug-in [!DNL Adobe Asset Link] kann auf zwei Arten installiert und für kreative Benutzer verfügbar gemacht werden:

* Kreative Benutzer können das Plug-in über ihr [!DNL Creative Cloud Desktop]-Programm installieren
* Ein Creative Cloud-Administrator kann in der Admin Console das Plug-in „Asset Link“ zu einem Creative Cloud-Paket hinzufügen

Die Wahl hängt von den IT-Richtlinien der Organisation ab.

**Die Installation mithilfe des [!DNL Creative Cloud Desktop]-Programms** wird [hier](https://helpx.adobe.com/de/creative-cloud/kb/installingextensionsandaddons.html) beschrieben. Es sind zwei Plug-ins verfügbar, die auf dem [Adobe Exchange](https://exchange.adobe.com/)-Marketplace gehostet werden, abhängig vom Creative Cloud-Programm:

* Für [!DNL Adobe Photoshop], [!DNL Adobe Illustrator] und [!DNL Adobe InDesign] handelt es sich um [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Für [!DNL Adobe XD] ist es [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

Die **Installation mit einem Creative Cloud-Paket** wird vom Creative Cloud-Administrator in der Admin Console ausgeführt, indem beim Erstellen eines Bereitstellungspakets das Plug-in „Asset Link“ einbezogen wird, das später auf Benutzer-Computern bereitgestellt werden kann. Suchen Sie im verwalteten Bildschirm „Plug-ins auswählen“ nach **Adobe Asset Link** im Abschnitt **Vorgestellte Geschäfts-Plug-ins**. Weitere Informationen finden Sie unter [Verpacken von Programmen über die Admin Console](https://helpx.adobe.com/de/enterprise/using/package-apps-admin-console.html).

## Verwenden von Adobe Asset Link {#use-asset-link}

Kreative Benutzer können Adobe Asset Link jetzt mit Photoshop, Illustrator, InDesign oder XD verwenden. Um das Bedienfeld in InDesign oder Illustrator zu öffnen, navigieren Sie zu „Fenster“ > „Erweiterungen“ > „Adobe Asset Link“. Navigieren Sie in Photoshop zu „Fenster“ > „Erweiterungen (alt)“ > „Adobe Asset Link“.

Informationen zum Einrichten von Adobe Asset Link für Adobe XD erhalten Sie, indem Sie [hier](https://helpx.adobe.com/de/enterprise/using/adobe-asset-link-for-xd.html) klicken.

>[!NOTE]
>
>Bei der Arbeit mit Apple-Chip-/M1-Hardware muss Adobe Photoshop im Rosetta-Kompatibilitätsmodus gestartet werden, um sicherzustellen, dass kreative Benutzer Zugriff auf das Bedienfeld „Adobe Asset Link“ haben, da es mithilfe der CEP-Erweiterungstechnologie erstellt wird. Weitere Informationen finden Sie unter [Photoshop für Apple-Chip](https://helpx.adobe.com/de/photoshop/kb/photoshop-for-apple-silicon.html).


Verwenden Sie Adobe Asset Link, um mit im Assets Essentials-Repository gespeicherten Assets zu arbeiten und sie zu ändern. Sie können verschiedene Aufgaben ausführen, z. B.:

* Suchen und Durchsuchen von Assets

* Hochladen von Assets

* Sortieren und Filtern von Assets

* Platzieren, Herunterladen und Ziehen eines Assets

* Auschecken und Einchecken eines Assets

* Anzeigen von Versionsverlauf und Dateidetails

Anweisungen zum Ausführen dieser Aufgaben finden Sie unter [Verwalten von Assets mithilfe von Adobe Asset Link](https://helpx.adobe.com/de/enterprise/using/manage-assets-using-adobe-asset-link.html).

## Wie geht es weiter

Nachdem Sie nun die Creative Cloud-Programme mit Assets Essentials integriert haben, [integrieren Sie Adobe Workfront mit Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).
