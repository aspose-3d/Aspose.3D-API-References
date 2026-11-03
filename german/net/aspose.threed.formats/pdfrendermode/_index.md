---
title: "Enum PdfRenderMode"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Formats.PdfRenderMode-Enum. Der Rendermodus gibt den Stil an, in dem das 3D‑Werk gerendert wird"
type: docs
weight: 1410
url: /de/net/aspose.threed.formats/pdfrendermode/
---
## PdfRenderMode enumeration

Rendermodus gibt den Stil an, in dem das 3D‑Werk gerendert wird.

```csharp
public enum PdfRenderMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Solid | `0` | Zeigt texturierte und beleuchtete geometrische Formen an. |
| SolidWireframe | `1` | Zeigt texturierte und beleuchtete geometrische Formen (Dreiecke) mit einfarbigen Kanten darüber an. |
| Transparent | `2` | Zeigt texturierte und beleuchtete geometrische Formen (Dreiecke) mit einem zusätzlichen Transparenzgrad an. |
| TransparentWireframe | `3` | Zeigt texturierte und beleuchtete geometrische Formen (Dreiecke) mit einem zusätzlichen Transparenzgrad und einfarbigen undurchsichtigen Kanten darüber an. |
| BoundingBox | `4` | Zeigt die Kanten der Begrenzungsbox jedes Knotens an, ausgerichtet an den Achsen des lokalen Koordinatensystems dieses Knotens. |
| TransparentBoundingBox | `5` | Zeigt die Flächen der Begrenzungsbox jedes Knotens an, ausgerichtet an den Achsen des lokalen Koordinatensystems dieses Knotens, mit einem zusätzlichen Transparenzgrad. |
| TransparentBoundingBoxOutline | `6` | Zeigt die Kanten und Flächen der Begrenzungsbox jedes Knotens an, ausgerichtet an den Achsen des lokalen Koordinatensystems dieses Knotens, mit einem zusätzlichen Transparenzgrad. |
| Wireframe | `7` | Zeigt nur Kanten in einer einzigen Farbe an. |
| ShadedWireframe | `8` | Zeigt nur Kanten an, interpoliert jedoch deren Farbe zwischen den beiden Scheitelpunkten und wendet Beleuchtung an. |
| HiddenWireframe | `9` | Zeigt Kanten in einer einzigen Farbe an, entfernt jedoch rückwärtsgerichtete und verdeckte Kanten. |
| Vertices | `10` | Zeigt nur Scheitelpunkte in einer einzigen Farbe an. |
| ShadedVertices | `11` | Zeigt nur Scheitelpunkte an, verwendet jedoch deren Scheitelpunktfarbe und wendet Beleuchtung an. |
| Illustration | `12` | Zeigt Silhouettenkanten mit Oberflächen an, entfernt verdeckte Linien. |
| SolidOutline | `13` | Zeigt Silhouettenkanten mit beleuchteten und texturierten Oberflächen an, entfernt verdeckte Linien. |
| ShadedIllustration | `14` | Zeigt Silhouettenkanten mit beleuchteten und texturierten Oberflächen sowie einem zusätzlichen emittierenden Term an, um schlecht beleuchtete Bereiche des Kunstwerks zu entfernen. |

### Siehe auch

* namespace [Aspose.ThreeD.Formats](../../aspose.threed.formats/)
* assembly [Aspose.3D](../../)


