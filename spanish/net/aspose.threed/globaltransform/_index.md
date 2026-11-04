---
title: "Clase GlobalTransform"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.GlobalTransform. La transformación global es similar a Transform pero es inmutable mientras representa la transformación final evaluada. Se utiliza un sistema de coordenadas de mano derecha al evaluar la transformación global."
type: docs
weight: 1560
url: /es/net/aspose.threed/globaltransform/
---
## GlobalTransform class

La transformación global es similar a [`Transform`](../transform/) pero es inmutable mientras representa la transformación final evaluada. Se utiliza un sistema de coordenadas de mano derecha al evaluar la transformación global.

```csharp
public class GlobalTransform
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [EulerAngles](../../aspose.threed/globaltransform/eulerangles/) { get; } | Obtiene la rotación representada en ángulos de Euler, medida en grados |
| [Rotation](../../aspose.threed/globaltransform/rotation/) { get; } | Obtiene la rotación representada en cuaternión. |
| [Scale](../../aspose.threed/globaltransform/scale/) { get; } | Obtiene la escala |
| [TransformMatrix](../../aspose.threed/globaltransform/transformmatrix/) { get; } | Obtiene la matriz de transformación. |
| [Translation](../../aspose.threed/globaltransform/translation/) { get; } | Obtiene la traslación |

## Ejemplos

El siguiente código muestra cómo leer la transformación global del nodo

```csharp
Scene scene = new Scene();
var boxNode = scene.RootNode.CreateChildNode(new Box());
//coloca la caja en (10, 0, 0)
boxNode.Transform.Translation = new Vector3(10, 0, 0);
var global = boxNode.GlobalTransform;
Console.WriteLine($"The box's position in world coordinate is {global.Translation}");
```

### Ver también

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


