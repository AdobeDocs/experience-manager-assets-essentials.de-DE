---
title: Verwalten von Benutzern
description: Anwendungsfälle für Administratoren, wie z. B. Bereitstellen und Verwalten von Benutzern in  [!DNL Assets Essentials].
role: Admin
exl-id: ef91126f-3aee-442b-b242-a6bf4034f3dc
source-git-commit: 65200f73a954e4ebf4fbd6dc3a819acc6e0beda4
workflow-type: tm+mt
source-wordcount: '1304'
ht-degree: 99%

---

# Verwalten von [!DNL Assets Essentials] und Hinzufügen von Benutzern {#administer}

[!DNL Adobe Experience Manager Assets Essentials] wird von Adobe für seine Kunden bereitgestellt. Im Rahmen der Implementierung wird [!DNL Assets Essentials] in der [!DNL Adobe Admin Console] zur Organisation eines Kunden hinzugefügt. Administratoren verwenden die [!DNL Admin Console], um Benutzerberechtigungen für [!DNL Assets Essentials] zu verwalten, und ernennen Programmadministratoren, um Berechtigungen und Metadatenformulare in [!DNL Assets Essentials] einzurichten.


Das folgende Datenflussdiagramm zeigt die Aufgabensequenz, die ein Administrator zur Konfiguration und Verwaltung von Assets Essentials durchführen muss:

![Bereitstellen von Assets Essentials](assets/deploy-assets-essentials.svg)

## Zugang zur Admin Console {#access-admin-console}

Nachdem die Assets Essentials-Lösung bereitgestellt wurde, erhält der Administrator eine E-Mail von Adobe. Die E-Mail enthält eine Willkommensnachricht und einen Link zu den ersten Schritten. Darüber hinaus startet Adobe den Prozess zur automatischen Bereitstellung von Assets Essentials. Der Bereitstellungsprozess dauert eine Stunde.

