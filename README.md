# Web-App für Rechnungs-Upload

Die Web-App beinhaltet ein Formular für den Rechnungs-Upload.
Die Rechnungen werden in eine Liste in SharePoint Online hochgeladen.

![image](https://user-images.githubusercontent.com/20394732/45976653-a4821680-c047-11e8-879d-3af31faf0ad9.png)

## Authentifizierung

Die Nutzer müssen sich an Office 365 authentifizieren, bevor sie auf die Webseite kommen.
Dafür muss eine App in Azure Active Directory registriert werden.
Die generierte Client ID muss dann in der appsettings.json hinterlegt werden.

Siehe Anleitung: https://azure.microsoft.com/en-us/resources/samples/active-directory-dotnet-webapp-openidconnect-aspnetcore/
