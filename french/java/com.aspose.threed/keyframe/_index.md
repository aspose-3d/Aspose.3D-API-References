---
title: "KeyFrame"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Une image-clé est principalement définie par un temps et une valeur ; pour certains types d'interpolation, tangent/tension/bias/continuity sont également utilisés lors du calcul de la valeur échantillonnée finale."
type: docs
weight: 89
url: /fr/java/com.aspose.threed/keyframe/
---

**Inheritance:**
java.lang.Object
```
public class KeyFrame
```

Une image-clé est principalement définie par un temps et une valeur ; pour certains types d'interpolation, tangent/tension/bias/continuity sont également utilisés lors du calcul de la valeur échantillonnée finale. Les valeurs échantillonnées à une position temporelle qui n'est pas une image-clé sont interpolées par les images-clés entre les images-clés précédentes et suivantes. La valeur avant/après la première/dernière image-clé est calculée par la classe [Extrapolation](../../com.aspose.threed/extrapolation).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [KeyFrame(KeyframeSequence curve, double time)](#KeyFrame-com.aspose.threed.KeyframeSequence-double-) | Créer une nouvelle image-clé sur la courbe spécifiée |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getBias()](#getBias--) | Obtient le biais utilisé dans la spline TCB |
| [getClass()](#getClass--) |  |
| [getContinuity()](#getContinuity--) | Obtient la continuité utilisée dans la spline TCB |
| [getFlat()](#getFlat--) | Obtient ou définit si l'image-clé est plate. |
| [getIndependentTangent()](#getIndependentTangent--) | Obtient que les tangentes de sortie et les suivantes d'entrée sont indépendantes. |
| [getInterpolation()](#getInterpolation--) | Obtient le type d'interpolation de la clé, list.data[index] définit l'algorithme de calcul de la valeur échantillonnée. |
| [getNextInTangent()](#getNextInTangent--) | Obtient la prochaine tangente d'entrée (gauche) sur cette image-clé. |
| [getNextInWeight()](#getNextInWeight--) | Obtient le prochain poids d'entrée (gauche) sur cette image-clé. |
| [getOutTangent()](#getOutTangent--) | Obtient la tangente de sortie (droite) sur cette image-clé. |
| [getOutWeight()](#getOutWeight--) | Obtient le poids de sortie (droite) sur cette image-clé. |
| [getStepMode()](#getStepMode--) | Obtient le mode d'étape de la clé. |
| [getTangentWeightMode()](#getTangentWeightMode--) | Obtient le mode de poids de la tangente de la clé. |
| [getTension()](#getTension--) | Obtient la tension utilisée dans la spline TCB |
| [getTime()](#getTime--) | Obtient la position temporelle de la image-clé list.data[index], mesurée en secondes. |
| [getTimeIndependentTangent()](#getTimeIndependentTangent--) | Obtient que la tangente est indépendante du temps. |
| [getValue()](#getValue--) | Obtient la valeur de l'image-clé. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setBias(float value)](#setBias-float-) | Définit le biais utilisé dans la spline TCB |
| [setContinuity(float value)](#setContinuity-float-) | Définit la continuité utilisée dans la spline TCB |
| [setFlat(boolean value)](#setFlat-boolean-) | Obtient ou définit si l'image-clé est plate. |
| [setIndependentTangent(boolean value)](#setIndependentTangent-boolean-) | Définit que les tangentes de sortie et les suivantes d'entrée sont indépendantes. |
| [setInterpolation(Interpolation value)](#setInterpolation-com.aspose.threed.Interpolation-) | Définit le type d'interpolation de la clé, list.data[index] définit l'algorithme de calcul de la valeur échantillonnée. |
| [setNextInTangent(Vector2 value)](#setNextInTangent-com.aspose.threed.Vector2-) | Définit la prochaine tangente d'entrée (gauche) sur cette image clé. |
| [setNextInWeight(float value)](#setNextInWeight-float-) | Définit le poids d'entrée suivant (gauche) sur cette image clé. |
| [setOutTangent(Vector2 value)](#setOutTangent-com.aspose.threed.Vector2-) | Définit la tangente de sortie (droite) sur cette image clé. |
| [setOutWeight(float value)](#setOutWeight-float-) | Définit le poids de sortie (droite) sur cette image clé. |
| [setStepMode(StepMode value)](#setStepMode-com.aspose.threed.StepMode-) | Définit le mode d'étape de la clé. |
| [setTangentWeightMode(int value)](#setTangentWeightMode-int-) | Définit le mode de poids de la tangente de la clé. |
| [setTension(float value)](#setTension-float-) | Définit la tension utilisée dans la spline TCB |
| [setTime(double value)](#setTime-double-) | Définit la position temporelle de l'image clé list.data[index], mesurée en secondes. |
| [setTimeIndependentTangent(boolean value)](#setTimeIndependentTangent-boolean-) | Définit que la tangente est indépendante du temps |
| [setValue(float value)](#setValue-float-) | Définit la valeur de l'image clé. |
| [toString()](#toString--) | Obtient la représentation sous forme de chaîne de caractères de l'image clé |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### KeyFrame(KeyframeSequence curve, double time) {#KeyFrame-com.aspose.threed.KeyframeSequence-double-}
```
public KeyFrame(KeyframeSequence curve, double time)
```


Créer une nouvelle image-clé sur la courbe spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| curve | [KeyframeSequence](../../com.aspose.threed/keyframesequence) | La courbe sur laquelle l'image clé sera créée |
| temps | double | La position temporelle de l'image clé |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getBias() {#getBias--}
```
public float getBias()
```


Obtient le biais utilisé dans la spline TCB

**Returns:**
float - le biais utilisé dans la spline TCB
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


Obtient la continuité utilisée dans la spline TCB

**Returns:**
float - la continuité utilisée dans la spline TCB
### getFlat() {#getFlat--}
```
public boolean getFlat()
```


Obtient ou définit si l'image clé est plate. L'image clé doit être plate si l'image clé suivante ou précédente a la même valeur. Une image clé plate a des tangentes plates et une interpolation fixe.

**Returns:**
boolean - Obtient ou définit si l'image clé est plate. L'image clé doit être plate si l'image clé suivante ou précédente a la même valeur. Une image clé plate a des tangentes plates et une interpolation fixe.
### getIndependentTangent() {#getIndependentTangent--}
```
public boolean getIndependentTangent()
```


Obtient que les tangentes de sortie et les suivantes d'entrée sont indépendantes.

**Returns:**
boolean - les tangentes de sortie et les suivantes d'entrée sont indépendantes.
### getInterpolation() {#getInterpolation--}
```
public Interpolation getInterpolation()
```


Obtient le type d'interpolation de la clé, list.data[index] définit l'algorithme de calcul de la valeur échantillonnée.

**Returns:**
[Interpolation](../../com.aspose.threed/interpolation) - the key's interpolation type, list.data[index] defines the algorithm how the sampled value is calculated.
### getNextInTangent() {#getNextInTangent--}
```
public Vector2 getNextInTangent()
```


Obtient la prochaine tangente d'entrée (gauche) sur cette image-clé.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the next in(left) tangent on this key frame.
### getNextInWeight() {#getNextInWeight--}
```
public float getNextInWeight()
```


Obtient le prochain poids d'entrée (gauche) sur cette image-clé.

**Returns:**
float - le poids d'entrée suivant (gauche) sur cette image clé.
### getOutTangent() {#getOutTangent--}
```
public Vector2 getOutTangent()
```


Obtient la tangente de sortie (droite) sur cette image-clé.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the out(right) tangent on this key frame.
### getOutWeight() {#getOutWeight--}
```
public float getOutWeight()
```


Obtient le poids de sortie (droite) sur cette image-clé.

**Returns:**
float - le poids de sortie (droite) sur cette image clé.
### getStepMode() {#getStepMode--}
```
public StepMode getStepMode()
```


Obtient le mode d'étape de la clé. Si le type d'interpolation est [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] détermine quelle valeur d'image clé sera utilisée pendant l'interpolation. Un [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) signifie que la valeur de l'image clé de gauche sera utilisée. Un [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) signifie que la valeur de l'image clé de droite suivante sera utilisée

**Returns:**
[StepMode](../../com.aspose.threed/stepmode) - the key's step mode. If the interpolation type is [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] decides which key-frame's value will be used during interpolation. A [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) means the left key-frame's value will be used A [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) means the next right key-frame's value will be used
### getTangentWeightMode() {#getTangentWeightMode--}
```
public int getTangentWeightMode()
```


Obtient le mode de poids de la tangente de la clé. La tangente de sortie ou la prochaine tangente d'entrée peut être personnalisée en sélectionnant le [WeightedMode](../../com.aspose.threed/weightedmode) correct.

**Returns:**
int - le mode de poids de la tangente de la clé. La tangente de sortie ou la prochaine tangente d'entrée peut être personnalisée en sélectionnant le [WeightedMode](../../com.aspose.threed/weightedmode) correct.
### getTension() {#getTension--}
```
public float getTension()
```


Obtient la tension utilisée dans la spline TCB

**Returns:**
float - tension utilisée dans le spline TCB
### getTime() {#getTime--}
```
public double getTime()
```


Obtient la position temporelle de la image-clé list.data[index], mesurée en secondes.

**Returns:**
double - la position temporelle de la trame clé list.data[index], mesurée en secondes.
### getTimeIndependentTangent() {#getTimeIndependentTangent--}
```
public boolean getTimeIndependentTangent()
```


Obtient que la tangente est indépendante du temps.

**Returns:**
boolean - la tangente est indépendante du temps
### getValue() {#getValue--}
```
public float getValue()
```


Obtient la valeur de l'image-clé.

**Returns:**
float - la valeur de la trame clé.
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


Définit le biais utilisé dans la spline TCB

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setContinuity(float value) {#setContinuity-float-}
```
public void setContinuity(float value)
```


Définit la continuité utilisée dans la spline TCB

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setFlat(boolean value) {#setFlat-boolean-}
```
public void setFlat(boolean value)
```


Obtient ou définit si l'image clé est plate. L'image clé doit être plate si l'image clé suivante ou précédente a la même valeur. Une image clé plate a des tangentes plates et une interpolation fixe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setIndependentTangent(boolean value) {#setIndependentTangent-boolean-}
```
public void setIndependentTangent(boolean value)
```


Définit que les tangentes de sortie et les suivantes d'entrée sont indépendantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setInterpolation(Interpolation value) {#setInterpolation-com.aspose.threed.Interpolation-}
```
public void setInterpolation(Interpolation value)
```


Définit le type d'interpolation de la clé, list.data[index] définit l'algorithme de calcul de la valeur échantillonnée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Interpolation](../../com.aspose.threed/interpolation) | Nouvelle valeur |

### setNextInTangent(Vector2 value) {#setNextInTangent-com.aspose.threed.Vector2-}
```
public void setNextInTangent(Vector2 value)
```


Définit la prochaine tangente d'entrée (gauche) sur cette image clé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

### setNextInWeight(float value) {#setNextInWeight-float-}
```
public void setNextInWeight(float value)
```


Définit le poids d'entrée suivant (gauche) sur cette image clé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setOutTangent(Vector2 value) {#setOutTangent-com.aspose.threed.Vector2-}
```
public void setOutTangent(Vector2 value)
```


Définit la tangente de sortie (droite) sur cette image clé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

### setOutWeight(float value) {#setOutWeight-float-}
```
public void setOutWeight(float value)
```


Définit le poids de sortie (droite) sur cette image clé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setStepMode(StepMode value) {#setStepMode-com.aspose.threed.StepMode-}
```
public void setStepMode(StepMode value)
```


Définit le mode d'étape de la clé. Si le type d'interpolation est [Interpolation.CONSTANT](../../com.aspose.threed/interpolation\#CONSTANT), list.data[index] détermine quelle valeur de trame clé sera utilisée pendant l'interpolation. Un [StepMode.PREVIOUS\_VALUE](../../com.aspose.threed/stepmode\#PREVIOUS-VALUE) signifie que la valeur de la trame clé de gauche sera utilisée. Un [StepMode.NEXT\_VALUE](../../com.aspose.threed/stepmode\#NEXT-VALUE) signifie que la valeur de la trame clé de droite suivante sera utilisée.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [StepMode](../../com.aspose.threed/stepmode) | Nouvelle valeur |

### setTangentWeightMode(int value) {#setTangentWeightMode-int-}
```
public void setTangentWeightMode(int value)
```


Définit le mode de poids de la tangente de la clé. La tangente de sortie ou la prochaine tangente d'entrée peut être personnalisée en sélectionnant le [WeightedMode](../../com.aspose.threed/weightedmode) correct.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setTension(float value) {#setTension-float-}
```
public void setTension(float value)
```


Définit la tension utilisée dans la spline TCB

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setTime(double value) {#setTime-double-}
```
public void setTime(double value)
```


Définit la position temporelle de l'image clé list.data[index], mesurée en secondes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setTimeIndependentTangent(boolean value) {#setTimeIndependentTangent-boolean-}
```
public void setTimeIndependentTangent(boolean value)
```


Définit que la tangente est indépendante du temps

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setValue(float value) {#setValue-float-}
```
public void setValue(float value)
```


Définit la valeur de l'image clé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### toString() {#toString--}
```
public String toString()
```


Obtient la représentation sous forme de chaîne de caractères de l'image clé

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

