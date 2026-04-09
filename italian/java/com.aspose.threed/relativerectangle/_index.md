---
title: RelativeRectangle
second_title: Aspose.3D for Java API Reference
description: Rettangolo relativo  La formula tra componente relativo e valore assoluto è  Scale  Reference Width  offset  Quindi, se vogliamo che rappresenti un valore assoluto, lasciare tutti i campi di scala a zero e usare i campi offset invece.
type: docs
weight: 147
url: /it/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

Rettangolo relativo La formula tra componente relativo e valore assoluto è: Scale \* (Larghezza di Riferimento) + offset Quindi, se vogliamo che rappresenti un valore assoluto, lascia tutti i campi di scala a zero e usa invece i campi di offset.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | Costruisci un [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | Costruisci un [RelativeRectangle](../../com.aspose.threed/relativerectangle) con tutti i campi offset a zero e i campi scala dai parametri forniti. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | Ottiene l'offset per l'altezza |
| [getOffsetWidth()](#getOffsetWidth--) | Ottiene l'offset per la larghezza |
| [getOffsetX()](#getOffsetX--) | Ottiene l'offset per la coordinata X |
| [getOffsetY()](#getOffsetY--) | Ottiene l'offset per la coordinata Y |
| [getScaleHeight()](#getScaleHeight--) | Altezza relativa |
| [getScaleWidth()](#getScaleWidth--) | Larghezza relativa |
| [getScaleX()](#getScaleX--) | Coordinata X relativa |
| [getScaleY()](#getScaleY--) | Coordinata Y relativa |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | Imposta l'offset per l'altezza |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | Imposta l'offset per la larghezza |
| [setOffsetX(int value)](#setOffsetX-int-) | Imposta l'offset per la coordinata X |
| [setOffsetY(int value)](#setOffsetY-int-) | Imposta l'offset per la coordinata Y |
| [setScaleHeight(float value)](#setScaleHeight-float-) | Altezza relativa |
| [setScaleWidth(float value)](#setScaleWidth-float-) | Larghezza relativa |
| [setScaleX(float value)](#setScaleX-float-) | Coordinata X relativa |
| [setScaleY(float value)](#setScaleY-float-) | Coordinata Y relativa |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | Converti il rettangolo relativo in rettangolo assoluto |
| [toString()](#toString--) | Converte il valore di questa istanza in una java.lang.String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


Costruisci un [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | int |  |
| superiore | int |  |
| larghezza | int |  |
| altezza | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


Clone current instance

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


Costruisci un [RelativeRectangle](../../com.aspose.threed/relativerectangle) con tutti i campi offset a zero e i campi scala dai parametri forniti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| scaleX | float |  |
| scaleY | float |  |
| scaleWidth | float |  |
| scaleHeight | float |  |

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getOffsetHeight() {#getOffsetHeight--}
```
public int getOffsetHeight()
```


Ottiene l'offset per l'altezza

**Returns:**
int - l'offset per l'altezza
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


Ottiene l'offset per la larghezza

**Returns:**
int - l'offset per la larghezza
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


Ottiene l'offset per la coordinata X

**Returns:**
int - l'offset per la coordinata X
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


Ottiene l'offset per la coordinata Y

**Returns:**
int - l'offset per la coordinata Y
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


Altezza relativa

**Returns:**
float - Altezza relativa
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


Larghezza relativa

**Returns:**
float - Larghezza relativa
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Coordinata X relativa

**Returns:**
float - Coordinata relativa X
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Coordinata Y relativa

**Returns:**
float - Coordinata relativa Y
### hashCode() {#hashCode--}
```
public int hashCode()
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




### setOffsetHeight(int value) {#setOffsetHeight-int-}
```
public void setOffsetHeight(int value)
```


Imposta l'offset per l'altezza

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


Imposta l'offset per la larghezza

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


Imposta l'offset per la coordinata X

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


Imposta l'offset per la coordinata Y

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | Nuovo valore |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


Altezza relativa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


Larghezza relativa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Coordinata X relativa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Coordinata Y relativa

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | Nuovo valore |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


Converti il rettangolo relativo in rettangolo assoluto

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sinistra | int | Sinistra del rettangolo |
| superiore | int | Superiore del rettangolo |
| larghezza | int | Larghezza del rettangolo |
| altezza | int | Altezza del rettangolo |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


Converte il valore di questa istanza in una java.lang.String.

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

