---
title: "NurbsCurve"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/nurbscurve/
---
## NurbsCurve class

NURBS-kurva är en kurva som representeras av NURBS (Non-uniform rational basis spline). En NURBS-kurva definieras av dess ordning, en uppsättning viktade Geometry.ControlPoints och en KnotVectors. w-komponenten i kontrollpunkten används som kontrollpunktens vikt, oavsett om den är CurveDimension.TWO_DIMENSIONAL eller CurveDimension.THREE_DIMENSIONAL.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av klassen NurbsCurve. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(name) | Initierar en ny instans av klassen NurbsCurve. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn |

 **Result:**



---


### getControlPoints{#getControlPoints}

| Namn | Beskrivning |
| --- | --- |
| getControlPoints() | Hämtar alla kontrollpunkter |

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
| getOrder() | Hämtar eller anger ordningen för en NURBS-kurva, den definierar antalet närliggande kontrollpunkter som påverkar varje given punkt på kurvan. Ordningen. |

 **Result:**



---


### setOrder{#setOrder}

| Namn | Beskrivning |
| --- | --- |
| setOrder(value) | Hämtar eller anger ordningen för en NURBS-kurva, den definierar antalet närliggande kontrollpunkter som påverkar varje given punkt på kurvan. Ordningen. |

 **Result:**



---


### getDimension{#getDimension}

| Namn | Beskrivning |
| --- | --- |
| getDimension() | Hämtar eller anger kurvans dimension. Värdet på egenskapen är en CurveDimension heltalskonstant. För en CurveDimension.TWO_DIMENSIONAL-kurva används z-komponenten i kontrollpunkten inte. |

 **Result:**



---


### setDimension{#setDimension}

| Namn | Beskrivning |
| --- | --- |
| setDimension(value) | Hämtar eller anger kurvans dimension. Värdet på egenskapen är en CurveDimension heltalskonstant. För en CurveDimension.TWO_DIMENSIONAL-kurva används z-komponenten i kontrollpunkten inte. |

 **Result:**



---


### getCurveType{#getCurveType}

| Namn | Beskrivning |
| --- | --- |
| getCurveType() | Hämtar eller anger kurvans typ. Värdet på egenskapen är NurbsType heltalskonstant. Kurvans typ. |

 **Result:**



---


### setCurveType{#setCurveType}

| Namn | Beskrivning |
| --- | --- |
| setCurveType(value) | Hämtar eller anger kurvans typ. Värdet på egenskapen är NurbsType heltalskonstant. Kurvans typ. |

 **Result:**



---


### getKnotVectors{#getKnotVectors}

| Namn | Beskrivning |
| --- | --- |
| getKnotVectors() | Hämtar knot-vektorn, den är en sekvens av parametervärden som bestämmer var och hur kontrollpunkterna påverkar NURBS-kurvan. |

 **Result:**



---


### getRational{#getRational}

| Namn | Beskrivning |
| --- | --- |
| getRational() | Hämtar eller anger om den är rationell, detta värde indikerar om denna NurbsCurve är en rationell spline eller en icke‑rationell spline. Icke‑rationell B-spline är ett specialfall av rationella B-splines. true om det är en rationell spline; annars, false är en icke‑rationell spline. |

 **Result:**



---


### setRational{#setRational}

| Namn | Beskrivning |
| --- | --- |
| setRational(value) | Hämtar eller anger om den är rationell, detta värde indikerar om denna NurbsCurve är en rationell spline eller en icke‑rationell spline. Icke‑rationell B-spline är ett specialfall av rationella B-splines. true om det är en rationell spline; annars, false är en icke‑rationell spline. |

 **Result:**



---


### getColor{#getColor}

| Namn | Beskrivning |
| --- | --- |
| getColor() | Hämtar eller anger färgen på linjen, standardvärdet är vit(1, 1, 1) |

 **Result:**



---


### setColor{#setColor}

| Namn | Beskrivning |
| --- | --- |
| setColor(value) | Hämtar eller anger färgen på linjen, standardvärdet är vit(1, 1, 1) |

 **Result:**



---


