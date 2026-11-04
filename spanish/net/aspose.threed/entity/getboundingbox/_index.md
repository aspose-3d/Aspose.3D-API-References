---
title: "Entity.GetBoundingBox"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Entity método. Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas del espacio del objeto"
type: docs
weight: 50
url: /es/net/aspose.threed/entity/getboundingbox/
---
## Entity.GetBoundingBox method

Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto.

```csharp
public BoundingBox GetBoundingBox()
```

### Valor de retorno

el cuadro delimitador de la entidad actual en su sistema de coordenadas del espacio del objeto.

## Ejemplos

El siguiente código muestra cómo calcular el cuadro delimitador de una forma

```csharp
Entity entity = new Sphere() { Radius = 10 };
var bbox = entity.GetBoundingBox();
Console.WriteLine($"The bounding box of the entity is {bbox.Minimum} ~ {bbox.Maximum}");
```

### Ver también

* struct [BoundingBox](../../../aspose.threed.utilities/boundingbox/)
* class [Entity](../)
* namespace [Aspose.ThreeD](../../entity/)
* assembly [Aspose.3D](../../../)


