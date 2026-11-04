---
title: "Clase SweptAreaSolid"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.SweptAreaSolid. Un SweptAreaSolid construye una geometría barrendo un perfil a lo largo de una directriz."
type: docs
weight: 750
url: /es/net/aspose.threed.entities/sweptareasolid/
---
## SweptAreaSolid class

Un `SweptAreaSolid` construye una geometría al barrer un perfil a lo largo de una directriz.

```csharp
public class SweptAreaSolid : Entity, IMeshConvertible
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SweptAreaSolid](sweptareasolid/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Directrix](../../aspose.threed.entities/sweptareasolid/directrix/) { get; set; } | La directriz con la que el área barrida se desplaza. |
| [EndPoint](../../aspose.threed.entities/sweptareasolid/endpoint/) { get; set; } | El punto final de la directriz. |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Shape](../../aspose.threed.entities/sweptareasolid/shape/) { get; set; } | El perfil base para construir la geometría. |
| [StartPoint](../../aspose.threed.entities/sweptareasolid/startpoint/) { get; set; } | El punto inicial de la directriz. |

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
| [ToMesh](../../aspose.threed.entities/sweptareasolid/tomesh/)() | Convertir el objeto actual a malla |

## Ejemplos

El siguiente código muestra cómo modelar una entidad sólida al barrer una forma en C sobre un círculo.

```csharp
var directrix = new Circle(20);
var shape = new CShape();

var swept = new SweptAreaSolid()
{
  Shape = shape,
  Directrix = directrix,
  StartPoint = EndPoint.FromDegree(0),
  EndPoint = EndPoint.FromDegree(130)
};

var scene = new Scene();
scene.RootNode.CreateChildNode(swept);
scene.Save("swept.obj");
```

### Ver también

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


