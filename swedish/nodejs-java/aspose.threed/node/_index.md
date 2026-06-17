---
title: "Nod"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/node/
---
## Node class

Representerar ett element i scengrafen. En scengraf är ett träd av Node-objekt. Trädhanteringstjänsterna är självständiga i denna klass. Observera att Aspose.3D SDK inte testar giltigheten av den konstruerade scengrafen. Det är anroparens ansvar att säkerställa att den inte genererar cykliska grafer i en nodhierarki. Förutom trädhanteringen definierar denna klass alla egenskaper som krävs för att beskriva objektets position i scenen. Denna information inkluderar de grundläggande egenskaperna Translation, Rotation och Scaling samt mer avancerade alternativ för pivoter, begränsningar och IK-leden attribut såsom styvhet och dämpning. När den först skapas är Node-objektet "tomt" (dvs. det är ett objekt utan någon grafisk representation som endast innehåller positionsinformation). I detta tillstånd kan det användas för att representera föräldrar i nodträdet men inte mycket mer. Den normala användningen av denna typ av objekt är att lägga till dem en entitet som specialiserar noden (se "Entity"). Entiteten är ett eget objekt och är kopplad till Node. Detta innebär också att samma entitet kan delas mellan flera noder. Camera, Light, Mesh osv... är alla entiteter och de är alla härledda från basklassen Entity.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av Node-klassen. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(name, entity) | Initierar en ny instans av Node-klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |
| entitet | Entitet | Standardentitet. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(name) | Initierar en ny instans av Node-klassen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namn. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Namn | Beskrivning |
| --- | --- |
| getAssetInfo() | Tillgångsinformation per nod |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Namn | Beskrivning |
| --- | --- |
| setAssetInfo(value) | Tillgångsinformation per nod |

 **Result:**



---


### getVisible{#getVisible}

| Namn | Beskrivning |
| --- | --- |
| getVisible() | Hämtar eller anger för att visa noden |

 **Result:**



---


### setVisible{#setVisible}

| Namn | Beskrivning |
| --- | --- |
| setVisible(value) | Hämtar eller anger för att visa noden |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Namn | Beskrivning |
| --- | --- |
| getChildNodes() | Hämtar barnnoderna. Noderna. |

 **Result:**



---


### getEntity{#getEntity}

| Namn | Beskrivning |
| --- | --- |
| getEntity() | Hämtar eller anger den första entiteten som är kopplad till denna nod, om den anges rensas andra entiteter. Nodens entitet. |

 **Result:**



---


### setEntity{#setEntity}

| Namn | Beskrivning |
| --- | --- |
| setEntity(value) | Hämtar eller anger den första entiteten som är kopplad till denna nod, om den anges rensas andra entiteter. Nodens entitet. |

 **Result:**



---


### getExcluded{#getExcluded}

| Namn | Beskrivning |
| --- | --- |
| getExcluded() | Hämtar eller anger om denna nod och alla barnnoder/entiteter ska exkluderas vid export. |

 **Result:**



---


### setExcluded{#setExcluded}

| Namn | Beskrivning |
| --- | --- |
| setExcluded(value) | Hämtar eller anger om denna nod och alla barnnoder/entiteter ska exkluderas vid export. |

 **Result:**



---


### getEntities{#getEntities}

| Namn | Beskrivning |
| --- | --- |
| getEntities() | Hämtar alla nodentiteter. Nodentiteterna. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Namn | Beskrivning |
| --- | --- |
| getMetaDatas() | Hämtar metadata som definierats i denna nod. Metadatan. |

 **Result:**



---


### getMaterials{#getMaterials}

| Namn | Beskrivning |
| --- | --- |
| getMaterials() | Hämtar materialen som är associerade med denna nod. Materialen. |

 **Result:**



---


### getMaterial{#getMaterial}

| Namn | Beskrivning |
| --- | --- |
| getMaterial() | Hämtar eller anger det första materialet som är associerat med denna nod; om det anges rensas andra material. Materialet. |

 **Result:**



---


### setMaterial{#setMaterial}

| Namn | Beskrivning |
| --- | --- |
| setMaterial(value) | Hämtar eller anger det första materialet som är associerat med denna nod; om det anges rensas andra material. Materialet. |

 **Result:**



---


### getParentNode{#getParentNode}

| Namn | Beskrivning |
| --- | --- |
| getParentNode() | Hämtar eller anger föräldranoden. Föräldranoden. |

 **Result:**



