---
title: "KeyFrame"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

En nyckelram definieras huvudsakligen av en tid och ett värde, för vissa interpoleringstyper används även tangent/spänning/bias/kontinuitet vid beräkning av det slutliga samplade värdet.  Samplade värden i en tidpunkt utan nyckelram interpoleras av nyckelramar mellan föregående och nästa nyckelram.  Värden före/efter den första/sista nyckelramen beräknas av klassen Extrapolation.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor(curve, time) | Skapa en ny nyckelram på angiven kurva |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| curve | KeyframeSequence | Kurvan som nyckelbilden kommer att skapas på |
| tid | Nummer | Tidspositionen för nyckelbilden |

 **Result:**



---


### getTime{#getTime}

| Namn | Beskrivning |
| --- | --- |
| getTime() | Hämtar eller anger tidspositionen för list.data[index] nyckelbild, mätt i sekunder. Tiden. |

 **Result:**



---


### setTime{#setTime}

| Namn | Beskrivning |
| --- | --- |
| setTime(value) | Hämtar eller anger tidspositionen för list.data[index] nyckelbild, mätt i sekunder. Tiden. |

 **Result:**



---


### getValue{#getValue}

| Namn | Beskrivning |
| --- | --- |
| getValue() | Hämtar eller anger nyckelbildens värde. Värdet. |

 **Result:**



---


### setValue{#setValue}

| Namn | Beskrivning |
| --- | --- |
| setValue(value) | Hämtar eller anger nyckelbildens värde. Värdet. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Namn | Beskrivning |
| --- | --- |
| getInterpolation() | Hämtar eller anger nyckelns interpoleringstyp, list.data[index] definierar algoritmen för hur det samplade värdet beräknas. Värdet på egenskapen är Interpolation heltalskonstant.Interpoleringen. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Namn | Beskrivning |
| --- | --- |
| setInterpolation(value) | Hämtar eller anger nyckelns interpoleringstyp, list.data[index] definierar algoritmen för hur det samplade värdet beräknas. Värdet på egenskapen är Interpolation heltalskonstant.Interpoleringen. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Namn | Beskrivning |
| --- | --- |
| getTangentWeightMode() | Hämtar eller anger nyckelns tangentviktläge. Den utgående tangenten eller nästa ingående tangent kan anpassas genom att välja rätt WeightedModeVärdet på egenskapen är WeightedMode heltalskonstant.Tangentviktläget. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Namn | Beskrivning |
| --- | --- |
| setTangentWeightMode(value) | Hämtar eller anger nyckelns tangentviktläge. Den utgående tangenten eller nästa ingående tangent kan anpassas genom att välja rätt WeightedModeVärdet på egenskapen är WeightedMode heltalskonstant.Tangentviktläget. |

 **Result:**



---


### getStepMode{#getStepMode}

| Namn | Beskrivning |
| --- | --- |
| getStepMode() | Hämtar eller anger nyckelns stegläge. Om interpoleringstypen är Interpolation.CONSTANT, bestämmer list.data[index] vilket nyckelbildsvärde som ska användas under interpolering. Ett StepMode.PREVIOUS_VALUE betyder att det vänstra nyckelbildsvärdet kommer att användas Ett StepMode.NEXT_VALUE betyder att nästa högra nyckelbildsvärde kommer att användas Värdet på egenskapen är StepMode heltalskonstant.Stegläget. |

 **Result:**



---


### setStepMode{#setStepMode}

