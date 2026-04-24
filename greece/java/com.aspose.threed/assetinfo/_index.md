---
title: AssetInfo
second_title: Aspose.3D for Java API Reference
description: Πληροφορίες του περιουσιακού στοιχείου.
type: docs
weight: 17
url: /el/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Πληροφορίες του περιουσιακού στοιχείου. Οι πληροφορίες περιουσιακού στοιχείου μπορούν να προσαρτηθούν σε μια [Scene](../../com.aspose.threed/scene). Το παιδί [Scene](../../com.aspose.threed/scene) μπορεί να έχει το δικό του [AssetInfo](../../com.aspose.threed/assetinfo) για να παρακάμψει τον ορισμό του γονέα. **Example:** Ο παρακάτω κώδικας δείχνει πώς να διαβάσετε τις πληροφορίες περιουσιακού στοιχείου από ένα αρχείο fbx:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Αρχικοποιεί μια νέα παρουσία της κλάσης [AssetInfo](../../com.aspose.threed/assetinfo) class. |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Αρχικοποιεί μια νέα παρουσία της κλάσης [AssetInfo](../../com.aspose.threed/assetinfo) class. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Βρίσκει την ιδιότητα. |
| [getAmbient()](#getAmbient--) | Επιστρέφει ή ορίζει το προεπιλεγμένο ατμοσφαιρικό χρώμα αυτού του περιουσιακού στοιχείου |
| [getApplicationName()](#getApplicationName--) | Επιστρέφει την εφαρμογή που δημιούργησε αυτό το περιουσιακό στοιχείο |
| [getApplicationVendor()](#getApplicationVendor--) | Επιστρέφει το όνομα του προμηθευτή της εφαρμογής |
| [getApplicationVersion()](#getApplicationVersion--) | Επιστρέφει την έκδοση της εφαρμογής που δημιούργησε αυτό το περιουσιακό στοιχείο. |
| [getAuthor()](#getAuthor--) | Επιστρέφει τον συγγραφέα αυτού του περιουσιακού στοιχείου |
| [getAxisSystem()](#getAxisSystem--) | Επιστρέφει το σύστημα συντεταγμένων/διάνυσμα άνω/διάνυσμα μπροστά των πληροφοριών περιουσιακού στοιχείου. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Επιστρέφει το σχόλιο αυτού του περιουσιακού στοιχείου. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Επιστρέφει το σύστημα συντεταγμένων που χρησιμοποιείται σε αυτό το περιουσιακό στοιχείο. |
| [getCopyright()](#getCopyright--) | Επιστρέφει τα πνευματικά δικαιώματα του εγγράφου |
| [getCreationTime()](#getCreationTime--) | Λαμβάνει ή ορίζει το χρόνο δημιουργίας αυτού του πόρου |
| [getFrontVector()](#getFrontVector--) | Λαμβάνει το διανύσμα μπροστά που χρησιμοποιείται σε αυτό το στοιχείο. |
| [getKeywords()](#getKeywords--) | Λαμβάνει τις λέξεις-κλειδιά αυτού του στοιχείου |
| [getModificationTime()](#getModificationTime--) | Λαμβάνει ή ορίζει το χρόνο τροποποίησης αυτού του πόρου |
| [getName()](#getName--) | Λαμβάνει το όνομα. |
| [getProperties()](#getProperties--) | Λαμβάνει τη συλλογή όλων των ιδιοτήτων. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Λάβετε την τιμή της συγκεκριμένης ιδιότητας |
| [getRevision()](#getRevision--) | Λαμβάνει τον αριθμό αναθεώρησης αυτού του στοιχείου, συνήθως χρησιμοποιείται σε σύστημα ελέγχου εκδόσεων. |
| [getSubject()](#getSubject--) | Λαμβάνει το θέμα αυτού του στοιχείου |
| [getTitle()](#getTitle--) | Λαμβάνει τον τίτλο αυτού του στοιχείου |
| [getUnitName()](#getUnitName--) | Λαμβάνει τη μονάδα μήκους που χρησιμοποιείται σε αυτό το στοιχείο. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Λαμβάνει τον συντελεστή κλίμακας σε πραγματικό μέτρο. |
| [getUpVector()](#getUpVector--) | Λαμβάνει το διανύσμα πάνω που χρησιμοποιείται σε αυτό το στοιχείο. |
| [getUrl()](#getUrl--) | Λαμβάνει ή ορίζει το URL αυτού του πόρου. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Αφαιρεί μια δυναμική ιδιότητα. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Αφαιρέστε την καθορισμένη ιδιότητα που προσδιορίζεται με όνομα |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Επιστρέφει ή ορίζει το προεπιλεγμένο ατμοσφαιρικό χρώμα αυτού του περιουσιακού στοιχείου |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Ορίζει την εφαρμογή που δημιούργησε αυτό το στοιχείο |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Ορίζει το όνομα του προμηθευτή της εφαρμογής |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Ορίζει την έκδοση της εφαρμογής που δημιούργησε αυτό το στοιχείο. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Ορίζει τον συγγραφέα αυτού του στοιχείου |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Ορίζει το σύστημα συντεταγμένων/διανύσμα πάνω/διανύσμα μπροστά των πληροφοριών του στοιχείου. |
| [setComment(String value)](#setComment-java.lang.String-) | Ορίζει το σχόλιο αυτού του στοιχείου. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Ορίζει το σύστημα συντεταγμένων που χρησιμοποιείται σε αυτό το στοιχείο. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Ορίζει το πνευματικό δικαίωμα του εγγράφου |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Λαμβάνει ή ορίζει το χρόνο δημιουργίας αυτού του πόρου |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Ορίζει το διανύσμα μπροστά που χρησιμοποιείται σε αυτό το στοιχείο. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Ορίζει τις λέξεις-κλειδιά αυτού του στοιχείου |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Λαμβάνει ή ορίζει το χρόνο τροποποίησης αυτού του πόρου |
| [setName(String value)](#setName-java.lang.String-) | Ορίζει το όνομα. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ορίζει την τιμή της συγκεκριμένης ιδιότητας |
| [setRevision(String value)](#setRevision-java.lang.String-) | Ορίζει τον αριθμό αναθεώρησης αυτού του στοιχείου, συνήθως χρησιμοποιείται σε σύστημα ελέγχου εκδόσεων. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Sets the subject of this asset |
| [setTitle(String value)](#setTitle-java.lang.String-) | Sets the title of this asset |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Sets the unit of length used in this asset. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Ορίζει τον συντελεστή κλίμακας σε πραγματικό μέτρο. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Ορίζει το διάνυσμα up που χρησιμοποιείται σε αυτό το στοιχείο. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Λαμβάνει ή ορίζει το URL αυτού του πόρου. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [AssetInfo](../../com.aspose.threed/assetinfo) class.

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Αρχικοποιεί μια νέα παρουσία της κλάσης [AssetInfo](../../com.aspose.threed/assetinfo) class.

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Επιστρέφει ή ορίζει το προεπιλεγμένο ατμοσφαιρικό χρώμα αυτού του περιουσιακού στοιχείου

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Επιστρέφει την εφαρμογή που δημιούργησε αυτό το περιουσιακό στοιχείο

**Returns:**
java.lang.String - η εφαρμογή που δημιούργησε αυτό το στοιχείο
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Επιστρέφει το όνομα του προμηθευτή της εφαρμογής

**Returns:**
java.lang.String - το όνομα του προμηθευτή της εφαρμογής
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Επιστρέφει την έκδοση της εφαρμογής που δημιούργησε αυτό το περιουσιακό στοιχείο.

**Returns:**
java.lang.String - η έκδοση της εφαρμογής που δημιούργησε αυτό το στοιχείο.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Επιστρέφει τον συγγραφέα αυτού του περιουσιακού στοιχείου

**Returns:**
java.lang.String - ο συγγραφέας αυτού του στοιχείου
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Επιστρέφει το σύστημα συντεταγμένων/διάνυσμα άνω/διάνυσμα μπροστά των πληροφοριών περιουσιακού στοιχείου.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


Επιστρέφει το σχόλιο αυτού του περιουσιακού στοιχείου.

**Returns:**
java.lang.String - το σχόλιο αυτού του στοιχείου.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Επιστρέφει το σύστημα συντεταγμένων που χρησιμοποιείται σε αυτό το περιουσιακό στοιχείο.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Επιστρέφει τα πνευματικά δικαιώματα του εγγράφου

**Returns:**
java.lang.String - το πνευματικό δικαίωμα του εγγράφου
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Λαμβάνει ή ορίζει το χρόνο δημιουργίας αυτού του πόρου

**Returns:**
java.util.Calendar - ή Ορίζει την ώρα δημιουργίας αυτού του στοιχείου
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Λαμβάνει το διανύσμα μπροστά που χρησιμοποιείται σε αυτό το στοιχείο.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Λαμβάνει τις λέξεις-κλειδιά αυτού του στοιχείου

**Returns:**
java.lang.String - οι λέξεις-κλειδιά αυτού του στοιχείου
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Λαμβάνει ή ορίζει το χρόνο τροποποίησης αυτού του πόρου

**Returns:**
java.util.Calendar - ή Ορίζει την ώρα τροποποίησης αυτού του στοιχείου
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


Λαμβάνει τον αριθμό αναθεώρησης αυτού του στοιχείου, συνήθως χρησιμοποιείται σε σύστημα ελέγχου εκδόσεων.

**Returns:**
java.lang.String - ο αριθμός αναθεώρησης αυτού του στοιχείου, συνήθως χρησιμοποιείται σε σύστημα ελέγχου εκδόσεων.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Λαμβάνει το θέμα αυτού του στοιχείου

**Returns:**
java.lang.String - το θέμα αυτού του στοιχείου
### getTitle() {#getTitle--}
```
public String getTitle()
```


Λαμβάνει τον τίτλο αυτού του στοιχείου

**Returns:**
java.lang.String - ο τίτλος αυτού του στοιχείου
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Λαμβάνει τη μονάδα μήκους που χρησιμοποιείται σε αυτό το στοιχείο. π.χ. cm/m/km/inch/feet

**Returns:**
java.lang.String - η μονάδα μήκους που χρησιμοποιείται σε αυτό το στοιχείο. π.χ. cm/m/km/inch/feet
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Λαμβάνει τον συντελεστή κλίμακας σε πραγματικό μέτρο.

**Returns:**
double - ο συντελεστής κλίμακας σε πραγματικό μέτρο. **Remarks:** Αυτό αγνοείται κατά τη σειριοποίηση εάν το όνομα μονάδας είναι null.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Λαμβάνει το διανύσμα πάνω που χρησιμοποιείται σε αυτό το στοιχείο.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Λαμβάνει ή ορίζει το URL αυτού του πόρου.

**Returns:**
java.lang.String - ή Ορίζει το URL αυτού του στοιχείου.
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Επιστρέφει ή ορίζει το προεπιλεγμένο ατμοσφαιρικό χρώμα αυτού του περιουσιακού στοιχείου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Νέα τιμή |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Ορίζει την εφαρμογή που δημιούργησε αυτό το στοιχείο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Ορίζει το όνομα του προμηθευτή της εφαρμογής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Ορίζει την έκδοση της εφαρμογής που δημιούργησε αυτό το στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Ορίζει τον συγγραφέα αυτού του στοιχείου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Ορίζει το σύστημα συντεταγμένων/διανύσμα πάνω/διανύσμα μπροστά των πληροφοριών του στοιχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Νέα τιμή |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Ορίζει το σχόλιο αυτού του στοιχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Ορίζει το σύστημα συντεταγμένων που χρησιμοποιείται σε αυτό το στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Νέα τιμή |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Ορίζει το πνευματικό δικαίωμα του εγγράφου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Λαμβάνει ή ορίζει το χρόνο δημιουργίας αυτού του πόρου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Calendar | Νέα τιμή |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Ορίζει το διανύσμα μπροστά που χρησιμοποιείται σε αυτό το στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Νέα τιμή |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Ορίζει τις λέξεις-κλειδιά αυτού του στοιχείου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Λαμβάνει ή ορίζει το χρόνο τροποποίησης αυτού του πόρου

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.util.Calendar | Νέα τιμή |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Ορίζει τον αριθμό αναθεώρησης αυτού του στοιχείου, συνήθως χρησιμοποιείται σε σύστημα ελέγχου εκδόσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Sets the subject of this asset

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Sets the title of this asset

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Ορίζει τη μονάδα μήκους που χρησιμοποιείται σε αυτό το στοιχείο. π.χ. cm/m/km/inch/feet

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Ορίζει τον συντελεστή κλίμακας σε πραγματικό μέτρο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή **Remarks:** Αυτό αγνοείται κατά τη σειριοποίηση εάν το όνομα μονάδας είναι null. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Ορίζει το διάνυσμα up που χρησιμοποιείται σε αυτό το στοιχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Νέα τιμή |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Λαμβάνει ή ορίζει το URL αυτού του πόρου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

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

