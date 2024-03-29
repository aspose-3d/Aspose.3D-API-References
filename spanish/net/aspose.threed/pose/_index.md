---
title: Pose
second_title: Referencia de API de Aspose.3D para .NET
description: La pose se usa para almacenar la matriz de transformación cuando la geometría está desollada. La pose es un conjunto deBonePose./bonepose  cadaBonePose./bonepose guarda la información de transformación concreta del nodo óseo.
type: docs
weight: 1490
url: /es/net/aspose.threed/pose/
---
## Pose class

La pose se usa para almacenar la matriz de transformación cuando la geometría está desollada. La pose es un conjunto de[`BonePose`](../bonepose) , cada[`BonePose`](../bonepose) guarda la información de transformación concreta del nodo óseo.

```csharp
public class Pose : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [Pose](pose#constructor)() | Inicializa una nueva instancia del[`Pose`](../pose) clase. |
| [Pose](pose#constructor_1)(string) | Inicializa una nueva instancia del[`Pose`](../pose) clase. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BonePoses](../../aspose.threed/pose/boneposes) { get; } | Obtiene todos[`BonePose`](../bonepose) . |
| virtual [Name](../../aspose.threed/a3dobject/name) { get; set; } | Obtiene o establece el nombre. |
| [PoseType](../../aspose.threed/pose/posetype) { get; set; } | Obtiene o establece el tipo de pose. |
| [Properties](../../aspose.threed/a3dobject/properties) { get; } | Obtiene la colección de todas las propiedades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [AddBonePose](../../aspose.threed/pose/addbonepose#addbonepose)(Node, Matrix4) | Guarda la matriz de transformación de pose para el nodo óseo dado. La matriz de transformación global está implícita. |
| [AddBonePose](../../aspose.threed/pose/addbonepose#addbonepose_1)(Node, Matrix4, bool) | Guarda la matriz de transformación de pose para el nodo óseo dado. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty)(string) | Obtener el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty)(string) | Eliminar la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [A3DObject](../a3dobject)
* espacio de nombres [Aspose.ThreeD](../../aspose.threed)
* asamblea [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
