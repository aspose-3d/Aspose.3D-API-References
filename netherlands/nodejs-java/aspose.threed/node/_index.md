---
title: "Node"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/node/
---
## Node class

Vertegenwoordigt een element in de scenegraph. Een scenegraph is een boom van Node-objecten. De boombeheer‑services zijn zelfvoorzienend in deze klasse. Let op: de Aspose.3D SDK test de geldigheid van de geconstrueerde scenegraph niet. Het is de verantwoordelijkheid van de aanroeper om ervoor te zorgen dat er geen cyclische grafen in een node‑hiërarchie worden gegenereerd. Naast het boombeheer definieert deze klasse alle eigenschappen die nodig zijn om de positie van het object in de scène te beschrijven. Deze informatie omvat de basis‑eigenschappen Translation, Rotation en Scaling en de meer geavanceerde opties voor pivots, limits en IK‑gewrichts‑attributen zoals stijfheid en demping. Wanneer het voor het eerst wordt aangemaakt, is het Node‑object "empty" (d.w.z.: het is een object zonder enige grafische weergave dat alleen de positiëlinformatie bevat). In deze toestand kan het worden gebruikt om ouders in de node‑boomstructuur te vertegenwoordigen, maar niet veel meer. Het normale gebruik van dit type objecten is om er een entiteit aan toe te voegen die de node specialiseert (zie "Entity"). De entiteit is een object op zichzelf en is verbonden met de Node. Dit betekent ook dat dezelfde entiteit kan worden gedeeld tussen meerdere nodes. Camera, Light, Mesh, enz... zijn allemaal entiteiten en ze zijn allemaal afgeleid van de basisklasse Entity.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de Node-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(name, entity) | Initialiseert een nieuw exemplaar van de Node-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |
| entity | Entity | Standaard entiteit. |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(name) | Initialiseert een nieuw exemplaar van de Node-klasse. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam. |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Naam | Beschrijving |
| --- | --- |
| getAssetInfo() | Per-node assetinformatie |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Naam | Beschrijving |
| --- | --- |
| setAssetInfo(value) | Per-node assetinformatie |

 **Result:**



---


### getVisible{#getVisible}

| Naam | Beschrijving |
| --- | --- |
| getVisible() | Haalt op of stelt in om de node te tonen |

 **Result:**



---


### setVisible{#setVisible}

| Naam | Beschrijving |
| --- | --- |
| setVisible(value) | Haalt op of stelt in om de node te tonen |

 **Result:**



---


### getChildNodes{#getChildNodes}

| Naam | Beschrijving |
| --- | --- |
| getChildNodes() | Haalt de kindnodes op. De nodes. |

 **Result:**



---


### getEntity{#getEntity}

| Naam | Beschrijving |
| --- | --- |
| getEntity() | Haalt de eerste entiteit op die aan deze node is gekoppeld, of stelt deze in; bij instellen worden andere entiteiten gewist. De node-entiteit. |

 **Result:**



---


### setEntity{#setEntity}

| Naam | Beschrijving |
| --- | --- |
| setEntity(value) | Haalt de eerste entiteit op die aan deze node is gekoppeld, of stelt deze in; bij instellen worden andere entiteiten gewist. De node-entiteit. |

 **Result:**



---


### getExcluded{#getExcluded}

| Naam | Beschrijving |
| --- | --- |
| getExcluded() | Haalt op of stelt in of deze node en alle kindnodes/entiteiten moeten worden uitgesloten tijdens het exporteren. |

 **Result:**



---


### setExcluded{#setExcluded}

| Naam | Beschrijving |
| --- | --- |
| setExcluded(value) | Haalt op of stelt in of deze node en alle kindnodes/entiteiten moeten worden uitgesloten tijdens het exporteren. |

 **Result:**



---


### getEntities{#getEntities}

| Naam | Beschrijving |
| --- | --- |
| getEntities() | Haalt alle node-entiteiten op. De node-entiteiten. |

 **Result:**



---


### getMetaDatas{#getMetaDatas}

| Naam | Beschrijving |
| --- | --- |
| getMetaDatas() | Haalt de metagegevens op die in deze node zijn gedefinieerd. De metagegevens. |

 **Result:**



---


### getMaterials{#getMaterials}

| Naam | Beschrijving |
| --- | --- |
| getMaterials() | Haalt de materialen op die aan deze node zijn gekoppeld. De materialen. |

 **Result:**



---


### getMaterial{#getMaterial}

| Naam | Beschrijving |
| --- | --- |
| getMaterial() | Haalt het eerste materiaal op dat aan deze node is gekoppeld, of stelt dit in; bij instellen worden andere materialen gewist. Het materiaal. |

 **Result:**



---


### setMaterial{#setMaterial}

| Naam | Beschrijving |
| --- | --- |
| setMaterial(value) | Haalt het eerste materiaal op dat aan deze node is gekoppeld, of stelt dit in; bij instellen worden andere materialen gewist. Het materiaal. |

 **Result:**



---


### getParentNode{#getParentNode}

| Naam | Beschrijving |
| --- | --- |
| getParentNode() | Haalt de bovenliggende node op of stelt deze in. De bovenliggende node. |

 **Result:**



---


### setParentNode{#setParentNode}

| Naam | Beschrijving |
| --- | --- |
| setParentNode(value) | Haalt de bovenliggende node op of stelt deze in. De bovenliggende node. |

 **Result:**



---


### getTransform{#getTransform}

| Naam | Beschrijving |
| --- | --- |
| getTransform() | Haalt de lokale transformatie op. De transformatie. |

 **Result:**



---


### getGlobalTransform{#getGlobalTransform}

