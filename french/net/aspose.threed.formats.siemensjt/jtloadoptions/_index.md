---
title: "Classe JtLoadOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.SiemensJT.JtLoadOptions. Options de chargement pour Siemens JT"
type: docs
weight: 1380
url: /fr/net/aspose.threed.formats.siemensjt/jtloadoptions/
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
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. (Hérité de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrer/Charger actuelle. (Hérité de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. (Hérité de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes lors du chargement/enregistrement. (Hérité de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |
| [LoadPMI](../../aspose.threed.formats.siemensjt/jtloadoptions/loadpmi/) { get; set; } | Charge les informations PMI du fichier JT si possible, les données seront enregistrées en tant que propriété "PMI" de [`AssetInfo`](../../aspose.threed/scene/assetinfo/). La valeur par défaut est false. |
| [LoadProperties](../../aspose.threed.formats.siemensjt/jtloadoptions/loadproperties/) { get; set; } | Charge les propriétés depuis la table de propriétés du JT en tant que propriétés Aspose.3D. La valeur par défaut est false. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent de fichiers externes, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. (Hérité de [`IOConfig`](../../aspose.threed.formats/ioconfig/).) |

### Voir aussi

* class [LoadOptions](../../aspose.threed.formats/loadoptions/)
* namespace [Aspose.ThreeD.Formats.SiemensJT](../../aspose.threed.formats.siemensjt/)
* assembly [Aspose.3D](../../)


