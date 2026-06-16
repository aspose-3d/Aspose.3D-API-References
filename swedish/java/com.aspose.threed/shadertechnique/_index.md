---
title: "ShaderTechnique"
second_title: "Aspose.3D for Java API-referens"
description: "En shaderteknik representerar en konkret renderingsimplementation."
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
| [ShaderTechnique()](#ShaderTechnique--) | Initierar en ny instans av klassen [ShaderTechnique](../../com.aspose.threed/shadertechnique). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Kopplar den dynamiska egenskapen till shaderparameter |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Hämtar beskrivningen av denna teknik |
| [getRenderAPI()](#getRenderAPI--) | Hämtar renderings-API:t som används av denna teknik |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | Hämtar versionen av renderings-API:t. |
| [getShaderContent()](#getShaderContent--) | Hämtar innehållet i ett inbäddat shader‑skript. |
| [getShaderEntry()](#getShaderEntry--) | Hämtar ingångspunkten för shadern, vissa shaders som HLSL kan ha anpassade shader‑ingångar. |
| [getShaderFile()](#getShaderFile--) | Hämtar filnamnet på den externa shader‑filen. |
| [getShaderLanguage()](#getShaderLanguage--) | Hämtar shaderspråket som används av denna teknik. |
| [getShaderParameters()](#getShaderParameters--) | Hämtar definitionen av shader‑parametern. |
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


Initierar en ny instans av klassen [ShaderTechnique](../../com.aspose.threed/shadertechnique).

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


Kopplar den dynamiska egenskapen till shaderparameter

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


Hämtar beskrivningen av denna teknik

**Returns:**
java.lang.String - beskrivningen av denna teknik
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Hämtar renderings-API:t som används av denna teknik

**Returns:**
java.lang.String - renderings‑API:t som används av denna teknik
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Hämtar versionen av renderings-API:t.

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


Hämtar ingångspunkten för shadern, vissa shaders som HLSL kan ha anpassade shader‑ingångar.

**Returns:**
java.lang.String - ingångspunkten för shadern, vissa shaders som HLSL kan ha anpassade shader‑ingångar.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Hämtar filnamnet på den externa shader‑filen.

**Returns:**
java.lang.String - filnamnet för den externa shader‑filen.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Hämtar shaderspråket som används av denna teknik.

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

