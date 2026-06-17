---
title: "KeyFrame"
second_title: "Referencia de API de Aspose.3D para Node.js vía Java"
description: 
type: docs

url: /es/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Un fotograma clave se define principalmente por un tiempo y un valor; para algunos tipos de interpolación, también se utilizan tangente/ tensión/ sesgo/ continuidad al calcular el valor muestreado final.  Los valores muestreados en una posición de tiempo sin fotograma clave se interpolan mediante fotogramas clave entre el fotograma clave anterior y el siguiente.  Los valores antes/después del primer/último fotograma clave se calculan con la clase Extrapolation.


## Métodos

### constructor{#constructor}

| Nombre | Descripción |
| --- | --- |
| constructor(curve, time) | Crear un nuevo fotograma clave en la curva especificada |

 **Parameters:**

| Nombre | Tipo | Descripción |
| --- | --- | --- |
| curve | KeyframeSequence | La curva en la que se creará el fotograma clave |
| tiempo | Número | La posición de tiempo del fotograma clave |

 **Result:**



---


### getTime{#getTime}

| Nombre | Descripción |
| --- | --- |
| getTime() | Obtiene o establece la posición de tiempo del fotograma clave list.data[index], medida en segundos. El tiempo. |

 **Result:**



---


### setTime{#setTime}

| Nombre | Descripción |
| --- | --- |
| setTime(value) | Obtiene o establece la posición de tiempo del fotograma clave list.data[index], medida en segundos. El tiempo. |

 **Result:**



---


### getValue{#getValue}

| Nombre | Descripción |
| --- | --- |
| getValue() | Obtiene o establece el valor del fotograma clave. El valor. |

 **Result:**



---


### setValue{#setValue}

| Nombre | Descripción |
| --- | --- |
| setValue(value) | Obtiene o establece el valor del fotograma clave. El valor. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Nombre | Descripción |
| --- | --- |
| getInterpolation() | Obtiene o establece el tipo de interpolación de la clave, list.data[index] define el algoritmo con el que se calcula el valor muestreado. El valor de la propiedad es la constante entera Interpolation. La interpolación. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Nombre | Descripción |
| --- | --- |
| setInterpolation(value) | Obtiene o establece el tipo de interpolación de la clave, list.data[index] define el algoritmo con el que se calcula el valor muestreado. El valor de la propiedad es la constante entera Interpolation. La interpolación. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Nombre | Descripción |
| --- | --- |
| getTangentWeightMode() | Obtiene o establece el modo de peso de la tangente de la clave. La tangente de salida o la siguiente tangente de entrada pueden personalizarse seleccionando el WeightedMode correcto. El valor de la propiedad es la constante entera WeightedMode. El modo de peso de la tangente. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Nombre | Descripción |
| --- | --- |
| setTangentWeightMode(value) | Obtiene o establece el modo de peso de la tangente de la clave. La tangente de salida o la siguiente tangente de entrada pueden personalizarse seleccionando el WeightedMode correcto. El valor de la propiedad es la constante entera WeightedMode. El modo de peso de la tangente. |

 **Result:**



---


### getStepMode{#getStepMode}

| Nombre | Descripción |
| --- | --- |
| getStepMode() | Obtiene o establece el modo de paso de la clave. Si el tipo de interpolación es Interpolation.CONSTANT, list.data[index] decide qué valor del fotograma clave se utilizará durante la interpolación. Un StepMode.PREVIOUS_VALUE significa que se usará el valor del fotograma clave izquierdo. Un StepMode.NEXT_VALUE significa que se usará el valor del fotograma clave derecho siguiente. El valor de la propiedad es la constante entera StepMode. El modo de paso. |

 **Result:**



---


### setStepMode{#setStepMode}

