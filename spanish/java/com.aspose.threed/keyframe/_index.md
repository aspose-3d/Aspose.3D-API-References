---
title: KeyFrame
second_title: Referencia de API de Aspose.3D para Java
description: Un fotograma clave se define principalmente por un tiempo y un valor; para algunos tipos de interpolación, tangente/tensión/sesgo/continuidad también se utilizan al calcular el valor muestreado final.
type: docs
weight: 89
url: /es/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Un fotograma clave se define principalmente por un tiempo y un valor; para algunos tipos de interpolación, tangente/tensión/sesgo/continuidad también se utilizan al calcular el valor muestreado final. Los valores muestreados en una posición de tiempo que no es un fotograma clave se interpolan mediante fotogramas clave entre los fotogramas clave anteriores y siguientes. El valor antes/después del primer/último fotograma clave se calcula mediante la clase [Extrapolation](../../com.aspose.threed/extrapolation).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Crear un nuevo fotograma clave en la curva especificada |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | Obtiene el sesgo usado en la spline TCB |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | Obtiene la continuidad usada en la spline TCB |
| [getFlat()](#getFlat--) | Obtener o establecer si el fotograma clave es plano. |
| [getIndependentTangent()](#getIndependentTangent--) | Obtiene si las tangentes de salida y la siguiente de entrada son independientes. |
| [getInterpolation()](#getInterpolation--) | Obtiene el tipo de interpolación de la clave, list.data[index] define el algoritmo de cómo se calcula el valor muestreado. |
| [getNextInTangent()](#getNextInTangent--) | Obtiene la siguiente tangente de entrada (izquierda) en este fotograma clave. |
| [getNextInWeight()](#getNextInWeight--) | Obtiene el siguiente peso de entrada (izquierda) en este fotograma clave. |
| [getOutTangent()](#getOutTangent--) | Obtiene la tangente de salida (derecha) en este fotograma clave. |
| [getOutWeight()](#getOutWeight--) | Obtiene el peso de salida (derecha) en este fotograma clave. |
| [getStepMode()](#getStepMode--) | Obtiene el modo de paso de la clave. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Obtiene el modo de peso de la tangente de la clave. |
| [getTension()](#getTension--) | Obtiene la tensión usada en la spline TCB |
| [getTime()](#getTime--) | Obtiene la posición temporal del fotograma clave list.data[index], medida en segundos. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Obtiene que la tangente es independiente del tiempo. |
| [getValue()](#getValue--) | Obtiene el valor del fotograma clave. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | Establece el sesgo usado en la spline TCB |
| [setContinuity(float value)](#setContinuity-float-) | Establece la continuidad usada en la spline TCB |
| [setFlat(boolean value)](#setFlat-boolean-) | Obtener o establecer si el fotograma clave es plano. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Establece que las tangentes de salida y la siguiente de entrada son independientes. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Establece el tipo de interpolación de la clave, list.data[index] define el algoritmo de cómo se calcula el valor muestreado. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Establece la siguiente tangente de entrada (izquierda) en este fotograma clave. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Establece el peso de la siguiente entrada (izquierda) en este fotograma clave. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Establece la tangente de salida (derecha) en este fotograma clave. |
| [setOutWeight(float value)](#setOutWeight-float-) | Establece el peso de salida (derecha) en este fotograma clave. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Establece el modo de paso de la clave. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Establece el modo de peso de la tangente de la clave. |
| [setTension(float value)](#setTension-float-) | Establece la tensión utilizada en la spline TCB |
| [setTime(double value)](#setTime-double-) | Establece la posición temporal del fotograma clave list.data[index], medida en segundos. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Establece que la tangente es independiente del tiempo |
| [setValue(float value)](#setValue-float-) | Establece el valor del fotograma clave. |
| [toString()](#toString--) | Obtiene la representación en cadena del fotograma clave |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Crear un nuevo fotograma clave en la curva especificada

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | La curva en la que se creará el fotograma clave |
| tiempo | double | La posición temporal del fotograma clave |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


Obtiene el sesgo usado en la spline TCB

**Returns:**
float - el sesgo utilizado en la spline TCB
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContinuity() {#getContinuity--}
```
public float getContinuity()
```


Obtiene la continuidad usada en la spline TCB

**Returns:**
float - la continuidad utilizada en la spline TCB
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Obtenga o establezca si el fotograma clave es plano. El fotograma clave debe ser plano si el siguiente o anterior fotograma clave tiene el mismo valor. Un fotograma clave plano tiene tangentes planas e interpolación fija.

**Returns:**
boolean - Obtenga o establezca si el fotograma clave es plano. El fotograma clave debe ser plano si el siguiente o anterior fotograma clave tiene el mismo valor. Un fotograma clave plano tiene tangentes planas e interpolación fija.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Obtiene si las tangentes de salida y la siguiente de entrada son independientes.

**Returns:**
boolean - la tangente de salida y la siguiente de entrada son independientes.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Obtiene el tipo de interpolación de la clave, list.data[index] define el algoritmo de cómo se calcula el valor muestreado.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Obtiene la siguiente tangente de entrada (izquierda) en este fotograma clave.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Obtiene el siguiente peso de entrada (izquierda) en este fotograma clave.

**Returns:**
float - el peso de la siguiente entrada (izquierda) en este fotograma clave.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Obtiene la tangente de salida (derecha) en este fotograma clave.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Obtiene el peso de salida (derecha) en este fotograma clave.

**Returns:**
float - el peso de salida (derecha) en este fotograma clave.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Obtiene el modo de paso de la clave. Si el tipo de interpolación es [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decide qué valor del fotograma clave se utilizará durante la interpolación. Un [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) significa que se usará el valor del fotograma clave izquierdo. Un [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) significa que se usará el valor del siguiente fotograma clave derecho.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Obtiene el modo de peso de la tangente de la clave. La tangente de salida o la siguiente tangente de entrada pueden personalizarse seleccionando el [WeightedMode](../../com.aspose.threed/weightedmode) correcto.

**Returns:**
int - el modo de peso de la tangente de la clave. La tangente de salida o la siguiente tangente de entrada pueden personalizarse seleccionando el [WeightedMode](../../com.aspose.threed/weightedmode) correcto.
### getTension() {#getTension--}
```
public float getTension()
```


Obtiene la tensión usada en la spline TCB

**Returns:**
float - tensión utilizada en la spline TCB
### getTime() {#getTime--}
```
public double getTime()
```


Obtiene la posición temporal del fotograma clave list.data[index], medida en segundos.

**Returns:**
double - la posición temporal del fotograma clave list.data[index], medida en segundos.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Obtiene que la tangente es independiente del tiempo.

**Returns:**
boolean - la tangente es independiente del tiempo
### getValue() {#getValue--}
```
public float getValue()
```


Obtiene el valor del fotograma clave.

**Returns:**
float - el valor del fotograma clave.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setBias(float value) {#setBias-float-}
```
public void setBias(float value)
```


Establece el sesgo usado en la spline TCB

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


Establece la continuidad usada en la spline TCB

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Obtenga o establezca si el fotograma clave es plano. El fotograma clave debe ser plano si el siguiente o anterior fotograma clave tiene el mismo valor. Un fotograma clave plano tiene tangentes planas e interpolación fija.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Establece que las tangentes de salida y la siguiente de entrada son independientes.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Establece el tipo de interpolación de la clave, list.data[index] define el algoritmo de cómo se calcula el valor muestreado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Nuevo valor |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Establece la siguiente tangente de entrada (izquierda) en este fotograma clave.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Establece el peso de la siguiente entrada (izquierda) en este fotograma clave.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Establece la tangente de salida (derecha) en este fotograma clave.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuevo valor |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Establece el peso de salida (derecha) en este fotograma clave.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Establece el modo de paso de la clave. Si el tipo de interpolación es [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decide qué valor del fotograma clave se utilizará durante la interpolación. Un [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) significa que se usará el valor del fotograma clave izquierdo. Un [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) significa que se usará el valor del siguiente fotograma clave derecho.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Nuevo valor |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Establece el modo de peso de la tangente de la clave. La tangente de salida o la siguiente tangente de entrada pueden personalizarse seleccionando el [WeightedMode](../../com.aspose.threed/weightedmode) correcto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | Nuevo valor |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Establece la tensión utilizada en la spline TCB

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


Establece la posición temporal del fotograma clave list.data[index], medida en segundos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | double | Nuevo valor |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Establece que la tangente es independiente del tiempo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | boolean | Nuevo valor |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Establece el valor del fotograma clave.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | float | Nuevo valor |

### toString() {#toString--}
```
public String toString()
```


Obtiene la representación en cadena del fotograma clave

**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

