---
title: "Clase Bone"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Deformers.Bone. Un hueso define el subconjunto del punto de control de la geometría y define el peso de mezcla para cada punto de control. El objeto Bone no puede usarse directamente; se utiliza una instancia de SkinDeformer para deformar la geometría y SkinDeformer viene con un conjunto de huesos, cada hueso vinculado a un nodo. NOTA: Un punto de control de una geometría puede estar vinculado a más de un hueso."
type: docs
weight: 190
url: /es/net/aspose.threed.deformers/bone/
---
## Bone class

Un hueso define el subconjunto del punto de control de la geometría y define el peso de mezcla para cada punto de control. El objeto `Bone` no puede usarse directamente, una instancia de [`SkinDeformer`](../skindeformer/) se utiliza para deformar la geometría, y [`SkinDeformer`](../skindeformer/) viene con un conjunto de huesos, cada hueso vinculado a un nodo. NOTA: Un punto de control de una geometría puede estar vinculado a más de un hueso.

```csharp
public class Bone : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Bone](bone/#constructor)() | Inicializa una nueva instancia de la clase `Bone`. |
| [Bone](bone/#constructor_1)(string) | Inicializa una nueva instancia de la clase `Bone`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform/) { get; set; } | Obtiene o establece la matriz de transformación del hueso. |
| [Item](../../aspose.threed.deformers/bone/item/) { get; set; } |  |
| [LinkMode](../../aspose.threed.deformers/bone/linkmode/) { get; set; } | El modo de enlace de un hueso se refiere a la forma en que un hueso está conectado o enlazado a su hueso padre dentro de una estructura jerárquica. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Node](../../aspose.threed.deformers/bone/node/) { get; set; } | Obtiene o establece el nodo. El nodo del hueso es el hueso al que se adjunta la piel, el [`SkinDeformer`](../skindeformer/) utilizará el nodo del hueso para influir en el desplazamiento de los puntos de control. El nodo del hueso suele tener un [`Skeleton`](../../aspose.threed.entities/skeleton/) adjunto, pero no es obligatorio. El [`Skeleton`](../../aspose.threed.entities/skeleton/) adjunto suele ser usado por el software DCC para mostrar el esqueleto al usuario. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Transform](../../aspose.threed.deformers/bone/transform/) { get; set; } | Obtiene o establece la matriz de transformación del nodo que contiene el hueso. |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount/) { get; } | Obtiene el recuento de peso, este se amplía automáticamente mediante [`SetWeight`](./setweight/) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [GetWeight](../../aspose.threed.deformers/bone/getweight/)(int) | Obtiene el peso del punto de control especificado por índice |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| [SetWeight](../../aspose.threed.deformers/bone/setweight/)(int, double) | Establece el peso del punto de control especificado por índice |

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


