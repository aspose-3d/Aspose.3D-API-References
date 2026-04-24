---
title: IOrientable
second_title: Aspose.3D for Java API-referentie
description: Oriënteerbare entiteiten moeten deze interface implementeren.
type: docs
weight: 246
url: /nl/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Oriënteerbare entiteiten moeten deze interface implementeren.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getDirection()](#getDirection--) | Haalt de richting op waar de entiteit naar kijkt. |
| [getTarget()](#getTarget--) | Haalt het doel op waar de entiteit naar kijkt. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Stelt de richting in waar de entiteit naar kijkt. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Stelt het doel in waar de entiteit naar kijkt. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Haalt de richting op waar de entiteit naar kijkt.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Haalt het doel op waar de entiteit naar kijkt.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Stelt de richting in waar de entiteit naar kijkt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Stelt het doel in waar de entiteit naar kijkt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nieuwe waarde |

