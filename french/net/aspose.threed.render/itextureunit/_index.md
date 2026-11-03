---
title: "Interface ITextureUnit"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Render.ITextureUnit interface. ITextureUnit représente une texture dans la mémoire qui est partagée entre le GPU et le CPU et peut être échantillonnée par le shader où la Texture ne représente qu'une référence à un fichier externe. Plus de détails peuvent être trouvés https//en.wikipedia.org/wiki/Texture_mapping_unit"
type: docs
weight: 2170
url: /fr/net/aspose.threed.render/itextureunit/
---
## ITextureUnit interface

`ITextureUnit` représente une texture dans la mémoire qui est partagée entre le GPU et le CPU et peut être échantillonnée par le shader, où le [`Texture`](../../aspose.threed.shading/texture/) ne représente qu'une référence à un fichier externe. Plus de détails peuvent être trouvés https://en.wikipedia.org/wiki/Texture_mapping_unit

```csharp
public interface ITextureUnit : IDisposable
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Depth](../../aspose.threed.render/itextureunit/depth/) { get; } | Obtient la hauteur de cette texture, pour une texture non 3D elle est toujours de 1. |
| [Height](../../aspose.threed.render/itextureunit/height/) { get; } | Obtient la hauteur de cette texture. |
| [Magnification](../../aspose.threed.render/itextureunit/magnification/) { get; set; } | Obtient ou définit le mode de filtrage pour l'agrandissement. |
| [Minification](../../aspose.threed.render/itextureunit/minification/) { get; set; } | Obtient ou définit le mode de filtrage pour la minification. |
| [Mipmap](../../aspose.threed.render/itextureunit/mipmap/) { get; set; } | Obtient ou définit le mode de filtrage pour le mipmap. |
| [Scale](../../aspose.threed.render/itextureunit/scale/) { get; set; } | Obtient ou définit l'échelle de la coordonnée UV. |
| [Scroll](../../aspose.threed.render/itextureunit/scroll/) { get; set; } | Obtient ou définit le défilement de la coordonnée UV. |
| [Type](../../aspose.threed.render/itextureunit/type/) { get; } | Obtient le type de cette unité de texture. |
| [UWrap](../../aspose.threed.render/itextureunit/uwrap/) { get; set; } | Obtient ou définit le mode d'enroulement pour la coordonnée U de la texture. |
| [VWrap](../../aspose.threed.render/itextureunit/vwrap/) { get; set; } | Obtient ou définit le mode d'enroulement pour la coordonnée V de la texture. |
| [Width](../../aspose.threed.render/itextureunit/width/) { get; } | Obtient la largeur de cette texture. |
| [WWrap](../../aspose.threed.render/itextureunit/wwrap/) { get; set; } | Obtient ou définit le mode d'enroulement pour la coordonnée W de la texture. |

### Voir aussi

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


