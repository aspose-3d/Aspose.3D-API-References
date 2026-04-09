---
title: PbrMaterial
second_title: Aspose.3D for Java API Reference
description: Υλικό για φυσικά-βασισμένη απόδοση (physically based rendering) βασισμένο στο χρώμα αλμπέντο/μετάλλιο/τραχύτητα
type: docs
weight: 121
url: /el/java/com.aspose.threed/pbrmaterial/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.Material](../../com.aspose.threed/material)
```
public class PbrMaterial extends Material
```

Υλικό για φυσικά-βασισμένη απόδοση (physically based rendering) βασισμένο στο χρώμα αλμπέντο/μετάλλιο/τραχύτητα
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [PbrMaterial()](#PbrMaterial--) | Δημιουργήστε μια προεπιλεγμένη παρουσία υλικού PBR |
| [PbrMaterial(Vector3 albedo)](#PbrMaterial-com.aspose.threed.Vector3-) | Δημιουργήστε ένα προεπιλεγμένο υλικό PBR με καθορισμένη τιμή χρώματος αλμπέδο. |
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
| [fromMaterial(Material material)](#fromMaterial-com.aspose.threed.Material-) | Επιτρέψτε τη μετατροπή άλλου υλικού σε PbrMaterial **Παράδειγμα:** |
| [getAlbedo()](#getAlbedo--) | Λαμβάνει το βασικό χρώμα του υλικού |
| [getAlbedoTexture()](#getAlbedoTexture--) | Λαμβάνει την υφή για το αλμπέδο |
| [getClass()](#getClass--) |  |
| [getEmissiveColor()](#getEmissiveColor--) | Λαμβάνει το εκπεμπόμενο χρώμα |
| [getEmissiveTexture()](#getEmissiveTexture--) | Λαμβάνει την υφή για το εκπεμπόμενο |
| [getMetallicFactor()](#getMetallicFactor--) | Λαμβάνει τη μεταλλικότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι μέταλλο και η τιμή 0 σημαίνει ότι το υλικό είναι διηλεκτρικό. |
| [getMetallicRoughness()](#getMetallicRoughness--) | Λαμβάνει την υφή για το μεταλλικό (στο κανάλι R) και την τραχύτητα (στο κανάλι G) |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getNormalTexture()](#getNormalTexture--) | Λαμβάνει την υφή της κανονικής χαρτογράφησης |
| [getOcclusionFactor()](#getOcclusionFactor--) | Λαμβάνει τον παράγοντα της απόσβεσης περιβάλλοντος |
| [getOcclusionTexture()](#getOcclusionTexture--) | Λαμβάνει την υφή για την απόσβεση περιβάλλοντος |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getRoughnessFactor()](#getRoughnessFactor--) | Λαμβάνει την τραχύτητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι εντελώς τραχύ και η τιμή 0 σημαίνει ότι το υλικό είναι εντελώς λείο. |
| [getSpecularTexture()](#getSpecularTexture--) | Λαμβάνει την υφή για το καθρεπτικό χρώμα |
| [getTexture(String slotName)](#getTexture-java.lang.String-) | Λαμβάνει την υφή από το καθορισμένο slot, μπορεί να είναι το όνομα ιδιότητας του υλικού ή το όνομα παραμέτρου του shader. |
| [getTransparency()](#getTransparency--) | Λαμβάνει τον παράγοντα διαφάνειας. |
| [hashCode()](#hashCode--) |  |
| [iterator()](#iterator--) | Λαμβάνει τον απαριθμητή για την απαρίθμηση των εσωτερικών θέσεων υφής. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setAlbedo(Vector3 value)](#setAlbedo-com.aspose.threed.Vector3-) | Ορίζει το βασικό χρώμα του υλικού |
| [setAlbedoTexture(TextureBase value)](#setAlbedoTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή για το albedo |
| [setEmissiveColor(Vector3 value)](#setEmissiveColor-com.aspose.threed.Vector3-) | Ορίζει το εκπεμπόμενο χρώμα |
| [setEmissiveTexture(TextureBase value)](#setEmissiveTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή για την εκπομπή |
| [setMetallicFactor(double value)](#setMetallicFactor-double-) | Ορίζει τη μεταλλικότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι μέταλλο και η τιμή 0 σημαίνει ότι το υλικό είναι διηλεκτρικό. |
| [setMetallicRoughness(TextureBase value)](#setMetallicRoughness-com.aspose.threed.TextureBase-) | Ορίζει την υφή για το metallic (στο κανάλι R) και το roughness (στο κανάλι G) |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setNormalTexture(TextureBase value)](#setNormalTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή της κανονικής χαρτογράφησης |
| [setOcclusionFactor(double value)](#setOcclusionFactor-double-) | Ορίζει τον παράγοντα του ambient occlusion |
| [setOcclusionTexture(TextureBase value)](#setOcclusionTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή για το ambient occlusion |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setRoughnessFactor(double value)](#setRoughnessFactor-double-) | Ορίζει τη σκληρότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι εντελώς σκληρό και η τιμή 0 σημαίνει ότι το υλικό είναι εντελώς λείο. |
| [setSpecularTexture(TextureBase value)](#setSpecularTexture-com.aspose.threed.TextureBase-) | Ορίζει την υφή για το specular color |
| [setTexture(String slotName, TextureBase texture)](#setTexture-java.lang.String-com.aspose.threed.TextureBase-) | Ορίζει την υφή στο καθορισμένο slot |
| [setTransparency(double value)](#setTransparency-double-) | Ορίζει τον παράγοντα διαφάνειας. |
| [toString()](#toString--) | Μετατρέπει το αντικείμενο σε συμβολοσειρά |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PbrMaterial() {#PbrMaterial--}
```
public PbrMaterial()
```


Δημιουργήστε μια προεπιλεγμένη παρουσία υλικού PBR

### PbrMaterial(Vector3 albedo) {#PbrMaterial-com.aspose.threed.Vector3-}
```
public PbrMaterial(Vector3 albedo)
```


Δημιουργήστε ένα προεπιλεγμένο υλικό PBR με καθορισμένη τιμή χρώματος αλμπέδο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| albedo | [Vector3](../../com.aspose.threed/vector3) | Η προεπιλεγμένη τιμή χρώματος albedo |

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
### fromMaterial(Material material) {#fromMaterial-com.aspose.threed.Material-}
```
public static PbrMaterial fromMaterial(Material material)
```


Επιτρέψτε τη μετατροπή άλλου υλικού σε PbrMaterial **Παράδειγμα:**

```
var mat = new LambertMaterial();
     var tex = new Texture();
     tex.setFileName("diffuse.png");
     mat.setTexture(Material.MAP_DIFFUSE, tex);
     mat.setDiffuseColor(new Vector3(0.3, 0.9, 0.4));
     PbrMaterial pbr = PbrMaterial.fromMaterial(mat);
```

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| material | [Material](../../com.aspose.threed/material) |  |

**Returns:**
[PbrMaterial](../../com.aspose.threed/pbrmaterial)
### getAlbedo() {#getAlbedo--}
```
public Vector3 getAlbedo()
```


Λαμβάνει το βασικό χρώμα του υλικού

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the base color of the material
### getAlbedoTexture() {#getAlbedoTexture--}
```
public TextureBase getAlbedoTexture()
```


Λαμβάνει την υφή για το αλμπέδο

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for albedo
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEmissiveColor() {#getEmissiveColor--}
```
public Vector3 getEmissiveColor()
```


Λαμβάνει το εκπεμπόμενο χρώμα

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the emissive color
### getEmissiveTexture() {#getEmissiveTexture--}
```
public TextureBase getEmissiveTexture()
```


Λαμβάνει την υφή για το εκπεμπόμενο

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for emissive
### getMetallicFactor() {#getMetallicFactor--}
```
public double getMetallicFactor()
```


Λαμβάνει τη μεταλλικότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι μέταλλο και η τιμή 0 σημαίνει ότι το υλικό είναι διηλεκτρικό.

**Returns:**
double - η μεταλλικότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι μέταλλο και η τιμή 0 σημαίνει ότι το υλικό είναι διηλεκτρικό.
### getMetallicRoughness() {#getMetallicRoughness--}
```
public TextureBase getMetallicRoughness()
```


Λαμβάνει την υφή για το μεταλλικό (στο κανάλι R) και την τραχύτητα (στο κανάλι G)

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for metallic(in R channel) and roughness(in G channel)
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
### getOcclusionFactor() {#getOcclusionFactor--}
```
public double getOcclusionFactor()
```


Λαμβάνει τον παράγοντα της απόσβεσης περιβάλλοντος

**Returns:**
double - ο παράγοντας του ambient occlusion
### getOcclusionTexture() {#getOcclusionTexture--}
```
public TextureBase getOcclusionTexture()
```


Λαμβάνει την υφή για την απόσβεση περιβάλλοντος

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for ambient occlusion
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
### getRoughnessFactor() {#getRoughnessFactor--}
```
public double getRoughnessFactor()
```


Λαμβάνει την τραχύτητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι εντελώς τραχύ και η τιμή 0 σημαίνει ότι το υλικό είναι εντελώς λείο.

**Returns:**
double - η σκληρότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι εντελώς σκληρό και η τιμή 0 σημαίνει ότι το υλικό είναι εντελώς λείο.
### getSpecularTexture() {#getSpecularTexture--}
```
public TextureBase getSpecularTexture()
```


Λαμβάνει την υφή για το καθρεπτικό χρώμα

**Returns:**
[TextureBase](../../com.aspose.threed/texturebase) - the texture for specular color
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
### setAlbedo(Vector3 value) {#setAlbedo-com.aspose.threed.Vector3-}
```
public void setAlbedo(Vector3 value)
```


Ορίζει το βασικό χρώμα του υλικού

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setAlbedoTexture(TextureBase value) {#setAlbedoTexture-com.aspose.threed.TextureBase-}
```
public void setAlbedoTexture(TextureBase value)
```


Ορίζει την υφή για το albedo

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Νέα τιμή |

### setEmissiveColor(Vector3 value) {#setEmissiveColor-com.aspose.threed.Vector3-}
```
public void setEmissiveColor(Vector3 value)
```


Ορίζει το εκπεμπόμενο χρώμα

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

### setMetallicFactor(double value) {#setMetallicFactor-double-}
```
public void setMetallicFactor(double value)
```


Ορίζει τη μεταλλικότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι μέταλλο και η τιμή 0 σημαίνει ότι το υλικό είναι διηλεκτρικό.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setMetallicRoughness(TextureBase value) {#setMetallicRoughness-com.aspose.threed.TextureBase-}
```
public void setMetallicRoughness(TextureBase value)
```


Ορίζει την υφή για το metallic (στο κανάλι R) και το roughness (στο κανάλι G)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureBase](../../com.aspose.threed/texturebase) | Νέα τιμή |

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

### setOcclusionFactor(double value) {#setOcclusionFactor-double-}
```
public void setOcclusionFactor(double value)
```


Ορίζει τον παράγοντα του ambient occlusion

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setOcclusionTexture(TextureBase value) {#setOcclusionTexture-com.aspose.threed.TextureBase-}
```
public void setOcclusionTexture(TextureBase value)
```


Ορίζει την υφή για το ambient occlusion

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

### setRoughnessFactor(double value) {#setRoughnessFactor-double-}
```
public void setRoughnessFactor(double value)
```


Ορίζει τη σκληρότητα του υλικού, η τιμή 1 σημαίνει ότι το υλικό είναι εντελώς σκληρό και η τιμή 0 σημαίνει ότι το υλικό είναι εντελώς λείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setSpecularTexture(TextureBase value) {#setSpecularTexture-com.aspose.threed.TextureBase-}
```
public void setSpecularTexture(TextureBase value)
```


Ορίζει την υφή για το specular color

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

