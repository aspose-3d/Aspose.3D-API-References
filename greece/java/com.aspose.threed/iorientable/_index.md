---
title: IOrientable
second_title: Aspose.3D for Java API Reference
description: Οι προσανατολίσιμες οντότητες πρέπει να υλοποιούν αυτή τη διεπαφή.
type: docs
weight: 246
url: /el/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Οι προσανατολίσιμες οντότητες πρέπει να υλοποιούν αυτή τη διεπαφή.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getDirection()](#getDirection--) | Λαμβάνει την κατεύθυνση προς την οποία κοιτάζει η οντότητα. |
| [getTarget()](#getTarget--) | Λαμβάνει τον στόχο προς τον οποίο κοιτάζει η οντότητα. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Ορίζει την κατεύθυνση προς την οποία κοιτάζει η οντότητα. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Ορίζει τον στόχο προς τον οποίο κοιτάζει η οντότητα. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Λαμβάνει την κατεύθυνση προς την οποία κοιτάζει η οντότητα.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Λαμβάνει τον στόχο προς τον οποίο κοιτάζει η οντότητα.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Ορίζει την κατεύθυνση προς την οποία κοιτάζει η οντότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Ορίζει τον στόχο προς τον οποίο κοιτάζει η οντότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Νέα τιμή |

