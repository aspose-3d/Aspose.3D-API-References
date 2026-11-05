---
title: "KeyFrame"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Een keyframe wordt voornamelijk gedefinieerd door een tijd en een waarde; voor sommige interpolatietypen worden tangent/tension/bias/continuity ook gebruikt bij het berekenen van de uiteindelijke bemonsterde waarde.  Bemonsterde waarden op een tijdstip zonder keyframe worden geïnterpoleerd door keyframes tussen de vorige en volgende keyframes.  Waarden vóór/na het eerste/laatste keyframe worden berekend door de Extrapolation-klasse.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor(curve, time) | Maak een nieuw keyframe op de opgegeven curve |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| curve | KeyframeSequence | De curve waarop het keyframe wordt aangemaakt. |
| time | Nummer | De tijdpositie van het keyframe. |

 **Result:**



---


### getTime{#getTime}

| Naam | Beschrijving |
| --- | --- |
| getTime() | Haalt of stelt de tijdpositie van list.data[index] keyframe in, gemeten in seconden. De tijd. |

 **Result:**



---


### setTime{#setTime}

| Naam | Beschrijving |
| --- | --- |
| setTime(value) | Haalt of stelt de tijdpositie van list.data[index] keyframe in, gemeten in seconden. De tijd. |

 **Result:**



---


### getValue{#getValue}

| Naam | Beschrijving |
| --- | --- |
| getValue() | Haalt of stelt de waarde van het keyframe in. De waarde. |

 **Result:**



---


### setValue{#setValue}

| Naam | Beschrijving |
| --- | --- |
| setValue(value) | Haalt of stelt de waarde van het keyframe in. De waarde. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Naam | Beschrijving |
| --- | --- |
| getInterpolation() | Haalt of stelt het interpolatietype van de key in, list.data[index] definieert het algoritme hoe de bemonsterde waarde wordt berekend. De waarde van de eigenschap is Interpolation integer constant. De interpolatie. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Naam | Beschrijving |
| --- | --- |
| setInterpolation(value) | Haalt of stelt het interpolatietype van de key in, list.data[index] definieert het algoritme hoe de bemonsterde waarde wordt berekend. De waarde van de eigenschap is Interpolation integer constant. De interpolatie. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Naam | Beschrijving |
| --- | --- |
| getTangentWeightMode() | Haalt of stelt de tangentgewichtsmodus van de key in. De uit-tangent of de volgende in-tangent kan worden aangepast door de juiste WeightedMode te selecteren. De waarde van de eigenschap is WeightedMode integer constant. De tangentgewichtsmodus. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Naam | Beschrijving |
| --- | --- |
| setTangentWeightMode(value) | Haalt of stelt de tangentgewichtsmodus van de key in. De uit-tangent of de volgende in-tangent kan worden aangepast door de juiste WeightedMode te selecteren. De waarde van de eigenschap is WeightedMode integer constant. De tangentgewichtsmodus. |

 **Result:**



---


### getStepMode{#getStepMode}

| Naam | Beschrijving |
| --- | --- |
| getStepMode() | Haalt of stelt de stapmodus van de key in. Als het interpolatietype Interpolation.CONSTANT is, bepaalt list.data[index] welke keyframe-waarde wordt gebruikt tijdens interpolatie. Een StepMode.PREVIOUS_VALUE betekent dat de waarde van het linkse keyframe wordt gebruikt. Een StepMode.NEXT_VALUE betekent dat de waarde van het rechtse keyframe wordt gebruikt. De waarde van de eigenschap is StepMode integer constant. De stapmodus. |

 **Result:**



---


### setStepMode{#setStepMode}

