---
title: Discreet3dsLoadOptions
second_title: Aspose.3D for Java API-referentie
description: Laadopties voor 3DS-bestand.
type: docs
weight: 43
url: /nl/java/com.aspose.threed/discreet3dsloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class Discreet3dsLoadOptions extends LoadOptions
```

Laadopties voor 3DS-bestand.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [Discreet3dsLoadOptions()](#Discreet3dsLoadOptions--) | Constructor van [Discreet3dsLoadOptions](../../com.aspose.threed/discreet3dsloadoptions) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyAnimationTransform()](#getApplyAnimationTransform--) | Geeft aan of de transformatie gedefinieerd in het eerste frame van de animatietrack moet worden gebruikt. |
| [getClass()](#getClass--) |  |
| [getEncoding()](#getEncoding--) | Haalt de standaardcodering op voor tekstgebaseerde bestanden. |
| [getFileFormat()](#getFileFormat--) | Haalt het bestandsformaat op dat is gespecificeerd in de huidige opslaan/laden-optie. |
| [getFileName()](#getFileName--) | De bestandsnaam van de exporterende/importerende scène. |
| [getFileSystem()](#getFileSystem--) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Haalt de fabrieksklasse op voor FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Haalt het omkeren van het coördinatensysteem van controlepunten/normaal op tijdens importeren/exporteren. |
| [getGammaCorrectedColor()](#getGammaCorrectedColor--) | Een 3ds-bestand kan originele kleur en gamma-gecorrigeerde kleur voor hetzelfde attribuut bevatten. Als dit op true wordt gezet, wordt de gamma-gecorrigeerde kleur gebruikt indien mogelijk, anders zal Aspose.3D proberen de originele kleur te gebruiken. |
| [getLookupPaths()](#getLookupPaths--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyAnimationTransform(boolean value)](#setApplyAnimationTransform-boolean-) | Stelt in of de transformatie gedefinieerd in het eerste frame van de animatietrack moet worden gebruikt. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Stelt de standaardcodering in voor tekstgebaseerde bestanden. |
| [setFileName(String value)](#setFileName-java.lang.String-) | De bestandsnaam van de exporterende/importerende scène. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Stelt de fabrieksklasse in voor FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Stelt het omkeren van het coördinatensysteem van controlepunten/normaal in tijdens importeren/exporteren. |
| [setGammaCorrectedColor(boolean value)](#setGammaCorrectedColor-boolean-) | Een 3ds-bestand kan originele kleur en gamma-gecorrigeerde kleur voor hetzelfde attribuut bevatten. Als dit op true wordt gezet, wordt de gamma-gecorrigeerde kleur gebruikt indien mogelijk, anders zal Aspose.3D proberen de originele kleur te gebruiken. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Discreet3dsLoadOptions() {#Discreet3dsLoadOptions--}
```
public Discreet3dsLoadOptions()
```


Constructor van [Discreet3dsLoadOptions](../../com.aspose.threed/discreet3dsloadoptions)

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
### getApplyAnimationTransform() {#getApplyAnimationTransform--}
```
public boolean getApplyAnimationTransform()
```


Geeft aan of de transformatie gedefinieerd in het eerste frame van de animatietrack moet worden gebruikt.

**Returns:**
boolean - of de transformatie gedefinieerd in het eerste frame van de animatietrack moet worden gebruikt.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


Haalt het omkeren van het coördinatensysteem van controlepunten/normaal op tijdens importeren/exporteren.

**Returns:**
boolean - draai het coördinatensysteem van controlepunten/normaal om tijdens importeren/exporteren.
### getGammaCorrectedColor() {#getGammaCorrectedColor--}
```
public boolean getGammaCorrectedColor()
```


Een 3ds-bestand kan originele kleur en gamma-gecorrigeerde kleur voor hetzelfde attribuut bevatten. Als dit op true wordt gezet, wordt de gamma-gecorrigeerde kleur gebruikt indien mogelijk, anders zal Aspose.3D proberen de originele kleur te gebruiken.

**Returns:**
boolean - Een 3ds-bestand kan originele kleur en gamma-gecorrigeerde kleur voor hetzelfde attribuut bevatten. Als dit op true wordt gezet, wordt de gamma-gecorrigeerde kleur gebruikt indien mogelijk, anders zal Aspose.3D proberen de originele kleur te gebruiken.
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




### setApplyAnimationTransform(boolean value) {#setApplyAnimationTransform-boolean-}
```
public void setApplyAnimationTransform(boolean value)
```


Stelt in of de transformatie gedefinieerd in het eerste frame van de animatietrack moet worden gebruikt.

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


Stelt het omkeren van het coördinatensysteem van controlepunten/normaal in tijdens importeren/exporteren.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setGammaCorrectedColor(boolean value) {#setGammaCorrectedColor-boolean-}
```
public void setGammaCorrectedColor(boolean value)
```


Een 3ds-bestand kan originele kleur en gamma-gecorrigeerde kleur voor hetzelfde attribuut bevatten. Als dit op true wordt gezet, wordt de gamma-gecorrigeerde kleur gebruikt indien mogelijk, anders zal Aspose.3D proberen de originele kleur te gebruiken.

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

