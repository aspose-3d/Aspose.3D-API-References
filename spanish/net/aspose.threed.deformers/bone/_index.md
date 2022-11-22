---
title: Bone
second_title: Referencia de API de Aspose.3D para .NET
description: Un hueso define el subconjunto del punto de control de la geometría y el peso de mezcla definido para cada punto de control. ElBone./bone objeto no se puede utilizar directamente unSkinDeformer./skindeformer instancia se utiliza para deformar la geometría ySkinDeformer./skindeformerviene con un conjunto de huesos cada hueso vinculado a un nodo. NOTA Un punto de control de una geometría puede estar delimitado a más de un Hueso.
type: docs
weight: 180
url: /es/net/aspose.threed.deformers/bone/
---
## Bone class

Un hueso define el subconjunto del punto de control de la geometría y el peso de mezcla definido para cada punto de control. El[`Bone`](../bone) objeto no se puede utilizar directamente, un[`SkinDeformer`](../skindeformer) instancia se utiliza para deformar la geometría, y[`SkinDeformer`](../skindeformer)viene con un conjunto de huesos, cada hueso vinculado a un nodo. NOTA: Un punto de control de una geometría puede estar delimitado a más de un Hueso.

```csharp
public class Bone : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Bone](bone#constructor)() | Inicializa una nueva instancia del[`Bone`](../bone) clase. |
| [Bone](bone#constructor_1)(string) | Inicializa una nueva instancia del[`Bone`](../bone) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BoneTransform](../../aspose.threed.deformers/bone/bonetransform) { get; set; } | Obtiene o establece la matriz de transformación del hueso. |
| [Item](../../aspose.threed.deformers/bone/item) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [Node](../../aspose.threed.deformers/bone/node) { get; set; } | Obtiene o establece el nodo. El nódulo óseo es el hueso al que se adhiere la piel, el[`SkinDeformer`](../skindeformer) utilizará el nodo óseo para influir en el desplazamiento de los puntos de control. El nodo óseo suele tener un[`Skeleton`](../../aspose.threed.entities/skeleton)adjunto, pero no es obligatorio. Adjunto[`Skeleton`](../../aspose.threed.entities/skeleton) generalmente lo usa el software DCC para mostrar el esqueleto al usuario. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |
| [Transform](../../aspose.threed.deformers/bone/transform) { get; set; } | Obtiene o establece la matriz de transformación del nodo que contiene el hueso. |
| [WeightCount](../../aspose.threed.deformers/bone/weightcount) { get; } | Obtiene el conteo de peso, este se extiende automáticamente por[`SetWeight`](./setweight) |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [GetWeight](../../aspose.threed.deformers/bone/getweight)(int) | Obtiene el peso del punto de control especificado por index |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |
| [SetWeight](../../aspose.threed.deformers/bone/setweight)(int, double) | Establece el peso para el punto de control especificado por index |

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject)
* espacio de nombres [Aspose.ThreeD.Deformers](../../aspose.threed.deformers)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->