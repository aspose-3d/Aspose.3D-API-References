---
title: "Aspose.ThreeD.Animation"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "El espacio de nombres de animación de Aspose.3D donde se definen todas las clases relacionadas con la animación"
type: docs
weight: 20
url: /es/net/aspose.threed.animation/
---
El espacio de nombres de animación de Aspose.3D, todas las clases relacionadas con la animación se definen en este espacio de nombres

## Clases

| Clase | Descripción |
| --- | --- |
| [AnimationChannel](./animationchannel/) | Un canal asigna el campo de componente de la propiedad a un conjunto de secuencias de fotogramas clave |
| [AnimationClip](./animationclip/) | El clip de animación es una colección de animaciones. La escena puede tener uno o más clips de animación. |
| [AnimationNode](./animationnode/) | Aspose.3D admite jerarquía de animación, cada animación puede estar compuesta por varias animaciones y la definición de fotogramas clave de la animación. [`AnimationNode`](../aspose.threed.animation/animationnode/) define la transformación de un valor de propiedad a lo largo del tiempo; por ejemplo, el nodo de animación puede usarse para controlar la transformación de un nodo u otras propiedades numéricas de un objeto [`A3DObject`](../aspose.threed/a3dobject/). |
| [BindPoint](./bindpoint/) | Un [`BindPoint`](../aspose.threed.animation/bindpoint/) suele crearse en la propiedad de un objeto; algunos tipos de propiedad contienen múltiples campos de componentes (como un campo Vector3). [`BindPoint`](../aspose.threed.animation/bindpoint/) generará un canal para cada campo de componente y conectará el campo a una o más instancias de secuencia de fotogramas clave mediante los canales. |
| [Extrapolation](./extrapolation/) | La extrapolación define qué hacer cuando el valor muestreado está fuera del rango definido por el primer y último fotograma clave. |
| [KeyFrame](./keyframe/) | Un fotograma clave se define principalmente por un tiempo y un valor; para algunos tipos de interpolación, también se utilizan tangente/ tensión/ sesgo/ continuidad al calcular el valor muestreado final. Los valores muestreados en una posición de tiempo sin fotograma clave se interpolan mediante los fotogramas clave entre el fotograma clave anterior y el siguiente. Los valores antes/después del primer/último fotograma clave se calculan mediante la clase [`Extrapolation`](../aspose.threed.animation/extrapolation/). |
| [KeyframeSequence](./keyframesequence/) | La secuencia de fotogramas clave, describe la transformación de un valor muestreado a lo largo del tiempo. |
## Enumeración

| Enumeración | Descripción |
| --- | --- |
| [ExtrapolationType](./extrapolationtype/) | Tipo de extrapolación. |
| [Interpolation](./interpolation/) | El tipo de interpolación del fotograma clave. |
| [StepMode](./stepmode/) | Modo de paso de interpolación. |
| [WeightedMode](./weightedmode/) | Modo ponderado. |


