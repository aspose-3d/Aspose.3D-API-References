---
title: "Klasse TextureBase"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Shading.TextureBase Klasse. Basisklasse für alle konkreten Texturen. Textur definiert das Aussehen und das Gefühl einer Geometrie-Oberfläche"
type: docs
weight: 2610
url: /de/net/aspose.threed.shading/texturebase/
---
## TextureBase class

Basisklasse für alle konkreten Texturen. Eine Textur definiert das Aussehen und das Gefühl einer geometrischen Oberfläche.

```csharp
public class TextureBase : A3DObject
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [TextureBase](texturebase/)(string) | Initialisiert eine neue Instanz der `TextureBase` Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [Alpha](../../aspose.threed.shading/texturebase/alpha/) { get; set; } | Liest oder setzt den Standard‑Alpha‑Wert der Textur. Dieser ist gültig, wenn [`AlphaSource`](./alphasource/) PixelAlpha ist. Standardwert ist 1,0, gültiger Wertebereich liegt zwischen 0 und 1. |
| [AlphaSource](../../aspose.threed.shading/texturebase/alphasource/) { get; set; } | Liest oder setzt, ob die Textur den Alpha-Kanal definiert. Standardwert ist None |
| [MagFilter](../../aspose.threed.shading/texturebase/magfilter/) { get; set; } | Liest oder setzt den Filter für Vergrößerung. |
| [MinFilter](../../aspose.threed.shading/texturebase/minfilter/) { get; set; } | Liest oder setzt den Filter für Verkleinerung. |
| [MipFilter](../../aspose.threed.shading/texturebase/mipfilter/) { get; set; } | Liest oder setzt den Filter für Mip-Level-Abtastung. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Liest oder setzt den Namen. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Gibt die Sammlung aller Eigenschaften zurück. |
| [UVRotation](../../aspose.threed.shading/texturebase/uvrotation/) { get; set; } | Liest oder setzt die Drehung der Textur |
| [UVScale](../../aspose.threed.shading/texturebase/uvscale/) { get; set; } | Liest oder setzt die UV-Skalierung. |
| [UVTranslation](../../aspose.threed.shading/texturebase/uvtranslation/) { get; set; } | Liest oder setzt die UV-Translation. |
| [WrapModeU](../../aspose.threed.shading/texturebase/wrapmodeu/) { get; set; } | Liest oder setzt die Textur-Wrap-Modi in U. |
| [WrapModeV](../../aspose.threed.shading/texturebase/wrapmodev/) { get; set; } | Liest oder setzt die Textur-Wrap-Modi in V. |
| [WrapModeW](../../aspose.threed.shading/texturebase/wrapmodew/) { get; set; } | Liest oder setzt die Textur-Wrap-Modi in W. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Findet die Eigenschaft. Sie kann eine dynamische Eigenschaft sein (erstellt durch CreateDynamicProperty/SetProperty) oder eine native Eigenschaft (identifiziert über ihren Namen). |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Liefert den Wert der angegebenen Eigenschaft |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Entfernt eine dynamische Eigenschaft. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Entfernt die angegebene, nach Namen identifizierte Eigenschaft |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Setzt den Wert der angegebenen Eigenschaft |
| [SetRotation](../../aspose.threed.shading/texturebase/setrotation/)(double, double) | Setzt die UV-Drehung. |
| [SetScale](../../aspose.threed.shading/texturebase/setscale/)(double, double) | Setzt die UV-Skalierung. |
| [SetTranslation](../../aspose.threed.shading/texturebase/settranslation/)(double, double) | Setzt die UV-Translation. |

### Siehe auch

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Shading](../../aspose.threed.shading/)
* assembly [Aspose.3D](../../)


