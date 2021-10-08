---
title: Implementieren und Verwalten von Benutzern
description: Anwendungsfälle für Administratoren, wie z. B. Implementieren und Verwalten von Benutzern in  [!DNL Assets Essentials].
role: Admin
source-git-commit: a1dc66213f602bce5b5a2ec0ba99084c7f7b1ee1
workflow-type: ht
source-wordcount: '887'
ht-degree: 100%

---


# Implementieren von [!DNL Assets Essentials] und Hinzufügen von Benutzern {#administer}

[!DNL Adobe Experience Manager Assets Essentials] wird von Adobe für seine Kunden bereitgestellt. Im Rahmen der Implementierung wird [!DNL Assets Essentials] in der [!DNL Adobe Admin Console] zur Organisation eines Kunden hinzugefügt. Kunden haben auch Zugriff auf [!DNL Experience Manager Cloud Manager] als Implementierungs-Tool und auf [!DNL Admin Console], um Benutzerberechtigungen für die [!DNL Assets Essentials]-Lösung zu verwalten.

Administratoren führen die folgenden Aufgaben durch:

* [Implementieren von [!DNL Assets Essentials]](#deploy-essentials) für ihre Organisation.
* [Verwalten des Benutzerzugriffs ](#add-users-to-essentials) von Organisationsmitgliedern auf [!DNL Assets Essentials].
* Optional können Sie [den Service-Status und die Protokolle](#view-logs) anzeigen.

## Implementieren von [!DNL Assets Essentials] {#deploy-essentials}

Nach der Implementierung wird Ihrer Organisation die Berechtigung für [!DNL Assets Essentials] in der [!DNL Admin Console] hinzugefügt. Bevor die Lösung für den Benutzer verfügbar ist, muss sie von einem Administrator der Organisation bereitgestellt werden. Der Administrator führt eine einmalige Implementierung über die [!DNL Cloud Manager]-Benutzeroberfläche durch. Nach der ersten Implementierung führt Adobe die Wartungsarbeiten und Aktualisierungen des Services durch. Nachdem die Lösung bereitgestellt wurde, erhält der Administrator eine E-Mail von Adobe. Die E-Mail enthält eine Begrüßungsnachricht und einen Link zu den ersten Schritten. Gehen Sie zur Implementierung wie folgt vor:

1. Greifen Sie über den Link in der E-Mail auf die [Admin Console](https://adminconsole.adobe.com) zu und melden Sie sich an. Wenn Sie Administratorzugriff auf mehr als ein Konto einer Organisation haben, wählen Sie die entsprechende Organisation aus oder wechseln Sie mithilfe des Umschalters in der oberen Leiste zu ihr. Die Produktkarte für [!DNL Assets Essentials] ist in der [!DNL Admin Console] sichtbar.

   ![[!DNL Assets Essentials]-Karte in der [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Abbildung: [!DNL Assets Essentials]-Karte in der [!DNL Admin Console].*

1. Fügen Sie sich als Administrator dem `AEM Assets Essentials - Cloud Manager`-Produktprofil in der [!DNL Admin Console] hinzu. Statt sich selbst können Sie ein anderes Mitglied Ihrer Organisation hinzufügen oder mehr als einen Administrator hinzufügen.

1. Klicken Sie auf ![Hinzufügen-Symbol](assets/do-not-localize/add-icon.svg) für die Option [!UICONTROL Produktprofile auswählen] und wählen Sie dann [!UICONTROL Implementierungs-Manager – Assets Essentials] als **[!UICONTROL Produktprofil]** aus. Der in diesem Schritt hinzugefügte Benutzer erhält eine E-Mail von Adobe mit Zugriff auf [!DNL Cloud Manager] und kann die Implementierung durchführen.

   ![Hinzufügen eines Administrators und Auswahl eines Produktprofils in der [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Abbildung: Hinzufügen eines Administrators und Auswahl eines Produktprofils in der [!DNL Admin Console].*

1. Um auf [!DNL Cloud Manager] zuzugreifen, klicken Sie auf den Link in der E-Mail mit Zugriff auf [!DNL Cloud Manager]. Alternativ können Sie [https://experience.adobe.com/de/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) in Ihrem Browser aufrufen.

1. Klicken Sie in der Benutzeroberfläche von Cloud Manager oben rechts auf **[!UICONTROL Programm hinzufügen]**.

1. Geben Sie einen Namen Ihrer Wahl ein, laden Sie optional ein Bild hoch (es stellt das Programm in [!DNL Cloud Manager] dar) und klicken Sie dann auf **[!UICONTROL Erstellen]**. [!DNL Cloud Manager] benötigt einige Minuten, bis das Programm eingerichtet ist.

1. Wenn das Programm fertig ist, bewegen Sie den Mauszeiger über die Kachel und klicken Sie auf ![Symbol für das Hinzufügen einer Umgebung](assets/do-not-localize/add-environment-icon.png).

1. Um den Service [!DNL Assets Essentials] zu Ihrer Organisation hinzuzufügen, klicken Sie auf **[!UICONTROL Umgebung hinzufügen]**, wählen Sie einen Namen und eine Implementierungsregion aus und klicken Sie auf **[!UICONTROL Speichern]**. Sie können die Implementierungsregion später nicht mehr ändern. Versuchen Sie, für [!DNL Assets Essentials] dieselbe Implementierungsregion zu wählen wie für die andere Lösung, mit der Sie [!DNL Assets Essentials] verwenden möchten. Dadurch soll der schnellstmögliche Netzwerkzugriff auf digitale Assets und die geringstmögliche Latenz gewährleistet werden.

   ![Hinzufügen einer Umgebung in [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Abbildung: Hinzufügen einer Umgebung in [!DNL Cloud Manager], um mit der Verwendung von [!DNL Assets Essentials] zu beginnen.*

1. Nach einigen Minuten, wenn die Umgebung erfolgreich erstellt wurde, können Sie auf die [!DNL Admin Console] zugreifen und die Benutzer Ihrer Organisation zur [!DNL Assets Essentials]-Lösung hinzufügen. Klicken Sie auf ![Optionssymbol](assets/do-not-localize/options-ellipses-icon.png) und wählen Sie die Option **[!UICONTROL Zugriff verwalten]** aus.

   ![Einsatzbereite Umgebung in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Abbildung: Eine Umgebung in [!DNL Cloud Manager], die einsatzbereit ist.*

## Benutzerverwaltung {#add-users-to-essentials}

Ein Administrator verwaltet, welche Benutzer Zugriff auf [!DNL Assets Essentials] haben. Administratoren verwenden die [!DNL Adobe Admin Console], um Benutzerzugriff hinzuzufügen oder zu entfernen. [!DNL Assets Essentials] verfügt über die folgenden beiden Arten von Benutzerzugriff.

* Benutzer von **[!DNL Assets Essentials]** haben Zugriff auf die gesamte Benutzeroberfläche. Diese Benutzer können digitale Assets hochladen, organisieren, taggen und suchen.
* Endverbraucher-Benutzer von **[!DNL Assets Essentials]** haben Zugriff auf das eingebettete Asset-Auswahlerlebnis im E-Mail-Vorlageneditor von [!DNL Adobe Journey Optimizer]. Weitere Informationen finden Sie unter [Verwenden von  [!DNL Assets Essentials]  in  [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html?lang=de).

In der [!DNL Admin Console] werden diese beiden Zugriffstypen durch zwei [!UICONTROL Produktprofile] dargestellt. Gehen Sie wie folgt vor, um Mitglieder Ihrer Organisation zu einem der beiden Profile hinzuzufügen oder daraus zu entfernen:

1. Greifen Sie auf die [!DNL Admin Console] für Ihr Unternehmen zu, klicken Sie in der oberen Leiste auf **[!UICONTROL Produkte]**, klicken Sie auf **[!UICONTROL AEM Assets Essentials]** und klicken Sie dann auf die [!DNL Assets Essentials]-Umgebung. [!DNL Assets Essentials] verfügt über zwei Produktprofile, die den Zugriff für reguläre Benutzer und Endverbraucher-Benutzer darstellen.

   ![Zwei Profile für zwei Benutzertypen](assets/adminconsole-user-types.png)

   *Abbildung: Zwei Profile stehen zur Verfügung, um die beiden Benutzertypen hinzuzufügen.*

1. Um einen Benutzer zu einer Gruppe hinzuzufügen, klicken Sie auf die Gruppe, wählen Sie **[!UICONTROL Benutzer hinzufügen]**, geben Sie die Benutzerdetails an und klicken Sie auf **[!UICONTROL Speichern]**. Wenn Sie einen Benutzer hinzufügen, erhält der Benutzer eine Einladung per E-Mail. Sie können die E-Mail-Einladungen in den Produktprofileinstellungen in der [!DNL Admin Console] deaktivieren.

   ![Benutzer hinzufügen zu [!DNL Assets Essentials]](assets/adminconsole-add-user.png) 

   *Abbildung: Hinzufügen eines Benutzers zu [!DNL Assets Essentials] von der [!DNL Admin Console] aus.*

1. Um einen Benutzer aus einer Gruppe zu entfernen, klicken Sie auf die Gruppe, wählen Sie einen vorhandenen Benutzer aus und wählen Sie **[!UICONTROL Benutzer entfernen]** aus.

>[!TIP]
>
>In der [!DNL Admin Console] können Sie die Benutzer mithilfe von CSV-Dateien stapelweise verwalten. Weitere Informationen finden Sie in der [[!DNL Admin Console] -Dokumentation](https://helpx.adobe.com/de/enterprise/using/accounts.html).

## Anzeigen von Service-Status und Zugriffsprotokollen {#view-logs}

Nach der Implementierung stellen Administratoren [!DNL Assets Essentials] nur einmal bereit. Nach der ersten Implementierung führt Adobe die Wartungsarbeiten und Aktualisierungen des Services durch. Administratoren können die [!DNL Cloud Manager]-Benutzeroberfläche verwenden, um den Service-Status zu überprüfen und die aktuellen Zugriffsprotokolle herunterzuladen.

1. Wenn Benutzer Probleme melden, überprüfen Sie den Service-Status von [!DNL Assets Essentials] in der Benutzeroberfläche der **[!UICONTROL Programmübersicht]**. Wenn die Lösung normal funktioniert, ist der Status `Running`. Wenn [!DNL Cloud Manager] einen anderen Status anzeigt, erstellen Sie ein Support-Ticket im Support-Abschnitt der [!DNL Admin Console].

   ![Der Status von [!DNL Assets Essentials] in [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Abbildung: Der normale Status von [!DNL Assets Essentials] in [!DNL Cloud Manager] lautet `Running`.*

1. Um die aktuellen Zugriffsprotokolle herunterzuladen, klicken Sie auf ![Optionssymbol](assets/do-not-localize/options-ellipses-icon.png), wählen Sie **[!UICONTROL Protokolle herunterladen]** und befolgen Sie die Anweisungen auf dem Bildschirm. Sie können die HTTPS-Zugriffsanfragen mithilfe der Protokolle überprüfen.

   ![Option zum Herunterladen der Zugriffsprotokolle](assets/cloudmanager-download-logs.png)

   *Abbildung: Option zum Herunterladen der Zugriffsprotokolle.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] -Hilfe](https://helpx.adobe.com/de/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] -Hilfe](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=de)
>* [Dokumentation zu Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=de)
>* [Versionshinweise](release-notes.md)
>* [Erste Schritte mit [!DNL Assets Essentials]](get-started.md)

