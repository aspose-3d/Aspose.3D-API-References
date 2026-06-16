---
title: "IOrientable"
second_title: "Aspose.3D for Java API Referansı"
description: "Yönlendirilebilir varlıklar bu arayüzü uygulamalıdır."
type: docs
weight: 246
url: /tr/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Yönlendirilebilir varlıklar bu arayüzü uygulamalıdır.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDirection()](#getDirection--) | Varlığın baktığı yönü alır. |
| [getTarget()](#getTarget--) | Varlığın baktığı hedefi alır. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Varlığın baktığı yönü ayarlar. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Varlığın baktığı hedefi ayarlar. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Varlığın baktığı yönü alır.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Varlığın baktığı hedefi alır.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Varlığın baktığı yönü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Yeni değer |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Varlığın baktığı hedefi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Yeni değer |

