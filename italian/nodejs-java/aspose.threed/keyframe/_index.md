---
title: "KeyFrame"
second_title: "Aspose.3D per Node.js via Java API Reference"
description: 
type: docs

url: /it/nodejs-java/aspose.threed/keyframe/
---
## KeyFrame class

Un key frame è principalmente definito da un tempo e un valore; per alcuni tipi di interpolazione, tangente/tensione/bias/continuità sono anche usati nel calcolo del valore campionato finale.  I valori campionati in una posizione temporale non key-frame sono interpolati dai key-frame tra il key-frame precedente e quello successivo.  I valori prima/dopo il primo/ultimo key-frame sono calcolati dalla classe Extrapolation.


## Metodi

### constructor{#constructor}

| Nome | Descrizione |
| --- | --- |
| constructor(curve, time) | Crea un nuovo key frame sulla curva specificata |

 **Parameters:**

| Nome | Tipo | Descrizione |
| --- | --- | --- |
| curve | KeyframeSequence | La curva su cui verrà creato il fotogramma chiave |
| time | Numero | La posizione temporale del fotogramma chiave |

 **Result:**



---


### getTime{#getTime}

| Nome | Descrizione |
| --- | --- |
| getTime() | Ottiene o imposta la posizione temporale del fotogramma chiave list.data[index], misurata in secondi. Il tempo. |

 **Result:**



---


### setTime{#setTime}

| Nome | Descrizione |
| --- | --- |
| setTime(value) | Ottiene o imposta la posizione temporale del fotogramma chiave list.data[index], misurata in secondi. Il tempo. |

 **Result:**



---


### getValue{#getValue}

| Nome | Descrizione |
| --- | --- |
| getValue() | Ottiene o imposta il valore del fotogramma chiave. Il valore. |

 **Result:**



---


### setValue{#setValue}

| Nome | Descrizione |
| --- | --- |
| setValue(value) | Ottiene o imposta il valore del fotogramma chiave. Il valore. |

 **Result:**



---


### getInterpolation{#getInterpolation}

| Nome | Descrizione |
| --- | --- |
| getInterpolation() | Ottiene o imposta il tipo di interpolazione del fotogramma chiave, list.data[index] definisce l'algoritmo con cui viene calcolato il valore campionato. Il valore della proprietà è la costante intera Interpolation. L'interpolazione. |

 **Result:**



---


### setInterpolation{#setInterpolation}

| Nome | Descrizione |
| --- | --- |
| setInterpolation(value) | Ottiene o imposta il tipo di interpolazione del fotogramma chiave, list.data[index] definisce l'algoritmo con cui viene calcolato il valore campionato. Il valore della proprietà è la costante intera Interpolation. L'interpolazione. |

 **Result:**



---


### getTangentWeightMode{#getTangentWeightMode}

| Nome | Descrizione |
| --- | --- |
| getTangentWeightMode() | Ottiene o imposta la modalità di peso della tangente del fotogramma chiave. La tangente di uscita o la successiva tangente di ingresso possono essere personalizzate selezionando il WeightedMode corretto. Il valore della proprietà è la costante intera WeightedMode. La modalità di peso della tangente. |

 **Result:**



---


### setTangentWeightMode{#setTangentWeightMode}

| Nome | Descrizione |
| --- | --- |
| setTangentWeightMode(value) | Ottiene o imposta la modalità di peso della tangente del fotogramma chiave. La tangente di uscita o la successiva tangente di ingresso possono essere personalizzate selezionando il WeightedMode corretto. Il valore della proprietà è la costante intera WeightedMode. La modalità di peso della tangente. |

 **Result:**



---


### getStepMode{#getStepMode}

