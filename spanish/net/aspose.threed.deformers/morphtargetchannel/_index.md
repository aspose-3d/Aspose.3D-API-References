---
title: "Clase MorphTargetChannel"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Deformers.MorphTargetChannel. Un MorphTargetChannel es usado por MorphTargetDeformer para organizar las geometrías objetivo. Algunos formatos de archivo como FBX admiten múltiples canales en paralelo."
type: docs
weight: 220
url: /es/net/aspose.threed.deformers/morphtargetchannel/
---
## MorphTargetChannel class

Un MorphTargetChannel es usado por [`MorphTargetDeformer`](../morphtargetdeformer/) para organizar las geometrías objetivo. Algunos formatos de archivo como FBX admiten múltiples canales en paralelo.

```csharp
public class MorphTargetChannel : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MorphTargetChannel](morphtargetchannel/#constructor)() | Inicializa una nueva instancia de la clase `MorphTargetChannel`. |
| [MorphTargetChannel](morphtargetchannel/#constructor_1)(string) | Inicializa una nueva instancia de la clase `MorphTargetChannel`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [ChannelWeight](../../aspose.threed.deformers/morphtargetchannel/channelweight/) { get; set; } | Obtiene o establece el peso del deformador de este canal. El peso está entre 0.0 y 1.0 |
| [Item](../../aspose.threed.deformers/morphtargetchannel/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [Targets](../../aspose.threed.deformers/morphtargetchannel/targets/) { get; } | Obtiene todos los objetivos asociados con el canal. |
| [Weights](../../aspose.threed.deformers/morphtargetchannel/weights/) { get; } | Obtiene los valores de peso completos de las geometrías objetivo. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [GetWeight](../../aspose.threed.deformers/morphtargetchannel/getweight/)(Shape) | Obtiene el peso del objetivo especificado; si el objetivo no pertenece a este canal, se devuelve el valor predeterminado 0. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |
| [SetWeight](../../aspose.threed.deformers/morphtargetchannel/setweight/)(Shape, double) | Establece el peso del objetivo especificado, el valor predeterminado es 1, el rango debe estar entre 0~1. |

## Campos

| Nombre | Descripción |
| --- | --- |
| const [DefaultWeight](../../aspose.threed.deformers/morphtargetchannel/defaultweight/) | Peso predeterminado para el morph target. |

## Observaciones

El peso está entre 0 y 1.0, y el peso predeterminado para el objetivo es 0.0;

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