| Namn | Beskrivning |
| --- | --- |
| setStepMode(value) | Hämtar eller anger nyckelns stegläge. Om interpoleringstypen är Interpolation.CONSTANT, bestämmer list.data[index] vilket nyckelbildsvärde som ska användas under interpolering. Ett StepMode.PREVIOUS_VALUE betyder att det vänstra nyckelbildsvärdet kommer att användas Ett StepMode.NEXT_VALUE betyder att nästa högra nyckelbildsvärde kommer att användas Värdet på egenskapen är StepMode heltalskonstant.Stegläget. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Namn | Beskrivning |
| --- | --- |
| getNextInTangent() | Hämtar eller anger nästa ingående (vänstra) tangent på denna nyckelbild. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Namn | Beskrivning |
| --- | --- |
| setNextInTangent(value) | Hämtar eller anger nästa ingående (vänstra) tangent på denna nyckelbild. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Namn | Beskrivning |
| --- | --- |
| getOutTangent() | Hämtar eller anger den utgående (högra) tangenten på denna nyckelbild. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Namn | Beskrivning |
| --- | --- |
| setOutTangent(value) | Hämtar eller anger den utgående (högra) tangenten på denna nyckelbild. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Namn | Beskrivning |
| --- | --- |
| getOutWeight() | Hämtar eller anger den utgående (högra) vikten på denna nyckelbild. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Namn | Beskrivning |
| --- | --- |
| setOutWeight(value) | Hämtar eller anger den utgående (högra) vikten på denna nyckelbild. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Namn | Beskrivning |
| --- | --- |
| getNextInWeight() | Hämtar eller anger nästa in(left) vikt på detta nyckelbild. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Namn | Beskrivning |
| --- | --- |
| setNextInWeight(value) | Hämtar eller anger nästa in(left) vikt på detta nyckelbild. |

 **Result:**



---


### getTension{#getTension}

| Namn | Beskrivning |
| --- | --- |
| getTension() | Hämtar eller anger spänning som används i TCB-spline |

 **Result:**



---


### setTension{#setTension}

| Namn | Beskrivning |
| --- | --- |
| setTension(value) | Hämtar eller anger spänning som används i TCB-spline |

 **Result:**



---


### getContinuity{#getContinuity}

| Namn | Beskrivning |
| --- | --- |
| getContinuity() | Hämtar eller anger kontinuiteten som används i TCB-spline |

 **Result:**



---


### setContinuity{#setContinuity}

| Namn | Beskrivning |
| --- | --- |
| setContinuity(value) | Hämtar eller anger kontinuiteten som används i TCB-spline |

 **Result:**



---


### getBias{#getBias}

| Namn | Beskrivning |
| --- | --- |
| getBias() | Hämtar eller anger bias som används i TCB-spline |

 **Result:**



---


### setBias{#setBias}

| Namn | Beskrivning |
| --- | --- |
| setBias(value) | Hämtar eller anger bias som används i TCB-spline |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Namn | Beskrivning |
| --- | --- |
| getIndependentTangent() | Hämtar eller anger att ut- och nästa in-tangenter är oberoende. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Namn | Beskrivning |
| --- | --- |
| setIndependentTangent(value) | Hämtar eller anger att ut- och nästa in-tangenter är oberoende. |

 **Result:**



---


### getFlat{#getFlat}

| Namn | Beskrivning |
| --- | --- |
| getFlat() | Hämta eller ange om nyckelbilden är platt. Nyckelbilden bör vara platt om nästa eller föregående nyckelbild har samma värde. En platt nyckelbild har platta tangenter och fast interpolation. |

 **Result:**



---


### setFlat{#setFlat}

| Namn | Beskrivning |
| --- | --- |
| setFlat(value) | Hämta eller ange om nyckelbilden är platt. Nyckelbilden bör vara platt om nästa eller föregående nyckelbild har samma värde. En platt nyckelbild har platta tangenter och fast interpolation. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Namn | Beskrivning |
| --- | --- |
| getTimeIndependentTangent() | Hämtar eller anger att tangenten är tidsoberoende |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Namn | Beskrivning |
| --- | --- |
| setTimeIndependentTangent(value) | Hämtar eller anger att tangenten är tidsoberoende |

 **Result:**



---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Hämtar strängrepresentationen av nyckelbilden |

 **Result:**
Sträng


---



