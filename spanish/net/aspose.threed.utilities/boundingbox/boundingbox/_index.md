---
title: "BoundingBox.BoundingBox"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Constructor de BoundingBox. Inicializa una caja delimitadora finita con la esquina mínima y máxima dadas."
type: docs
weight: 10
url: /es/net/aspose.threed.utilities/boundingbox/boundingbox/
---
## BoundingBox(Vector3, Vector3) {#constructor}

Inicializar una caja delimitadora finita con la esquina mínima y máxima dadas

```csharp
public BoundingBox(Vector3 minimum, Vector3 maximum)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mínimo | Vector3 | La esquina mínima |
| máximo | Vector3 | La esquina máxima |

## Ejemplos

El siguiente código muestra cómo construir una caja delimitadora a partir de las esquinas mínima y máxima.

```csharp
var minimum = new Vector3(0, 0, 0);
var maximum = new Vector3(10, 10, 10);
var boundingBox = new BoundingBox(minimum, maximum);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ver también

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## BoundingBox(double, double, double, double, double, double) {#constructor_1}

Inicializar una caja delimitadora finita con la esquina mínima y máxima dadas

```csharp
public BoundingBox(double minX, double minY, double minZ, double maxX, double maxY, double maxZ)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| minX | Doble | La X de la esquina mínima |
| minY | Doble | La Y de la esquina mínima |
| minZ | Doble | La Z de la esquina mínima |
| maxX | Doble | La X de la esquina máxima |
| maxY | Doble | La Y de la esquina máxima |
| maxZ | Doble | La Z de la esquina máxima |

## Ejemplos

El siguiente código muestra cómo construir una caja delimitadora a partir de las esquinas mínima y máxima.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
Console.WriteLine("Bounding box = " + boundingBox);
```

### Ver también

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


