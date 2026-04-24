---
title: WeightedMode
second_title: Aspose.3D for Java API Reference
description: Modalità ponderata.
type: docs
weight: 231
url: /it/java/com.aspose.threed/weightedmode/
---

**Inheritance:**
java.lang.Object
```
public final class WeightedMode
```

Modalità ponderata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WeightedMode()](#WeightedMode--) |  |
## Campi

| Campo | Descrizione |
| --- | --- |
| [BOTH](#BOTH) | Entrambe le tangenti di uscita e di ingresso successive sono ponderate. |
| [NEXT_IN_WEIGHT](#NEXT-IN-WEIGHT) | La tangente di ingresso successiva (sinistra) è ponderata. |
| [NONE](#NONE) | Entrambi i pesi di uscita e di ingresso successivi non sono utilizzati. |
| [OUT_WEIGHT](#OUT-WEIGHT) | La tangente di uscita (destra) è ponderata. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### WeightedMode() {#WeightedMode--}
```
public WeightedMode()
```


### BOTH {#BOTH}
```
public static final int BOTH
```


Entrambe le tangenti di uscita e di ingresso successive sono ponderate.

### NEXT_IN_WEIGHT {#NEXT-IN-WEIGHT}
```
public static final int NEXT_IN_WEIGHT
```


La tangente di ingresso successiva (sinistra) è ponderata.

### NONE {#NONE}
```
public static final int NONE
```


Entrambi i pesi di uscita e di ingresso successivi non sono utilizzati. Quando il calcolo necessita delle informazioni di tangente, verrà usato il valore predefinito(0.3333).

### OUT_WEIGHT {#OUT-WEIGHT}
```
public static final int OUT_WEIGHT
```


La tangente di uscita (destra) è ponderata.

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

