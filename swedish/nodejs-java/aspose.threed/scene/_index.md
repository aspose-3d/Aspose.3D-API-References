---
title: "Scene"
second_title: "Aspose.3D för Node.js via Java API-referens"
description: 
type: docs

url: /sv/nodejs-java/aspose.threed/scene/
---
## Scene class

En scen är ett top‑nivåobjekt som innehåller noder, geometrier, material, texturer, animationer, poser, under‑scener etc.  Scenen kan ha under‑scener, fungerar som stöd för flera dokument i filer som collada/blender/fbx.  Nodhierarkin kan nås via RootNodeLibrary som används för att hålla en referens till oanslutna objekt under serialisering (som metadata eller anpassade objekt) så att den kan användas som ett bibliotek.


## Metoder

### constructor{#constructor}

| Namn | Beskrivning |
| --- | --- |
| constructor() | Initierar en ny instans av Scene-klassen. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload(entity) | Initierar en ny instans av Scene-klassen med en entity fäst vid en ny nod. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| entitet | Entitet | Den initiala entity som fästes vid scene |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload2(parentScene, name) | Initierar en ny instans av Scene-klassen som en delscen. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| parentScene | Scene | Den överordnade scenen. |
| name | Sträng | Scenens namn. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Namn | Beskrivning |
| --- | --- |
| constructor_overload3(fileName) | Initierar en ny instans av Scene-klassen och öppnar filen omedelbart. Detta är en föråldrad konstruktor, vänligen använd #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filens namn att öppna. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Namn | Beskrivning |
| --- | --- |
| getSubScenes() | Hämtar alla delscener |

 **Result:**



---


### getLibrary{#getLibrary}

| Namn | Beskrivning |
| --- | --- |
| getLibrary() | Objekt som inte används direkt i scenhierarkin kan definieras i Library. Detta är användbart när du använder delscener och placerar återanvändbara komponenter under delscener. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Namn | Beskrivning |
| --- | --- |
| getAnimationClips() | Hämtar alla AnimationClip som definierats i scenen. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Namn | Beskrivning |
| --- | --- |
| getCurrentAnimationClip() | Hämtar eller anger den aktiva AnimationClip |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Namn | Beskrivning |
| --- | --- |
| setCurrentAnimationClip(value) | Hämtar eller anger den aktiva AnimationClip |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Namn | Beskrivning |
| --- | --- |
| getAssetInfo() | Hämtar eller anger top‑nivå tillgångsinformation. Dokumentinformationen. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Namn | Beskrivning |
| --- | --- |
| setAssetInfo(value) | Hämtar eller anger top‑nivå tillgångsinformation. Dokumentinformationen. |

 **Result:**



---


### getPoses{#getPoses}

| Namn | Beskrivning |
| --- | --- |
| getPoses() | Hämtar alla Pose som används i denna scen. Poseerna. |

 **Result:**



---


### getRootNode{#getRootNode}

| Namn | Beskrivning |
| --- | --- |
| getRootNode() | Hämtar rot‑noden i scenen. Rot‑noden. |

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


### getAnimationClip{#getAnimationClip}

| Namn | Beskrivning |
| --- | --- |
| getAnimationClip(name) | Hämtar en namngiven AnimationClip |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Den |

 **Result:**
AnimationClip


---


### clear{#clear}

| Namn | Beskrivning |
| --- | --- |
| clear() | Rensar scenens innehåll och återställer standardinställningarna. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Namn | Beskrivning |
| --- | --- |
| createAnimationClip(name) | En förkortad funktion för att skapa och registrera AnimationClip. Den första AnimationClip kommer att tilldelas CurrentAnimationClip. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| name | Sträng | Namnet på animation clip. |

 **Result:**
AnimationClip


---


### open{#open}

| Namn | Beskrivning |
| --- | --- |
| open(fileName, options) | Öppnar scenen från angiven sökväg med angivet filformat. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamn. |
| alternativ | LoadOptions | Mer detaljerad konfiguration för att öppna strömmen. |

 **Result:**
AnimationClip


---


### open{#open}

| Namn | Beskrivning |
| --- | --- |
| open(fileName) | Öppnar scenen från angiven sökväg |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamn. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Namn | Beskrivning |
| --- | --- |
| fromFile(fileName) | Öppnar scenen från angiven sökväg |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamn. |

 **Result:**
AnimationClip


---


### save{#save}

| Namn | Beskrivning |
| --- | --- |
| save(fileName) | Sparar scenen till angiven sökväg med angivet filformat. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamn. |

 **Result:**
AnimationClip


---


### save{#save}

| Namn | Beskrivning |
| --- | --- |
| save(fileName, format) | Sparar scenen till angiven sökväg med angivet filformat. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamn. |
| format | Filformat | Format. |

 **Result:**
AnimationClip


---


### save{#save}

| Namn | Beskrivning |
| --- | --- |
| save(fileName, options) | Sparar scenen till angiven sökväg med angivet filformat. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| fileName | Sträng | Filnamn. |
| alternativ | SaveOptions | Mer detaljerad konfiguration för att spara strömmen. |

 **Result:**
AnimationClip


---


### render{#render}

| Namn | Beskrivning |
| --- | --- |
| render(camera, fileName) | Rendera scenen till en extern fil från den angivna kamerans perspektiv. Standardutdata är 1024x768 och utdataformatet är png. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| kamera | Kamera | Från vilken kameras perspektiv scenen ska renderas |
| fileName | Sträng | Filnamnet på utdatafilen |

 **Result:**
AnimationClip


---


### render{#render}

| Namn | Beskrivning |
| --- | --- |
| render(camera, fileName, size, format) | Rendera scenen till en extern fil från den angivna kamerans perspektiv. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| kamera | Kamera | Från vilken kameras perspektiv scenen ska renderas |
| fileName | Sträng | Filnamnet på utdatafilen |
| storlek | Vector2 | Storleken på den slutliga renderade bilden |
| format | Sträng | Bildformatet för utdatafilen |

 **Result:**
AnimationClip


---


### render{#render}

| Namn | Beskrivning |
| --- | --- |
| render(camera, fileName, size, format, options) | Rendera scenen till en extern fil från den angivna kamerans perspektiv. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| kamera | Kamera | Från vilken kameras perspektiv scenen ska renderas |
| fileName | Sträng | Filnamnet på utdatafilen |
| storlek | Vector2 | Storleken på den slutliga renderade bilden |
| format | Sträng | Bildformatet för utdatafilen |
| alternativ | ImageRenderOptions | Alternativet för att anpassa vissa interna inställningar. |

 **Result:**
AnimationClip


---


### render{#render}

| Namn | Beskrivning |
| --- | --- |
| render(camera, bitmap) | Rendera scenen till bitmap från den givna kamerans perspektiv. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| kamera | Kamera | Från vilken kameras perspektiv scenen ska renderas |
| bitmap | TextureData | Mål för det renderade resultatet |

 **Result:**
AnimationClip


---


### render{#render}

| Namn | Beskrivning |
| --- | --- |
| render(camera, bitmap, options) | Rendera scenen till bitmap från den givna kamerans perspektiv. |

 **Parameters:**

| Namn | Typ | Beskrivning |
| --- | --- | --- |
| kamera | Kamera | Från vilken kameras perspektiv scenen ska renderas |
| bitmap | TextureData | Mål för det renderade resultatet |
| alternativ | ImageRenderOptions | Alternativet för att anpassa vissa interna inställningar. |

 **Result:**
AnimationClip


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



