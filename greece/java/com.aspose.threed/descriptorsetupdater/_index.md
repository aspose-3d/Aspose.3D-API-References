---
title: DescriptorSetUpdater
second_title: Aspose.3D for Java API Reference
description: Αυτή η κλάση επιτρέπει την ενημέρωση του  σε μια αλυσίδα λειτουργίας.
type: docs
weight: 42
url: /el/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Αυτή η κλάση επιτρέπει την ενημέρωση του [IDescriptorSet](../../com.aspose.threed/idescriptorset) σε μια αλυσίδα λειτουργίας.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Δέσμευση ολόκληρου του buffer στο τρέχον descriptor |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Δέσμευση του buffer στο τρέχον descriptor set |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Δέσμευση της μονάδας υφής στο τρέχον descriptor set |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Δέσμευση του buffer στο τρέχον descriptor set στην καθορισμένη θέση δέσμευσης. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Δέσμευση του buffer στο τρέχον descriptor set στην καθορισμένη θέση δέσμευσης. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Δέσμευση της μονάδας υφής στο τρέχον descriptor set |
| [close()](#close--) | Απόρριψη του updater και υποβολή των αλλαγών στη συσκευή υλικού. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### bind(IBuffer buffer) {#bind-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(IBuffer buffer)
```


Δέσμευση ολόκληρου του buffer στο τρέχον descriptor

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Δέσμευση του buffer στο τρέχον descriptor set

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Ποιο buffer να δεσμευτεί |
| μετατόπιση | int | Μετατόπιση του buffer για δέσμευση |
| μέγεθος | int | Μέγεθος του buffer για δέσμευση |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Δέσμευση της μονάδας υφής στο τρέχον descriptor set

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Η texture unit για δέσμευση |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Δέσμευση του buffer στο τρέχον descriptor set στην καθορισμένη θέση δέσμευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δέσμευση | int | Τοποθεσία δέσμευσης |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Το ολόκληρο buffer για δέσμευση |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Δέσμευση του buffer στο τρέχον descriptor set στην καθορισμένη θέση δέσμευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δέσμευση | int | Τοποθεσία δέσμευσης |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Το buffer για δέσμευση |
| μετατόπιση | int | Μετατόπιση του buffer για δέσμευση |
| μέγεθος | int | Μέγεθος του buffer για δέσμευση |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Δέσμευση της μονάδας υφής στο τρέχον descriptor set

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δέσμευση | int | Η τοποθεσία δέσμευσης |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | Η texture unit για δέσμευση |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Απόρριψη του updater και υποβολή των αλλαγών στη συσκευή υλικού.

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

