---
title: KeyFrame
second_title: Aspose.3D für Node.js via Java API-Referenz
description: 
type: docs

url: /de/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Ein Schlüsselbild wird hauptsächlich durch eine Zeit und einen Wert definiert; bei einigen Interpolationstypen werden Tangente/Spannung/Bias/Kontinuität ebenfalls zur Berechnung des endgültigen abgetasteten Wertes verwendet. Abgetastete Werte an einer Zeitposition, die kein Schlüsselbild ist, werden durch Schlüsselbilder zwischen dem vorherigen und dem nächsten Schlüsselbild interpoliert. Werte vor/nach dem ersten/letzten Schlüsselbild werden von der Extrapolation-Klasse berechnet.


## Methoden

### constructor{#constructor}

| Name | Beschreibung |
| --- | --- |
| constructor(curve, time) | Erstelle ein neues Schlüsselbild auf der angegebenen Kurve |

 **Parameters:**

| Name | Typ | Beschreibung |
| --- | --- | --- |
| curve | KeyframeSequence | Die Kurve, auf der das Schlüsselbild erstellt wird. |
| Zeit | Number | Die Zeitposition des Schlüsselbilds. |

 **Result:**



---


### getTime{#getTime}

| Name | Beschreibung |
| --- | --- |
| getTime() | Liest oder setzt die Zeitposition des Schlüsselbilds list.data[index], gemessen in Sekunden. Die Zeit. |

 **Result:**



---


### setTime{#setTime}

| Name | Beschreibung |
| --- | --- |
| setTime(value) | Liest oder setzt die Zeitposition des Schlüsselbilds list.data[index], gemessen in Sekunden. Die Zeit. |

 **Result:**



---


### getValue{#getValue}

| Name | Beschreibung |
| --- | --- |
| getValue() | Liest oder setzt den Wert des Schlüsselbilds. Der Wert. |

 **Result:**



---


### setValue{#setValue}

| Name | Beschreibung |
| --- | --- |
| setValue(value) | Liest oder setzt den Wert des Schlüsselbilds. Der Wert. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Name | Beschreibung |
| --- | --- |
| getInterpolation() | Liest oder setzt den Interpolationstyp des Schlüssels, list.data[index] definiert den Algorithmus, wie der abgetastete Wert berechnet wird. Der Wert der Eigenschaft ist die ganzzahlige Konstante Interpolation. Die Interpolation. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Name | Beschreibung |
| --- | --- |
| setInterpolation(value) | Liest oder setzt den Interpolationstyp des Schlüssels, list.data[index] definiert den Algorithmus, wie der abgetastete Wert berechnet wird. Der Wert der Eigenschaft ist die ganzzahlige Konstante Interpolation. Die Interpolation. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Name | Beschreibung |
| --- | --- |
| getTangentWeightMode() | Liest oder setzt den Tangentialgewichtmodus des Schlüssels. Der Ausgangstangente oder die nächste Eingangs‑Tangente kann durch Auswahl des richtigen WeightedMode angepasst werden. Der Wert der Eigenschaft ist die ganzzahlige Konstante WeightedMode. Der Tangentialgewichtmodus. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Name | Beschreibung |
| --- | --- |
| setTangentWeightMode(value) | Liest oder setzt den Tangentialgewichtmodus des Schlüssels. Der Ausgangstangente oder die nächste Eingangs‑Tangente kann durch Auswahl des richtigen WeightedMode angepasst werden. Der Wert der Eigenschaft ist die ganzzahlige Konstante WeightedMode. Der Tangentialgewichtmodus. |

 **Result:**



---


### getStepMode{#getStepMode}

| Name | Beschreibung |
| --- | --- |
| getStepMode() | Liest oder setzt den Schrittmodus des Schlüssels. Wenn der Interpolationstyp Interpolation.CONSTANT ist, entscheidet list.data[index], welcher Schlüsselbildwert während der Interpolation verwendet wird. Ein StepMode.PREVIOUS_VALUE bedeutet, dass der Wert des linken Schlüsselbildes verwendet wird. Ein StepMode.NEXT_VALUE bedeutet, dass der Wert des nächsten rechten Schlüsselbildes verwendet wird. Der Wert der Eigenschaft ist die ganzzahlige Konstante StepMode. Der Schrittmodus. |

 **Result:**



---


### setStepMode{#setStepMode}

