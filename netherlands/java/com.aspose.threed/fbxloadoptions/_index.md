---
title: FbxLoadOptions
second_title: Aspose.3D for Java API-referentie
description: Laadopties voor het Fbx-formaat.
type: docs
weight: 62
url: /nl/java/com.aspose.threed/fbxloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class FbxLoadOptions extends LoadOptions
```

Laadopties voor het Fbx-formaat.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [FbxLoadOptions(FileFormat format)](#FbxLoadOptions-com.aspose.threed.FileFormat-) | Constructor van [FbxLoadOptions](../../com.aspose.threed/fbxloadoptions) |
| [FbxLoadOptions()](#FbxLoadOptions--) | Constructor van [FbxLoadOptions](../../com.aspose.threed/fbxloadoptions) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getCompatibleMode()](#getCompatibleMode--) | Geeft aan of compatibele modus moet worden ingeschakeld. |
| [getEncoding()](#getEncoding--) | Haalt de standaardcodering op voor tekstgebaseerde bestanden. |
| [getFileFormat()](#getFileFormat--) | Haalt het bestandsformaat op dat is gespecificeerd in de huidige opslaan/laden-optie. |
| [getFileName()](#getFileName--) | De bestandsnaam van de exporterende/importerende scène. |
| [getFileSystem()](#getFileSystem--) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Haalt de fabrieksklasse op voor FileSystem. |
| [getKeepBuiltinGlobalSettings()](#getKeepBuiltinGlobalSettings--) | Geeft aan of de ingebouwde eigenschappen in GlobalSettings die een native eigenschapsvervanging hebben in [AssetInfo](../../com.aspose.threed/assetinfo) moeten worden behouden. |
| [getLookupPaths()](#getLookupPaths--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setCompatibleMode(boolean value)](#setCompatibleMode-boolean-) | Stelt in of compatibele modus moet worden ingeschakeld. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Stelt de standaardcodering in voor tekstgebaseerde bestanden. |
| [setFileName(String value)](#setFileName-java.lang.String-) | De bestandsnaam van de exporterende/importerende scène. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Stelt de fabrieksklasse in voor FileSystem. |
| [setKeepBuiltinGlobalSettings(boolean value)](#setKeepBuiltinGlobalSettings-boolean-) | Stelt in of de ingebouwde eigenschappen in GlobalSettings die een native eigenschapsvervanging hebben in [AssetInfo](../../com.aspose.threed/assetinfo) moeten worden behouden. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FbxLoadOptions(FileFormat format) {#FbxLoadOptions-com.aspose.threed.FileFormat-}
```
public FbxLoadOptions(FileFormat format)
```


Constructor van [FbxLoadOptions](../../com.aspose.threed/fbxloadoptions)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) | Instantie van [getFileFormat](../../com.aspose.threed/fbxloadoptions\#getFileFormat), dit moet een geldig FBX-formaat zijn. |

### FbxLoadOptions() {#FbxLoadOptions--}
```
public FbxLoadOptions()
```


Constructor van [FbxLoadOptions](../../com.aspose.threed/fbxloadoptions)

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
### getCompatibleMode() {#getCompatibleMode--}
```
public boolean getCompatibleMode()
```


Geeft aan of compatibele modus moet worden ingeschakeld. Compatibele modus probeert niet-standaard FBX-definities te ondersteunen, zoals PBR-materialen geëxporteerd door Blender. Standaardwaarde is false.

**Returns:**
boolean - of compatibele modus moet worden ingeschakeld. Compatibele modus probeert niet-standaard FBX-definities te ondersteunen, zoals PBR-materialen geëxporteerd door Blender. Standaardwaarde is false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Haalt de standaardcodering op voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.

**Returns:**
java.nio.charset.Charset - de standaardcodering voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.
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
### getKeepBuiltinGlobalSettings() {#getKeepBuiltinGlobalSettings--}
```
public boolean getKeepBuiltinGlobalSettings()
```


Geeft aan of de ingebouwde eigenschappen in GlobalSettings die een native eigenschapsvervanging hebben in [AssetInfo](../../com.aspose.threed/assetinfo) moeten worden behouden. Stel dit in op true als je de volledige eigenschappen in GlobalSettings wilt. Standaardwaarde is false

**Returns:**
boolean - of de ingebouwde eigenschappen in GlobalSettings die een native eigenschapsvervanging hebben in [AssetInfo](../../com.aspose.threed/assetinfo) moeten worden behouden. Stel dit in op true als je de volledige eigenschappen in GlobalSettings wilt. Standaardwaarde is false
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




### setCompatibleMode(boolean value) {#setCompatibleMode-boolean-}
```
public void setCompatibleMode(boolean value)
```


Stelt in of compatibele modus moet worden ingeschakeld. Compatibele modus probeert niet-standaard FBX-definities te ondersteunen, zoals PBR-materialen geëxporteerd door Blender. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Stelt de standaardcodering in voor tekstgebaseerde bestanden. Standaardwaarde is null, wat betekent dat de importeur/exporteur beslist welke codering te gebruiken.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.nio.charset.Charset | Nieuwe waarde |

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

### setKeepBuiltinGlobalSettings(boolean value) {#setKeepBuiltinGlobalSettings-boolean-}
```
public void setKeepBuiltinGlobalSettings(boolean value)
```


Stelt in of de ingebouwde eigenschappen in GlobalSettings die een native eigenschapsvervanging hebben in [AssetInfo](../../com.aspose.threed/assetinfo) moeten worden behouden. Stel dit in op true als je de volledige eigenschappen in GlobalSettings wilt. Standaardwaarde is false

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

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

