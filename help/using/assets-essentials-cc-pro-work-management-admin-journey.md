---
title: Einrichten von Assets Essentials für Creative Cloud Pro mit Work-Management-Lösungen
description: In diesem Tutorial erfahren Administratoren, wie sie die Integration von Assets Essentials mit Creative Cloud-Client-Programmen und Adobe Workfront aktivieren. Zu den Creative Cloud-Desktop-Programmen gehören Adobe Photoshop, Adobe Illustrator, Adobe InDesign und Adobe XD.
exl-id: a5e9e0c3-35ec-41de-9656-f4f0f88946c7
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '870'
ht-degree: 100%

---

# Assets Essentials für Creative Cloud Pro mit Work-Management-Lösungen {#creative-cloud-enterprise-user-journeys}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-next-banner-landing-page.png)

## Einführung {#introduction}

Creative Cloud Pro für Unternehmen mit Work-Management-Lösungen integriert Tools für Kreativ-, Inhalts- und Arbeitsverwaltung, um Ihre Fähigkeit zu steigern, kreative Inhalte zu erstellen und Geschäftsziele schnell zu erreichen. Die Lösung umfasst die folgenden Komponenten:

* Creative Cloud Pro

* Adobe Workfront

* Experience Manager Assets Essentials

In diesem Tutorial erfahren Administratoren, wie sie die Integration von Assets Essentials mit Creative Cloud-Client-Programmen und Adobe Workfront aktivieren. Zu den Creative Cloud-Desktop-Programmen gehören Adobe Photoshop, Adobe Illustrator, Adobe InDesign und Adobe XD.

## Bereitstellungstypen {#deployment-types}

Da die Lösung aus Programmen und Services von Creative Cloud und Adobe Experience Cloud besteht, können sie in einer oder zwei Adobe Admin Consoles in Ihrem Unternehmen bereitgestellt werden.

Bei einer Bereitstellung in zwei Admin Consoles ist ein zusätzlicher Konfigurationsschritt erforderlich:

