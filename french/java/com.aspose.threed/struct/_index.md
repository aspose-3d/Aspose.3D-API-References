---
title: "Structure"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Créé par lexchou le 13/11/2017."
type: docs
weight: 262
url: /fr/java/com.aspose.threed/struct/
---

**All Implemented Interfaces:**
java.lang.Cloneable, java.io.Serializable
```
public interface Struct<T> extends Cloneable, Serializable
```

Créé par lexchou le 13/11/2017.
## Méthodes

| Méthode | Description |
| --- | --- |
| [<T>byVal(T value)](#-T-byVal-T-) | Essayer de copier la valeur d'entrée si c'est une Structure |
| [clone()](#clone--) | Cloner l'instance actuelle |
| [copyFrom(T t)](#copyFrom-T-) | Copier l'état interne de l'argument t |
### <T>byVal(T value) {#-T-byVal-T-}
```
public static T <T>byVal(T value)
```


Essayer de copier la valeur d'entrée si c'est une Structure

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | T | valeur d'entrée à cloner |

**Returns:**
T - null si l'entrée est nulle ou instance clonée
### clone() {#clone--}
```
public abstract T clone()
```


Cloner l'instance actuelle

**Returns:**
T - instance clonée
### copyFrom(T t) {#copyFrom-T-}
```
public abstract void copyFrom(T t)
```


Copier l'état interne de l'argument t

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| t | T | instance source à copier |

