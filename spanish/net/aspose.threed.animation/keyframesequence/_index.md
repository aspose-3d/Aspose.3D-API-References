---
title: "Clase KeyframeSequence"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Clase Aspose.ThreeD.Animation.KeyframeSequence. La secuencia de fotogramas clave describe la transformación de un valor muestreado a lo largo del tiempo"
type: docs
weight: 100
url: /es/net/aspose.threed.animation/keyframesequence/
---
## KeyframeSequence class

La secuencia de fotogramas clave, describe la transformación de un valor muestreado a lo largo del tiempo.

```csharp
public class KeyframeSequence : A3DObject, IEnumerable<KeyFrame>
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [KeyframeSequence](keyframesequence/#constructor)() | Inicializa una nueva instancia de la clase `KeyframeSequence`. |
| [KeyframeSequence](keyframesequence/#constructor_1)(string) | Inicializa una nueva instancia de la clase `KeyframeSequence`. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [BindPoint](../../aspose.threed.animation/keyframesequence/bindpoint/) { get; } | Obtiene el punto de enlace de la propiedad que posee esta curva |
| [KeyFrames](../../aspose.threed.animation/keyframesequence/keyframes/) { get; } | Obtiene los fotogramas clave de esta curva. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Obtiene o establece el nombre. |
| [PostBehavior](../../aspose.threed.animation/keyframesequence/postbehavior/) { get; } | Obtiene el comportamiento posterior que indica cuál debe ser el valor muestreado después del último fotograma clave. |
| [PreBehavior](../../aspose.threed.animation/keyframesequence/prebehavior/) { get; } | Obtiene el comportamiento previo que indica cuál debe ser el valor muestreado antes del primer fotograma clave. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Obtiene la colección de todas las propiedades. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add)(double, float) | Crea un nuevo fotograma clave con el valor especificado |
| [Add](../../aspose.threed.animation/keyframesequence/add/#add_1)(double, float, Interpolation) | Crea un nuevo fotograma clave con el valor especificado |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Encuentra la propiedad. Puede ser una propiedad dinámica (Creada por CreateDynamicProperty/SetProperty) o una propiedad nativa (Identificada por su nombre) |
| [GetEnumerator](../../aspose.threed.animation/keyframesequence/getenumerator/)() | Obtiene el enumerador para recorrer todos los fotogramas clave. |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Obtén el valor de la propiedad especificada |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Elimina una propiedad dinámica. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Elimina la propiedad especificada identificada por nombre |
| [Reset](../../aspose.threed.animation/keyframesequence/reset/)() | Elimina todos los fotogramas clave y restablece los comportamientos posterior y previo. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Establece el valor de la propiedad especificada |

### Ver también

* class [A3DObject](../../aspose.threed/a3dobject/)
* class [KeyFrame](../keyframe/)
* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


