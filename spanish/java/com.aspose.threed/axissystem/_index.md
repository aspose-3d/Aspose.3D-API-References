---
title: "AxisSystem"
second_title: "Referencia de API de Aspose.3D for Java"
description: "El sistema de ejes es una combinación del vector ascendente del sistema de coordenadas y del vector frontal."
type: docs
weight: 18
url: /es/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

El sistema de ejes es una combinación de sistema de coordenadas, vector ascendente y vector frontal.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | Construye un nuevo sistema de ejes |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Construye un nuevo sistema de ejes |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Construye un nuevo sistema de ejes |
## Métodos

| Método | Descripción |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | Crear [AxisSystem](../../com.aspose.threed/axissystem) a partir de [AssetInfo](../../com.aspose.threed/assetinfo) |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | Obtiene el sistema de coordenadas de este sistema de ejes. |
| [getFront()](#getFront--) | Obtiene el vector frontal de este sistema de ejes |
| [getUp()](#getUp--) | Obtiene el vector ascendente de este sistema de ejes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | Crear una matriz utilizada para convertir del sistema de ejes actual al sistema de ejes objetivo. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


Construye un nuevo sistema de ejes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | El sistema de coordenadas utilizado en este sistema de ejes |
| up | [Axis](../../com.aspose.threed/axis) | El vector ascendente del sistema de ejes |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


Construye un nuevo sistema de ejes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | El vector ascendente del sistema de ejes |
| front | [Axis](../../com.aspose.threed/axis) | El vector frontal del sistema de ejes |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


Construye un nuevo sistema de ejes

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | El sistema de coordenadas utilizado en este sistema de ejes |
| up | [Axis](../../com.aspose.threed/axis) | El vector ascendente del sistema de ejes |
| front | [Axis](../../com.aspose.threed/axis) | El vector frontal del sistema de ejes |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


Crear [AxisSystem](../../com.aspose.threed/axissystem) a partir de [AssetInfo](../../com.aspose.threed/assetinfo)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | De qué información de activo leer el sistema de coordenadas, el vector ascendente y el vector frontal. |

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - Axis system containg coordinate system, up, front from given asset info
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Obtiene el sistema de coordenadas de este sistema de ejes.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


Obtiene el vector frontal de este sistema de ejes

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


Obtiene el vector ascendente de este sistema de ejes.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up vector of this axis system.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformTo(AxisSystem targetSystem) {#transformTo-com.aspose.threed.AxisSystem-}
```
public Matrix4 transformTo(AxisSystem targetSystem)
```


Crear una matriz utilizada para convertir del sistema de ejes actual al sistema de ejes objetivo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | Sistema de ejes objetivo |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - A new transformation matrix to do the axis conversion
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

