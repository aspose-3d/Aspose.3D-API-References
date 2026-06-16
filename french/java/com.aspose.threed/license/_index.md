---
title: "Licence"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Fournit des méthodes pour licencier le composant."
type: docs
weight: 93
url: /fr/java/com.aspose.threed/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Fournit des méthodes pour licencier le composant.

Pour en savoir plus, consultez l'article de documentation **Licensing and Subscription**.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [License()](#License--) | Initialise une nouvelle instance de cette classe. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licence le composant. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licence le composant. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Initialise une nouvelle instance de cette classe.

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licence le composant.

Utilisez cette méthode pour charger une licence à partir d'un flux.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| flux | java.io.InputStream | Un flux qui contient la licence. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licence le composant.

Essaye de trouver la licence aux emplacements suivants :

1. Chemin explicite.

2. Le dossier qui contient le fichier JAR du composant Aspose.

3. Le dossier qui contient le fichier JAR appelé par le client.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| licenseName | java.lang.String | Peut être un nom de fichier complet ou court. Utilisez une chaîne vide pour passer en mode d'évaluation. |

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

