---
title: Scen
second_title: Aspose.3D for Java API-referens
description: 
type: docs
weight: 161
url: /sv/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Initierar en ny instans av klassen [Scene](../../com.aspose.threed/scene) med en entitet kopplad till en ny nod. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Initierar en ny instans av klassen [Scene](../../com.aspose.threed/scene) som en delscen. |
| [Scene()](#Scene--) | Initierar en ny instans av klassen [Scene](../../com.aspose.threed/scene). |
## Fält

| Fält | Beskrivning |
| --- | --- |
| [VERSION](#VERSION) | Hämtar den aktuella versionen. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clear()](#clear--) | Rensar scenens innehåll och återställer standardinställningarna. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | En förkortad funktion för att skapa och registrera [AnimationClip](../../com.aspose.threed/animationclip) Det första [AnimationClip](../../com.aspose.threed/animationclip) kommer att tilldelas till [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Öppnar scenen från angiven sökväg. |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven sökväg. |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Öppnar scenen från angiven sökväg med angivet filformat. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven sökväg med angivet filformat. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Öppnar scenen från angiven sökväg med angivet filformat. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven sökväg med angivet filformat. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Öppnar scenen från angiven ström. |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström. |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Öppnar scenen från angiven ström med angivet filformat. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström med angivet filformat. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Öppnar scenen från angiven ström med angiven IO-konfiguration. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström med angiven IO-konfiguration. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Öppnar scenen från angiven ström. |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström. |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Öppnar scenen från angiven ström med angivet filformat. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström med angivet filformat. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Öppnar scenen från angiven ström med angiven IO-konfiguration. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström med angiven IO-konfiguration. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Hämtar en namngiven [AnimationClip](../../com.aspose.threed/animationclip) |
| [getAnimationClips()](#getAnimationClips--) | Hämtar alla [AnimationClip](../../com.aspose.threed/animationclip) som definierats i scenen. |
| [getAssetInfo()](#getAssetInfo--) | Hämtar information om tillgång på översta nivån. |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Hämtar den aktiva [AnimationClip](../../com.aspose.threed/animationclip) |
| [getLibrary()](#getLibrary--) | Objekt som inte används direkt i scenhierarkin kan definieras i Biblioteket. |
| [getName()](#getName--) | Hämtar namnet. |
| [getPoses()](#getPoses--) | Hämtar alla [Pose](../../com.aspose.threed/pose) som används i denna scen. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getRootNode()](#getRootNode--) | Hämtar rotknuten i scenen. |
| [getScene()](#getScene--) | Hämtar scenen som detta objekt tillhör |
| [getSubScenes()](#getSubScenes--) | Hämtar alla delscener. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Öppnar scenen från angiven ström. |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström. |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Öppnar scenen från angiven ström med angivet filformat. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström med angivet filformat. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Öppnar scenen från angiven ström med angiven IO-konfiguration. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström med angiven IO-konfiguration. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Öppnar scenen från angiven ström. |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström. |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Öppnar scenen från angiven ström med angivet filformat. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström med angivet filformat. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Öppnar scenen från angiven ström med angiven IO-konfiguration. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven ström med angiven IO-konfiguration. |
| [open(String fileName)](#open-java.lang.String-) | Öppnar scenen från angiven sökväg. |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven sökväg. |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Öppnar scenen från angiven sökväg med angivet filformat. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven sökväg med angivet filformat. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Öppnar scenen från angiven sökväg med angivet filformat. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Öppnar scenen från angiven sökväg med angivet filformat. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Rendera scenen till en bitmap från den angivna kamerans perspektiv. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Rendera scenen till en bitmap från den angivna kamerans perspektiv. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Rendera scenen till en extern fil från den angivna kamerans perspektiv. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Rendera scenen till en extern fil från den angivna kamerans perspektiv. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Rendera scenen till en extern fil från den angivna kamerans perspektiv. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Sparar scenen till en ström med angivet filformat. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Sparar scenen till en ström med angivet filformat. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Sparar scenen till en ström med angivet filformat. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Sparar scenen till en ström med angivet filformat. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Sparar scenen till en ström med angivet filformat. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Sparar scenen till en ström med angivet filformat. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Sparar scenen till en ström med angivet filformat. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Sparar scenen till en ström med angivet filformat. |
| [save(String fileName)](#save-java.lang.String-) | Sparar scenen till angiven sökväg med angivet filformat. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Sparar scenen till angiven sökväg med angivet filformat. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Sparar scenen till angiven sökväg med angivet filformat. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Sparar scenen till angiven sökväg med angivet filformat. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Sparar scenen till angiven sökväg med angivet filformat. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Ställer in top‑nivå tillgångsinformation |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Ställer in den aktiva [AnimationClip](../../com.aspose.threed/animationclip) |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Initierar en ny instans av klassen [Scene](../../com.aspose.threed/scene) med en entitet kopplad till en ny nod.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | Den initiala entiteten som är fäst vid scenen **Exempel:** Följande kod visar hur man skapar en [getScene](../../com.aspose.threed/scene\\#getScene) direkt från en [Entity](../../com.aspose.threed/entity): |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Initierar en ny instans av klassen [Scene](../../com.aspose.threed/scene) som en delscen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | Den överordnade scenen. |
| namn | java.lang.String | Scenens namn. |

### Scene() {#Scene--}
```
public Scene()
```


Initierar en ny instans av klassen [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


Hämtar den aktuella versionen.

### clear() {#clear--}
```
public void clear()
```


Rensar scenens innehåll och återställer standardinställningarna.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


En förkortad funktion för att skapa och registrera [AnimationClip](../../com.aspose.threed/animationclip) Det första [AnimationClip](../../com.aspose.threed/animationclip) kommer att tilldelas till [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Animationsklippets namn |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | java.lang.String | Egenskapsnamn. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Öppnar scenen från angiven sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Öppnar scenen från angiven sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Öppnar scenen från angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Öppnar scenen från angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Öppnar scenen från angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Öppnar scenen från angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Öppnar scenen från angiven ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Öppnar scenen från angiven ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Öppnar scenen från angiven ström med angiven IO-konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström med angiven IO-konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Öppnar scenen från angiven ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. **Exempel:** Följande kod visar hur man skapar en scen från en ström med en cancellation token source |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften **Exempel:** Följande kod visar hur man skapar en scen från en ström med en cancellation token source |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


Öppnar scenen från angiven ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. **Exempel:** Följande kod visar hur man skapar en scen från en ström |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften **Exempel:** Följande kod visar hur man skapar en scen från en ström |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


Öppnar scenen från angiven ström med angiven IO-konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. **Exempel:** Följande kod visar hur man skapar en scen från en ström med laddningsalternativ |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström med angiven IO-konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften **Exempel:** Följande kod visar hur man skapar en scen från en ström med laddningsalternativ |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


Hämtar en namngiven [AnimationClip](../../com.aspose.threed/animationclip)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| name | java.lang.String | Namnet på [AnimationClip](../../com.aspose.threed/animationclip) att slå upp |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Hämtar alla [AnimationClip](../../com.aspose.threed/animationclip) som definierats i scenen.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - alla [AnimationClip](../../com.aspose.threed/animationclip) som definierats i scenen.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Hämtar information om tillgång på översta nivån.

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


Hämtar den aktiva [AnimationClip](../../com.aspose.threed/animationclip)

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Objekt som inte används direkt i scenhierarkin kan definieras i Library. Detta är användbart när du använder delscener och placerar återanvändbara komponenter under delscener.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - Objekt som inte används direkt i scenhierarkin kan definieras i Library. Detta är användbart när du använder delscener och placerar återanvändbara komponenter under delscener.
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Hämtar alla [Pose](../../com.aspose.threed/pose) som används i denna scen.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - alla [Pose](../../com.aspose.threed/pose) som används i denna scen.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Hämtar samlingen av alla egenskaper.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Hämta värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |

**Returns:**
java.lang.Object - Värdet på den hittade egenskapen
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Hämtar rotknuten i scenen.

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


Hämtar scenen som detta objekt tillhör

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Hämtar alla delscener.

**Returns:**
java.util.List<com.aspose.threed.Scene> - alla delscener
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


Öppnar scenen från angiven ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Öppnar scenen från angiven ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Öppnar scenen från angiven ström med angiven IO-konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström med angiven IO-konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Öppnar scenen från angiven ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. **Exempel:** Följande kod visar hur man öppnar en scen från en ström |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för inläsningsuppgiften **Example:** Följande kod visar hur man öppnar en scen från ström med en avbokningstoken |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


Öppnar scenen från angiven ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. **Example:** Följande kod visar hur man öppnar en scen från ström |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för inläsningsuppgiften **Example:** Följande kod visar hur man öppnar en scen från ström |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


Öppnar scenen från angiven ström med angiven IO-konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. **Example:** Följande kod visar hur man öppnar en scen från ström med extra inläsningsalternativ |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


Öppnar scenen från angiven ström med angiven IO-konfiguration.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för inläsningsuppgiften **Example:** Följande kod visar hur man öppnar en scen från ström med extra inläsningsalternativ |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


Öppnar scenen från angiven sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Öppnar scenen från angiven sökväg.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Öppnar scenen från angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Öppnar scenen från angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Filformat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Öppnar scenen från angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Öppnar scenen från angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Mer detaljerad konfiguration för att öppna strömmen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken till laddningsuppgiften |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Tar bort en dynamisk egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Ta bort den angivna egenskapen identifierad med namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Rendera scenen till en bitmap från den angivna kamerans perspektiv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Från vilken kameras perspektiv scenen ska renderas |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Mål för det renderade resultatet |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Rendera scenen till en bitmap från den angivna kamerans perspektiv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Från vilken kameras perspektiv scenen ska renderas |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Mål för det renderade resultatet |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | Alternativet för att anpassa vissa interna inställningar. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Rendera scenen till en extern fil från angivet kameraperspektiv. Standardutdata storlek är 1024x768 och utdataformat är png

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Från vilken kameras perspektiv scenen ska renderas |
| fileName | java.lang.String | Filnamnet för utdatafilen |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Rendera scenen till en extern fil från den angivna kamerans perspektiv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Från vilken kameras perspektiv scenen ska renderas |
| fileName | java.lang.String | Filnamnet för utdatafilen |
| size | [Vector2](../../com.aspose.threed/vector2) | Storleken på den slutgiltiga renderade bilden |
| format | java.lang.String | Bildformatet för utdatafilen |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Rendera scenen till en extern fil från den angivna kamerans perspektiv.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Från vilken kameras perspektiv scenen ska renderas |
| fileName | java.lang.String | Filnamnet för utdatafilen |
| size | [Vector2](../../com.aspose.threed/vector2) | Storleken på den slutgiltiga renderade bilden |
| format | java.lang.String | Bildformatet för utdatafilen |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | Alternativet för att anpassa vissa interna inställningar. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Sparar scenen till en ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Sparar scenen till en ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för sparuppgiften |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Sparar scenen till en ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Mer detaljerad konfiguration för att spara strömmen. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Sparar scenen till en ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Mer detaljerad konfiguration för att spara strömmen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för sparuppgiften |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Sparar scenen till en ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Format. **Example:** Följande kod visar hur man sparar scenen |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


Sparar scenen till en ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för sparuppgiften **Example:** Följande kod visar hur man sparar scenen |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


Sparar scenen till en ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Mer detaljerad konfiguration för att spara strömmen. **Example:** Följande kod visar hur man sparar scenen |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


Sparar scenen till en ström med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.OutputStream | Inmatningsström, användaren ansvarar för att stänga strömmen. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Mer detaljerad konfiguration för att spara strömmen. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för sparuppgiften **Example:** Följande kod visar hur man sparar scenen |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Sparar scenen till angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Sparar scenen till angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Sparar scenen till angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Format. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för sparuppgiften |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Sparar scenen till angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Mer detaljerad konfiguration för att spara strömmen. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Sparar scenen till angiven sökväg med angivet filformat.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | java.lang.String | Filnamn. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Mer detaljerad konfiguration för att spara strömmen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Avbokningstoken för sparuppgiften |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Ställer in top‑nivå tillgångsinformation

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nytt värde **Example:** Följande kod visar hur man läser programinformation från en FBX-fil: |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


Ställer in den aktiva [AnimationClip](../../com.aspose.threed/animationclip)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ställer in värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |
| värde | java.lang.Object | Värdet på egenskapen |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

