---
title: "ShaderTechnique"
second_title: "Aspose.3D for Java API Referansı"
description: "Bir shader tekniği, somut bir render uygulamasını temsil eder."
type: docs
weight: 169
url: /tr/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Bir shader tekniği, somut bir render uygulamasını temsil eder.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Yeni bir [ShaderTechnique](../../com.aspose.threed/shadertechnique) sınıfının bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Dinamik özelliği gölgelendirici parametresine bağlar |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Bu tekniğin açıklamasını alır |
| [getRenderAPI()](#getRenderAPI--) | Bu teknik tarafından kullanılan renderleme API'sini alır |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | Renderleme API'sinin sürümünü alır. |
| [getShaderContent()](#getShaderContent--) | Gömülü bir gölgelendirici betiğinin içeriğini alır. |
| [getShaderEntry()](#getShaderEntry--) | Gölgelendiricinin giriş noktasını alır, HLSL gibi bazı gölgelendiriciler özelleştirilmiş girişlere sahip olabilir. |
| [getShaderFile()](#getShaderFile--) | Harici gölgelendirici dosyasının dosya adını alır. |
| [getShaderLanguage()](#getShaderLanguage--) | Bu teknik tarafından kullanılan gölgelendirici dilini alır. |
| [getShaderParameters()](#getShaderParameters--) | Gölgelendirici parametre tanımını alır. |
| [getShaderVersion()](#getShaderVersion--) | Bu teknik tarafından kullanılan gölgelendirici sürümünü alır. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Bu tekniğin açıklamasını ayarlar |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Bu teknik tarafından kullanılan renderleme API'sını ayarlar |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Renderleme API'sının sürümünü ayarlar. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Gömülü bir gölgelendirici betiğinin içeriğini ayarlar. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Gölgelendiricinin giriş noktasını ayarlar, HLSL gibi bazı gölgelendiriciler özelleştirilmiş girişlere sahip olabilir. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Harici gölgelendirici dosyasının dosya adını ayarlar. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Bu teknik tarafından kullanılan gölgelendirici dilini ayarlar. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Bu teknik tarafından kullanılan gölgelendirici sürümünü ayarlar. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


Yeni bir [ShaderTechnique](../../com.aspose.threed/shadertechnique) sınıfının bir örneğini başlatır.

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


Dinamik özelliği gölgelendirici parametresine bağlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| özellik | java.lang.String | Dinamik özelliğin adı. |
| shaderParameter | java.lang.String | Gölgelendirici parametresinin adı. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametre | Tür | Açıklama |
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


Bu tekniğin açıklamasını alır

**Returns:**
java.lang.String - bu tekniğin açıklaması
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Bu teknik tarafından kullanılan renderleme API'sini alır

**Returns:**
java.lang.String - bu teknik tarafından kullanılan renderleme API'sı
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Renderleme API'sinin sürümünü alır.

**Returns:**
java.lang.String - renderleme API'sının sürümü.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Gömülü bir gölgelendirici betiğinin içeriğini alır. HLSL/GLSL gölgelendirici kaynak dosyası olabilir.

**Returns:**
byte[] - gömülü bir gölgelendirici betiğinin içeriği. HLSL/GLSL gölgelendirici kaynak dosyası olabilir.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Gölgelendiricinin giriş noktasını alır, HLSL gibi bazı gölgelendiriciler özelleştirilmiş girişlere sahip olabilir.

**Returns:**
java.lang.String - gölgelendiricinin giriş noktası, HLSL gibi bazı gölgelendiriciler özelleştirilmiş girişlere sahip olabilir.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Harici gölgelendirici dosyasının dosya adını alır.

**Returns:**
java.lang.String - harici gölgelendirici dosyasının dosya adı.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Bu teknik tarafından kullanılan gölgelendirici dilini alır.

**Returns:**
java.lang.String - bu teknik tarafından kullanılan gölgelendirici dili.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Gölgelendirici parametre tanımını alır. Anahtar, dinamik özelliğin adı, değer ise özelliğin bağlandığı gölgelendirici parametre adıdır.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - gölgelendirici parametre tanımı. Anahtar, dinamik özelliğin adı, değer ise özelliğin bağlandığı gölgelendirici parametre adıdır.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Bu teknik tarafından kullanılan gölgelendirici sürümünü alır.

**Returns:**
java.lang.String - bu teknik tarafından kullanılan gölgelendirici sürümü.
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


Bu tekniğin açıklamasını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Bu teknik tarafından kullanılan renderleme API'sını ayarlar

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Renderleme API'sının sürümünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Gömülü bir gölgelendirici betiğinin içeriğini ayarlar. HLSL/GLSL gölgelendirici kaynak dosyası olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] | Yeni değer |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Gölgelendiricinin giriş noktasını ayarlar, HLSL gibi bazı gölgelendiriciler özelleştirilmiş girişlere sahip olabilir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Harici gölgelendirici dosyasının dosya adını ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Bu teknik tarafından kullanılan gölgelendirici dilini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Bu teknik tarafından kullanılan gölgelendirici sürümünü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | Yeni değer |

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

