---
title: "Node.EvaluateGlobalTransform"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Node-Methode. Bewertet die globale Transformation, ob die geometrische Transformation einbezogen wird oder nicht."
type: docs
weight: 180
url: /de/net/aspose.threed/node/evaluateglobaltransform/
---
## Node.EvaluateGlobalTransform method

Bewertet die globale Transformation, wobei die geometrische Transformation einbezogen wird oder nicht.

```csharp
public Matrix4 EvaluateGlobalTransform(bool withGeometricTransform)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| withGeometricTransform | Boolean | Ob die geometrische Transformation benötigt wird. |

### Rückgabewert

Die globale Transformationsmatrix.

## Beispiele

Der folgende Code zeigt, wie man die globale Transformationsmatrix des Knotens liest.

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//Platziere die Box bei (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
Matrix4 mat = boxNode.EvaluateGlobalTransform(true);
Console.WriteLine($"The box's global transform matrix is {mat}");
```

### Siehe auch

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Node](../)
* namespace [Aspose.ThreeD](../../node/)
* assembly [Aspose.3D](../../../)


