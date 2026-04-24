---
title: PbrSpecularMaterial
second_title: Aspose.3D for Java API Reference
description: Υλικό για φυσικά-βασισμένη απόδοση βασισμένο στο διαχυτικό χρώμα/συγκοπτικό/γυαλάδα
type: docs
weight: 122
url: /el/java/com.aspose.threed/pbrspecularmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrSpecularMaterial extends Material
```

Υλικό για φυσικά-βασισμένη απόδοση βασισμένο στο διαχυτικό χρώμα/συγκοπτικό/γυαλάδα
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [PbrSpecularMaterial()](#PbrSpecularMaterial--) | Κατασκευαστής του [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial) |
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [MAP_AMBIENT](#MAP-AMBIENT) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας ατμοσφαιρικής χαρτογράφησης υφής. |
| [MAP_DIFFUSE](#MAP-DIFFUSE) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας διαχυτικής χαρτογράφησης υφής. |
| [MAP_EMISSIVE](#MAP-EMISSIVE) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας εκπεμπόμενης χαρτογράφησης υφής. |
| [MAP_NORMAL](#MAP-NORMAL) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας κανονικής χαρτογράφησης υφής. |
| [MAP_SPECULAR](#MAP-SPECULAR) | Χρησιμοποιείται στο [setTexture](../../com.aspose.threed/material\#setTexture) για την ανάθεση μιας αντικατοπτριστικής χαρτογράφησης υφής. |
| [MAP_SPECULAR_GLOSSINESS](#MAP-SPECULAR-GLOSSINESS) | Ο χάρτης υφής για τη γυαλότητα του specular |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getClass()](#getClass--) |  |
| [getDiffuse()](#getDiffuse--) | Λαμβάνει το διάχυτο χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1) |
| [getDiffuseTexture()](#getDiffuseTexture--) | Λαμβάνει την υφή για το διάχυτο |
| [getEmissiveColor()](#getEmissiveColor--) | Λαμβάνει το εκπεμπόμενο χρώμα, η προεπιλεγμένη τιμή είναι (0, 0, 0) |
| [getEmissiveTexture()](#getEmissiveTexture--) | Λαμβάνει την υφή για το εκπεμπόμενο |
| [getGlossinessFactor()](#getGlossinessFactor--) | Λαμβάνει τη γυαλότητα (ομαλότητα) του υλικού, 1 σημαίνει απολύτως ομαλό και 0 σημαίνει απολύτως τραχύ, η προεπιλεγμένη τιμή είναι 1, το εύρος είναι [0, 1] |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getNormalTexture()](#getNormalTexture--) | Λαμβάνει την υφή της κανονικής χαρτογράφησης |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getSpecular()](#getSpecular--) | Λαμβάνει το specular χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1). |
| [getSpecularGlossinessTexture()](#getSpecularGlossinessTexture--) | Λαμβάνει την υφή για το specular χρώμα, το κανάλι RGB αποθηκεύει το specular χρώμα και το κανάλι A αποθηκεύει τη γυαλότητα. |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Λαμβάνει την υφή από το καθορισμένο slot, μπορεί να είναι το όνομα ιδιότητας του υλικού ή το όνομα παραμέτρου του shader. |
| [getTransparency()](#getTransparency--) | Λαμβάνει τον παράγοντα διαφάνειας. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Λαμβάνει τον απαριθμητή για την απαρίθμηση των εσωτερικών θέσεων υφής. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setDiffuse(Vector3 value)](#setDiffuse-com.aspose.threed.Vector3-) | Ορίζει το διάχυτο χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1) |
| [setDiffuseTexture(TextureBase value)](#setDiffuseTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή για το διάχυτο |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Ορίζει το εκπεμπόμενο χρώμα, η προεπιλεγμένη τιμή είναι (0, 0, 0) |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή για την εκπομπή |
| [setGlossinessFactor(double value)](#setGlossinessFactor-double-) | Ορίζει τη γυαλάδα (ομαλότητα) του υλικού, το 1 σημαίνει απόλυτα ομαλό και το 0 σημαίνει απόλυτα τραχύ, η προεπιλεγμένη τιμή είναι 1, το εύρος είναι [0, 1] |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή της κανονικής χαρτογράφησης |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setSpecular(Vector3 value)](#setSpecular-com.aspose.threed.Vector3-) | Ορίζει το καθρεπτικό χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1). |
| [setSpecularGlossinessTexture(TextureBase value)](#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή για το καθρεπτικό χρώμα, το κανάλι RGB αποθηκεύει το καθρεπτικό χρώμα και το κανάλι A αποθηκεύει τη γυαλάδα. |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ορίζει την υφή στο καθορισμένο slot |
| [setTransparency(double value)](#setTransparency-double-) | Ορίζει τον παράγοντα διαφάνειας. |
| [toString()](#toString--) | Μετατρέπει το αντικείμενο σε συμβολοσειρά |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrSpecularMaterial() {#PbrSpecularMaterial--}
```
public PbrSpecularMaterial()
```


Κατασκευαστής του [PbrSpecularMaterial](../../com.aspose.threed/pbrspecularmaterial)

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

### MAP_SPECULAR_GLOSSINESS {#MAP-SPECULAR-GLOSSINESS}
```
public static final String MAP_SPECULAR_GLOSSINESS
```


Ο χάρτης υφής για τη γυαλότητα του specular

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
### getDiffuse() {#getDiffuse--}
```
public Vector3 getDiffuse()
```


Λαμβάνει το διάχυτο χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the diffuse color of the material, default value is (1, 1, 1)
### getDiffuseTexture() {#getDiffuseTexture--}
```
public TextureBase getDiffuseTexture()
```


Λαμβάνει την υφή για το διάχυτο

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for diffuse
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Λαμβάνει το εκπεμπόμενο χρώμα, η προεπιλεγμένη τιμή είναι (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color, default value is (0, 0, 0)
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Λαμβάνει την υφή για το εκπεμπόμενο

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getGlossinessFactor() {#getGlossinessFactor--}
```
public double getGlossinessFactor()
```


Λαμβάνει τη γυαλότητα (ομαλότητα) του υλικού, 1 σημαίνει απολύτως ομαλό και 0 σημαίνει απολύτως τραχύ, η προεπιλεγμένη τιμή είναι 1, το εύρος είναι [0, 1]

**Returns:**
double - η γυαλάδα (ομαλότητα) του υλικού, το 1 σημαίνει απόλυτα ομαλό και το 0 σημαίνει απόλυτα τραχύ, η προεπιλεγμένη τιμή είναι 1, το εύρος είναι [0, 1]
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getNormalTexture() {#getNormalTexture--}
```
public TextureBase getNormalTexture()
```


Λαμβάνει την υφή της κανονικής χαρτογράφησης

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture of normal mapping
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
### getSpecular() {#getSpecular--}
```
public Vector3 getSpecular()
```


Λαμβάνει το specular χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the specular color of the material, default value is (1, 1, 1).
### getSpecularGlossinessTexture() {#getSpecularGlossinessTexture--}
```
public TextureBase getSpecularGlossinessTexture()
```


Λαμβάνει την υφή για το specular χρώμα, το κανάλι RGB αποθηκεύει το specular χρώμα και το κανάλι A αποθηκεύει τη γυαλότητα.

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color, channel RGB stores the specular color and channel A stores the glossiness.
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
### setDiffuse(Vector3 value) {#setDiffuse-com.aspose.threed.Vector3-}
```
public void setDiffuse(Vector3 value)
```


Ορίζει το διάχυτο χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setDiffuseTexture(TextureBase value) {#setDiffuseTexture-com.aspose.threed.TextureBase-}
```
public void setDiffuseTexture(TextureBase value)
```


Ορίζει την υφή για το διάχυτο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Νέα τιμή |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Ορίζει το εκπεμπόμενο χρώμα, η προεπιλεγμένη τιμή είναι (0, 0, 0)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setEmissiveTexture(TextureBase value) {#setEmissiveTexture-com.aspose.threed.TextureBase-}
```
public void setEmissiveTexture(TextureBase value)
```


Ορίζει την υφή για την εκπομπή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Νέα τιμή |

### setGlossinessFactor(double value) {#setGlossinessFactor-double-}
```
public void setGlossinessFactor(double value)
```


Ορίζει τη γυαλάδα (ομαλότητα) του υλικού, το 1 σημαίνει απόλυτα ομαλό και το 0 σημαίνει απόλυτα τραχύ, η προεπιλεγμένη τιμή είναι 1, το εύρος είναι [0, 1]

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ορίζει το όνομα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setNormalTexture(TextureBase value) {#setNormalTexture-com.aspose.threed.TextureBase-}
```
public void setNormalTexture(TextureBase value)
```


Ορίζει την υφή της κανονικής χαρτογράφησης

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Νέα τιμή |

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

### setSpecular(Vector3 value) {#setSpecular-com.aspose.threed.Vector3-}
```
public void setSpecular(Vector3 value)
```


Ορίζει το καθρεπτικό χρώμα του υλικού, η προεπιλεγμένη τιμή είναι (1, 1, 1).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setSpecularGlossinessTexture(TextureBase value) {#setSpecularGlossinessTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularGlossinessTexture(TextureBase value)
```


Ορίζει την υφή για το καθρεπτικό χρώμα, το κανάλι RGB αποθηκεύει το καθρεπτικό χρώμα και το κανάλι A αποθηκεύει τη γυαλάδα.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Νέα τιμή |

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

