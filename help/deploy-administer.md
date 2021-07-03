---
title: Bereitstellen und Verwalten von Benutzern
description: Anwendungsfälle für Administratoren, wie z. B. Bereitstellung und Benutzerverwaltung in [!DNL Assets Essentials].
role: Admin
source-git-commit: a1dc66213f602bce5b5a2ec0ba99084c7f7b1ee1
workflow-type: tm+mt
source-wordcount: '887'
ht-degree: 2%

---


# [!DNL Assets Essentials] bereitstellen und Benutzer hinzufügen {#administer}

[!DNL Adobe Experience Manager Assets Essentials] wird von Adobe für seine Kunden bereitgestellt. Im Rahmen der Bereitstellung wird [!DNL Assets Essentials] zur Organisation eines Kunden in [!DNL Adobe Admin Console] hinzugefügt. Die Kunden haben auch Zugriff auf [!DNL Experience Manager Cloud Manager] als Bereitstellungswerkzeug und auf [!DNL Admin Console], um Benutzerberechtigungen für die [!DNL Assets Essentials] -Lösung zu verwalten.

Administratoren führen die folgenden Aufgaben aus:

* [ [!DNL Assets Essentials]](#deploy-essentials) Stellen Sie für ihre Organisation bereit.
* [Verwalten Sie den Benutzerzugriff ](#add-users-to-essentials) von Organisationsmitgliedern auf  [!DNL Assets Essentials].
* Optional können Sie [den Dienststatus und die Protokolle](#view-logs) anzeigen.

## Bereitstellen [!DNL Assets Essentials] {#deploy-essentials}

Nach der Bereitstellung wird Ihrer Organisation die Berechtigung [!DNL Assets Essentials] in [!DNL Admin Console] hinzugefügt. Bevor die Lösung für den Benutzer verfügbar ist, muss sie von einem Organisationsadministrator bereitgestellt werden. Der Administrator führt eine einmalige Bereitstellung über die [!DNL Cloud Manager] -Benutzeroberfläche durch. Nach der ersten Bereitstellung führt Adobe die Wartungsarbeiten und Aktualisierungen des Dienstes durch. Nachdem die Lösung bereitgestellt wurde, erhält der Administrator eine E-Mail von Adobe. Die E-Mail enthält eine Begrüßungsnachricht und einen Link zu den ersten Schritten. Gehen Sie zur Bereitstellung wie folgt vor:

1. Greifen Sie über den Link in der E-Mail auf [Admin Console](https://adminconsole.adobe.com) zu und melden Sie sich an. Wenn Sie Administratorzugriff auf mehr als ein Unternehmenskonto haben, wählen Sie die entsprechende Organisation aus oder wechseln Sie mithilfe des Switchers in der oberen Leiste zu ihr. Die Produktkarte für [!DNL Assets Essentials] ist im [!DNL Admin Console] sichtbar.

   ![[!DNL Assets Essentials] Karte in  [!DNL Admin Console]](assets/essentials-in-admin-console.png)

   *Abbildung:  [!DNL Assets Essentials] Karte in  [!DNL Admin Console].*

1. Fügen Sie sich als Administrator dem `AEM Assets Essentials - Cloud Manager` -Produktprofil im [!DNL Admin Console] hinzu. Statt Ihnen können Sie ein anderes Mitglied Ihrer Organisation hinzufügen oder mehr als einen Administrator hinzufügen.

1. Klicken Sie auf ![Symbol](assets/do-not-localize/add-icon.svg) zu [!UICONTROL Wählen Sie Produktprofile] aus und wählen Sie dann [!UICONTROL Deployment Manager - Assets Essentials] als **[!UICONTROL Produktprofil]** aus. Der in diesem Schritt hinzugefügte Benutzer erhält eine E-Mail von Adobe mit Zugriff auf [!DNL Cloud Manager] und kann die Bereitstellung durchführen.

   ![Fügen Sie einen Administrator hinzu und wählen Sie ein Produktprofil in  [!DNL Admin Console]](assets/adminconsole-user1.png)

   *Abbildung: Fügen Sie einen Administrator hinzu und wählen Sie ein Produktprofil in  [!DNL Admin Console]aus.*

1. Um auf [!DNL Cloud Manager] zuzugreifen, klicken Sie auf den Link in der E-Mail mit Zugriff auf [!DNL Cloud Manager]. Alternativ können Sie [https://experience.adobe.com/#/cloud-manager/](https://experience.adobe.com/#/cloud-manager/) in Ihrem Browser aufrufen.

1. Klicken Sie in der Cloud Manager-Benutzeroberfläche oben rechts auf **[!UICONTROL Programm]** hinzufügen .

1. Geben Sie einen Namen Ihrer Wahl ein, laden Sie optional ein Bild hoch (es stellt das Programm in [!DNL Cloud Manager] dar) und klicken Sie dann auf **[!UICONTROL Erstellen]**. [!DNL Cloud Manager] Es dauert einige Minuten, bis das Programm eingerichtet ist.

1. Wenn das Programm fertig ist, bewegen Sie den Mauszeiger über die Kachel und klicken Sie auf ![Umgebungssymbol hinzufügen](assets/do-not-localize/add-environment-icon.png).

1. Um den Dienst [!DNL Assets Essentials] zu Ihrer Organisation hinzuzufügen, klicken Sie auf **[!UICONTROL Umgebung hinzufügen]**, wählen Sie einen Namen und eine Bereitstellungsregion aus und klicken Sie auf **[!UICONTROL Speichern]**. Sie können die Bereitstellungsregion nicht später ändern. Versuchen Sie, den Bereitstellungsbereich von [!DNL Assets Essentials] mit dem Bereitstellungsbereich der anderen Lösung abzugleichen, mit der Sie [!DNL Assets Essentials] verwenden möchten. Dabei soll der schnellstmögliche Netzwerkzugriff auf digitale Assets und die geringstmögliche Latenz gewährleistet werden.

   ![Hinzufügen einer Umgebung in  [!DNL Cloud Manager]](assets/cloudmanager-add-environment-for-essentials.png)

   *Abbildung: Fügen Sie eine Umgebung in  [!DNL Cloud Manager] hinzu, um mit der Verwendung von  [!DNL Assets Essentials]zu beginnen.*

1. Nach einigen Minuten, wenn die Umgebung erfolgreich erstellt wurde, können Sie auf [!DNL Admin Console] zugreifen und die Benutzer Ihrer Organisation zur [!DNL Assets Essentials] -Lösung hinzufügen. Klicken Sie auf das Symbol ![Optionen](assets/do-not-localize/options-ellipses-icon.png) und wählen Sie die Option **[!UICONTROL Zugriff verwalten]** aus.

   ![Bereitgestellte Umgebung in  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Abbildung: Eine Umgebung in ,  [!DNL Cloud Manager] die einsatzbereit ist.*

## Benutzerverwaltung {#add-users-to-essentials}

Ein Administrator verwaltet, welche Benutzer Zugriff auf [!DNL Assets Essentials] haben. Administratoren verwenden [!DNL Adobe Admin Console], um Benutzerzugriff hinzuzufügen oder zu entfernen. [!DNL Assets Essentials] verfügt über die folgenden beiden Arten von Benutzerzugriff.

* **[!DNL Assets Essentials]** Benutzer haben Zugriff auf die gesamte Benutzeroberfläche. Diese Benutzer können digitale Assets hochladen, organisieren, taggen und suchen.
* **[!DNL Assets Essentials]Verbraucher**: Sie haben Zugriff auf das eingebettete Asset-Auswahlerlebnis im  [!DNL Adobe Journey Optimizer] E-Mail-Vorlageneditor. Weitere Informationen finden Sie unter [Verwendung [!DNL Assets Essentials] in [!DNL Journey Optimizer]](https://experienceleague.adobe.com/docs/journey-optimizer/using/create-messages/assets-essentials.html).

In [!DNL Admin Console] werden diese beiden Zugriffstypen durch zwei [!UICONTROL Produktprofile] dargestellt. Gehen Sie wie folgt vor, um Mitglieder Ihrer Organisation zu einem der beiden Profile hinzuzufügen und daraus zu entfernen:

1. Rufen Sie [!DNL Admin Console] für Ihr Unternehmen auf, klicken Sie in der oberen Leiste auf **[!UICONTROL Produkte]**, klicken Sie auf **[!UICONTROL AEM Assets Essentials]** und klicken Sie dann auf die Umgebung [!DNL Assets Essentials] . [!DNL Assets Essentials] verfügt über zwei Produktprofile, die den Zugriff für reguläre Benutzer und Verbraucher darstellen.

   ![Zwei Profile für zwei Benutzertypen](assets/adminconsole-user-types.png)

   *Abbildung: Zwei Profile stehen zur Verfügung, um die beiden Benutzertypen hinzuzufügen.*

1. Um einen Benutzer zu einer Gruppe hinzuzufügen, klicken Sie auf die Gruppe, wählen Sie **[!UICONTROL Benutzer hinzufügen]**, geben Sie die Benutzerdetails an und klicken Sie auf **[!UICONTROL Speichern]**. Wenn Sie einen Benutzer hinzufügen, erhält der Benutzer eine Einladung per E-Mail, um zu beginnen. Sie können die E-Mail-Einladungen in den Produktprofileinstellungen in [!DNL Admin Console] deaktivieren.

   ![Benutzer hinzufügen zu  [!DNL Assets Essentials]](assets/adminconsole-add-user.png)

   *Abbildung: Fügen Sie einen Benutzer zu  [!DNL Assets Essentials] von  [!DNL Admin Console]hinzu.*

1. Um einen Benutzer aus einer Gruppe zu entfernen, klicken Sie auf die Gruppe, wählen Sie einen vorhandenen Benutzer aus und wählen Sie **[!UICONTROL Benutzer entfernen]** aus.

>[!TIP]
>
>In [!DNL Admin Console] können Sie die Benutzer mithilfe von CSV-Dateien stapelweise verwalten. Weitere Informationen finden Sie unter [[!DNL Admin Console] Dokumentation](https://helpx.adobe.com/enterprise/using/accounts.html).

## Anzeigen des Dienststatus und Zugriffsprotokolle {#view-logs}

Nach der Bereitstellung stellen Administratoren [!DNL Assets Essentials] nur einmal bereit. Nach der ersten Bereitstellung führt Adobe die Wartungsarbeiten und Aktualisierungen des Dienstes durch. Administratoren können die [!DNL Cloud Manager]-Benutzeroberfläche verwenden, um den Dienststatus zu überprüfen und die aktuellen Zugriffsprotokolle herunterzuladen.

1. Wenn Benutzer Probleme melden, überprüfen Sie den Dienststatus von [!DNL Assets Essentials] in der **[!UICONTROL Programmübersicht]**-Benutzeroberfläche. Während der normalen Arbeit der Lösung ist der Status `Running`. Wenn [!DNL Cloud Manager] einen anderen Status anzeigt, erstellen Sie ein Support-Ticket im Abschnitt [!DNL Admin Console] Support .

   ![Der Status von  [!DNL Assets Essentials] in  [!DNL Cloud Manager]](assets/cloudmanager-manage-access-essentials.png)

   *Abbildung: Der Normalstatus von  [!DNL Assets Essentials] in  [!DNL Cloud Manager] lautet  `Running`.*

1. Um die aktuellen Zugriffsprotokolle herunterzuladen, klicken Sie auf das Symbol ![Optionen](assets/do-not-localize/options-ellipses-icon.png), wählen Sie **[!UICONTROL Protokolle herunterladen]** und befolgen Sie die Anweisungen auf dem Bildschirm. Sie können die HTTPS-Zugriffsanforderungen mithilfe der Protokolle überprüfen.

   ![ Option zum Herunterladen der Zugriffsprotokolle](assets/cloudmanager-download-logs.png)

   *Abbildung: Option zum Herunterladen der Zugriffsprotokolle.*

>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] help](https://helpx.adobe.com/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] help](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=de)
>* [Adobe Journey Optimizer-Dokumentation](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html)
>* [Versionshinweise](release-notes.md)
* [Erste Schritte mit  [!DNL Assets Essentials]](get-started.md)

