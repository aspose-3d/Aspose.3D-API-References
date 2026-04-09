---
title: PlySaveOptions
second_title: Aspose.3D for Java API-referens
description: Sparaalternativ för att exportera scenen som en PLY-fil.
type: docs
weight: 131
url: /sv/java/com.aspose.threed/plysaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class PlySaveOptions extends SaveOptions
```

Sparaalternativ för att exportera scenen som en PLY-fil.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [PlySaveOptions()](#PlySaveOptions--) | Konstruktor för [PlySaveOptions](../../com.aspose.threed/plysaveoptions) |
| [PlySaveOptions(FileContentType contentType)](#PlySaveOptions-com.aspose.threed.FileContentType-) | Konstruktor för [PlySaveOptions](../../com.aspose.threed/plysaveoptions) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAxisSystem()](#getAxisSystem--) | Hämtar axelsystemet i den exporterade stl‑filen. |
| [getClass()](#getClass--) |  |
| [getColorComponents()](#getColorComponents--) | Komponentnamnen för vertex‑färg, standardvärdet är ("red", "green", "blue") |
| [getEncoding()](#getEncoding--) | Hämtar standardkodningen för textbaserade filer. |
| [getExportTextures()](#getExportTextures--) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [getFaceElement()](#getFaceElement--) | Elementnamnet för ansiktsdata, standardvärdet är "face" |
| [getFaceProperty()](#getFaceProperty--) | Egenskapsnamnet för ansiktsdata, standardvärdet är "vertex\_index" |
| [getFileFormat()](#getFileFormat--) | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |
| [getFileName()](#getFileName--) | Filnamnet för den exporterande/importerande scenen. |
| [getFileSystem()](#getFileSystem--) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Hämtar fabriksklassen för FileSystem. |
| [getFlipCoordinate()](#getFlipCoordinate--) | Vänd koordinaten när scenen sparas, standardvärdet är true |
| [getLookupPaths()](#getLookupPaths--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [getNormalComponents()](#getNormalComponents--) | Komponentnamnen för normaldata, standardvärdet är ("nx", "ny", "nz") |
| [getPointCloud()](#getPointCloud--) | Exportera scenen som punktmoln, standardvärdet är false. |
| [getPositionComponents()](#getPositionComponents--) | Komponentnamnen för positionsdata, standardvärdet är ("x", "y", "z") |
| [getTextureCoordinateComponents()](#getTextureCoordinateComponents--) | Komponentnamnen för texturkoordinatdata, standardvärdet är ("u", "v") |
| [getVertexElement()](#getVertexElement--) | Elementnamnet för vertexdata, standardvärdet är "vertex" |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Ställer in axelsystemet i den exporterade stl-filen. |
| [setColorComponents(Tuple_3<String,String,String> value)](#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Komponentnamnen för vertex‑färg, standardvärdet är ("red", "green", "blue") |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ställer in standardkodningen för textbaserade filer. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [setFaceElement(String value)](#setFaceElement-java.lang.String-) | Elementnamnet för ansiktsdata, standardvärdet är "face" |
| [setFaceProperty(String value)](#setFaceProperty-java.lang.String-) | Egenskapsnamnet för ansiktsdata, standardvärdet är "vertex\_index" |
| [setFileName(String value)](#setFileName-java.lang.String-) | Filnamnet för den exporterande/importerande scenen. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ställer in fabriksklassen för FileSystem. |
| [setFlipCoordinate(boolean value)](#setFlipCoordinate-boolean-) | Vänd koordinaten när scenen sparas, standardvärdet är true |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [setNormalComponents(Tuple_3<String,String,String> value)](#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Komponentnamnen för normaldata, standardvärdet är ("nx", "ny", "nz") |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | Exportera scenen som punktmoln, standardvärdet är false. |
| [setPositionComponents(Tuple_3<String,String,String> value)](#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--) | Komponentnamnen för positionsdata, standardvärdet är ("x", "y", "z") |
| [setTextureCoordinateComponents(Tuple_2<String,String> value)](#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--) | Komponentnamnen för texturkoordinatdata, standardvärdet är ("u", "v") |
| [setVertexElement(String value)](#setVertexElement-java.lang.String-) | Elementnamnet för vertexdata, standardvärdet är "vertex" |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### PlySaveOptions() {#PlySaveOptions--}
```
public PlySaveOptions()
```


Konstruktor för [PlySaveOptions](../../com.aspose.threed/plysaveoptions)

### PlySaveOptions(FileContentType contentType) {#PlySaveOptions-com.aspose.threed.FileContentType-}
```
public PlySaveOptions(FileContentType contentType)
```


Konstruktor för [PlySaveOptions](../../com.aspose.threed/plysaveoptions)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

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
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Hämtar axelsystemet i den exporterade stl‑filen.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported stl file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getColorComponents() {#getColorComponents--}
```
public Tuple_3<String,String,String> getColorComponents()
```


Komponentnamnen för vertex‑färg, standardvärdet är ("red", "green", "blue")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Komponentnamnen för vertexfärg, standardvärdet är ("red", "green", "blue")
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Hämtar standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.

**Returns:**
java.nio.charset.Charset - standardkodningen för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Försök att kopiera texturer som används i scenen till utmatningskatalogen.

**Returns:**
boolean - Försök att kopiera texturer som används i scenen till utdata katalogen.
### getFaceElement() {#getFaceElement--}
```
public String getFaceElement()
```


Elementnamnet för ansiktsdata, standardvärdet är "face"

**Returns:**
java.lang.String - Elementnamnet för ansiktsdata, standardvärdet är "face"
### getFaceProperty() {#getFaceProperty--}
```
public String getFaceProperty()
```


Egenskapsnamnet för ansiktsdata, standardvärdet är "vertex\_index"

**Returns:**
java.lang.String - Egenskapsnamnet för ansiktsdata, standardvärdet är "vertex\_index"
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa resurser som OBJ:s material.

**Returns:**
java.lang.String - Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa resurser som OBJ:s material.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Och du kan också använda din egen implementation.

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


Hämtar fabriks‑klassen för FileSystem. Standardfabriken kommer att skapa com.aspose.threed.LocalFileSystem som inte är lämplig för servermiljö.

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
### getFlipCoordinate() {#getFlipCoordinate--}
```
public boolean getFlipCoordinate()
```


Vänd koordinaten när scenen sparas, standardvärdet är true

**Returns:**
boolean - Vänd koordinaten när scenen sparas, standardvärdet är true
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda.

**Returns:**
java.util.ArrayList<java.lang.String> - Vissa filer som OBJ beror på externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. **Example:** Följande kod visar hur man manuellt specificerar uppslagnings‑texturer, så att importören kan hitta

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
```
### getNormalComponents() {#getNormalComponents--}
```
public Tuple_3<String,String,String> getNormalComponents()
```


