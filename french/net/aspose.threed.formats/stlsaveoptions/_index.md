---
title: "Classe StlSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.StlSaveOptions. Options d'enregistrement pour STL"
type: docs
weight: 1510
url: /fr/net/aspose.threed.formats/stlsaveoptions/
---
## StlSaveOptions class

Options d'enregistrement pour STL

```csharp
public class StlSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [StlSaveOptions](stlsaveoptions/#constructor)() | Initialise une nouvelle instance de `StlSaveOptions`. |
| [StlSaveOptions](stlsaveoptions/#constructor_1)(FileContentType) | Initialise une nouvelle instance de `StlSaveOptions`. |

## Propriétés

| Nom | Description |
| --- | --- |
| [AxisSystem](../../aspose.threed.formats/stlsaveoptions/axissystem/) { get; set; } | Obtient ou définit le système d'axes dans le fichier STL exporté. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipCoordinateSystem](../../aspose.threed.formats/stlsaveoptions/flipcoordinatesystem/) { get; set; } | Obtient ou définit si le système de coordonnées des points de contrôle/normales doit être inversé lors de l'exportation. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