---


### setParentNode{#setParentNode}

| Namn | Beskrivning |
| --- | --- |
| setParentNode(value) | Hämtar eller anger föräldranoden. Föräldranoden. |

 **Result:**



---


### getTransform{#getTransform}

| Namn | Beskrivning |
| --- | --- |
| getTransform() | Hämtar den lokala transformen. Transformen. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Namn | Beskrivning |
| --- | --- |
| getGlobalTransform() | Hämtar den globala transformen. Den globala transformen. |

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


### createChildNode{#createChildNode}

| Namn | Beskrivning |
| --- | --- |
| createChildNode() | Skapar en barnnod |

 **Result:**
Nod


---


### merge{#merge}

| Namn | Beskrivning |
| --- | --- |
| merge(node) | Koppla loss allt under noden och fäst dem på den aktuella noden. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nod | Nod | null |

 **Result:**
Nod


---


### createChildNode{#createChildNode}

| Namn | Beskrivning |
| --- | --- |
| createChildNode(nodeName) | Skapa en ny barnnod med angivet nodnamn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | Sträng | Det nya barnnodens namn |

 **Result:**
Nod


---


### createChildNode{#createChildNode}

| Namn | Beskrivning |
| --- | --- |
| createChildNode(entity) | Skapa en ny barnnod med angiven entitet bifogad |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| entitet | Entitet | Standardentitet bifogad till noden |

 **Result:**
Nod


---


### createChildNode{#createChildNode}

| Namn | Beskrivning |
| --- | --- |
| createChildNode(nodeName, entity) | Skapa en ny barnnod med angivet nodnamn |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | Sträng | Det nya barnnodens namn |
| entitet | Entitet | Standardentitet bifogad till noden |

 **Result:**
Nod


---


### createChildNode{#createChildNode}

| Namn | Beskrivning |
| --- | --- |
| createChildNode(nodeName, entity, material) | Skapa en ny barnnod med angivet nodnamn och fäst angiven entitet samt ett material |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | Sträng | Det nya barnnodens namn |
| entitet | Entitet | Standardentitet bifogad till noden |
| material | Material | Materialet bifogat till noden |

 **Result:**
Nod


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Namn | Beskrivning |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Utvärdera den globala transformen, inkludera den geometriska transformen eller inte. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| withGeometricTransform | boolean | Om den geometriska transformen behövs. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Namn | Beskrivning |
| --- | --- |
| getChild(index) | Hämtar barnnoden på angivet index. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| index | Nummer | Index. |

 **Result:**
Nod


---


### getChild{#getChild}

| Namn | Beskrivning |
| --- | --- |
| getChild(nodeName) | Hämtar barnnoden med det angivna namnet |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nodeName | Sträng | Barnnamnet att hitta. |

 **Result:**
Nod


---


### accept{#accept}

| Namn | Beskrivning |
| --- | --- |
| accept(visitor) | Går igenom alla underordnade noder (inklusive den aktuella noden) och anropar besökaren med noden. Besökaren kan avbryta genomgången genom att returnera falskt |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| visitor | NodeVisitor | Besöksåteruppringning för att besöka noden |

 **Result:**
boolean


---


### toString{#toString}

| Namn | Beskrivning |
| --- | --- |
| toString() | Hämtar strängrepresentationen av denna nod. |

 **Result:**
Sträng


---


### getBoundingBox{#getBoundingBox}

| Namn | Beskrivning |
| --- | --- |
| getBoundingBox() | Beräkna begränsningsrutan för noden |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Namn | Beskrivning |
| --- | --- |
| addEntity(entity) | Lägg till en entitet i noden. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| entitet | Entitet | Entiteten som ska bifogas noden |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Namn | Beskrivning |
| --- | --- |
| addChildNode(node) | Lägg till en barnnod till denna nod |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| nod | Nod | Barnnoden som ska bifogas |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Namn | Beskrivning |
| --- | --- |
| selectSingleObject(path) | Välj ett enskilt objekt under den aktuella noden med XPath-liknande frågesyntax. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| pat | Sträng | null |

 **Result:**
Objekt


---


### selectObjects{#selectObjects}

| Namn | Beskrivning |
| --- | --- |
| selectObjects(path) | Välj flera objekt under den aktuella noden med XPath-liknande frågesyntax. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| pat | Sträng | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


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



