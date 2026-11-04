---
title: "Clase SkinDeformer"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Deformers.SkinDeformer. Un deformer de piel contiene múltiples huesos; cada hueso combina una parte de la geometría mediante pesos de puntos de control."
type: docs
weight: 240
url: /es/net/aspose.threed.deformers/skindeformer/
---
## SkinDeformer class

Un deformer de piel contiene varios huesos para trabajar, cada hueso mezcla una parte de la geometría mediante los pesos de los puntos de control.

```csharp
public class SkinDeformer : Deformer
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [SkinDeformer](skindeformer/#constructor)() | Inicializa una nueva instancia de la clase `SkinDeformer`. |
| [SkinDeformer](skindeformer/#constructor_1)(string) | Inicializa una nueva instancia de la clase `SkinDeformer`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bones](../../aspose.threed.deformers/skindeformer/bones/) { get; } | Obtiene todos los huesos que contiene el deformer de piel |
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


