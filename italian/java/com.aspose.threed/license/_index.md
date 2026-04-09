---
title: Licenza
second_title: Aspose.3D for Java API Reference
description: Fornisce metodi per licenziare il componente.
type: docs
weight: 93
url: /it/java/com.aspose.threed/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Fornisce metodi per licenziare il componente.

Per saperne di più, visita l'articolo di documentazione **Licensing and Subscription**.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [License()](#License--) | Inizializza una nuova istanza di questa classe. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licenzia il componente. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licenzia il componente. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Inizializza una nuova istanza di questa classe.

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licenzia il componente.

Usa questo metodo per caricare una licenza da uno stream.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| flusso | java.io.InputStream | Un flusso che contiene la licenza. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licenzia il componente.

Cerca di trovare la licenza nei seguenti percorsi:

1. Percorso esplicito.

2. La cartella che contiene il file JAR del componente Aspose.

3. La cartella che contiene il file JAR chiamato dal client.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| licenseName | java.lang.String | Può essere un nome file completo o abbreviato. Usa una stringa vuota per passare alla modalità di valutazione. |

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

