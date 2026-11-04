---
title: "Clase MorphTargetDeformer"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Deformers.MorphTargetDeformer class. MorphTargetDeformer proporciona animación por vértice. MorphTargetDeformer organiza todos los objetivos a través de MorphTargetChannel; cada canal puede organizar múltiples objetivos. Un uso común del deformer de morph target es aplicar expresiones faciales a un personaje. Se pueden encontrar más detalles en https//en.wikipedia.org/wiki/Morph_target_animation"
type: docs
weight: 230
url: /es/net/aspose.threed.deformers/morphtargetdeformer/
---
## MorphTargetDeformer class

MorphTargetDeformer proporciona animación por vértice. MorphTargetDeformer organiza todos los objetivos a través de [`MorphTargetChannel`](../morphtargetchannel/), cada canal puede organizar múltiples objetivos. Un uso común del deformer de morph target es aplicar expresiones faciales a un personaje. Se pueden encontrar más detalles en https://en.wikipedia.org/wiki/Morph_target_animation

```csharp
public class MorphTargetDeformer : Deformer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [MorphTargetDeformer](morphtargetdeformer/#constructor)() | Inicializa una nueva instancia de la clase `MorphTargetDeformer`. |
| [MorphTargetDeformer](morphtargetdeformer/#constructor_1)(string) | Inicializa una nueva instancia de la clase `MorphTargetDeformer`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Channels](../../aspose.threed.deformers/morphtargetdeformer/channels/) { get; } | Obtiene todos los canales contenidos en este deformer |
| [Item](../../aspose.threed.deformers/morphtargetdeformer/item/) { get; set; } |  |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Owner](../../aspose.threed.deformers/deformer/owner/) { get; } | Obtiene la geometría que posee este deformer |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [Deformer](../deformer/)
* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


