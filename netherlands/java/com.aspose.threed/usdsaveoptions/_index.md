---
title: UsdSaveOptions
second_title: Aspose.3D for Java API-referentie
description: Opslagopties voor USD/USDZ-formaten.
type: docs
weight: 200
url: /nl/java/com.aspose.threed/usdsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class UsdSaveOptions extends SaveOptions
```

Opslagopties voor USD/USDZ-formaten.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [UsdSaveOptions()](#UsdSaveOptions--) | Initialiseer een nieuwe [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) met het [FileFormat.USD](../../com.aspose.threed/fileformat\#USD) formaat |
| [UsdSaveOptions(FileFormat fileFormat)](#UsdSaveOptions-com.aspose.threed.FileFormat-) | Initialiseer een nieuwe [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) met het opgegeven USD/USDZ‑formaat. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Haalt de standaardcodering op voor tekstgebaseerde bestanden. |
| [getExportMetaData()](#getExportMetaData--) | Exporteer de eigenschappen van het knooppunt via het customData‑veld van USD. |
| [getExportTextures()](#getExportTextures--) | Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [getFileFormat()](#getFileFormat--) | Haalt het bestandsformaat op dat is gespecificeerd in de huidige opslaan/laden-optie. |
| [getFileName()](#getFileName--) | De bestandsnaam van de exporterende/importerende scène. |
| [getFileSystem()](#getFileSystem--) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Haalt de fabrieksklasse op voor FileSystem. |
| [getLookupPaths()](#getLookupPaths--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [getMaterialConverter()](#getMaterialConverter--) | Aangepaste converter om het materiaal van de geometrie om te zetten naar PBR‑materiaal. Als dit niet is toegewezen, zal de USD‑exporter het standaardmateriaal automatisch omzetten naar PBR‑materiaal. |
| [getPrimitiveToMesh()](#getPrimitiveToMesh--) | Converteer de primitieve entiteiten naar een mesh tijdens het exporteren. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Stelt de standaardcodering in voor tekstgebaseerde bestanden. |
| [setExportMetaData(boolean value)](#setExportMetaData-boolean-) | Exporteer de eigenschappen van het knooppunt via het customData‑veld van USD. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [setFileName(String value)](#setFileName-java.lang.String-) | De bestandsnaam van de exporterende/importerende scène. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Stelt de fabrieksklasse in voor FileSystem. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Aangepaste converter om het materiaal van de geometrie om te zetten naar PBR‑materiaal. Als dit niet is toegewezen, zal de USD‑exporter het standaardmateriaal automatisch omzetten naar PBR‑materiaal. |
| [setPrimitiveToMesh(boolean value)](#setPrimitiveToMesh-boolean-) | Converteer de primitieve entiteiten naar een mesh tijdens het exporteren. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### UsdSaveOptions() {#UsdSaveOptions--}
```
public UsdSaveOptions()
```


Initialiseer een nieuwe [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) met het [FileFormat.USD](../../com.aspose.threed/fileformat\#USD) formaat

### UsdSaveOptions(FileFormat fileFormat) {#UsdSaveOptions-com.aspose.threed.FileFormat-}
```
public UsdSaveOptions(FileFormat fileFormat)
```


Initialiseer een nieuwe [UsdSaveOptions](../../com.aspose.threed/usdsaveoptions) met het opgegeven USD/USDZ‑formaat.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| fileFormat | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Haalt de standaardcodering op voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.

**Returns:**
java.nio.charset.Charset - de standaardcodering voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.
### getExportMetaData() {#getExportMetaData--}
```
public boolean getExportMetaData()
```


Exporteer de eigenschappen van het knooppunt via het customData‑veld van USD.

**Returns:**
boolean - Exporteer de eigenschappen van het knooppunt via het customData-veld van USD.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap.

**Returns:**
boolean - Probeer texturen die in de scène worden gebruikt naar de uitvoermap te kopiëren.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Haalt het bestandsformaat op dat is gespecificeerd in de huidige opslaan/laden-optie.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


De bestandsnaam van de export‑/importscene. Dit is optioneel, maar handig bij het serialiseren van externe assets zoals het materiaal van OBJ.

**Returns:**
java.lang.String - De bestandsnaam van de export‑/importscene. Dit is optioneel, maar handig bij het serialiseren van externe assets zoals het materiaal van OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

En je kunt ook je eigen implementatie gebruiken.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
```
### getFileSystemFactory() {#getFileSystemFactory--}
```
public static FileSystemFactory getFileSystemFactory()
```


Haalt de fabrieksklasse voor FileSystem op. De standaardfabriek maakt com.aspose.threed.LocalFileSystem aan, wat niet geschikt is voor een serveromgeving.

