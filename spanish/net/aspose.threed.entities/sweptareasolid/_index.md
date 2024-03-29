---
title: SweptAreaSolid
second_title: Referencia de API de Aspose.3D para .NET
description: ASweptAreaSolid./sweptareasolid construye una geometría mediante el barrido de un perfil a lo largo de una directriz.
type: docs
weight: 690
url: /es/net/aspose.threed.entities/sweptareasolid/
---
## SweptAreaSolid class

A[`SweptAreaSolid`](../sweptareasolid) construye una geometría mediante el barrido de un perfil a lo largo de una directriz.

```csharp
public class SweptAreaSolid : Entity, IMeshConvertible
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SweptAreaSolid](sweptareasolid)() | Constructor predeterminado |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Directrix](../../aspose.threed.entities/sweptareasolid/directrix) { get; set; } | La directriz con la que barre el área barrida. |
| [EndPoint](../../aspose.threed.entities/sweptareasolid/endpoint) { get; set; } | El punto final de la directriz. |
| [Excluded](../../aspose.threed/entity/excluded) { get; set; } | Obtiene o establece si se excluye esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode) { get; set; } | Obtiene o establece el primer nodo principal; si se establece el primer nodo principal, esta entidad se separará de otros nodos principales. |
| [ParentNodes](../../aspose.threed/entity/parentnodes) { get; } | Obtiene todos los nodos principales, una entidad se puede adjuntar a varios nodos principales para crear instancias de geometría |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Shape](../../aspose.threed.entities/sweptareasolid/shape) { get; set; } | El perfil base para construir la geometría. |
| [StartPoint](../../aspose.threed.entities/sweptareasolid/startpoint) { get; set; } | El punto de inicio de la directriz. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox)() | Obtiene el cuadro delimitador de la entidad actual en su sistema de coordenadas de espacio de objetos. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey)() | Obtiene la clave del renderizador de entidades registrado en el renderizador |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |
| [ToMesh](../../aspose.threed.entities/sweptareasolid/tomesh)() | Convertir objeto actual a mesh |

### Ver también

* class [Entity](../../aspose.threed/entity)
* interface [IMeshConvertible](../imeshconvertible)
* espacio de nombres [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
