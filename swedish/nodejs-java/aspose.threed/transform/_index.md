---
title: "Transform"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/transform/
---
## Transform class

En transform innehåller information som möjliggör åtkomst till objektets förflyttning/skala/rotation eller transformmatris med minimal kostnad. Detta används av lokal transform.  @hideconstructor


## Metoder

### getGeometricTranslation{#getGeometricTranslation}

| Namn | Beskrivning |
| --- | --- |
| getGeometricTranslation() | Hämtar eller anger den geometriska translationen. Geometrisk transformation påverkar endast de bifogade enheterna och lämnar underordnade noder opåverkade. Den kommer att slås ihop som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stödjer den. |

 **Result:**



---


### setGeometricTranslation{#setGeometricTranslation}

| Namn | Beskrivning |
| --- | --- |
| setGeometricTranslation(value) | Hämtar eller anger den geometriska translationen. Geometrisk transformation påverkar endast de bifogade enheterna och lämnar underordnade noder opåverkade. Den kommer att slås ihop som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stödjer den. |

 **Result:**



---


### getGeometricScaling{#getGeometricScaling}

| Namn | Beskrivning |
| --- | --- |
| getGeometricScaling() | Hämtar eller anger den geometriska skalningen. Geometrisk transformation påverkar endast de bifogade enheterna och lämnar underordnade noder opåverkade. Den kommer att slås ihop som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stödjer den. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Namn | Beskrivning |
| --- | --- |
| setGeometricScaling(value) | Hämtar eller anger den geometriska skalningen. Geometrisk transformation påverkar endast de bifogade enheterna och lämnar underordnade noder opåverkade. Den kommer att slås ihop som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stödjer den. |

 **Result:**



---


### getGeometricRotation{#getGeometricRotation}

| Namn | Beskrivning |
| --- | --- |
| getGeometricRotation() | Hämtar eller anger den geometriska Euler-rotationen (mätt i grader). Geometrisk transformation påverkar endast de bifogade enheterna och lämnar underordnade noder opåverkade. Den kommer att slås ihop som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stödjer den. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Namn | Beskrivning |
| --- | --- |
| setGeometricRotation(value) | Hämtar eller anger den geometriska Euler-rotationen (mätt i grader). Geometrisk transformation påverkar endast de bifogade enheterna och lämnar underordnade noder opåverkade. Den kommer att slås ihop som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stödjer den. |

 **Result:**



---


### getTranslation{#getTranslation}

| Namn | Beskrivning |
| --- | --- |
| getTranslation() | Hämtar eller anger översättningen |

 **Result:**



---


### setTranslation{#setTranslation}

| Namn | Beskrivning |
| --- | --- |
| setTranslation(value) | Hämtar eller anger översättningen |

 **Result:**



---


### getScale{#getScale}

| Namn | Beskrivning |
| --- | --- |
| getScale() | Hämtar eller anger skalan |

 **Result:**



---


### setScale{#setScale}

| Namn | Beskrivning |
| --- | --- |
| setScale(value) | Hämtar eller anger skalan |

 **Result:**



---


### getPreRotation{#getPreRotation}

| Namn | Beskrivning |
| --- | --- |
| getPreRotation() | Hämtar eller anger förrotationen representerad i grader |

 **Result:**



---


### setPreRotation{#setPreRotation}

| Namn | Beskrivning |
| --- | --- |
| setPreRotation(value) | Hämtar eller anger förrotationen representerad i grader |

 **Result:**



---


### getPostRotation{#getPostRotation}

| Namn | Beskrivning |
| --- | --- |
| getPostRotation() | Hämtar eller anger efterrotationen representerad i grader |

 **Result:**



---


### setPostRotation{#setPostRotation}

| Namn | Beskrivning |
| --- | --- |
| setPostRotation(value) | Hämtar eller anger efterrotationen representerad i grader |

 **Result:**



---


### getEulerAngles{#getEulerAngles}

| Namn | Beskrivning |
| --- | --- |
| getEulerAngles() | Hämtar eller anger rotationen representerad i Euler-vinklar, mätt i grader |

 **Result:**



---


### setEulerAngles{#setEulerAngles}

