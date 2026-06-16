---
title: "EntityRenderer"
second_title: "Aspose.3D for Java API Reference"
description: "Κληρονομήστε αυτήν την κλάση για να υλοποιήσετε την απόδοση διαφορετικών τύπων οντοτήτων."
type: docs
weight: 53
url: /el/java/com.aspose.threed/entityrenderer/
---

**Inheritance:**
java.lang.Object
```
public class EntityRenderer
```

Κληρονομήστε αυτήν την κλάση για να υλοποιήσετε την απόδοση διαφορετικών τύπων οντοτήτων.
## Κατασκευαστές

| Κατασκευαστής | Περιγραφή |
| --- | --- |
| [EntityRenderer(String key, byte features)](#EntityRenderer-java.lang.String-byte-) | Κατασκευαστής του [EntityRenderer](../../com.aspose.threed/entityrenderer) |
| [EntityRenderer(String key)](#EntityRenderer-java.lang.String-) | Κατασκευαστής του [EntityRenderer](../../com.aspose.threed/entityrenderer) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [dispose()](#dispose--) | Ο renderer της οντότητας διαγράφεται, απελευθερώστε τους κοινόχρηστους πόρους. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [frameBegin(Renderer renderer, IRenderQueue renderQueue)](#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Έναρξη απόδοσης ενός καρέ |
| [frameEnd(Renderer renderer, IRenderQueue renderQueue)](#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-) | Τέλος απόδοσης ενός καρέ |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [initialize(Renderer renderer)](#initialize-com.aspose.threed.Renderer-) | Αρχικοποίηση του αποτυπωτή οντοτήτων |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [prepareRenderQueue(Renderer renderer, IRenderQueue queue, Node node, Entity entity)](#prepareRenderQueue-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-com.aspose.threed.Node-com.aspose.threed.Entity-) | Προετοιμασία εντολών απόδοσης για το συγκεκριμένο ζεύγος κόμβου/οντότητας. |
| [renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)](#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-) | Κάθε εργασία απόδοσης που προωθείται στην [IRenderQueue](../../com.aspose.threed/irenderqueue) θα έχει μια αντίστοιχη κλήση RenderEntity για την εκτέλεση της συγκεκριμένης εργασίας απόδοσης. |
| [resetSceneCache()](#resetSceneCache--) | Η σκηνή έχει αλλάξει ή αφαιρεθεί, χρειάζεται να απορριφθούν οι πόροι απόδοσης σε επίπεδο σκηνής σε αυτό |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### EntityRenderer(String key, byte features) {#EntityRenderer-java.lang.String-byte-}
```
public EntityRenderer(String key, byte features)
```


Κατασκευαστής του [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί του entity renderer |
| χαρακτηριστικά | byte | Τα επιπλέον χαρακτηριστικά του αποτυπωτή οντοτήτων |

### EntityRenderer(String key) {#EntityRenderer-java.lang.String-}
```
public EntityRenderer(String key)
```


Κατασκευαστής του [EntityRenderer](../../com.aspose.threed/entityrenderer)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| κλειδί | java.lang.String | Το κλειδί του entity renderer |

### dispose() {#dispose--}
```
public void dispose()
```


Ο renderer της οντότητας διαγράφεται, απελευθερώστε τους κοινόχρηστους πόρους.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### frameBegin(Renderer renderer, IRenderQueue renderQueue) {#frameBegin-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameBegin(Renderer renderer, IRenderQueue renderQueue)
```


Έναρξη απόδοσης ενός καρέ

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Τρέχων αποτυπωτής |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Ουρά απόδοσης |

### frameEnd(Renderer renderer, IRenderQueue renderQueue) {#frameEnd-com.aspose.threed.Renderer-com.aspose.threed.IRenderQueue-}
```
public void frameEnd(Renderer renderer, IRenderQueue renderQueue)
```


Τέλος απόδοσης ενός καρέ

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Τρέχων αποτυπωτής |
| renderQueue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Ουρά απόδοσης |

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


Αρχικοποίηση του αποτυπωτή οντοτήτων

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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


Προετοιμασία εντολών απόδοσης για το συγκεκριμένο ζεύγος κόμβου/οντότητας.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Το τρέχον αντικείμενο αποτυπωτή |
| queue | [IRenderQueue](../../com.aspose.threed/irenderqueue) | Η ουρά απόδοσης που χρησιμοποιείται για τη διαχείριση εργασιών απόδοσης |
| node | [Node](../../com.aspose.threed/node) | Τρέχων κόμβος |
| entity | [Entity](../../com.aspose.threed/entity) | Η οντότητα που πρέπει να αποδοθεί |

### renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity) {#renderEntity-com.aspose.threed.Renderer-com.aspose.threed.ICommandList-com.aspose.threed.Node-java.lang.Object-int-}
```
public void renderEntity(Renderer renderer, ICommandList commandList, Node node, Object renderableResource, int subEntity)
```


Κάθε εργασία απόδοσης που προωθείται στην [IRenderQueue](../../com.aspose.threed/irenderqueue) θα έχει μια αντίστοιχη κλήση RenderEntity για την εκτέλεση της συγκεκριμένης εργασίας απόδοσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| renderer | [Renderer](../../com.aspose.threed/renderer) | Ο renderer |
| commandList | [ICommandList](../../com.aspose.threed/icommandlist) | Η commandList που χρησιμοποιείται για την καταγραφή των εντολών απόδοσης |
| node | [Node](../../com.aspose.threed/node) | Ο ίδιος κόμβος που περάστηκε στο PrepareRenderQueue της οντότητας που θα αποδοθεί |
| renderableResource | java.lang.Object | Το προσαρμοσμένο αντικείμενο που περάστηκε στο IRenderQueue κατά τη διάρκεια του PrepareRenderQueue |
| subEntity | int | Το ευρετήριο της υποοντότητας που περάστηκε στο IRenderQueue |

### resetSceneCache() {#resetSceneCache--}
```
public void resetSceneCache()
```


Η σκηνή έχει αλλάξει ή αφαιρεθεί, χρειάζεται να απορριφθούν οι πόροι απόδοσης σε επίπεδο σκηνής σε αυτό

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

