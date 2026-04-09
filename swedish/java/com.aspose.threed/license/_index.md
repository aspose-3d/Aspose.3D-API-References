---
title: Licens
second_title: Aspose.3D for Java API-referens
description: Tillhandahåller metoder för att licensiera komponenten.
type: docs
weight: 93
url: /sv/java/com.aspose.threed/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

Tillhandahåller metoder för att licensiera komponenten.

För att lära dig mer, besök dokumentationsartikeln **Licensing and Subscription**.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [License()](#License--) | Initierar en ny instans av denna klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | Licensierar komponenten. |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | Licensierar komponenten. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


Initierar en ny instans av denna klass.

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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


Licensierar komponenten.

Använd den här metoden för att läsa in en licens från en ström.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | java.io.InputStream | En ström som innehåller licensen. |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


Licensierar komponenten.

Försöker hitta licensen på följande platser:

1. Explicit sökväg.

2. Mappen som innehåller Aspose-komponentens JAR‑fil.

3. Mappen som innehåller klientens anropande JAR‑fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| licenseName | java.lang.String | Kan vara ett fullständigt eller kort filnamn. Använd en tom sträng för att växla till utvärderingsläge. |

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

