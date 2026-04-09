---
title: ShaderTechnique
second_title: Aspose.3D for Java API-referens
description: En shaderteknik representerar en konkret renderingsimplementation.
type: docs
weight: 169
url: /sv/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

En shaderteknik representerar en konkret renderingsimplementation.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Initializes a new instance of the [ShaderTechnique](../../com.aspose.threed/shadertechnique) class. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Binds the dynamic property to shader parameter |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Gets the description of this technique |
| [getRenderAPI()](#getRenderAPI--) | Gets the rendering API used by this technique |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | Gets the version of the rendering API. |
| [getShaderContent()](#getShaderContent--) | Gets the content of a embedded shader script. |
| [getShaderEntry()](#getShaderEntry--) | Gets the entry point of the shader, some shader like HLSL can have customized shader entries. |
| [getShaderFile()](#getShaderFile--) | Gets the file name of the external shader file. |
| [getShaderLanguage()](#getShaderLanguage--) | Gets the shader language used by this technique. |
| [getShaderParameters()](#getShaderParameters--) | Gets the shader parameter definition. |
| [getShaderVersion()](#getShaderVersion--) | Hämtar shader‑versionen som används av denna teknik. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Ställer in beskrivningen av denna teknik |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Ställer in renderings‑API:t som används av denna teknik |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Ställer in versionen av renderings‑API:t. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Ställer in innehållet i ett inbäddat shader‑skript. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Ställer in ingångspunkten för shadern, vissa shaders som HLSL kan ha anpassade shader‑ingångar. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Ställer in filnamnet för den externa shader‑filen. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Ställer in shader‑språket som används av denna teknik. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Ställer in shader‑versionen som används av denna teknik. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


Initializes a new instance of the [ShaderTechnique](../../com.aspose.threed/shadertechnique) class.

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


Binds the dynamic property to shader parameter

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Namnet på den dynamiska egenskapen. |
| shaderParameter | java.lang.String | Namnet på shader‑parametern. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
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


Gets the description of this technique

**Returns:**
java.lang.String - beskrivningen av denna teknik
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Gets the rendering API used by this technique

**Returns:**
java.lang.String - renderings‑API:t som används av denna teknik
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Gets the version of the rendering API.

**Returns:**
java.lang.String - versionen av renderings‑API:t.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Hämtar innehållet i ett inbäddat shader‑skript. Det kan vara en HLSL/GLSL‑shaderkällfil.

**Returns:**
byte[] - innehållet i ett inbäddat shader‑skript. Det kan vara en HLSL/GLSL‑shaderkällfil.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Gets the entry point of the shader, some shader like HLSL can have customized shader entries.

**Returns:**
java.lang.String - ingångspunkten för shadern, vissa shaders som HLSL kan ha anpassade shader‑ingångar.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Gets the file name of the external shader file.

**Returns:**
java.lang.String - filnamnet för den externa shader‑filen.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Gets the shader language used by this technique.

**Returns:**
java.lang.String - shader‑språket som används av denna teknik.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Hämtar definitionen av shader‑parametern. Nyckeln är namnet på den dynamiska egenskapen, och värdet är shader‑parameterns namn som egenskapen är kopplad till.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - definitionen av shader‑parametern. Nyckeln är namnet på den dynamiska egenskapen, och värdet är shader‑parameterns namn som egenskapen är kopplad till.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Hämtar shader‑versionen som används av denna teknik.

**Returns:**
java.lang.String - shader‑versionen som används av denna teknik.
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


Ställer in beskrivningen av denna teknik

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Ställer in renderings‑API:t som används av denna teknik

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Ställer in versionen av renderings‑API:t.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Ställer in innehållet i ett inbäddat shader‑skript. Det kan vara en HLSL/GLSL‑shaderkällfil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | byte[] | Nytt värde |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Ställer in ingångspunkten för shadern, vissa shaders som HLSL kan ha anpassade shader‑ingångar.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Ställer in filnamnet för den externa shader‑filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Ställer in shader‑språket som används av denna teknik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Ställer in shader‑versionen som används av denna teknik.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

