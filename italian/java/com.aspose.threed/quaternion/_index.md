---
title: Quaternion
second_title: Aspose.3D for Java API Reference
description: Il quaternione è solitamente usato per eseguire rotazioni nella grafica computerizzata.
type: docs
weight: 143
url: /it/java/com.aspose.threed/quaternion/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class Quaternion implements Struct<Quaternion>, Serializable
```

Il quaternione è solitamente usato per eseguire rotazioni nella grafica computerizzata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Quaternion(double w, double x, double y, double z)](#Quaternion-double-double-double-double-) | Inizializza una nuova istanza della classe [Quaternion](../../com.aspose.threed/quaternion). |
| [Quaternion()](#Quaternion--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [IDENTITY](#IDENTITY) | Il quaternione di identità. |
| [w](#w) | Il componente w. |
| [x](#x) | La componente x. |
| [y](#y) | La componente y. |
| [z](#z) | La componente z. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [add(Quaternion lhs, Quaternion rhs)](#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Sovraccarico dell'operatore per + |
| [clone()](#clone--) |  |
| [concat(Quaternion rhs)](#concat-com.aspose.threed.Quaternion-) | Concatena due quaternioni |
| [conjugate()](#conjugate--) | Restituisce un quaternione coniugato del quaternione corrente |
| [copyFrom(Quaternion src)](#copyFrom-com.aspose.threed.Quaternion-) |  |
| [div(Quaternion lhs, double rhs)](#div-com.aspose.threed.Quaternion-double-) | Sovraccarico dell'operatore per / |
| [dot(Quaternion q)](#dot-com.aspose.threed.Quaternion-) | Prodotto scalare |
| [equals(Object obj)](#equals-java.lang.Object-) | Verifica se due quaternioni sono uguali |
| [eulerAngles()](#eulerAngles--) | Converte il quaternione in una rotazione rappresentata da angoli di Eulero. Tutti i componenti sono in radianti. |
| [fromAngleAxis(double a, Vector3 axis)](#fromAngleAxis-double-com.aspose.threed.Vector3-) | Crea un quaternione attorno all'asse dato e ruota in senso orario |
| [fromEulerAngle(Vector3 eulerAngle)](#fromEulerAngle-com.aspose.threed.Vector3-) | Crea un quaternione da un angolo di Eulero fornito |
| [fromEulerAngle(double pitch, double yaw, double roll)](#fromEulerAngle-double-double-double-) | Crea un quaternione da un angolo di Eulero fornito |
| [fromRotation(Vector3 orig, Vector3 dest)](#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-) | Crea un quaternione che ruota dalla direzione originale a quella di destinazione |
| [getClass()](#getClass--) |  |
| [getLength()](#getLength--) | Ottiene la lunghezza del quaternione |
| [hashCode()](#hashCode--) | Ottiene il codice hash del quaternione |
| [interpolate(float t, Quaternion from, Quaternion to)](#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Popola questo quaternione con il valore interpolato tra i quaternioni forniti per un t compreso tra da e a. |
| [inverse()](#inverse--) | Restituisce un quaternione inverso del quaternione corrente |
| [mul(Quaternion lhs, Quaternion rhs)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Sovraccarico dell'operatore per \* |
| [mul(Quaternion q, Vector3 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-) | Sovraccarico dell'operatore per \* |
| [mul(Quaternion q, Vector4 v)](#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-) | Sovraccarico dell'operatore per \* |
| [mul(Quaternion lhs, double rhs)](#mul-com.aspose.threed.Quaternion-double-) | Sovraccarico dell'operatore per \* |
| [mul(Vector3 v, Quaternion q)](#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-) | Sovraccarico dell'operatore per \* |
| [normalize()](#normalize--) | Normalizza il quaternione |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_eq(Quaternion lhs, Quaternion rhs)](#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operatore di uguaglianza per il quaternione |
| [op_ne(Quaternion lhs, Quaternion rhs)](#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Operatore di disuguaglianza per il quaternione |
| [slerp(double t, Quaternion v1, Quaternion v2)](#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-) | Esegue l'interpolazione lineare sferica tra due valori |
| [toAngleAxis(double[] angle, Vector3 axis)](#toAngleAxis-double---com.aspose.threed.Vector3-) | Decompone il quaternione in angolo e asse |
| [toMatrix()](#toMatrix--) | Converte la rotazione rappresentata dal quaternione in una matrice di trasformazione. |
| [toMatrix(Vector3 translation)](#toMatrix-com.aspose.threed.Vector3-) | Converte la rotazione rappresentata dal quaternione in una matrice di trasformazione. |
| [toString()](#toString--) | Ottiene la rappresentazione del quaternione in stringa |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Quaternion(double w, double x, double y, double z) {#Quaternion-double-double-double-double-}
```
public Quaternion(double w, double x, double y, double z)
```


Inizializza una nuova istanza della classe [Quaternion](../../com.aspose.threed/quaternion).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| w | double | componente w del quaternione |
| x | double | componente x del quaternione |
| y | double | componente y del quaternione |
| z | double | componente z del quaternione |

### Quaternion() {#Quaternion--}
```
public Quaternion()
```


### IDENTITY {#IDENTITY}
```
public static final Quaternion IDENTITY
```


Il quaternione di identità.

### w {#w}
```
public double w
```


Il componente w.

### x {#x}
```
public double x
```


La componente x.

### y {#y}
```
public double y
```


La componente y.

### z {#z}
```
public double z
```


La componente z.

### add(Quaternion lhs, Quaternion rhs) {#add-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion add(Quaternion lhs, Quaternion rhs)
```


