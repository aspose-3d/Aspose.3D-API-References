---
title: "BoundingBox.Merge"
second_title: "Riferimento API Aspose.3D per .NET"
description: "Metodo BoundingBox. Unisci il BoundingBox corrente con il punto fornito"
type: docs
weight: 130
url: /it/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Unisci il BoundingBox corrente con il punto fornito

```csharp
public void Merge(Vector4 pt)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | Vector4 | Il punto da unire al BoundingBox |

## Esempi

Il codice seguente mostra come unire un punto al BoundingBox.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Vedi anche

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Unisci il BoundingBox corrente con il punto fornito

```csharp
public void Merge(Vector3 pt)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pt | Vector3 | Il punto da unire al BoundingBox |

## Esempi

Il codice seguente mostra come unire un punto al BoundingBox.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Vedi anche

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Unisci il BoundingBox corrente con il punto fornito

```csharp
public void Merge(double x, double y, double z)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | Double | Il punto da unire al BoundingBox |
| y | Double | Il punto da unire al BoundingBox |
| z | Double | Il punto da unire al BoundingBox |

## Esempi

Il codice seguente mostra come unire un punto al BoundingBox.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Vedi anche

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Unisce il nuovo BoundingBox al BoundingBox corrente.

```csharp
public void Merge(BoundingBox bb)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bb | BoundingBox | Il BoundingBox da unire |

### Vedi anche

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


