---
title: IOrientable
second_title: Aspose.3D for Java API Reference
description: ओरिएंटेबल इकाइयों को यह इंटरफ़ेस लागू करना चाहिए।
type: docs
weight: 246
url: /hi/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

ओरिएंटेबल इकाइयों को यह इंटरफ़ेस लागू करना चाहिए।
## Methods

| Method | विवरण |
| --- | --- |
| [getDirection()](#getDirection--) | इकाई जिस दिशा की ओर देख रही है, उसे प्राप्त करता है। |
| [getTarget()](#getTarget--) | इकाई जिस लक्ष्य की ओर देख रही है, उसे प्राप्त करता है। |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | इकाई जिस दिशा की ओर देख रही है, उसे सेट करता है। |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | इकाई जिस लक्ष्य की ओर देख रही है, उसे सेट करता है। |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


इकाई जिस दिशा की ओर देख रही है, उसे प्राप्त करता है।

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


इकाई जिस लक्ष्य की ओर देख रही है, उसे प्राप्त करता है।

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


इकाई जिस दिशा की ओर देख रही है, उसे सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | नया मान |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


इकाई जिस लक्ष्य की ओर देख रही है, उसे सेट करता है।

**Parameters:**
| Parameter | Type | विवरण |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | नया मान |

