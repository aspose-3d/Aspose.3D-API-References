---
title: KeyFrame
second_title: Aspose.3D for Java API-referentie
description: Een keyframe wordt voornamelijk gedefinieerd door een tijd en een waarde; voor sommige interpolatietypen worden tangent/tension/bias/continuity ook gebruikt bij het berekenen van de uiteindelijke bemonsterde waarde.
type: docs
weight: 89
url: /nl/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Een keyframe wordt voornamelijk gedefinieerd door een tijd en een waarde; voor sommige interpolatietypen worden tangent/tension/bias/continuity ook gebruikt bij het berekenen van de uiteindelijke bemonsterde waarde. Bemonsterde waarden op een tijdstip zonder keyframe worden geïnterpoleerd door keyframes tussen de vorige en volgende keyframes. De waarde vóór/na de eerste/laatste keyframe wordt berekend door de [Extrapolation](../../com.aspose.threed/extrapolation) klasse.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Maak een nieuw keyframe op de opgegeven curve. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | Haalt de bias op die wordt gebruikt in de TCB-spline. |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | Haalt de continuïteit op die wordt gebruikt in de TCB-spline. |
| [getFlat()](#getFlat--) | Haal op of stel in of het keyframe vlak is. |
| [getIndependentTangent()](#getIndependentTangent--) | Haalt op dat de uit- en volgende in-tangenten onafhankelijk zijn. |
| [getInterpolation()](#getInterpolation--) | Haalt het interpolatietype van de key op; list.data[index] definieert het algoritme waarmee de bemonsterde waarde wordt berekend. |
| [getNextInTangent()](#getNextInTangent--) | Haalt de volgende in (linker) tangent op van dit keyframe. |
| [getNextInWeight()](#getNextInWeight--) | Haalt het volgende in (linker) gewicht op van dit keyframe. |
| [getOutTangent()](#getOutTangent--) | Haalt de uit (rechter) tangent op van dit keyframe. |
| [getOutWeight()](#getOutWeight--) | Haalt het uit (rechter) gewicht op van dit keyframe. |
| [getStepMode()](#getStepMode--) | Haalt de stapmodus van de key op. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Haalt de tangentsgewichtsmodus van de key op. |
| [getTension()](#getTension--) | Haalt de spanning op die wordt gebruikt in de TCB-spline. |
| [getTime()](#getTime--) | Haalt de tijdspositie op van het list.data[index] keyframe, gemeten in seconden. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Haalt op dat de tangent tijdsonafhankelijk is. |
| [getValue()](#getValue--) | Haalt de waarde van het keyframe op. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | Stelt de bias in die wordt gebruikt in de TCB-spline. |
| [setContinuity(float value)](#setContinuity-float-) | Stelt de continuïteit in die wordt gebruikt in de TCB-spline. |
| [setFlat(boolean value)](#setFlat-boolean-) | Haal op of stel in of het keyframe vlak is. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Stelt in dat de uit- en volgende in-tangenten onafhankelijk zijn. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Stelt het interpolatietype van de sleutel in, list.data[index] definieert het algoritme hoe de bemonsterde waarde wordt berekend. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Stelt de volgende in (linker) tangent in op dit keyframe. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Stelt het volgende in (linker) gewicht in op dit keyframe. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Stelt de uit (rechter) tangent in op dit keyframe. |
| [setOutWeight(float value)](#setOutWeight-float-) | Stelt het uit (rechter) gewicht in op dit keyframe. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Stelt de stapmodus van de sleutel in. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Stelt de tangent-gewichtsmodus van de sleutel in. |
| [setTension(float value)](#setTension-float-) | Stelt de spanning in die wordt gebruikt in TCB-spline. |
| [setTime(double value)](#setTime-double-) | Stelt de tijdspositie van het list.data[index] keyframe in, gemeten in seconden. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Stelt in dat de tangent tijdsonafhankelijk is. |
| [setValue(float value)](#setValue-float-) | Stelt de waarde van het keyframe in. |
| [toString()](#toString--) | Haalt de tekenreeksrepresentatie van het keyframe op. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Maak een nieuw keyframe op de opgegeven curve.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | De curve waarop het keyframe wordt aangemaakt. |
| tijd | double | De tijdspositie van het keyframe. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


Haalt de bias op die wordt gebruikt in de TCB-spline.

**Returns:**
float - de bias die wordt gebruikt in TCB-spline.
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


Haalt de continuïteit op die wordt gebruikt in de TCB-spline.

**Returns:**
float - de continuïteit die wordt gebruikt in TCB-spline.
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Haal op of stel in of het keyframe vlak is. Een keyframe moet vlak zijn als het volgende of vorige keyframe dezelfde waarde heeft. Een vlak keyframe heeft vlakke tangenten en vaste interpolatie.

**Returns:**
boolean - Haal op of stel in of het keyframe vlak is. Een keyframe moet vlak zijn als het volgende of vorige keyframe dezelfde waarde heeft. Een vlak keyframe heeft vlakke tangenten en vaste interpolatie.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Haalt op dat de uit- en volgende in-tangenten onafhankelijk zijn.

**Returns:**
boolean - de uit- en volgende in-tangenten zijn onafhankelijk.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Haalt het interpolatietype van de key op; list.data[index] definieert het algoritme waarmee de bemonsterde waarde wordt berekend.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Haalt de volgende in (linker) tangent op van dit keyframe.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Haalt het volgende in (linker) gewicht op van dit keyframe.

**Returns:**
float - het volgende in (linker) gewicht op dit keyframe.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Haalt de uit (rechter) tangent op van dit keyframe.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Haalt het uit (rechter) gewicht op van dit keyframe.

**Returns:**
float - het uit (rechter) gewicht op dit keyframe.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Haalt de stapmodus van de sleutel op. Als het interpolatietype [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) is, bepaalt list.data[index] welke keyframe-waarde tijdens interpolatie wordt gebruikt. Een [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) betekent dat de waarde van het linker keyframe wordt gebruikt. Een [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) betekent dat de waarde van het volgende rechter keyframe wordt gebruikt.

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Haalt de tangent-gewichtsmodus van de sleutel op. De uit-tangent of de volgende in-tangent kan worden aangepast door de juiste [WeightedMode](../../com.aspose.threed/weightedmode) te selecteren.

**Returns:**
int - de tangent-gewichtsmodus van de sleutel. De uit-tangent of de volgende in-tangent kan worden aangepast door de juiste [WeightedMode](../../com.aspose.threed/weightedmode) te selecteren.
### getTension() {#getTension--}
```
public float getTension()
```


Haalt de spanning op die wordt gebruikt in de TCB-spline.

**Returns:**
float - spanning gebruikt in TCB spline
### getTime() {#getTime--}
```
public double getTime()
```


Haalt de tijdspositie op van het list.data[index] keyframe, gemeten in seconden.

**Returns:**
double - de tijdpositie van list.data[index] key frame, gemeten in seconden.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Haalt op dat de tangent tijdsonafhankelijk is.

**Returns:**
boolean - de tangent is tijdsonafhankelijk
### getValue() {#getValue--}
```
public float getValue()
```


Haalt de waarde van het keyframe op.

**Returns:**
float - de waarde van het key-frame.
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


Stelt de bias in die wordt gebruikt in de TCB-spline.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


Stelt de continuïteit in die wordt gebruikt in de TCB-spline.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Haal op of stel in of het keyframe vlak is. Een keyframe moet vlak zijn als het volgende of vorige keyframe dezelfde waarde heeft. Een vlak keyframe heeft vlakke tangenten en vaste interpolatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Stelt in dat de uit- en volgende in-tangenten onafhankelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Stelt het interpolatietype van de sleutel in, list.data[index] definieert het algoritme hoe de bemonsterde waarde wordt berekend.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Nieuwe waarde |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Stelt de volgende in (linker) tangent in op dit keyframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Stelt het volgende in (linker) gewicht in op dit keyframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Stelt de uit (rechter) tangent in op dit keyframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nieuwe waarde |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Stelt het uit (rechter) gewicht in op dit keyframe.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Stelt de stapmodus van de key in. Als het interpolatietype [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT) is, bepaalt list.data[index] welke key-frame waarde wordt gebruikt tijdens interpolatie. Een [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) betekent dat de waarde van de linkse key-frame wordt gebruikt. Een [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) betekent dat de waarde van de volgende rechter key-frame wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Nieuwe waarde |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Stelt de tangent gewichtsmodus van de key in. De uitgaande tangent of de volgende inkomende tangent kan worden aangepast door de juiste [WeightedMode](../../com.aspose.threed/weightedmode) te selecteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Stelt de spanning in die wordt gebruikt in TCB-spline.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


Stelt de tijdspositie van het list.data[index] keyframe in, gemeten in seconden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Stelt in dat de tangent tijdsonafhankelijk is.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Stelt de waarde van het keyframe in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### toString() {#toString--}
```
public String toString()
```


Haalt de tekenreeksrepresentatie van het keyframe op.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

