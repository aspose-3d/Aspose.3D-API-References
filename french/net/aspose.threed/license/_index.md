---
title: "Classe License"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.License. Fournit des méthodes pour licencier le composant"
type: docs
weight: 1610
url: /fr/net/aspose.threed/license/
---
## License class

Fournit des méthodes pour licencier le composant.

```csharp
public class License
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [License](license/)() | Initialise une nouvelle instance de cette classe. |

## Méthodes

| Nom | Description |
| --- | --- |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense)(Stream) | Licence le composant. |
| [SetLicense](../../aspose.threed/license/setlicense/#setlicense_1)(string) | Licence le composant. |

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

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