| Naam | Beschrijving |
| --- | --- |
| getGlobalTransform() | Haalt de globale transformatie op. De globale transformatie. |

 **Result:**



---


### getScene{#getScene}

| Naam | Beschrijving |
| --- | --- |
| getScene() | Haalt de scène op waartoe dit object behoort. |

 **Result:**



---


### getName{#getName}

| Naam | Beschrijving |
| --- | --- |
| getName() | Haalt de naam op of stelt deze in. De naam. |

 **Result:**



---


### setName{#setName}

| Naam | Beschrijving |
| --- | --- |
| setName(value) | Haalt de naam op of stelt deze in. De naam. |

 **Result:**



---


### getProperties{#getProperties}

| Naam | Beschrijving |
| --- | --- |
| getProperties() | Haalt de collectie van alle eigenschappen op. |

 **Result:**



---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode() | Maakt een kindknooppunt |

 **Result:**
Node


---


### merge{#merge}

| Naam | Beschrijving |
| --- | --- |
| merge(node) | Ontkoppel alles onder het knooppunt en koppel ze aan het huidige knooppunt. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nod | Node | null |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode(nodeName) | Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | De naam van het nieuwe kindknooppunt |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode(entity) | Maak een nieuw kindknooppunt met de opgegeven entiteit gekoppeld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| entity | Entity | Standaard entiteit gekoppeld aan het knooppunt |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode(nodeName, entity) | Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | De naam van het nieuwe kindknooppunt |
| entity | Entity | Standaard entiteit gekoppeld aan het knooppunt |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode(nodeName, entity, material) | Maak een nieuw kindknooppunt met de opgegeven knooppuntnaam, en koppel de gespecificeerde entiteit en een materiaal |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | De naam van het nieuwe kindknooppunt |
| entity | Entity | Standaard entiteit gekoppeld aan het knooppunt |
| material | Materiaal | Het materiaal gekoppeld aan het knooppunt |

 **Result:**
Node


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Naam | Beschrijving |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Evalueer de globale transformatie, al dan niet inclusief de geometrische transformatie. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| withGeometricTransform | boolean | Of de geometrische transformatie nodig is. |

 **Result:**
Matrix4


---


### getChild{#getChild}

| Naam | Beschrijving |
| --- | --- |
| getChild(index) | Haalt het kindknooppunt op op de opgegeven index. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| index | Number | Index. |

 **Result:**
Node


---


### getChild{#getChild}

| Naam | Beschrijving |
| --- | --- |
| getChild(nodeName) | Haalt het kindknooppunt op met de opgegeven naam. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | De naam van het kind om te vinden. |

 **Result:**
Node


---


### accept{#accept}

| Naam | Beschrijving |
| --- | --- |
| accept(visitor) | Doorloopt alle afstammingsknooppunten (inclusief het huidige knooppunt) en roept de visitor aan met het knooppunt. Visitor kan de doorloop onderbreken door false te retourneren. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| visitor | NodeVisitor | Visitor callback om het knooppunt te bezoeken |

 **Result:**
boolean


---


### toString{#toString}

| Naam | Beschrijving |
| --- | --- |
| toString() | Haalt de tekenreeksrepresentatie van dit knooppunt op. |

 **Result:**
String


---


### getBoundingBox{#getBoundingBox}

| Naam | Beschrijving |
| --- | --- |
| getBoundingBox() | Bereken het begrenzingsvak van het knooppunt |

 **Result:**
BoundingBox


---


### addEntity{#addEntity}

| Naam | Beschrijving |
| --- | --- |
| addEntity(entity) | Voeg een entiteit toe aan het knooppunt. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| entity | Entity | De entiteit die aan het knooppunt moet worden gekoppeld |

 **Result:**
BoundingBox


---


### addChildNode{#addChildNode}

| Naam | Beschrijving |
| --- | --- |
| addChildNode(node) | Voeg een kindknooppunt toe aan dit knooppunt |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| node | Node | Het kindknooppunt dat moet worden gekoppeld |

 **Result:**
BoundingBox


---


### selectSingleObject{#selectSingleObject}

| Naam | Beschrijving |
| --- | --- |
| selectSingleObject(path) | Selecteer een enkel object onder het huidige knooppunt met behulp van XPath-achtige querysyntaxis. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| pat | String | null |

 **Result:**
Object


---


### selectObjects{#selectObjects}

| Naam | Beschrijving |
| --- | --- |
| selectObjects(path) | Selecteer meerdere objecten onder het huidige knooppunt met behulp van XPath-achtige querysyntaxis. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| pat | String | null |

 **Result:**
0, Culture=neutral, PublicKeyToken=b77a5c561934e089]]


---


### removeProperty{#removeProperty}

| Naam | Beschrijving |
| --- | --- |
| removeProperty(property) | Verwijdert een dynamische eigenschap. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | Eigenschap | Welke eigenschap moet worden verwijderd |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Naam | Beschrijving |
| --- | --- |
| removeProperty(property) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Naam | Beschrijving |
| --- | --- |
| getProperty(property) | Haal de waarde van de opgegeven eigenschap op |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | String | Naam van eigenschap |

 **Result:**
Object


---


### setProperty{#setProperty}

| Naam | Beschrijving |
| --- | --- |
| setProperty(property, value) | Stelt de waarde van de opgegeven eigenschap in |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | String | Naam van eigenschap |
| value | Object | De waarde van de eigenschap |

 **Result:**
Object


---


### findProperty{#findProperty}

| Naam | Beschrijving |
| --- | --- |
| findProperty(propertyName) | Zoekt de eigenschap. Het kan een dynamische eigenschap (Gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap(Geadresseerd aan de hand van zijn naam) |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| propertyName | String | Naam van eigenschap. |

 **Result:**
Eigenschap


---



