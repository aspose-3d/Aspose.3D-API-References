---
title: AssetInfo
second_title: Aspose.3D for Java API Reference
description: Informazioni sull'asset.
type: docs
weight: 17
url: /it/java/com.aspose.threed/assetinfo/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)
```
public class AssetInfo extends A3DObject
```

Informazioni dell'asset. Le informazioni sull'asset possono essere associate a una [Scene](../../com.aspose.threed/scene). Una [Scene](../../com.aspose.threed/scene) figlia può avere il proprio [AssetInfo](../../com.aspose.threed/assetinfo) per sovrascrivere la definizione del genitore. **Example:** Il codice seguente mostra come leggere le informazioni dell'asset da un file fbx:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The file is created at %s by %s %s",
          scene.getAssetInfo().getCreationTime(),
          scene.getAssetInfo().getApplicationName(),
          scene.getAssetInfo().getApplicationVersion());
```
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [AssetInfo()](#AssetInfo--) | Inizializza una nuova istanza della classe [AssetInfo](../../com.aspose.threed/assetinfo). |
| [AssetInfo(String name)](#AssetInfo-java.lang.String-) | Inizializza una nuova istanza della classe [AssetInfo](../../com.aspose.threed/assetinfo). |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | Trova la proprietà. |
| [getAmbient()](#getAmbient--) | Ottiene o imposta il colore ambientale predefinito di questo asset |
| [getApplicationName()](#getApplicationName--) | Ottiene l'applicazione che ha creato questo asset |
| [getApplicationVendor()](#getApplicationVendor--) | Ottiene il nome del fornitore dell'applicazione |
| [getApplicationVersion()](#getApplicationVersion--) | Ottiene la versione dell'applicazione che ha creato questo asset. |
| [getAuthor()](#getAuthor--) | Ottiene l'autore di questo asset |
| [getAxisSystem()](#getAxisSystem--) | Ottiene il sistema di coordinate/vettore up/vettore front delle informazioni dell'asset. |
| [getClass()](#getClass--) |  |
| [getComment()](#getComment--) | Ottiene il commento di questo asset. |
| [getCoordinateSystem()](#getCoordinateSystem--) | Ottiene il sistema di coordinate utilizzato in questo asset. |
| [getCopyright()](#getCopyright--) | Ottiene il copyright del documento |
| [getCreationTime()](#getCreationTime--) | Ottiene o imposta l'ora di creazione di questo asset |
| [getFrontVector()](#getFrontVector--) | Ottiene il vettore frontale utilizzato in questo asset. |
| [getKeywords()](#getKeywords--) | Ottiene le parole chiave di questo asset |
| [getModificationTime()](#getModificationTime--) | Ottiene o imposta l'ora di modifica di questo asset |
| [getName()](#getName--) | Ottiene il nome. |
| [getProperties()](#getProperties--) | Ottiene la collezione di tutte le proprietà. |
| [getProperty(String property)](#getProperty-java.lang.String-) | Ottieni il valore della proprietà specificata |
| [getRevision()](#getRevision--) | Ottiene il numero di revisione di questo asset, solitamente usato nei sistemi di controllo versione. |
| [getSubject()](#getSubject--) | Ottiene l'oggetto di questo asset |
| [getTitle()](#getTitle--) | Ottiene il titolo di questo asset |
| [getUnitName()](#getUnitName--) | Ottiene l'unità di lunghezza utilizzata in questo asset. |
| [getUnitScaleFactor()](#getUnitScaleFactor--) | Ottiene il fattore di scala in metri del mondo reale. |
| [getUpVector()](#getUpVector--) | Ottiene il vettore up utilizzato in questo asset. |
| [getUrl()](#getUrl--) | Ottiene o imposta l'URL di questo asset. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | Rimuove una proprietà dinamica. |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | Rimuove la proprietà specificata identificata per nome |
| [setAmbient(Vector4 value)](#setAmbient-com.aspose.threed.Vector4-) | Ottiene o imposta il colore ambientale predefinito di questo asset |
| [setApplicationName(String value)](#setApplicationName-java.lang.String-) | Imposta l'applicazione che ha creato questo asset |
| [setApplicationVendor(String value)](#setApplicationVendor-java.lang.String-) | Imposta il nome del fornitore dell'applicazione |
| [setApplicationVersion(String value)](#setApplicationVersion-java.lang.String-) | Imposta la versione dell'applicazione che ha creato questo asset. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Imposta l'autore di questo asset |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Imposta il sistema di coordinate/vettore up/vettore frontale delle informazioni dell'asset. |
| [setComment(String value)](#setComment-java.lang.String-) | Imposta il commento di questo asset. |
| [setCoordinateSystem(CoordinateSystem value)](#setCoordinateSystem-com.aspose.threed.CoordinateSystem-) | Imposta il sistema di coordinate utilizzato in questo asset. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Imposta il copyright del documento |
| [setCreationTime(Calendar value)](#setCreationTime-java.util.Calendar-) | Ottiene o imposta l'ora di creazione di questo asset |
| [setFrontVector(Axis value)](#setFrontVector-com.aspose.threed.Axis-) | Imposta il vettore frontale utilizzato in questo asset. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Imposta le parole chiave di questo asset |
| [setModificationTime(Calendar value)](#setModificationTime-java.util.Calendar-) | Ottiene o imposta l'ora di modifica di questo asset |
| [setName(String value)](#setName-java.lang.String-) | Imposta il nome. |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | Imposta il valore della proprietà specificata |
| [setRevision(String value)](#setRevision-java.lang.String-) | Imposta il numero di revisione di questo asset, solitamente usato nei sistemi di controllo versione. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Imposta l'oggetto di questo asset |
| [setTitle(String value)](#setTitle-java.lang.String-) | Imposta il titolo di questo asset |
| [setUnitName(String value)](#setUnitName-java.lang.String-) | Imposta l'unità di lunghezza utilizzata in questo asset. |
| [setUnitScaleFactor(double value)](#setUnitScaleFactor-double-) | Imposta il fattore di scala al metro reale. |
| [setUpVector(Axis value)](#setUpVector-com.aspose.threed.Axis-) | Imposta il vettore up utilizzato in questo asset. |
| [setUrl(String value)](#setUrl-java.lang.String-) | Ottiene o imposta l'URL di questo asset. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### AssetInfo() {#AssetInfo--}
```
public AssetInfo()
```


Inizializza una nuova istanza della classe [AssetInfo](../../com.aspose.threed/assetinfo).

### AssetInfo(String name) {#AssetInfo-java.lang.String-}
```
public AssetInfo(String name)
```


Inizializza una nuova istanza della classe [AssetInfo](../../com.aspose.threed/assetinfo).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String | Nome |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


Trova la proprietà. Può essere una proprietà dinamica (creata con CreateDynamicProperty/SetProperty) o una proprietà nativa (identificata per nome).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| propertyName | java.lang.String | Nome della proprietà. |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### getAmbient() {#getAmbient--}
```
public Vector4 getAmbient()
```


Ottiene o imposta il colore ambientale predefinito di questo asset

**Returns:**
[Vector4](../../com.aspose.threed/vector4) - or Sets the default ambient color of this asset
### getApplicationName() {#getApplicationName--}
```
public String getApplicationName()
```


Ottiene l'applicazione che ha creato questo asset

**Returns:**
java.lang.String - l'applicazione che ha creato questo asset
### getApplicationVendor() {#getApplicationVendor--}
```
public String getApplicationVendor()
```


Ottiene il nome del fornitore dell'applicazione

**Returns:**
java.lang.String - il nome del fornitore dell'applicazione
### getApplicationVersion() {#getApplicationVersion--}
```
public String getApplicationVersion()
```


Ottiene la versione dell'applicazione che ha creato questo asset.

**Returns:**
java.lang.String - la versione dell'applicazione che ha creato questo asset.
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Ottiene l'autore di questo asset

**Returns:**
java.lang.String - l'autore di questo asset
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Ottiene il sistema di coordinate/vettore up/vettore front delle informazioni dell'asset.

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


Ottiene il commento di questo asset.

**Returns:**
java.lang.String - il commento di questo asset.
### getCoordinateSystem() {#getCoordinateSystem--}
```
public CoordinateSystem getCoordinateSystem()
```


Ottiene il sistema di coordinate utilizzato in questo asset.

**Returns:**
[CoordinateSystem](../../com.aspose.threed/coordinatesystem) - the coordinate system used in this asset.
### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Ottiene il copyright del documento

**Returns:**
java.lang.String - il copyright del documento
### getCreationTime() {#getCreationTime--}
```
public Calendar getCreationTime()
```


Ottiene o imposta l'ora di creazione di questo asset

**Returns:**
java.util.Calendar - o Imposta l'ora di creazione di questo asset
### getFrontVector() {#getFrontVector--}
```
public Axis getFrontVector()
```


Ottiene il vettore frontale utilizzato in questo asset.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the front-vector used in this asset.
### getKeywords() {#getKeywords--}
```
public String getKeywords()
```


Ottiene le parole chiave di questo asset

**Returns:**
java.lang.String - le parole chiave di questo asset
### getModificationTime() {#getModificationTime--}
```
public Calendar getModificationTime()
```


Ottiene o imposta l'ora di modifica di questo asset

**Returns:**
java.util.Calendar - o Imposta l'ora di modifica di questo asset
### getName() {#getName--}
```
public String getName()
```


Ottiene il nome.

**Returns:**
java.lang.String - il nome.
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


Ottiene la collezione di tutte le proprietà.

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


Ottieni il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |

**Returns:**
java.lang.Object - Il valore della proprietà trovata
### getRevision() {#getRevision--}
```
public String getRevision()
```


Ottiene il numero di revisione di questo asset, solitamente usato nei sistemi di controllo versione.

**Returns:**
java.lang.String - il numero di revisione di questo asset, solitamente usato nei sistemi di controllo versione.
### getSubject() {#getSubject--}
```
public String getSubject()
```


Ottiene l'oggetto di questo asset

**Returns:**
java.lang.String - l'oggetto di questo asset
### getTitle() {#getTitle--}
```
public String getTitle()
```


Ottiene il titolo di questo asset

**Returns:**
java.lang.String - il titolo di questo asset
### getUnitName() {#getUnitName--}
```
public String getUnitName()
```


Ottiene l'unità di lunghezza utilizzata in questo asset. es. cm/m/km/pollice/piedi

**Returns:**
java.lang.String - l'unità di lunghezza utilizzata in questo asset. es. cm/m/km/pollice/piedi
### getUnitScaleFactor() {#getUnitScaleFactor--}
```
public double getUnitScaleFactor()
```


Ottiene il fattore di scala in metri del mondo reale.

**Returns:**
double - il fattore di scala al metro reale. **Remarks:** Questo è ignorato durante la serializzazione se il nome dell'unità è nullo.
### getUpVector() {#getUpVector--}
```
public Axis getUpVector()
```


Ottiene il vettore up utilizzato in questo asset.

**Returns:**
[Axis](../../com.aspose.threed/axis) - the up-vector used in this asset.
### getUrl() {#getUrl--}
```
public String getUrl()
```


Ottiene o imposta l'URL di questo asset.

**Returns:**
java.lang.String - o Imposta l'URL di questo asset.
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


Rimuove una proprietà dinamica.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


Rimuove la proprietà specificata identificata per nome

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Quale proprietà rimuovere |

**Returns:**
boolean - true se la proprietà è stata rimossa con successo
### setAmbient(Vector4 value) {#setAmbient-com.aspose.threed.Vector4-}
```
public void setAmbient(Vector4 value)
```


Ottiene o imposta il colore ambientale predefinito di questo asset

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector4](../../com.aspose.threed/vector4) | Nuovo valore |

### setApplicationName(String value) {#setApplicationName-java.lang.String-}
```
public void setApplicationName(String value)
```


Imposta l'applicazione che ha creato questo asset

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setApplicationVendor(String value) {#setApplicationVendor-java.lang.String-}
```
public void setApplicationVendor(String value)
```


Imposta il nome del fornitore dell'applicazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setApplicationVersion(String value) {#setApplicationVersion-java.lang.String-}
```
public void setApplicationVersion(String value)
```


Imposta la versione dell'applicazione che ha creato questo asset.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Imposta l'autore di questo asset

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Imposta il sistema di coordinate/vettore up/vettore frontale delle informazioni dell'asset.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nuovo valore |

### setComment(String value) {#setComment-java.lang.String-}
```
public void setComment(String value)
```


Imposta il commento di questo asset.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setCoordinateSystem(CoordinateSystem value) {#setCoordinateSystem-com.aspose.threed.CoordinateSystem-}
```
public void setCoordinateSystem(CoordinateSystem value)
```


Imposta il sistema di coordinate utilizzato in questo asset.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CoordinateSystem](../../com.aspose.threed/coordinatesystem) | Nuovo valore |

### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Imposta il copyright del documento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setCreationTime(Calendar value) {#setCreationTime-java.util.Calendar-}
```
public void setCreationTime(Calendar value)
```


Ottiene o imposta l'ora di creazione di questo asset

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Calendar | Nuovo valore |

### setFrontVector(Axis value) {#setFrontVector-com.aspose.threed.Axis-}
```
public void setFrontVector(Axis value)
```


Imposta il vettore frontale utilizzato in questo asset.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nuovo valore |

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public void setKeywords(String value)
```


