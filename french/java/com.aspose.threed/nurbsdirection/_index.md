---
title: "NurbsDirection"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Un 3D  possède deux directions le  et le  le  définit les données pour chaque direction."
type: docs
weight: 113
url: /fr/java/com.aspose.threed/nurbsdirection/
---

**Inheritance:**
java.lang.Object
```
public class NurbsDirection
```

Un 3D [NurbsSurface](../../com.aspose.threed/nurbssurface) possède deux directions, le [NurbsSurface.getU](../../com.aspose.threed/nurbssurface\#getU) et le [NurbsSurface.getV](../../com.aspose.threed/nurbssurface\#getV), le [NurbsDirection](../../com.aspose.threed/nurbsdirection) définit les données pour chaque direction. Une direction est en fait une courbe NURBS, ce qui signifie qu'elle est également définie par son [getOrder](../../com.aspose.threed/nurbsdirection\#getOrder), un [getKnotVectors](../../com.aspose.threed/nurbsdirection\#getKnotVectors), et un ensemble de points de contrôle pondérés (définis dans [NurbsSurface](../../com.aspose.threed/nurbssurface)).
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [NurbsDirection()](#NurbsDirection--) | Construit une nouvelle instance de [NurbsDirection](../../com.aspose.threed/nurbsdirection) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Obtient le nombre de points de contrôle dans la direction actuelle. |
| [getDegree()](#getDegree--) | Obtient le degré d'une courbe NURBS, le degré est défini comme Ordre - 1 |
| [getDivisions()](#getDivisions--) | Obtient le nombre de divisions entre les points de contrôle adjacents dans la direction actuelle. |
| [getKnotVectors()](#getKnotVectors--) | Obtient le vecteur de nœuds, c'est une séquence de valeurs de paramètres qui détermine où et comment les points de contrôle affectent la courbe NURBS. |
| [getMultiplicity()](#getMultiplicity--) | Obtient la multiplicité. |
| [getOrder()](#getOrder--) | Obtient l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent chaque point de la courbe. |
| [getType()](#getType--) | Obtient le type de la direction actuelle. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(int value)](#setCount-int-) | Définit le nombre de points de contrôle dans la direction actuelle. |
| [setDegree(int value)](#setDegree-int-) | Définit le degré d'une courbe NURBS, le degré est défini comme Ordre - 1 |
| [setDivisions(int value)](#setDivisions-int-) | Définit le nombre de divisions entre les points de contrôle adjacents dans la direction actuelle. |
| [setOrder(int value)](#setOrder-int-) | Définit l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent chaque point de la courbe. |
| [setType(NurbsType value)](#setType-com.aspose.threed.NurbsType-) | Définit le type de la direction actuelle. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### NurbsDirection() {#NurbsDirection--}
```
public NurbsDirection()
```


Construit une nouvelle instance de [NurbsDirection](../../com.aspose.threed/nurbsdirection)

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
### getCount() {#getCount--}
```
public int getCount()
```


Obtient le nombre de points de contrôle dans la direction actuelle.

**Returns:**
int - le nombre de points de contrôle dans la direction actuelle.
### getDegree() {#getDegree--}
```
public int getDegree()
```


Obtient le degré d'une courbe NURBS, le degré est défini comme Ordre - 1

**Returns:**
int - le degré d'une courbe NURBS, le degré est défini comme Ordre - 1
### getDivisions() {#getDivisions--}
```
public int getDivisions()
```


Obtient le nombre de divisions entre les points de contrôle adjacents dans la direction actuelle.

**Returns:**
int - le nombre de divisions entre les points de contrôle adjacents dans la direction actuelle.
### getKnotVectors() {#getKnotVectors--}
```
public List<Double> getKnotVectors()
```


Obtient le vecteur de nœuds, c'est une séquence de valeurs de paramètres qui détermine où et comment les points de contrôle affectent la courbe NURBS.

**Returns:**
java.util.List<java.lang.Double> - le vecteur de nœuds, c'est une séquence de valeurs de paramètres qui détermine où et comment les points de contrôle affectent la courbe NURBS.
### getMultiplicity() {#getMultiplicity--}
```
public List<Integer> getMultiplicity()
```


Obtient la multiplicité.

**Returns:**
java.util.List<java.lang.Integer> - la multiplicité.
### getOrder() {#getOrder--}
```
public int getOrder()
```


Obtient l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent chaque point de la courbe.

**Returns:**
int - l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent tout point donné de la courbe.
### getType() {#getType--}
```
public NurbsType getType()
```


Obtient le type de la direction actuelle.

**Returns:**
[NurbsType](../../com.aspose.threed/nurbstype) - the type of the current direction.
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




### setCount(int value) {#setCount-int-}
```
public void setCount(int value)
```


Définit le nombre de points de contrôle dans la direction actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setDegree(int value) {#setDegree-int-}
```
public void setDegree(int value)
```


Définit le degré d'une courbe NURBS, le degré est défini comme Ordre - 1

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setDivisions(int value) {#setDivisions-int-}
```
public void setDivisions(int value)
```


Définit le nombre de divisions entre les points de contrôle adjacents dans la direction actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setOrder(int value) {#setOrder-int-}
```
public void setOrder(int value)
```


Définit l'ordre d'une courbe NURBS, il définit le nombre de points de contrôle proches qui influencent chaque point de la courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setType(NurbsType value) {#setType-com.aspose.threed.NurbsType-}
```
public void setType(NurbsType value)
```


Définit le type de la direction actuelle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [NurbsType](../../com.aspose.threed/nurbstype) | Nouvelle valeur |

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

