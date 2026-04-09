---
title: GltfSaveOptions
second_title: Aspose.3D for Java API-referentie
description: Opslagopties voor het glTF-formaat.
type: docs
weight: 74
url: /nl/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

Opslagopties voor het glTF-formaat.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Constructor van [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Constructor van [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Pas [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) toe op de mesh. |
| [getBufferFile()](#getBufferFile--) | De bestandsnaam van het externe bufferbestand dat wordt gebruikt om binaire gegevens op te slaan. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Geeft of draco-compressie ingeschakeld moet worden. |
| [getEmbedAssets()](#getEmbedAssets--) | Alle externe assets als base64 in één bestand insluiten in ASCII-modus, standaardwaarde is false. |
| [getEncoding()](#getEncoding--) | Haalt de standaardcodering op voor tekstgebaseerde bestanden. |
| [getExportTextures()](#getExportTextures--) | Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Gebruik een externe draco-encoder om de compressiesnelheid van draco te versnellen. |
| [getFallbackNormal()](#getFallbackNormal--) | Wanneer de GLTF2-exporteur een ongeldige normaal heeft gedetecteerd, wordt dit gebruikt in plaats van de oorspronkelijke waarde om de validatie te omzeilen. |
| [getFileFormat()](#getFileFormat--) | Haalt het bestandsformaat op dat is gespecificeerd in de huidige opslaan/laden-optie. |
| [getFileName()](#getFileName--) | De bestandsnaam van de exporterende/importerende scène. |
| [getFileSystem()](#getFileSystem--) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Haalt de fabrieksklasse op voor FileSystem. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Draai de textuurcoördinaat v(t)-component om, standaardwaarde is true. |
| [getImageFormat()](#getImageFormat--) | Standaard glTF ondersteunt alleen PNG/JPG als textuurformaat; deze optie geeft aan hoe Aspose.3D niet‑standaard afbeeldingen converteert naar een ondersteund formaat tijdens het exporteren. |
| [getLookupPaths()](#getLookupPaths--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [getMaterialConverter()](#getMaterialConverter--) | Aangepaste converter om het materiaal van de geometrie te converteren naar PBR‑materiaal. Als dit niet is toegewezen, zal de glTF 2.0‑exporteur automatisch het standaardmateriaal converteren naar PBR‑materiaal. |
| [getPrettyPrint()](#getPrettyPrint--) | De JSON‑inhoud van het GLTF‑bestand is ingesprongen voor menselijke leesbaarheid, standaardwaarde is false. |
| [getSaveExtras()](#getSaveExtras--) | Sla de dynamische eigenschappen van het scène‑object op in 'extra'-velden in het gegenereerde glTF‑bestand. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Serialiseer materialen met behulp van KHR‑gemeenschappelijke materiaalextensies, standaardwaarde is false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Pas [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) toe op de mesh. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | De bestandsnaam van het externe bufferbestand dat wordt gebruikt om binaire gegevens op te slaan. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Stelt in of draco‑compressie moet worden ingeschakeld. |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Alle externe assets als base64 in één bestand insluiten in ASCII-modus, standaardwaarde is false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Stelt de standaardcodering in voor tekstgebaseerde bestanden. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Gebruik een externe draco-encoder om de compressiesnelheid van draco te versnellen. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | Wanneer de GLTF2-exporteur een ongeldige normaal heeft gedetecteerd, wordt dit gebruikt in plaats van de oorspronkelijke waarde om de validatie te omzeilen. |
| [setFileName(String value)](#setFileName-java.lang.String-) | De bestandsnaam van de exporterende/importerende scène. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Sta de gebruiker toe om te bepalen hoe de externe afhankelijkheden tijdens laden/opslaan worden beheerd. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Stelt de fabrieksklasse in voor FileSystem. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Draai de textuurcoördinaat v(t)-component om, standaardwaarde is true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Standaard glTF ondersteunt alleen PNG/JPG als textuurformaat; deze optie geeft aan hoe Aspose.3D niet‑standaard afbeeldingen converteert naar een ondersteund formaat tijdens het exporteren. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Sommige bestanden zoals OBJ zijn afhankelijk van externe bestanden; de zoekpaden stellen Aspose.3D in staat om externe bestanden te zoeken om te laden. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Aangepaste converter om het materiaal van de geometrie te converteren naar PBR‑materiaal. Als dit niet is toegewezen, zal de glTF 2.0‑exporteur automatisch het standaardmateriaal converteren naar PBR‑materiaal. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | De JSON‑inhoud van het GLTF‑bestand is ingesprongen voor menselijke leesbaarheid, standaardwaarde is false. |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Sla de dynamische eigenschappen van het scène‑object op in 'extra'-velden in het gegenereerde glTF‑bestand. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Serialiseer materialen met behulp van KHR‑gemeenschappelijke materiaalextensies, standaardwaarde is false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Constructor van [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Constructor van [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Pas [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) toe op de mesh. Standaardwaarde is false.

**Returns:**
boolean - Pas [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) toe op de mesh. Standaardwaarde is false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


De bestandsnaam van het externe bufferbestand dat wordt gebruikt om binaire gegevens op te slaan. Als dit bestand niet is opgegeven, genereert Aspose.3D een naam voor u. Dit wordt genegeerd bij het exporteren van glTF in binaire modus.

**Returns:**
java.lang.String - De bestandsnaam van het externe bufferbestand dat wordt gebruikt om binaire gegevens op te slaan. Als dit bestand niet is opgegeven, genereert Aspose.3D een naam voor u. Dit wordt genegeerd bij het exporteren van glTF in binaire modus.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDracoCompression() {#getDracoCompression--}
```
public boolean getDracoCompression()
```


Geeft of draco-compressie ingeschakeld moet worden.

**Returns:**
boolean - of draco‑compressie moet worden ingeschakeld
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Alle externe assets als base64 in één bestand insluiten in ASCII-modus, standaardwaarde is false.

**Returns:**
boolean - Alle externe assets als base64 in één bestand embedden in ASCII‑modus, standaardwaarde is false.
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


Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap.

**Returns:**
boolean - Probeer texturen die in de scène worden gebruikt naar de uitvoermap te kopiëren.
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Gebruik een externe draco-encoder om de compressiesnelheid van draco te versnellen.

**Returns:**
java.lang.String - Gebruik een externe draco‑encoder om de draco‑compressiesnelheid te versnellen. **Remarks:** Aspose.3D zal een nieuw subprocess maken om het mesh te coderen naar het draco‑formaat, gebruik op eigen risico.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


Wanneer de GLTF2‑exporteur een ongeldige normaal detecteert, wordt dit gebruikt in plaats van de oorspronkelijke waarde om de validatie te omzeilen. Standaardwaarde is (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
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
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


Draai de textuurcoördinaat v(t)-component om, standaardwaarde is true.

**Returns:**
boolean - Draai de textuurcoördinaat v(t)-component om, standaardwaarde is true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Standaard glTF ondersteunt alleen PNG/JPG als textuurformaat; deze optie geeft aan hoe Aspose.3D niet‑standaard afbeeldingen converteert naar een ondersteund formaat tijdens het exporteren. Standaardwaarde is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
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


Aangepaste converter om het materiaal van de geometrie te converteren naar PBR‑materiaal. Als dit niet is toegewezen, zal de glTF 2.0‑exporteur automatisch het standaardmateriaal converteren naar PBR‑materiaal. Standaardwaarde is null. Deze eigenschap wordt gebruikt bij het exporteren van een scène naar een glTF 2.0‑bestand.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


De JSON‑inhoud van het GLTF‑bestand is ingesprongen voor menselijke leesbaarheid, standaardwaarde is false.

**Returns:**
boolean - De JSON‑inhoud van het GLTF‑bestand is ingesprongen voor menselijke leesbaarheid, standaardwaarde is false
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Sla de dynamische eigenschappen van het scène‑object op in 'extra'-velden in het gegenereerde glTF‑bestand. Dit is nuttig om toepassingsspecifieke gegevens te leveren. Standaardwaarde is false.

**Returns:**
boolean - Sla de dynamische eigenschappen van het scène‑object op in 'extra'-velden in het gegenereerde glTF‑bestand. Dit is nuttig om toepassingsspecifieke gegevens te leveren. Standaardwaarde is false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Serialiseer materialen met behulp van KHR‑gemeenschappelijke materiaalextensies, standaardwaarde is false. Als dit op false wordt gezet, zal Aspose.3D een set vertex-/fragment‑shaders exporteren als [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
boolean - Serialiseer materialen met behulp van KHR‑gemeenschappelijke materiaalextensies, standaardwaarde is false. Als dit op false wordt gezet, zal Aspose.3D een set vertex-/fragment‑shaders exporteren als [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** Deze eigenschap werkt alleen voor glTF 1.0
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




### setApplyUnitScale(boolean value) {#setApplyUnitScale-boolean-}
```
public void setApplyUnitScale(boolean value)
```


Pas [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) toe op de mesh. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


De bestandsnaam van het externe bufferbestand dat wordt gebruikt om binaire gegevens op te slaan. Als dit bestand niet is opgegeven, genereert Aspose.3D een naam voor u. Dit wordt genegeerd bij het exporteren van glTF in binaire modus.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Stelt in of draco‑compressie moet worden ingeschakeld.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Alle externe assets als base64 in één bestand insluiten in ASCII-modus, standaardwaarde is false.

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

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Probeer textures die in de scène worden gebruikt te kopiëren naar de uitvoermap.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Gebruik een externe draco-encoder om de compressiesnelheid van draco te versnellen.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | java.lang.String | Nieuwe waarde **Remarks:** Aspose.3D zal een nieuw subprocess maken om het mesh te coderen naar het draco‑formaat, gebruik op eigen risico. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


Wanneer de GLTF2‑exporteur een ongeldige normaal detecteert, wordt dit gebruikt in plaats van de oorspronkelijke waarde om de validatie te omzeilen. Standaardwaarde is (0, 1, 0).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nieuwe waarde |

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

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


Draai de textuurcoördinaat v(t)-component om, standaardwaarde is true.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Standaard glTF ondersteunt alleen PNG/JPG als textuurformaat; deze optie geeft aan hoe Aspose.3D niet‑standaard afbeeldingen converteert naar een ondersteund formaat tijdens het exporteren. Standaardwaarde is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Nieuwe waarde |

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


Aangepaste converter om het materiaal van de geometrie te converteren naar PBR‑materiaal. Als dit niet is toegewezen, zal de glTF 2.0‑exporteur automatisch het standaardmateriaal converteren naar PBR‑materiaal. Standaardwaarde is null. Deze eigenschap wordt gebruikt bij het exporteren van een scène naar een glTF 2.0‑bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nieuwe waarde |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


De JSON‑inhoud van het GLTF‑bestand is ingesprongen voor menselijke leesbaarheid, standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Sla de dynamische eigenschappen van het scène‑object op in 'extra'-velden in het gegenereerde glTF‑bestand. Dit is nuttig om toepassingsspecifieke gegevens te leveren. Standaardwaarde is false.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Serialiseer materialen met behulp van KHR‑gemeenschappelijke materiaalextensies, standaardwaarde is false. Als dit op false wordt gezet, zal Aspose.3D een set vertex-/fragment‑shaders exporteren als [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| waarde | boolean | Nieuwe waarde **Remarks:** Deze eigenschap werkt alleen voor glTF 1.0 |

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

