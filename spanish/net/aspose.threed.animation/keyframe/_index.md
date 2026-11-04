---
title: "Clase KeyFrame"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Aspose.ThreeD.Animation.KeyFrame class. Un fotograma clave se define principalmente por un tiempo y un valor; para algunos tipos de interpolación, tangente/ tensión/ sesgo/ continuidad también se utilizan al calcular el valor muestreado final. Los valores muestreados en una posición de tiempo sin fotograma clave se interpolan mediante fotogramas clave entre el fotograma clave anterior y el siguiente. El valor antes/después del primer/último fotograma clave se calcula mediante la clase Extrapolation."
type: docs
weight: 90
url: /es/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

Un fotograma clave se define principalmente por un tiempo y un valor; para algunos tipos de interpolación, tangente/ tensión/ sesgo/ continuidad también se utilizan al calcular el valor muestreado final. Los valores muestreados en una posición de tiempo sin fotograma clave se interpolan mediante fotogramas clave entre el fotograma clave anterior y el siguiente. El valor antes/después del primer/último fotograma clave se calcula mediante la clase [`Extrapolation`](../extrapolation/).

```csharp
public class KeyFrame
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [KeyFrame](keyframe/)(KeyframeSequence, double) | Crear un nuevo fotograma clave en la curva especificada |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias/) { get; set; } | Obtiene o establece el sesgo usado en la spline TCB |
| [Continuity](../../aspose.threed.animation/keyframe/continuity/) { get; set; } | Obtiene o establece la continuidad usada en la spline TCB |
| [Flat](../../aspose.threed.animation/keyframe/flat/) { get; set; } | Obtiene o establece si el fotograma clave es plano. El fotograma clave debe ser plano si el siguiente o el anterior fotograma clave tiene el mismo valor. Un fotograma clave plano tiene tangentes planas e interpolación fija. |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent/) { get; set; } | Obtiene o establece si las tangentes de salida y la siguiente de entrada son independientes. |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation/) { get; set; } | Obtiene o establece el tipo de interpolación de la clave, list.data[index] define el algoritmo de cómo se calcula el valor muestreado. |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent/) { get; set; } | Obtiene o establece la siguiente tangente de entrada (izquierda) en este fotograma clave. |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight/) { get; set; } | Obtiene o establece el siguiente peso de entrada (izquierda) en este fotograma clave. |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent/) { get; set; } | Obtiene o establece la tangente de salida (derecha) en este fotograma clave. |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight/) { get; set; } | Obtiene o establece el peso de salida (derecha) en este fotograma clave. |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode/) { get; set; } | Obtiene o establece el modo de paso de la clave. Si el tipo de interpolación es Constante, list.data[index] decide qué valor de fotograma clave se usará durante la interpolación. Un PreviousValue significa que se usará el valor del fotograma clave izquierdo. Un NextValue significa que se usará el valor del siguiente fotograma clave derecho. |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode/) { get; set; } | Obtiene o establece el modo de peso de la tangente de la clave. La tangente de salida o la siguiente tangente de entrada pueden personalizarse seleccionando el [`WeightedMode`](../weightedmode/) correcto. |
| [Tension](../../aspose.threed.animation/keyframe/tension/) { get; set; } | Obtiene o establece la tensión usada en la spline TCB |
| [Time](../../aspose.threed.animation/keyframe/time/) { get; set; } | Obtiene o establece la posición temporal del fotograma clave list.data[index], medida en segundos. |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent/) { get; set; } | Obtiene o establece que la tangente es independiente del tiempo |
| [Value](../../aspose.threed.animation/keyframe/value/) { get; set; } | Obtiene o establece el valor del fotograma clave. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring/)() | Obtiene la representación en cadena del fotograma clave |

### Ver también

* namespace [Aspose.ThreeD.Animation](../../aspose.threed.animation/)
* assembly [Aspose.3D](../../)


