---
title: RelativeRectangle
second_title: Aspose.3D for Java API-referens
description: Relativ rektangel  Formeln mellan relativ komponent och absolut värde är  Skala  Referensbredd  offset  Så om vi vill att den ska representera ett absolut värde lämna alla skalafält noll och använd offset-fält istället.
type: docs
weight: 147
url: /sv/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

Relativ rektangel Formeln mellan relativ komponent och absolut värde är: Scale \* (Reference Width) + offset Så om vi vill att den ska representera ett absolut värde, lämna alla skalafält noll och använd offset‑fält istället.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | Skapa en [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | Skapa en [RelativeRectangle](../../com.aspose.threed/relativerectangle) med alla offset-fält noll och skalafält från angivna parametrar. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | Hämtar offset för höjd |
| [getOffsetWidth()](#getOffsetWidth--) | Hämtar offset för bredd |
| [getOffsetX()](#getOffsetX--) | Hämtar offset för koordinat X |
| [getOffsetY()](#getOffsetY--) | Hämtar offset för koordinat Y |
| [getScaleHeight()](#getScaleHeight--) | Relativ höjd |
| [getScaleWidth()](#getScaleWidth--) | Relativ bredd |
| [getScaleX()](#getScaleX--) | Relativ koordinat X |
| [getScaleY()](#getScaleY--) | Relativ koordinat Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | Ställer in offset för höjd |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | Ställer in offset för bredd |
| [setOffsetX(int value)](#setOffsetX-int-) | Ställer in offset för koordinat X |
| [setOffsetY(int value)](#setOffsetY-int-) | Ställer in offset för koordinat Y |
| [setScaleHeight(float value)](#setScaleHeight-float-) | Relativ höjd |
| [setScaleWidth(float value)](#setScaleWidth-float-) | Relativ bredd |
| [setScaleX(float value)](#setScaleX-float-) | Relativ koordinat X |
| [setScaleY(float value)](#setScaleY-float-) | Relativ koordinat Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | Konvertera den relativa rektangeln till en absolut rektangel |
| [toString()](#toString--) | Konverterar värdet av denna instans till en java.lang.String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


Skapa en [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | int |  |
| överkant | int |  |
| bredd | int |  |
| höjd | int |  |

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


Skapa en [RelativeRectangle](../../com.aspose.threed/relativerectangle) med alla offset-fält noll och skalafält från angivna parametrar.

**Parameters:**
| Parameter | Typ | Beskrivning |
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


Hämtar offset för höjd

**Returns:**
int - förskjutning för höjden
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


Hämtar offset för bredd

**Returns:**
int - förskjutning för bredden
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


Hämtar offset för koordinat X

**Returns:**
int - förskjutning för koordinat X
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


Hämtar offset för koordinat Y

**Returns:**
int - förskjutning för koordinat Y
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


Relativ höjd

**Returns:**
float - Relativ höjd
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


Relativ bredd

**Returns:**
float - Relativ bredd
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Relativ koordinat X

**Returns:**
float - Relativ koordinat X
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Relativ koordinat Y

**Returns:**
float - Relativ koordinat Y
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


Ställer in offset för höjd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


Ställer in offset för bredd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


Ställer in offset för koordinat X

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


Ställer in offset för koordinat Y

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | Nytt värde |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


Relativ höjd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


Relativ bredd

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Relativ koordinat X

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Relativ koordinat Y

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | float | Nytt värde |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


Konvertera den relativa rektangeln till en absolut rektangel

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vänster | int | Vänster om rektangeln |
| överkant | int | Topp av rektangeln |
| bredd | int | Bredd på rektangeln |
| höjd | int | Höjd på rektangeln |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


Konverterar värdet av denna instans till en java.lang.String.

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

