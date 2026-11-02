---
title: "Html5SaveOptions"
second_title: "Aspose.3D voor Java API-referentie"
description: "Opslagopties voor HTML5"
type: docs
weight: 80
url: /nl/java/com.aspose.threed/html5saveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class Html5SaveOptions extends SaveOptions
```

Opslagopties voor HTML5
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Html5SaveOptions()](#Html5SaveOptions--) | Constructor van [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) met alle standaardinstellingen. |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getCameraPosition()](#getCameraPosition--) | Haalt de initiële positie van de camera op, standaardwaarde is (10, 10, 10) |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Haalt de standaardcodering op voor tekstgebaseerde bestanden. |
| [getExportTextures()](#getExportTextures--) | Probeer texturen die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [getFarPlane()](#getFarPlane--) | Haalt het verre vlak van de camera op, standaardwaarde is 1000. |
| [getFieldOfView()](#getFieldOfView--) | Haalt het gezichtsveld op, standaardwaarde is 45, gemeten in graden. |
| [getFileFormat()](#getFileFormat--) | Haalt het bestandsformaat op dat is gespecificeerd in de huidige Opslaan/Laden-optie. |
| [getFileName()](#getFileName--) | De bestandsnaam van de exporterende/importerende scène. |
| [getFileSystem()](#getFileSystem--) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Haalt de fabriekklasse op voor FileSystem. |
| [getLookAt()](#getLookAt--) | Haalt de standaard kijkpositie op, standaardwaarde is (0, 0, 0) |
| [getLookupPaths()](#getLookupPaths--) | Sommige bestanden zoals OBJ zijn afhankelijk van een extern bestand; de zoekpaden stellen Aspose.3D in staat om naar het externe bestand te zoeken om te laden. |
| [getNearPlane()](#getNearPlane--) | Haalt het nabije vlak van de camera op, standaardwaarde is 1 |
| [getOrientationBox()](#getOrientationBox--) | Toon een oriëntatievak. |
| [getShowGrid()](#getShowGrid--) | Toon een raster in de scène. |
| [getShowRulers()](#getShowRulers--) | Toon linialen van de x/y/z-assen in de scène om het model te meten. |
| [getShowUI()](#getShowUI--) | Toon een eenvoudige UI in de scène. |
| [getUpVector()](#getUpVector--) | Haalt de up-vector op, waarde kan "x"/"y"/"z" zijn, standaardwaarde is "y" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCameraPosition(Vector3 value)](#setCameraPosition-com.aspose.threed.Vector3-) | Stelt de initiële positie van de camera in, standaardwaarde is (10, 10, 10) |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Stelt de standaardcodering in voor tekstgebaseerde bestanden. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Probeer texturen die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [setFarPlane(double value)](#setFarPlane-double-) | Stelt het verafgelegen vlak van de camera in, standaardwaarde is 1000. |
| [setFieldOfView(double value)](#setFieldOfView-double-) | Stelt het gezichtsveld in, standaardwaarde is 45, gemeten in graden. |
| [setFileName(String value)](#setFileName-java.lang.String-) | De bestandsnaam van de exporterende/importerende scène. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Stelt de fabriekklasse in voor FileSystem. |
| [setLookAt(Vector3 value)](#setLookAt-com.aspose.threed.Vector3-) | Stelt de standaard kijkpositie in, standaardwaarde is (0, 0, 0) |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Sommige bestanden zoals OBJ zijn afhankelijk van een extern bestand; de zoekpaden stellen Aspose.3D in staat om naar het externe bestand te zoeken om te laden. |
| [setNearPlane(double value)](#setNearPlane-double-) | Stelt het nabije vlak van de camera in, standaardwaarde is 1 |
| [setOrientationBox(boolean value)](#setOrientationBox-boolean-) | Toon een oriëntatievak. |
| [setShowGrid(boolean value)](#setShowGrid-boolean-) | Toon een raster in de scène. |
| [setShowRulers(boolean value)](#setShowRulers-boolean-) | Toon linialen van de x/y/z-assen in de scène om het model te meten. |
| [setShowUI(boolean value)](#setShowUI-boolean-) | Toon een eenvoudige UI in de scène. |
| [setUpVector(String value)](#setUpVector-java.lang.String-) | Stelt de up-vector in, waarde kan "x"/"y"/"z" zijn, standaardwaarde is "y" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Html5SaveOptions() {#Html5SaveOptions--}
```
public Html5SaveOptions()
```


Constructor van [Html5SaveOptions](../../com.aspose.threed/html5saveoptions) met alle standaardinstellingen.

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
### getCameraPosition() {#getCameraPosition--}
```
public Vector3 getCameraPosition()
```


Haalt de initiële positie van de camera op, standaardwaarde is (10, 10, 10)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the initial position of the camera, default value is (10, 10, 10)
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
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Probeer texturen die in de scène worden gebruikt te kopiëren naar de uitvoermap.

**Returns:**
boolean - Probeer texturen die in de scène worden gebruikt naar de uitvoermap te kopiëren.
### getFarPlane() {#getFarPlane--}
```
public double getFarPlane()
```


Haalt het verre vlak van de camera op, standaardwaarde is 1000.

**Returns:**
double - het verafgelegen vlak van de camera, standaardwaarde is 1000.
### getFieldOfView() {#getFieldOfView--}
```
public double getFieldOfView()
```


Haalt het gezichtsveld op, standaardwaarde is 45, gemeten in graden.

**Returns:**
double - het gezichtsveld, standaardwaarde is 45, gemeten in graden.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Haalt het bestandsformaat op dat is gespecificeerd in de huidige Opslaan/Laden-optie.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


De bestandsnaam van de exporteer-/importeer‑scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ.

**Returns:**
java.lang.String - De bestandsnaam van de exporteer-/importeer‑scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ.
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


Haalt de fabrieksklasse op voor FileSystem. De standaardfabriek maakt com.aspose.threed.LocalFileSystem aan, wat niet geschikt is voor een serveromgeving.

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
### getLookAt() {#getLookAt--}
```
public Vector3 getLookAt()
```


Haalt de standaard kijkpositie op, standaardwaarde is (0, 0, 0)

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - the default look at position, default value is (0, 0, 0)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Sommige bestanden zoals OBJ zijn afhankelijk van een extern bestand; de zoekpaden stellen Aspose.3D in staat om naar het externe bestand te zoeken om te laden.

**Returns:**
java.util.ArrayList<java.lang.String> - Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. **Example:** De volgende code toont hoe je handmatig de opzoektexturen specificeert, zodat de importeur ze kan vinden

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getNearPlane() {#getNearPlane--}
```
public double getNearPlane()
```


Haalt het nabije vlak van de camera op, standaardwaarde is 1

**Returns:**
double - het nabije vlak van de camera, standaardwaarde is 1
### getOrientationBox() {#getOrientationBox--}
```
public boolean getOrientationBox()
```


Geef een oriëntatievak weer. Standaardwaarde is true.

**Returns:**
boolean - Geef een oriëntatievak weer. Standaardwaarde is true.
### getShowGrid() {#getShowGrid--}
```
public boolean getShowGrid()
```


Geef een raster in de scène weer. Standaardwaarde is true.

**Returns:**
boolean - Geef een raster in de scène weer. Standaardwaarde is true.
### getShowRulers() {#getShowRulers--}
```
public boolean getShowRulers()
```


Geef linialen van de x/y/z-assen in de scène weer om het model te meten. Standaardwaarde is false.

**Returns:**
boolean - Geef linialen van de x/y/z-assen in de scène weer om het model te meten. Standaardwaarde is false.
### getShowUI() {#getShowUI--}
```
public boolean getShowUI()
```


Geef een eenvoudige UI in de scène weer. Standaardwaarde is true.

**Returns:**
boolean - Geef een eenvoudige UI in de scène weer. Standaardwaarde is true.
### getUpVector() {#getUpVector--}
```
public String getUpVector()
```


Haalt de up-vector op, waarde kan "x"/"y"/"z" zijn, standaardwaarde is "y"

**Returns:**
java.lang.String - de up-vector, waarde kan "x"/"y"/"z" zijn, standaardwaarde is "y"
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




### setCameraPosition(Vector3 value) {#setCameraPosition-com.aspose.threed.Vector3-}
```
public void setCameraPosition(Vector3 value)
```


Stelt de initiële positie van de camera in, standaardwaarde is (10, 10, 10)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Stelt de standaardcodering in voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset | Nieuwe waarde |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Probeer texturen die in de scène worden gebruikt te kopiëren naar de uitvoermap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setFarPlane(double value) {#setFarPlane-double-}
```
public void setFarPlane(double value)
```


Stelt het verafgelegen vlak van de camera in, standaardwaarde is 1000.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setFieldOfView(double value) {#setFieldOfView-double-}
```
public void setFieldOfView(double value)
```


Stelt het gezichtsveld in, standaardwaarde is 45, gemeten in graden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


De bestandsnaam van de exporteer-/importeer‑scène. Dit is optioneel, maar nuttig bij het serialiseren van externe assets zoals het materiaal van OBJ.

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
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nieuwe waarde **Example:** Het standaard FileSystem is LocalFileSystem, dit is niet veilig in een omgeving zoals server-side, maar je kunt de bestandsysteemtoegang overschrijven door een andere implementatie op te geven. Aspose.3D biedt verschillende FileSystem-implementaties, zoals: |

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


Stelt de fabrieksklasse in voor FileSystem. De standaardfabriek maakt com.aspose.threed.LocalFileSystem aan, wat niet geschikt is voor een serveromgeving.

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

### setLookAt(Vector3 value) {#setLookAt-com.aspose.threed.Vector3-}
```
public void setLookAt(Vector3 value)
```


Stelt de standaard kijkpositie in, standaardwaarde is (0, 0, 0)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Sommige bestanden zoals OBJ zijn afhankelijk van een extern bestand; de zoekpaden stellen Aspose.3D in staat om naar het externe bestand te zoeken om te laden.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
|  | waarde | java.util.ArrayList<java.lang.String> | Nieuwe waarde **Example:** De volgende code toont hoe je handmatig de opzoektexturen specificeert, zodat de importeur ze kan vinden |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setNearPlane(double value) {#setNearPlane-double-}
```
public void setNearPlane(double value)
```


Stelt het nabije vlak van de camera in, standaardwaarde is 1

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | double | Nieuwe waarde |

### setOrientationBox(boolean value) {#setOrientationBox-boolean-}
```
public void setOrientationBox(boolean value)
```


Geef een oriëntatievak weer. Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setShowGrid(boolean value) {#setShowGrid-boolean-}
```
public void setShowGrid(boolean value)
```


Geef een raster in de scène weer. Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setShowRulers(boolean value) {#setShowRulers-boolean-}
```
public void setShowRulers(boolean value)
```


Geef linialen van de x/y/z-assen in de scène weer om het model te meten. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setShowUI(boolean value) {#setShowUI-boolean-}
```
public void setShowUI(boolean value)
```


Geef een eenvoudige UI in de scène weer. Standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setUpVector(String value) {#setUpVector-java.lang.String-}
```
public void setUpVector(String value)
```


Stelt de up-vector in, waarde kan "x"/"y"/"z" zijn, standaardwaarde is "y"

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