Komponentnamnen för normaldata, standardvärdet är ("nx", "ny", "nz")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Komponentnamnen för normaldata, standardvärdet är ("nx", "ny", "nz")
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


Exportera scenen som punktmoln, standardvärdet är false.

**Returns:**
boolean - Exportera scenen som punktmoln, standardvärdet är false.
### getPositionComponents() {#getPositionComponents--}
```
public Tuple_3<String,String,String> getPositionComponents()
```


Komponentnamnen för positionsdata, standardvärdet är ("x", "y", "z")

**Returns:**
com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> - Komponentnamnen för positionsdata, standardvärdet är ("x", "y", "z")
### getTextureCoordinateComponents() {#getTextureCoordinateComponents--}
```
public Tuple_2<String,String> getTextureCoordinateComponents()
```


Komponentnamnen för texturkoordinatdata, standardvärdet är ("u", "v")

**Returns:**
com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> - Komponentnamnen för texturkoordinatdata, standardvärdet är ("u", "v")
### getVertexElement() {#getVertexElement--}
```
public String getVertexElement()
```


Elementnamnet för vertexdata, standardvärdet är "vertex"

**Returns:**
java.lang.String - Elementnamnet för vertexdata, standardvärdet är "vertex"
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




### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Ställer in axelsystemet i den exporterade stl-filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nytt värde **Anmärkningar:** FlipCoordinateSystem måste vara aktiverat för att använda denna funktion. |

