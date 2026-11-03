---
title: "BoundingBox.Merge"
second_title: "Aspose.3D für .NET API-Referenz"
description: "BoundingBox-Methode. Fügt die aktuelle Begrenzungsbox mit dem angegebenen Punkt zusammen"
type: docs
weight: 130
url: /de/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Füge die aktuelle Begrenzungsbox mit dem angegebenen Punkt zusammen

```csharp
public void Merge(Vector4 pt)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | Vector4 | Der Punkt, der in die Begrenzungsbox eingefügt werden soll |

## Beispiele

Der folgende Code zeigt, wie man einen Punkt in die Begrenzungsbox einfügt.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Siehe auch

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Füge die aktuelle Begrenzungsbox mit dem angegebenen Punkt zusammen

```csharp
public void Merge(Vector3 pt)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pt | Vector3 | Der Punkt, der in die Begrenzungsbox eingefügt werden soll |

## Beispiele

Der folgende Code zeigt, wie man einen Punkt in die Begrenzungsbox einfügt.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Siehe auch

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Füge die aktuelle Begrenzungsbox mit dem angegebenen Punkt zusammen

```csharp
public void Merge(double x, double y, double z)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| x | Double | Der Punkt, der in die Begrenzungsbox eingefügt werden soll |
| y | Double | Der Punkt, der in die Begrenzungsbox eingefügt werden soll |
| z | Double | Der Punkt, der in die Begrenzungsbox eingefügt werden soll |

## Beispiele

Der folgende Code zeigt, wie man einen Punkt in die Begrenzungsbox einfügt.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Siehe auch

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Fügt die neue Box in die aktuelle Begrenzungsbox ein.

```csharp
public void Merge(BoundingBox bb)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bb | BoundingBox | Die Bounding-Box zum Zusammenführen |

### Siehe auch

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


