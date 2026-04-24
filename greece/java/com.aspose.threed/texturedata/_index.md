---
title: TextureData
second_title: Aspose.3D for Java API Reference
description: Αυτή η κλάση περιέχει τα ακατέργαστα δεδομένα και τον ορισμό μορφής μιας υφής.
type: docs
weight: 187
url: /el/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

Αυτή η κλάση περιέχει τα ακατέργαστα δεδομένα και τον ορισμό μορφής μιας υφής.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | Κατασκευαστής του [TextureData](../../com.aspose.threed/texturedata) |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | Δημιουργεί ένα νέο [TextureData](../../com.aspose.threed/texturedata) και εκχωρεί δεδομένα εικονοστοιχείου. |
| [TextureData()](#TextureData--) | Κατασκευαστής του [TextureData](../../com.aspose.threed/texturedata) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Φορτώστε μια υφή από αρχείο |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Φορτώστε μια υφή από ροή |
| [getBytesPerPixel()](#getBytesPerPixel--) | Αριθμός byte ενός εικονοστοιχείου |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Ακατέργαστα byte δεδομένων εικονοστοιχείου |
| [getHeight()](#getHeight--) | Αριθμός κάθετων εικονοστοιχείων |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getPixelFormat()](#getPixelFormat--) | Η μορφή του εικονοστοιχείου |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getStride()](#getStride--) | Αριθμός byte μιας γραμμής σάρωσης. |
| [getWidth()](#getWidth--) | Αριθμός οριζόντιων εικονοστοιχείων |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | Αντιστοίχηση όλων των εικονοστοιχείων για ανάγνωση/εγγραφή |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Αντιστοίχηση όλων των εικονοστοιχείων για ανάγνωση/εγγραφή σε δεδομένη μορφή εικονοστοιχείου |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Αντιστοίχηση εικονοστοιχείων που προσδιορίζονται από το rect για ανάγνωση/εγγραφή σε δεδομένη μορφή εικονοστοιχείου |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | Αποθήκευση δεδομένων υφής σε καθορισμένη μορφή εικόνας |
| [save(String fileName)](#save-java.lang.String-) | Αποθήκευση δεδομένων υφής σε αρχείο εικόνας |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | Αποθήκευση δεδομένων υφής σε αρχείο εικόνας |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | Μετασχηματισμός της διάταξης του εικονοστοιχείου σε νέα μορφή εικονοστοιχείου. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


Κατασκευαστής του [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | int |  |
| height | int |  |
| stride | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| δεδομένα | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


Δημιουργεί ένα νέο [TextureData](../../com.aspose.threed/texturedata) και εκχωρεί δεδομένα εικονοστοιχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | int |  |
| height | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


Κατασκευαστής του [TextureData](../../com.aspose.threed/texturedata)

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


Φορτώστε μια υφή από αρχείο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Φορτώστε μια υφή από ροή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Αριθμός byte ενός εικονοστοιχείου

**Returns:**
int - Αριθμός byte ενός εικονοστοιχείου
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


Ακατέργαστα byte δεδομένων εικονοστοιχείου

**Returns:**
byte[] - Ακατέργαστα byte δεδομένων εικονοστοιχείου
### getHeight() {#getHeight--}
```
public int getHeight()
```


Αριθμός κάθετων εικονοστοιχείων

**Returns:**
int - Αριθμός κάθετων εικονοστοιχείων
### getName() {#getName--}
```
public String getName()
```


Λαμβάνει το όνομα.

**Returns:**
java.lang.String - το όνομα.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


Η μορφή του εικονοστοιχείου

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


Αριθμός byte μιας γραμμής σάρωσης.

**Returns:**
int - Αριθμός byte μιας γραμμής σάρωσης.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Αριθμός οριζόντιων εικονοστοιχείων

**Returns:**
int - Αριθμός οριζόντιων εικονοστοιχείων
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


Αντιστοίχηση όλων των εικονοστοιχείων για ανάγνωση/εγγραφή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Λειτουργία αντιστοίχισης |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


Αντιστοίχηση όλων των εικονοστοιχείων για ανάγνωση/εγγραφή σε δεδομένη μορφή εικονοστοιχείου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Λειτουργία αντιστοίχισης |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Μορφή εικονοστοιχείου |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


Αντιστοίχηση εικονοστοιχείων που προσδιορίζονται από το rect για ανάγνωση/εγγραφή σε δεδομένη μορφή εικονοστοιχείου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | Η περιοχή των εικονοστοιχείων που θα προσπελαστεί |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Λειτουργία αντιστοίχισης |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Μορφή εικονοστοιχείου |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


Αποθήκευση δεδομένων υφής σε καθορισμένη μορφή εικόνας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Η ροή που περιέχει την αποθηκευμένη εικόνα |
| format | java.lang.String | Μορφή εικόνας, συνήθως επέκταση αρχείου |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Αποθήκευση δεδομένων υφής σε αρχείο εικόνας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το όνομα αρχείου όπου θα αποθηκευτεί η εικόνα. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


Αποθήκευση δεδομένων υφής σε αρχείο εικόνας

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το όνομα αρχείου όπου θα αποθηκευτεί η εικόνα. |
| format | java.lang.String | Μορφή εικόνας του αρχείου εξόδου. |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


Μετασχηματισμός της διάταξης του εικονοστοιχείου σε νέα μορφή εικονοστοιχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | Μορφή εικονοστοιχείου προορισμού |

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

