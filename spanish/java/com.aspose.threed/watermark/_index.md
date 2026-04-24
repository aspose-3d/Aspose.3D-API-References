---
title: Watermark
second_title: Referencia de API de Aspose.3D para Java
description: Utilidad para codificar/decodificar una marca de agua ciega a/de una malla.
type: docs
weight: 230
url: /es/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Utilidad para codificar/decodificar una marca de agua ciega a/de una malla. **Remarks:** Tanto [Watermark](../../com.aspose.threed/watermark) como [Watermark](../../com.aspose.threed/watermark) realizarán la verificación de licencia. El uso de prueba lanzará una excepción, puedes usar [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\\#getSuppressTrialException) para suprimir la excepción, pero no eliminará la restricción aquí. Se requiere una licencia válida para usar estas funciones sin restricciones. **Example:** El siguiente código muestra cómo codificar una marca de agua ciega en una malla y decodificarla.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Métodos

| Método | Descripción |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Decodificar la marca de agua de una malla |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Decodificar la marca de agua de una malla |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Codificar un texto en la marca de agua ciega de la malla. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Codificar un texto en la marca de agua ciega de la malla. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Codificar un texto en la marca de agua ciega de la malla. |
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


Decodificar la marca de agua de una malla

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | La malla para extraer la marca de agua |

**Returns:**
java.lang.String - Marca de agua ciega o null si no se decodifica ninguna marca de agua.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Decodificar la marca de agua de una malla

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | La malla para extraer la marca de agua |
| contraseña | java.lang.String | La contraseña para descifrar la marca de agua |

**Returns:**
java.lang.String - Marca de agua ciega o null si no se decodifica ninguna marca de agua.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Codificar un texto en la marca de agua ciega de la malla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Malla para codificar una marca de agua ciega |
| texto | java.lang.String | Texto para codificar en la malla |

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


Codificar un texto en la marca de agua ciega de la malla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Malla para codificar una marca de agua ciega |
| texto | java.lang.String | Texto para codificar en la malla |
| contraseña | java.lang.String | Contraseña para proteger la marca de agua, es opcional |

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


Codificar un texto en la marca de agua ciega de la malla.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Malla para codificar una marca de agua ciega |
| texto | java.lang.String | Texto para codificar en la malla |
| contraseña | java.lang.String | Contraseña para proteger la marca de agua, es opcional |
| permanente | boolean | La marca de agua permanente no será sobrescrita ni eliminada. |

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

