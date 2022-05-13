---
title: Integrieren von Assets Essentials mit Creative Cloud-Anwendungen
description: Integrieren Sie Assets Essentials in Creative Cloud-Anwendungen, damit Sie über den Link "Adobe Asset"im App-Bedienfeld eine Verbindung zu [!DNL Assets Essentials] Repository aus dem unterstützten [!DNL Adobe Creative Cloud] Desktop-Applikationen.
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '854'
ht-degree: 7%

---


# Integrieren von Assets Essentials mit Creative Cloud-Anwendungen {#integrate-assets-essentials-creative-cloud-applications}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-creative-cloud.png)

## Die Geschichte bis jetzt

Nachher [Konfigurieren von Experience Manager Assets Essentials](adminster-aem-assets-essentials.md) in diesem Tutorial können Sie auf dem Erlebnis aufbauen, um die Creative Cloud-Anwendungen in Assets Essentials zu integrieren.

## Ziel

* **Zielgruppe**: Creative Cloud-Administratoren

* **Ziel**: Integrieren Sie Assets Essentials in Creative Cloud-Apps, damit kreative Benutzer über den Link &quot;Adobe Asset&quot;im App-Bedienfeld eine Verbindung zu [!DNL Assets Essentials] Repository aus dem unterstützten [!DNL Adobe Creative Cloud] Desktop-Applikationen.

## Übersicht