Greifen Sie über den Link in der E-Mail auf die [Admin Console](https://adminconsole.adobe.com) zu und melden Sie sich an. Wenn Sie Administratorzugriff auf mehr als ein Konto einer Organisation haben, wählen Sie die entsprechende Organisation aus oder wechseln Sie mithilfe des [Organisationsselektors](https://helpx.adobe.com/de/enterprise/using/admin-console.html) zu ihr. Sobald der automatische Bereitstellungsprozess abgeschlossen ist, wird die Produktkarte für [!DNL AEM Assets Essentials] in [!DNL Admin Console] angezeigt.

Führen Sie mithilfe von Admin Console die folgenden Aufgaben zur Benutzerberechtigung aus:

* [Erstellen eines Assets Essentials-Anwendungsadministrators](#create-assets-essentials-administrator)

* [Hinzufügen von Benutzergruppen](#add-user-groups)

* [Hinzufügen von Benutzergruppen zu Produktprofilen](#add-users-to-product-profiles)

![Bereitstellung von Assets Essentials](assets/admin-console-cards.png)

### Erstellen eines Assets Essentials-Anwendungsadministrators {#create-assets-essentials-administrator}

Ein Admin Console-Administrator bzw. -Administratorin muss das Assets Essentials-Administratorproduktprofil einem Benutzer bzw. einer Benutzerin statt einer Benutzergruppe hinzufügen. Der Assets Essentials-Anwendungsadministrator kann dann Aufgaben wie das Erstellen einer Ordnerstruktur, das Hochladen von Assets, das Einrichten von Berechtigungen, das Einrichten von Metadatenformularen und das Erstellen öffentlicher Sammlungen verwalten. Informationen zum Zuweisen eines für die Assets Essentials-Anwendungs-Administratorprofils zu einem Benutzer bzw. einer Benutzerin finden Sie unter [Hinzufügen von Produktprofilen zu Benutzergruppen](#add-product-profiles-to-user-groups).

### Hinzufügen von Benutzergruppen {#add-user-groups}

Erstellen Sie Benutzergruppen und weisen Sie dann Ihre Benutzer den Benutzergruppen zu. Diese Benutzergruppen stehen in Assets Essentials zum Festlegen von Berechtigungen für Ordner zur Verfügung.

Informationen zum Verwalten von Benutzergruppen finden Sie unter `Create user groups` und `Edit user groups`, verfügbar unter [Verwalten von Benutzergruppen](https://helpx.adobe.com/de/enterprise/using/user-groups.html).

>[!NOTE]
>
>Wenn Ihre Admin Console so eingerichtet ist, dass sie ein externes System zur Verwaltung von Benutzer-/Gruppenzuweisungen wie Azure- oder Google-Connectoren, ein Benutzersynchronisierungs-Tool oder die User Management-Rest-API nutzt, werden Ihre Gruppen und Benutzerzuweisungen automatisch konfiguriert. Weitere Informationen finden Sie unter [Adobe Admin Console-Benutzer](https://helpx.adobe.com/de/enterprise/using/users.html).

Informationen zum Verwalten hinzugefügter Benutzender zu Benutzergruppen finden Sie unter `Add users to groups`, verfügbar unter [Verwalten von Benutzergruppen](https://helpx.adobe.com/de/enterprise/using/user-groups.html#add-users-to-groups).

### Hinzufügen von Produktprofilen zu Benutzergruppen {#add-product-profiles-to-user-groups}

Fügen Sie Benutzergruppen Produktprofile hinzu, damit diese Zugriff auf die Asset Essentials-Anwendung haben.

So fügen Sie Benutzergruppen Produktprofile hinzu:

1. Rufen Sie die [Admin Console](https://adminconsole.adobe.com) für Ihre Organisation auf, klicken Sie in der oberen Leiste auf **[!UICONTROL Produkte]**, dann auf **[!UICONTROL AEM Assets Essentials]** und anschließend auf die Instanz für [!DNL Assets Essentials]. Der Name der Instanz kann sich von dem im folgenden Screenshot unterscheiden.
   >[!NOTE]
   >
   >Die [!DNL Cloud Manager]-Instanz ist nur für spezielle Admin-Zwecke wie die Überprüfung des Service-Status und den Zugriff auf Service-Protokolle vorgesehen und kann nicht zum Hinzufügen von Benutzenden zum Produkt verwendet werden. 

   ![Admin-Profil der Admin Console](assets/assets-essentials-instance.png)

   [!DNL Assets Essentials] verfügt über drei Produktprofile, die den Zugriff für Admins, Standardbenutzer und Privatkunden darstellen.

   * **[!DNL Assets Essentials]-Administratoren** verfügen über administrativen Zugriff auf das Programm. Zusätzlich zu allen Endbenutzer-Funktionen können Programmadministratoren in dieser Gruppe auch die Berechtigungen aller Ordner und Gruppen/Benutzer im gesamten Programm-Repository verwalten.

   * Benutzer von **[!DNL Assets Essentials]** haben Zugriff auf die gesamte Benutzeroberfläche. Diese Benutzer können digitale Assets hochladen, organisieren, taggen und suchen.

   * **[!DNL Assets Essentials]-Privatkundinnen und -kunden** können Such-, Vorschau- und Download-Vorgänge in Assets Essentials durchführen. Sie können auch Assets in Adobe Journey Optimizer suchen und auswählen sowie Assets zur Verwendung in Workfront suchen und auswählen.
Weitere Informationen finden Sie unter [Integration mit anderen Lösungen](integration.md).

   ![Admin-Profil der Admin Console](assets/admin-console-admin-profile.png)

1. Um eine Benutzergruppe zum Produkt hinzuzufügen, klicken Sie auf eines der drei Assets Essentials-Produktprofile, wählen Sie **[!UICONTROL Benutzer hinzufügen]**, geben Sie die Details der Benutzergruppe ein und klicken Sie auf **[!UICONTROL Speichern]**.

   ![Hinzufügen des Administratorprofils für Benutzer](assets/add-users-admin-profile.png)

   Wenn Sie einen Benutzer hinzufügen, erhält der Benutzer eine Einladung per E-Mail. Sie können die E-Mail-Einladungen in den Produktprofileinstellungen in der [!DNL Admin Console] deaktivieren.

   >[!NOTE]
   >
   >Sie müssen einen Benutzer zum Produktprofil eines Assets Essentials-Administrators in der Admin Console hinzufügen, damit er in Assets Essentials Verwaltungsaufgaben ausführen kann. Diese Aufgaben umfassen das [Erstellen einer Ordnerstruktur](#create-folder-structure), [Verwalten von Berechtigungen für Ordner](#manage-permissions-for-folders) und [Einrichten von Metadatenformularen](#metadata-forms).

## Zugriff auf das Assets Essentials-Programm {#access-assets-essentials-application}

Nachdem Sie Benutzerberechtigungen in Admin Console vergeben haben, können Sie auf das Assets Essentials-Programm zugreifen, um die folgenden Aufgaben auszuführen:

* [Erstellen einer Ordnerstruktur](#create-folder-structure)

* [Hochladen von Assets](#upload-assets)

* [Verwaltung von Zugriffsberechtigungen für Ordner](#manage-permissions-for-folders)

* [Einrichten von Metadatenformularen](#metadata-forms)

* [Erstellen öffentlicher Sammlungen](#create-public-collections)

### Erstellen einer Ordnerstruktur {#create-folder-structure}

Sie können die folgenden Methoden verwenden, um eine Ordnerstruktur im Assets Essentials-Repository zu erstellen:

* Klicken Sie auf die Option **[!UICONTROL Ordner erstellen]** in der Symbolleiste, um einen leeren Ordner zu erstellen.

* Klicken Sie auf die Option **[!UICONTROL Assets hinzufügen]** in der Symbolleiste, um [eine auf Ihrem lokalen Computer vorhandene Ordnerstruktur hochzuladen](add-delete.md).

Erstellen Sie eine Ordnerstruktur entsprechend Ihren betrieblichen Anforderungen. Wenn Sie eine vorhandene Ordnerstruktur in das Assets Essentials-Repository hochladen, sollten Sie die Struktur überprüfen. Weitere Informationen finden Sie unter [Best Practices für die effektive Verwaltung von Zugriffsberechtigungen](permission-management-best-practices.md##folder-structure-assets-essentials).

Es gibt verschiedene mögliche Ordnerstrukturtypen, die Sie für Ihr Unternehmen verwenden können. Im Folgenden finden Sie einige Beispiele für typische Ordnerstrukturen:

![Typische Ordnerstrukturen](assets/folder-structure.svg)

>[!NOTE]
>
>Um diese Aufgaben, insbesondere die Verwaltung von Berechtigungen, durchführen zu können, müssen Ihr Benutzenden über Administratorrechte für Programme verfügen und dazu dem [Produktprofil eines Assets Essentials-Administrators](#add-users-to-product-profiles) hinzugefügt werden.

### Hochladen von Assets {#upload-assets}

Um neue Assets hinzuzufügen, mit denen Sie arbeiten können, laden Sie einige Assets aus Ihrem lokalen Dateisystem hoch. Sie können entweder Assets oder Ordner auf die Benutzeroberfläche ziehen und den Anweisungen auf dem Bildschirm folgen, oder Sie klicken auf die Option **[!UICONTROL Hinzufügen von Assets]** in der Symbolleiste und fügen einige Dateien zum Upload-Dialog hinzu. [!DNL Assets Essentials] bietet eine leistungsstarke Volltext-Suchfunktion, Sie können aber auch Ordner verwenden, um Ihre Assets besser zu organisieren. Weitere Informationen hierzu finden Sie unter [Hochladen von Assets](add-delete.md).

![Hochladen von Dateien und Ordnern](assets/upload-assets.png)

### Verwaltung von Zugriffsberechtigungen für Ordner {#manage-permissions-for-folders}

Mit Assets Essentials können Administratoren die Zugriffsebenen für Ordner verwalten, die im Repository verfügbar sind. Als Administrator können Sie Benutzergruppen erstellen und diesen Gruppen Berechtigungen zum Verwalten von Zugriffsebenen zuweisen. Sie können Benutzergruppen die Berechtigung zur Zugriffsberechtigungsverwaltung auch auf Ordnerebene zuweisen.

>[!VIDEO](https://video.tv.adobe.com/v/341104)

Weitere Informationen finden Sie unter [Verwalten von Berechtigungen für Ordner](manage-permissions.md).

### Einrichten von Metadaten-Forms (optional) {#metadata-forms}

Assets Essentials bietet standardmäßig viele Standard-Metadatenfelder. Unternehmen haben zusätzliche Metadatenanforderungen und benötigen mehr Metadatenfelder, um geschäftsspezifische Metadaten hinzuzufügen. Mit Metadatenformularen können Unternehmen benutzerdefinierte Metadatenfelder zur Seite [!UICONTROL Details] eines Assets hinzufügen. Die geschäftsspezifischen Metadaten verbessern die Verwaltung und Erkennung der Assets. Sie können Formulare von Grund auf neu erstellen oder ein vorhandenes Formular wiederverwenden.

Sie können Metadatenformulare für verschiedene Asset-Typen (verschiedene MIME-Typen) konfigurieren. Verwenden Sie denselben Formularnamen wie den MIME-Typ der Datei. Essentials passt den MIME-Typ der hochgeladenen Assets automatisch an den Namen des Formulars an und aktualisiert die Metadaten für die hochgeladenen Assets basierend auf den Formularfeldern.

Wenn beispielsweise ein Metadatenformular mit dem Namen `PDF` oder `pdf` vorhanden ist, enthalten die hochgeladenen PDF-Dokumente Metadatenfelder, wie sie im Formular definiert wurden.

Weitere Informationen finden Sie unter [Metadatenformulare](metadata.md#metadata-forms).

>[!VIDEO](https://video.tv.adobe.com/v/341275)

Weitere Informationen zu Metadatenformularen finden Sie unter [Metadatenformulare in Assets Essentials](metadata.md#metadata-forms).

### Erstellen öffentlicher Sammlungen (optional) {#create-public-collections}

Eine Sammlung ist ein Satz von Assets innerhalb von Experience Manager Assets Essentials. Anhand von Sammlungen können Assets von mehreren Benutzenden gemeinsam verwendet werden.

Im Gegensatz zu Ordnern kann eine Sammlung Assets von verschiedenen Speicherorten enthalten. Sie können mehrere Sammlungen für eine Benutzerin bzw. einen Benutzer freigeben. Jede Sammlung enthält Verweise auf Assets. Die referenzielle Integrität von Assets wird sammlungsübergreifend aufrechterhalten. Weitere Informationen finden Sie unter [Verwalten von Sammlungen](manage-collections.md).

![Sammlungen](assets/collections.png)

## Nächste Schritte {#next-steps}

<!-- THIS URL IS A 404 ERROR; NO REDIRECT WAS PUT IN PLACE * [Watch a video to deploy Assets Essentials](https://experienceleague.adobe.com/docs/experience-manager-learn/assets-essentials/provisioning.html?lang=en) -->

* Geben Sie Produkt-Feedback über die Option [!UICONTROL Feedback] in der Benutzeroberfläche von Assets Essentials

* Geben Sie Feedback zur Dokumentation durch ![Bearbeiten der Seite](assets/do-not-localize/edit-page.png) über die Option [!UICONTROL Diese Seite bearbeiten] oder durch ![Erstellen eines GitHub-Themas](assets/do-not-localize/github-issue.png) über die Option [!UICONTROL Problem protokollieren] in der rechten Seitenleiste

* Kontaktieren Sie die [Kundenunterstützung](https://experienceleague.adobe.com/de?support-solution=General&amp;lang=de#support)



>[!MORELIKETHIS]
>
>* [[!DNL Admin Console] -Hilfe](https://helpx.adobe.com/de/enterprise/using/admin-console.html)
>* [[!DNL Cloud Manager] -Hilfe](https://experienceleague.adobe.com/docs/experience-manager-cloud-manager/using/introduction-to-cloud-manager.html?lang=de)
>* [Dokumentation zu Adobe Journey Optimizer](https://experienceleague.adobe.com/docs/journey-optimizer/using/ajo-home.html?lang=de)
>* [Versionshinweise](release-notes.md)
>* [Erste Schritte mit  [!DNL Assets Essentials]](get-started.md)
