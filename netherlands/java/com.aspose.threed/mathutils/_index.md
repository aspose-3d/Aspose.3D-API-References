---
title: MathUtils
second_title: Aspose.3D for Java API-referentie
description: Een verzameling nuttige wiskundige hulpprogramma's.
type: docs
weight: 99
url: /nl/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

Een verzameling nuttige wiskundige hulpprogramma's.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | Beperk waarde tot bereik [min, max] |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Controleer of punt p binnen de driehoek (p0, p1, p2) ligt |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Controleer of straal (origin, dir) intersecteert met lijnsegment(start, end) |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | Converteer een [Vector3](../../com.aspose.threed/vector3) van radialen naar graden. |
| [toDegree(double radian)](#toDegree-double-) | Converteer een getal van radialen naar graden |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | Converteer een getal van radialen naar graden |
| [toDegree(float radian)](#toDegree-float-) | Converteer een getal van radialen naar graden |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | Converteer een [Vector3](../../com.aspose.threed/vector3) van graden naar radialen |
| [toRadian(double degree)](#toRadian-double-) | Converteer een getal van graad naar radiaal |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | Converteer een vector van graad naar radiaal |
| [toRadian(float degree)](#toRadian-float-) | Converteer een getal van graad naar radiaal |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


Beperk waarde tot bereik [min, max]

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| val | double | Waarde om te begrenzen. |
| min | double | Minimumwaarde. |
| max | double | Maximumwaarde. |

**Returns:**
double - De waarde tussen [min, max] **Example:**

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Controleer of punt p binnen de driehoek (p0, p1, p2) ligt

**Parameters:**
| Parameter | Type | Beschrijving |
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


Controleer of straal (origin, dir) intersecteert met lijnsegment(start, end)

**Parameters:**
| Parameter | Type | Beschrijving |
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


Converteer een [Vector3](../../com.aspose.threed/vector3) van radialen naar graden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | De radiale waarde. |

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


Converteer een getal van radialen naar graden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radiaal | double | De radiale waarde. |

**Returns:**
double - De graadwaarde. **Example:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


Converteer een getal van radialen naar graden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | De x-component in radiale waarde. |
| y | double | De y-component in radiale waarde. |
| z | double | De z-component in radiale waarde. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


Converteer een getal van radialen naar graden

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| radiaal | float | De radiale waarde. |

**Returns:**
float - De graadwaarde. **Example:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


Converteer een [Vector3](../../com.aspose.threed/vector3) van graden naar radialen

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | De graadwaarde. |

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


Converteer een getal van graad naar radiaal

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| graad | double | De graadwaarde. |

**Returns:**
double - De radiale waarde. **Example:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


Converteer een vector van graad naar radiaal

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| x | double | De x-component in graadwaarde. |
| y | double | De y-component in graadwaarde. |
| z | double | De z-component in graadwaarde. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


Converteer een getal van graad naar radiaal

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| graad | float | De graadwaarde. |

**Returns:**
float - De radiale waarde. **Example:**

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

