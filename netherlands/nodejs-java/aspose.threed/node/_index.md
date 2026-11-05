---
title: "Node"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/node/
---
## Node class

Stelt een element in de scenegraph voor.  Een scenegraph is een boom van Node-objecten. De boombeheerservices zijn zelfvoorzienend in deze klasse.  Merk op dat de Aspose.3D SDK de geldigheid van de geconstrueerde scenegraph niet test. Het is de verantwoordelijkheid van de aanroeper om ervoor te zorgen dat er geen cyclische grafen worden gegenereerd in een node-hiërarchie.  Naast het boombeheer definieert deze klasse alle eigenschappen die nodig zijn om de positie van het object in de scène te beschrijven. Deze informatie omvat de basis Translation-, Rotation- en Scaling-eigenschappen en de meer geavanceerde opties voor pivots, limits en IK-joint-attributen zoals stiffness en dampening.  Wanneer het voor het eerst wordt aangemaakt, is het Node-object "empty" (d.w.z.: het is een object zonder enige grafische weergave dat alleen de positiebepaling bevat). In deze toestand kan het worden gebruikt om ouders in de node-boomstructuur te vertegenwoordigen, maar niet veel meer. Het normale gebruik van dit type objecten is om ze een entity toe te voegen die de node specialiseert (zie de "Entity").  De entity is een object op zich en is verbonden met de Node. Dit betekent ook dat dezelfde entity kan worden gedeeld tussen meerdere nodes. Camera, Light, Mesh, enz... zijn allemaal entities en ze zijn allemaal afgeleid van de basisklasse Entity.


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
| entiteit | Entiteit | Standaard entiteit. |

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
| getAssetInfo() | Assetinformatie per node |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Naam | Beschrijving |
| --- | --- |
| setAssetInfo(value) | Assetinformatie per node |

 **Result:**



---


### getVisible{#getVisible}

| Naam | Beschrijving |
| --- | --- |
| getVisible() | Krijgt of stelt in om de node te tonen |

 **Result:**



---


### setVisible{#setVisible}

| Naam | Beschrijving |
| --- | --- |
| setVisible(value) | Krijgt of stelt in om de node te tonen |

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
| getMaterial() | Haalt op of stelt het eerste materiaal in dat aan dit knooppunt is gekoppeld; bij instellen worden andere materialen gewist. Het materiaal. |

 **Result:**



---


### setMaterial{#setMaterial}

| Naam | Beschrijving |
| --- | --- |
| setMaterial(value) | Haalt op of stelt het eerste materiaal in dat aan dit knooppunt is gekoppeld; bij instellen worden andere materialen gewist. Het materiaal. |

 **Result:**



---


### getParentNode{#getParentNode}

| Naam | Beschrijving |
| --- | --- |
| getParentNode() | Haalt op of stelt het bovenliggende knooppunt in. Het bovenliggende knooppunt. |

 **Result:**



---


### setParentNode{#setParentNode}

| Naam | Beschrijving |
| --- | --- |
| setParentNode(value) | Haalt op of stelt het bovenliggende knooppunt in. Het bovenliggende knooppunt. |

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
| getScene() | Haalt de scène op waartoe dit object behoort |

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
| getProperties() | Haalt de verzameling van alle eigenschappen op. |

 **Result:**



---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode() | Maakt een onderliggend knooppunt aan |

 **Result:**
Node


---


### merge{#merge}

| Naam | Beschrijving |
| --- | --- |
| merge(node) | Ontkoppel alles onder het knooppunt en koppel het aan het huidige knooppunt. |

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
| createChildNode(nodeName) | Maak een nieuw onderliggend knooppunt met de opgegeven knooppuntnaam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | De naam van het nieuwe onderliggende knooppunt |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode(entity) | Maak een nieuw onderliggend knooppunt met de opgegeven entiteit gekoppeld |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| entiteit | Entiteit | Standaard entiteit gekoppeld aan het knooppunt |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode(nodeName, entity) | Maak een nieuw onderliggend knooppunt met de opgegeven knooppuntnaam |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | De naam van het nieuwe onderliggende knooppunt |
| entiteit | Entiteit | Standaard entiteit gekoppeld aan het knooppunt |

 **Result:**
Node


---


### createChildNode{#createChildNode}

| Naam | Beschrijving |
| --- | --- |
| createChildNode(nodeName, entity, material) | Maak een nieuw onderliggend knooppunt met de opgegeven knooppuntnaam en koppel de gespecificeerde entiteit en een materiaal |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| nodeName | String | De naam van het nieuwe onderliggende knooppunt |
| entiteit | Entiteit | Standaard entiteit gekoppeld aan het knooppunt |
| material | Materiaal | Het materiaal dat aan het knooppunt is gekoppeld |

 **Result:**
Node


---


### evaluateGlobalTransform{#evaluateGlobalTransform}

| Naam | Beschrijving |
| --- | --- |
| evaluateGlobalTransform(withGeometricTransform) | Evalueer de globale transformatie, al dan niet de geometrische transformatie opnemen. |

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
| index | Nummer | Index. |

 **Result:**
Node


---


### getChild{#getChild}

| Naam | Beschrijving |
| --- | --- |
| getChild(nodeName) | Haalt het kindknooppunt op met de opgegeven naam |

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
| accept(visitor) | Doorloopt alle afstammingsknooppunten (inclusief het huidige knooppunt) en roept de bezoeker aan met het knooppunt. De bezoeker kan de doorloop onderbreken door false te retourneren. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| visitor | NodeVisitor | Bezoeker-callback om het knooppunt te bezoeken |

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
| getBoundingBox() | Bereken de omhullende rechthoek van het knooppunt |

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
| entiteit | Entiteit | De entiteit die aan het knooppunt moet worden gekoppeld |

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
| selectSingleObject(path) | Selecteer één enkel object onder het huidige knooppunt met XPath-achtige querysyntaxis. |

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
| selectObjects(path) | Selecteer meerdere objecten onder het huidige knooppunt met XPath-achtige querysyntaxis. |

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
| property | Eigenschap | Welke eigenschap moet worden verwijderd |

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
| eigenschap | String | null |

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
| property | String | Naam van eigenschap |

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
| property | String | Naam van eigenschap |
| waarde | Object | De waarde van de eigenschap |

 **Result:**
Object


---


### findProperty{#findProperty}

| Naam | Beschrijving |
| --- | --- |
| findProperty(propertyName) | Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (Created by CreateDynamicProperty/SetProperty) of een native eigenschap (Identified by its name) |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| propertyName | String | Naam van eigenschap. |

 **Result:**
Eigenschap


---