| Name | Beschreibung |
| --- | --- |
| setStepMode(value) | Liest oder setzt den Schrittmodus des Schlüssels. Wenn der Interpolationstyp Interpolation.CONSTANT ist, entscheidet list.data[index], welcher Schlüsselbildwert während der Interpolation verwendet wird. Ein StepMode.PREVIOUS_VALUE bedeutet, dass der Wert des linken Schlüsselbildes verwendet wird. Ein StepMode.NEXT_VALUE bedeutet, dass der Wert des nächsten rechten Schlüsselbildes verwendet wird. Der Wert der Eigenschaft ist die ganzzahlige Konstante StepMode. Der Schrittmodus. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Name | Beschreibung |
| --- | --- |
| getNextInTangent() | Liest oder setzt die nächste Eingangs‑Tangente (links) dieses Schlüsselbildes. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Name | Beschreibung |
| --- | --- |
| setNextInTangent(value) | Liest oder setzt die nächste Eingangs‑Tangente (links) dieses Schlüsselbildes. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Name | Beschreibung |
| --- | --- |
| getOutTangent() | Liest oder setzt die Ausgangs‑Tangente (rechts) dieses Schlüsselbildes. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Name | Beschreibung |
| --- | --- |
| setOutTangent(value) | Liest oder setzt die Ausgangs‑Tangente (rechts) dieses Schlüsselbildes. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Name | Beschreibung |
| --- | --- |
| getOutWeight() | Liest oder setzt das Ausgangs‑Gewicht (rechts) dieses Schlüsselbildes. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Name | Beschreibung |
| --- | --- |
| setOutWeight(value) | Liest oder setzt das Ausgangs‑Gewicht (rechts) dieses Schlüsselbildes. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Name | Beschreibung |
| --- | --- |
| getNextInWeight() | Liest oder setzt das nächste Eingangs‑Gewicht (links) dieses Schlüsselbildes. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Name | Beschreibung |
| --- | --- |
| setNextInWeight(value) | Liest oder setzt das nächste Eingangs‑Gewicht (links) dieses Schlüsselbildes. |

 **Result:**



---


### getTension{#getTension}

| Name | Beschreibung |
| --- | --- |
| getTension() | Liest oder setzt die Spannung, die im TCB‑Spline verwendet wird |

 **Result:**



---


### setTension{#setTension}

| Name | Beschreibung |
| --- | --- |
| setTension(value) | Liest oder setzt die Spannung, die im TCB‑Spline verwendet wird |

 **Result:**



---


### getContinuity{#getContinuity}

| Name | Beschreibung |
| --- | --- |
| getContinuity() | Liest oder setzt die Kontinuität, die im TCB‑Spline verwendet wird |

 **Result:**



---


### setContinuity{#setContinuity}

| Name | Beschreibung |
| --- | --- |
| setContinuity(value) | Liest oder setzt die Kontinuität, die im TCB‑Spline verwendet wird |

 **Result:**



---


### getBias{#getBias}

| Name | Beschreibung |
| --- | --- |
| getBias() | Liest oder setzt den Bias, der in TCB-Splines verwendet wird |

 **Result:**



---


### setBias{#setBias}

| Name | Beschreibung |
| --- | --- |
| setBias(value) | Liest oder setzt den Bias, der in TCB-Splines verwendet wird |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Name | Beschreibung |
| --- | --- |
| getIndependentTangent() | Liest oder setzt, dass die Ausgangs- und nächsten Eingabetangenten unabhängig sind. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Name | Beschreibung |
| --- | --- |
| setIndependentTangent(value) | Liest oder setzt, dass die Ausgangs- und nächsten Eingabetangenten unabhängig sind. |

 **Result:**



---


### getFlat{#getFlat}

| Name | Beschreibung |
| --- | --- |
| getFlat() | Abrufen oder Festlegen, ob das Schlüsselbild flach ist. Das Schlüsselbild sollte flach sein, wenn das nächste oder vorherige Schlüsselbild denselben Wert hat. Ein flaches Schlüsselbild hat flache Tangenten und feste Interpolation. |

 **Result:**



---


### setFlat{#setFlat}

| Name | Beschreibung |
| --- | --- |
| setFlat(value) | Abrufen oder Festlegen, ob das Schlüsselbild flach ist. Das Schlüsselbild sollte flach sein, wenn das nächste oder vorherige Schlüsselbild denselben Wert hat. Ein flaches Schlüsselbild hat flache Tangenten und feste Interpolation. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Name | Beschreibung |
| --- | --- |
| getTimeIndependentTangent() | Liest oder setzt, dass die Tangente zeitunabhängig ist. |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Name | Beschreibung |
| --- | --- |
| setTimeIndependentTangent(value) | Liest oder setzt, dass die Tangente zeitunabhängig ist. |

 **Result:**



---


### toString{#toString}

| Name | Beschreibung |
| --- | --- |
| toString() | Liefert die Zeichenkettenrepräsentation des Schlüsselbilds. |

 **Result:**
String


---



