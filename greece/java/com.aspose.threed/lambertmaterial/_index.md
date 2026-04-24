---
title: LambertMaterial
second_title: Aspose.3D for Java API Reference
description: Υλικό για το μοντέλο σκίασης Lambert
type: docs
weight: 92
url: /el/java/com.aspose.threed/lambertmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class LambertMaterial extends Material
```

Υλικό για το μοντέλο σκίασης Lambert
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [LambertMaterial()](#LambertMaterial--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LambertMaterial](../../com.aspose.threed/lambertmaterial). |
| [LambertMaterial(String name)](#LambertMaterial-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LambertMaterial](../../com.aspose.threed/lambertmaterial). |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας ατμοσφαιρικής χαρτογράφησης υφής. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας διαχυτικής χαρτογράφησης υφής. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας εκπεμπόμενης χαρτογράφησης υφής. |
| [MAP_NORMAL](#MAP-NORMAL) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας κανονικής χαρτογράφησης υφής. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας αντικατοπτριστικής χαρτογράφησης υφής. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getAmbientColor()](#getAmbientColor--) | Λαμβάνει το ατμοσφαιρικό χρώμα |
| [getClass()](#getClass--) |  |
| [getDiffuseColor()](#getDiffuseColor--) | Λαμβάνει το διαχυτικό χρώμα |
| [getEmissiveColor()](#getEmissiveColor--) | Λαμβάνει το εκπεμπόμενο χρώμα |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Λαμβάνει την υφή από το καθορισμένο slot, μπορεί να είναι το όνομα ιδιότητας του υλικού ή το όνομα παραμέτρου του shader. |
| [getTransparency()](#getTransparency--) | Λαμβάνει τον παράγοντα διαφάνειας. |
| [getTransparentColor()](#getTransparentColor--) | Λαμβάνει το διαφανές χρώμα. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Λαμβάνει τον απαριθμητή για την απαρίθμηση των εσωτερικών θέσεων υφής. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setAmbientColor(Vector3 value)](#setAmbientColor-com.aspose.threed.Vector3-) | Ορίζει το ατμοσφαιρικό χρώμα |
| [setDiffuseColor(Vector3 value)](#setDiffuseColor-com.aspose.threed.Vector3-) | Ορίζει το διαχυτικό χρώμα |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Ορίζει το εκπεμπόμενο χρώμα |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ορίζει την υφή στο καθορισμένο slot |
| [setTransparency(double value)](#setTransparency-double-) | Ορίζει τον παράγοντα διαφάνειας. |
| [setTransparentColor(Vector3 value)](#setTransparentColor-com.aspose.threed.Vector3-) | Ορίζει το διαφανές χρώμα |
| [toString()](#toString--) | Μετατρέπει το αντικείμενο σε συμβολοσειρά |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### LambertMaterial() {#LambertMaterial--}
```
public LambertMaterial()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LambertMaterial](../../com.aspose.threed/lambertmaterial).

### LambertMaterial(String name) {#LambertMaterial-java.lang.String-}
```
public LambertMaterial(String name)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [LambertMaterial](../../com.aspose.threed/lambertmaterial).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα |

### MAP_AMBIENT {#MAP-AMBIENT}
```
public static final String MAP_AMBIENT
```


Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας ατμοσφαιρικής χαρτογράφησης υφής.

### MAP_DIFFUSE {#MAP-DIFFUSE}
```
public static final String MAP_DIFFUSE
```


Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας διαχυτικής χαρτογράφησης υφής.

### MAP_EMISSIVE {#MAP-EMISSIVE}
```
public static final String MAP_EMISSIVE
```


Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας εκπεμπόμενης χαρτογράφησης υφής.

### MAP_NORMAL {#MAP-NORMAL}
```
public static final String MAP_NORMAL
```


Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας κανονικής χαρτογράφησης υφής.

### MAP_SPECULAR {#MAP-SPECULAR}
```
public static final String MAP_SPECULAR
```


Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας αντικατοπτριστικής χαρτογράφησης υφής.

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Βρίσκει την ιδιότητα. Μπορεί να είναι μια δυναμική ιδιότητα (Δημιουργήθηκε με CreateDynamicProperty/SetProperty) ή εγγενής ιδιότητα (Προσδιορίζεται με το όνομά της)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| propertyName | java.lang.String | Όνομα ιδιότητας. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAmbientColor() {#getAmbientColor--}
```
public Vector3 getAmbientColor()
```


Λαμβάνει το ατμοσφαιρικό χρώμα

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the ambient color
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDiffuseColor() {#getDiffuseColor--}
```
public Vector3 getDiffuseColor()
```


Λαμβάνει το διαχυτικό χρώμα

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Λαμβάνει το εκπεμπόμενο χρώμα

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color **Example:**

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
```
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Λαμβάνει τη συλλογή όλων των ιδιοτήτων.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Λάβετε την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |

