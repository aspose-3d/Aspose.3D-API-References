---
title: "Classe FbxLoadOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.FbxLoadOptions. Options de chargement pour le format Fbx"
type: docs
weight: 1170
url: /fr/net/aspose.threed.formats/fbxloadoptions/
---
## FbxLoadOptions class

Options de chargement pour le format Fbx.

```csharp
public class FbxLoadOptions : LoadOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [FbxLoadOptions](fbxloadoptions/#constructor)() | Constructeur de `FbxLoadOptions` |
| [FbxLoadOptions](fbxloadoptions/#constructor_1)(FileFormat) | Constructeur de `FbxLoadOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [CompatibleMode](../../aspose.threed.formats/fbxloadoptions/compatiblemode/) { get; set; } | Obtient ou définit si le mode compatible doit être activé. Le mode compatible tentera de prendre en charge les définitions FBX non standard comme les matériaux PBR exportés par Blender. La valeur par défaut est false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [KeepBuiltinGlobalSettings](../../aspose.threed.formats/fbxloadoptions/keepbuiltinglobalsettings/) { get; set; } | Obtient ou définit si les propriétés intégrées dans GlobalSettings, qui ont un remplacement de propriété native dans [`AssetInfo`](../../aspose.threed/assetinfo/), doivent être conservées. Mettez cette valeur à true si vous souhaitez toutes les propriétés dans GlobalSettings. La valeur par défaut est false |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |

### Voir aussi

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


