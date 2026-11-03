---
title: "Classe StlLoadOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.StlLoadOptions. Options de chargement pour STL"
type: docs
weight: 1500
url: /fr/net/aspose.threed.formats/stlloadoptions/
---
## StlLoadOptions class

Options de chargement pour STL

```csharp
public class StlLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [StlLoadOptions](stlloadoptions/#constructor)() | Initialise une nouvelle instance de `StlLoadOptions`. |
| [StlLoadOptions](stlloadoptions/#constructor_1)(FileContentType) | Initialise une nouvelle instance de `StlLoadOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [RecalculateNormal](../../aspose.threed.formats/stlloadoptions/recalculatenormal/) { get; set; } | Ignore les données de normales stockées dans le fichier STL et recalcule les normales en fonction de la position des sommets. La valeur par défaut est false. |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