**Returns:**
[FileSystemFactory](../../com.aspose.threed/filesystemfactory) - the factory class for FileSystem. The default factory will create com.aspose.threed.LocalFileSystem which is not suitable for server environment. **Example:** The default FileSystem in SaveOptions/LoadOptions is directory-based file system, You can override the default implementation by specify it through IOConfig.FileSystemFactory:

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
```
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden.

**Returns:**
java.util.ArrayList<java.lang.String> - Sommige bestanden, zoals OBJ, zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te vinden om te laden. **Example:** De volgende code laat zien hoe je handmatig de te zoeken textures opgeeft, zodat de importeur ze kan vinden

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


Aangepaste converter om het materiaal van de geometrie te converteren naar PBR-materiaal. Als dit niet is toegewezen, zal de USD-exporteur automatisch het standaardmateriaal converteren naar PBR-materiaal. Standaardwaarde is null.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, USD exporter will automatically convert the standard material to PBR material. Default value is null
### getPrimitiveToMesh() {#getPrimitiveToMesh--}
```
public boolean getPrimitiveToMesh()
```


Converteer de primitieve entiteiten naar een mesh tijdens de export. Of codeer de primitieven direct naar het uitvoerbestand (er wordt de extensiedefinitie van Aspose gebruikt voor niet-officiële primitieven zoals Dish, Torus). Standaardwaarde is true.

**Returns:**
boolean - Converteer de primitieve entiteiten naar een mesh tijdens de export. Of codeer de primitieven direct naar het uitvoerbestand (er wordt de extensiedefinitie van Aspose gebruikt voor niet-officiële primitieven zoals Dish, Torus). Standaardwaarde is true.
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




### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Stelt de standaardcodering in voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset | Nieuwe waarde |

### setExportMetaData(boolean value) {#setExportMetaData-boolean-}
```
public void setExportMetaData(boolean value)
```


Exporteer de eigenschappen van het knooppunt via het customData‑veld van USD.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


De bestandsnaam van de export‑/importscene. Dit is optioneel, maar handig bij het serialiseren van externe assets zoals het materiaal van OBJ.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nieuwe waarde **Example:** De standaard FileSystem is LocalFileSystem, dit is niet veilig in een omgeving zoals server-side, maar je kunt de bestandsysteemtoegang overschrijven door een andere implementatie op te geven. Aspose.3D biedt verschillende FileSystem-implementaties, zoals: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

En je kunt ook je eigen implementatie gebruiken.

```
Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             var opt = new ObjSaveOptions();
             var memFs = new HashMap<string, MemoryStream>();
             opt.setFileSystem(FileSystem.createMemoryFileSystem(memFs));
 			opt.setFileName("output.obj");
             try(var output = new ByteArrayOutputStream()) {
 				scene.save(output, opt);
 				//The material will be written to variable memFs named output.mtl
 				var materialInBytes = memFs["output.mtl"].toArray();
             }
``` |

### setFileSystemFactory(FileSystemFactory value) {#setFileSystemFactory-com.aspose.threed.FileSystemFactory-}
```
public static void setFileSystemFactory(FileSystemFactory value)
```


Stelt de fabrieksklasse voor FileSystem in. De standaardfabriek maakt com.aspose.threed.LocalFileSystem aan, wat niet geschikt is voor een serveromgeving.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nieuwe waarde **Example:** Het standaard FileSystem in SaveOptions/LoadOptions is een mapgebaseerd bestandssysteem. Je kunt de standaardimplementatie overschrijven door deze op te geven via IOConfig.FileSystemFactory: |

```
IOConfig.setFileSystemFactory(new FileSystemFactory() {
 				@Override
 				public FileSystem call() {
 					return FileSystem.createDummyFileSystem();
 				}
 			});
 
             Scene scene = new Scene();
             var material = new PhongMaterial();
             var boxNode = scene.getRootNode().createChildNode(new Box());
             boxNode.setMaterial(material);
 
             //opt.FileSystem would be dummy file system now
             var opt = new ObjSaveOptions();
             scene.Save("output.obj", opt);
             //the material file output.mtl will not be written to any places because we've configured a dummy file system as default implementation.
``` |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.ArrayList<java.lang.String> | Nieuwe waarde **Example:** De volgende code laat zien hoe je handmatig de te zoeken textures opgeeft, zodat de importeur ze kan vinden |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


Aangepaste converter om het materiaal van de geometrie te converteren naar PBR-materiaal. Als dit niet is toegewezen, zal de USD-exporteur automatisch het standaardmateriaal converteren naar PBR-materiaal. Standaardwaarde is null.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nieuwe waarde |

### setPrimitiveToMesh(boolean value) {#setPrimitiveToMesh-boolean-}
```
public void setPrimitiveToMesh(boolean value)
```


Converteer de primitieve entiteiten naar een mesh tijdens de export. Of codeer de primitieven direct naar het uitvoerbestand (er wordt de extensiedefinitie van Aspose gebruikt voor niet-officiële primitieven zoals Dish, Torus). Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

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

