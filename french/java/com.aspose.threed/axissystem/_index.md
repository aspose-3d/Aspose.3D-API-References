---
title: "AxisSystem"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Le système d'axes est une combinaison du vecteur up et du vecteur front du système de coordonnées."
type: docs
weight: 18
url: /fr/java/com.aspose.threed/axissystem/
---

**Inheritance:**
java.lang.Object
```
public class AxisSystem
```

Le système d'axes est une combinaison du système de coordonnées, du vecteur up et du vecteur front.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-) | Construit un nouveau système d'axes |
| [AxisSystem(Axis up, Axis front)](#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Construit un nouveau système d'axes |
| [AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)](#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-) | Construit un nouveau système d'axes |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [fromAssetInfo(AssetInfo assetInfo)](#fromAssetInfo-com.aspose.threed.AssetInfo-) | Crée [AxisSystem](../../com.aspose.threed/axissystem) à partir de [AssetInfo](../../com.aspose.threed/assetinfo) |
| [getClass()](#getClass--) |  |
| [getCoordinateSystem()](#getCoordinateSystem--) | Obtient le système de coordonnées de ce système d'axes. |
| [getFront()](#getFront--) | Obtient le vecteur front de ce système d'axes |
| [getUp()](#getUp--) | Obtient le vecteur up de ce système d'axes. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [transformTo(AxisSystem targetSystem)](#transformTo-com.aspose.threed.AxisSystem-) | Crée une matrice utilisée pour convertir du système d'axes actuel vers le système d'axes cible. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AxisSystem(CoordinateSystem coordinateSystem, Axis up) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up)
```


Construit un nouveau système d'axes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Le système de coordonnées utilisé dans ce système d'axes |
| up | [Axis](../../com.aspose.threed/axis) | Le vecteur up du système d'axes |

### AxisSystem(Axis up, Axis front) {#AxisSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(Axis up, Axis front)
```


Construit un nouveau système d'axes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| up | [Axis](../../com.aspose.threed/axis) | Le vecteur up du système d'axes |
| front | [Axis](../../com.aspose.threed/axis) | Le vecteur front du système d'axes |

### AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front) {#AxisSystem-com.aspose.threed.CoordinateSystem-com.aspose.threed.Axis-com.aspose.threed.Axis-}
```
public AxisSystem(CoordinateSystem coordinateSystem, Axis up, Axis front)
```


Construit un nouveau système d'axes

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| coordinateSystem | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Le système de coordonnées utilisé dans ce système d'axes |
| up | [Axis](../../com.aspose.threed/axis) | Le vecteur up du système d'axes |
| front | [Axis](../../com.aspose.threed/axis) | Le vecteur front du système d'axes |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### fromAssetInfo(AssetInfo assetInfo) {#fromAssetInfo-com.aspose.threed.AssetInfo-}
```
public static AxisSystem fromAssetInfo(AssetInfo assetInfo)
```


Crée [AxisSystem](../../com.aspose.threed/axissystem) à partir de [AssetInfo](../../com.aspose.threed/assetinfo)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| assetInfo | [AssetInfo](../../com.aspose.threed/assetinfo) | À partir de quelles informations d'actif lire le système de coordonnées, le vecteur up et le vecteur front. |

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


Obtient le système de coordonnées de ce système d'axes.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system of this axis system.
### getFront() {#getFront--}
```
public Axis getFront()
```


Obtient le vecteur front de ce système d'axes

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front vector of this axis system
### getUp() {#getUp--}
```
public Axis getUp()
```


Obtient le vecteur up de ce système d'axes.

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


Crée une matrice utilisée pour convertir du système d'axes actuel vers le système d'axes cible.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| targetSystem | [AxisSystem](../../com.aspose.threed/axissystem) | Système d'axes cible |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

