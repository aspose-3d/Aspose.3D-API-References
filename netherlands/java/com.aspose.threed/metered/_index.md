---
title: "Metered"
second_title: "Aspose.3D voor Java API-referentie"
description: "Biedt methoden om een gemeten sleutel in te stellen."
type: docs
weight: 103
url: /nl/java/com.aspose.threed/metered/
---

**Inheritance:**
java.lang.Object
```
public class Metered
```

Biedt methoden om een gemeten sleutel in te stellen.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Metered()](#Metered--) | Initialiseert een nieuw exemplaar van deze klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getConsumptionCredit()](#getConsumptionCredit--) | Haalt verbruikcredits op |
| [getConsumptionQuantity()](#getConsumptionQuantity--) | Haalt de bestandsgrootte van het verbruik op |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setMeteredKey(String publicKey, String privateKey)](#setMeteredKey-java.lang.String-java.lang.String-) | Stelt de metered openbare en privésleutel in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Metered() {#Metered--}
```
public Metered()
```


Initialiseert een nieuw exemplaar van deze klasse.

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
### getConsumptionCredit() {#getConsumptionCredit--}
```
public static double getConsumptionCredit()
```


Haalt verbruikcredits op

**Returns:**
double - verbruikhoeveelheid
### getConsumptionQuantity() {#getConsumptionQuantity--}
```
public static double getConsumptionQuantity()
```


Haalt de bestandsgrootte van het verbruik op

**Returns:**
double - verbruikhoeveelheid
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




### setMeteredKey(String publicKey, String privateKey) {#setMeteredKey-java.lang.String-java.lang.String-}
```
public void setMeteredKey(String publicKey, String privateKey)
```


Stelt de metered openbare en privésleutel in. Als u een metered-licentie aanschaft, moet deze API bij het starten van de applicatie worden aangeroepen; normaal gesproken is dit voldoende. Echter, als het uploaden van verbruiksgegevens steeds mislukt en 24 uur wordt overschreden, wordt de licentie op evaluatiestatus gezet. Om dit te voorkomen, dient u regelmatig de licentiestatus te controleren; als deze op evaluatiestatus staat, roept u deze API opnieuw aan.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| publicKey | java.lang.String | openbare sleutel |
| privateKey | java.lang.String | privésleutel |

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

