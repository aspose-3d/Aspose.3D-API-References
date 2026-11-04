---
title: "BoundingBox.op_Multiply"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método BoundingBox. Sobrecarga del operador de multiplicación; la nueva esquina mínima y máxima del cuadro delimitador serán transformadas por la matriz"
type: docs
weight: 170
url: /es/net/aspose.threed.utilities/boundingbox/op_multiply/
---
## BoundingBox Multiply operator

Sobrecarga de operador para multiplicar, la esquina mínima y máxima del nuevo cuadro delimitador serán transformadas por la matriz.

```csharp
public static BoundingBox operator *(BoundingBox bbox, Matrix4 mat)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| bbox | BoundingBox | El cuadro delimitador de entrada. |
| mat | Matrix4 | La matriz utilizada para transformar las esquinas del cuadro delimitador |

### Valor de retorno

El producto del cuadro delimitador y la matriz de transformación.

### Ver también

* struct [Matrix4](../../matrix4/)
* struct [BoundingBox](../)
* namespace [Aspose.ThreeD.Utilities](../../boundingbox/)
* assembly [Aspose.3D](../../../)


