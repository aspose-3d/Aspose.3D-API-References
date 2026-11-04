---
title: "BoundingBox.Contains"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método BoundingBox. Verifica si el punto p está dentro de la caja delimitadora"
type: docs
weight: 100
url: /es/net/aspose.threed.utilities/boundingbox/contains/
---
## Contains(Vector3) {#contains_1}

Comprobar si el punto p está dentro de la caja delimitadora

```csharp
public bool Contains(Vector3 p)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| p | Vector3 | El punto a probar |

### Valor de retorno

Verdadero si el punto está dentro de la caja delimitadora

## Ejemplos

El siguiente código muestra cómo verificar si un punto está dentro de la caja delimitadora.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var pt = new Vector3(4, 4, 4);
Console.WriteLine("Bounding box overlaps = " + boundingBox.Contains(pt));
```

### Ver también

* struct [Vector3](../../vector3/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)

---

## Contains(BoundingBox) {#contains}

La caja delimitadora para comprobar si está dentro de la caja delimitadora actual.

```csharp
public bool Contains(BoundingBox bbox)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bbox | BoundingBox |  |

### Ver también

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


