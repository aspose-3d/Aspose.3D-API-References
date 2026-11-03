---
title: "FileFormat.GetFormatByExtension"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode FileFormat. Obtient le format de fichier préféré à partir du nom d'extension. Le nom d'extension doit commencer par un point."
type: docs
weight: 470
url: /fr/net/aspose.threed/fileformat/getformatbyextension/
---
## FileFormat.GetFormatByExtension method

Obtient le format de fichier préféré à partir du nom d'extension du fichier. Le nom d'extension doit commencer par un point ('.').

```csharp
public static FileFormat GetFormatByExtension(string extensionName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| extensionName | String | Le nom d'extension commence par '.' pour interroger. |

### Valeur de retour

Instance de [`FileFormat`](../), sinon null retourné.

## Exemples

Le code suivant montre comment enregistrer la scène en mémoire en utilisant le format spécifié

```csharp
Scene scene = new Scene(new Box());
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
using(var ms = new MemoryStream())
{
    scene.Save(ms, format);
}
```

### Voir aussi

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