* Creative Cloud-Services und -Programme (Creative Cloud Pro für Unternehmen und optionale Module) werden in der [Adobe Admin Console für Ihre Creative Cloud-Bereitstellung](https://helpx.adobe.com/de/enterprise/admin-guide.html) verwaltet.

* Adobe Workfront und Adobe Experience Manager Assets Essentials werden in der [Adobe Admin Console für Experience Cloud-Lösungen](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=de) verwaltet.

Um Creative Cloud- und Assets Essentials-Programme zu integrieren, müssen die Benutzer, die in der Admin Console für Creative Cloud verfügbar sind, auch in der Admin Console für Experience Cloud verfügbar gemacht werden. Um die Benutzer in der Admin Console von Experience Cloud verfügbar zu machen, erstellen Sie ein Verzeichnis, um [Verzeichnisvertrauen](https://helpx.adobe.com/de/enterprise/using/set-up-identity.html#directory-trusting) zwischen den beiden Admin Consoles herzustellen.

![Creative Cloud-Benutzer](assets/creative-cloud-users.svg)

Wie im Diagramm dargestellt, werden die Creative Cloud-Benutzer automatisch in der Admin Console von Experience Cloud bereitgestellt, basierend auf einer Vertrauensbeziehung zwischen den beiden Konsolen. Anschließend können Sie die Benutzer zu Assets Essentials-Produktprofilen hinzufügen. Daher können Creative Cloud-Benutzer auf Adobe Asset Link zugreifen, das mit dem Assets Essentials-Repository interagieren kann. Weitere Informationen finden Sie unter [Integrieren von Assets Essentials mit Creative Cloud-Programmen](integrate-with-creative-cloud.md).

## Dokumentations-Touren zu Experience Manager {#documentation-journeys}

Eine Dokumentations-Tour verbindet viele verschiedene und möglicherweise komplizierte Themen und Funktionen, indem sie dem Leser, der mit Assets Essentials noch nicht vertraut ist, hilft, ein geschäftliches Problem von Anfang bis Ende zu verstehen und zu lösen, wobei nur minimale Vorkenntnisse zum Thema oder zu Assets Essentials vorausgesetzt werden.

Dokumentations-Touren werden auf der Grundlage von Best-Practice-Prinzipien entwickelt, die auf Informationen aus den neuesten Forschungsergebnissen von Adobe, bewährten Implementierungserfahrungen der Adobe-Berater und dem Feedback aus Kundenprojekten beruhen.

## Voraussetzungen

* [Zugriff auf die Adobe Admin Console for Experience Cloud-Lösungen](https://experienceleague.adobe.com/docs/core-services/interface/administration/admin-getting-started.html?lang=de)

* [Zugriff auf die Adobe Admin Console für die Bereitstellung von Creative Cloud für Unternehmen](https://helpx.adobe.com/de/enterprise/admin-guide.html)

## Verwalten von Experience Manager Assets Essentials {#administer-assets-essentials}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-assets.png)

Adobe Experience Manager Assets Essentials ist eine neue, schlanke Edition von Adobe Experience Manager Assets. Assets Essentials bietet ein einheitliches Asset-Management und Zusammenarbeit mit einer vereinfachten und konsistenten Benutzeroberfläche. Durch die Benutzerfreundlichkeit können mehr Kreativ- und Marketing-Teams digitale Assets speichern, finden und verteilen.

Adobe Experience Manager Assets Essentials wird von Adobe für seine Kunden bereitgestellt. Im Rahmen der Bereitstellung wird Assets Essentials der Organisation eines Kunden in der Adobe Admin Console hinzugefügt.

Administratoren verwenden die Admin Console, um Benutzerberechtigungen für Assets Essentials-Produkte zu verwalten:

* Hinzufügen von Benutzergruppen

* Hinzufügen von Benutzern zu Benutzergruppen

* Hinzufügen von Benutzern zu Assets Essentials-Produktprofilen

Nach der Verwaltung der Benutzerberechtigungen in der Admin Console können Administratoren Assets Essentials für folgende Aufgaben verwenden:

* Erstellen einer Ordnerstruktur, um die Anforderungen der Organisation optimal zu unterstützen.

* Verwalten von Berechtigungen für die Ordnerstruktur

* Einrichten von Metadatenformularen

[![Siehe Handbuch](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](deploy-administer.md)

Nachdem Sie nun Assets Essentials konfiguriert und verwaltet haben, [integrieren Sie Creative Cloud-Programme mit Experience Manager Assets Essentials](integrate-with-creative-cloud.md).

## Integration von Creative Cloud-Programmen mit Experience Manager Assets Essentials {#administer-creative-cloud-applications}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-creative-cloud.png)

[Mit dem programminternen Bedienfeld für Adobe Asset Link](https://www.adobe.com/de/creativecloud/business/enterprise/adobe-asset-link.html) können Kreativprofis aus den unterstützten [!DNL Assets Essentials]-Desktop-Programmen heraus eine Verbindung zum [!DNL Adobe Creative Cloud]-Repository herstellen. Das Bedienfeld ist für [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] und [!DNL Adobe XD] verfügbar. Dadurch wird der Zugriff auf Assets optimiert, was wiederum die Content Velocity erhöht.

Dieses Tutorial führt Sie durch die Integration der Programme [!DNL Adobe Photoshop], [!DNL Adobe Illustrator], [!DNL Adobe InDesign] und [!DNL Adobe XD] mit Experience Manager Assets Essentials.

Ziele:

* Herstellen von Verzeichnisvertrauen zwischen der Admin Console von Creative Cloud und Experience Cloud

* Hinzufügen von Creative Cloud-Benutzern zu Assets Essentials-Produktprofilen

* Installieren von Adobe Asset Link

* Verwenden von Adobe Asset Link

[![Siehe Handbuch](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-creative-cloud.md)

Nachdem Sie nun die Creative Cloud-Programme mit Assets Essentials integriert haben, [integrieren Sie Adobe Workfront mit Experience Manager Assets Essentials](integrate-with-workfront.md).

## Integration von Adobe Workfront mit Experience Manager Assets Essentials {#administer-adobe-workfront}

![Voreinstellung zum Umschalten zwischen dunklem und hellem Design](assets/cce-workfront.png)

[[!DNL Adobe Workfront]](https://www.workfront.com/) ist ein Programm für Work-Management, mit dem Sie den gesamten Arbeitszyklus an einem Ort verwalten können. Durch die native Integration von [!DNL Adobe Workfront] und [!DNL Assets Essentials] können Unternehmen die Geschwindigkeit von Inhalten und die Markteinführungszeit verbessern, indem sie Work- und Asset-Management miteinander verbinden. Im Rahmen der Verwaltung ihrer Arbeit haben Benutzer in derselben Lösung Zugriff auf die erforderlichen Dokumente und Bilder.

In diesem Tutorial erfahren Sie, wie Sie Adobe Workfront verwalten und dann in Experience Manager Assets Essentials integrieren können.

Ziele:

* Hinzufügen von Benutzern zu Workfront-Produktprofilen

* Hinzufügen von Benutzern zu Assets Essentials-Produktprofilen

* Konfigurieren der Integration von Experience Manager Assets Essentials

[![Siehe Handbuch](https://helpx.adobe.com/content/dam/help/en/marketing-cloud/how-to/digital-foundation/_jcr_content/main-pars/image_1250343773/see-the-guide-sm.png)](integrate-with-workfront.md)
