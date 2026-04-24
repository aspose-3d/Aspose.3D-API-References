---
title: ObjSaveOptions
second_title: Aspose.3D for Java API-referens
description: Sparaalternativ för wavefront obj-fil
type: docs
weight: 116
url: /sv/java/com.aspose.threed/objsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class ObjSaveOptions extends SaveOptions
```

Sparaalternativ för wavefront obj-fil
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [ObjSaveOptions()](#ObjSaveOptions--) | Konstruktor för [ObjSaveOptions](../../com.aspose.threed/objsaveoptions). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Tillämpa [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) på meshen. |
| [getAxisSystem()](#getAxisSystem--) | Hämtar axelsystemet i den exporterade filen. |
| [getClass()](#getClass--) |  |
| [getEnableMaterials()](#getEnableMaterials--) | Hämtar om material för import/export ska användas för varje objekt |
| [getEncoding()](#getEncoding--) | Hämtar standardkodningen för textbaserade filer. |
| [getExportTextures()](#getExportTextures--) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [getFileFormat()](#getFileFormat--) | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |
| [getFileName()](#getFileName--) | Filnamnet för den exporterande/importerande scenen. |
| [getFileSystem()](#getFileSystem--) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Hämtar fabriksklassen för FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Hämtar om koordinatsystemet för kontrollpunkter/normaler ska vändas under import/export. |
| [getLookupPaths()](#getLookupPaths--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [getPointCloud()](#getPointCloud--) | Hämtar flaggan som anger om exportören ska exportera scenen som punktmoln (utan topologisk struktur), standardvärdet är falskt. |
| [getSerializeW()](#getSerializeW--) | Hämtar om W-komponenten i modellens vertexposition ska serialiseras. |
| [getVerbose()](#getVerbose--) | Hämtar om kommentarer ska genereras för varje sektion. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Tillämpa [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) på meshen. |
| [setAxisSystem(AxisSystem value)](#setAxisSystem-com.aspose.threed.AxisSystem-) | Ställer in axelsystemet i den exporterade filen. |
| [setEnableMaterials(boolean value)](#setEnableMaterials-boolean-) | Ställer in om material för import/export ska användas för varje objekt. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ställer in standardkodningen för textbaserade filer. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Filnamnet för den exporterande/importerande scenen. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ställer in fabriksklassen för FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Ställer in om koordinatsystemet för kontrollpunkter/normaler ska vändas under import/export. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [setPointCloud(boolean value)](#setPointCloud-boolean-) | Ställer in flaggan som anger om exportören ska exportera scenen som punktmoln (utan topologisk struktur), standardvärdet är falskt. |
| [setSerializeW(boolean value)](#setSerializeW-boolean-) | Ställer in om W-komponenten ska serialiseras i modellens vertexposition. |
| [setVerbose(boolean value)](#setVerbose-boolean-) | Ställer in om kommentarer ska genereras för varje avsnitt |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ObjSaveOptions() {#ObjSaveOptions--}
```
public ObjSaveOptions()
```


Konstruktor för [ObjSaveOptions](../../com.aspose.threed/objsaveoptions).

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Tillämpa [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) på meshen. Standardvärdet är falskt.

**Returns:**
boolean - Tillämpa [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) på meshen. Standardvärdet är falskt.
### getAxisSystem() {#getAxisSystem--}
```
public AxisSystem getAxisSystem()
```


Hämtar axelsystemet i den exporterade filen.

**Returns:**
[AxisSystem](../../com.aspose.threed/axissystem) - the axis system in the exported file. **Remarks:** FlipCoordinateSystem must be enabled to utilize this feature.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getEnableMaterials() {#getEnableMaterials--}
```
public boolean getEnableMaterials()
```


Hämtar om material för import/export ska användas för varje objekt

**Returns:**
boolean - om material ska importeras/exporteras för varje objekt
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


Hämtar om koordinatsystemet för kontrollpunkter/normaler ska vändas under import/export.

**Returns:**
boolean - om koordinatsystemet för kontrollpunkter/normaler ska vändas under import/export.
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
### getPointCloud() {#getPointCloud--}
```
public boolean getPointCloud()
```


Hämtar flaggan som anger om exportören ska exportera scenen som punktmoln (utan topologisk struktur), standardvärdet är falskt.

**Returns:**
boolean - flaggan om exportören ska exportera scenen som punktmoln (utan topologisk struktur), standardvärdet är false
### getSerializeW() {#getSerializeW--}
```
public boolean getSerializeW()
```


Hämtar om W-komponenten i modellens vertexposition ska serialiseras.

**Returns:**
boolean - om W-komponenten ska serialiseras i modellens vertexposition.
### getVerbose() {#getVerbose--}
```
public boolean getVerbose()
```


Hämtar om kommentarer ska genereras för varje sektion.

**Returns:**
boolean - om kommentarer ska genereras för varje avsnitt
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


Tillämpa [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) på meshen. Standardvärdet är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setAxisSystem(AxisSystem value) {#setAxisSystem-com.aspose.threed.AxisSystem-}
```
public void setAxisSystem(AxisSystem value)
```


Ställer in axelsystemet i den exporterade filen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [AxisSystem](../../com.aspose.threed/axissystem) | Nytt värde **Anmärkningar:** FlipCoordinateSystem måste vara aktiverat för att använda denna funktion. |

### setEnableMaterials(boolean value) {#setEnableMaterials-boolean-}
```
public void setEnableMaterials(boolean value)
```


Ställer in om material för import/export ska användas för varje objekt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


Ställer in om koordinatsystemet för kontrollpunkter/normaler ska vändas under import/export.

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

### setPointCloud(boolean value) {#setPointCloud-boolean-}
```
public void setPointCloud(boolean value)
```


Ställer in flaggan som anger om exportören ska exportera scenen som punktmoln (utan topologisk struktur), standardvärdet är falskt.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setSerializeW(boolean value) {#setSerializeW-boolean-}
```
public void setSerializeW(boolean value)
```


Ställer in om W-komponenten ska serialiseras i modellens vertexposition.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setVerbose(boolean value) {#setVerbose-boolean-}
```
public void setVerbose(boolean value)
```


Ställer in om kommentarer ska genereras för varje avsnitt

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

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

