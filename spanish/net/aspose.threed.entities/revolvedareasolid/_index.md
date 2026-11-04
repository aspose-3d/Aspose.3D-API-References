---
title: "Clase RevolvedAreaSolid"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.RevolvedAreaSolid. Esta clase representa un modelo sólido al revolver una sección transversal proporcionada por un perfil alrededor de un eje"
type: docs
weight: 680
url: /es/net/aspose.threed.entities/revolvedareasolid/
---
## RevolvedAreaSolid class

Esta clase representa un modelo sólido al girar una sección transversal proporcionada por un perfil alrededor de un eje.

```csharp
public class RevolvedAreaSolid : Entity, IMeshConvertible
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [RevolvedAreaSolid](revolvedareasolid/)() | El constructor predeterminado. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [AngleEnd](../../aspose.threed.entities/revolvedareasolid/angleend/) { get; set; } | Obtiene o establece el ángulo final del procedimiento de revolución, medido en radianes, el valor predeterminado es pi. |
| [AngleStart](../../aspose.threed.entities/revolvedareasolid/anglestart/) { get; set; } | Obtiene o establece el ángulo inicial del procedimiento de revolución, medido en radianes, el valor predeterminado es 0. |
| [Axis](../../aspose.threed.entities/revolvedareasolid/axis/) { get; set; } | Obtiene o establece la dirección del eje, el valor predeterminado es (0, 1, 0). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Origin](../../aspose.threed.entities/revolvedareasolid/origin/) { get; set; } | Obtiene o establece el punto de origen de la revolución, el valor predeterminado es (0, 0, 0). |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Shape](../../aspose.threed.entities/revolvedareasolid/shape/) { get; set; } | Obtiene o establece el perfil base utilizado para girar. |

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
| [ToMesh](../../aspose.threed.entities/revolvedareasolid/tomesh/)() | Convierte el `RevolvedAreaSolid` en una malla. |

## Ejemplos

El siguiente código muestra cómo usar RevolvedAreaSolid para girar una forma en un modelo sólido.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Crear una nueva escena 3D
Scene scene = new Scene();

// Inicializar el perfil base que se girará
var profile = new RectangleShape()
{
    RoundingRadius = 0.3
};
//crear una instancia de RevolvedAreaSolid 
var revolved = new RevolvedAreaSolid()
{
  Shape = profile,
  Origin = new Vector3(1, 0, 0),
  AngleStart = 0,
  AngleEnd = Math.PI
};
scene.RootNode.CreateChildNode(revolved);

scene.Save("revolved.obj");
```

```csharp
//Crear una nueva escena 3D
Scene scene = new Scene();

// Inicializar el perfil base que se extruirá
var profile = new RectangleShape();
profile.setRoundingRadius(0.3);

var revolved = new RevolvedAreaSolid();
revolved.setShape(profile);
revolved.setOrigin(new Vector3(1, 0, 0));
revolved.setAngleStart(0);
revolved.setAngleEnd(Math.PI);
scene.getRootNode().createChildNode(revolved);

scene.save("revolved.obj");
```

### Ver también

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


