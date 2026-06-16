---
title: ShaderTechnique
second_title: Referencia de API de Aspose.3D para Java
description: Una técnica de shader representa una implementación concreta de renderizado.
type: docs
weight: 169
url: /es/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Una técnica de shader representa una implementación concreta de renderizado.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Inicializa una nueva instancia de la clase [ShaderTechnique](../../com.aspose.threed/shadertechnique). |
## Métodos

| Método | Descripción |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Vincula la propiedad dinámica al parámetro del shader |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Obtiene la descripción de esta técnica |
| [getRenderAPI()](#getRenderAPI--) | Obtiene la API de renderizado utilizada por esta técnica |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | Obtiene la versión de la API de renderizado. |
| [getShaderContent()](#getShaderContent--) | Obtiene el contenido de un script de shader incrustado. |
| [getShaderEntry()](#getShaderEntry--) | Obtiene el punto de entrada del shader, algunos shaders como HLSL pueden tener entradas de shader personalizadas. |
| [getShaderFile()](#getShaderFile--) | Obtiene el nombre de archivo del shader externo. |
| [getShaderLanguage()](#getShaderLanguage--) | Obtiene el lenguaje del shader utilizado por esta técnica. |
| [getShaderParameters()](#getShaderParameters--) | Obtiene la definición del parámetro del shader. |
| [getShaderVersion()](#getShaderVersion--) | Obtiene la versión del shader utilizada por esta técnica. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Establece la descripción de esta técnica |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Establece la API de renderizado utilizada por esta técnica |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Establece la versión de la API de renderizado. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Establece el contenido de un script de shader incrustado. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Establece el punto de entrada del shader, algunos shaders como HLSL pueden tener entradas de shader personalizadas. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Establece el nombre de archivo del shader externo. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Establece el lenguaje del shader utilizado por esta técnica. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Establece la versión del shader utilizada por esta técnica. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


Inicializa una nueva instancia de la clase [ShaderTechnique](../../com.aspose.threed/shadertechnique).

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


Vincula la propiedad dinámica al parámetro del shader

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| propiedad | java.lang.String | El nombre de la propiedad dinámica. |
| shaderParameter | java.lang.String | El nombre del parámetro del shader. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
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


Obtiene la descripción de esta técnica

**Returns:**
java.lang.String - la descripción de esta técnica
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Obtiene la API de renderizado utilizada por esta técnica

**Returns:**
java.lang.String - la API de renderizado utilizada por esta técnica
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Obtiene la versión de la API de renderizado.

**Returns:**
java.lang.String - la versión de la API de renderizado.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Obtiene el contenido de un script de shader incrustado. Puede ser un archivo fuente de shader HLSL/GLSL.

**Returns:**
byte[] - el contenido de un script de shader incrustado. Puede ser un archivo fuente de shader HLSL/GLSL.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Obtiene el punto de entrada del shader, algunos shaders como HLSL pueden tener entradas de shader personalizadas.

**Returns:**
java.lang.String - el punto de entrada del shader, algunos shaders como HLSL pueden tener entradas de shader personalizadas.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Obtiene el nombre de archivo del shader externo.

**Returns:**
java.lang.String - el nombre de archivo del shader externo.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Obtiene el lenguaje del shader utilizado por esta técnica.

**Returns:**
java.lang.String - el lenguaje del shader utilizado por esta técnica.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Obtiene la definición del parámetro del shader. La clave es el nombre de la propiedad dinámica, y el valor es el nombre del parámetro del shader al que la propiedad está conectada.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - la definición del parámetro del shader. La clave es el nombre de la propiedad dinámica, y el valor es el nombre del parámetro del shader al que la propiedad está conectada.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Obtiene la versión del shader utilizada por esta técnica.

**Returns:**
java.lang.String - la versión del shader utilizada por esta técnica.
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


Establece la descripción de esta técnica

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Establece la API de renderizado utilizada por esta técnica

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Establece la versión de la API de renderizado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Establece el contenido de un script de shader incrustado. Puede ser un archivo fuente de shader HLSL/GLSL.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | byte[] | Nuevo valor |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Establece el punto de entrada del shader, algunos shaders como HLSL pueden tener entradas de shader personalizadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Establece el nombre de archivo del shader externo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Establece el lenguaje del shader utilizado por esta técnica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Establece la versión del shader utilizada por esta técnica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.lang.String | Nuevo valor |

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

