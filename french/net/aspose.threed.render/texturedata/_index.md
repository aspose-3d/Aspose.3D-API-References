---
title: "Classe TextureData"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Classe Aspose.ThreeD.Render.TextureData. Cette classe contient les données brutes et la définition du format d'une texture"
type: docs
weight: 2460
url: /fr/net/aspose.threed.render/texturedata/
---
## TextureData class

Cette classe contient les données brutes et la définition du format d'une texture.

```csharp
public class TextureData : A3DObject
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextureData](texturedata/#constructor)() | Constructeur de `TextureData` |
| [TextureData](texturedata/#constructor_1)(int, int, PixelFormat) | Construit un nouveau `TextureData` et alloue les données de pixels. |
| [TextureData](texturedata/#constructor_2)(int, int, int, int, PixelFormat, byte[]) | Constructeur de `TextureData` |

## Propriétés

| Nom | Description |
| --- | --- |
| [BytesPerPixel](../../aspose.threed.render/texturedata/bytesperpixel/) { get; } | Nombre d'octets d'un pixel |
| [Data](../../aspose.threed.render/texturedata/data/) { get; } | Octets bruts des données de pixel |
| [Height](../../aspose.threed.render/texturedata/height/) { get; } | Nombre de pixels verticaux |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtient ou définit le nom. |
| [PixelFormat](../../aspose.threed.render/texturedata/pixelformat/) { get; } | Le format du pixel |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtient la collection de toutes les propriétés. |
| [Stride](../../aspose.threed.render/texturedata/stride/) { get; } | Nombre d'octets d'une ligne de balayage. |
| [Width](../../aspose.threed.render/texturedata/width/) { get; } | Nombre de pixels horizontaux |

## Méthodes

| Nom | Description |
| --- | --- |
| static [FromFile](../../aspose.threed.render/texturedata/fromfile/)(string) | Charger une texture depuis un fichier |
| static [FromStream](../../aspose.threed.render/texturedata/fromstream/)(Stream) | Charger une texture depuis un flux |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtenir la valeur de la propriété spécifiée |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels)(PixelMapMode) | Mapper tous les pixels en lecture/écriture |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_1)(PixelMapMode, PixelFormat) | Mapper tous les pixels en lecture/écriture dans le format de pixel donné |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_2)(Rect, PixelMapMode, PixelFormat) | Mapper les pixels délimités par un rectangle pour la lecture/écriture dans le format de pixel donné |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Supprime une propriété dynamique. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Supprime la propriété spécifiée identifiée par son nom |
| [Save](../../aspose.threed.render/texturedata/save/#save_1)(string) | Enregistrer les données de texture dans un fichier image |
| [Save](../../aspose.threed.render/texturedata/save/#save)(Stream, string) | Enregistrer les données de texture dans le format d'image spécifié |
| [Save](../../aspose.threed.render/texturedata/save/#save_2)(string, string) | Enregistrer les données de texture dans un fichier image |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Définit la valeur de la propriété spécifiée |
| [TransformPixelFormat](../../aspose.threed.render/texturedata/transformpixelformat/)(PixelFormat) | Transformer la disposition du pixel vers un nouveau format de pixel. |

### Voir aussi

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