| Nombre | Descripción |
| --- | --- |
| setStepMode(value) | Obtiene o establece el modo de paso de la clave. Si el tipo de interpolación es Interpolation.CONSTANT, list.data[index] decide qué valor del fotograma clave se utilizará durante la interpolación. Un StepMode.PREVIOUS_VALUE significa que se usará el valor del fotograma clave izquierdo. Un StepMode.NEXT_VALUE significa que se usará el valor del fotograma clave derecho siguiente. El valor de la propiedad es la constante entera StepMode. El modo de paso. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Nombre | Descripción |
| --- | --- |
| getNextInTangent() | Obtiene o establece la siguiente tangente de entrada (izquierda) en este fotograma clave. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Nombre | Descripción |
| --- | --- |
| setNextInTangent(value) | Obtiene o establece la siguiente tangente de entrada (izquierda) en este fotograma clave. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Nombre | Descripción |
| --- | --- |
| getOutTangent() | Obtiene o establece la tangente de salida (derecha) en este fotograma clave. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Nombre | Descripción |
| --- | --- |
| setOutTangent(value) | Obtiene o establece la tangente de salida (derecha) en este fotograma clave. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Nombre | Descripción |
| --- | --- |
| getOutWeight() | Obtiene o establece el peso de salida (derecha) en este fotograma clave. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Nombre | Descripción |
| --- | --- |
| setOutWeight(value) | Obtiene o establece el peso de salida (derecha) en este fotograma clave. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Nombre | Descripción |
| --- | --- |
| getNextInWeight() | Obtiene o establece el siguiente peso in(left) en este fotograma clave. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Nombre | Descripción |
| --- | --- |
| setNextInWeight(value) | Obtiene o establece el siguiente peso in(left) en este fotograma clave. |

 **Result:**



---


### getTension{#getTension}

| Nombre | Descripción |
| --- | --- |
| getTension() | Obtiene o establece la tensión utilizada en la spline TCB |

 **Result:**



---


### setTension{#setTension}

| Nombre | Descripción |
| --- | --- |
| setTension(value) | Obtiene o establece la tensión utilizada en la spline TCB |

 **Result:**



---


### getContinuity{#getContinuity}

| Nombre | Descripción |
| --- | --- |
| getContinuity() | Obtiene o establece la continuidad utilizada en la spline TCB |

 **Result:**



---


### setContinuity{#setContinuity}

| Nombre | Descripción |
| --- | --- |
| setContinuity(value) | Obtiene o establece la continuidad utilizada en la spline TCB |

 **Result:**



---


### getBias{#getBias}

| Nombre | Descripción |
| --- | --- |
| getBias() | Obtiene o establece el sesgo utilizado en la spline TCB |

 **Result:**



---


### setBias{#setBias}

| Nombre | Descripción |
| --- | --- |
| setBias(value) | Obtiene o establece el sesgo utilizado en la spline TCB |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Nombre | Descripción |
| --- | --- |
| getIndependentTangent() | Obtiene o establece que las tangentes de salida y la siguiente de entrada son independientes. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Nombre | Descripción |
| --- | --- |
| setIndependentTangent(value) | Obtiene o establece que las tangentes de salida y la siguiente de entrada son independientes. |

 **Result:**



---


### getFlat{#getFlat}

| Nombre | Descripción |
| --- | --- |
| getFlat() | Obtenga o establezca si el fotograma clave es plano. El fotograma clave debe ser plano si el siguiente o el anterior fotograma clave tiene el mismo valor. Un fotograma clave plano tiene tangentes planas e interpolación fija. |

 **Result:**



---


### setFlat{#setFlat}

| Nombre | Descripción |
| --- | --- |
| setFlat(value) | Obtenga o establezca si el fotograma clave es plano. El fotograma clave debe ser plano si el siguiente o el anterior fotograma clave tiene el mismo valor. Un fotograma clave plano tiene tangentes planas e interpolación fija. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Nombre | Descripción |
| --- | --- |
| getTimeIndependentTangent() | Obtiene o establece que la tangente es independiente del tiempo |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Nombre | Descripción |
| --- | --- |
| setTimeIndependentTangent(value) | Obtiene o establece que la tangente es independiente del tiempo |

 **Result:**



---


### toString{#toString}

| Nombre | Descripción |
| --- | --- |
| toString() | Obtiene la representación en cadena del fotograma clave |

 **Result:**
Cadena


---



