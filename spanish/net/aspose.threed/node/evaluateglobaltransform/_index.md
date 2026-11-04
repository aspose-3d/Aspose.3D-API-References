---
title: "Node.EvaluateGlobalTransform"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Node. Evalúa la transformación global incluyendo o no la transformación geométrica"
type: docs
weight: 180
url: /es/net/aspose.threed/node/evaluateglobaltransform/
---
## Node.EvaluateGlobalTransform method

Evaluar la transformación global, incluir la transformación geométrica o no.

```csharp
public Matrix4 EvaluateGlobalTransform(bool withGeometricTransform)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| withGeometricTransform | Boolean | Si se necesita la transformación geométrica. |

### Valor de retorno

La matriz de transformación global.

## Ejemplos

El siguiente código muestra cómo leer la matriz de transformación global del nodo.

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//coloca la caja en (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
Matrix4 mat = boxNode.EvaluateGlobalTransform(true);
Console.WriteLine($"The box's global transform matrix is {mat}");
```

### Ver también

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


