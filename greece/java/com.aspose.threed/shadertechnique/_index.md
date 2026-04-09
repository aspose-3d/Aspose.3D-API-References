---
title: ShaderTechnique
second_title: Aspose.3D for Java API Reference
description: Μια τεχνική shader αντιπροσωπεύει μια συγκεκριμένη υλοποίηση απόδοσης.
type: docs
weight: 169
url: /el/java/com.aspose.threed/shadertechnique/
---

**Inheritance:**
java.lang.Object
```
public class ShaderTechnique
```

Μια τεχνική shader αντιπροσωπεύει μια συγκεκριμένη υλοποίηση απόδοσης.
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [ShaderTechnique()](#ShaderTechnique--) | Initializes a new instance of the [ShaderTechnique](../../com.aspose.threed/shadertechnique) class. |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [addBinding(String property, String shaderParameter)](#addBinding-java.lang.String-java.lang.String-) | Συνδέει τη δυναμική ιδιότητα με την παράμετρο shader |
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
| [getShaderVersion()](#getShaderVersion--) | Λαμβάνει την έκδοση του shader που χρησιμοποιείται από αυτήν την τεχνική. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setDescription(String value)](#setDescription-java.lang.String-) | Ορίζει την περιγραφή αυτής της τεχνικής |
| [setRenderAPI(String value)](#setRenderAPI-java.lang.String-) | Ορίζει το API απόδοσης που χρησιμοποιείται από αυτήν την τεχνική |
| [setRenderAPIVersion(String value)](#setRenderAPIVersion-java.lang.String-) | Ορίζει την έκδοση του API απόδοσης. |
| [setShaderContent(byte[] value)](#setShaderContent-byte---) | Ορίζει το περιεχόμενο ενός ενσωματωμένου script shader. |
| [setShaderEntry(String value)](#setShaderEntry-java.lang.String-) | Ορίζει το σημείο εισόδου του shader, ορισμένα shader όπως το HLSL μπορούν να έχουν προσαρμοσμένες εισόδους shader. |
| [setShaderFile(String value)](#setShaderFile-java.lang.String-) | Ορίζει το όνομα αρχείου του εξωτερικού αρχείου shader. |
| [setShaderLanguage(String value)](#setShaderLanguage-java.lang.String-) | Ορίζει τη γλώσσα shader που χρησιμοποιείται από αυτήν την τεχνική. |
| [setShaderVersion(String value)](#setShaderVersion-java.lang.String-) | Ορίζει την έκδοση του shader που χρησιμοποιείται από αυτήν την τεχνική. |
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


Συνδέει τη δυναμική ιδιότητα με την παράμετρο shader

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| ιδιότητα | java.lang.String | Το όνομα της δυναμικής ιδιότητας. |
| shaderParameter | java.lang.String | Το όνομα της παραμέτρου shader. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
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
java.lang.String - η περιγραφή αυτής της τεχνικής
### getRenderAPI() {#getRenderAPI--}
```
public String getRenderAPI()
```


Gets the rendering API used by this technique

**Returns:**
java.lang.String - το API απόδοσης που χρησιμοποιείται από αυτήν την τεχνική
### getRenderAPIVersion() {#getRenderAPIVersion--}
```
public String getRenderAPIVersion()
```


Gets the version of the rendering API.

**Returns:**
java.lang.String - η έκδοση του API απόδοσης.
### getShaderContent() {#getShaderContent--}
```
public byte[] getShaderContent()
```


Λαμβάνει το περιεχόμενο ενός ενσωματωμένου script shader. Μπορεί να είναι αρχείο πηγαίου κώδικα shader HLSL/GLSL.

**Returns:**
byte[] - το περιεχόμενο ενός ενσωματωμένου script shader. Μπορεί να είναι αρχείο πηγαίου κώδικα shader HLSL/GLSL.
### getShaderEntry() {#getShaderEntry--}
```
public String getShaderEntry()
```


Gets the entry point of the shader, some shader like HLSL can have customized shader entries.

**Returns:**
java.lang.String - το σημείο εισόδου του shader, ορισμένα shader όπως το HLSL μπορούν να έχουν προσαρμοσμένες εισόδους shader.
### getShaderFile() {#getShaderFile--}
```
public String getShaderFile()
```


Gets the file name of the external shader file.

**Returns:**
java.lang.String - το όνομα αρχείου του εξωτερικού αρχείου shader.
### getShaderLanguage() {#getShaderLanguage--}
```
public String getShaderLanguage()
```


Gets the shader language used by this technique.

**Returns:**
java.lang.String - η γλώσσα shader που χρησιμοποιείται από αυτήν την τεχνική.
### getShaderParameters() {#getShaderParameters--}
```
public Map<String,String> getShaderParameters()
```


Λαμβάνει τον ορισμό της παραμέτρου shader. Το κλειδί είναι το όνομα της δυναμικής ιδιότητας, και η τιμή είναι το όνομα της παραμέτρου shader στην οποία συνδέεται η ιδιότητα.

**Returns:**
java.util.Map<java.lang.String,java.lang.String> - ο ορισμός της παραμέτρου shader. Το κλειδί είναι το όνομα της δυναμικής ιδιότητας, και η τιμή είναι το όνομα της παραμέτρου shader στην οποία συνδέεται η ιδιότητα.
### getShaderVersion() {#getShaderVersion--}
```
public String getShaderVersion()
```


Λαμβάνει την έκδοση του shader που χρησιμοποιείται από αυτήν την τεχνική.

**Returns:**
java.lang.String - η έκδοση του shader που χρησιμοποιείται από αυτήν την τεχνική.
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


Ορίζει την περιγραφή αυτής της τεχνικής

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setRenderAPI(String value) {#setRenderAPI-java.lang.String-}
```
public void setRenderAPI(String value)
```


Ορίζει το API απόδοσης που χρησιμοποιείται από αυτήν την τεχνική

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setRenderAPIVersion(String value) {#setRenderAPIVersion-java.lang.String-}
```
public void setRenderAPIVersion(String value)
```


Ορίζει την έκδοση του API απόδοσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setShaderContent(byte[] value) {#setShaderContent-byte---}
```
public void setShaderContent(byte[] value)
```


Ορίζει το περιεχόμενο ενός ενσωματωμένου script shader. Μπορεί να είναι αρχείο πηγαίου κώδικα shader HLSL/GLSL.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | byte[] | Νέα τιμή |

### setShaderEntry(String value) {#setShaderEntry-java.lang.String-}
```
public void setShaderEntry(String value)
```


Ορίζει το σημείο εισόδου του shader, ορισμένα shader όπως το HLSL μπορούν να έχουν προσαρμοσμένες εισόδους shader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setShaderFile(String value) {#setShaderFile-java.lang.String-}
```
public void setShaderFile(String value)
```


Ορίζει το όνομα αρχείου του εξωτερικού αρχείου shader.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setShaderLanguage(String value) {#setShaderLanguage-java.lang.String-}
```
public void setShaderLanguage(String value)
```


Ορίζει τη γλώσσα shader που χρησιμοποιείται από αυτήν την τεχνική.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setShaderVersion(String value) {#setShaderVersion-java.lang.String-}
```
public void setShaderVersion(String value)
```


Ορίζει την έκδοση του shader που χρησιμοποιείται από αυτήν την τεχνική.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

