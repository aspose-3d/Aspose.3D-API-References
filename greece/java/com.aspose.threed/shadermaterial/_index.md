---
title: ShaderMaterial
second_title: Aspose.3D for Java API Reference
description: Ένα υλικό shader επιτρέπει την περιγραφή του υλικού από εξωτερική μηχανή απόδοσης ή γλώσσα shader.
type: docs
weight: 164
url: /el/java/com.aspose.threed/shadermaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class ShaderMaterial extends Material
```

Ένα υλικό σκίασης επιτρέπει την περιγραφή του υλικού από εξωτερική μηχανή απόδοσης ή γλώσσα σκίασης. [ShaderMaterial](../../com.aspose.threed/shadermaterial) χρησιμοποιεί το [ShaderTechnique](../../com.aspose.threed/shadertechnique) για να περιγράψει τις συγκεκριμένες λεπτομέρειες απόδοσης, και το πιο κατάλληλο θα χρησιμοποιηθεί ανάλογα με την τελική πλατφόρμα απόδοσης. Για παράδειγμα, η παρουσία σας του [ShaderMaterial](../../com.aspose.threed/shadermaterial) μπορεί να έχει δύο τεχνικές, η μία ορίζεται από HLSL και η άλλη από GLSL. Σε πλατφόρμα χωρίς παράθυρο, το GLSL θα πρέπει να χρησιμοποιείται αντί του HLSL.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [ShaderMaterial()](#ShaderMaterial--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ShaderMaterial](../../com.aspose.threed/shadermaterial). |
| [ShaderMaterial(String name)](#ShaderMaterial-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [ShaderMaterial](../../com.aspose.threed/shadermaterial). |
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
| [getClass()](#getClass--) |  |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getTechniques()](#getTechniques--) | Λαμβάνει όλες τις διαθέσιμες τεχνικές που ορίζονται σε αυτό το υλικό. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Λαμβάνει την υφή από το καθορισμένο slot, μπορεί να είναι το όνομα ιδιότητας του υλικού ή το όνομα παραμέτρου του shader. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Λαμβάνει τον απαριθμητή για την απαρίθμηση των εσωτερικών θέσεων υφής. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ορίζει την υφή στο καθορισμένο slot |
| [toString()](#toString--) | Μετατρέπει το αντικείμενο σε συμβολοσειρά |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderMaterial() {#ShaderMaterial--}
```
public ShaderMaterial()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [ShaderMaterial](../../com.aspose.threed/shadermaterial).

### ShaderMaterial(String name) {#ShaderMaterial-java.lang.String-}
```
public ShaderMaterial(String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [ShaderMaterial](../../com.aspose.threed/shadermaterial).

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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
### getTechniques() {#getTechniques--}
```
public List<ShaderTechnique> getTechniques()
```


Λαμβάνει όλες τις διαθέσιμες τεχνικές που ορίζονται σε αυτό το υλικό.

**Returns:**
java.util.List<com.aspose.threed.ShaderTechnique> - όλες τις διαθέσιμες τεχνικές που ορίζονται σε αυτό το υλικό.
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

