---
title: "IOrientable"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "الكيانات القابلة للتوجيه يجب أن تنفذ هذه الواجهة."
type: docs
weight: 246
url: /ar/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

الكيانات القابلة للتوجيه يجب أن تنفذ هذه الواجهة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [getDirection()](#getDirection--) | يحصل على الاتجاه الذي ينظر إليه الكيان. |
| [getTarget()](#getTarget--) | يحصل على الهدف الذي ينظر إليه الكيان. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | يضبط الاتجاه الذي ينظر إليه الكيان. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | يضبط الهدف الذي ينظر إليه الكيان. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


يحصل على الاتجاه الذي ينظر إليه الكيان.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


يحصل على الهدف الذي ينظر إليه الكيان.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


يضبط الاتجاه الذي ينظر إليه الكيان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | القيمة الجديدة |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


يضبط الهدف الذي ينظر إليه الكيان.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | القيمة الجديدة |

