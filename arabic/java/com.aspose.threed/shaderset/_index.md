---
title: "ShaderSet"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "برامج التظليل لكل نوع من المواد"
type: docs
weight: 166
url: /ar/java/com.aspose.threed/shaderset/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public class ShaderSet implements Closeable
```

برامج التظليل لكل نوع من المواد
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ShaderSet()](#ShaderSet--) | إنشاء نسخة من [ShaderSet](../../com.aspose.threed/shaderset) |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [close()](#close--) | تخلص من هذه النسخة وأطلق جميع برامج التظليل. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getFallback()](#getFallback--) | يحصل على برنامج التظليل الاحتياطي عندما يكون برنامج التظليل المطلوب غير متوفر |
| [getLambert()](#getLambert--) | يحصل على برنامج التظليل المستخدم لتصيير مادة لامبرت |
| [getPbr()](#getPbr--) | يحصل على برنامج التظليل المستخدم لتصيير مادة PBR |
| [getPhong()](#getPhong--) | يحصل على برنامج التظليل المستخدم لتصيير مادة فونغ |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setFallback(ShaderProgram value)](#setFallback-com.aspose.threed.ShaderProgram-) | يضبط برنامج التظليل الاحتياطي عندما يكون برنامج التظليل المطلوب غير متوفر |
| [setLambert(ShaderProgram value)](#setLambert-com.aspose.threed.ShaderProgram-) | يضبط برنامج التظليل المستخدم لتصيير مادة لامبرت |
| [setPbr(ShaderProgram value)](#setPbr-com.aspose.threed.ShaderProgram-) | يضبط برنامج التظليل المستخدم لتصيير مادة PBR |
| [setPhong(ShaderProgram value)](#setPhong-com.aspose.threed.ShaderProgram-) | يضبط برنامج التظليل المستخدم لتصيير مادة فونغ |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderSet() {#ShaderSet--}
```
public ShaderSet()
```


إنشاء نسخة من [ShaderSet](../../com.aspose.threed/shaderset)

### close() {#close--}
```
public void close()
```


تخلص من هذه النسخة وأطلق جميع برامج التظليل.

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
### getFallback() {#getFallback--}
```
public ShaderProgram getFallback()
```


يحصل على برنامج التظليل الاحتياطي عندما يكون برنامج التظليل المطلوب غير متوفر

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the fallback shader when required shader is unavailable
### getLambert() {#getLambert--}
```
public ShaderProgram getLambert()
```


يحصل على برنامج التظليل المستخدم لتصيير مادة لامبرت

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the lambert material
### getPbr() {#getPbr--}
```
public ShaderProgram getPbr()
```


يحصل على برنامج التظليل المستخدم لتصيير مادة PBR

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the PBR material
### getPhong() {#getPhong--}
```
public ShaderProgram getPhong()
```


يحصل على برنامج التظليل المستخدم لتصيير مادة فونغ

**Returns:**
[ShaderProgram](../../com.aspose.threed/shaderprogram) - the shader that used to render the phong material
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




### setFallback(ShaderProgram value) {#setFallback-com.aspose.threed.ShaderProgram-}
```
public void setFallback(ShaderProgram value)
```


يضبط برنامج التظليل الاحتياطي عندما يكون برنامج التظليل المطلوب غير متوفر

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | القيمة الجديدة |

### setLambert(ShaderProgram value) {#setLambert-com.aspose.threed.ShaderProgram-}
```
public void setLambert(ShaderProgram value)
```


يضبط برنامج التظليل المستخدم لتصيير مادة لامبرت

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | القيمة الجديدة |

### setPbr(ShaderProgram value) {#setPbr-com.aspose.threed.ShaderProgram-}
```
public void setPbr(ShaderProgram value)
```


يضبط برنامج التظليل المستخدم لتصيير مادة PBR

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | القيمة الجديدة |

### setPhong(ShaderProgram value) {#setPhong-com.aspose.threed.ShaderProgram-}
```
public void setPhong(ShaderProgram value)
```


يضبط برنامج التظليل المستخدم لتصيير مادة فونغ

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| value | [ShaderProgram](../../com.aspose.threed/shaderprogram) | القيمة الجديدة |

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