| Namn | Beskrivning |
| --- | --- |
| setEulerAngles(value) | Hämtar eller anger rotationen representerad i Euler-vinklar, mätt i grader |

 **Result:**



---


### getRotation{#getRotation}

| Namn | Beskrivning |
| --- | --- |
| getRotation() | Hämtar eller anger rotationen representerad i en kvaternion. |

 **Result:**



---


### setRotation{#setRotation}

| Namn | Beskrivning |
| --- | --- |
| setRotation(value) | Hämtar eller anger rotationen representerad i en kvaternion. |

 **Result:**



---


### getTransformMatrix{#getTransformMatrix}

| Namn | Beskrivning |
| --- | --- |
| getTransformMatrix() | Hämtar eller anger transformmatrisen. En tilldelning här kommer att återställa Översättningen, Skalan och Rotation, medan GeometricRotation, GeometricScaling och GeometricTranslation inte påverkas. |

 **Result:**



---


### setTransformMatrix{#setTransformMatrix}

| Namn | Beskrivning |
| --- | --- |
| setTransformMatrix(value) | Hämtar eller anger transformmatrisen. En tilldelning här kommer att återställa Översättningen, Skalan och Rotation, medan GeometricRotation, GeometricScaling och GeometricTranslation inte påverkas. |

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


### setGeometricTranslation{#setGeometricTranslation}

| Namn | Beskrivning |
| --- | --- |
| setGeometricTranslation(x, y, z) | Anger den geometriska översättningen. Geometrisk transformation påverkar endast de bifogade enheterna och lämnar barnnoderna opåverkade. Den kommer att slås samman som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stöder den. |

 **Result:**



---


### setGeometricScaling{#setGeometricScaling}

| Namn | Beskrivning |
| --- | --- |
| setGeometricScaling(sx, sy, sz) | Anger den geometriska skalningen. Geometrisk transformation påverkar endast de bifogade enheterna och lämnar barnnoderna opåverkade. Den kommer att slås samman som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stöder den. |

 **Result:**



---


### setGeometricRotation{#setGeometricRotation}

| Namn | Beskrivning |
| --- | --- |
| setGeometricRotation(rx, ry, rz) | Anger den geometriska Euler-rotationen (mätt i grader). Geometrisk transformation påverkar endast de bifogade enheterna och lämnar barnnoderna opåverkade. Den kommer att slås samman som lokal transformation när du exporterar den geometriska transformationen till filtyper som inte stöder den. |

 **Result:**



---


### setTranslation{#setTranslation}

| Namn | Beskrivning |
| --- | --- |
| setTranslation(tx, ty, tz) | Anger översättningen för den aktuella transformen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| t | Nummer | null |
| t | Nummer | null |
| t | Nummer | null |

 **Result:**
Transform


---


### setScale{#setScale}

| Namn | Beskrivning |
| --- | --- |
| setScale(sx, sy, sz) | Anger skalan för den aktuella transformen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| s | Nummer | null |
| s | Nummer | null |
| s | Nummer | null |

 **Result:**
Transform


---


### setEulerAngles{#setEulerAngles}

| Namn | Beskrivning |
| --- | --- |
| setEulerAngles(rx, ry, rz) | Ställer in Euler-vinklarna i grader för den aktuella transformationen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| r | Nummer | null |
| r | Nummer | null |
| r | Nummer | null |

 **Result:**
Transform


---


### setRotation{#setRotation}

| Namn | Beskrivning |
| --- | --- |
| setRotation(rw, rx, ry, rz) | Ställer in rotationen (som kvaternionkomponenter) för den aktuella transformationen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| r | Nummer | null |
| r | Nummer | null |
| r | Nummer | null |
| r | Nummer | null |

 **Result:**
Transform


---


### setPreRotation{#setPreRotation}

| Namn | Beskrivning |
| --- | --- |
| setPreRotation(rx, ry, rz) | Ställer in förrotationen representerad i grader |

 **Result:**
Transform


---


### setPostRotation{#setPostRotation}

| Namn | Beskrivning |
| --- | --- |
| setPostRotation(rx, ry, rz) | Ställer in efterrotationen representerad i grader |

 **Result:**
Transform


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



