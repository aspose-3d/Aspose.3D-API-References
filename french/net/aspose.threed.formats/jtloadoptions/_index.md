---
title: "Classe JtLoadOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.JtLoadOptions. Options de chargement pour Siemens JT"
type: docs
weight: 1310
url: /fr/net/aspose.threed.formats/jtloadoptions/
---
## JtLoadOptions class

Options de chargement pour Siemens JT

```csharp
public class JtLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [JtLoadOptions](jtloadoptions/)() | Le constructeur par défaut. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [LoadPMI](../../aspose.threed.formats/jtloadoptions/loadpmi/) { get; set; } | Charge les informations PMI du fichier JT si possible, les données seront enregistrées en tant que propriété "PMI" de [`AssetInfo`](../../aspose.threed/scene/assetinfo/). La valeur par défaut est false. |
| [LoadProperties](../../aspose.threed.formats/jtloadoptions/loadproperties/) { get; set; } | Charge les propriétés depuis la table de propriétés du JT en tant que propriétés Aspose.3D. La valeur par défaut est false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


