---
title: AssetInfo
second_title: Aspose.3D for Java API-referentie
description: Informatie van asset.
type: docs
weight: 17
url: /nl/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Informatie van asset. Assetinformatie kan worden gekoppeld aan een [Scene](../../com.aspose.threed/scene). Een onderliggende [Scene](../../com.aspose.threed/scene) kan zijn eigen [AssetInfo](../../com.aspose.threed/assetinfo) hebben om de definitie van de ouder te overschrijven. **Voorbeeld:** De volgende code laat zien hoe assetinformatie uit een fbx‑bestand kan worden gelezen:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Initialiseert een nieuw exemplaar van de [AssetInfo](../../com.aspose.threed/assetinfo) klasse. |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Initialiseert een nieuw exemplaar van de [AssetInfo](../../com.aspose.threed/assetinfo) klasse. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Zoekt de eigenschap. |
| [getAmbient()](#getAmbient--) | Haalt op of stelt de standaard omgevingskleur van dit asset in. |
| [getApplicationName()](#getApplicationName--) | Haalt de applicatie op die dit asset heeft gemaakt. |
| [getApplicationVendor()](#getApplicationVendor--) | Haalt de naam van de leverancier van de applicatie op. |
| [getApplicationVersion()](#getApplicationVersion--) | Haalt de versie van de applicatie op die dit asset heeft gemaakt. |
| [getAuthor()](#getAuthor--) | Haalt de auteur van dit asset op. |
| [getAxisSystem()](#getAxisSystem--) | Haalt het coördinatensysteem/up‑vector/front‑vector van de assetinformatie op. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Haalt de opmerking van dit asset op. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Haalt het coördinatensysteem op dat in dit asset wordt gebruikt. |
| [getCopyright()](#getCopyright--) | Haalt het auteursrecht van het document op. |
| [getCreationTime()](#getCreationTime--) | Haalt op of stelt de creatietijd van dit asset in |
| [getFrontVector()](#getFrontVector--) | Haalt de front-vector op die in dit asset wordt gebruikt. |
| [getKeywords()](#getKeywords--) | Haalt de trefwoorden van dit asset op |
| [getModificationTime()](#getModificationTime--) | Haalt op of stelt de wijzigingstijd van dit asset in |
| [getName()](#getName--) | Haalt de naam op. |
| [getProperties()](#getProperties--) | Haalt de verzameling van alle eigenschappen op. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Haalt de waarde op van de opgegeven eigenschap |
| [getRevision()](#getRevision--) | Haalt het revisienummer van dit asset op, meestal gebruikt in versiebeheersystemen. |
| [getSubject()](#getSubject--) | Haalt het onderwerp van dit asset op |
| [getTitle()](#getTitle--) | Haalt de titel van dit asset op |
| [getUnitName()](#getUnitName--) | Haalt de eenheid van lengte die in dit asset wordt gebruikt op. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Haalt de schaalfactor naar de echte meter op. |
| [getUpVector()](#getUpVector--) | Haalt de up-vector op die in dit asset wordt gebruikt. |
| [getUrl()](#getUrl--) | Haalt op of stelt de URL van dit asset in. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Verwijdert een dynamische eigenschap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Verwijder de opgegeven eigenschap geïdentificeerd op naam |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Haalt op of stelt de standaard omgevingskleur van dit asset in. |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Stelt de applicatie in die dit asset heeft gemaakt. |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Stelt de naam van de applicatieleverancier in. |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Stelt de versie van de applicatie in die dit asset heeft gemaakt. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Stelt de auteur van dit asset in. |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Stelt het coördinatensysteem/up-vector/front-vector van de assetinformatie in. |
| [setComment(String value)](#setComment-java.lang.String-) | Stelt de opmerking van dit asset in. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Stelt het coördinatensysteem in dat in dit asset wordt gebruikt. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Stelt het auteursrecht van het document in. |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Haalt op of stelt de creatietijd van dit asset in |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Stelt de front-vector in die in dit asset wordt gebruikt. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Stelt de trefwoorden van dit asset in. |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Haalt op of stelt de wijzigingstijd van dit asset in |
| [setName(String value)](#setName-java.lang.String-) | Stelt de naam in. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Stelt de waarde in van de opgegeven eigenschap |
| [setRevision(String value)](#setRevision-java.lang.String-) | Stelt het revisienummer van dit asset in, meestal gebruikt in versiebeheersystemen. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Stelt het onderwerp van dit asset in. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Stelt de titel van dit asset in. |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Stelt de eenheid van lengte in die in dit asset wordt gebruikt. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Stelt de schaalfactor in op echte meter. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Stelt de up-vector in die in dit asset wordt gebruikt. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Haalt op of stelt de URL van dit asset in. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Initialiseert een nieuw exemplaar van de [AssetInfo](../../com.aspose.threed/assetinfo) klasse.

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Initialiseert een nieuw exemplaar van de [AssetInfo](../../com.aspose.threed/assetinfo) klasse.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| naam | java.lang.String | Naam |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Zoekt de eigenschap. Het kan een dynamische eigenschap zijn (gemaakt door CreateDynamicProperty/SetProperty) of een native eigenschap (geïdentificeerd op naam).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| propertyName | java.lang.String | Eigenschapnaam. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Haalt op of stelt de standaard omgevingskleur van dit asset in.

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Haalt de applicatie op die dit asset heeft gemaakt.

**Returns:**
java.lang.String - de applicatie die dit asset heeft gemaakt
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Haalt de naam van de leverancier van de applicatie op.

**Returns:**
java.lang.String - de naam van de leverancier van de applicatie
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Haalt de versie van de applicatie op die dit asset heeft gemaakt.

**Returns:**
java.lang.String - de versie van de applicatie die dit asset heeft gemaakt.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Haalt de auteur van dit asset op.

**Returns:**
java.lang.String - de auteur van dit asset
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Haalt het coördinatensysteem/up‑vector/front‑vector van de assetinformatie op.

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


Haalt de opmerking van dit asset op.

**Returns:**
java.lang.String - de opmerking van dit asset.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Haalt het coördinatensysteem op dat in dit asset wordt gebruikt.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Haalt het auteursrecht van het document op.

**Returns:**
java.lang.String - het auteursrecht van het document
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Haalt op of stelt de creatietijd van dit asset in

**Returns:**
java.util.Calendar - of stelt de creatietijd van dit asset in
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Haalt de front-vector op die in dit asset wordt gebruikt.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Haalt de trefwoorden van dit asset op

**Returns:**
java.lang.String - de trefwoorden van dit asset
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Haalt op of stelt de wijzigingstijd van dit asset in

**Returns:**
java.util.Calendar - of stelt de wijzigingstijd van dit asset in
### getName() {#getName--}
```
public String getName()
```


Haalt de naam op.

**Returns:**
java.lang.String - de naam.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Haalt de verzameling van alle eigenschappen op.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Haalt de waarde op van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |

**Returns:**
java.lang.Object - De waarde van de gevonden eigenschap
### getRevision() {#getRevision--}
```
public String getRevision()
```


Haalt het revisienummer van dit asset op, meestal gebruikt in versiebeheersystemen.

**Returns:**
java.lang.String - het revisienummer van dit asset, meestal gebruikt in versiebeheersystemen.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Haalt het onderwerp van dit asset op

**Returns:**
java.lang.String - het onderwerp van dit asset
### getTitle() {#getTitle--}
```
public String getTitle()
```


Haalt de titel van dit asset op

**Returns:**
java.lang.String - de titel van dit asset
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Haalt de lengteeenheid op die in dit asset wordt gebruikt. bijv. cm/m/km/inch/feet

**Returns:**
java.lang.String - de lengteeenheid die in dit asset wordt gebruikt. bijv. cm/m/km/inch/feet
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Haalt de schaalfactor naar de echte meter op.

**Returns:**
double - de schaalfactor naar echte meter. **Opmerkingen:** Dit wordt genegeerd tijdens serialisatie als de eenheidsnaam null is.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Haalt de up-vector op die in dit asset wordt gebruikt.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Haalt op of stelt de URL van dit asset in.

**Returns:**
java.lang.String - of stelt de URL van dit asset in.
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


Verwijdert een dynamische eigenschap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Verwijder de opgegeven eigenschap geïdentificeerd op naam

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Welke eigenschap moet worden verwijderd |

**Returns:**
boolean - true als de eigenschap succesvol is verwijderd
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Haalt op of stelt de standaard omgevingskleur van dit asset in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Nieuwe waarde |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Stelt de applicatie in die dit asset heeft gemaakt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Stelt de naam van de applicatieleverancier in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Stelt de versie van de applicatie in die dit asset heeft gemaakt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Stelt de auteur van dit asset in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Stelt het coördinatensysteem/up-vector/front-vector van de assetinformatie in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nieuwe waarde |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Stelt de opmerking van dit asset in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Stelt het coördinatensysteem in dat in dit asset wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Nieuwe waarde |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Stelt het auteursrecht van het document in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Haalt op of stelt de creatietijd van dit asset in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Calendar | Nieuwe waarde |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Stelt de front-vector in die in dit asset wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nieuwe waarde |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Stelt de trefwoorden van dit asset in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Haalt op of stelt de wijzigingstijd van dit asset in

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.util.Calendar | Nieuwe waarde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Stelt de naam in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Stelt de waarde in van de opgegeven eigenschap

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| eigenschap | java.lang.String | Naam van eigenschap |
| waarde | java.lang.Object | De waarde van de eigenschap |

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Stelt het revisienummer van dit asset in, meestal gebruikt in versiebeheersystemen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Stelt het onderwerp van dit asset in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Stelt de titel van dit asset in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Stelt de lengteeenheid in die in dit asset wordt gebruikt. bijv. cm/m/km/inch/feet

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Stelt de schaalfactor in op echte meter.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde **Opmerkingen:** Dit wordt genegeerd tijdens serialisatie als de eenheidsnaam null is. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Stelt de up-vector in die in dit asset wordt gebruikt.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nieuwe waarde |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Haalt op of stelt de URL van dit asset in.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

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

