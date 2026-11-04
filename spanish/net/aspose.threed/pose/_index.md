---
title: "Clase Pose"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Pose. La pose se utiliza para almacenar la matriz de transformación cuando la geometría está skinneada. La pose es un conjunto de BonePose; cada BonePose guarda la información concreta de transformación del nodo óseo"
type: docs
weight: 1650
url: /es/net/aspose.threed/pose/
---
## Pose class

La pose se utiliza para almacenar la matriz de transformación cuando la geometría está skinneada. La pose es un conjunto de [`BonePose`](../bonepose/), cada [`BonePose`](../bonepose/) guarda la información concreta de transformación del nodo óseo.

```csharp
public class Pose : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Pose](pose/#constructor)() | Inicializa una nueva instancia de la clase `Pose`. |
| [Pose](pose/#constructor_1)(string) | Inicializa una nueva instancia de la clase `Pose`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes/) { get; } | Obtiene todos los [`BonePose`](../bonepose/). |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [PoseType](../../aspose.threed/pose/posetype/) { get; set; } | Obtiene o establece el tipo de la pose. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose)(Node, Matrix4) | Guarda la matriz de transformación de la pose para el nodo óseo dado. Se implica la matriz de transformación global. |
| [AddBonePose](../../aspose.threed/pose/addbonepose/#addbonepose_1)(Node, Matrix4, bool) | Guarda la matriz de transformación de la pose para el nodo óseo dado. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


