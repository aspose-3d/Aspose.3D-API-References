---
title: "ShaderTechnique"
second_title: "مرجع API لـ Aspose.3D for Java"
description: "تقنية التظليل تمثل تنفيذًا فعليًا للعرض."
type: docs
weight: 169
url: /ar/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

تقنية التظليل تمثل تنفيذًا فعليًا للعرض.
## المنشئات

| منشئ | الوصف |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | ينشئ مثيلاً جديداً من الفئة [ShaderTechnique](../../com.aspose.threed/shadertechnique). |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | يربط الخاصية الديناميكية بمعامل البرنامج المظلل |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | يحصل على وصف هذه التقنية |
| [getRenderAPI()](#getRenderAPI--) | يحصل على واجهة برمجة التطبيقات للتصيير المستخدمة في هذه التقنية |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | يحصل على نسخة واجهة برمجة التطبيقات للتصيير. |
| [getShaderContent()](#getShaderContent--) | يحصل على محتوى برنامج تظليل مضمّن. |
| [getShaderEntry()](#getShaderEntry--) | يحصل على نقطة الدخول للبرنامج التظليل، بعض برامج التظليل مثل HLSL يمكن أن تحتوي على مداخل مخصصة. |
| [getShaderFile()](#getShaderFile--) | يحصل على اسم ملف البرنامج التظليل الخارجي. |
| [getShaderLanguage()](#getShaderLanguage--) | يحصل على لغة البرنامج التظليل المستخدمة في هذه التقنية. |
| [getShaderParameters()](#getShaderParameters--) | يحصل على تعريف معلمة البرنامج التظليل. |
| [getShaderVersion()](#getShaderVersion--) | يحصل على إصدار الـ shader المستخدم في هذه التقنية. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | يضبط وصف هذه التقنية |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | يضبط واجهة برمجة التطبيقات للتصيير المستخدمة في هذه التقنية |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | يضبط إصدار واجهة برمجة التطبيقات للتصيير. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | يضبط محتوى سكريبت shader المدمج. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | يضبط نقطة الدخول للـ shader، بعض الـ shaders مثل HLSL يمكن أن تحتوي على مداخل shader مخصصة. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | يضبط اسم ملف الـ shader الخارجي. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | يضبط لغة الـ shader المستخدمة في هذه التقنية. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | يضبط إصدار الـ shader المستخدم في هذه التقنية. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


ينشئ مثيلاً جديداً من الفئة [ShaderTechnique](../../com.aspose.threed/shadertechnique).

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


يربط الخاصية الديناميكية بمعامل البرنامج المظلل

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| خاصية | java.lang.String | اسم الخاصية الديناميكية. |
| shaderParameter | java.lang.String | اسم معلمة الـ shader. |

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
### getDescription() {#getDescription--}
```
public String getDescription()
```


يحصل على وصف هذه التقنية

**Returns:**
java.lang.String - وصف هذه التقنية
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


يحصل على واجهة برمجة التطبيقات للتصيير المستخدمة في هذه التقنية

**Returns:**
java.lang.String - واجهة برمجة التطبيقات للتصيير المستخدمة في هذه التقنية
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


يحصل على نسخة واجهة برمجة التطبيقات للتصيير.

**Returns:**
java.lang.String - إصدار واجهة برمجة التطبيقات للتصيير.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


يحصل على محتوى سكريبت shader مدمج. يمكن أن يكون ملف مصدر shader من نوع HLSL/GLSL.

**Returns:**
byte[] - محتوى سكريبت shader مدمج. يمكن أن يكون ملف مصدر shader من نوع HLSL/GLSL.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


يحصل على نقطة الدخول للبرنامج التظليل، بعض برامج التظليل مثل HLSL يمكن أن تحتوي على مداخل مخصصة.

**Returns:**
java.lang.String - نقطة الدخول للـ shader، بعض الـ shaders مثل HLSL يمكن أن تحتوي على مداخل shader مخصصة.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


يحصل على اسم ملف البرنامج التظليل الخارجي.

**Returns:**
java.lang.String - اسم ملف الـ shader الخارجي.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


يحصل على لغة البرنامج التظليل المستخدمة في هذه التقنية.

**Returns:**
java.lang.String - لغة الـ shader المستخدمة في هذه التقنية.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


يحصل على تعريف معلمة الـ shader. المفتاح هو اسم الخاصية الديناميكية، والقيمة هي اسم معلمة الـ shader التي ترتبط بها الخاصية.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - تعريف معلمة الـ shader. المفتاح هو اسم الخاصية الديناميكية، والقيمة هي اسم معلمة الـ shader التي ترتبط بها الخاصية.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


يحصل على إصدار الـ shader المستخدم في هذه التقنية.

**Returns:**
java.lang.String - إصدار الـ shader المستخدم في هذه التقنية.
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




### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


يضبط وصف هذه التقنية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


يضبط واجهة برمجة التطبيقات للتصيير المستخدمة في هذه التقنية

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


يضبط إصدار واجهة برمجة التطبيقات للتصيير.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


يضبط محتوى سكريبت shader مدمج. يمكن أن يكون ملف مصدر shader من نوع HLSL/GLSL.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | byte[] | القيمة الجديدة |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


يضبط نقطة الدخول للـ shader، بعض الـ shaders مثل HLSL يمكن أن تحتوي على مداخل shader مخصصة.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


يضبط اسم ملف الـ shader الخارجي.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


يضبط لغة الـ shader المستخدمة في هذه التقنية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


يضبط إصدار الـ shader المستخدم في هذه التقنية.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| القيمة | java.lang.String | القيمة الجديدة |

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

