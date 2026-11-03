---
title: "TextureData.MapPixels"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode TextureData. Mappe tous les pixels en lecture/écriture"
type: docs
weight: 100
url: /fr/net/aspose.threed.render/texturedata/mappixels/
---
## MapPixels(PixelMapMode) {#mappixels}

Mapper tous les pixels en lecture/écriture

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mapMode | PixelMapMode | Mode de cartographie |

### Voir aussi

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(PixelMapMode, PixelFormat) {#mappixels_1}

Mapper tous les pixels en lecture/écriture dans le format de pixel donné

```csharp
public PixelMapping MapPixels(PixelMapMode mapMode, PixelFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| mapMode | PixelMapMode | Mode de cartographie |
| format | PixelFormat | Format de pixel |

### Voir aussi

* class [PixelMapping](../../pixelmapping/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)

---

## MapPixels(Rect, PixelMapMode, PixelFormat) {#mappixels_2}

Mapper les pixels délimités par un rectangle pour la lecture/écriture dans le format de pixel donné

```csharp
public PixelMapping MapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| rect | Rect | La zone de pixels à accéder |
| mapMode | PixelMapMode | Mode de cartographie |
| format | PixelFormat | Format de pixel |

### Valeur de retour

Renvoie un objet de mappage, il doit être libéré lorsqu'il n'est plus nécessaire.

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException |  |

### Voir aussi

* class [PixelMapping](../../pixelmapping/)
* struct [Rect](../../../aspose.threed.utilities/rect/)
* enum [PixelMapMode](../../pixelmapmode/)
* enum [PixelFormat](../../pixelformat/)
* class [TextureData](../)
* namespace [Aspose.ThreeD.Render](../../texturedata/)
* assembly [Aspose.3D](../../../)


