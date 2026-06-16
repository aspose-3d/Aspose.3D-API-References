---
title: "Watermark"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Utilitaire pour encoder/décoder un filigrane aveugle vers/dé un maillage."
type: docs
weight: 230
url: /fr/java/com.aspose.threed/watermark/
---

**Inheritance:**
java.lang.Object
```
public class Watermark
```

Utilitaire pour encoder/décoder un filigrane aveugle vers/dé un maillage. **Remarques:** Les deux [Watermark](../../com.aspose.threed/watermark) et [Watermark](../../com.aspose.threed/watermark) effectueront une vérification de licence. L'utilisation en version d'essai déclenchera une exception, vous pouvez utiliser [TrialException.getSuppressTrialException](../../com.aspose.threed/trialexception\#getSuppressTrialException) pour supprimer l'exception, mais cela ne lèvera pas la restriction ici. Une licence valide est requise pour utiliser ces fonctionnalités sans aucune restriction. **Exemple:** Le code suivant montre comment encoder un filigrane aveugle dans un maillage et le décoder.

```
Mesh mesh = (new Cylinder()).toMesh();
     Mesh encodedMesh = Watermark.encodeWatermark(mesh, "Hello", null);
     String watermark = Watermark.decodeWatermark(encodedMesh, null);
```
## Méthodes

| Méthode | Description |
| --- | --- |
| [decodeWatermark(Mesh input)](#decodeWatermark-com.aspose.threed.Mesh-) | Décoder le filigrane d'un maillage |
| [decodeWatermark(Mesh input, String password)](#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Décoder le filigrane d'un maillage |
| [encodeWatermark(Mesh input, String text)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-) | Encoder un texte dans le filigrane aveugle du maillage. |
| [encodeWatermark(Mesh input, String text, String password)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-) | Encoder un texte dans le filigrane aveugle du maillage. |
| [encodeWatermark(Mesh input, String text, String password, boolean permanent)](#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-java.lang.String-boolean-) | Encoder un texte dans le filigrane aveugle du maillage. |
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


Décoder le filigrane d'un maillage

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Le maillage pour extraire le filigrane |

**Returns:**
java.lang.String - Filigrane aveugle ou null si aucun filigrane n'est décodé.
### decodeWatermark(Mesh input, String password) {#decodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static String decodeWatermark(Mesh input, String password)
```


Décoder le filigrane d'un maillage

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Le maillage pour extraire le filigrane |
| mot de passe | java.lang.String | Le mot de passe pour déchiffrer le filigrane |

**Returns:**
java.lang.String - Filigrane aveugle ou null si aucun filigrane n'est décodé.
### encodeWatermark(Mesh input, String text) {#encodeWatermark-com.aspose.threed.Mesh-java.lang.String-}
```
public static Mesh encodeWatermark(Mesh input, String text)
```


Encoder un texte dans le filigrane aveugle du maillage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Maillage pour encoder un filigrane aveugle |
| text | java.lang.String | Texte à encoder dans le maillage |

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


Encoder un texte dans le filigrane aveugle du maillage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Maillage pour encoder un filigrane aveugle |
| text | java.lang.String | Texte à encoder dans le maillage |
| mot de passe | java.lang.String | Mot de passe pour protéger le filigrane, il est optionnel |

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


Encoder un texte dans le filigrane aveugle du maillage.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| input | [Mesh](../../com.aspose.threed/mesh) | Maillage pour encoder un filigrane aveugle |
| text | java.lang.String | Texte à encoder dans le maillage |
| mot de passe | java.lang.String | Mot de passe pour protéger le filigrane, il est optionnel |
| permanent | boolean | Le filigrane permanent ne sera pas écrasé ni supprimé. |

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

