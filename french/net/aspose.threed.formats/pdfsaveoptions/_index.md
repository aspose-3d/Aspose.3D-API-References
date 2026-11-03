---
title: "Classe PdfSaveOptions"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.PdfSaveOptions. Les options d'enregistrement lors de l'exportation PDF"
type: docs
weight: 1420
url: /fr/net/aspose.threed.formats/pdfsaveoptions/
---
## PdfSaveOptions class

Les options d'enregistrement lors de l'exportation PDF.

```csharp
public class PdfSaveOptions : SaveOptions
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [PdfSaveOptions](pdfsaveoptions/)() | Constructeur de `PdfSaveOptions` |

## Propriétés

| Nom | Description |
| --- | --- |
| [AuxiliaryColor](../../aspose.threed.formats/pdfsaveoptions/auxiliarycolor/) { get; set; } | Obtient ou définit la couleur auxiliaire à utiliser lors du rendu du contenu 3D. L'interprétation de cette couleur dépend du [`RenderMode`](./rendermode/) |
| [BackgroundColor](../../aspose.threed.formats/pdfsaveoptions/backgroundcolor/) { get; set; } | Couleur d'arrière-plan de la vue 3D dans le fichier PDF. |
| [EmbedTextures](../../aspose.threed.formats/pdfsaveoptions/embedtextures/) { get; set; } | Intègre les textures externes dans le fichier PDF, la valeur par défaut est false. |
| [Encoding](../../aspose.threed.formats/ioconfig/encoding/) { get; set; } | Obtient ou définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser. |
| [ExportTextures](../../aspose.threed.formats/saveoptions/exporttextures/) { get; set; } | Essaye de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [FaceColor](../../aspose.threed.formats/pdfsaveoptions/facecolor/) { get; set; } | Obtient ou définit la couleur de face à utiliser lors du rendu du contenu 3D. Cela n'est pertinent que lorsque le [`RenderMode`](./rendermode/) a la valeur Illustration. |
| [FileFormat](../../aspose.threed.formats/ioconfig/fileformat/) { get; } | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [FileName](../../aspose.threed.formats/ioconfig/filename/) { get; set; } | Le nom de fichier de la scène exportée/importée. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ. |
| [FileSystem](../../aspose.threed.formats/ioconfig/filesystem/) { get; set; } | Permet à l'utilisateur de gérer la façon de gérer les dépendances externes pendant le chargement/enregistrement. |
| [FlipCoordinateSystem](../../aspose.threed.formats/pdfsaveoptions/flipcoordinatesystem/) { get; set; } | Obtient ou définit le retournement du système de coordonnées de la scène lors de l'exportation. |
| [LightingScheme](../../aspose.threed.formats/pdfsaveoptions/lightingscheme/) { get; set; } | LightingScheme spécifie l'éclairage à appliquer aux œuvres 3D. |
| [LookupPaths](../../aspose.threed.formats/ioconfig/lookuppaths/) { get; set; } | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettront à Aspose.3D de rechercher le fichier externe à charger. |
| [RenderMode](../../aspose.threed.formats/pdfsaveoptions/rendermode/) { get; set; } | Le mode de rendu spécifie le style dans lequel l'œuvre 3D est rendue. |

### Voir aussi

* class [SaveOptions](../saveoptions/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


