---
title: PolygonBuilder
second_title: Aspose.3D for Java API Reference
description: Μια βοηθητική κλάση για τη δημιουργία πολυγώνου για  Παράδειγμα
type: docs
weight: 133
url: /el/java/com.aspose.threed/polygonbuilder/
---

**Inheritance:**
java.lang.Object
```
public final class PolygonBuilder
```

Μια βοηθητική κλάση για τη δημιουργία πολυγώνου για [Mesh](../../com.aspose.threed/mesh) **Παράδειγμα:**

```
Mesh mesh = new Mesh();
  PolygonBuilder builder = new PolygonBuilder(mesh);
  builder.begin();
  builder.addVertex(0);
  builder.addVertex(1);
  builder.addVertex(2);
  builder.end();
```

Ισούται με :

```
Mesh mesh = new Mesh();
  int[] indices = new int[] {0, 1, 2};
  mesh.createPolygon(indices);
```

Εάν όλα τα ευρετήρια είναι έτοιμα για χρήση, το [Mesh](../../com.aspose.threed/mesh) προτιμάται, διαφορετικά το [PolygonBuilder](../../com.aspose.threed/polygonbuilder) θα ήταν καλύτερη επιλογή.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [PolygonBuilder(Mesh mesh)](#PolygonBuilder-com.aspose.threed.Mesh-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PolygonBuilder](../../com.aspose.threed/polygonbuilder). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addVertex(int index)](#addVertex-int-) | Προσθέτει έναν δείκτη κορυφής στο πολύγωνο |
| [begin()](#begin--) | Ξεκινά την προσθήκη ενός νέου πολύγωνου |
| [end()](#end--) | Ολοκληρώνει τη δημιουργία του πολύγωνου |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PolygonBuilder(Mesh mesh) {#PolygonBuilder-com.aspose.threed.Mesh-}
```
public PolygonBuilder(Mesh mesh)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [PolygonBuilder](../../com.aspose.threed/polygonbuilder).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [Mesh](../../com.aspose.threed/mesh) | Σε ποιο πλέγμα θα δημιουργηθεί το πολύγωνο. |

### addVertex(int index) {#addVertex-int-}
```
public void addVertex(int index)
```


Προσθέτει έναν δείκτη κορυφής στο πολύγωνο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτης | int |  |

### begin() {#begin--}
```
public void begin()
```


Ξεκινά την προσθήκη ενός νέου πολύγωνου

### end() {#end--}
```
public void end()
```


Ολοκληρώνει τη δημιουργία του πολύγωνου

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

