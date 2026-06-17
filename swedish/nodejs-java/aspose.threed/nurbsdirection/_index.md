---
title: "NurbsDirection"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/nurbsdirection/
---
## NurbsDirection class

En 3D NurbsSurface har två riktningar, NurbsSurface.U och NurbsSurface.V, där NurbsDirection definierar data för varje riktning. En riktning är i själva verket en NURBS-kurva, vilket betyder att den också definieras av dess ordning, en KnotVectors och en uppsättning viktade kontrollpunkter (definierade i NurbsSurface).


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() |  |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Namn | Beskrivning |
| --- | --- |
| getKnotVectors() | Hämtar knot-vektorn, den är en sekvens av parametervärden som bestämmer var och hur kontrollpunkterna påverkar NURBS-kurvan. |

 **Result:**



---


### getMultiplicity{#getMultiplicity}

| Namn | Beskrivning |
| --- | --- |
| getMultiplicity() | Hämtar multipliciteten. Multipliciteten. |

 **Result:**



---


### getOrder{#getOrder}

| Namn | Beskrivning |
| --- | --- |
| getOrder() | Hämtar eller anger ordningen för en NURBS-kurva, den definierar antalet närliggande kontrollpunkter som påverkar varje given punkt på kurvan. |

 **Result:**



---


### setOrder{#setOrder}

| Namn | Beskrivning |
| --- | --- |
| setOrder(value) | Hämtar eller anger ordningen för en NURBS-kurva, den definierar antalet närliggande kontrollpunkter som påverkar varje given punkt på kurvan. |

 **Result:**



---


### getDivisions{#getDivisions}

| Namn | Beskrivning |
| --- | --- |
| getDivisions() | Hämtar eller anger antalet divisioner mellan intilliggande kontrollpunkter i aktuell riktning. Steget. |

 **Result:**



---


### setDivisions{#setDivisions}

| Namn | Beskrivning |
| --- | --- |
| setDivisions(value) | Hämtar eller anger antalet divisioner mellan intilliggande kontrollpunkter i aktuell riktning. Steget. |

 **Result:**



---


### getType{#getType}

| Namn | Beskrivning |
| --- | --- |
| getType() | Hämtar eller anger typen för den aktuella riktningen. Värdet på egenskapen är NurbsType heltalskonstant. |

 **Result:**



---


### setType{#setType}

| Namn | Beskrivning |
| --- | --- |
| setType(value) | Hämtar eller anger typen för den aktuella riktningen. Värdet på egenskapen är NurbsType heltalskonstant. |

 **Result:**



---


### getCount{#getCount}

| Namn | Beskrivning |
| --- | --- |
| getCount() | Hämtar eller anger antalet kontrollpunkter i aktuell riktning. Antalet. |

 **Result:**



---


### setCount{#setCount}

| Namn | Beskrivning |
| --- | --- |
| setCount(value) | Hämtar eller anger antalet kontrollpunkter i aktuell riktning. Antalet. |

 **Result:**



---



