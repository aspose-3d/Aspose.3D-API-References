---
title: "TextureData"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Cette classe contient les données brutes et la définition du format d’une texture."
type: docs
weight: 187
url: /fr/java/com.aspose.threed/texturedata/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class TextureData extends A3DObject
```

Cette classe contient les données brutes et la définition du format d’une texture.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)](#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---) | Constructeur de [TextureData](../../com.aspose.threed/texturedata) |
| [TextureData(int width, int height, PixelFormat pixelFormat)](#TextureData-int-int-com.aspose.threed.PixelFormat-) | Construit un nouveau [TextureData](../../com.aspose.threed/texturedata) et alloue les données de pixel. |
| [TextureData()](#TextureData--) | Constructeur de [TextureData](../../com.aspose.threed/texturedata) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | Charger une texture depuis un fichier |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | Charger une texture depuis un flux |
| [getBytesPerPixel()](#getBytesPerPixel--) | Nombre d'octets d'un pixel |
| [getClass()](#getClass--) |  |
| [getData()](#getData--) | Octets bruts des données de pixel |
| [getHeight()](#getHeight--) | Nombre de pixels verticaux |
| [getName()](#getName--) | Obtient le nom. |
| [getPixelFormat()](#getPixelFormat--) | Le format du pixel |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getStride()](#getStride--) | Nombre d'octets d'une ligne de balayage. |
| [getWidth()](#getWidth--) | Nombre de pixels horizontaux |
| [hashCode()](#hashCode--) |  |
| [mapPixels(PixelMapMode mapMode)](#mapPixels-com.aspose.threed.PixelMapMode-) | Mapper tous les pixels en lecture/écriture |
| [mapPixels(PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Mapper tous les pixels en lecture/écriture dans le format de pixel donné |
| [mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)](#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-) | Mapper les pixels adressés par le rectangle pour la lecture/écriture dans le format de pixel donné |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [save(Stream stream, String format)](#save-com.aspose.threed.Stream-java.lang.String-) | Enregistrer les données de texture dans le format d'image spécifié |
| [save(String fileName)](#save-java.lang.String-) | Enregistrer les données de texture dans un fichier image |
| [save(String fileName, String format)](#save-java.lang.String-java.lang.String-) | Enregistrer les données de texture dans un fichier image |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [toString()](#toString--) |  |
| [transformPixelFormat(PixelFormat pixelFormat)](#transformPixelFormat-com.aspose.threed.PixelFormat-) | Transformer la disposition du pixel vers un nouveau format de pixel. |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data) {#TextureData-int-int-int-int-com.aspose.threed.PixelFormat-byte---}
```
public TextureData(int width, int height, int stride, int bytesPerPixel, PixelFormat pixelFormat, byte[] data)
```


Constructeur de [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int |  |
| hauteur | int |  |
| stride | int |  |
| bytesPerPixel | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |
| données | byte[] |  |

### TextureData(int width, int height, PixelFormat pixelFormat) {#TextureData-int-int-com.aspose.threed.PixelFormat-}
```
public TextureData(int width, int height, PixelFormat pixelFormat)
```


Construit un nouveau [TextureData](../../com.aspose.threed/texturedata) et alloue les données de pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur | int |  |
| hauteur | int |  |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) |  |

### TextureData() {#TextureData--}
```
public TextureData()
```


Constructeur de [TextureData](../../com.aspose.threed/texturedata)

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
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static TextureData fromFile(String fileName)
```


Charger une texture depuis un fichier

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static TextureData fromStream(Stream stream)
```


Charger une texture depuis un flux

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
### getBytesPerPixel() {#getBytesPerPixel--}
```
public int getBytesPerPixel()
```


Nombre d'octets d'un pixel

**Returns:**
int - Nombre d'octets d'un pixel
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getData() {#getData--}
```
public byte[] getData()
```


Octets bruts des données de pixel

**Returns:**
byte[] - Octets bruts des données du pixel
### getHeight() {#getHeight--}
```
public int getHeight()
```


Nombre de pixels verticaux

**Returns:**
int - Nombre de pixels verticaux
### getName() {#getName--}
```
public String getName()
```


Obtient le nom.

**Returns:**
java.lang.String - le nom.
### getPixelFormat() {#getPixelFormat--}
```
public PixelFormat getPixelFormat()
```


Le format du pixel

**Returns:**
[PixelFormat](../../com.aspose.threed/pixelformat) - The pixel's format
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
### getStride() {#getStride--}
```
public int getStride()
```


Nombre d'octets d'une ligne de balayage.

**Returns:**
int - Nombre d'octets d'une ligne de balayage.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Nombre de pixels horizontaux

**Returns:**
int - Nombre de pixels horizontaux
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### mapPixels(PixelMapMode mapMode) {#mapPixels-com.aspose.threed.PixelMapMode-}
```
public PixelMapping mapPixels(PixelMapMode mapMode)
```


Mapper tous les pixels en lecture/écriture

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Mode de mappage |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(PixelMapMode mapMode, PixelFormat format)
```


Mapper tous les pixels en lecture/écriture dans le format de pixel donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Mode de mappage |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Format de pixel |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping)
### mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format) {#mapPixels-com.aspose.threed.Rect-com.aspose.threed.PixelMapMode-com.aspose.threed.PixelFormat-}
```
public PixelMapping mapPixels(Rect rect, PixelMapMode mapMode, PixelFormat format)
```


Mapper les pixels adressés par le rectangle pour la lecture/écriture dans le format de pixel donné

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| rect | [Rect](../../com.aspose.threed/rect) | La zone de pixels à accéder |
| mapMode | [PixelMapMode](../../com.aspose.threed/pixelmapmode) | Mode de mappage |
| format | [PixelFormat](../../com.aspose.threed/pixelformat) | Format de pixel |

**Returns:**
[PixelMapping](../../com.aspose.threed/pixelmapping) - Returns a mapping object, it should be disposed when no longer needed.
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
### save(Stream stream, String format) {#save-com.aspose.threed.Stream-java.lang.String-}
```
public void save(Stream stream, String format)
```


Enregistrer les données de texture dans le format d'image spécifié

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Le flux qui contient l'image enregistrée |
| format | java.lang.String | Format d'image, généralement l'extension du fichier |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


Enregistrer les données de texture dans un fichier image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nom de fichier où l'image sera enregistrée. |

### save(String fileName, String format) {#save-java.lang.String-java.lang.String-}
```
public void save(String fileName, String format)
```


Enregistrer les données de texture dans un fichier image

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | java.lang.String | Le nom de fichier où l'image sera enregistrée. |
| format | java.lang.String | Format d'image du fichier de sortie. |

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

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### transformPixelFormat(PixelFormat pixelFormat) {#transformPixelFormat-com.aspose.threed.PixelFormat-}
```
public void transformPixelFormat(PixelFormat pixelFormat)
```


Transformer la disposition du pixel vers un nouveau format de pixel.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| pixelFormat | [PixelFormat](../../com.aspose.threed/pixelformat) | Format de pixel de destination |

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

