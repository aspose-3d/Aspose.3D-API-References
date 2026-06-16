---
title: "MathUtils"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un ensemble d'utilitaires mathématiques utiles."
type: docs
weight: 99
url: /fr/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

Un ensemble d'utilitaires mathématiques utiles.
## Méthodes

| Méthode | Description |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | Limite la valeur à la plage [min, max] |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vérifie si le point p est à l'intérieur du triangle (p0, p1, p2) |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Vérifie si le rayon (origin, dir) intersecte le segment de ligne (start, end) |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | Convertit un [Vector3](../../com.aspose.threed/vector3) de radian en degré. |
| [toDegree(double radian)](#toDegree-double-) | Convertit un nombre de radian en degré |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | Convertit un nombre de radian en degré |
| [toDegree(float radian)](#toDegree-float-) | Convertit un nombre de radian en degré |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | Convertit un [Vector3](../../com.aspose.threed/vector3) de degré en radian |
| [toRadian(double degree)](#toRadian-double-) | Convertir un nombre de degrés en radians |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | Convertir un vecteur de degrés en radians |
| [toRadian(float degree)](#toRadian-float-) | Convertir un nombre de degrés en radians |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


Limite la valeur à la plage [min, max]

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| val | double | Valeur à limiter. |
| min | double | Valeur minimale. |
| max | double | Valeur maximale. |

**Returns:**
double - La valeur entre [min, max] **Exemple:**

```
double val = 195;
     //Clamp value to [0, 100]
     double clampedValue = MathUtils.clamp(val, 0, 100);
     //This will output 100
     System.out.printf("Value = %d", val);
```
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
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| p0 | [Vector2](../../com.aspose.threed/vector2) |  |
| d0 | [Vector2](../../com.aspose.threed/vector2) |  |
| p1 | [Vector2](../../com.aspose.threed/vector2) |  |
| d1 | [Vector2](../../com.aspose.threed/vector2) |  |
| results | [Vector2\[\]](../../com.aspose.threed/vector2) |  |

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2) {#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static boolean pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)
```


Vérifie si le point p est à l'intérieur du triangle (p0, p1, p2)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| p | [Vector2](../../com.aspose.threed/vector2) |  |
| p0 | [Vector2](../../com.aspose.threed/vector2) |  |
| p1 | [Vector2](../../com.aspose.threed/vector2) |  |
| p2 | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
boolean
### rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b) {#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-}
```
public static Vector2 rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)
```


Vérifie si le rayon (origin, dir) intersecte le segment de ligne (start, end)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| origin | [Vector2](../../com.aspose.threed/vector2) |  |
| dir | [Vector2](../../com.aspose.threed/vector2) |  |
| a | [Vector2](../../com.aspose.threed/vector2) |  |
| b | [Vector2](../../com.aspose.threed/vector2) |  |

**Returns:**
[Vector2](../../com.aspose.threed/vector2)
### toDegree(Vector3 radian) {#toDegree-com.aspose.threed.Vector3-}
```
public static Vector3 toDegree(Vector3 radian)
```


Convertit un [Vector3](../../com.aspose.threed/vector3) de radian en degré.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | La valeur en radians. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value. **Example:**

```
Vector3 degrees = MathUtils.toDegree(new Vector3(0.34, 0.9, 0.2));
     System.out.printf("Degrees = %s", degrees);
```
### toDegree(double radian) {#toDegree-double-}
```
public static double toDegree(double radian)
```


Convertit un nombre de radian en degré

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radian | double | La valeur en radians. |

**Returns:**
double - La valeur en degrés. **Exemple:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


Convertit un nombre de radian en degré

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | Le composant x en valeur radian. |
| y | double | Le composant y en valeur radian. |
| z | double | Le composant z en valeur radian. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


Convertit un nombre de radian en degré

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| radian | float | La valeur en radians. |

**Returns:**
float - La valeur en degrés. **Exemple:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


Convertit un [Vector3](../../com.aspose.threed/vector3) de degré en radian

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | La valeur du degré. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value. **Example:**

```
Vector3 radians = MathUtils.toRadian(new Vector3(90, 134, 0));
     System.out.printf("Radians = %s", radians);
```
### toRadian(double degree) {#toRadian-double-}
```
public static double toRadian(double degree)
```


Convertir un nombre de degrés en radians

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| degré | double | La valeur du degré. |

**Returns:**
double - La valeur en radians. **Exemple:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


Convertir un vecteur de degrés en radians

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x | double | Le composant x en valeur degré. |
| y | double | Le composant y en valeur degré. |
| z | double | Le composant z en valeur degré. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


Convertir un nombre de degrés en radians

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| degré | float | La valeur du degré. |

**Returns:**
float - La valeur en radians. **Exemple:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
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

