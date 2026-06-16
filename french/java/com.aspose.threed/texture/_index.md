---
title: "Texture"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Cette classe définit la texture à partir d’un fichier externe."
type: docs
weight: 184
url: /fr/java/com.aspose.threed/texture/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject), [com.aspose.threed.TextureBase](../../com.aspose.threed/texturebase)
```
public class Texture extends TextureBase
```

Cette classe définit la texture à partir d’un fichier externe.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Texture()](#Texture--) | Initialise une nouvelle instance de la classe [Texture](../../com.aspose.threed/texture). |
| [Texture(String name)](#Texture-java.lang.String-) | Initialise une nouvelle instance de la classe [Texture](../../com.aspose.threed/texture). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAlpha()](#getAlpha--) | Obtient la valeur alpha par défaut de la texture. Ceci est valable lorsque le [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) est [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). La valeur par défaut est 1.0, la plage de valeurs valides est comprise entre 0 et 1. |
| [getAlphaSource()](#getAlphaSource--) | Obtient si la texture définit le canal alpha. |
| [getClass()](#getClass--) |  |
| [getContent()](#getContent--) | Obtient le contenu binaire de la texture. |
| [getEnableMipMap()](#getEnableMipMap--) | Obtient si le mipmap est activé pour cette texture |
| [getFileName()](#getFileName--) | Obtient le fichier de texture associé. |
| [getMagFilter()](#getMagFilter--) | Obtient le filtre pour l'agrandissement. |
| [getMinFilter()](#getMinFilter--) | Obtient le filtre pour la réduction. |
| [getMipFilter()](#getMipFilter--) | Obtient le filtre pour l'échantillonnage du niveau de mip. |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getUVRotation()](#getUVRotation--) | Obtient la rotation de la texture |
| [getUVScale()](#getUVScale--) | Obtient l'échelle UV. |
| [getUVTranslation()](#getUVTranslation--) | Obtient la translation UV. |
| [getWrapModeU()](#getWrapModeU--) | Obtient les modes d'enroulement de la texture en U. |
| [getWrapModeV()](#getWrapModeV--) | Obtient les modes d'enroulement de la texture en V. |
| [getWrapModeW()](#getWrapModeW--) | Obtient les modes d'enroulement de la texture en W. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAlpha(double value)](#setAlpha-double-) | Définit la valeur alpha par défaut de la texture. Ceci est valable lorsque le [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) est [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). La valeur par défaut est 1.0, la plage de valeurs valides est comprise entre 0 et 1. |
| [setAlphaSource(AlphaSource value)](#setAlphaSource-com.aspose.threed.AlphaSource-) | Définit si la texture définit le canal alpha. |
| [setContent(byte[] value)](#setContent-byte---) | Définit le contenu binaire de la texture. |
| [setEnableMipMap(boolean value)](#setEnableMipMap-boolean-) | Définit si le mipmap est activé pour cette texture |
| [setFileName(String value)](#setFileName-java.lang.String-) | Définit le fichier de texture associé. |
| [setMagFilter(TextureFilter value)](#setMagFilter-com.aspose.threed.TextureFilter-) | Définit le filtre pour l'agrandissement. |
| [setMinFilter(TextureFilter value)](#setMinFilter-com.aspose.threed.TextureFilter-) | Définit le filtre pour la minification. |
| [setMipFilter(TextureFilter value)](#setMipFilter-com.aspose.threed.TextureFilter-) | Définit le filtre pour l'échantillonnage du niveau de mip. |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRotation(double u, double v)](#setRotation-double-double-) | Définit la rotation UV. |
| [setScale(double u, double v)](#setScale-double-double-) | Définit l'échelle UV. |
| [setTranslation(double u, double v)](#setTranslation-double-double-) | Définit la translation UV. |
| [setUVRotation(Vector3 value)](#setUVRotation-com.aspose.threed.Vector3-) | Définit la rotation de la texture |
| [setUVScale(Vector2 value)](#setUVScale-com.aspose.threed.Vector2-) | Définit l'échelle UV. |
| [setUVTranslation(Vector2 value)](#setUVTranslation-com.aspose.threed.Vector2-) | Définit la translation UV. |
| [setWrapModeU(WrapMode value)](#setWrapModeU-com.aspose.threed.WrapMode-) | Définit les modes d'enroulement de la texture en U. |
| [setWrapModeV(WrapMode value)](#setWrapModeV-com.aspose.threed.WrapMode-) | Définit les modes d'enroulement de la texture en V. |
| [setWrapModeW(WrapMode value)](#setWrapModeW-com.aspose.threed.WrapMode-) | Définit les modes d'enroulement de la texture en W. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Texture() {#Texture--}
```
public Texture()
```


Initialise une nouvelle instance de la classe [Texture](../../com.aspose.threed/texture).

### Texture(String name) {#Texture-java.lang.String-}
```
public Texture(String name)
```


Initialise une nouvelle instance de la classe [Texture](../../com.aspose.threed/texture).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String | Nom |

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
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trouve la propriété. Elle peut être une propriété dynamique (Créée par CreateDynamicProperty/SetProperty) ou une propriété native (Identifiée par son nom)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propertyName | java.lang.String | Nom de la propriété. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAlpha() {#getAlpha--}
```
public double getAlpha()
```


Obtient la valeur alpha par défaut de la texture. Ceci est valable lorsque le [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) est [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). La valeur par défaut est 1.0, la plage de valeurs valides est comprise entre 0 et 1.

**Returns:**
double - la valeur alpha par défaut de la texture. Ceci est valide lorsque le [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) est [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). La valeur par défaut est 1,0, la plage de valeurs valides est comprise entre 0 et 1
### getAlphaSource() {#getAlphaSource--}
```
public AlphaSource getAlphaSource()
```


Obtient si la texture définit le canal alpha. La valeur par défaut est [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Returns:**
[AlphaSource](../../com.aspose.threed/alphasource) - whether the texture defines the alpha channel. Default value is [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContent() {#getContent--}
```
public byte[] getContent()
```


Obtient le contenu binaire de la texture. Le contenu de texture intégré est optionnel, l'utilisateur doit charger la texture à partir d'un fichier externe si celui-ci est manquant.

**Returns:**
byte[] - le contenu binaire de la texture. Le contenu de texture intégré est optionnel, l'utilisateur doit charger la texture à partir d'un fichier externe si celui-ci est manquant.
### getEnableMipMap() {#getEnableMipMap--}
```
public boolean getEnableMipMap()
```


Obtient si le mipmap est activé pour cette texture

**Returns:**
boolean - si le mipmap est activé pour cette texture
### getFileName() {#getFileName--}
```
public String getFileName()
```


Obtient le fichier de texture associé.

**Returns:**
java.lang.String - le fichier de texture associé.
### getMagFilter() {#getMagFilter--}
```
public TextureFilter getMagFilter()
```


Obtient le filtre pour l'agrandissement.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for magnification.
### getMinFilter() {#getMinFilter--}
```
public TextureFilter getMinFilter()
```


Obtient le filtre pour la réduction.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for minification.
### getMipFilter() {#getMipFilter--}
```
public TextureFilter getMipFilter()
```


Obtient le filtre pour l'échantillonnage du niveau de mip.

**Returns:**
[TextureFilter](../../com.aspose.threed/texturefilter) - the filter for mip-level sampling.
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Obtient la collection de toutes les propriétés.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Obtenir la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |

**Returns:**
java.lang.Object - La valeur de la propriété trouvée
### getUVRotation() {#getUVRotation--}
```
public Vector3 getUVRotation()
```


Obtient la rotation de la texture

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the rotation of the texture
### getUVScale() {#getUVScale--}
```
public Vector2 getUVScale()
```


Obtient l'échelle UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV scale.
### getUVTranslation() {#getUVTranslation--}
```
public Vector2 getUVTranslation()
```


Obtient la translation UV.

**Returns:**
[Vector2](../../com.aspose.threed/vector2) - the UV translation.
### getWrapModeU() {#getWrapModeU--}
```
public WrapMode getWrapModeU()
```


Obtient les modes d'enroulement de la texture en U.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in U.
### getWrapModeV() {#getWrapModeV--}
```
public WrapMode getWrapModeV()
```


Obtient les modes d'enroulement de la texture en V.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in V.
### getWrapModeW() {#getWrapModeW--}
```
public WrapMode getWrapModeW()
```


Obtient les modes d'enroulement de la texture en W.

**Returns:**
[WrapMode](../../com.aspose.threed/wrapmode) - the texture wrap modes in W.
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




### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


Supprime une propriété dynamique.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Supprime la propriété spécifiée identifiée par son nom

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Quelle propriété supprimer |

**Returns:**
boolean - vrai si la propriété est supprimée avec succès
### setAlpha(double value) {#setAlpha-double-}
```
public void setAlpha(double value)
```


Définit la valeur alpha par défaut de la texture. Ceci est valable lorsque le [getAlphaSource](../../com.aspose.threed/texturebase\#getAlphaSource) est [AlphaSource.PIXEL\_ALPHA](../../com.aspose.threed/alphasource\#PIXEL-ALPHA). La valeur par défaut est 1.0, la plage de valeurs valides est comprise entre 0 et 1.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur |

### setAlphaSource(AlphaSource value) {#setAlphaSource-com.aspose.threed.AlphaSource-}
```
public void setAlphaSource(AlphaSource value)
```


Définit si la texture définit le canal alpha. La valeur par défaut est [AlphaSource.NONE](../../com.aspose.threed/alphasource\#NONE)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AlphaSource](../../com.aspose.threed/alphasource) | Nouvelle valeur |

### setContent(byte[] value) {#setContent-byte---}
```
public void setContent(byte[] value)
```


Définit le contenu binaire de la texture. Le contenu de texture intégré est optionnel, l'utilisateur doit charger la texture à partir d'un fichier externe si celui-ci est manquant.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | byte[] | Nouvelle valeur |

### setEnableMipMap(boolean value) {#setEnableMipMap-boolean-}
```
public void setEnableMipMap(boolean value)
```


Définit si le mipmap est activé pour cette texture

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Définit le fichier de texture associé.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setMagFilter(TextureFilter value) {#setMagFilter-com.aspose.threed.TextureFilter-}
```
public void setMagFilter(TextureFilter value)
```


Définit le filtre pour l'agrandissement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nouvelle valeur |

### setMinFilter(TextureFilter value) {#setMinFilter-com.aspose.threed.TextureFilter-}
```
public void setMinFilter(TextureFilter value)
```


Définit le filtre pour la minification.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nouvelle valeur |

### setMipFilter(TextureFilter value) {#setMipFilter-com.aspose.threed.TextureFilter-}
```
public void setMipFilter(TextureFilter value)
```


Définit le filtre pour l'échantillonnage du niveau de mip.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [TextureFilter](../../com.aspose.threed/texturefilter) | Nouvelle valeur |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Définit le nom.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Définit la valeur de la propriété spécifiée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| propriété | java.lang.String | Nom de la propriété |
| valeur | java.lang.Object | La valeur de la propriété |

### setRotation(double u, double v) {#setRotation-double-double-}
```
public void setRotation(double u, double v)
```


Définit la rotation UV.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setScale(double u, double v) {#setScale-double-double-}
```
public void setScale(double u, double v)
```


Définit l'échelle UV.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setTranslation(double u, double v) {#setTranslation-double-double-}
```
public void setTranslation(double u, double v)
```


Définit la translation UV.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| u | double | U. |
| v | double | V. |

### setUVRotation(Vector3 value) {#setUVRotation-com.aspose.threed.Vector3-}
```
public void setUVRotation(Vector3 value)
```


Définit la rotation de la texture

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setUVScale(Vector2 value) {#setUVScale-com.aspose.threed.Vector2-}
```
public void setUVScale(Vector2 value)
```


Définit l'échelle UV.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

### setUVTranslation(Vector2 value) {#setUVTranslation-com.aspose.threed.Vector2-}
```
public void setUVTranslation(Vector2 value)
```


Définit la translation UV.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector2](../../com.aspose.threed/vector2) | Nouvelle valeur |

### setWrapModeU(WrapMode value) {#setWrapModeU-com.aspose.threed.WrapMode-}
```
public void setWrapModeU(WrapMode value)
```


Définit les modes d'enroulement de la texture en U.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nouvelle valeur |

### setWrapModeV(WrapMode value) {#setWrapModeV-com.aspose.threed.WrapMode-}
```
public void setWrapModeV(WrapMode value)
```


Définit les modes d'enroulement de la texture en V.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nouvelle valeur |

### setWrapModeW(WrapMode value) {#setWrapModeW-com.aspose.threed.WrapMode-}
```
public void setWrapModeW(WrapMode value)
```


Définit les modes d'enroulement de la texture en W.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [WrapMode](../../com.aspose.threed/wrapmode) | Nouvelle valeur |

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

