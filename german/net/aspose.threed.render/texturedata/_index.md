---
title: "Klasse TextureData"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Render.TextureData Klasse. Diese Klasse enthält die Rohdaten und die Formatdefinition einer Textur"
type: docs
weight: 2460
url: /de/net/aspose.threed.render/texturedata/
---
## TextureData class

Diese Klasse enthält die Rohdaten und die Formatdefinition einer Textur.

```csharp
public class TextureData : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextureData](texturedata/#constructor)() | Konstruktor von `TextureData` |
| [TextureData](texturedata/#constructor_1)(int, int, PixelFormat) | Konstruiert ein neues `TextureData` und reserviert Pixeldaten. |
| [TextureData](texturedata/#constructor_2)(int, int, int, int, PixelFormat, byte[]) | Konstruktor von `TextureData` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BytesPerPixel](../../aspose.threed.render/texturedata/bytesperpixel/) { get; } | Anzahl der Bytes eines Pixels |
| [Data](../../aspose.threed.render/texturedata/data/) { get; } | Rohbytes der Pixeldaten |
| [Height](../../aspose.threed.render/texturedata/height/) { get; } | Anzahl der vertikalen Pixel |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [PixelFormat](../../aspose.threed.render/texturedata/pixelformat/) { get; } | Das Format des Pixels |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [Stride](../../aspose.threed.render/texturedata/stride/) { get; } | Anzahl der Bytes einer Scanzeile. |
| [Width](../../aspose.threed.render/texturedata/width/) { get; } | Anzahl der horizontalen Pixel |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromFile](../../aspose.threed.render/texturedata/fromfile/)(string) | Lade eine Textur aus Datei |
| static [FromStream](../../aspose.threed.render/texturedata/fromstream/)(Stream) | Lade eine Textur aus Stream |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels)(PixelMapMode) | Alle Pixel für Lesen/Schreiben abbilden |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_1)(PixelMapMode, PixelFormat) | Alle Pixel für Lesen/Schreiben im angegebenen Pixel-Format abbilden |
| [MapPixels](../../aspose.threed.render/texturedata/mappixels/#mappixels_2)(Rect, PixelMapMode, PixelFormat) | Pixel, die durch Rechteck adressiert werden, für Lesen/Schreiben im angegebenen Pixel-Format abbilden |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [Save](../../aspose.threed.render/texturedata/save/#save_1)(string) | Texturdaten in Bilddatei speichern |
| [Save](../../aspose.threed.render/texturedata/save/#save)(Stream, string) | Texturdaten in angegebenes Bildformat speichern |
| [Save](../../aspose.threed.render/texturedata/save/#save_2)(string, string) | Texturdaten in Bilddatei speichern |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| [TransformPixelFormat](../../aspose.threed.render/texturedata/transformpixelformat/)(PixelFormat) | Layout des Pixels in ein neues Pixel-Format umwandeln. |

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


