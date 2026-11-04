---
title: "Transform.GeometricRotation"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Transform. Obtiene o establece la rotación geométrica Euler medida en grados. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exporte la transformación geométrica a tipos de archivo que no la soportan."
type: docs
weight: 20
url: /es/net/aspose.threed/transform/geometricrotation/
---
## Transform.GeometricRotation property

Obtiene o establece la rotación geométrica de Euler (medida en grados). La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan.

```csharp
public Vector3 GeometricRotation { get; set; }
```

## Ejemplos

```csharp
Node node = new Node();
node.getTransform().setGeometricRotation(new Vector3(90, 0, 0));
```

### Ver también

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