### setColorComponents(Tuple_3<String,String,String> value) {#setColorComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setColorComponents(Tuple_3<String,String,String> value)
```


Komponentnamnen för vertex‑färg, standardvärdet är ("red", "green", "blue")

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nytt värde |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Ställer in standardkodning för textbaserade filer. Standardvärdet är null vilket betyder att importören/exportören bestämmer vilken kodning som ska användas.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.nio.charset.Charset | Nytt värde |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Försök att kopiera texturer som används i scenen till utmatningskatalogen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setFaceElement(String value) {#setFaceElement-java.lang.String-}
```
public void setFaceElement(String value)
```


Elementnamnet för ansiktsdata, standardvärdet är "face"

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setFaceProperty(String value) {#setFaceProperty-java.lang.String-}
```
public void setFaceProperty(String value)
```


Egenskapsnamnet för ansiktsdata, standardvärdet är "vertex\_index"

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Filnamnet för den exporterande/importerande scenen. Detta är valfritt, men användbart när man serialiserar externa resurser som OBJ:s material.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | New value **Example:** Standard‑FileSystem är LocalFileSystem, den är inte säker i miljöer som server‑sidan, men du kan åsidosätta filsystem‑åtkomsten genom att ange en annan implementation. Aspose.3D tillhandahåller olika FileSystem‑implementationer såsom: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Och du kan också använda din egen implementation.

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


Ställer in fabriks‑klassen för FileSystem. Standardfabriken kommer att skapa com.aspose.threed.LocalFileSystem som inte är lämplig för servermiljö.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | New value **Example:** Standard‑FileSystem i SaveOptions/LoadOptions är ett katalogbaserat filsystem, du kan åsidosätta standardimplementationen genom att specificera den via IOConfig.FileSystemFactory: |

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

### setFlipCoordinate(boolean value) {#setFlipCoordinate-boolean-}
```
public void setFlipCoordinate(boolean value)
```


Vänd koordinaten när scenen sparas, standardvärdet är true

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
|  | värde | java.util.ArrayList<java.lang.String> | New value **Example:** Följande kod visar hur man manuellt specificerar uppslagnings‑texturer, så att importören kan hitta |

```
var opt = new ObjLoadOptions();
             //Specify the lookup paths, so the textures can be located.
             opt.getLookupPaths().add("textures");
             var scene = Scene.fromFile("input.obj", opt);
             scene.save("output.glb");
``` |

### setNormalComponents(Tuple_3<String,String,String> value) {#setNormalComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setNormalComponents(Tuple_3<String,String,String> value)
```


Komponentnamnen för normaldata, standardvärdet är ("nx", "ny", "nz")

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nytt värde |

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


Exportera scenen som punktmoln, standardvärdet är false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setPositionComponents(Tuple_3<String,String,String> value) {#setPositionComponents-com.aspose.threed.Tuple-3-java.lang.String-java.lang.String-java.lang.String--}
```
public void setPositionComponents(Tuple_3<String,String,String> value)
```


Komponentnamnen för positionsdata, standardvärdet är ("x", "y", "z")

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.threed.Tuple_3<java.lang.String,java.lang.String,java.lang.String> | Nytt värde |

### setTextureCoordinateComponents(Tuple_2<String,String> value) {#setTextureCoordinateComponents-com.aspose.threed.Tuple-2-java.lang.String-java.lang.String--}
```
public void setTextureCoordinateComponents(Tuple_2<String,String> value)
```


Komponentnamnen för texturkoordinatdata, standardvärdet är ("u", "v")

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | com.aspose.threed.Tuple_2<java.lang.String,java.lang.String> | Nytt värde |

### setVertexElement(String value) {#setVertexElement-java.lang.String-}
```
public void setVertexElement(String value)
```


Elementnamnet för vertexdata, standardvärdet är "vertex"

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

