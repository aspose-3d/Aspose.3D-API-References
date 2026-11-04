---
title: "Clase Frustum"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Frustum. La clase base de Camera y Light"
type: docs
weight: 400
url: /es/net/aspose.threed.entities/frustum/
---
## Frustum class

La clase base de [`Camera`](../camera/) y [`Light`](../light/)

```csharp
public abstract class Frustum : Entity, IOrientable
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Obtiene o establece la relación de aspecto del frustum |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Obtiene o establece la dirección a la que mira la cámara. Los cambios en esta propiedad también afectan a [`LookAt`](./lookat/) y [`Target`](./target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Obtiene o establece la distancia del plano lejano del frustum. |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Obtiene o establece la posición de interés a la que mira la cámara. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Obtiene o establece la distancia del plano cercano del frustum. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Obtiene o establece la altura cuando el frustum está en proyección ortográfica. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Obtiene o establece el modo de orientación del frustum. Esta propiedad solo funciona cuando [`Target`](./target/) es nulo. Si el valor es FixedTarget, la dirección siempre se calcula mediante la propiedad [`LookAt`](./lookat/). De lo contrario, [`LookAt`](./lookat/) siempre se calcula mediante [`Direction`](./direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Obtiene o establece el objetivo al que mira la cámara. Si el usuario admite esta propiedad, debe ser anterior a la propiedad [`LookAt`](./lookat/). |
| [Up](../../aspose.threed.entities/frustum/up/) { get; set; } | Obtiene o establece la dirección ascendente de la cámara |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objeto. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Obtiene la clave del renderizador de entidad registrado en el renderizador |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [Entity](../../aspose.threed/entity/)
* interface [IOrientable](../iorientable/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


