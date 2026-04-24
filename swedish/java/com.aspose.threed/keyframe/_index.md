---
title: KeyFrame
second_title: Aspose.3D for Java API-referens
description: En nyckelram definieras huvudsakligen av en tid och ett värde för vissa interpolations typer tangent/tension/bias/continuity används också vid beräkning av det slutliga samplade värdet.
type: docs
weight: 89
url: /sv/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

En nyckelram definieras huvudsakligen av en tid och ett värde; för vissa interpolations typer används tangent/tension/bias/continuity också vid beräkning av det slutliga samplade värdet. Samplade värden i en icke-nyckelram tidsposition interpoleras av nyckelramar mellan föregående och nästa nyckelram. Värdet före/efter den första/sista nyckelramen beräknas av klassen [Extrapolation](../../com.aspose.threed/extrapolation).
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Skapa en ny nyckelram på angiven kurva |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | Hämtar bias som används i TCB-spline |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | Hämtar kontinuitet som används i TCB-spline |
| [getFlat()](#getFlat--) | Hämta eller ange om nyckelramen är platt. |
| [getIndependentTangent()](#getIndependentTangent--) | Hämtar om ut- och nästa in-tangenter är oberoende. |
| [getInterpolation()](#getInterpolation--) | Hämtar nyckelns interpolationstyp, list.data[index] definierar algoritmen för hur det samplade värdet beräknas. |
| [getNextInTangent()](#getNextInTangent--) | Hämtar nästa in (vänster) tangent på denna nyckelram. |
| [getNextInWeight()](#getNextInWeight--) | Hämtar nästa in (vänster) vikt på denna nyckelram. |
| [getOutTangent()](#getOutTangent--) | Hämtar ut (höger) tangent på denna nyckelram. |
| [getOutWeight()](#getOutWeight--) | Hämtar ut (höger) vikt på denna nyckelram. |
| [getStepMode()](#getStepMode--) | Hämtar nyckelns stegläge. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Hämtar nyckelns tangentviktläge. |
| [getTension()](#getTension--) | Hämtar spänning som används i TCB-spline |
| [getTime()](#getTime--) | Hämtar tidspositionen för list.data[index] nyckelram, mätt i sekunder. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Hämtar att tangenten är tidsoberoende |
| [getValue()](#getValue--) | Hämtar nyckelramens värde. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | Ställer in bias som används i TCB-spline |
| [setContinuity(float value)](#setContinuity-float-) | Ställer in kontinuitet som används i TCB-spline |
| [setFlat(boolean value)](#setFlat-boolean-) | Hämta eller ange om nyckelramen är platt. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Ställer in att de utgående och nästa in-tangenter är oberoende. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Ställer in nyckelns interpoleringstyp, list.data[index] definierar algoritmen för hur det samplade värdet beräknas. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Ställer in nästa in (vänster) tangent på detta nyckelbild. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Ställer in nästa in (vänster) vikt på detta nyckelbild. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Ställer in den utgående (höger) tangenten på detta nyckelbild. |
| [setOutWeight(float value)](#setOutWeight-float-) | Ställer in den utgående (höger) vikten på detta nyckelbild. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Ställer in nyckelns stegläge. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Ställer in nyckelns tangentviktläge. |
| [setTension(float value)](#setTension-float-) | Ställer in spänning som används i TCB-spline. |
| [setTime(double value)](#setTime-double-) | Ställer in tidspositionen för list.data[index] nyckelbild, mätt i sekunder. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Ställer in att tangenten är tidsoberoende. |
| [setValue(float value)](#setValue-float-) | Ställer in nyckelbildens värde. |
| [toString()](#toString--) | Hämtar strängrepresentationen av nyckelbilden. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Skapa en ny nyckelram på angiven kurva

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | Kurvan som nyckelbilden kommer att skapas på. |
| tid | double | Tidspositionen för nyckelbilden. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


Hämtar bias som används i TCB-spline

**Returns:**
float – bias som används i TCB-spline.
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


Hämtar kontinuitet som används i TCB-spline

**Returns:**
float – kontinuitet som används i TCB-spline.
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Hämta eller ange om nyckelbilden är platt. Nyckelbilden bör vara platt om nästa eller föregående nyckelbild har samma värde. En platt nyckelbild har platta tangenter och fast interpolering.

**Returns:**
boolean – Hämta eller ange om nyckelbilden är platt. Nyckelbilden bör vara platt om nästa eller föregående nyckelbild har samma värde. En platt nyckelbild har platta tangenter och fast interpolering.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Hämtar om ut- och nästa in-tangenter är oberoende.

**Returns:**
boolean – de utgående och nästa in-tangenterna är oberoende.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Hämtar nyckelns interpolationstyp, list.data[index] definierar algoritmen för hur det samplade värdet beräknas.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Hämtar nästa in (vänster) tangent på denna nyckelram.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Hämtar nästa in (vänster) vikt på denna nyckelram.

**Returns:**
float – nästa in (vänster) vikt på detta nyckelbild.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Hämtar ut (höger) tangent på denna nyckelram.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Hämtar ut (höger) vikt på denna nyckelram.

**Returns:**
float – den utgående (höger) vikten på detta nyckelbild.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Hämtar nyckelns stegläge. Om interpoleringstypen är [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), bestämmer list.data[index] vilket nyckelbildsvärde som kommer att användas under interpolering. En [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) betyder att det vänstra nyckelbildsvärdet kommer att användas. En [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) betyder att nästa högra nyckelbildsvärde kommer att användas.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Hämtar nyckelns tangentviktläge. Den utgående tangenten eller nästa in-tangent kan anpassas genom att välja rätt [WeightedMode](../../com.aspose.threed/weightedmode).

**Returns:**
int – nyckelns tangentviktläge. Den utgående tangenten eller nästa in-tangent kan anpassas genom att välja rätt [WeightedMode](../../com.aspose.threed/weightedmode).
### getTension() {#getTension--}
```
public float getTension()
```


Hämtar spänning som används i TCB-spline

**Returns:**
float - spänning som används i TCB-spline
### getTime() {#getTime--}
```
public double getTime()
```


Hämtar tidspositionen för list.data[index] nyckelram, mätt i sekunder.

**Returns:**
double - tidspositionen för list.data[index] nyckelram, mätt i sekunder.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Hämtar att tangenten är tidsoberoende

**Returns:**
boolean - tangenten är tidsoberoende
### getValue() {#getValue--}
```
public float getValue()
```


Hämtar nyckelramens värde.

**Returns:**
float - nyckelramens värde.
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


Ställer in bias som används i TCB-spline

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


Ställer in kontinuitet som används i TCB-spline

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Hämta eller ange om nyckelbilden är platt. Nyckelbilden bör vara platt om nästa eller föregående nyckelbild har samma värde. En platt nyckelbild har platta tangenter och fast interpolering.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Ställer in att de utgående och nästa in-tangenter är oberoende.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Ställer in nyckelns interpoleringstyp, list.data[index] definierar algoritmen för hur det samplade värdet beräknas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Nytt värde |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Ställer in nästa in (vänster) tangent på detta nyckelbild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Ställer in nästa in (vänster) vikt på detta nyckelbild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Ställer in den utgående (höger) tangenten på detta nyckelbild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nytt värde |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Ställer in den utgående (höger) vikten på detta nyckelbild.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Sätter nyckelns stegläge. Om interpoleringstypen är [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), bestämmer list.data[index] vilket nyckelramvärde som ska användas under interpolering. En [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) betyder att vänstra nyckelramens värde kommer att användas. En [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) betyder att nästa högra nyckelramens värde kommer att användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Nytt värde |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Ställer in nyckelns tangentviktläge. Utgående tangent eller nästa ingående tangent kan anpassas genom att välja rätt [WeightedMode](../../com.aspose.threed/weightedmode)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Ställer in spänning som används i TCB-spline.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


Ställer in tidspositionen för list.data[index] nyckelbild, mätt i sekunder.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Ställer in att tangenten är tidsoberoende.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Ställer in nyckelbildens värde.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### toString() {#toString--}
```
public String toString()
```


Hämtar strängrepresentationen av nyckelbilden.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

