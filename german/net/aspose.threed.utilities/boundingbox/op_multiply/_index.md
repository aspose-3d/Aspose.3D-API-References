---
title: "BoundingBox.op_Multiply"
second_title: "Aspose.3D für .NET API-Referenz"
description: "BoundingBox-Methode. Operatorüberladung zum Multiplizieren, neue minimale und maximale Ecke des BoundingBox werden durch die Matrix transformiert."
type: docs
weight: 170
url: /de/net/aspose.threed.utilities/boundingbox/op_multiply/
---
## BoundingBox Multiply operator

Operatorüberladung für Multiplikation, die minimale und maximale Ecke der neuen Begrenzungsbox werden durch die Matrix transformiert.

```csharp
public static BoundingBox operator *(BoundingBox bbox, Matrix4 mat)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| bbox | BoundingBox | Die Eingabe-BoundingBox. |
| mat | Matrix4 | Die Matrix, die verwendet wird, um die Ecken der BoundingBox zu transformieren. |

### Rückgabewert

Das Produkt aus BoundingBox und Transformationsmatrix.

### Siehe auch

* struct [Matrix4](../../matrix4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


