---
title: "Classe AmfSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.AmfSaveOptions. Options d'enregistrement pour AMF"
type: docs
weight: 1090
url: /fr/net/aspose.threed.formats/amfsaveoptions/
---
## AmfSaveOptions class

Options d'enregistrement pour AMF

```csharp
public class AmfSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [AmfSaveOptions](amfsaveoptions/)() | Constructeur de `AmfSaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [EnableCompression](../../aspose.threed.formats/amfsaveoptions/enablecompression/) { get; set; } | Indique s'il faut utiliser la compression pour réduire la taille finale du fichier, valeur par défaut : true |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


