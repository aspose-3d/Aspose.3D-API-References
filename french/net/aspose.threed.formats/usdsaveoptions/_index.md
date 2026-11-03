---
title: "Classe UsdSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Formats.UsdSaveOptions classe. Options d'enregistrement pour les formats USD/USDZ"
type: docs
weight: 1540
url: /fr/net/aspose.threed.formats/usdsaveoptions/
---
## UsdSaveOptions class

Options d'enregistrement pour les formats USD/USDZ.

```csharp
public class UsdSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [UsdSaveOptions](usdsaveoptions/#constructor)() | Initialisez un nouveau `UsdSaveOptions` avec le format [`USD`](../../aspose.threed/fileformat/usd/) |
| [UsdSaveOptions](usdsaveoptions/#constructor_1)(FileFormat) | Initialisez un nouveau `UsdSaveOptions` avec le format USD/USDZ spécifié. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportMetaData](../../aspose.threed.formats/usdsaveoptions/exportmetadata/) { get; set; } | Exportez les propriétés du nœud via le champ customData d'USD. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [MaterialConverter](../../aspose.threed.formats/usdsaveoptions/materialconverter/) { get; set; } | Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si cela n'est pas assigné, l'exportateur USD convertira automatiquement le matériau standard en matériau PBR. Valeur par défaut : null |
| [PrimitiveToMesh](../../aspose.threed.formats/usdsaveoptions/primitivetomesh/) { get; set; } | Convertissez les entités primitives en maillage lors de l'exportation. Ou encodez directement les primitives dans le fichier de sortie (utilisera la définition d'extension d'Aspose pour les primitives non officielles comme Dish, Torus). Valeur par défaut : true. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


