---
title: "Classe PdfFormat"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Formats.PdfFormat. Format de document portable d'Adobe"
type: docs
weight: 1380
url: /fr/net/aspose.threed.formats/pdfformat/
---
## PdfFormat class

Format de document portable d'Adobe

```csharp
public class PdfFormat : FileFormat
```

## Propriétés

| Nom | Description |
| --- | --- |
| [CanExport](../../aspose.threed/fileformat/canexport/) { get; } | Obtient si Aspose.3D prend en charge l'exportation de la scène vers le format de fichier actuel. |
| [CanImport](../../aspose.threed/fileformat/canimport/) { get; } | Obtient si Aspose.3D prend en charge l'importation de la scène depuis le format de fichier actuel. |
| [ContentType](../../aspose.threed/fileformat/contenttype/) { get; } | Obtient le type de contenu du format de fichier |
| [Extension](../../aspose.threed/fileformat/extension/) { get; } | Obtient le nom d'extension de ce type. |
| [Extensions](../../aspose.threed/fileformat/extensions/) { get; } | Obtient les noms d'extension de ce type. |
| [FileFormatType](../../aspose.threed/fileformat/fileformattype/) { get; } | Obtient le type de format de fichier |
| [Version](../../aspose.threed/fileformat/version/) { get; } | Obtient la version du format de fichier |

## Méthodes

| Nom | Description |
| --- | --- |
| [CreateLoadOptions](../../aspose.threed/fileformat/createloadoptions/)() | Crée des options de chargement par défaut pour ce format de fichier |
| [CreateSaveOptions](../../aspose.threed/fileformat/createsaveoptions/)() | Crée des options d'enregistrement par défaut pour ce format de fichier |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract)(Stream, byte[]) | Extraire le contenu 3D brut du flux PDF. |
| [Extract](../../aspose.threed.formats/pdfformat/extract/#extract_1)(string, byte[]) | Extraire le contenu 3D brut du fichier PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_1)(string) | Extraire les scènes 3D du fichier PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene)(Stream, byte[]) | Extraire le contenu 3D brut du flux PDF. |
| [ExtractScene](../../aspose.threed.formats/pdfformat/extractscene/#extractscene_2)(string, byte[]) | Extraire les scènes 3D du fichier PDF. |
| override [ToString](../../aspose.threed/fileformat/tostring/)() | Formate en chaîne |

## Exemples

Le code suivant montre comment extraire toutes les scènes 3D prises en charge d'un fichier PDF 3D, et les écrire au format obj.

```csharp
var scenes = FileFormat.PDF.ExtractScene("input.pdf");
for(int i = 0; i < scenes.Count; i++) 
{
    scenes[i].Save($"output-{i}.obj");
}
```

### Voir aussi

* class [FileFormat](../../aspose.threed/fileformat/)
* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


