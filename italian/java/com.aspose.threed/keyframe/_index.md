---
title: KeyFrame
second_title: Aspose.3D for Java API Reference
description: Un key frame è principalmente definito da un tempo e da un valore; per alcuni tipi di interpolazione tangente/tensione/bias/continuità è anche usato nel calcolo del valore campionato finale.
type: docs
weight: 89
url: /it/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Un key frame è principalmente definito da un tempo e da un valore; per alcuni tipi di interpolazione, tangente/tensione/bias/continuità è anche usato nel calcolo del valore campionato finale. I valori campionati in una posizione temporale non appartenente a un key frame sono interpolati dai key frame tra i key frame precedenti e successivi. Il valore prima/dopo il primo/ultimo key frame è calcolato dalla classe [Extrapolation](../../com.aspose.threed/extrapolation).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Crea un nuovo key frame sulla curva specificata |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | Restituisce il bias usato nella TCB spline |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | Restituisce la continuità usata nella TCB spline |
| [getFlat()](#getFlat--) | Ottieni o imposta se il key frame è piatto. |
| [getIndependentTangent()](#getIndependentTangent--) | Restituisce che le tangenti out e next in sono indipendenti. |
| [getInterpolation()](#getInterpolation--) | Restituisce il tipo di interpolazione del key, list.data[index] definisce l'algoritmo con cui il valore campionato è calcolato. |
| [getNextInTangent()](#getNextInTangent--) | Restituisce la tangente in (sinistra) successiva su questo key frame. |
| [getNextInWeight()](#getNextInWeight--) | Restituisce il peso in (sinistra) successivo su questo key frame. |
| [getOutTangent()](#getOutTangent--) | Restituisce la tangente out (destra) su questo key frame. |
| [getOutWeight()](#getOutWeight--) | Restituisce il peso out (destra) su questo key frame. |
| [getStepMode()](#getStepMode--) | Restituisce la modalità step del key. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Restituisce la modalità di peso della tangente del key. |
| [getTension()](#getTension--) | Restituisce la tensione usata nella TCB spline |
| [getTime()](#getTime--) | Restituisce la posizione temporale del key frame list.data[index], misurata in secondi. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Restituisce che la tangente è indipendente dal tempo |
| [getValue()](#getValue--) | Restituisce il valore del key-frame. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | Imposta il bias usato nella TCB spline |
| [setContinuity(float value)](#setContinuity-float-) | Imposta la continuità usata nella TCB spline |
| [setFlat(boolean value)](#setFlat-boolean-) | Ottieni o imposta se il key frame è piatto. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Imposta che le tangenti di uscita e la successiva di ingresso siano indipendenti. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Imposta il tipo di interpolazione della chiave, list.data[index] definisce l'algoritmo con cui viene calcolato il valore campionato. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Imposta la tangente di ingresso (sinistra) successiva su questo fotogramma chiave. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Imposta il peso di ingresso (sinistra) successivo su questo fotogramma chiave. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Imposta la tangente di uscita (destra) su questo fotogramma chiave. |
| [setOutWeight(float value)](#setOutWeight-float-) | Imposta il peso di uscita (destra) su questo fotogramma chiave. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Imposta la modalità passo della chiave. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Imposta la modalità di peso della tangente della chiave. |
| [setTension(float value)](#setTension-float-) | Imposta la tensione usata nella spline TCB |
| [setTime(double value)](#setTime-double-) | Imposta la posizione temporale del fotogramma chiave list.data[index], misurata in secondi. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Imposta che la tangente sia indipendente dal tempo |
| [setValue(float value)](#setValue-float-) | Imposta il valore del fotogramma chiave. |
| [toString()](#toString--) | Ottiene la rappresentazione stringa del fotogramma chiave |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Crea un nuovo key frame sulla curva specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | La curva su cui verrà creato il fotogramma chiave |
| tempo | double | La posizione temporale del fotogramma chiave |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


Restituisce il bias usato nella TCB spline

**Returns:**
float - il bias usato nella spline TCB
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


Restituisce la continuità usata nella TCB spline

**Returns:**
float - la continuità usata nella spline TCB
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Ottieni o imposta se il fotogramma chiave è piatto. Il fotogramma chiave dovrebbe essere piatto se il fotogramma chiave successivo o precedente ha lo stesso valore. Un fotogramma chiave piatto ha tangenti piatte e interpolazione fissa.

**Returns:**
boolean - Ottieni o imposta se il fotogramma chiave è piatto. Il fotogramma chiave dovrebbe essere piatto se il fotogramma chiave successivo o precedente ha lo stesso valore. Un fotogramma chiave piatto ha tangenti piatte e interpolazione fissa.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Restituisce che le tangenti out e next in sono indipendenti.

**Returns:**
boolean - le tangenti di uscita e la successiva di ingresso sono indipendenti.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Restituisce il tipo di interpolazione del key, list.data[index] definisce l'algoritmo con cui il valore campionato è calcolato.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Restituisce la tangente in (sinistra) successiva su questo key frame.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Restituisce il peso in (sinistra) successivo su questo key frame.

**Returns:**
float - il peso di ingresso (sinistra) successivo su questo fotogramma chiave.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Restituisce la tangente out (destra) su questo key frame.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Restituisce il peso out (destra) su questo key frame.

**Returns:**
float - il peso di uscita (destra) su questo fotogramma chiave.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Ottiene la modalità passo della chiave. Se il tipo di interpolazione è [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decide quale valore del fotogramma chiave verrà usato durante l'interpolazione. Un [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) indica che verrà usato il valore del fotogramma chiave sinistro. Un [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) indica che verrà usato il valore del fotogramma chiave destro successivo

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Ottiene la modalità di peso della tangente della chiave. La tangente di uscita o la tangente di ingresso successiva possono essere personalizzate selezionando il corretto [WeightedMode](../../com.aspose.threed/weightedmode)

**Returns:**
int - la modalità di peso della tangente della chiave. La tangente di uscita o la tangente di ingresso successiva possono essere personalizzate selezionando il corretto [WeightedMode](../../com.aspose.threed/weightedmode)
### getTension() {#getTension--}
```
public float getTension()
```


Restituisce la tensione usata nella TCB spline

**Returns:**
float - tension used in TCB spline
### getTime() {#getTime--}
```
public double getTime()
```


Restituisce la posizione temporale del key frame list.data[index], misurata in secondi.

**Returns:**
double - the time position of list.data[index] key frame, measured in seconds.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Restituisce che la tangente è indipendente dal tempo

**Returns:**
boolean - the tangent is time-independent
### getValue() {#getValue--}
```
public float getValue()
```


Restituisce il valore del key-frame.

**Returns:**
float - the key-frame's value.
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


Imposta il bias usato nella TCB spline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


Imposta la continuità usata nella TCB spline

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Ottieni o imposta se il fotogramma chiave è piatto. Il fotogramma chiave dovrebbe essere piatto se il fotogramma chiave successivo o precedente ha lo stesso valore. Un fotogramma chiave piatto ha tangenti piatte e interpolazione fissa.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Imposta che le tangenti di uscita e la successiva di ingresso siano indipendenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Imposta il tipo di interpolazione della chiave, list.data[index] definisce l'algoritmo con cui viene calcolato il valore campionato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Nuovo valore |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Imposta la tangente di ingresso (sinistra) successiva su questo fotogramma chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Imposta il peso di ingresso (sinistra) successivo su questo fotogramma chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Imposta la tangente di uscita (destra) su questo fotogramma chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nuovo valore |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Imposta il peso di uscita (destra) su questo fotogramma chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Sets the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Nuovo valore |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Sets the key's tangent weight mode. The out tangent or the next in tangent can be customized by select correct [WeightedMode](../../com.aspose.threed/weightedmode)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Imposta la tensione usata nella spline TCB

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


Imposta la posizione temporale del fotogramma chiave list.data[index], misurata in secondi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Imposta che la tangente sia indipendente dal tempo

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Imposta il valore del fotogramma chiave.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### toString() {#toString--}
```
public String toString()
```


Ottiene la rappresentazione stringa del fotogramma chiave

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

