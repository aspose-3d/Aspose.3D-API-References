---
title: AssetInfo
second_title: Aspose.3D for Java API-referens
description: Information om tillgången.
type: docs
weight: 17
url: /sv/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Information om tillgången. Tillgångsinformation kan bifogas till en [Scene](../../com.aspose.threed/scene). Ett underordnat [Scene](../../com.aspose.threed/scene) kan ha sin egen [AssetInfo](../../com.aspose.threed/assetinfo) för att åsidosätta förälderns definition. **Exempel:** Följande kod visar hur man läser tillgångsinformation från en fbx-fil:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Initierar en ny instans av klassen [AssetInfo](../../com.aspose.threed/assetinfo). |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Initierar en ny instans av klassen [AssetInfo](../../com.aspose.threed/assetinfo). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Hittar egenskapen. |
| [getAmbient()](#getAmbient--) | Hämtar eller anger standardambientfärgen för denna tillgång |
| [getApplicationName()](#getApplicationName--) | Hämtar applikationen som skapade denna tillgång |
| [getApplicationVendor()](#getApplicationVendor--) | Hämtar applikationens leverantörsnamn |
| [getApplicationVersion()](#getApplicationVersion--) | Hämtar versionen av applikationen som skapade denna tillgång. |
| [getAuthor()](#getAuthor--) | Hämtar författaren till denna tillgång |
| [getAxisSystem()](#getAxisSystem--) | Hämtar koordinatsystemet/uppvektorn/främre vektorn för tillgångsinformationen. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Hämtar kommentaren för denna tillgång. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Hämtar koordinatsystemet som används i denna tillgång. |
| [getCopyright()](#getCopyright--) | Hämtar dokumentets upphovsrätt |
| [getCreationTime()](#getCreationTime--) | Hämtar eller anger skapandetiden för denna tillgång |
| [getFrontVector()](#getFrontVector--) | Hämtar frontvektorn som används i denna tillgång. |
| [getKeywords()](#getKeywords--) | Hämtar nyckelorden för denna tillgång |
| [getModificationTime()](#getModificationTime--) | Hämtar eller anger ändringstiden för denna tillgång |
| [getName()](#getName--) | Hämtar namnet. |
| [getProperties()](#getProperties--) | Hämtar samlingen av alla egenskaper. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Hämta värdet för angiven egenskap |
| [getRevision()](#getRevision--) | Hämtar revisionsnumret för denna tillgång, vanligtvis använt i versionskontrollsystem. |
| [getSubject()](#getSubject--) | Hämtar ämnet för denna tillgång |
| [getTitle()](#getTitle--) | Hämtar titeln för denna tillgång |
| [getUnitName()](#getUnitName--) | Hämtar längdenheten som används i denna tillgång. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Hämtar skalfaktorn till verklig meter. |
| [getUpVector()](#getUpVector--) | Hämtar uppvektorn som används i denna tillgång. |
| [getUrl()](#getUrl--) | Hämtar eller anger URL:en för denna tillgång. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Tar bort en dynamisk egenskap. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Ta bort den angivna egenskapen identifierad med namn |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Hämtar eller anger standardambientfärgen för denna tillgång |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Anger programmet som skapade denna tillgång |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Anger leverantörens namn för programmet |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Anger versionen av programmet som skapade denna tillgång. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Anger författaren till denna tillgång |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Anger koordinatsystemet/uppvektorn/frontvektorn för tillgångsinformationen. |
| [setComment(String value)](#setComment-java.lang.String-) | Anger kommentaren för denna tillgång. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Anger koordinatsystemet som används i denna tillgång. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Anger dokumentets upphovsrätt |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Hämtar eller anger skapandetiden för denna tillgång |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Anger frontvektorn som används i denna tillgång. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Anger nyckelorden för denna tillgång |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Hämtar eller anger ändringstiden för denna tillgång |
| [setName(String value)](#setName-java.lang.String-) | Ställer in namnet. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Ställer in värdet för angiven egenskap |
| [setRevision(String value)](#setRevision-java.lang.String-) | Anger revisionsnumret för denna tillgång, vanligtvis använt i versionskontrollsystem. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Anger ämnet för denna tillgång |
| [setTitle(String value)](#setTitle-java.lang.String-) | Anger titeln för denna tillgång |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Anger längdenheten som används i denna tillgång. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Ställer in skalfaktorn till verklig meter. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Ställer in uppvektorn som används i denna tillgång. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Hämtar eller anger URL:en för denna tillgång. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Initierar en ny instans av klassen [AssetInfo](../../com.aspose.threed/assetinfo).

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Initierar en ny instans av klassen [AssetInfo](../../com.aspose.threed/assetinfo).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String | Namn |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Hittar egenskapen. Den kan vara en dynamisk egenskap (Skapad av CreateDynamicProperty/SetProperty) eller en inbyggd egenskap (Identifierad med dess namn)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| propertyName | java.lang.String | Egenskapsnamn. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Hämtar eller anger standardambientfärgen för denna tillgång

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Hämtar applikationen som skapade denna tillgång

**Returns:**
java.lang.String - programmet som skapade denna tillgång
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Hämtar applikationens leverantörsnamn

**Returns:**
java.lang.String - leverantörens namn för applikationen
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Hämtar versionen av applikationen som skapade denna tillgång.

**Returns:**
java.lang.String - versionen av programmet som skapade denna tillgång.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Hämtar författaren till denna tillgång

**Returns:**
java.lang.String - författaren till denna tillgång
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Hämtar koordinatsystemet/uppvektorn/främre vektorn för tillgångsinformationen.

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


Hämtar kommentaren för denna tillgång.

**Returns:**
java.lang.String - kommentaren för denna tillgång.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Hämtar koordinatsystemet som används i denna tillgång.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Hämtar dokumentets upphovsrätt

**Returns:**
java.lang.String - dokumentets upphovsrätt
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Hämtar eller anger skapandetiden för denna tillgång

**Returns:**
java.util.Calendar - eller Ställer in skapandetiden för denna tillgång
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Hämtar frontvektorn som används i denna tillgång.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Hämtar nyckelorden för denna tillgång

**Returns:**
java.lang.String - nyckelorden för denna tillgång
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Hämtar eller anger ändringstiden för denna tillgång

**Returns:**
java.util.Calendar - eller Ställer in ändringstiden för denna tillgång
### getName() {#getName--}
```
public String getName()
```


Hämtar namnet.

**Returns:**
java.lang.String - namnet.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Hämtar samlingen av alla egenskaper.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Hämta värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |

**Returns:**
java.lang.Object - Värdet på den hittade egenskapen
### getRevision() {#getRevision--}
```
public String getRevision()
```


Hämtar revisionsnumret för denna tillgång, vanligtvis använt i versionskontrollsystem.

**Returns:**
java.lang.String - revisionsnumret för denna tillgång, vanligtvis använt i versionskontrollsystem.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Hämtar ämnet för denna tillgång

**Returns:**
java.lang.String - ämnet för denna tillgång
### getTitle() {#getTitle--}
```
public String getTitle()
```


Hämtar titeln för denna tillgång

**Returns:**
java.lang.String - titeln för denna tillgång
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Hämtar längdenheten som används i denna tillgång. t.ex. cm/m/km/tum/fot

**Returns:**
java.lang.String - längdenheten som används i denna tillgång. t.ex. cm/m/km/tum/fot
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Hämtar skalfaktorn till verklig meter.

**Returns:**
double - skalfaktorn till verklig meter. **Remarks:** Detta ignoreras vid serialisering om enhetsnamnet är null.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Hämtar uppvektorn som används i denna tillgång.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Hämtar eller anger URL:en för denna tillgång.

**Returns:**
java.lang.String - eller Ställer in URL:en för denna tillgång.
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


Tar bort en dynamisk egenskap.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Ta bort den angivna egenskapen identifierad med namn

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Vilken egenskap som ska tas bort |

**Returns:**
boolean - true om egenskapen har tagits bort framgångsrikt
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Hämtar eller anger standardambientfärgen för denna tillgång

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Nytt värde |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Anger programmet som skapade denna tillgång

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Anger leverantörens namn för programmet

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Anger versionen av programmet som skapade denna tillgång.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Anger författaren till denna tillgång

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Anger koordinatsystemet/uppvektorn/frontvektorn för tillgångsinformationen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nytt värde |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Anger kommentaren för denna tillgång.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Anger koordinatsystemet som används i denna tillgång.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Nytt värde |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Anger dokumentets upphovsrätt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Hämtar eller anger skapandetiden för denna tillgång

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Calendar | Nytt värde |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Anger frontvektorn som används i denna tillgång.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nytt värde |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Anger nyckelorden för denna tillgång

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Hämtar eller anger ändringstiden för denna tillgång

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.Calendar | Nytt värde |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Ställer in namnet.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Ställer in värdet för angiven egenskap

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| egenskap | java.lang.String | Egenskapsnamn |
| värde | java.lang.Object | Värdet på egenskapen |

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Anger revisionsnumret för denna tillgång, vanligtvis använt i versionskontrollsystem.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Anger ämnet för denna tillgång

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Anger titeln för denna tillgång

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Ställer in längdenheten som används i denna tillgång. t.ex. cm/m/km/tum/fot

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Ställer in skalfaktorn till verklig meter.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | double | Nytt värde **Remarks:** Detta ignoreras vid serialisering om enhetsnamnet är null. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Ställer in uppvektorn som används i denna tillgång.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nytt värde |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Hämtar eller anger URL:en för denna tillgång.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

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

