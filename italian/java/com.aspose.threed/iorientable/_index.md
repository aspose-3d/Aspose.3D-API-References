---
title: IOrientable
second_title: Aspose.3D for Java API Reference
description: Le entità orientabili devono implementare questa interfaccia.
type: docs
weight: 246
url: /it/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Le entità orientabili devono implementare questa interfaccia.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getDirection()](#getDirection--) | Ottiene la direzione verso cui l'entità sta guardando. |
| [getTarget()](#getTarget--) | Ottiene il bersaglio verso cui l'entità sta guardando. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Imposta la direzione verso cui l'entità sta guardando. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Imposta il bersaglio verso cui l'entità sta guardando. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Ottiene la direzione verso cui l'entità sta guardando.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Ottiene il bersaglio verso cui l'entità sta guardando.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Imposta la direzione verso cui l'entità sta guardando.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Imposta il bersaglio verso cui l'entità sta guardando.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuovo valore |

