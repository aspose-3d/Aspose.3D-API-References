---
title: "Transform.TransformMatrix"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Transform. Obtiene o establece la matriz de transformación"
type: docs
weight: 130
url: /es/net/aspose.threed/transform/transformmatrix/
---
## Transform.TransformMatrix property

Obtiene o establece la matriz de transformación.

```csharp
public Matrix4 TransformMatrix { get; set; }
```

## Observaciones

Asignar en esto restablecerá la [`Translation`](../translation/), [`Scaling`](../scaling/) y [`Rotation`](../rotation/), mientras que [`GeometricRotation`](../geometricrotation/), [`GeometricScaling`](../geometricscaling/) y [`GeometricTranslation`](../geometrictranslation/) no se verán afectados.

## Ejemplos

```csharp
Node node = new Node();
node.Transform.TransformMatrix = Matrix4.Identity;
```

### Ver también

* struct [Matrix4](../../../aspose.threed.utilities/matrix4/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


