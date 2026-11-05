---
title: "KeyFrame"
second_title: "Aspose.3D per Node.js via Java Riferimento API"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Un fotogramma chiave è principalmente definito da un tempo e un valore; per alcuni tipi di interpolazione, tangente/tensione/bias/continuità sono anche usati nel calcolo del valore campionato finale.  I valori campionati in una posizione temporale non appartenente a un fotogramma chiave sono interpolati dai fotogrammi chiave tra il precedente e il successivo.  Il valore prima/dopo il primo/ultimo fotogramma chiave è calcolato dalla classe Extrapolation.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(curve, time) | Crea un nuovo key frame sulla curva specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| curva | KeyframeSequence | La curva su cui verrà creato il key frame |
| time | Numero | La posizione temporale del key frame |

 **Result:**



---


### getTime{#getTime}

| Nome | Descrizione |
| --- | --- |
| getTime() | Ottiene o imposta la posizione temporale del key frame list.data[index], misurata in secondi. Il tempo. |

 **Result:**



---


### setTime{#setTime}

| Nome | Descrizione |
| --- | --- |
| setTime(value) | Ottiene o imposta la posizione temporale del key frame list.data[index], misurata in secondi. Il tempo. |

 **Result:**



---


### getValue{#getValue}

| Nome | Descrizione |
| --- | --- |
| getValue() | Ottiene o imposta il valore del key-frame. Il valore. |

 **Result:**



---


### setValue{#setValue}

| Nome | Descrizione |
| --- | --- |
| setValue(value) | Ottiene o imposta il valore del key-frame. Il valore. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Nome | Descrizione |
| --- | --- |
| getInterpolation() | Ottiene o imposta il tipo di interpolazione del key, list.data[index] definisce l'algoritmo con cui il valore campionato è calcolato. Il valore della proprietà è la costante intera Interpolation. L'interpolazione. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Nome | Descrizione |
| --- | --- |
| setInterpolation(value) | Ottiene o imposta il tipo di interpolazione del key, list.data[index] definisce l'algoritmo con cui il valore campionato è calcolato. Il valore della proprietà è la costante intera Interpolation. L'interpolazione. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Nome | Descrizione |
| --- | --- |
| getTangentWeightMode() | Ottiene o imposta la modalità di peso della tangente del key. La tangente di uscita o la successiva tangente di ingresso possono essere personalizzate selezionando il WeightedMode corretto. Il valore della proprietà è la costante intera WeightedMode. La modalità di peso della tangente. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Nome | Descrizione |
| --- | --- |
| setTangentWeightMode(value) | Ottiene o imposta la modalità di peso della tangente del key. La tangente di uscita o la successiva tangente di ingresso possono essere personalizzate selezionando il WeightedMode corretto. Il valore della proprietà è la costante intera WeightedMode. La modalità di peso della tangente. |

 **Result:**



---


### getStepMode{#getStepMode}

| Nome | Descrizione |
| --- | --- |
| getStepMode() | Ottiene o imposta la modalità step del key. Se il tipo di interpolazione è Interpolation.CONSTANT, list.data[index] decide quale valore del key-frame verrà usato durante l'interpolazione. Un valore StepMode.PREVIOUS_VALUE significa che verrà usato il valore del key-frame a sinistra. Un valore StepMode.NEXT_VALUE significa che verrà usato il valore del key-frame a destra. Il valore della proprietà è la costante intera StepMode. La modalità step. |

 **Result:**



---


### setStepMode{#setStepMode}

