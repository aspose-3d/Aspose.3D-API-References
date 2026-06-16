---
title: "RelativeRectangle"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Rectangle relatif  La formule entre le composant relatif et la valeur absolue est  Échelle  Largeur de référence  décalage  Ainsi, si nous voulons qu'il représente une valeur absolue, laissez tous les champs d'échelle à zéro et utilisez les champs de décalage à la place."
type: docs
weight: 147
url: /fr/java/com.aspose.threed/relativerectangle/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.threed.Struct, java.io.Serializable
```
public final class RelativeRectangle implements Struct<RelativeRectangle>, Serializable
```

Rectangle relatif La formule entre le composant relatif et la valeur absolue est : Scale \* (Reference Width) + offset Ainsi, si nous voulons qu'il représente une valeur absolue, laissez tous les champs d'échelle à zéro et utilisez les champs de décalage à la place.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RelativeRectangle(int left, int top, int width, int height)](#RelativeRectangle-int-int-int-int-) | Construire un [RelativeRectangle](../../com.aspose.threed/relativerectangle) |
| [RelativeRectangle()](#RelativeRectangle--) |  |
## Méthodes

| Méthode | Description |
| --- | --- |
| [clone()](#clone--) |  |
| [copyFrom(RelativeRectangle src)](#copyFrom-com.aspose.threed.RelativeRectangle-) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)](#fromScale-float-float-float-float-) | Construire un [RelativeRectangle](../../com.aspose.threed/relativerectangle) avec tous les champs de décalage à zéro et les champs d'échelle provenant des paramètres fournis. |
| [getClass()](#getClass--) |  |
| [getOffsetHeight()](#getOffsetHeight--) | Obtient le décalage pour la hauteur |
| [getOffsetWidth()](#getOffsetWidth--) | Obtient le décalage pour la largeur |
| [getOffsetX()](#getOffsetX--) | Obtient le décalage pour la coordonnée X |
| [getOffsetY()](#getOffsetY--) | Obtient le décalage pour la coordonnée Y |
| [getScaleHeight()](#getScaleHeight--) | Hauteur relative |
| [getScaleWidth()](#getScaleWidth--) | Largeur relative |
| [getScaleX()](#getScaleX--) | Coordonnée relative X |
| [getScaleY()](#getScaleY--) | Coordonnée relative Y |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setOffsetHeight(int value)](#setOffsetHeight-int-) | Définit le décalage pour la hauteur |
| [setOffsetWidth(int value)](#setOffsetWidth-int-) | Définit le décalage pour la largeur |
| [setOffsetX(int value)](#setOffsetX-int-) | Définit le décalage pour la coordonnée X |
| [setOffsetY(int value)](#setOffsetY-int-) | Définit le décalage pour la coordonnée Y |
| [setScaleHeight(float value)](#setScaleHeight-float-) | Hauteur relative |
| [setScaleWidth(float value)](#setScaleWidth-float-) | Largeur relative |
| [setScaleX(float value)](#setScaleX-float-) | Coordonnée relative X |
| [setScaleY(float value)](#setScaleY-float-) | Coordonnée relative Y |
| [toAbsolute(int left, int top, int width, int height)](#toAbsolute-int-int-int-int-) | Convertir le rectangle relatif en rectangle absolu |
| [toString()](#toString--) | Convertit la valeur de cette instance en java.lang.String. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RelativeRectangle(int left, int top, int width, int height) {#RelativeRectangle-int-int-int-int-}
```
public RelativeRectangle(int left, int top, int width, int height)
```


Construire un [RelativeRectangle](../../com.aspose.threed/relativerectangle)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | int |  |
| haut | int |  |
| largeur | int |  |
| hauteur | int |  |

### RelativeRectangle() {#RelativeRectangle--}
```
public RelativeRectangle()
```


### clone() {#clone--}
```
public RelativeRectangle clone()
```


Cloner l'instance actuelle

**Returns:**
[RelativeRectangle](../../com.aspose.threed/relativerectangle)
### copyFrom(RelativeRectangle src) {#copyFrom-com.aspose.threed.RelativeRectangle-}
```
public void copyFrom(RelativeRectangle src)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| src | [RelativeRectangle](../../com.aspose.threed/relativerectangle) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returns:**
boolean
### fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight) {#fromScale-float-float-float-float-}
```
public static RelativeRectangle fromScale(float scaleX, float scaleY, float scaleWidth, float scaleHeight)
```


Construire un [RelativeRectangle](../../com.aspose.threed/relativerectangle) avec tous les champs de décalage à zéro et les champs d'échelle provenant des paramètres fournis.

**Parameters:**
| Paramètre | Type | Description |
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


Obtient le décalage pour la hauteur

**Returns:**
int - le décalage pour la hauteur
### getOffsetWidth() {#getOffsetWidth--}
```
public int getOffsetWidth()
```


Obtient le décalage pour la largeur

**Returns:**
int - le décalage pour la largeur
### getOffsetX() {#getOffsetX--}
```
public int getOffsetX()
```


Obtient le décalage pour la coordonnée X

**Returns:**
int - le décalage pour la coordonnée X
### getOffsetY() {#getOffsetY--}
```
public int getOffsetY()
```


Obtient le décalage pour la coordonnée Y

**Returns:**
int - le décalage pour la coordonnée Y
### getScaleHeight() {#getScaleHeight--}
```
public float getScaleHeight()
```


Hauteur relative

**Returns:**
float - Hauteur relative
### getScaleWidth() {#getScaleWidth--}
```
public float getScaleWidth()
```


Largeur relative

**Returns:**
float - Largeur relative
### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Coordonnée relative X

**Returns:**
float - Coordonnée relative X
### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Coordonnée relative Y

**Returns:**
float - Coordonnée relative Y
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


Définit le décalage pour la hauteur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setOffsetWidth(int value) {#setOffsetWidth-int-}
```
public void setOffsetWidth(int value)
```


Définit le décalage pour la largeur

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setOffsetX(int value) {#setOffsetX-int-}
```
public void setOffsetX(int value)
```


Définit le décalage pour la coordonnée X

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setOffsetY(int value) {#setOffsetY-int-}
```
public void setOffsetY(int value)
```


Définit le décalage pour la coordonnée Y

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setScaleHeight(float value) {#setScaleHeight-float-}
```
public void setScaleHeight(float value)
```


Hauteur relative

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setScaleWidth(float value) {#setScaleWidth-float-}
```
public void setScaleWidth(float value)
```


Largeur relative

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Coordonnée relative X

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Coordonnée relative Y

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | float | Nouvelle valeur |

### toAbsolute(int left, int top, int width, int height) {#toAbsolute-int-int-int-int-}
```
public Rect toAbsolute(int left, int top, int width, int height)
```


Convertir le rectangle relatif en rectangle absolu

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| gauche | int | Gauche du rectangle |
| haut | int | Haut du rectangle |
| largeur | int | Largeur du rectangle |
| hauteur | int | Hauteur du rectangle |

**Returns:**
[Rect](../../com.aspose.threed/rect)
### toString() {#toString--}
```
public String toString()
```


Convertit la valeur de cette instance en java.lang.String.

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