Sovraccarico dell'operatore per +

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternione sinistro |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternione destro |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### clone() {#clone--}
```
public Quaternion clone()
```


Clone current instance

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### concat(Quaternion rhs) {#concat-com.aspose.threed.Quaternion-}
```
public Quaternion concat(Quaternion rhs)
```


Concatena due quaternioni

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) |  |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### conjugate() {#conjugate--}
```
public Quaternion conjugate()
```


Restituisce un quaternione coniugato del quaternione corrente

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The conjugate quaternion.
### copyFrom(Quaternion src) {#copyFrom-com.aspose.threed.Quaternion-}
```
public void copyFrom(Quaternion src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [Quaternion](../../com.aspose.threed/quaternion) |  |

### div(Quaternion lhs, double rhs) {#div-com.aspose.threed.Quaternion-double-}
```
public static Quaternion div(Quaternion lhs, double rhs)
```


Sovraccarico dell'operatore per /

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternione sinistro |
| rhs | double | Quaternione destro |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### dot(Quaternion q) {#dot-com.aspose.threed.Quaternion-}
```
public double dot(Quaternion q)
```


Prodotto scalare

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Il quaternione |

**Returns:**
double - Valore del prodotto scalare
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Verifica se due quaternioni sono uguali

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object | L'oggetto da verificare l'uguaglianza. |

**Returns:**
boolean - Vero se tutti i componenti sono identicamente uguali.
### eulerAngles() {#eulerAngles--}
```
public Vector3 eulerAngles()
```


Converte il quaternione in una rotazione rappresentata da angoli di Eulero. Tutti i componenti sono in radianti.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Result vector
### fromAngleAxis(double a, Vector3 axis) {#fromAngleAxis-double-com.aspose.threed.Vector3-}
```
public static Quaternion fromAngleAxis(double a, Vector3 axis)
```


Crea un quaternione attorno all'asse dato e ruota in senso orario

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| a | double | Rotazione in senso orario in radianti |
| axis | [Vector3](../../com.aspose.threed/vector3) | Asse |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(Vector3 eulerAngle) {#fromEulerAngle-com.aspose.threed.Vector3-}
```
public static Quaternion fromEulerAngle(Vector3 eulerAngle)
```


Crea un quaternione da un angolo di Eulero fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| eulerAngle | [Vector3](../../com.aspose.threed/vector3) | Angolo di Eulero in radianti |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromEulerAngle(double pitch, double yaw, double roll) {#fromEulerAngle-double-double-double-}
```
public static Quaternion fromEulerAngle(double pitch, double yaw, double roll)
```


Crea un quaternione da un angolo di Eulero fornito

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| beccheggio | double | Beccheggio in radianti |
| imbardata | double | Imbardata in radianti |
| rollio | double | Rollio in radianti |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### fromRotation(Vector3 orig, Vector3 dest) {#fromRotation-com.aspose.threed.Vector3-com.aspose.threed.Vector3-}
```
public static Quaternion fromRotation(Vector3 orig, Vector3 dest)
```


Crea un quaternione che ruota dalla direzione originale a quella di destinazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| orig | [Vector3](../../com.aspose.threed/vector3) | Direzione originale |
| dest | [Vector3](../../com.aspose.threed/vector3) | Direzione di destinazione |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Created quaternion
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getLength() {#getLength--}
```
public double getLength()
```


Ottiene la lunghezza del quaternione

**Returns:**
double - la lunghezza del quaternione
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottiene il codice hash del quaternione

**Returns:**
int - Il codice hash del [Quaternion](../../com.aspose.threed/quaternion)
### interpolate(float t, Quaternion from, Quaternion to) {#interpolate-float-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion interpolate(float t, Quaternion from, Quaternion to)
```


