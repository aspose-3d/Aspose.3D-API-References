---
title: EntityRenderer
second_title: Aspose.3D for Java API-referentie
description: Maak hiervan een subklasse om weergave voor verschillende soorten entiteiten te implementeren.
type: docs
weight: 53
url: /nl/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Maak hiervan een subklasse om weergave voor verschillende soorten entiteiten te implementeren.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Constructor van [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Constructor van [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [dispose()](#dispose--) | De entity renderer wordt verwijderd, deelbare bronnen vrijgeven. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Begin met het renderen van een frame |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Beëindigt het renderen van een frame |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Initialiseer de entity renderer |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Bereid renderopdrachten voor voor het opgegeven knooppunt/entity-paar. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Elke rendertaak die naar de [IRenderQueue](../../com.aspose.threed/irenderqueue) wordt gestuurd, zal een overeenkomstige RenderEntity‑aanroep hebben om de concrete rendertaak uit te voeren. |
| [resetSceneCache()](#resetSceneCache--) | De scène is gewijzigd of verwijderd, er moeten scene‑niveau renderbronnen worden vrijgegeven in dit geval. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Constructor van [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De sleutel van de entiteitrenderer |
| functies | byte | De extra functies van de entiteitrenderer |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Constructor van [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sleutel | java.lang.String | De sleutel van de entiteitrenderer |

### dispose() {#dispose--}
```
public void dispose()
```


De entity renderer wordt verwijderd, deelbare bronnen vrijgeven.

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
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Begin met het renderen van een frame

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Huidige renderer |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Renderwachtrij |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Beëindigt het renderen van een frame

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Huidige renderer |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Renderwachtrij |

### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### initialize(Renderer renderer) {#initialize-com.aspose.threed.Renderer-}
```
public void initialize(Renderer renderer)
```


Initialiseer de entity renderer

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) |  |

### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity) {#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-}
```
public void prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)
```


Bereid renderopdrachten voor voor het opgegeven knooppunt/entity-paar.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | De huidige rendererinstantie |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | De renderwachtrij die wordt gebruikt om rendertaken te beheren |
| node | [Node](../../com.aspose.threed/node) | Huidige knoop |
| entity | [Entity](../../com.aspose.threed/entity) | De entiteit die moet worden gerenderd |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Elke rendertaak die naar de [IRenderQueue](../../com.aspose.threed/irenderqueue) wordt gestuurd, zal een overeenkomstige RenderEntity‑aanroep hebben om de concrete rendertaak uit te voeren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | De renderer |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | De commandList die wordt gebruikt om de renderopdrachten vast te leggen |
| node | [Node](../../com.aspose.threed/node) | Dezelfde knoop die is doorgegeven aan PrepareRenderQueue van de entiteit die zal worden gerenderd |
| renderableResource | java.lang.Object | Het aangepaste object dat tijdens de PrepareRenderQueue aan IRenderQueue wordt doorgegeven |
| subEntity | int | De index van de subentiteit die aan IRenderQueue wordt doorgegeven |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


De scène is gewijzigd of verwijderd, er moeten scene‑niveau renderbronnen worden vrijgegeven in dit geval.

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

