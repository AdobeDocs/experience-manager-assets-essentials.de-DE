---
title: Einrichten von Assets Essentials für Creative Cloud Pro mit Work Management-Lösungen
description: 'In diesem Tutorial wird eine Journey für Administratoren vorgestellt, mit der die Assets Essentials-Anwendung in Creative Cloud-Desktop-Applikationen und in Adobe Workfront integriert werden kann. Zu den Creative Cloud-Desktop-Programmen gehören Adobe Photoshop, Adobe Illustrator, Adobe InDesign und Adobe XD. '
source-git-commit: f4e56fc6bb76eeb2770b18be88b7da1a1829069c
workflow-type: tm+mt
source-wordcount: '900'
ht-degree: 15%

---


# Assets Essentials für Creative Cloud Pro mit Work Management-Lösungen {#creative-cloud-enterprise-user-journeys}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-next-banner-landing-page.png)

## Einführung {#introduction}

Creative Cloud Pro for Enterprise mit Work Management Solutions integriert Tools für Kreativ-, Inhalts- und Arbeitsverwaltung, um Ihre Fähigkeit zu steigern, kreative Inhalte zu erstellen und Geschäftsziele schnell zu erreichen. Die Lösung umfasst die folgenden Komponenten:

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

In diesem Tutorial wird eine Journey für Administratoren vorgestellt, mit der die Assets Essentials-Anwendung in Creative Cloud-Desktop-Applikationen und in Adobe Workfront integriert werden kann. Zu den Creative Cloud-Desktop-Programmen gehören Adobe Photoshop, Adobe Illustrator, Adobe InDesign und Adobe XD.

## Bereitstellungstypen {#deployment-types}

Da die Lösung aus Anwendungen und Diensten von Creative Cloud und Adobe Experience Cloud besteht, können diese in einer oder zwei Adoben Admin Consolen für Ihr Unternehmen bereitgestellt werden.

Bei einer Bereitstellung in zwei Admin Consolen ist ein zusätzlicher Konfigurationsschritt erforderlich:

