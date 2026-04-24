---
title: Υφή
second_title: Aspose.3D for Java API Reference
description: Αυτή η κλάση ορίζει την υφή από ένα εξωτερικό αρχείο.
type: docs
weight: 184
url: /el/java/com.aspose.threed/texture/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.TextureBase](../../com.aspose.threed/texturebase)
```
public class Texture extends TextureBase
```

Αυτή η κλάση ορίζει την υφή από ένα εξωτερικό αρχείο.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [Texture()](#Texture--) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Texture](../../com.aspose.threed/texture). |
| [Texture(String name)](#Texture-java.lang.String-) | Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Texture](../../com.aspose.threed/texture). |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getAlpha()](#getAlpha--) | Λαμβάνει την προεπιλεγμένη τιμή άλφα της υφής. Αυτό ισχύει όταν το [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) είναι [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Η προεπιλεγμένη τιμή είναι 1.0, το έγκυρο εύρος τιμών είναι μεταξύ 0 και 1. |
| [getAlphaSource()](#getAlphaSource--) | Λαμβάνει αν η υφή ορίζει το κανάλι άλφα. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | Λαμβάνει το δυαδικό περιεχόμενο της υφής. |
| [getEnableMipMap()](#getEnableMipMap--) | Λαμβάνει αν το mipmap είναι ενεργοποιημένο για αυτήν την υφή |
| [getFileName()](#getFileName--) | Λαμβάνει το σχετικό αρχείο υφής. |
| [getMagFilter()](#getMagFilter--) | Λαμβάνει το φίλτρο για μεγέθυνση. |
| [getMinFilter()](#getMinFilter--) | Λαμβάνει το φίλτρο για σμίκρυνση. |
| [getMipFilter()](#getMipFilter--) | Λαμβάνει το φίλτρο για δειγματοληψία επιπέδου mip. |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getUVRotation()](#getUVRotation--) | Λαμβάνει την περιστροφή της υφής |
| [getUVScale()](#getUVScale--) | Λαμβάνει την κλίμακα UV. |
| [getUVTranslation()](#getUVTranslation--) | Λαμβάνει τη μετάφραση UV. |
| [getWrapModeU()](#getWrapModeU--) | Λαμβάνει τις λειτουργίες περιτύλιξης της υφής στο U. |
| [getWrapModeV()](#getWrapModeV--) | Λαμβάνει τις λειτουργίες περιτύλιξης της υφής στο V. |
| [getWrapModeW()](#getWrapModeW--) | Λαμβάνει τις λειτουργίες περιτύλιξης της υφής στο W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setAlpha(double value)](#setAlpha-double-) | Ορίζει την προεπιλεγμένη τιμή άλφα της υφής. Αυτό ισχύει όταν το [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) είναι [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Η προεπιλεγμένη τιμή είναι 1.0, το έγκυρο εύρος τιμών είναι μεταξύ 0 και 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Ορίζει αν η υφή ορίζει το κανάλι άλφα. |
| [setContent(byte[] value)](#setContent-byte---) | Ορίζει το δυαδικό περιεχόμενο της υφής. |
| [setEnableMipMap(boolean value)](#setEnableMipMap-boolean-) | Ορίζει αν το mipmap είναι ενεργοποιημένο για αυτήν την υφή |
| [setFileName(String value)](#setFileName-java.lang.String-) | Ορίζει το σχετικό αρχείο υφής. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Ορίζει το φίλτρο για μεγέθυνση. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Ορίζει το φίλτρο για σμίκρυνση. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Ορίζει το φίλτρο για δειγματοληψία επιπέδου mip. |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setRotation(double u, double v)](#setRotation-double-double-) | Ορίζει την περιστροφή UV. |
| [setScale(double u, double v)](#setScale-double-double-) | Ορίζει την κλίμακα UV. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | Ορίζει τη μετάφραση UV. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Ορίζει την περιστροφή της υφής |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | Ορίζει την κλίμακα UV. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | Ορίζει τη μετάφραση UV. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | Ορίζει τις λειτουργίες περιτύλιξης της υφής στο U. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | Ορίζει τις λειτουργίες περιτύλιξης της υφής στο V. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | Ορίζει τις λειτουργίες περιτύλιξης της υφής στο W. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Texture() {#Texture--}
```
public Texture()
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Texture](../../com.aspose.threed/texture).

### Texture(String name) {#Texture-java.lang.String-}
```
public Texture(String name)
```


Αρχικοποιεί ένα νέο αντικείμενο της κλάσης [Texture](../../com.aspose.threed/texture).

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String | Όνομα |

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
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Λαμβάνει την προεπιλεγμένη τιμή άλφα της υφής. Αυτό ισχύει όταν το [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) είναι [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Η προεπιλεγμένη τιμή είναι 1.0, το έγκυρο εύρος τιμών είναι μεταξύ 0 και 1.

**Returns:**
double - η προεπιλεγμένη τιμή άλφα της υφής. Αυτό είναι έγκυρο όταν το [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) είναι [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Η προεπιλεγμένη τιμή είναι 1.0, το έγκυρο εύρος τιμών είναι μεταξύ 0 και 1
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Λαμβάνει αν η υφή ορίζει το κανάλι άλφα. Η προεπιλεγμένη τιμή είναι [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContent() {#getContent--}
```
public byte[] getContent()
```


Λαμβάνει το δυαδικό περιεχόμενο της υφής. Το ενσωματωμένο περιεχόμενο της υφής είναι προαιρετικό, ο χρήστης πρέπει να φορτώσει την υφή από εξωτερικό αρχείο εάν λείπει.

**Returns:**
byte[] - το δυαδικό περιεχόμενο της υφής. Το ενσωματωμένο περιεχόμενο της υφής είναι προαιρετικό, ο χρήστης πρέπει να φορτώσει την υφή από εξωτερικό αρχείο εάν λείπει.
### getEnableMipMap() {#getEnableMipMap--}
```
public boolean getEnableMipMap()
```


Λαμβάνει αν το mipmap είναι ενεργοποιημένο για αυτήν την υφή

**Returns:**
boolean - αν το mipmap είναι ενεργοποιημένο για αυτήν την υφή
### getFileName() {#getFileName--}
```
public String getFileName()
```


Λαμβάνει το σχετικό αρχείο υφής.

**Returns:**
java.lang.String - το σχετικό αρχείο υφής.
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


Λαμβάνει το φίλτρο για μεγέθυνση.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Λαμβάνει το φίλτρο για σμίκρυνση.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Λαμβάνει το φίλτρο για δειγματοληψία επιπέδου mip.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
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
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Λαμβάνει την περιστροφή της υφής

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


Λαμβάνει την κλίμακα UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


Λαμβάνει τη μετάφραση UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


Λαμβάνει τις λειτουργίες περιτύλιξης της υφής στο U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


Λαμβάνει τις λειτουργίες περιτύλιξης της υφής στο V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


Λαμβάνει τις λειτουργίες περιτύλιξης της υφής στο W.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Ορίζει την προεπιλεγμένη τιμή άλφα της υφής. Αυτό ισχύει όταν το [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) είναι [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). Η προεπιλεγμένη τιμή είναι 1.0, το έγκυρο εύρος τιμών είναι μεταξύ 0 και 1.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Ορίζει αν η υφή ορίζει το κανάλι άλφα. Η προεπιλεγμένη τιμή είναι [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Νέα τιμή |

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Ορίζει το δυαδικό περιεχόμενο της υφής. Το ενσωματωμένο περιεχόμενο της υφής είναι προαιρετικό, ο χρήστης πρέπει να φορτώσει την υφή από εξωτερικό αρχείο εάν λείπει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] | Νέα τιμή |

### setEnableMipMap(boolean value) {#setEnableMipMap-boolean-}
```
public void setEnableMipMap(boolean value)
```


Ορίζει αν το mipmap είναι ενεργοποιημένο για αυτήν την υφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Ορίζει το σχετικό αρχείο υφής.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Ορίζει το φίλτρο για μεγέθυνση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Νέα τιμή |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Ορίζει το φίλτρο για σμίκρυνση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Νέα τιμή |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Ορίζει το φίλτρο για δειγματοληψία επιπέδου mip.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Νέα τιμή |

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

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


Ορίζει την περιστροφή UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


Ορίζει την κλίμακα UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


Ορίζει τη μετάφραση UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Ορίζει την περιστροφή της υφής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Νέα τιμή |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


Ορίζει την κλίμακα UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Νέα τιμή |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


Ορίζει τη μετάφραση UV.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Νέα τιμή |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


Ορίζει τις λειτουργίες περιτύλιξης της υφής στο U.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Νέα τιμή |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


Ορίζει τις λειτουργίες περιτύλιξης της υφής στο V.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Νέα τιμή |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


Ορίζει τις λειτουργίες περιτύλιξης της υφής στο W.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Νέα τιμή |

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

