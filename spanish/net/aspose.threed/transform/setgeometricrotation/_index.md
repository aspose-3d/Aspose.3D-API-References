---
title: "Transform.SetGeometricRotation"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método Transform. Establece la rotación Euler geométrica medida en grados. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se combinará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no la soportan."
type: docs
weight: 160
url: /es/net/aspose.threed/transform/setgeometricrotation/
---
## Transform.SetGeometricRotation method

Establece la rotación geométrica de Euler (medida en grados). La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan.

```csharp
public Transform SetGeometricRotation(double rx, double ry, double rz)
```

## Ejemplos

```csharp
Node node = new Node();
node.Transform.SetGeometricRotation(90, 0, 0);
```

### Ver también

* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


