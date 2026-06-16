---
title: "StructuralMetadata.Property"
second_title: "Référence d'API Aspose.3D pour Java"
description: "La définition de la propriété dans les classes de métadonnées"
type: docs
weight: 13
url: /fr/java/com.aspose.threed/structuralmetadata.property/
---

**Inheritance:**
java.lang.Object
```
public static class StructuralMetadata.Property
```

La définition de la propriété dans les classes des métadonnées
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-) | Constructeur de la propriété des métadonnées |
| [Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)](#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-) | Constructeur de la propriété des métadonnées |
| [Property(String name, Class<?> type)](#Property-java.lang.String-java.lang.Class----) | Constructeur de la propriété des métadonnées |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCount()](#getCount--) | Nombre de données pour le tableau à taille fixe. |
| [getDescription()](#getDescription--) | La description de la propriété |
| [getDisplayName()](#getDisplayName--) | Le nom de la propriété, utilisé par l'interface utilisateur pour la représentation. |
| [getEnumType()](#getEnumType--) | Le type d'énumération |
| [getName()](#getName--) | Le nom unique de la propriété |
| [getNormalized()](#getNormalized--) | Les données sont-elles normalisées. |
| [getType()](#getType--) | Le type de données de la propriété |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCount(Integer value)](#setCount-java.lang.Integer-) | Nombre de données pour le tableau à taille fixe. |
| [setDescription(String value)](#setDescription-java.lang.String-) | La description de la propriété |
| [setDisplayName(String value)](#setDisplayName-java.lang.String-) | Le nom de la propriété, utilisé par l'interface utilisateur pour la représentation. |
| [setEnumType(StructuralMetadata.EnumType value)](#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-) | Le type d'énumération |
| [setNormalized(boolean value)](#setNormalized-boolean-) | Les données sont-elles normalisées. |
| [toString()](#toString--) | Obtient la représentation sous forme de chaîne de cette instance. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-java.lang.Class----boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, Class<?> type, boolean normalized, Integer count)
```


Constructeur de la propriété des métadonnées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom unique de la propriété |
| displayName | java.lang.String | Le nom de la propriété, utilisé par l'interface utilisateur pour la représentation. |
| description | java.lang.String | La description de la propriété |
| type | java.lang.Class<?> | Type de données de la propriété |
| normalized | boolean | Les données sont normalisées |
| nombre | java.lang.Integer | Nombre de données pour le tableau à taille fixe |

### Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count) {#Property-java.lang.String-java.lang.String-java.lang.String-com.aspose.threed.StructuralMetadata.EnumType-boolean-java.lang.Integer-}
```
public Property(String name, String displayName, String description, StructuralMetadata.EnumType type, boolean array, Integer count)
```


Constructeur de la propriété des métadonnées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom unique de la propriété |
| displayName | java.lang.String | Le nom de la propriété, utilisé par l'interface utilisateur pour la représentation. |
| description | java.lang.String | La description de la propriété |
| type | [EnumType](../../com.aspose.threed/enumtype) | Type de données de la propriété |
| tableau | boolean | Chaque valeur de propriété est-elle un tableau ou un scalaire |
| nombre | java.lang.Integer | Nombre de données pour le tableau à taille fixe |

### Property(String name, Class<?> type) {#Property-java.lang.String-java.lang.Class----}
```
public Property(String name, Class<?> type)
```


Constructeur de la propriété des métadonnées

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Le nom unique de la propriété |
| type | java.lang.Class<?> | Type de données de la propriété |

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
public Integer getCount()
```


Nombre de données pour le tableau à taille fixe.

**Returns:**
java.lang.Integer - Nombre de données pour le tableau à taille fixe.
### getDescription() {#getDescription--}
```
public String getDescription()
```


La description de la propriété

**Returns:**
java.lang.String - La description de la propriété
### getDisplayName() {#getDisplayName--}
```
public String getDisplayName()
```


Le nom de la propriété, utilisé par l'interface utilisateur pour la représentation.

**Returns:**
java.lang.String - Le nom de la propriété, utilisé par l'interface utilisateur pour la représentation.
### getEnumType() {#getEnumType--}
```
public StructuralMetadata.EnumType getEnumType()
```


Le type d'énumération

**Returns:**
[EnumType](../../com.aspose.threed/enumtype) - The enum type
### getName() {#getName--}
```
public String getName()
```


Le nom unique de la propriété

**Returns:**
java.lang.String - Le nom unique de la propriété
### getNormalized() {#getNormalized--}
```
public boolean getNormalized()
```


Les données sont-elles normalisées.

**Returns:**
boolean - Les données sont-elles normalisées.
### getType() {#getType--}
```
public Class<?> getType()
```


Le type de données de la propriété

**Returns:**
java.lang.Class<?> - Le type de données de la propriété
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




### setCount(Integer value) {#setCount-java.lang.Integer-}
```
public void setCount(Integer value)
```


Nombre de données pour le tableau à taille fixe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.Integer | Nouvelle valeur |

### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


La description de la propriété

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setDisplayName(String value) {#setDisplayName-java.lang.String-}
```
public void setDisplayName(String value)
```


Le nom de la propriété, utilisé par l'interface utilisateur pour la représentation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setEnumType(StructuralMetadata.EnumType value) {#setEnumType-com.aspose.threed.StructuralMetadata.EnumType-}
```
public void setEnumType(StructuralMetadata.EnumType value)
```


Le type d'énumération

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [EnumType](../../com.aspose.threed/enumtype) | Nouvelle valeur |

### setNormalized(boolean value) {#setNormalized-boolean-}
```
public void setNormalized(boolean value)
```


Les données sont-elles normalisées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### toString() {#toString--}
```
public String toString()
```


Obtient la représentation sous forme de chaîne de cette instance.

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

