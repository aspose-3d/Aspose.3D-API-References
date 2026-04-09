---
title: Watermark
second_title: Aspose.3D for Java API Reference
description: Utility per codificare/decodificare watermark cieco da/a una mesh.
type: docs
weight: 230
url: /it/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Utility per codificare/decodificare watermark cieco da/a una mesh. **Osservazioni:** Sia [Watermark](../../com.aspose.threed/watermark) che [Watermark](../../com.aspose.threed/watermark) eseguiranno il controllo della licenza. L'uso in modalità trial genererà un'eccezione; è possibile utilizzare [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) per sopprimere l'eccezione, ma ciò non rimuoverà la restrizione. È necessaria una licenza valida per utilizzare queste funzionalità senza restrizioni. **Esempio:** Il codice seguente mostra come codificare un watermark cieco in una mesh e decodificarlo.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Decodifica il watermark da una mesh |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Decodifica il watermark da una mesh |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Codifica un testo nel watermark cieco della mesh. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Codifica un testo nel watermark cieco della mesh. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Codifica un testo nel watermark cieco della mesh. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### decodeWatermark(Mesh input) {#decodeWatermark-com.aspose.threed.Mesh-}
```
public static String decodeWatermark(Mesh input)
```


Decodifica il watermark da una mesh

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | La mesh da cui estrarre il watermark |

**Returns:**
java.lang.String - Watermark cieco o null se nessun watermark è stato decodificato.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Decodifica il watermark da una mesh

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | La mesh da cui estrarre il watermark |
| password | java.lang.String | La password per decifrare il watermark |

**Returns:**
java.lang.String - Watermark cieco o null se nessun watermark è stato decodificato.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Codifica un testo nel watermark cieco della mesh.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh per codificare un watermark cieco |
| testo | java.lang.String | Testo da codificare nella mesh |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password)
```


Codifica un testo nel watermark cieco della mesh.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh per codificare un watermark cieco |
| testo | java.lang.String | Testo da codificare nella mesh |
| password | java.lang.String | Password per proteggere il watermark, è opzionale |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
### encodeWatermark(Mesh input, String text, String password, boolean permanent) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-}
```
public static Mesh encodeWatermark(Mesh input, String text, String password, boolean permanent)
```


Codifica un testo nel watermark cieco della mesh.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh per codificare un watermark cieco |
| testo | java.lang.String | Testo da codificare nella mesh |
| password | java.lang.String | Password per proteggere il watermark, è opzionale |
| permanente | boolean | Il watermark permanente non sarà sovrascritto né rimosso. |

**Returns:**
[Mesh](../../com.aspose.threed/mesh) - A new mesh instance with blind watermark encoded **Remarks:** Both [Watermark](../../com.aspose.threed/watermark) and [Watermark](../../com.aspose.threed/watermark) will perform license check Trial usage will throw exception, you can use [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) to suppress the exception, but it will not lift the restriction here. A valid license is required to use these features without any restrictions. **Example:** The following code shows how to encode a blind watermark into a mesh and save to ply file

```
Mesh mesh = (new Cylinder()).toMesh();
     var encodedMesh = Watermark.encodeWatermark(mesh, "Hello", "password");
     new Scene(encodedMesh).save("test.ply");
```
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

