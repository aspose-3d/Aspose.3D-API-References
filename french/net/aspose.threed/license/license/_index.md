---
title: "License.License"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Constructeur License. Initialise une nouvelle instance de cette classe"
type: docs
weight: 10
url: /fr/net/aspose.threed/license/license/
---
## License constructor

Initialise une nouvelle instance de cette classe.

```csharp
public License()
```

## Exemples

Dans cet exemple, une tentative sera faite pour trouver un fichier de licence nommé MyLicense.lic dans le dossier contenant le composant, dans le dossier contenant l'assembly appelant, dans le dossier de l'assembly d'entrée, puis dans les ressources incorporées de l'assembly appelant.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

le fichier jar du composant:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### Voir aussi

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)


