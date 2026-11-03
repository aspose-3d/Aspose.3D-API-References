---
title: "Schnittstelle ITextureUnit"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.ITextureUnit interface. ITextureUnit stellt eine Textur im Speicher dar, die zwischen GPU und CPU gemeinsam genutzt wird und vom Shader abgetastet werden kann, wobei die Texture nur einen Verweis auf eine externe Datei darstellt. Weitere Details finden Sie unter https//en.wikipedia.org/wiki/Texture_mapping_unit"
type: docs
weight: 2170
url: /de/net/aspose.threed.render/itextureunit/
---
## ITextureUnit interface

`ITextureUnit` stellt eine Textur im Speicher dar, die zwischen GPU und CPU gemeinsam genutzt wird und vom Shader abgetastet werden kann, wobei die [`Texture`](../../aspose.threed.shading/texture/) nur einen Verweis auf eine externe Datei darstellt. Weitere Details finden Sie unter https://en.wikipedia.org/wiki/Texture_mapping_unit

```csharp
public interface ITextureUnit : IDisposable
```

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Depth](../../aspose.threed.render/itextureunit/depth/) { get; } | Liefert die Höhe dieser Textur, bei nicht‑3D‑Texturen ist sie immer 1. |
| [Height](../../aspose.threed.render/itextureunit/height/) { get; } | Liefert die Höhe dieser Textur. |
| [Magnification](../../aspose.threed.render/itextureunit/magnification/) { get; set; } | Liefert oder setzt den Filtermodus für Vergrößerung. |
| [Minification](../../aspose.threed.render/itextureunit/minification/) { get; set; } | Liefert oder setzt den Filtermodus für Verkleinerung. |
| [Mipmap](../../aspose.threed.render/itextureunit/mipmap/) { get; set; } | Liefert oder setzt den Filtermodus für Mipmap. |
| [Scale](../../aspose.threed.render/itextureunit/scale/) { get; set; } | Liefert oder setzt die Skalierung der UV‑Koordinate. |
| [Scroll](../../aspose.threed.render/itextureunit/scroll/) { get; set; } | Liefert oder setzt das Scrollen der UV‑Koordinate. |
| [Type](../../aspose.threed.render/itextureunit/type/) { get; } | Liefert den Typ dieser Textureinheit. |
| [UWrap](../../aspose.threed.render/itextureunit/uwrap/) { get; set; } | Liefert oder setzt den Wrap‑Modus für die U‑Koordinate der Textur. |
| [VWrap](../../aspose.threed.render/itextureunit/vwrap/) { get; set; } | Liefert oder setzt den Wrap‑Modus für die V‑Koordinate der Textur. |
| [Width](../../aspose.threed.render/itextureunit/width/) { get; } | Liefert die Breite dieser Textur. |
| [WWrap](../../aspose.threed.render/itextureunit/wwrap/) { get; set; } | Liefert oder setzt den Wrap‑Modus für die W‑Koordinate der Textur. |

### Siehe auch

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


