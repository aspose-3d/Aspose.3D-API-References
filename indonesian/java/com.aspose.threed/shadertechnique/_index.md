---
title: ShaderTechnique
second_title: Referensi API Aspose.3D untuk Java
description: Teknik shader merepresentasikan implementasi rendering yang konkret.
type: docs
weight: 169
url: /id/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Teknik shader merepresentasikan implementasi rendering yang konkret.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Menginisialisasi sebuah instance baru dari kelas [ShaderTechnique](../../com.aspose.threed/shadertechnique). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Mengikat properti dinamis ke parameter shader |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Mendapatkan deskripsi teknik ini |
| [getRenderAPI()](#getRenderAPI--) | Mendapatkan API rendering yang digunakan oleh teknik ini |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | Mendapatkan versi API rendering. |
| [getShaderContent()](#getShaderContent--) | Mendapatkan konten skrip shader yang disematkan. |
| [getShaderEntry()](#getShaderEntry--) | Mendapatkan titik masuk shader, beberapa shader seperti HLSL dapat memiliki entri shader yang disesuaikan. |
| [getShaderFile()](#getShaderFile--) | Mendapatkan nama file shader eksternal. |
| [getShaderLanguage()](#getShaderLanguage--) | Mendapatkan bahasa shader yang digunakan oleh teknik ini. |
| [getShaderParameters()](#getShaderParameters--) | Mendapatkan definisi parameter shader. |
| [getShaderVersion()](#getShaderVersion--) | Mendapatkan versi shader yang digunakan oleh teknik ini. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Mengatur deskripsi teknik ini |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Mengatur API rendering yang digunakan oleh teknik ini |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Mengatur versi API rendering. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Mengatur konten skrip shader tersemat. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Mengatur titik masuk shader, beberapa shader seperti HLSL dapat memiliki entri shader yang disesuaikan. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Mengatur nama file shader eksternal. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Mengatur bahasa shader yang digunakan oleh teknik ini. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Mengatur versi shader yang digunakan oleh teknik ini. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


Menginisialisasi sebuah instance baru dari kelas [ShaderTechnique](../../com.aspose.threed/shadertechnique).

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


Mengikat properti dinamis ke parameter shader

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| properti | java.lang.String | Nama properti dinamis. |
| shaderParameter | java.lang.String | Nama parameter shader. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
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


Mendapatkan deskripsi teknik ini

**Returns:**
java.lang.String - deskripsi teknik ini
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Mendapatkan API rendering yang digunakan oleh teknik ini

**Returns:**
java.lang.String - API rendering yang digunakan oleh teknik ini
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Mendapatkan versi API rendering.

**Returns:**
java.lang.String - versi API rendering.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Mendapatkan konten skrip shader tersemat. Itu dapat berupa file sumber shader HLSL/GLSL.

**Returns:**
byte[] - konten skrip shader tersemat. Itu dapat berupa file sumber shader HLSL/GLSL.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Mendapatkan titik masuk shader, beberapa shader seperti HLSL dapat memiliki entri shader yang disesuaikan.

**Returns:**
java.lang.String - titik masuk shader, beberapa shader seperti HLSL dapat memiliki entri shader yang disesuaikan.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Mendapatkan nama file shader eksternal.

**Returns:**
java.lang.String - nama file shader eksternal.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Mendapatkan bahasa shader yang digunakan oleh teknik ini.

**Returns:**
java.lang.String - bahasa shader yang digunakan oleh teknik ini.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Mendapatkan definisi parameter shader. Kunci adalah nama properti dinamis, dan nilai adalah nama parameter shader yang terhubung ke properti tersebut.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - definisi parameter shader. Kunci adalah nama properti dinamis, dan nilai adalah nama parameter shader yang terhubung ke properti tersebut.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Mendapatkan versi shader yang digunakan oleh teknik ini.

**Returns:**
java.lang.String - versi shader yang digunakan oleh teknik ini.
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


Mengatur deskripsi teknik ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Mengatur API rendering yang digunakan oleh teknik ini

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Mengatur versi API rendering.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Mengatur konten skrip shader tersemat. Itu dapat berupa file sumber shader HLSL/GLSL.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | byte[] | Nilai baru |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Mengatur titik masuk shader, beberapa shader seperti HLSL dapat memiliki entri shader yang disesuaikan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Mengatur nama file shader eksternal.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Mengatur bahasa shader yang digunakan oleh teknik ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Mengatur versi shader yang digunakan oleh teknik ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai | java.lang.String | Nilai baru |

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
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

