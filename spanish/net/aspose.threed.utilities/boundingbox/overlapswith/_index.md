---
title: "BoundingBox.OverlapsWith"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método BoundingBox. Verifica si la caja delimitadora actual se superpone con la caja delimitadora especificada"
type: docs
weight: 140
url: /es/net/aspose.threed.utilities/boundingbox/overlapswith/
---
## BoundingBox.OverlapsWith method

Verifique si el cuadro delimitador actual se superpone con el cuadro delimitador especificado.

```csharp
public bool OverlapsWith(BoundingBox box)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| caja | BoundingBox | La otra caja delimitadora a probar |

### Valor de retorno

Verdadero si la caja delimitadora actual se superpone con la dada.

## Ejemplos

El siguiente código muestra cómo verificar si dos cajas delimitadoras se superponen entre sí.

```csharp
var boundingBox = new BoundingBox(0, 0, 0, 10, 10, 10);
var bbox2 = new BoundingBox(1, 1, 1, 11, 11, 11);
Console.WriteLine("Bounding box overlaps = " + boundingBox.OverlapsWith(bbox2));
```

### Ver también

* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


