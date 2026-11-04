---
title: "Transform.GeometricScaling"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Transform. Obtiene o establece la escala geométrica. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exporte la transformación geométrica a tipos de archivo que no la soportan."
type: docs
weight: 30
url: /es/net/aspose.threed/transform/geometricscaling/
---
## Transform.GeometricScaling property

Obtiene o establece el escalado geométrico. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan.

```csharp
public Vector3 GeometricScaling { get; set; }
```

## Ejemplos

```csharp
Node node = new Node();
node.Transform.GeometricScaling = new Vector3(2, 2, 2);
```

### Ver también

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