### getParentNodes{#getParentNodes}

| Namn | Beskrivning |
| --- | --- |
| getParentNodes() | Hämtar alla föräldranoder, en entitet kan fästas vid flera föräldranoder för geometri‑instansering. Noderna. |

 **Result:**



---


### getExcluded{#getExcluded}

| Namn | Beskrivning |
| --- | --- |
| getExcluded() | Hämtar eller anger om denna enhet ska exkluderas vid export. |

 **Result:**



---


### setExcluded{#setExcluded}

| Namn | Beskrivning |
| --- | --- |
| setExcluded(value) | Hämtar eller anger om denna enhet ska exkluderas vid export. |

 **Result:**



---


### getParentNode{#getParentNode}

| Namn | Beskrivning |
| --- | --- |
| getParentNode() | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer denna enhet att frikopplas från andra föräldranoder. Föräldranoden. |

 **Result:**



---


### setParentNode{#setParentNode}

| Namn | Beskrivning |
| --- | --- |
| setParentNode(value) | Hämtar eller anger den första föräldranoden, om den första föräldranoden anges kommer denna enhet att frikopplas från andra föräldranoder. Föräldranoden. |

 **Result:**



---


### getScene{#getScene}

| Namn | Beskrivning |
| --- | --- |
| getScene() | Hämtar scenen som detta objekt tillhör |

 **Result:**



---


### getName{#getName}

| Namn | Beskrivning |
| --- | --- |
| getName() | Hämtar eller anger namnet. Namnet. |

 **Result:**



---


### setName{#setName}

| Namn | Beskrivning |
| --- | --- |
| setName(value) | Hämtar eller anger namnet. Namnet. |

 **Result:**



---


### getProperties{#getProperties}

| Namn | Beskrivning |
| --- | --- |
| getProperties() | Hämtar samlingen av alla egenskaper. |

 **Result:**



---


### evaluate{#evaluate}

| Namn | Beskrivning |
| --- | --- |
| evaluate(steps) | Utvärdera NURBS-kurvan |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| steps | Nummer | Utvärderingsfrekvensen mellan två intilliggande knutar, standardvärdet är 20 |

 **Result:**
Vector4[]


---


### evaluateAt{#evaluateAt}

| Namn | Beskrivning |
| --- | --- |
| evaluateAt(u) | Utvärdera kurvans punkt vid angiven position |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| u | Nummer | Positionen i kurvan, mellan 0 och 1 |

 **Result:**
Vector4


---


### getEntityRendererKey{#getEntityRendererKey}

| Namn | Beskrivning |
| --- | --- |
| getEntityRendererKey() | Hämtar nyckeln för enhetens renderare som är registrerad i renderaren |

 **Result:**
EntityRendererKey


---


### getBoundingBox{#getBoundingBox}

| Namn | Beskrivning |
| --- | --- |
| getBoundingBox() | Hämtar den omgivande lådan för den aktuella enheten i dess objektrums koordinatsystem. |

 **Result:**
EntityRendererKey


---


### removeProperty{#removeProperty}

| Namn | Beskrivning |
| --- | --- |
| removeProperty(property) | Tar bort en dynamisk egenskap. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Property | Vilken egenskap som ska tas bort |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Namn | Beskrivning |
| --- | --- |
| removeProperty(property) | Ta bort den angivna egenskapen som identifieras med namn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| propert | Sträng | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Namn | Beskrivning |
| --- | --- |
| getProperty(property) | Hämta värdet för den angivna egenskapen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Sträng | Egenskapsnamn |

 **Result:**
Objekt


---


### setProperty{#setProperty}

| Namn | Beskrivning |
| --- | --- |
| setProperty(property, value) | Sätter värdet för den angivna egenskapen |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| property | Sträng | Egenskapsnamn |
| värde | Objekt | Värdet för egenskapen |

 **Result:**
Objekt


---


### findProperty{#findProperty}

| Namn | Beskrivning |
| --- | --- |
| findProperty(propertyName) | Hittar egenskapen. Det kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad av dess namn) |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | Sträng | Egenskapsnamn. |

 **Result:**
Property


---



