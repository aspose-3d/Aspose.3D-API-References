---
title: "Clase AnimationNode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Animation.AnimationNode. Aspose.3Ds admite jerarquía de animación; cada animación puede estar compuesta por varias animaciones y la definición de fotogramas clave de la animación. AnimationNode define la transformación de un valor de propiedad a lo largo del tiempo; por ejemplo, un nodo de animación puede usarse para controlar la transformación de un nodo o las propiedades numéricas de otros objetos A3DObject."
type: docs
weight: 40
url: /es/net/aspose.threed.animation/animationnode/
---
## AnimationNode class

Aspose.3D admite jerarquía de animación, cada animación puede estar compuesta por varias animaciones y la definición de fotogramas clave de la animación. `AnimationNode` define la transformación de un valor de propiedad a lo largo del tiempo; por ejemplo, un nodo de animación puede usarse para controlar la transformación de un nodo o las propiedades numéricas de otro objeto [`A3DObject`](../../aspose.threed/a3dobject/).

```csharp
public class AnimationNode : A3DObject
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [AnimationNode](animationnode/#constructor)() | Inicializa una nueva instancia de la clase `AnimationNode`. |
| [AnimationNode](animationnode/#constructor_1)(string) | Inicializa una nueva instancia de la clase `AnimationNode`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BindPoints](../../aspose.threed.animation/animationnode/bindpoints/) { get; } | Obtiene los puntos de enlace de propiedad actuales |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |
| [SubAnimations](../../aspose.threed.animation/animationnode/subanimations/) { get; } | Obtiene los nodos de subanimación bajo las animaciones actuales |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [CreateBindPoint](../../aspose.threed.animation/animationnode/createbindpoint/)(A3DObject, string) | Crea un BindPoint basado en el tipo de datos de la propiedad. |
| [FindBindPoint](../../aspose.threed.animation/animationnode/findbindpoint/)(A3DObject, string) | Encuentra el punto de enlace por objetivo y nombre. |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetBindPoint](../../aspose.threed.animation/animationnode/getbindpoint/)(A3DObject, string, bool) | Obtiene el punto de enlace de animación en la propiedad dada. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence)(A3DObject, string, bool) | Obtiene la secuencia de fotogramas clave en la propiedad dada. |
| [GetKeyframeSequence](../../aspose.threed.animation/animationnode/getkeyframesequence/#getkeyframesequence_1)(A3DObject, string, string, bool) | Obtiene la secuencia de fotogramas clave en la propiedad y canal dados. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