| Nome | Descrizione |
| --- | --- |
| setStepMode(value) | Ottiene o imposta la modalità step del key. Se il tipo di interpolazione è Interpolation.CONSTANT, list.data[index] decide quale valore del key-frame verrà usato durante l'interpolazione. Un valore StepMode.PREVIOUS_VALUE significa che verrà usato il valore del key-frame a sinistra. Un valore StepMode.NEXT_VALUE significa che verrà usato il valore del key-frame a destra. Il valore della proprietà è la costante intera StepMode. La modalità step. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Nome | Descrizione |
| --- | --- |
| getNextInTangent() | Ottiene o imposta la prossima tangente di ingresso (sinistra) su questo key frame. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Nome | Descrizione |
| --- | --- |
| setNextInTangent(value) | Ottiene o imposta la prossima tangente di ingresso (sinistra) su questo key frame. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Nome | Descrizione |
| --- | --- |
| getOutTangent() | Ottiene o imposta la tangente di uscita (destra) su questo key frame. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Nome | Descrizione |
| --- | --- |
| setOutTangent(value) | Ottiene o imposta la tangente di uscita (destra) su questo key frame. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Nome | Descrizione |
| --- | --- |
| getOutWeight() | Ottiene o imposta il peso out(right) su questo fotogramma chiave. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Nome | Descrizione |
| --- | --- |
| setOutWeight(value) | Ottiene o imposta il peso out(right) su questo fotogramma chiave. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Nome | Descrizione |
| --- | --- |
| getNextInWeight() | Ottiene o imposta il peso next in(left) su questo fotogramma chiave. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Nome | Descrizione |
| --- | --- |
| setNextInWeight(value) | Ottiene o imposta il peso next in(left) su questo fotogramma chiave. |

 **Result:**



---


### getTension{#getTension}

| Nome | Descrizione |
| --- | --- |
| getTension() | Ottiene o imposta la tensione usata nella spline TCB |

 **Result:**



---


### setTension{#setTension}

| Nome | Descrizione |
| --- | --- |
| setTension(value) | Ottiene o imposta la tensione usata nella spline TCB |

 **Result:**



---


### getContinuity{#getContinuity}

| Nome | Descrizione |
| --- | --- |
| getContinuity() | Ottiene o imposta la continuità usata nella spline TCB |

 **Result:**



---


### setContinuity{#setContinuity}

| Nome | Descrizione |
| --- | --- |
| setContinuity(value) | Ottiene o imposta la continuità usata nella spline TCB |

 **Result:**



---


### getBias{#getBias}

| Nome | Descrizione |
| --- | --- |
| getBias() | Ottiene o imposta il bias usato nella spline TCB |

 **Result:**



---


### setBias{#setBias}

| Nome | Descrizione |
| --- | --- |
| setBias(value) | Ottiene o imposta il bias usato nella spline TCB |

 **Result:**



---


### getIndependentTangent{#getIndependentTangent}

| Nome | Descrizione |
| --- | --- |
| getIndependentTangent() | Ottiene o imposta che le tangenti out e next in siano indipendenti. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Nome | Descrizione |
| --- | --- |
| setIndependentTangent(value) | Ottiene o imposta che le tangenti out e next in siano indipendenti. |

 **Result:**



---


### getFlat{#getFlat}

| Nome | Descrizione |
| --- | --- |
| getFlat() | Ottieni o imposta se il fotogramma chiave è piatto. Il fotogramma chiave dovrebbe essere piatto se il fotogramma chiave successivo o precedente ha lo stesso valore. Un fotogramma chiave piatto ha tangenti piatte e interpolazione fissa. |

 **Result:**



---


### setFlat{#setFlat}

| Nome | Descrizione |
| --- | --- |
| setFlat(value) | Ottieni o imposta se il fotogramma chiave è piatto. Il fotogramma chiave dovrebbe essere piatto se il fotogramma chiave successivo o precedente ha lo stesso valore. Un fotogramma chiave piatto ha tangenti piatte e interpolazione fissa. |

 **Result:**



---


### getTimeIndependentTangent{#getTimeIndependentTangent}

| Nome | Descrizione |
| --- | --- |
| getTimeIndependentTangent() | Ottiene o imposta che la tangente sia indipendente dal tempo. |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Nome | Descrizione |
| --- | --- |
| setTimeIndependentTangent(value) | Ottiene o imposta che la tangente sia indipendente dal tempo. |

 **Result:**



---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Ottiene la rappresentazione stringa del fotogramma chiave |

 **Result:**
String


---