Popola questo quaternione con il valore interpolato tra i quaternioni forniti per un t compreso tra da e a.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| t | float | Il coefficiente da interpolare. |
| from | [Quaternion](../../com.aspose.threed/quaternion) | Quaternione sorgente. |
| to | [Quaternion](../../com.aspose.threed/quaternion) | Quaternione di destinazione. |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - The interpolated quaternion.
### inverse() {#inverse--}
```
public Quaternion inverse()
```


Restituisce un quaternione inverso del quaternione corrente

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Inverse quaternion.
### mul(Quaternion lhs, Quaternion rhs) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion mul(Quaternion lhs, Quaternion rhs)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternione sinistro |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternione destro |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Quaternion q, Vector3 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector3-}
```
public static Vector3 mul(Quaternion q, Vector3 v)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Il quaternione di rotazione |
| v | [Vector3](../../com.aspose.threed/vector3) | Vettore da ruotare |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### mul(Quaternion q, Vector4 v) {#mul-com.aspose.threed.Quaternion-com.aspose.threed.Vector4-}
```
public static Vector4 mul(Quaternion q, Vector4 v)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Il quaternione di rotazione |
| v | [Vector4](../../com.aspose.threed/vector4) | Vettore da ruotare |

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - Rotated vector
### mul(Quaternion lhs, double rhs) {#mul-com.aspose.threed.Quaternion-double-}
```
public static Quaternion mul(Quaternion lhs, double rhs)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Quaternione sinistro |
| rhs | double | Quaternione destro |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Result quaternion
### mul(Vector3 v, Quaternion q) {#mul-com.aspose.threed.Vector3-com.aspose.threed.Quaternion-}
```
public static Vector3 mul(Vector3 v, Quaternion q)
```


Sovraccarico dell'operatore per \*

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| v | [Vector3](../../com.aspose.threed/vector3) | Il quaternione di rotazione |
| q | [Quaternion](../../com.aspose.threed/quaternion) | Vettore da ruotare |

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - Rotated vector
### normalize() {#normalize--}
```
public Quaternion normalize()
```


Normalizza il quaternione

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion) - Normalized quaternion.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_eq(Quaternion lhs, Quaternion rhs) {#op-eq-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_eq(Quaternion lhs, Quaternion rhs)
```


Operatore di uguaglianza per il quaternione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Valore del lato sinistro. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Valore del lato destro. |

**Returns:**
boolean - Vero se tutti i componenti sono identicamente uguali.
### op_ne(Quaternion lhs, Quaternion rhs) {#op-ne-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static boolean op_ne(Quaternion lhs, Quaternion rhs)
```


Operatore di disuguaglianza per il quaternione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| lhs | [Quaternion](../../com.aspose.threed/quaternion) | Valore del lato sinistro. |
| rhs | [Quaternion](../../com.aspose.threed/quaternion) | Valore del lato destro. |

**Returns:**
boolean - Vero se due quaternioni non sono uguali.
### slerp(double t, Quaternion v1, Quaternion v2) {#slerp-double-com.aspose.threed.Quaternion-com.aspose.threed.Quaternion-}
```
public static Quaternion slerp(double t, Quaternion v1, Quaternion v2)
```


Esegue l'interpolazione lineare sferica tra due valori

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| t | double | t è compreso tra 0 e 1 |
| v1 | [Quaternion](../../com.aspose.threed/quaternion) | Primo valore |
| v2 | [Quaternion](../../com.aspose.threed/quaternion) | Secondo valore |

**Returns:**
[Quaternion](../../com.aspose.threed/quaternion)
### toAngleAxis(double[] angle, Vector3 axis) {#toAngleAxis-double---com.aspose.threed.Vector3-}
```
public void toAngleAxis(double[] angle, Vector3 axis)
```


Decompone il quaternione in angolo e asse

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| angle | double[] | L'angolo da ruotare, in radianti. |
| axis | [Vector3](../../com.aspose.threed/vector3) | L'asse attorno al quale ruotare. |

### toMatrix() {#toMatrix--}
```
public Matrix4 toMatrix()
```


Converte la rotazione rappresentata dal quaternione in una matrice di trasformazione.

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toMatrix(Vector3 translation) {#toMatrix-com.aspose.threed.Vector3-}
```
public Matrix4 toMatrix(Vector3 translation)
```


Converte la rotazione rappresentata dal quaternione in una matrice di trasformazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| translation | [Vector3](../../com.aspose.threed/vector3) | La parte di traslazione della matrice. |

**Returns:**
[Matrix4](../../com.aspose.threed/matrix4) - The matrix representation of current quaternion.
### toString() {#toString--}
```
public String toString()
```


Ottiene la rappresentazione del quaternione in stringa

**Returns:**
java.lang.String - Stringa dell'oggetto
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

