---
title: "Struktur RelativeRectangle"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Utilities.RelativeRectangle Struktur. Relatives Rechteck Die Formel zwischen relativer Komponente und absolutem Wert ist Scale  Reference Width  offset. Wenn wir ein absolutes Ergebnis darstellen wollen, lassen Sie alle Scale‑Felder auf Null und verwenden stattdessen die Offset‑Felder."
type: docs
weight: 2830
url: /de/net/aspose.threed.utilities/relativerectangle/
---
## RelativeRectangle structure

Relatives Rechteck. Die Formel zur Umrechnung von relativen Komponenten in absolute Werte lautet: Scale * (Referenzbreite) + Offset. Wenn wir also einen absoluten Wert darstellen wollen, setzen wir alle Skalierungsfelder auf Null und verwenden stattdessen Offset-Felder stattdessen.

```csharp
public struct RelativeRectangle
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [RelativeRectangle](relativerectangle/)(int, int, int, int) | Erstelle ein `RelativeRectangle` |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [OffsetHeight](../../aspose.threed.utilities/relativerectangle/offsetheight/) { get; set; } | Liest oder setzt den Offset für die Höhe |
| [OffsetWidth](../../aspose.threed.utilities/relativerectangle/offsetwidth/) { get; set; } | Liest oder setzt den Offset für die Breite |
| [OffsetX](../../aspose.threed.utilities/relativerectangle/offsetx/) { get; set; } | Liest oder setzt den Offset für die Koordinate X |
| [OffsetY](../../aspose.threed.utilities/relativerectangle/offsety/) { get; set; } | Liest oder setzt den Offset für die Koordinate Y |
| [ScaleHeight](../../aspose.threed.utilities/relativerectangle/scaleheight/) { get; set; } | Relative Höhe |
| [ScaleWidth](../../aspose.threed.utilities/relativerectangle/scalewidth/) { get; set; } | Relative Breite |
| [ScaleX](../../aspose.threed.utilities/relativerectangle/scalex/) { get; set; } | Relative Koordinate X |
| [ScaleY](../../aspose.threed.utilities/relativerectangle/scaley/) { get; set; } | Relative Koordinate Y |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [FromScale](../../aspose.threed.utilities/relativerectangle/fromscale/)(float, float, float, float) | Erstelle ein `RelativeRectangle` mit allen Offset‑Feldern auf Null und Scale‑Feldern aus den angegebenen Parametern. |
| [ToAbsolute](../../aspose.threed.utilities/relativerectangle/toabsolute/)(int, int, int, int) | Konvertiere das relative Rechteck in ein absolutes Rechteck |
| override [ToString](../../aspose.threed.utilities/relativerectangle/tostring/)() | Konvertiert den Wert dieser Instanz in einen String. |

### Siehe auch

* namespace [Aspose.ThreeD.Utilities](../../aspose.threed.utilities/)
* assembly [Aspose.3D](../../)


