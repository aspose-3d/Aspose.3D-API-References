---
title: IOrientable
second_title: Referensi API Aspose.3D untuk Java
description: Entitas yang dapat diputar harus mengimplementasikan antarmuka ini.
type: docs
weight: 246
url: /id/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Entitas yang dapat diputar harus mengimplementasikan antarmuka ini.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDirection()](#getDirection--) | Mendapatkan arah yang dilihat entitas. |
| [getTarget()](#getTarget--) | Mendapatkan target yang dilihat entitas. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Mengatur arah yang dilihat entitas. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Mengatur target yang dilihat entitas. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Mendapatkan arah yang dilihat entitas.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Mendapatkan target yang dilihat entitas.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Mengatur arah yang dilihat entitas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nilai baru |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Mengatur target yang dilihat entitas.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nilai baru |

