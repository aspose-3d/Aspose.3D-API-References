---
title: "DescriptorSetUpdater"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "هذه الفئة تسمح بتحديث الـ  في عملية سلسلة."
type: docs
weight: 42
url: /ar/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

هذه الفئة تسمح بتحديث الـ [IDescriptorSet](../../com.aspose.threed/idescriptorset) في عملية سلسلة.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | ربط كامل المخزن المؤقت بالوصف الحالي |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | ربط المخزن المؤقت بمجموعة الوصف الحالية |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | ربط وحدة النسيج بمجموعة الوصف الحالية |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | ربط المخزن المؤقت بمجموعة الوصف الحالية في موقع الربط المحدد. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | ربط المخزن المؤقت بمجموعة الوصف الحالية في موقع الربط المحدد. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | ربط وحدة النسيج بمجموعة الوصف الحالية |
| [close()](#close--) | إلغاء تحديث المُحدّث وتطبيق التغييرات على الجهاز المادي. |
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


ربط كامل المخزن المؤقت بالوصف الحالي

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


ربط المخزن المؤقت بمجموعة الوصف الحالية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | أي buffer لربطه |
| offset | int | الإزاحة للـ buffer المراد ربطه |
| الحجم | int | حجم الـ buffer المراد ربطه |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


ربط وحدة النسيج بمجموعة الوصف الحالية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | وحدة القوام للربط |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


ربط المخزن المؤقت بمجموعة الوصف الحالية في موقع الربط المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ربط | int | موقع الربط |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | الـ buffer الكامل للربط |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


ربط المخزن المؤقت بمجموعة الوصف الحالية في موقع الربط المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ربط | int | موقع الربط |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | الـ buffer للربط |
| offset | int | الإزاحة للـ buffer المراد ربطه |
| الحجم | int | حجم الـ buffer المراد ربطه |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


ربط وحدة النسيج بمجموعة الوصف الحالية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| ربط | int | موقع الربط |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | وحدة القوام للربط |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


إلغاء تحديث المُحدّث وتطبيق التغييرات على الجهاز المادي.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| معامل | نوع | الوصف |
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
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

