---
title: MathUtils
second_title: Aspose.3D for Java API Reference
description: Un insieme di utilità matematiche utili.
type: docs
weight: 99
url: /it/java/com.aspose.threed/mathutils/
---

**Inheritance:**
java.lang.Object
```
public class MathUtils
```

Un insieme di utilità matematiche utili.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [calcNormal(Vector3[] points)](#calcNormal-com.aspose.threed.Vector3---) |  |
| [clamp(double val, double min, double max)](#clamp-double-double-double-) | Limita il valore all'intervallo [min, max] |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)](#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [pointInsideTriangle(Vector2 p, Vector2 p0, Vector2 p1, Vector2 p2)](#pointInsideTriangle-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Verifica se il punto p è all'interno del triangolo (p0, p1, p2) |
| [rayIntersect(Vector2 origin, Vector2 dir, Vector2 a, Vector2 b)](#rayIntersect-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-) | Verifica se il raggio (origin, dir) interseca il segmento di linea (start, end) |
| [toDegree(Vector3 radian)](#toDegree-com.aspose.threed.Vector3-) | Converti un [Vector3](../../com.aspose.threed/vector3) da radianti a gradi. |
| [toDegree(double radian)](#toDegree-double-) | Converti un numero da radianti a gradi |
| [toDegree(double x, double y, double z)](#toDegree-double-double-double-) | Converti un numero da radianti a gradi |
| [toDegree(float radian)](#toDegree-float-) | Converti un numero da radianti a gradi |
| [toRadian(Vector3 degree)](#toRadian-com.aspose.threed.Vector3-) | Converti un [Vector3](../../com.aspose.threed/vector3) da gradi a radianti |
| [toRadian(double degree)](#toRadian-double-) | Converti un numero da gradi a radianti |
| [toRadian(double x, double y, double z)](#toRadian-double-double-double-) | Converti un vettore da gradi a radianti |
| [toRadian(float degree)](#toRadian-float-) | Converti un numero da gradi a radianti |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### calcNormal(Vector3[] points) {#calcNormal-com.aspose.threed.Vector3---}
```
public static Vector3 calcNormal(Vector3[] points)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| points | [Vector3\[\]](../../com.aspose.threed/vector3) |  |

**Returns:**
[Vector3](../../com.aspose.threed/vector3)
### clamp(double val, double min, double max) {#clamp-double-double-double-}
```
public static double clamp(double val, double min, double max)
```


Limita il valore all'intervallo [min, max]

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| val | double | Valore da limitare. |
| min | double | Valore minimo. |
| max | double | Valore massimo. |

**Returns:**
double - Il valore compreso tra [min, max] **Esempio:**

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results) {#findIntersection-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2-com.aspose.threed.Vector2---}
```
public static int findIntersection(Vector2 p0, Vector2 d0, Vector2 p1, Vector2 d1, Vector2[] results)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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


Verifica se il punto p è all'interno del triangolo (p0, p1, p2)

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Verifica se il raggio (origin, dir) interseca il segmento di linea (start, end)

**Parameters:**
| Parametro | Tipo | Descrizione |
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


Converti un [Vector3](../../com.aspose.threed/vector3) da radianti a gradi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radian | [Vector3](../../com.aspose.threed/vector3) | Il valore in radianti. |

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


Converti un numero da radianti a gradi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radian | double | Il valore in radianti. |

**Returns:**
double - Il valore in gradi. **Esempio:**

```
var deg = MathUtils.toDegree(0.3);
     System.out.printf("Degrees = %s", deg);
```
### toDegree(double x, double y, double z) {#toDegree-double-double-double-}
```
public static Vector3 toDegree(double x, double y, double z)
```


Converti un numero da radianti a gradi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | La componente x nel valore in radianti. |
| y | double | La componente y nel valore in radianti. |
| z | double | La componente z nel valore in radianti. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The degree value.
### toDegree(float radian) {#toDegree-float-}
```
public static float toDegree(float radian)
```


Converti un numero da radianti a gradi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| radian | float | Il valore in radianti. |

**Returns:**
float - Il valore in gradi. **Esempio:**

```
var deg = MathUtils.toDegree(0.3f);
     System.out.printf("Degrees = %s", deg);
```
### toRadian(Vector3 degree) {#toRadian-com.aspose.threed.Vector3-}
```
public static Vector3 toRadian(Vector3 degree)
```


Converti un [Vector3](../../com.aspose.threed/vector3) da gradi a radianti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | [Vector3](../../com.aspose.threed/vector3) | Il valore in gradi. |

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


Converti un numero da gradi a radianti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | double | Il valore in gradi. |

**Returns:**
double - Il valore in radianti. **Esempio:**

```
var rad = MathUtils.toRadian(0.3);
     System.out.printf("Radian = %d", rad);
```
### toRadian(double x, double y, double z) {#toRadian-double-double-double-}
```
public static Vector3 toRadian(double x, double y, double z)
```


Converti un vettore da gradi a radianti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| x | double | La componente x nel valore in gradi. |
| y | double | La componente y nel valore in gradi. |
| z | double | La componente z nel valore in gradi. |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - The radian value.
### toRadian(float degree) {#toRadian-float-}
```
public static float toRadian(float degree)
```


Converti un numero da gradi a radianti

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| degree | float | Il valore in gradi. |

**Returns:**
float - Il valore in radianti. **Esempio:**

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