[Mit dem programminternen Bedienfeld für Adobe Asset Link](https://www.adobe.com/de/creativecloud/business/enterprise/adobe-asset-link.html) können Kreativprofis aus den unterstützten [!DNL Assets Essentials]-Desktop-Programmen heraus eine Verbindung zum [!DNL Adobe Creative Cloud]-Repository herstellen. Das Bedienfeld ist für [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] und [!DNL Adobe XD] verfügbar. Dadurch wird der Zugriff auf Assets optimiert, was wiederum dazu beiträgt, die Geschwindigkeit von Inhalten zu erhöhen.

Anwender von Creative Cloud-Anwendungen können das Bedienfeld &quot;Adobe Asset Link&quot;nur verwenden, wenn Sie die Creative Cloud-Anwendungen in das Repository von Experience Manager Assets Essentials integrieren.

Führen Sie die folgenden Schritte aus, um Assets Essentials in Creative Cloud-Anwendungen zu integrieren:

* [Erstellen von Verzeichnissen, die zwischen der Admin Console von Creative Cloud und Experience Cloud vertrauenswürdig sind](#directory-trusting-cc-assets-essentials-consoles)

* [Hinzufügen von Creative Cloud-Benutzern zu Assets Essentials-Produktprofilen](#add-cc-users-assets-essentials-product-profiles)

* [Adobe Asset Link installieren](#install-asset-link)

* [Adobe Asset Link verwenden](#use-asset-link)

## Erstellen von Verzeichnissen, die zwischen Creative Cloud- und Experience Cloud-Admin Consolen vertrauenswürdig sind {#directory-trusting-cc-assets-essentials-consoles}

Wenn Ihr Creative Cloud in einer anderen Adobe-Admin Console als der mit Assets Essentials (Experience Cloud-Lösung) bereitgestellt wird, müssen Sie eine Vertrauensbeziehung zwischen den beiden Konsolen hinzufügen.

Um Creative Cloud- und Assets Essentials-Anwendungen zu integrieren, müssen die Benutzer, die in Admin Console für Creative Cloud verfügbar sind, in Admin Console für Experience Cloud verfügbar gemacht werden. Wenn Creative Cloud und Assets Essentials in separaten Admin Consolen bereitgestellt werden, ist eine Vertrauensbeziehung zwischen ihnen erforderlich, um dies zu aktivieren.

Klicken Sie auf der Admin Console Experience Cloud auf **[!UICONTROL Einstellungen]** und verwenden Sie **[!UICONTROL Verzeichnisse]** -Registerkarte, um ein Verzeichnis zu erstellen, das erstellt werden soll [directory trusting](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) zwischen den beiden Admin Consolen.

## Hinzufügen von Creative Cloud-Benutzern zu Assets Essentials-Produktprofilen {#add-cc-users-assets-essentials-product-profiles}

Nachdem Sie das Verzeichnis erstellt haben, das zwischen der Admin Console für Creative Cloud und der Admin Console für Experience Cloud vertraut, weisen Sie die Creative Cloud-Benutzer dem **[!DNL Assets Essentials]Benutzer** Produktprofil unter [!DNL Assets Essentials] Produktkarte in der Experience Cloud-Admin Console. Creative Cloud-Benutzer können über ihr Adobe Asset Link-Plug-in-Bedienfeld auf Assets Essentials zugreifen. Darüber hinaus erhalten sie Zugriff auf die gesamte Assets Essentials-Webbenutzeroberfläche, über die sie digitale Assets über einen Webbrowser hochladen, organisieren, taggen und finden können.

Andere Assets Essentials-Produktprofile - **[!DNL Assets Essentials]Administratoren** und **[!DNL Assets Essentials]Verbraucherbenutzer** - werden für verschiedene Benutzerberechtigungen verwendet (Anwendungsadministratoren und Anwender, die über Experience Cloud-Integrationen auf Assets Essentials zugreifen).

Weitere Informationen zum Zuweisen von Benutzern zu Assets Essentials-Produktprofilen finden Sie unter [Zuweisen von Benutzern zu Assets Essentials-Produktprofilen](adminster-aem-assets-essentials.md#add-users-to-product-profiles).

## Adobe Asset Link installieren {#install-asset-link}

[!DNL Adobe Asset Link] -Plug-in kann auf zwei Arten installiert und für kreative Benutzer verfügbar gemacht werden:

* Creative-Benutzer können das Plug-in über ihre [!DNL Creative Cloud Desktop] application
* Creative Cloud-Administrator kann in Admin Console einem Creative Cloud-Package das Asset Link-Plug-in hinzufügen

Die Wahl hängt von den IT-Richtlinien der Organisation ab.

**Installation mit [!DNL Creative Cloud Desktop] application** wird beschrieben [here](https://helpx.adobe.com/creative-cloud/kb/installingextensionsandaddons.html). Es sind zwei Plug-ins verfügbar, die auf gehostet werden [Adobe Exchange](https://exchange.adobe.com/) Marketplace, abhängig von der Creative Cloud-Anwendung:

* Für [!DNL Adobe Photoshop], [!DNL Adobe Illustrator]und [!DNL Adobe InDesign]: [Adobe Asset Link CEP](https://exchange.adobe.com/creativecloud.details.106875.adobe-asset-link-cep.html)
* Für [!DNL Adobe XD]: [Adobe Asset Link](https://exchange.adobe.com/creativecloud/plugindetails.html/app/cc/61d229b9)

**Installation mit einem Creative Cloud-Package** wird vom Creative Cloud-Administrator in Admin Console ausgeführt, indem beim Erstellen eines Bereitstellungspakets das Asset-Link-Plug-in einbezogen wird, das später auf Benutzercomputern bereitgestellt werden kann. Suchen Sie im verwalteten Bildschirm &quot;Plug-ins auswählen&quot;nach **Adobe Asset Link** im **Vorgestellte Geschäfts-Plugins** Abschnitt. Weitere Informationen finden Sie unter [Verpacken von Apps über die Admin Console](https://helpx.adobe.com/enterprise/using/package-apps-admin-console.html).

## Adobe Asset Link verwenden {#use-asset-link}

Kreative Benutzer können jetzt Adobe Asset Link mit Photoshop, Illustrator, InDesign oder XD verwenden. Um das Bedienfeld auf InDesign oder Illustrator zu öffnen, navigieren Sie zu Windows > Erweiterungen > Adobe Asset Link. Navigieren Sie in Photoshop zu &quot;Fenster&quot;> &quot;Erweiterungen (alt)&quot;> &quot;Adobe Asset Link&quot;.

Informationen zum Einrichten von Adobe Asset Link für Adobe XD erhalten Sie durch Klicken auf [here](https://helpx.adobe.com/de/enterprise/using/adobe-asset-link-for-xd.html).

>[!NOTE]
>
>Bei der Arbeit mit Apple Silicon/M1-Hardware muss Adobe Photoshop mit dem Rosetta-Kompatibilitätsmodus gestartet werden, um sicherzustellen, dass kreative Benutzer Zugriff auf das Adobe Asset Link-Bedienfeld haben, da es mithilfe der CEP-Erweiterungstechnologie erstellt wurde. Weitere Informationen finden Sie unter [Photoshop for Apple Silicon](https://helpx.adobe.com/photoshop/kb/photoshop-for-apple-silicon.html).


Verwenden Sie Adobe Asset Link , um mit im Assets Essentials-Repository gespeicherten Assets zu arbeiten und sie zu ändern. Sie können verschiedene Aufgaben ausführen, z. B.:

* Suchen und Durchsuchen von Assets

* Hochladen von Assets

* Sortieren und Filtern von Assets

* Platzieren, Herunterladen und Ziehen eines Assets

* Auschecken und Einchecken eines Assets

* Versionsverlauf und Dateidetails anzeigen

Anweisungen zum Ausführen dieser Aufgaben finden Sie unter [Verwalten von Assets mithilfe von Adobe Asset Link](https://helpx.adobe.com/in/enterprise/using/manage-assets-using-adobe-asset-link.html).

## Wie geht es weiter

Nachdem Sie die Creative Cloud-Anwendungen in Assets Essentials integriert haben, [Integration von Adobe Workfront in Experience Manager Assets Essentials](integrate-assets-essentials-workfront.md).
