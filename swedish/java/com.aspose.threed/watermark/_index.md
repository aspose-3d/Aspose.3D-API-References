---
title: Watermark
second_title: Aspose.3D for Java API-referens
description: Verktyg för att koda/avkoda blind vattenstämpel till/från ett mesh.
type: docs
weight: 230
url: /sv/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Verktyg för att koda/avkoda blind vattenstämpel till/från ett mesh. **Anmärkningar:** Både [Watermark](../../com.aspose.threed/watermark) och [Watermark](../../com.aspose.threed/watermark) kommer att utföra licenskontroll. Användning av provversion kommer att kasta ett undantag, du kan använda [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) för att undertrycka undantaget, men det kommer inte att ta bort begränsningen här. En giltig licens krävs för att använda dessa funktioner utan några begränsningar. **Exempel:** Följande kod visar hur man kodar en blind vattenstämpel i ett mesh och avkodar den.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Avkoda vattenstämpeln från ett mesh |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Avkoda vattenstämpeln från ett mesh |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Koda en text i meshens blinda vattenstämpel. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Koda en text i meshens blinda vattenstämpel. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Koda en text i meshens blinda vattenstämpel. |
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


Avkoda vattenstämpeln från ett mesh

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh för att extrahera vattenstämpeln |

**Returns:**
java.lang.String - Blind vattenstämpel eller null om ingen vattenstämpel avkodades.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Avkoda vattenstämpeln från ett mesh

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh för att extrahera vattenstämpeln |
| lösenord | java.lang.String | Lösenordet för att dekryptera vattenstämpeln |

**Returns:**
java.lang.String - Blind vattenstämpel eller null om ingen vattenstämpel avkodades.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Koda en text i meshens blinda vattenstämpel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh för att koda en blind vattenstämpel |
| text | java.lang.String | Text att koda till mesh |

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


Koda en text i meshens blinda vattenstämpel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh för att koda en blind vattenstämpel |
| text | java.lang.String | Text att koda till mesh |
| lösenord | java.lang.String | Lösenord för att skydda vattenstämpeln, det är valfritt |

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


Koda en text i meshens blinda vattenstämpel.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh för att koda en blind vattenstämpel |
| text | java.lang.String | Text att koda till mesh |
| lösenord | java.lang.String | Lösenord för att skydda vattenstämpeln, det är valfritt |
| permanent | boolean | Den permanenta vattenstämpeln kommer inte att skrivas över eller tas bort. |

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

