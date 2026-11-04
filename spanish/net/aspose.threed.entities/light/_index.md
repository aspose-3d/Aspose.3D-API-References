---
title: "Clase Light"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Entities.Light. La luz ilumina la escena"
type: docs
weight: 460
url: /es/net/aspose.threed.entities/light/
---
## Light class

La luz ilumina la escena.

La fórmula para calcular la atenuación total de la luz es: `A = ConstantAttenuation + (Dist * LinearAttenuation) + ((Dist^2) * QuadraticAttenuation)`

```csharp
public class Light : Frustum
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Light](light/#constructor)() | Inicializa una nueva instancia de la clase `Light`. |
| [Light](light/#constructor_1)(string) | Inicializa una nueva instancia de la clase `Light`. |
| [Light](light/#constructor_2)(string, LightType) | Inicializa una nueva instancia de la clase `Light`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Aspect](../../aspose.threed.entities/frustum/aspect/) { get; set; } | Obtiene o establece la relación de aspecto del frustum |
| [CastLight](../../aspose.threed.entities/light/castlight/) { get; set; } | Obtiene o establece si la instancia actual de luz puede iluminar otros objetos. |
| [CastShadows](../../aspose.threed.entities/light/castshadows/) { get; set; } | Obtiene o establece si la luz puede proyectar sombras sobre otros objetos. |
| [Color](../../aspose.threed.entities/light/color/) { get; set; } | Obtiene o establece el color de la luz |
| [ConstantAttenuation](../../aspose.threed.entities/light/constantattenuation/) { get; set; } | Obtiene o establece la atenuación constante para calcular la atenuación total de la luz |
| [Direction](../../aspose.threed.entities/frustum/direction/) { get; set; } | Obtiene o establece la dirección a la que mira la cámara. Los cambios en esta propiedad también afectarán a [`LookAt`](../frustum/lookat/) y [`Target`](../frustum/target/). |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Obtiene o establece si excluir esta entidad durante la exportación. |
| [Falloff](../../aspose.threed.entities/light/falloff/) { get; set; } | Obtiene o establece el ángulo del cono de caída (en grados). |
| [FarPlane](../../aspose.threed.entities/frustum/farplane/) { get; set; } | Obtiene o establece la distancia del plano lejano del frustum. |
| [HotSpot](../../aspose.threed.entities/light/hotspot/) { get; set; } | Obtiene o establece el ángulo del cono del punto caliente (en grados). |
| [Intensity](../../aspose.threed.entities/light/intensity/) { get; set; } | Obtiene o establece la intensidad de la luz, el valor predeterminado es 100 |
| [LightType](../../aspose.threed.entities/light/lighttype/) { get; set; } | Obtiene o establece el tipo de la luz |
| [LinearAttenuation](../../aspose.threed.entities/light/linearattenuation/) { get; set; } | Obtiene o establece la atenuación lineal para calcular la atenuación total de la luz |
| [LookAt](../../aspose.threed.entities/frustum/lookat/) { get; set; } | Obtiene o establece la posición de interés a la que mira la cámara. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [NearPlane](../../aspose.threed.entities/frustum/nearplane/) { get; set; } | Obtiene o establece la distancia del plano cercano del frustum. |
| [OrthoHeight](../../aspose.threed.entities/frustum/orthoheight/) { get; set; } | Obtiene o establece la altura cuando el frustum está en proyección ortográfica. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Obtiene o establece el primer nodo padre; si se establece el primer nodo padre, esta entidad se desacoplará de los demás nodos padres. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Obtiene todos los nodos padre, una entidad puede estar adjunta a varios nodos padre para la instanciación de geometría |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [QuadraticAttenuation](../../aspose.threed.entities/light/quadraticattenuation/) { get; set; } | Obtiene o establece la atenuación cuadrática para calcular la atenuación total de la luz |
| [RotationMode](../../aspose.threed.entities/frustum/rotationmode/) { get; set; } | Obtiene o establece el modo de orientación del frustum. Esta propiedad solo funciona cuando [`Target`](../frustum/target/) es nulo. Si el valor es FixedTarget, la dirección siempre se calcula mediante la propiedad [`LookAt`](../frustum/lookat/). De lo contrario, [`LookAt`](../frustum/lookat/) siempre se calcula mediante [`Direction`](../frustum/direction/). |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Obtiene la escena a la que pertenece este objeto |
| [ShadowColor](../../aspose.threed.entities/light/shadowcolor/) { get; set; } | Obtiene o establece el color de la sombra. |
| [Target](../../aspose.threed.entities/frustum/target/) { get; set; } | Obtiene o establece el objetivo al que mira la cámara. Si el usuario admite esta propiedad, debe estar antes de la propiedad [`LookAt`](../frustum/lookat/). |
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

* class [Frustum](../frustum/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


