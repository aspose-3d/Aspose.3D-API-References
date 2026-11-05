---
title: "Scene"
second_title: "Aspose.3D voor Node.js via Java API-referentie"
description: 
type: docs

url: /nl/nodejs-java/aspose.threed/scene/
---
## Scene class

Een scène is een object op het hoogste niveau dat de knooppunten, geometrieën, materialen, texturen, animaties, poses, sub‑scènes enzovoort bevat.  Een scène kan sub‑scènes hebben, fungeert als ondersteuning voor meerdere documenten in bestanden zoals collada/blender/fbx.  De knooppunthierarchie kan worden benaderd via RootNodeLibrary, die wordt gebruikt om een referentie naar niet‑gekoppelde objecten tijdens serialisatie (zoals metadata of aangepaste objecten) bij te houden, zodat deze als bibliotheek kan worden gebruikt.


## Methoden

### constructor{#constructor}

| Naam | Beschrijving |
| --- | --- |
| constructor() | Initialiseert een nieuw exemplaar van de Scene-klasse. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload(entity) | Initialiseert een nieuw exemplaar van de Scene-klasse met een entiteit die is gekoppeld aan een nieuw knooppunt. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| entiteit | Entiteit | De initiële entiteit die aan de scene is gekoppeld |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload2(parentScene, name) | Initialiseert een nieuw exemplaar van de Scene-klasse als een subscene. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| parentScene | Scene | De bovenliggende scene. |
| name | String | Naam van de scene. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Naam | Beschrijving |
| --- | --- |
| constructor_overload3(fileName) | Initialiseert een nieuw exemplaar van de Scene-klasse en opent het bestand onmiddellijk. Dit is een verouderde constructor, gebruik alstublieft #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Naam van het te openen bestand. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Naam | Beschrijving |
| --- | --- |
| getSubScenes() | Haalt alle subscènes op |

 **Result:**



---


### getLibrary{#getLibrary}

| Naam | Beschrijving |
| --- | --- |
| getLibrary() | Objecten die niet direct worden gebruikt in de scene-hiërarchie kunnen worden gedefinieerd in de Bibliotheek. Dit is handig wanneer je subscènes gebruikt en herbruikbare componenten onder subscènes plaatst. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Naam | Beschrijving |
| --- | --- |
| getAnimationClips() | Haalt alle AnimationClip op die in de scene zijn gedefinieerd. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Naam | Beschrijving |
| --- | --- |
| getCurrentAnimationClip() | Haalt de actieve AnimationClip op of stelt deze in |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Naam | Beschrijving |
| --- | --- |
| setCurrentAnimationClip(value) | Haalt de actieve AnimationClip op of stelt deze in |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Naam | Beschrijving |
| --- | --- |
| getAssetInfo() | Haalt of stelt de top-level asset-informatie in. De documentinformatie. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Naam | Beschrijving |
| --- | --- |
| setAssetInfo(value) | Haalt of stelt de top-level asset-informatie in. De documentinformatie. |

 **Result:**



---


### getPoses{#getPoses}

| Naam | Beschrijving |
| --- | --- |
| getPoses() | Haalt alle Pose op die in deze scene worden gebruikt. De poses. |

 **Result:**



---


### getRootNode{#getRootNode}

| Naam | Beschrijving |
| --- | --- |
| getRootNode() | Haalt het root-knooppunt van de scène op. Het root-knooppunt. |

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


### getAnimationClip{#getAnimationClip}

| Naam | Beschrijving |
| --- | --- |
| getAnimationClip(name) | Haalt een benoemde AnimationClip op |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | De |

 **Result:**
AnimationClip


---


### clear{#clear}

| Naam | Beschrijving |
| --- | --- |
| clear() | Verwijdert de inhoud van de scène en herstelt de standaardinstellingen. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Naam | Beschrijving |
| --- | --- |
| createAnimationClip(name) | Een verkorte functie om de AnimationClip te maken en te registreren. De eerste AnimationClip wordt toegewezen aan de CurrentAnimationClip |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| name | String | Naam van de animatieclip |

 **Result:**
AnimationClip


---


### open{#open}

