---
title: RelativeRectangle
second_title: Aspose.3D for Java API-referentie
description: Relatieve rechthoek  De formule tussen een relatief component en een absolute waarde is  Scale  Reference Width  offset  Dus als we een absolute waarde willen weergeven, laat alle schaalvelden op nul staan en gebruik in plaats daarvan offset-velden.
type: docs
weight: 147
url: /nl/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

Relatieve rechthoek De formule tussen een relatief component en een absolute waarde is: Scale \* (Reference Width) + offset. Dus als we willen dat het een absolute waarde vertegenwoordigt, laat alle schaalvelden op nul staan en gebruik in plaats daarvan offset-velden.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | Construeer een [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | Construeer een [RelativeRectangle](../../com.aspose.threed/relativerectangle) met alle offset-velden op nul en scale-velden uit de opgegeven parameters. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | Haalt de offset voor hoogte op |
| [getOffsetWidth()](#getOffsetWidth--) | Haalt de offset voor breedte op |
| [getOffsetX()](#getOffsetX--) | Haalt de offset voor coördinaat X op |
| [getOffsetY()](#getOffsetY--) | Haalt de offset voor coördinaat Y op |
| [getScaleHeight()](#getScaleHeight--) | Relatieve hoogte |
| [getScaleWidth()](#getScaleWidth--) | Relatieve breedte |
| [getScaleX()](#getScaleX--) | Relatieve coördinaat X |
| [getScaleY()](#getScaleY--) | Relatieve coördinaat Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | Stelt de offset in voor hoogte |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | Stelt de offset in voor breedte |
| [setOffsetX(int value)](#setOffsetX-int-) | Stelt de offset in voor coördinaat X |
| [setOffsetY(int value)](#setOffsetY-int-) | Stelt de offset in voor coördinaat Y |
| [setScaleHeight(float value)](#setScaleHeight-float-) | Relatieve hoogte |
| [setScaleWidth(float value)](#setScaleWidth-float-) | Relatieve breedte |
| [setScaleX(float value)](#setScaleX-float-) | Relatieve coördinaat X |
| [setScaleY(float value)](#setScaleY-float-) | Relatieve coördinaat Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | Converteer de relatieve rechthoek naar een absolute rechthoek |
| [toString()](#toString--) | Converteert de waarde van deze instantie naar een java.lang.String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


Construeer een [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| links | int |  |
| boven | int |  |
| breedte | int |  |
| hoogte | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


Kloon huidige instantie

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


Construeer een [RelativeRectangle](../../com.aspose.threed/relativerectangle) met alle offset-velden op nul en scale-velden uit de opgegeven parameters.

**Parameters:**
| Parameter | Type | Beschrijving |
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


Haalt de offset voor hoogte op

**Returns:**
int - de offset voor de hoogte
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


Haalt de offset voor breedte op

**Returns:**
int - de offset voor de breedte
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


Haalt de offset voor coördinaat X op

**Returns:**
int - de offset voor coördinaat X
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


Haalt de offset voor coördinaat Y op

**Returns:**
int - de offset voor coördinaat Y
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


Relatieve hoogte

**Returns:**
float - Relatieve hoogte
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


Relatieve breedte

**Returns:**
float - Relatieve breedte
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Relatieve coördinaat X

**Returns:**
float - Relatieve coördinaat X
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Relatieve coördinaat Y

**Returns:**
float - Relatieve coördinaat Y
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


Stelt de offset in voor hoogte

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


Stelt de offset in voor breedte

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


Stelt de offset in voor coördinaat X

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


Stelt de offset in voor coördinaat Y

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | int | Nieuwe waarde |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


Relatieve hoogte

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


Relatieve breedte

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Relatieve coördinaat X

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Relatieve coördinaat Y

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | float | Nieuwe waarde |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


Converteer de relatieve rechthoek naar een absolute rechthoek

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| links | int | Links van de rechthoek |
| boven | int | Bovenkant van de rechthoek |
| breedte | int | Breedte van de rechthoek |
| hoogte | int | Hoogte van de rechthoek |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


Converteert de waarde van deze instantie naar een java.lang.String.

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

