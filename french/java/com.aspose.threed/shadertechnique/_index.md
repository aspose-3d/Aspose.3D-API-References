---
title: "ShaderTechnique"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Une technique de shader représente une implémentation de rendu concrète."
type: docs
weight: 169
url: /fr/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Une technique de shader représente une implémentation de rendu concrète.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Initialise une nouvelle instance de la classe [ShaderTechnique](../../com.aspose.threed/shadertechnique). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Lie la propriété dynamique au paramètre du shader |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | Obtient la description de cette technique |
| [getRenderAPI()](#getRenderAPI--) | Obtient l'API de rendu utilisée par cette technique |
| [getRenderAPIVersion()](#getRenderAPIVersion--) | Obtient la version de l'API de rendu. |
| [getShaderContent()](#getShaderContent--) | Obtient le contenu d'un script de shader intégré. |
| [getShaderEntry()](#getShaderEntry--) | Obtient le point d'entrée du shader, certains shaders comme HLSL peuvent avoir des entrées de shader personnalisées. |
| [getShaderFile()](#getShaderFile--) | Obtient le nom de fichier du shader externe. |
| [getShaderLanguage()](#getShaderLanguage--) | Obtient le langage du shader utilisé par cette technique. |
| [getShaderParameters()](#getShaderParameters--) | Obtient la définition du paramètre du shader. |
| [getShaderVersion()](#getShaderVersion--) | Obtient la version du shader utilisée par cette technique. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Définit la description de cette technique |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Définit l'API de rendu utilisée par cette technique |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Définit la version de l'API de rendu. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Définit le contenu d'un script shader intégré. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Définit le point d'entrée du shader, certains shaders comme HLSL peuvent avoir des entrées de shader personnalisées. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Définit le nom de fichier du shader externe. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Définit le langage du shader utilisé par cette technique. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Définit la version du shader utilisée par cette technique. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ShaderTechnique() {#ShaderTechnique--}
```
public ShaderTechnique()
```


Initialise une nouvelle instance de la classe [ShaderTechnique](../../com.aspose.threed/shadertechnique).

### addBinding(String property, String shaderParameter) {#addBinding-java.lang.String-java.lang.String-}
```
public void addBinding(String property, String shaderParameter)
```


Lie la propriété dynamique au paramètre du shader

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Le nom de la propriété dynamique. |
| shaderParameter | java.lang.String | Le nom du paramètre du shader. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
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


Obtient la description de cette technique

**Returns:**
java.lang.String - la description de cette technique
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Obtient l'API de rendu utilisée par cette technique

**Returns:**
java.lang.String - l'API de rendu utilisée par cette technique
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Obtient la version de l'API de rendu.

**Returns:**
java.lang.String - la version de l'API de rendu.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Obtient le contenu d'un script shader intégré. Il peut s'agir d'un fichier source de shader HLSL/GLSL.

**Returns:**
byte[] - le contenu d'un script shader intégré. Il peut s'agir d'un fichier source de shader HLSL/GLSL.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Obtient le point d'entrée du shader, certains shaders comme HLSL peuvent avoir des entrées de shader personnalisées.

**Returns:**
java.lang.String - le point d'entrée du shader, certains shaders comme HLSL peuvent avoir des entrées de shader personnalisées.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Obtient le nom de fichier du shader externe.

**Returns:**
java.lang.String - le nom de fichier du shader externe.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Obtient le langage du shader utilisé par cette technique.

**Returns:**
java.lang.String - le langage du shader utilisé par cette technique.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Obtient la définition du paramètre du shader. La clé est le nom de la propriété dynamique, et la valeur est le nom du paramètre du shader auquel la propriété est connectée.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - la définition du paramètre du shader. La clé est le nom de la propriété dynamique, et la valeur est le nom du paramètre du shader auquel la propriété est connectée.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Obtient la version du shader utilisée par cette technique.

**Returns:**
java.lang.String - la version du shader utilisée par cette technique.
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


Définit la description de cette technique

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Définit l'API de rendu utilisée par cette technique

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Définit la version de l'API de rendu.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Définit le contenu d'un script shader intégré. Il peut s'agir d'un fichier source de shader HLSL/GLSL.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] | Nouvelle valeur |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Définit le point d'entrée du shader, certains shaders comme HLSL peuvent avoir des entrées de shader personnalisées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Définit le nom de fichier du shader externe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Définit le langage du shader utilisé par cette technique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Définit la version du shader utilisée par cette technique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

