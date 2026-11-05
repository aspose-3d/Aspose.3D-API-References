---
title: "BoundingBox.Merge"
second_title: "Aspose.3D för .NET API‑referens"
description: "BoundingBox-metod. Slå ihop den aktuella avgränsningsrutan med den angivna punkten"
type: docs
weight: 130
url: /sv/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Slå ihop den aktuella avgränsningsrutan med den angivna punkten

```csharp
public void Merge(Vector4 pt)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | Vector4 | Punkten som ska slås ihop med avgränsningsrutan |

## Exempel

Följande kod visar hur man slår ihop en punkt med avgränsningsrutan.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Se även

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Slå ihop den aktuella avgränsningsrutan med den angivna punkten

```csharp
public void Merge(Vector3 pt)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pt | Vector3 | Punkten som ska slås ihop med avgränsningsrutan |

## Exempel

Följande kod visar hur man slår ihop en punkt med avgränsningsrutan.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Se även

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Slå ihop den aktuella avgränsningsrutan med den angivna punkten

```csharp
public void Merge(double x, double y, double z)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| x | Double | Punkten som ska slås ihop med avgränsningsrutan |
| y | Double | Punkten som ska slås ihop med avgränsningsrutan |
| z | Double | Punkten som ska slås ihop med avgränsningsrutan |

## Exempel

Följande kod visar hur man slår ihop en punkt med avgränsningsrutan.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Se även

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Slår ihop den nya rutan med den aktuella avgränsningsrutan.

```csharp
public void Merge(BoundingBox bb)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bb | BoundingBox | Avgränsningsrutan att slå ihop |

### Se även

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


