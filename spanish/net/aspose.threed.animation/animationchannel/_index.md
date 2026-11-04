---
title: "Clase AnimationChannel"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Animation.AnimationChannel. Un canal asigna el campo de componente de propiedades a un conjunto de secuencias de fotogramas clave"
type: docs
weight: 20
url: /es/net/aspose.threed.animation/animationchannel/
---
## AnimationChannel class

Un canal asigna el campo de componente de la propiedad a un conjunto de secuencias de fotogramas clave

```csharp
public class AnimationChannel : KeyframeSequence
```

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Obtiene el punto de enlace de la propiedad que posee esta curva |
| [ComponentType](../../aspose.threed.animation/animationchannel/componenttype/) { get; } | Obtiene el tipo del campo del componente |
| [DefaultValue](../../aspose.threed.animation/animationchannel/defaultvalue/) { get; set; } | Obtiene o establece el valor predeterminado del canal. Si un canal no tiene secuencias de fotogramas clave conectadas, se utilizará el valor predeterminado durante la evaluación de la animación. Un caso real: la animación solo anima la coordenada x de un nodo, las coordenadas y y z no se modifican, entonces se usará el valor predeterminado durante la evaluación completa de la traducción. |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Obtiene los fotogramas clave de esta curva. |
| [KeyframeSequence](../../aspose.threed.animation/animationchannel/keyframesequence/) { get; set; } | Obtiene la secuencia de fotogramas clave asociada dentro de este canal |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Obtiene el comportamiento posterior que indica cuál debe ser el valor muestreado después del último fotograma clave. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Obtiene el comportamiento previo que indica cuál debe ser el valor muestreado antes del primer fotograma clave. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float) | Crea un nuevo fotograma clave con el valor especificado |
| [Add](../../aspose.threed.animation/keyframesequence/add/)(double, float, Interpolation) | Crea un nuevo fotograma clave con el valor especificado |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Obtiene el enumerador para recorrer todos los fotogramas clave. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Elimina todos los fotogramas clave y restablece los comportamientos posterior y previo. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [KeyframeSequence](../keyframesequence/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