| Nome | Descrizione |
| --- | --- |
| getStepMode() | Ottiene o imposta la modalità di passo del fotogramma chiave. Se il tipo di interpolazione è Interpolation.CONSTANT, list.data[index] decide quale valore del fotogramma chiave verrà utilizzato durante l'interpolazione. Un valore StepMode.PREVIOUS_VALUE indica che verrà usato il valore del fotogramma chiave a sinistra. Un valore StepMode.NEXT_VALUE indica che verrà usato il valore del fotogramma chiave a destra. Il valore della proprietà è la costante intera StepMode. La modalità di passo. |

 **Result:**



---


### setStepMode{#setStepMode}

| Nome | Descrizione |
| --- | --- |
| setStepMode(value) | Ottiene o imposta la modalità di passo del fotogramma chiave. Se il tipo di interpolazione è Interpolation.CONSTANT, list.data[index] decide quale valore del fotogramma chiave verrà utilizzato durante l'interpolazione. Un valore StepMode.PREVIOUS_VALUE indica che verrà usato il valore del fotogramma chiave a sinistra. Un valore StepMode.NEXT_VALUE indica che verrà usato il valore del fotogramma chiave a destra. Il valore della proprietà è la costante intera StepMode. La modalità di passo. |

 **Result:**



---


### getNextInTangent{#getNextInTangent}

| Nome | Descrizione |
| --- | --- |
| getNextInTangent() | Ottiene o imposta la prossima tangente di ingresso (sinistra) su questo fotogramma chiave. |

 **Result:**



---


### setNextInTangent{#setNextInTangent}

| Nome | Descrizione |
| --- | --- |
| setNextInTangent(value) | Ottiene o imposta la prossima tangente di ingresso (sinistra) su questo fotogramma chiave. |

 **Result:**



---


### getOutTangent{#getOutTangent}

| Nome | Descrizione |
| --- | --- |
| getOutTangent() | Ottiene o imposta la tangente di uscita (destra) su questo fotogramma chiave. |

 **Result:**



---


### setOutTangent{#setOutTangent}

| Nome | Descrizione |
| --- | --- |
| setOutTangent(value) | Ottiene o imposta la tangente di uscita (destra) su questo fotogramma chiave. |

 **Result:**



---


### getOutWeight{#getOutWeight}

| Nome | Descrizione |
| --- | --- |
| getOutWeight() | Ottiene o imposta il peso di uscita (destra) su questo fotogramma chiave. |

 **Result:**



---


### setOutWeight{#setOutWeight}

| Nome | Descrizione |
| --- | --- |
| setOutWeight(value) | Ottiene o imposta il peso di uscita (destra) su questo fotogramma chiave. |

 **Result:**



---


### getNextInWeight{#getNextInWeight}

| Nome | Descrizione |
| --- | --- |
| getNextInWeight() | Ottiene o imposta il peso successivo in (sinistra) su questo fotogramma chiave. |

 **Result:**



---


### setNextInWeight{#setNextInWeight}

| Nome | Descrizione |
| --- | --- |
| setNextInWeight(value) | Ottiene o imposta il peso successivo in (sinistra) su questo fotogramma chiave. |

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
| getIndependentTangent() | Ottiene o imposta se le tangenti di uscita e la successiva in sono indipendenti. |

 **Result:**



---


### setIndependentTangent{#setIndependentTangent}

| Nome | Descrizione |
| --- | --- |
| setIndependentTangent(value) | Ottiene o imposta se le tangenti di uscita e la successiva in sono indipendenti. |

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
| getTimeIndependentTangent() | Ottiene o imposta se la tangente è indipendente dal tempo |

 **Result:**



---


### setTimeIndependentTangent{#setTimeIndependentTangent}

| Nome | Descrizione |
| --- | --- |
| setTimeIndependentTangent(value) | Ottiene o imposta se la tangente è indipendente dal tempo |

 **Result:**



---


### toString{#toString}

| Nome | Descrizione |
| --- | --- |
| toString() | Ottiene la rappresentazione stringa del fotogramma chiave |

 **Result:**
Stringa


---



