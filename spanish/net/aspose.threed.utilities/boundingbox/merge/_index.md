---
title: "BoundingBox.Merge"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método BoundingBox. Fusiona la caja delimitadora actual con el punto dado"
type: docs
weight: 130
url: /es/net/aspose.threed.utilities/boundingbox/merge/
---
## Merge(Vector4) {#merge_2}

Combinar la caja delimitadora actual con el punto dado

```csharp
public void Merge(Vector4 pt)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | Vector4 | El punto que se fusionará en la caja delimitadora |

## Ejemplos

El siguiente código muestra cómo fusionar un punto a la caja delimitadora.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector4(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ver también

* struct [Vector4](../../vector4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(Vector3) {#merge_1}

Combinar la caja delimitadora actual con el punto dado

```csharp
public void Merge(Vector3 pt)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| pt | Vector3 | El punto que se fusionará en la caja delimitadora |

## Ejemplos

El siguiente código muestra cómo fusionar un punto a la caja delimitadora.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(new Vector3(1, 10, -1));
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ver también

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(double, double, double) {#merge_3}

Combinar la caja delimitadora actual con el punto dado

```csharp
public void Merge(double x, double y, double z)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| x | Doble | El punto que se fusionará en la caja delimitadora |
| y | Doble | El punto que se fusionará en la caja delimitadora |
| z | Doble | El punto que se fusionará en la caja delimitadora |

## Ejemplos

El siguiente código muestra cómo fusionar un punto a la caja delimitadora.

```csharp
var boundingBox = BoundingBox.Null;
boundingBox.Merge(1, 10, -1);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ver también

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Merge(BoundingBox) {#merge}

Fusiona la nueva caja con la caja delimitadora actual.

```csharp
public void Merge(BoundingBox bb)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bb | BoundingBox | La caja delimitadora a fusionar |

### Ver también

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