* Creative Cloud Services und Anwendungen (Creative Cloud für Enterprise Pro und optionale Module) werden in verwaltet. [Adobe Admin Console für Ihre Creative Cloud-Bereitstellung](https://chl-author-preview.corp.adobe.com/content/help/en/enterprise/admin-guide.html).

* Adobe Workfront und Adobe Experience Manager Assets Essentials werden in verwaltet [Adobe Admin Console für Experience Cloud-Lösungen](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html).

Um Creative Cloud- und Assets Essentials-Anwendungen zu integrieren, müssen die Benutzer, die in Admin Console für Creative Cloud verfügbar sind, in Admin Console für Experience Cloud verfügbar gemacht werden. Um die Benutzer in Experience Cloud Admin Console verfügbar zu machen, erstellen Sie ein Verzeichnis, um [directory trusting](https://helpx.adobe.com/enterprise/using/set-up-identity.html#directory-trusting) zwischen den beiden Admin-Konsolen.

![Creative Cloud-Benutzer](assets/creative-cloud-users.svg)

Wie im Diagramm dargestellt, werden die Creative Cloud-Benutzer automatisch in der Experience Cloud-Admin Console bereitgestellt, basierend auf einer Vertrauensbeziehung zwischen den beiden Konsolen. Anschließend können Sie die Benutzer zu Assets Essentials-Produktprofilen hinzufügen. Daher können Creative Cloud-Benutzer auf die Adobe Asset Link-Anwendung zugreifen, die mit dem Assets Essentials-Repository interagieren kann. Weitere Informationen finden Sie unter [Integrieren von Assets Essentials mit Creative Cloud-Anwendungen](integrate-assets-essentials-creative-cloud.md).

## Journey der Experience Manager-Dokumentation {#documentation-journeys}

Eine Journey der Dokumentation verbindet viele verschiedene und möglicherweise komplexe Themen und Funktionen, indem sie eine Erzählung bereitstellt, die dem Leser, der neu bei Assets Essentials sein kann, dabei hilft, ein Geschäftsproblem von Anfang bis Ende zu verstehen und zu lösen, während er von vornherein nur über ein minimales Vorthema oder Assets Essentials-Wissen verfügt.

Die Journey der Dokumentation basieren auf Best-Practice-Prinzipien, die durch die neuesten Forschungsarbeiten der Adobe, die bewährte Implementierungserfahrung von Adobe-Beratern und das Feedback von Kundenprojekten informiert werden.

## Voraussetzungen

* [Zugriff auf Adobe Admin Console for Experience Cloud-Lösungen](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html)

* [Zugriff auf Adobe Admin Console for Creative Cloud für die Unternehmensbereitstellung](https://helpx.adobe.com/enterprise/admin-guide.html)

## Verwalten von Experience Manager Assets Essentials {#administer-assets-essentials}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials ist eine neue, einfache Ausgabe von Adobe Experience Manager Assets. Assets Essentials bietet eine einheitliche Asset-Verwaltung und Zusammenarbeit mit einer vereinfachten und konsistenten Benutzeroberfläche. Durch die Benutzerfreundlichkeit können mehr Kreativ- und Marketing-Teams digitale Assets speichern, finden und verteilen.

Adobe Experience Manager Assets Essentials wird von Adobe für seine Kunden bereitgestellt. Im Rahmen der Bereitstellung wird Assets Essentials zum Unternehmen eines Kunden in der Adobe Admin Console hinzugefügt.

Administratoren verwenden die Admin Console, um Benutzerberechtigungen für Assets Essentials-Produkte zu verwalten:

* Hinzufügen von Benutzergruppen

* Benutzer zu Benutzergruppen hinzufügen

* Hinzufügen von Benutzern zu Assets Essentials-Produktprofilen

Nach der Verwaltung der Benutzerberechtigungen in Admin Console können Administratoren die Assets Essentials-Anwendung für folgende Aufgaben verwenden:

* Erstellen Sie eine Ordnerstruktur, um die Anforderungen des Unternehmens optimal zu unterstützen.

* Berechtigungen für die Ordnerstruktur verwalten

* Einrichten von Metadatenformularen

[![Siehe Handbuch](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](adminster-aem-assets-essentials.md)

## Integration von Creative Cloud-Anwendungen in Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-creative-cloud.png)

[Mit dem programminternen Bedienfeld für Adobe Asset Link](https://www.adobe.com/de/creativecloud/business/enterprise/adobe-asset-link.html) können Kreativprofis aus den unterstützten [!DNL Assets Essentials]-Desktop-Programmen heraus eine Verbindung zum [!DNL Adobe Creative Cloud]-Repository herstellen. Das Bedienfeld ist für [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] und [!DNL Adobe XD] verfügbar. Dadurch wird der Zugriff auf Assets optimiert, was wiederum die Content Velocity erhöht.

Dieses Tutorial führt Sie zur Integration [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign]und [!DNL Adobe XD] Anwendungen mit Experience Manager Assets Essentials.

Ziele:

* Erstellen von Verzeichnissen, die zwischen Creative Cloud- und Experience Cloud-Admin Consolen vertrauenswürdig sind

* Hinzufügen von Creative Cloud-Benutzern zu Assets Essentials-Produktprofilen

* Adobe Asset Link installieren

* Adobe Asset Link verwenden

[![Siehe Handbuch](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-creative-cloud.md)

## Integration von Adobe Workfront in Experience Manager Assets Essentials {#administer-adobe-workfront}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) ist ein Programm für das Arbeits-Management, mit dem Sie den gesamten Arbeitszyklus an einem Ort verwalten können. Die native Integration zwischen [!DNL Adobe Workfront] und [!DNL Assets Essentials] ermöglicht Unternehmen, die Geschwindigkeit von Inhalten und die Time-to-Market zu steigern, indem sie Arbeit und Asset-Management systematisch miteinander verbinden. Im Rahmen der Verwaltung ihrer Arbeit haben Benutzer in derselben Lösung Zugriff auf die erforderlichen Dokumente und Bilder.

In diesem Tutorial erfahren Sie, wie Sie Adobe Workfront verwalten und dann in Experience Manager Assets Essentials integrieren können.

Ziele:

* Hinzufügen von Benutzern zu Workfront-Produktprofilen

* Hinzufügen von Benutzern zu Assets Essentials-Produktprofilen

* Integration von Experience Manager Assets Essentials konfigurieren

[![Siehe Handbuch](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-assets-essentials-workfront.md)


