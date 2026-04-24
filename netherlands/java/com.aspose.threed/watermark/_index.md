---
title: Watermark
second_title: Aspose.3D for Java API-referentie
description: Hulpmiddel om een blinde watermerk te coderen/decoderen naar/van een mesh.
type: docs
weight: 230
url: /nl/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Hulpmiddel om een blinde watermerk te coderen/decoderen naar/van een mesh. **Opmerkingen:** Zowel [Watermark](../../com.aspose.threed/watermark) als [Watermark](../../com.aspose.threed/watermark) voeren een licentiecontrole uit. Gebruik tijdens een proefperiode zal een uitzondering veroorzaken; je kunt [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) gebruiken om de uitzondering te onderdrukken, maar dit zal de beperking hier niet opheffen. Een geldige licentie is vereist om deze functies zonder beperkingen te gebruiken. **Voorbeeld:** De volgende code laat zien hoe je een blinde watermerk in een mesh codeert en decodeert.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Decodeer het watermerk van een mesh |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Decodeer het watermerk van een mesh |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Codeer een tekst in het blinde watermerk van een mesh. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Codeer een tekst in het blinde watermerk van een mesh. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Codeer een tekst in het blinde watermerk van een mesh. |
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


Decodeer het watermerk van een mesh

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | De mesh om het watermerk te extraheren |

**Returns:**
java.lang.String - Blinde watermerk of null als er geen watermerk is gedecodeerd.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Decodeer het watermerk van een mesh

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | De mesh om het watermerk te extraheren |
| wachtwoord | java.lang.String | Het wachtwoord om het watermerk te ontcijferen |

**Returns:**
java.lang.String - Blinde watermerk of null als er geen watermerk is gedecodeerd.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Codeer een tekst in het blinde watermerk van een mesh.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh om een blinde watermerk te coderen |
| tekst | java.lang.String | Tekst om te coderen naar de mesh |

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


Codeer een tekst in het blinde watermerk van een mesh.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh om een blinde watermerk te coderen |
| tekst | java.lang.String | Tekst om te coderen naar de mesh |
| wachtwoord | java.lang.String | Wachtwoord om het watermerk te beschermen, het is optioneel |

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


Codeer een tekst in het blinde watermerk van een mesh.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Mesh om een blinde watermerk te coderen |
| tekst | java.lang.String | Tekst om te coderen naar de mesh |
| wachtwoord | java.lang.String | Wachtwoord om het watermerk te beschermen, het is optioneel |
| permanent | boolean | Het permanente watermerk zal niet worden overschreven of verwijderd. |

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