Imposta le parole chiave di questo asset

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setModificationTime(Calendar value) {#setModificationTime-java.util.Calendar-}
```
public void setModificationTime(Calendar value)
```


Ottiene o imposta l'ora di modifica di questo asset

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.Calendar | Nuovo valore |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


Imposta il nome.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


Imposta il valore della proprietà specificata

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| proprietà | java.lang.String | Nome della proprietà |
| valore | java.lang.Object | Il valore della proprietà |

### setRevision(String value) {#setRevision-java.lang.String-}
```
public void setRevision(String value)
```


Imposta il numero di revisione di questo asset, solitamente usato nei sistemi di controllo versione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setSubject(String value) {#setSubject-java.lang.String-}
```
public void setSubject(String value)
```


Imposta l'oggetto di questo asset

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setTitle(String value) {#setTitle-java.lang.String-}
```
public void setTitle(String value)
```


Imposta il titolo di questo asset

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setUnitName(String value) {#setUnitName-java.lang.String-}
```
public void setUnitName(String value)
```


Imposta l'unità di lunghezza utilizzata in questo asset. es. cm/m/km/pollice/piedi

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setUnitScaleFactor(double value) {#setUnitScaleFactor-double-}
```
public void setUnitScaleFactor(double value)
```


Imposta il fattore di scala al metro reale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | double | Nuovo valore **Remarks:** Questo è ignorato durante la serializzazione se il nome dell'unità è nullo. |

### setUpVector(Axis value) {#setUpVector-com.aspose.threed.Axis-}
```
public void setUpVector(Axis value)
```


Imposta il vettore up utilizzato in questo asset.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Axis](../../com.aspose.threed/axis) | Nuovo valore |

### setUrl(String value) {#setUrl-java.lang.String-}
```
public void setUrl(String value)
```


Ottiene o imposta l'URL di questo asset.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

