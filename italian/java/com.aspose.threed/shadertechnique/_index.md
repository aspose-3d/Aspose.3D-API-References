---
title: ShaderTechnique
second_title: Aspose.3D for Java API Reference
description: Una tecnica shader rappresenta un'implementazione di rendering concreta.
type: docs
weight: 169
url: /it/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Una tecnica shader rappresenta un'implementazione di rendering concreta.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Initializes a new instance of the [ShaderTechnique](../../com.aspose.threed/shadertechnique) class. |
## Metodi

| Metodo | Descrizione |
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
| [getShaderVersion()](#getShaderVersion--) | Ottiene la versione dello shader utilizzata da questa tecnica. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Imposta la descrizione di questa tecnica |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Imposta l'API di rendering utilizzata da questa tecnica |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Imposta la versione dell'API di rendering. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Imposta il contenuto di uno script shader incorporato. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Imposta il punto di ingresso dello shader, alcuni shader come HLSL possono avere voci shader personalizzate. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Imposta il nome file dello shader esterno. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Imposta il linguaggio shader utilizzato da questa tecnica. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Imposta la versione dello shader utilizzata da questa tecnica. |
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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Il nome della proprietà dinamica. |
| shaderParameter | java.lang.String | Il nome del parametro shader. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
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
java.lang.String - la descrizione di questa tecnica
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Gets the rendering API used by this technique

**Returns:**
java.lang.String - l'API di rendering utilizzata da questa tecnica
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Gets the version of the rendering API.

**Returns:**
java.lang.String - la versione dell'API di rendering.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Ottiene il contenuto di uno script shader incorporato. Può essere un file sorgente shader HLSL/GLSL.

**Returns:**
byte[] - il contenuto di uno script shader incorporato. Può essere un file sorgente shader HLSL/GLSL.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Gets the entry point of the shader, some shader like HLSL can have customized shader entries.

**Returns:**
java.lang.String - il punto di ingresso dello shader, alcuni shader come HLSL possono avere voci shader personalizzate.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Gets the file name of the external shader file.

**Returns:**
java.lang.String - il nome file dello shader esterno.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Gets the shader language used by this technique.

**Returns:**
java.lang.String - il linguaggio shader utilizzato da questa tecnica.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Ottiene la definizione del parametro shader. La chiave è il nome della proprietà dinamica, e il valore è il nome del parametro shader a cui la proprietà è collegata.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - la definizione del parametro shader. La chiave è il nome della proprietà dinamica, e il valore è il nome del parametro shader a cui la proprietà è collegata.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Ottiene la versione dello shader utilizzata da questa tecnica.

**Returns:**
java.lang.String - la versione dello shader utilizzata da questa tecnica.
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


Imposta la descrizione di questa tecnica

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Imposta l'API di rendering utilizzata da questa tecnica

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Imposta la versione dell'API di rendering.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Imposta il contenuto di uno script shader incorporato. Può essere un file sorgente shader HLSL/GLSL.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] | Nuovo valore |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Imposta il punto di ingresso dello shader, alcuni shader come HLSL possono avere voci shader personalizzate.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Imposta il nome file dello shader esterno.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Imposta il linguaggio shader utilizzato da questa tecnica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Imposta la versione dello shader utilizzata da questa tecnica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

