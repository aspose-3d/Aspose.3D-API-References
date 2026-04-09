---
title: BoneLinkMode
second_title: Aspose.3D for Java API Reference
description: Ένας τρόπος σύνδεσης οστών αναφέρεται στον τρόπο με τον οποίο ένα οστό συνδέεται ή συνδέεται με το γονικό του οστό μέσα σε μια ιεραρχική δομή.
type: docs
weight: 267
url: /el/java/com.aspose.threed/bonelinkmode/
---

**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum BoneLinkMode extends Enum<BoneLinkMode>
```

Η λειτουργία σύνδεσης ενός οστού αναφέρεται στον τρόπο με τον οποίο ένα οστό συνδέεται ή συνδέεται με το γονικό του οστό μέσα σε μια ιεραρχική δομή.
## Πεδία

| Πεδίο | Περιγραφή |
| --- | --- |
| [ADDITIVE](#ADDITIVE) | Η προσθετική λειτουργία υπολογίζει τις μετασχηματισμούς των παιδικών οστών προσθέτοντας τις δικές τους τοπικές μετασχηματισμούς σε εκείνες των γονικών οστών. |
| [NORMALIZE](#NORMALIZE) | Σε αυτή τη λειτουργία, οι μετασχηματισμοί των παιδικών οστών κανονικοποιούνται σε σχέση με τους μετασχηματισμούς του γονικού οστού. |
| [TOTAL_ONE](#TOTAL-ONE) | Το Total One εξασφαλίζει ότι οι συνδυασμένοι μετασχηματισμοί του γονικού και του παιδικού οστού οδηγούν σε έναν συνδυασμένο μετασχηματισμό που κλιμακώνεται σε συνολικό μήκος ενός μονάδας. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [describeConstable()](#describeConstable--) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ADDITIVE {#ADDITIVE}
```
public static final BoneLinkMode ADDITIVE
```


Η προσθετική λειτουργία υπολογίζει τις μετασχηματισμούς των παιδικών οστών προσθέτοντας τις δικές τους τοπικές μετασχηματισμούς σε εκείνες των γονικών οστών.

### NORMALIZE {#NORMALIZE}
```
public static final BoneLinkMode NORMALIZE
```


Σε αυτή τη λειτουργία, οι μετασχηματισμοί των παιδικών οστών κανονικοποιούνται σε σχέση με τους μετασχηματισμούς του γονικού οστού.

### TOTAL_ONE {#TOTAL-ONE}
```
public static final BoneLinkMode TOTAL_ONE
```


Το Total One εξασφαλίζει ότι οι συνδυασμένοι μετασχηματισμοί του γονικού και του παιδικού οστού οδηγούν σε έναν συνδυασμένο μετασχηματισμό που κλιμακώνεται σε συνολικό μήκος ενός μονάδας.

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**Returns:**
T
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | E |  |

**Returns:**
int
### describeConstable() {#describeConstable--}
```
public final Optional<Enum.EnumDesc<E>> describeConstable()
```




**Returns:**
java.util.Optional<java.lang.Enum.EnumDesc<E>>
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**Returns:**
java.lang.Class<E>
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**Returns:**
int
### name() {#name--}
```
public final String name()
```




**Returns:**
java.lang.String
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**Returns:**
int
### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static BoneLinkMode valueOf(String name)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[BoneLinkMode](../../com.aspose.threed/bonelinkmode)
### values() {#values--}
```
public static BoneLinkMode[] values()
```




**Returns:**
com.aspose.threed.BoneLinkMode[]
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