**Returns:**
java.lang.Object - Η τιμή της ευρεθείσας ιδιότητας
### getTexture(String slotName) {#getTexture-java.lang.String-}
```
public TextureBase getTexture(String slotName)
```


Λαμβάνει την υφή από το καθορισμένο slot, μπορεί να είναι το όνομα ιδιότητας του υλικού ή το όνομα παραμέτρου του shader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slotName | java.lang.String | Όνομα υποδοχής. |

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - The texture. **Example:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     tex = (Texture)mat.getTexture(Material.MAP_DIFFUSE);
```
### getTransparency() {#getTransparency--}
```
public double getTransparency()
```


Λαμβάνει τον παράγοντα διαφάνειας. Ο παράγοντας πρέπει να βρίσκεται στο εύρος μεταξύ 0 (0%, πλήρως αδιαφανές) και 1 (100%, πλήρως διαφανές). Οποιαδήποτε μη έγκυρη τιμή παράγοντα θα περιοριστεί.

**Returns:**
double - ο παράγοντας διαφάνειας. Ο παράγοντας πρέπει να βρίσκεται στο εύρος μεταξύ 0 (0%, πλήρως αδιαφανές) και 1 (100%, πλήρως διαφανές). Οποιαδήποτε μη έγκυρη τιμή παράγοντα θα περιοριστεί.
### getTransparentColor() {#getTransparentColor--}
```
public Vector3 getTransparentColor()
```


Λαμβάνει το διαφανές χρώμα.

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the transparent color.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### iterator() {#iterator--}
```
public Iterator<TextureSlot> iterator()
```


Λαμβάνει τον απαριθμητή για την απαρίθμηση των εσωτερικών θέσεων υφής.

**Returns:**
java.util.Iterator<com.aspose.threed.TextureSlot>
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Αφαιρεί μια δυναμική ιδιότητα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Ποια ιδιότητα να αφαιρεθεί |

**Returns:**
boolean - true εάν η ιδιότητα αφαιρεθεί επιτυχώς
### setAmbientColor(Vector3 value) {#setAmbientColor-com.aspose.threed.Vector3-}
```
public void setAmbientColor(Vector3 value)
```


Ορίζει το ατμοσφαιρικό χρώμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setDiffuseColor(Vector3 value) {#setDiffuseColor-com.aspose.threed.Vector3-}
```
public void setDiffuseColor(Vector3 value)
```


Ορίζει το διαχυτικό χρώμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Ορίζει το εκπεμπόμενο χρώμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή **Example:** |

```
var mat = new LambertMaterial();
     mat.setEmissiveColor(new Vector3(1, 1, 1));
``` |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ορίζει την τιμή της συγκεκριμένης ιδιότητας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Όνομα ιδιότητας |
| τιμή | java.lang.Object | Η τιμή της ιδιότητας |

### setTexture(String slotName, TextureBase texture) {#setTexture-java.lang.String-com.aspose.threed.TextureBase-}
```
public void setTexture(String slotName, TextureBase texture)
```


Ορίζει την υφή στο καθορισμένο slot

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slotName | java.lang.String | Όνομα υποδοχής. |
|  | texture | [TextureBase](../../com.aspose.threed/texturebase) | Υφή. **Example:** |

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_NORMAL, tex);
``` |

### setTransparency(double value) {#setTransparency-double-}
```
public void setTransparency(double value)
```


Ορίζει τον παράγοντα διαφάνειας. Ο παράγοντας πρέπει να βρίσκεται στο εύρος μεταξύ 0 (0%, πλήρως αδιαφανές) και 1 (100%, πλήρως διαφανές). Οποιαδήποτε μη έγκυρη τιμή παράγοντα θα περιοριστεί.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setTransparentColor(Vector3 value) {#setTransparentColor-com.aspose.threed.Vector3-}
```
public void setTransparentColor(Vector3 value)
```


Ορίζει το διαφανές χρώμα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### toString() {#toString--}
```
public String toString()
```


Μετατρέπει το αντικείμενο σε συμβολοσειρά

**Returns:**
java.lang.String - Συμβολοσειρά αντικειμένου
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

