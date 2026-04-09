---
title: ShaderTechnique
second_title: Aspose.3D for Java API-referentie
description: Een shadertechniek vertegenwoordigt een concrete renderimplementatie.
type: docs
weight: 169
url: /nl/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Een shadertechniek vertegenwoordigt een concrete renderimplementatie.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Initialiseert een nieuw exemplaar van de [ShaderTechnique](../../com.aspose.threed/shadertechnique) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Bindt de dynamische eigenschap aan shaderparameter |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Haalt de beschrijving van deze techniek op |
| [getRenderAPI()](#getRenderAPI--) | Haalt de rendering-API op die door deze techniek wordt gebruikt |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | Haalt de versie van de rendering-API op. |
| [getShaderContent()](#getShaderContent--) | Haalt de inhoud van een ingebed shader‑script op. |
| [getShaderEntry()](#getShaderEntry--) | Haalt het entry point van de shader op, sommige shaders zoals HLSL kunnen aangepaste shader‑entries hebben. |
| [getShaderFile()](#getShaderFile--) | Haalt de bestandsnaam van het externe shader‑bestand op. |
| [getShaderLanguage()](#getShaderLanguage--) | Haalt de shader‑taal op die door deze techniek wordt gebruikt. |
| [getShaderParameters()](#getShaderParameters--) | Haalt de shader‑parameterdefinitie op. |
| [getShaderVersion()](#getShaderVersion--) | Haalt de shaderversie op die door deze techniek wordt gebruikt. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Stelt de beschrijving van deze techniek in |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Stelt de rendering-API in die door deze techniek wordt gebruikt |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Stelt de versie van de rendering-API in. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Stelt de inhoud van een ingebedde shader‑script in. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Stelt het ingangspunt van de shader in, sommige shaders zoals HLSL kunnen aangepaste shader‑ingangen hebben. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Stelt de bestandsnaam van het externe shader‑bestand in. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Stelt de shader‑taal in die door deze techniek wordt gebruikt. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Stelt de shaderversie in die door deze techniek wordt gebruikt. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


Initialiseert een nieuw exemplaar van de [ShaderTechnique](../../com.aspose.threed/shadertechnique) klasse.

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


Bindt de dynamische eigenschap aan shaderparameter

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | De naam van de dynamische eigenschap. |
| shaderParameter | java.lang.String | De naam van de shader‑parameter. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de beschrijving van deze techniek op

**Returns:**
java.lang.String - de beschrijving van deze techniek
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Haalt de rendering-API op die door deze techniek wordt gebruikt

**Returns:**
java.lang.String - de rendering-API die door deze techniek wordt gebruikt
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Haalt de versie van de rendering-API op.

**Returns:**
java.lang.String - de versie van de rendering-API.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Haalt de inhoud op van een ingebedde shader‑script. Het kan een HLSL/GLSL shader‑bronbestand zijn.

**Returns:**
byte[] - de inhoud van een ingebedde shader‑script. Het kan een HLSL/GLSL shader‑bronbestand zijn.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Haalt het entry point van de shader op, sommige shaders zoals HLSL kunnen aangepaste shader‑entries hebben.

**Returns:**
java.lang.String - het ingangspunt van de shader, sommige shaders zoals HLSL kunnen aangepaste shader‑ingangen hebben.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Haalt de bestandsnaam van het externe shader‑bestand op.

**Returns:**
java.lang.String - de bestandsnaam van het externe shader‑bestand.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Haalt de shader‑taal op die door deze techniek wordt gebruikt.

**Returns:**
java.lang.String - de shader‑taal die door deze techniek wordt gebruikt.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Haalt de definitie van de shader‑parameter op. De sleutel is de naam van de dynamische eigenschap, en de waarde is de shader‑parameternaam waaraan de eigenschap is gekoppeld.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - de shader‑parameterdefinitie. De sleutel is de naam van de dynamische eigenschap, en de waarde is de shader‑parameternaam waaraan de eigenschap is gekoppeld.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Haalt de shaderversie op die door deze techniek wordt gebruikt.

**Returns:**
java.lang.String - de shaderversie die door deze techniek wordt gebruikt.
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


Stelt de beschrijving van deze techniek in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Stelt de rendering-API in die door deze techniek wordt gebruikt

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Stelt de versie van de rendering-API in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Stelt de inhoud in van een ingebedde shader‑script. Het kan een HLSL/GLSL shader‑bronbestand zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | byte[] | Nieuwe waarde |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Stelt het ingangspunt van de shader in, sommige shaders zoals HLSL kunnen aangepaste shader‑ingangen hebben.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Stelt de bestandsnaam van het externe shader‑bestand in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Stelt de shader‑taal in die door deze techniek wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Stelt de shaderversie in die door deze techniek wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

