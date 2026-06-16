---
title: "AssetInfo"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Informations de l'actif."
type: docs
weight: 17
url: /fr/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Informations de l'actif. Les informations d'actif peuvent être attachées à une [Scene](../../com.aspose.threed/scene). Une [Scene](../../com.aspose.threed/scene) enfant peut avoir son propre [AssetInfo](../../com.aspose.threed/assetinfo) pour remplacer la définition du parent. **Exemple:** Le code suivant montre comment lire les informations d'actif à partir d'un fichier fbx :

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Initialise une nouvelle instance de la classe [AssetInfo](../../com.aspose.threed/assetinfo). |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Initialise une nouvelle instance de la classe [AssetInfo](../../com.aspose.threed/assetinfo). |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trouve la propriété. |
| [getAmbient()](#getAmbient--) | Obtient ou définit la couleur ambiante par défaut de cet actif |
| [getApplicationName()](#getApplicationName--) | Obtient l'application qui a créé cet actif |
| [getApplicationVendor()](#getApplicationVendor--) | Obtient le nom du fournisseur de l'application |
| [getApplicationVersion()](#getApplicationVersion--) | Obtient la version de l'application qui a créé cet actif. |
| [getAuthor()](#getAuthor--) | Obtient l'auteur de cet actif |
| [getAxisSystem()](#getAxisSystem--) | Obtient le système de coordonnées / le vecteur up / le vecteur front de l'information d'actif. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Obtient le commentaire de cet actif. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Obtient le système de coordonnées utilisé dans cet actif. |
| [getCopyright()](#getCopyright--) | Obtient le droit d'auteur du document |
| [getCreationTime()](#getCreationTime--) | Obtient ou définit l'heure de création de cet actif |
| [getFrontVector()](#getFrontVector--) | Obtient le vecteur avant utilisé dans cet actif. |
| [getKeywords()](#getKeywords--) | Obtient les mots-clés de cet actif |
| [getModificationTime()](#getModificationTime--) | Obtient ou définit l'heure de modification de cet actif |
| [getName()](#getName--) | Obtient le nom. |
| [getProperties()](#getProperties--) | Obtient la collection de toutes les propriétés. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Obtenir la valeur de la propriété spécifiée |
| [getRevision()](#getRevision--) | Obtient le numéro de révision de cet actif, généralement utilisé dans le système de contrôle de version. |
| [getSubject()](#getSubject--) | Obtient le sujet de cet actif |
| [getTitle()](#getTitle--) | Obtient le titre de cet actif |
| [getUnitName()](#getUnitName--) | Obtient l'unité de longueur utilisée dans cet actif. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Obtient le facteur d'échelle vers le mètre réel. |
| [getUpVector()](#getUpVector--) | Obtient le vecteur haut utilisé dans cet actif. |
| [getUrl()](#getUrl--) | Obtient ou définit l'URL de cet actif. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Supprime une propriété dynamique. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Supprime la propriété spécifiée identifiée par son nom |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Obtient ou définit la couleur ambiante par défaut de cet actif |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Définit l'application qui a créé cet actif |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Définit le nom du fournisseur de l'application |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Définit la version de l'application qui a créé cet actif. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Définit l'auteur de cet actif |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Définit le système de coordonnées/vecteur haut/vecteur avant des informations de l'actif. |
| [setComment(String value)](#setComment-java.lang.String-) | Définit le commentaire de cet actif. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Définit le système de coordonnées utilisé dans cet actif. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Définit le droit d'auteur du document |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Obtient ou définit l'heure de création de cet actif |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Définit le vecteur avant utilisé dans cet actif. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Définit les mots-clés de cet actif |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Obtient ou définit l'heure de modification de cet actif |
| [setName(String value)](#setName-java.lang.String-) | Définit le nom. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Définit la valeur de la propriété spécifiée |
| [setRevision(String value)](#setRevision-java.lang.String-) | Définit le numéro de révision de cet actif, généralement utilisé dans le système de contrôle de version. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Définit le sujet de cet actif |
| [setTitle(String value)](#setTitle-java.lang.String-) | Définit le titre de cet actif |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Définit l'unité de longueur utilisée dans cet actif. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Définit le facteur d'échelle en mètres réels. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Définit le vecteur up utilisé dans cet actif. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Obtient ou définit l'URL de cet actif. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Initialise une nouvelle instance de la classe [AssetInfo](../../com.aspose.threed/assetinfo).

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Initialise une nouvelle instance de la classe [AssetInfo](../../com.aspose.threed/assetinfo).

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
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Obtient ou définit la couleur ambiante par défaut de cet actif

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Obtient l'application qui a créé cet actif

**Returns:**
java.lang.String - l'application qui a créé cet actif
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Obtient le nom du fournisseur de l'application

**Returns:**
java.lang.String - le nom du fournisseur de l'application
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Obtient la version de l'application qui a créé cet actif.

**Returns:**
java.lang.String - la version de l'application qui a créé cet actif.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Obtient l'auteur de cet actif

**Returns:**
java.lang.String - l'auteur de cet actif
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Obtient le système de coordonnées / le vecteur up / le vecteur front de l'information d'actif.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the coordinate system/up vector/front vector of the asset info.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getComment() {#getComment--}
```
public String getComment()
```


Obtient le commentaire de cet actif.

**Returns:**
java.lang.String - le commentaire de cet actif.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Obtient le système de coordonnées utilisé dans cet actif.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Obtient le droit d'auteur du document

**Returns:**
java.lang.String - le droit d'auteur du document
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Obtient ou définit l'heure de création de cet actif

**Returns:**
java.util.Calendar - ou Définit l'heure de création de cet actif
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Obtient le vecteur avant utilisé dans cet actif.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Obtient les mots-clés de cet actif

**Returns:**
java.lang.String - les mots-clés de cet actif
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Obtient ou définit l'heure de modification de cet actif

**Returns:**
java.util.Calendar - ou Définit l'heure de modification de cet actif
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
### getRevision() {#getRevision--}
```
public String getRevision()
```


Obtient le numéro de révision de cet actif, généralement utilisé dans le système de contrôle de version.

**Returns:**
java.lang.String - le numéro de révision de cet actif, généralement utilisé dans le système de contrôle de version.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Obtient le sujet de cet actif

**Returns:**
java.lang.String - le sujet de cet actif
### getTitle() {#getTitle--}
```
public String getTitle()
```


Obtient le titre de cet actif

**Returns:**
java.lang.String - le titre de cet actif
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Obtient l'unité de longueur utilisée dans cet actif. ex. cm/m/km/pouce/pieds

**Returns:**
java.lang.String - l'unité de longueur utilisée dans cet actif. ex. cm/m/km/pouce/pieds
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Obtient le facteur d'échelle vers le mètre réel.

**Returns:**
double - le facteur d'échelle en mètres réels. **Remarks:** Ceci est ignoré lors de la sérialisation si le nom de l'unité est nul.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Obtient le vecteur haut utilisé dans cet actif.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Obtient ou définit l'URL de cet actif.

**Returns:**
java.lang.String - ou Définit l'URL de cet actif.
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
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Obtient ou définit la couleur ambiante par défaut de cet actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Nouvelle valeur |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Définit l'application qui a créé cet actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Définit le nom du fournisseur de l'application

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Définit la version de l'application qui a créé cet actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Définit l'auteur de cet actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Définit le système de coordonnées/vecteur haut/vecteur avant des informations de l'actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nouvelle valeur |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Définit le commentaire de cet actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Définit le système de coordonnées utilisé dans cet actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Nouvelle valeur |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Définit le droit d'auteur du document

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Obtient ou définit l'heure de création de cet actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Calendar | Nouvelle valeur |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Définit le vecteur avant utilisé dans cet actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nouvelle valeur |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Définit les mots-clés de cet actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Obtient ou définit l'heure de modification de cet actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.Calendar | Nouvelle valeur |

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

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Définit le numéro de révision de cet actif, généralement utilisé dans le système de contrôle de version.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Définit le sujet de cet actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Définit le titre de cet actif

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Définit l'unité de longueur utilisée dans cet actif. ex. cm/m/km/pouce/pieds

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Définit le facteur d'échelle en mètres réels.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | double | Nouvelle valeur **Remarks:** Ceci est ignoré lors de la sérialisation si le nom de l'unité est nul. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Définit le vecteur up utilisé dans cet actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nouvelle valeur |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Obtient ou définit l'URL de cet actif.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

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

