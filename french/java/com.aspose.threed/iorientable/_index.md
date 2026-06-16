---
title: "IOrientable"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Les entités orientables doivent implémenter cette interface."
type: docs
weight: 246
url: /fr/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Les entités orientables doivent implémenter cette interface.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getDirection()](#getDirection--) | Obtient la direction vers laquelle l'entité regarde. |
| [getTarget()](#getTarget--) | Obtient la cible vers laquelle l'entité regarde. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Définit la direction vers laquelle l'entité regarde. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Définit la cible vers laquelle l'entité regarde. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Obtient la direction vers laquelle l'entité regarde.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Obtient la cible vers laquelle l'entité regarde.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Définit la direction vers laquelle l'entité regarde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Définit la cible vers laquelle l'entité regarde.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nouvelle valeur |

