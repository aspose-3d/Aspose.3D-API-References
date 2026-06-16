---
title: IOrientable
second_title: Referencia de API de Aspose.3D para Java
description: Las entidades orientables deberán implementar esta interfaz.
type: docs
weight: 246
url: /es/java/com.aspose.threed/iorientable/
---
```
public interface IOrientable
```

Las entidades orientables deberán implementar esta interfaz.
## Métodos

| Método | Descripción |
| --- | --- |
| [getDirection()](#getDirection--) | Obtiene la dirección a la que la entidad está mirando. |
| [getTarget()](#getTarget--) | Obtiene el objetivo al que la entidad está mirando. |
| [setDirection(Vector3 value)](#setDirection-com.aspose.threed.Vector3-) | Establece la dirección a la que la entidad está mirando. |
| [setTarget(Node value)](#setTarget-com.aspose.threed.Node-) | Establece el objetivo al que la entidad está mirando. |
### getDirection() {#getDirection--}
```
public abstract Vector3 getDirection()
```


Obtiene la dirección a la que la entidad está mirando.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the direction that the entity is looking at.
### getTarget() {#getTarget--}
```
public abstract Node getTarget()
```


Obtiene el objetivo al que la entidad está mirando.

**Returns:**
[Node](../../com.aspose.threed/node) - the target that the entity is looking at.
### setDirection(Vector3 value) {#setDirection-com.aspose.threed.Vector3-}
```
public abstract void setDirection(Vector3 value)
```


Establece la dirección a la que la entidad está mirando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuevo valor |

### setTarget(Node value) {#setTarget-com.aspose.threed.Node-}
```
public abstract void setTarget(Node value)
```


Establece el objetivo al que la entidad está mirando.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [Node](../../com.aspose.threed/node) | Nuevo valor |