| Naam | Beschrijving |
| --- | --- |
| open(fileName, options) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Bestandsnaam. |
| options | LoadOptions | Gedetailleerdere configuratie om de stream te openen. |

 **Result:**
AnimationClip


---


### open{#open}

| Naam | Beschrijving |
| --- | --- |
| open(fileName) | Opent de scène vanaf het opgegeven pad |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Bestandsnaam. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Naam | Beschrijving |
| --- | --- |
| fromFile(fileName) | Opent de scène vanaf het opgegeven pad |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Bestandsnaam. |

 **Result:**
AnimationClip


---


### save{#save}

| Naam | Beschrijving |
| --- | --- |
| save(fileName) | Slaat de scène op naar het opgegeven pad met het gespecificeerde bestandsformaat. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Bestandsnaam. |

 **Result:**
AnimationClip


---


### save{#save}

| Naam | Beschrijving |
| --- | --- |
| save(fileName, format) | Slaat de scène op naar het opgegeven pad met het gespecificeerde bestandsformaat. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Bestandsnaam. |
| format | FileFormat | Formaat. |

 **Result:**
AnimationClip


---


### save{#save}

| Naam | Beschrijving |
| --- | --- |
| save(fileName, options) | Slaat de scène op naar het opgegeven pad met het gespecificeerde bestandsformaat. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| fileName | String | Bestandsnaam. |
| options | SaveOptions | Gedetailleerdere configuratie om de stream op te slaan. |

 **Result:**
AnimationClip


---


### render{#render}

| Naam | Beschrijving |
| --- | --- |
| render(camera, fileName) | Render de scène naar een extern bestand vanuit het perspectief van de opgegeven camera. De standaard uitvoergrootte is 1024x768 en het uitvoerformaat is png |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| camera | Camera | Vanuit welk camera-perspectief de scène moet worden gerenderd |
| fileName | String | De bestandsnaam van het uitvoerbestand |

 **Result:**
AnimationClip


---


### render{#render}

| Naam | Beschrijving |
| --- | --- |
| render(camera, fileName, size, format) | Render de scène naar een extern bestand vanuit het perspectief van de opgegeven camera. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| camera | Camera | Vanuit welk camera-perspectief de scène moet worden gerenderd |
| fileName | String | De bestandsnaam van het uitvoerbestand |
| grootte | Vector2 | De grootte van de uiteindelijk gerenderde afbeelding |
| format | String | Het afbeeldingsformaat van het uitvoerbestand |

 **Result:**
AnimationClip


---


### render{#render}

| Naam | Beschrijving |
| --- | --- |
| render(camera, fileName, size, format, options) | Render de scène naar een extern bestand vanuit het perspectief van de opgegeven camera. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| camera | Camera | Vanuit welk camera-perspectief de scène moet worden gerenderd |
| fileName | String | De bestandsnaam van het uitvoerbestand |
| grootte | Vector2 | De grootte van de uiteindelijk gerenderde afbeelding |
| format | String | Het afbeeldingsformaat van het uitvoerbestand |
| options | ImageRenderOptions | De optie om enkele interne instellingen aan te passen. |

 **Result:**
AnimationClip


---


### render{#render}

| Naam | Beschrijving |
| --- | --- |
| render(camera, bitmap) | Render de scène naar een bitmap vanuit het perspectief van de opgegeven camera. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| camera | Camera | Vanuit welk camera-perspectief de scène moet worden gerenderd |
| bitmap | TextureData | Doel van het gerenderde resultaat |

 **Result:**
AnimationClip


---


### render{#render}

| Naam | Beschrijving |
| --- | --- |
| render(camera, bitmap, options) | Render de scène naar een bitmap vanuit het perspectief van de opgegeven camera. |

 **Parameters:**

| Naam | Type | Beschrijving |
| --- | --- | --- |
| camera | Camera | Vanuit welk camera-perspectief de scène moet worden gerenderd |
| bitmap | TextureData | Doel van het gerenderde resultaat |
| options | ImageRenderOptions | De optie om enkele interne instellingen aan te passen. |

 **Result:**
AnimationClip


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



