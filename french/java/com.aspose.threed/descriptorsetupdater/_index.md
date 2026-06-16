---
title: "DescriptorSetUpdater"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Cette classe permet de mettre à jour le  dans une opération en chaîne."
type: docs
weight: 42
url: /fr/java/com.aspose.threed/descriptorsetupdater/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public final class DescriptorSetUpdater implements Closeable
```

Cette classe permet de mettre à jour le [IDescriptorSet](../../com.aspose.threed/idescriptorset) dans une opération en chaîne.
## Méthodes

| Méthode | Description |
| --- | --- |
| [bind(IBuffer buffer)](#bind-com.aspose.threed.IBuffer-) | Lier le tampon entier au descripteur actuel |
| [bind(IBuffer buffer, int offset, int size)](#bind-com.aspose.threed.IBuffer-int-int-) | Lier le tampon au jeu de descripteurs actuel |
| [bind(ITextureUnit texture)](#bind-com.aspose.threed.ITextureUnit-) | Lier l'unité de texture au jeu de descripteurs actuel |
| [bind(int binding, IBuffer buffer)](#bind-int-com.aspose.threed.IBuffer-) | Lier le tampon au jeu de descripteurs actuel à l'emplacement de liaison spécifié. |
| [bind(int binding, IBuffer buffer, int offset, int size)](#bind-int-com.aspose.threed.IBuffer-int-int-) | Lier le tampon au jeu de descripteurs actuel à l'emplacement de liaison spécifié. |
| [bind(int binding, ITextureUnit texture)](#bind-int-com.aspose.threed.ITextureUnit-) | Lier l'unité de texture au jeu de descripteurs actuel |
| [close()](#close--) | Libérez la mise à jour et validez les modifications sur le dispositif matériel. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### bind(IBuffer buffer) {#bind-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(IBuffer buffer)
```


Lier le tampon entier au descripteur actuel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) |  |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(IBuffer buffer, int offset, int size) {#bind-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(IBuffer buffer, int offset, int size)
```


Lier le tampon au jeu de descripteurs actuel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Quel tampon à lier |
| décalage | int | Décalage du tampon à lier |
| taille | int | Taille du tampon à lier |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(ITextureUnit texture) {#bind-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(ITextureUnit texture)
```


Lier l'unité de texture au jeu de descripteurs actuel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | L'unité de texture à lier |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer) {#bind-int-com.aspose.threed.IBuffer-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer)
```


Lier le tampon au jeu de descripteurs actuel à l'emplacement de liaison spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| liaison | int | Emplacement de liaison |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Le tampon complet à lier |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, IBuffer buffer, int offset, int size) {#bind-int-com.aspose.threed.IBuffer-int-int-}
```
public DescriptorSetUpdater bind(int binding, IBuffer buffer, int offset, int size)
```


Lier le tampon au jeu de descripteurs actuel à l'emplacement de liaison spécifié.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| liaison | int | Emplacement de liaison |
| buffer | [IBuffer](../../com.aspose.threed/ibuffer) | Le tampon à lier |
| décalage | int | Décalage du tampon à lier |
| taille | int | Taille du tampon à lier |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### bind(int binding, ITextureUnit texture) {#bind-int-com.aspose.threed.ITextureUnit-}
```
public DescriptorSetUpdater bind(int binding, ITextureUnit texture)
```


Lier l'unité de texture au jeu de descripteurs actuel

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| liaison | int | L'emplacement de liaison |
| texture | [ITextureUnit](../../com.aspose.threed/itextureunit) | L'unité de texture à lier |

**Returns:**
[DescriptorSetUpdater](../../com.aspose.threed/descriptorsetupdater) - Return current instance for chaining operation
### close() {#close--}
```
public void close()
```


Libérez la mise à jour et validez les modifications sur le dispositif matériel.

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

