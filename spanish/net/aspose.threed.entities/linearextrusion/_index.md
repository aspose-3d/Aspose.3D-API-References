---
title: "Clase LinearExtrusion"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.LinearExtrusion. La extrusión lineal toma una forma 2D como entrada y extiende la forma en la tercera dimensión."
type: docs
weight: 490
url: /es/net/aspose.threed.entities/linearextrusion/
---
## LinearExtrusion class

La extrusión lineal toma una forma 2D como entrada y extiende la forma en la tercera dimensión.

```csharp
public class LinearExtrusion : Entity, IMeshConvertible
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [LinearExtrusion](linearextrusion/#constructor)() | Constructor de la instancia `LinearExtrusion`. |
| [LinearExtrusion](linearextrusion/#constructor_1)(Profile, double) | Constructor de la instancia `LinearExtrusion`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Center](../../aspose.threed.entities/linearextrusion/center/) { get; set; } | Si este valor es falso, el rango Z de la extrusión lineal es de 0 a la altura; de lo contrario, el rango es de -altura/2 a altura/2. |
| [Direction](../../aspose.threed.entities/linearextrusion/direction/) { get; set; } | La dirección de la extrusión, el valor predeterminado es (0, 0, 1) |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [Height](../../aspose.threed.entities/linearextrusion/height/) { get; set; } | La altura de la geometría extruida, el valor predeterminado es 1.0 |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [Shape](../../aspose.threed.entities/linearextrusion/shape/) { get; set; } | La forma base a extruir. |
| [Slices](../../aspose.threed.entities/linearextrusion/slices/) { get; set; } | Las secciones de la geometría extruida retorcida, el valor predeterminado es 1. |
| [Twist](../../aspose.threed.entities/linearextrusion/twist/) { get; set; } | El número de grados a través de los cuales se extruye la forma. |
| [TwistOffset](../../aspose.threed.entities/linearextrusion/twistoffset/) { get; set; } | El desplazamiento usado en la torsión, el valor predeterminado es (0, 0, 0). |

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
| [ToMesh](../../aspose.threed.entities/linearextrusion/tomesh/)() | Convertir la extrusión a malla. |

## Ejemplos

El siguiente código muestra cómo usar LinearExtrusion para extruir una forma en un modelo sólido.

```csharp
using Aspose.ThreeD;
using Aspose.ThreeD.Entities;
using Aspose.ThreeD.Utilities;
using Aspose.ThreeD.Profiles;

//Crear una nueva escena 3D
Scene scene = new Scene();

// Inicializar el perfil base que se extruirá
var profile = new RectangleShape()
{
	RoundingRadius = 0.3
};

// Crear nodo izquierdo
var left = scene.RootNode.CreateChildNode();
left.CreateChildNode(new Box(0.01, 3, 3));

// Crear nodo derecho
var right = scene.RootNode.CreateChildNode();
right.CreateChildNode(new Box(0.01, 3, 3));
right.Transform.Translation = new Vector3(5, 0, 0);

//Realizar extrusión lineal en el nodo izquierdo usando la propiedad center y slices
left.CreateChildNode(new LinearExtrusion(profile, 10) { Center = false, Slices = 3, Twist = 20.0 });

// Realizar extrusión lineal en el nodo izquierdo usando la propiedad center y slices
right.CreateChildNode(new LinearExtrusion(profile, 10) { Center = true, Slices = 3, Twist = 90.0 });

scene
```

### Ver también

* class [Entity](../../aspose.threed/entity/)
* interface [IMeshConvertible](../imeshconvertible/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


