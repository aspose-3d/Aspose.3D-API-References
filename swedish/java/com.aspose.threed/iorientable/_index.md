---
title: IOrientable
second_title: Aspose.3D for Java API-referens
description: Orienterbara entiteter ska implementera detta gränssnitt.
type: docs
weight: 246
url: /sv/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Orienterbara entiteter ska implementera detta gränssnitt.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDirection()](#getDirection--) | Hämtar riktningen som enheten tittar på. |
| [getTarget()](#getTarget--) | Hämtar målet som enheten tittar på. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Ställer in riktningen som enheten tittar på. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Ställer in målet som enheten tittar på. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Hämtar riktningen som enheten tittar på.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Hämtar målet som enheten tittar på.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Ställer in riktningen som enheten tittar på.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Ställer in målet som enheten tittar på.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nytt värde |

