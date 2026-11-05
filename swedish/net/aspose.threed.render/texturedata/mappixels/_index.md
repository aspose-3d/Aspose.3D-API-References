---
title: "TextureData.MapPixels"
second_title: "Aspose.3D för .NET API‑referens"
description: "TextureData-metod. Mappa alla pixlar för läsning/skrivning"
type: docs
weight: 100
url: /sv/net/aspose.threed.render/texturedata/mappixels/
---
## MapPixels(PixelMapMode) {#mappixels}

Mappa alla pixlar för läsning/skrivning

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mapMode | PixelMapMode | Kartläge |

### Se även

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(PixelMapMode, PixelFormat) {#mappixels_1}

Mappa alla pixlar för läs/skriv i angivet pixelformat

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode, PixelFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| mapMode | PixelMapMode | Kartläge |
| format | PixelFormat | Pixelformat |

### Se även

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(Rect, PixelMapMode, PixelFormat) {#mappixels_2}

Mappa pixlar adresserade av rect för läs/skriv i angivet pixelformat

```csharp
public PixelMapping MapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| rect | Rect | Området av pixlar som ska nås |
| mapMode | PixelMapMode | Kartläge |
| format | PixelFormat | Pixelformat |

### Returvärde

Returnerar ett mappningsobjekt, det bör avskrivas när det inte längre behövs.

### Undantag

| undantag | villkor |
| --- | --- |
| NotSupportedException |  |

### Se även

* class [PixelMapping](../../pixelmapping/)
* struct [Rect](../../../aspose.threed.utilities/rect/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)


