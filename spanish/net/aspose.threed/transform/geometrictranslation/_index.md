---
title: "Transform.GeometricTranslation"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Propiedad Transform. Obtiene o establece la traducción geométrica. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se combinará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no la soportan."
type: docs
weight: 40
url: /es/net/aspose.threed/transform/geometrictranslation/
---
## Transform.GeometricTranslation property

Obtiene o establece la traslación geométrica. La transformación geométrica solo afecta a las entidades adjuntas y deja los nodos hijos sin cambios. Se fusionará como transformación local cuando exportes la transformación geométrica a tipos de archivo que no lo soportan.

```csharp
public Vector3 GeometricTranslation { get; set; }
```

## Ejemplos

```csharp
Node node = new Node();
node.Transform.GeometricTranslation = new Vector3(10, 0, 0);
```

### Ver también

* struct [Vector3](../../../aspose.threed.utilities/vector3/)
* class [Transform](../)
* namespace [Aspose.ThreeD](../../transform/)
* assembly [Aspose.3D](../../../)


