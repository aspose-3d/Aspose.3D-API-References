---
title: Scène
second_title: Aspose.3D for Java API-referentie
description: 
type: docs
weight: 161
url: /nl/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | Initialiseert een nieuw exemplaar van de klasse [Scene](../../com.aspose.threed/scene) met een entiteit gekoppeld aan een nieuw knooppunt. |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | Initialiseert een nieuw exemplaar van de klasse [Scene](../../com.aspose.threed/scene) als een subscene. |
| [Scene()](#Scene--) | Initialiseert een nieuw exemplaar van de klasse [Scene](../../com.aspose.threed/scene). |
## Velden

| Veld | Beschrijving |
| --- | --- |
| [VERSION](#VERSION) | Haalt de huidige releaseversie op |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clear()](#clear--) | Wis de scène-inhoud en herstel de standaardinstellingen. |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | Een verkorte functie om de [AnimationClip](../../com.aspose.threed/animationclip) te maken en te registreren. De eerste [AnimationClip](../../com.aspose.threed/animationclip) wordt toegewezen aan de [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Opent de scène vanaf het opgegeven pad |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | Opent de scène vanaf het opgegeven pad |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Opent de scène vanaf de opgegeven stream |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat. |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat. |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie. |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie. |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | Opent de scène vanaf de opgegeven stream |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat. |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat. |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie. |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie. |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | Haalt een benoemde [AnimationClip](../../com.aspose.threed/animationclip) op |
| [getAnimationClips()](#getAnimationClips--) | Haalt alle [AnimationClip](../../com.aspose.threed/animationclip) op die in de scène zijn gedefinieerd. |
| [getAssetInfo()](#getAssetInfo--) | Haalt de top‑niveau assetinformatie op |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | Haalt de actieve [AnimationClip](../../com.aspose.threed/animationclip) op |
| [getLibrary()](#getLibrary--) | Objecten die niet direct in de scène‑hiërarchie worden gebruikt, kunnen in de Bibliotheek worden gedefinieerd. |
| [getName()](#getName--) | Haalt de naam op. |
| [getPoses()](#getPoses--) | Haalt alle [Pose](../../com.aspose.threed/pose) op die in deze scène worden gebruikt. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getRootNode()](#getRootNode--) | Haalt het hoofd‑knooppunt van de scène op. |
| [getScene()](#getScene--) | Haalt de scène op waartoe dit object behoort |
| [getSubScenes()](#getSubScenes--) | Haalt alle sub‑scènes op |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | Opent de scène vanaf de opgegeven stream |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat. |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat. |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie. |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie. |
| [open(InputStream stream)](#open-java.io.InputStream-) | Opent de scène vanaf de opgegeven stream |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat. |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat. |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie. |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie. |
| [open(String fileName)](#open-java.lang.String-) | Opent de scène vanaf het opgegeven pad |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | Opent de scène vanaf het opgegeven pad |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat. |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | Render de scène naar een bitmap vanuit het perspectief van de opgegeven camera. |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | Render de scène naar een bitmap vanuit het perspectief van de opgegeven camera. |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | Render de scène naar een extern bestand vanuit het perspectief van de opgegeven camera. |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | Render de scène naar een extern bestand vanuit het perspectief van de opgegeven camera. |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | Render de scène naar een extern bestand vanuit het perspectief van de opgegeven camera. |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | Slaat de scène op naar een stream met het gespecificeerde bestandsformaat. |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Slaat de scène op naar een stream met het gespecificeerde bestandsformaat. |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | Slaat de scène op naar een stream met het gespecificeerde bestandsformaat. |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Slaat de scène op naar een stream met het gespecificeerde bestandsformaat. |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | Slaat de scène op naar een stream met het gespecificeerde bestandsformaat. |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Slaat de scène op naar een stream met het gespecificeerde bestandsformaat. |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | Slaat de scène op naar een stream met het gespecificeerde bestandsformaat. |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Slaat de scène op naar een stream met het gespecificeerde bestandsformaat. |
| [save(String fileName)](#save-java.lang.String-) | Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat. |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat. |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat. |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat. |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat. |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | Stelt de top-level asset-informatie in |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | Stelt de actieve [AnimationClip](../../com.aspose.threed/animationclip) in |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


Initialiseert een nieuw exemplaar van de klasse [Scene](../../com.aspose.threed/scene) met een entiteit gekoppeld aan een nieuw knooppunt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | De initiële entiteit die aan de scène is gekoppeld **Voorbeeld:** De volgende code laat zien hoe je een [getScene](../../com.aspose.threed/scene\#getScene) direct van een [Entity](../../com.aspose.threed/entity) maakt: |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


Initialiseert een nieuw exemplaar van de klasse [Scene](../../com.aspose.threed/scene) als een subscene.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | De bovenliggende scène. |
| naam | java.lang.String | Naam van de scène. |

### Scene() {#Scene--}
```
public Scene()
```


Initialiseert een nieuw exemplaar van de klasse [Scene](../../com.aspose.threed/scene).

### VERSION {#VERSION}
```
public static final String VERSION
```


Haalt de huidige releaseversie op

### clear() {#clear--}
```
public void clear()
```


Wis de scène-inhoud en herstel de standaardinstellingen.

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


Een verkorte functie om de [AnimationClip](../../com.aspose.threed/animationclip) te maken en te registreren. De eerste [AnimationClip](../../com.aspose.threed/animationclip) wordt toegewezen aan de [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam van de animatieclip |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap (geïdentificeerd op naam).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyName | java.lang.String | Eigenschapnaam. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


Opent de scène vanaf het opgegeven pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


Opent de scène vanaf het opgegeven pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


Opent de scène vanaf de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


Opent de scène vanaf de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


Opent de scène vanaf de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. **Voorbeeld:** De volgende code laat zien hoe je een scène maakt vanuit een stream met een annulerings-tokenbron |

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


Opent de scène vanaf de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak **Voorbeeld:** De volgende code laat zien hoe je een scène maakt vanuit een stream met een annulerings-tokenbron |

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


Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. **Voorbeeld:** De volgende code laat zien hoe je een scène maakt vanuit een stream |

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


Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak **Voorbeeld:** De volgende code laat zien hoe je een scène maakt vanuit een stream |

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


Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. **Voorbeeld:** De volgende code laat zien hoe je een scène maakt vanuit een stream met laadopties |

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


Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak **Voorbeeld:** De volgende code laat zien hoe je een scène maakt vanuit een stream met laadopties |

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


Haalt een benoemde [AnimationClip](../../com.aspose.threed/animationclip) op

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| name | java.lang.String | De naam van de [AnimationClip](../../com.aspose.threed/animationclip) om op te zoeken |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


Haalt alle [AnimationClip](../../com.aspose.threed/animationclip) op die in de scène zijn gedefinieerd.

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - alle [AnimationClip](../../com.aspose.threed/animationclip) gedefinieerd in de scène.
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


Haalt de top‑niveau assetinformatie op

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


Haalt de actieve [AnimationClip](../../com.aspose.threed/animationclip) op

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


Objecten die niet direct worden gebruikt in de scènehiërarchie kunnen worden gedefinieerd in de Bibliotheek. Dit is handig wanneer je sub‑scènes gebruikt en herbruikbare componenten onder sub‑scènes plaatst.

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - Objecten die niet direct worden gebruikt in de scènehiërarchie kunnen worden gedefinieerd in de Bibliotheek. Dit is handig wanneer je sub‑scènes gebruikt en herbruikbare componenten onder sub‑scènes plaatst.
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


Haalt alle [Pose](../../com.aspose.threed/pose) op die in deze scène worden gebruikt.

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - alle [Pose](../../com.aspose.threed/pose) gebruikt in deze scène.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Haalt de verzameling van alle eigenschappen op.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Haalt de waarde op van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |

**Returns:**
java.lang.Object - De waarde van de gevonden eigenschap
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


Haalt het hoofd‑knooppunt van de scène op.

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


Haalt de scène op waartoe dit object behoort

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


Haalt alle sub‑scènes op

**Returns:**
java.util.List<com.aspose.threed.Scene> - alle sub‑scènes
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


Opent de scène vanaf de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


Opent de scène vanaf de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


Opent de scène vanaf de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. **Voorbeeld:** De volgende code laat zien hoe je een scène opent vanuit een stream |

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


Opent de scène vanaf de opgegeven stream

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de laadtaak **Example:** De volgende code toont hoe een scène te openen vanuit een stream met een annulerings-token |

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


Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. **Example:** De volgende code toont hoe een scène te openen vanuit een stream |

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


Opent de scène vanaf de opgegeven stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de laadtaak **Example:** De volgende code toont hoe een scène te openen vanuit een stream |

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


Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. **Example:** De volgende code toont hoe een scène te openen vanuit een stream met extra laadopties |

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


Opent de scène vanaf de opgegeven stream met de gespecificeerde I/O-configuratie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.InputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de laadtaak **Example:** De volgende code toont hoe een scène te openen vanuit een stream met extra laadopties |

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


Opent de scène vanaf het opgegeven pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


Opent de scène vanaf het opgegeven pad

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Bestandsformaat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


Opent de scène vanaf het opgegeven pad met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | Gedetailleerdere configuratie om de stream te openen. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annuleringstoken voor de laadtaak |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Verwijder de opgegeven eigenschap geïdentificeerd op naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


Render de scène naar een bitmap vanuit het perspectief van de opgegeven camera.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Vanuit welk cameraperspectief de scène moet worden gerenderd |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Doel van het gerenderde resultaat |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


Render de scène naar een bitmap vanuit het perspectief van de opgegeven camera.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Vanuit welk cameraperspectief de scène moet worden gerenderd |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Doel van het gerenderde resultaat |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | De optie om enkele interne instellingen aan te passen. |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


Render de scène naar een extern bestand vanuit het opgegeven cameraperspectief. De standaard uitvoergrootte is 1024x768 en het uitvoerformaat is png

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Vanuit welk cameraperspectief de scène moet worden gerenderd |
| fileName | java.lang.String | De bestandsnaam van het uitvoerbestand |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


Render de scène naar een extern bestand vanuit het perspectief van de opgegeven camera.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Vanuit welk cameraperspectief de scène moet worden gerenderd |
| fileName | java.lang.String | De bestandsnaam van het uitvoerbestand |
| size | [Vector2](../../com.aspose.threed/vector2) | De grootte van de uiteindelijke gerenderde afbeelding |
| formaat | java.lang.String | Het afbeeldingsformaat van het uitvoerbestand |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


Render de scène naar een extern bestand vanuit het perspectief van de opgegeven camera.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | Vanuit welk cameraperspectief de scène moet worden gerenderd |
| fileName | java.lang.String | De bestandsnaam van het uitvoerbestand |
| size | [Vector2](../../com.aspose.threed/vector2) | De grootte van de uiteindelijke gerenderde afbeelding |
| formaat | java.lang.String | Het afbeeldingsformaat van het uitvoerbestand |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | De optie om enkele interne instellingen aan te passen. |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


Slaat de scène op naar een stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formaat. |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


Slaat de scène op naar een stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formaat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de opslagtaken |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


Slaat de scène op naar een stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Gedetailleerdere configuratie om de stream op te slaan. |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


Slaat de scène op naar een stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Gedetailleerdere configuratie om de stream op te slaan. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de opslagtaken |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


Slaat de scène op naar een stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | Formaat. **Example:** De volgende code toont hoe de scène op te slaan |

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


Slaat de scène op naar een stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formaat. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de opslagtaken **Example:** De volgende code toont hoe de scène op te slaan |

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


Slaat de scène op naar een stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | Gedetailleerdere configuratie om de stream op te slaan. **Example:** De volgende code toont hoe de scène op te slaan |

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


Slaat de scène op naar een stream met het gespecificeerde bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | Invoerstroom, de gebruiker is verantwoordelijk voor het sluiten van de stream. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Gedetailleerdere configuratie om de stream op te slaan. |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de opslagtaken **Example:** De volgende code toont hoe de scène op te slaan |

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


Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formaat. |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Formaat. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de opslagtaken |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Gedetailleerdere configuratie om de stream op te slaan. |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


Slaat de scène op naar het opgegeven pad met het opgegeven bestandsformaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileName | java.lang.String | Bestandsnaam. |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | Gedetailleerdere configuratie om de stream op te slaan. |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | Annulerings-token voor de opslagtaken |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


Stelt de top-level asset-informatie in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | Nieuwe waarde **Example:** De volgende code toont hoe de toepassingsinformatie uit een FBX-bestand te lezen: |

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


Stelt de actieve [AnimationClip](../../com.aspose.threed/animationclip) in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Stelt de waarde in van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |
| waarde | java.lang.Object | De waarde van de eigenschap |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