| Naam | Beschrijving |
| --- | --- |
| setStepMode(value) | Haalt of stelt de stapmodus van de key in. Als het interpolatietype Interpolation.CONSTANT is, bepaalt list.data[index] welke keyframe-waarde wordt gebruikt tijdens interpolatie. Een StepMode.PREVIOUS_VALUE betekent dat de waarde van het linkse keyframe wordt gebruikt. Een StepMode.NEXT_VALUE betekent dat de waarde van het rechtse keyframe wordt gebruikt. De waarde van de eigenschap is StepMode integer constant. De stapmodus. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Naam | Beschrijving |
| --- | --- |
| getNextInTangent() | Haalt of stelt de volgende in (linker) tangent op dit keyframe in. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Naam | Beschrijving |
| --- | --- |
| setNextInTangent(value) | Haalt of stelt de volgende in (linker) tangent op dit keyframe in. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Naam | Beschrijving |
| --- | --- |
| getOutTangent() | Haalt of stelt de uit (rechter) tangent op dit keyframe in. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Naam | Beschrijving |
| --- | --- |
| setOutTangent(value) | Haalt of stelt de uit (rechter) tangent op dit keyframe in. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Naam | Beschrijving |
| --- | --- |
| getOutWeight() | Haalt op of stelt het uit (rechts) gewicht in voor dit keyframe. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Naam | Beschrijving |
| --- | --- |
| setOutWeight(value) | Haalt op of stelt het uit (rechts) gewicht in voor dit keyframe. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Naam | Beschrijving |
| --- | --- |
| getNextInWeight() | Haalt op of stelt het volgende in (links) gewicht in voor dit keyframe. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Naam | Beschrijving |
| --- | --- |
| setNextInWeight(value) | Haalt op of stelt het volgende in (links) gewicht in voor dit keyframe. |

 **Result:**



---


### getTension{#getTension}

| Naam | Beschrijving |
| --- | --- |
| getTension() | Haalt op of stelt de spanning in die wordt gebruikt in TCB-spline |

 **Result:**



---


### setTension{#setTension}

| Naam | Beschrijving |
| --- | --- |
| setTension(value) | Haalt op of stelt de spanning in die wordt gebruikt in TCB-spline |

 **Result:**



---


### getContinuity{#getContinuity}

| Naam | Beschrijving |
| --- | --- |
| getContinuity() | Haalt op of stelt de continuïteit in die wordt gebruikt in TCB-spline |

 **Result:**



---


### setContinuity{#setContinuity}

| Naam | Beschrijving |
| --- | --- |
| setContinuity(value) | Haalt op of stelt de continuïteit in die wordt gebruikt in TCB-spline |

 **Result:**



---


### getBias{#getBias}

| Naam | Beschrijving |
| --- | --- |
| getBias() | Haalt op of stelt de bias in die wordt gebruikt in TCB-spline |

 **Result:**



---


### setBias{#setBias}

| Naam | Beschrijving |
| --- | --- |
| setBias(value) | Haalt op of stelt de bias in die wordt gebruikt in TCB-spline |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Naam | Beschrijving |
| --- | --- |
| getIndependentTangent() | Haalt op of stelt in of de uit- en volgende in-tangenten onafhankelijk zijn. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Naam | Beschrijving |
| --- | --- |
| setIndependentTangent(value) | Haalt op of stelt in of de uit- en volgende in-tangenten onafhankelijk zijn. |

 **Result:**



---


### getFlat{#getFlat}

| Naam | Beschrijving |
| --- | --- |
| getFlat() | Haalt op of stelt in of het keyframe vlak is. Het keyframe moet vlak zijn als het volgende of vorige keyframe dezelfde waarde heeft. Een vlak keyframe heeft vlakke tangenten en een vaste interpolatie. |

 **Result:**



---


### setFlat{#setFlat}

| Naam | Beschrijving |
| --- | --- |
| setFlat(value) | Haalt op of stelt in of het keyframe vlak is. Het keyframe moet vlak zijn als het volgende of vorige keyframe dezelfde waarde heeft. Een vlak keyframe heeft vlakke tangenten en een vaste interpolatie. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Naam | Beschrijving |
| --- | --- |
| getTimeIndependentTangent() | Haalt op of stelt in of de tangent tijdsonafhankelijk is |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Naam | Beschrijving |
| --- | --- |
| setTimeIndependentTangent(value) | Haalt op of stelt in of de tangent tijdsonafhankelijk is |

 **Result:**



---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Haalt de tekenreeksrepresentatie van de keyframe op |

 **Result:**
String


---



