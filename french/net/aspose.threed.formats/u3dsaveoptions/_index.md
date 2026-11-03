---
title: "Classe U3dSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.U3dSaveOptions. Options d'enregistrement pour le 3D universel"
type: docs
weight: 1530
url: /fr/net/aspose.threed.formats/u3dsaveoptions/
---
## U3dSaveOptions class

Options d'enregistrement pour le 3D universel

```csharp
public class U3dSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [U3dSaveOptions](u3dsaveoptions/)() | Constructeur de `U3dSaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [EmbedTextures](../../aspose.threed.formats/u3dsaveoptions/embedtextures/) { get; set; } | Intègre les textures externes dans le fichier U3D, la valeur par défaut est false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportNormals](../../aspose.threed.formats/u3dsaveoptions/exportnormals/) { get; set; } | Obtient ou définit si les données normales doivent être exportées. |
| [ExportTextureCoordinates](../../aspose.threed.formats/u3dsaveoptions/exporttexturecoordinates/) { get; set; } | Obtient ou définit si les coordonnées de texture doivent être exportées. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [ExportVertexDiffuse](../../aspose.threed.formats/u3dsaveoptions/exportvertexdiffuse/) { get; set; } | Obtient ou définit si la couleur diffuse des sommets doit être exportée. |
| [ExportVertexSpecular](../../aspose.threed.formats/u3dsaveoptions/exportvertexspecular/) { get; set; } | Obtient ou définit si la couleur spéculaire du sommet doit être exportée. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipCoordinateSystem](../../aspose.threed.formats/u3dsaveoptions/flipcoordinatesystem/) { get; set; } | Obtient ou définit si le système de coordonnées des points de contrôle/normales doit être inversé lors de l'importation/exportation. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [MeshCompression](../../aspose.threed.formats/u3dsaveoptions/meshcompression/) { get; set; } | Obtient ou définit si la compression des données de maillage doit être activée. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


