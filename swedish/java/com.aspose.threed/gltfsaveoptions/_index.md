---
title: GltfSaveOptions
second_title: Aspose.3D for Java API-referens
description: Sparaalternativ för glTF-format.
type: docs
weight: 74
url: /sv/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

Sparaalternativ för glTF-format.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Konstruktor för [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Konstruktor för [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Tillämpa [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) på meshen. |
| [getBufferFile()](#getBufferFile--) | Filnamnet på den externa buffertfilen som används för att lagra binär data. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Hämtar om draco-komprimering ska aktiveras |
| [getEmbedAssets()](#getEmbedAssets--) | Bädda in alla externa resurser som base64 i en enda fil i ASCII-läge, standardvärdet är falskt. |
| [getEncoding()](#getEncoding--) | Hämtar standardkodningen för textbaserade filer. |
| [getExportTextures()](#getExportTextures--) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Använd extern draco-kodare för att påskynda draco-komprimeringshastigheten. |
| [getFallbackNormal()](#getFallbackNormal--) | När GLTF2-exportören upptäcker en ogiltig normal, kommer detta att användas istället för dess ursprungliga värde för att kringgå valideringen. |
| [getFileFormat()](#getFileFormat--) | Hämtar filformatet som anges i aktuellt Spara/Ladda-alternativ. |
| [getFileName()](#getFileName--) | Filnamnet för den exporterande/importerande scenen. |
| [getFileSystem()](#getFileSystem--) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Hämtar fabriksklassen för FileSystem. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Vänd texturkoordinatens v(t)-komponent, standardvärdet är sant. |
| [getImageFormat()](#getImageFormat--) | Standard glTF stöder endast PNG/JPG som sitt texturformat, det här alternativet kommer att styra hur Aspose.3D konverterar de icke‑standardbilderna till ett stödformat under exporten. |
| [getLookupPaths()](#getLookupPaths--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [getMaterialConverter()](#getMaterialConverter--) | Anpassad konverterare för att konvertera geometrins material till PBR‑material. Om detta är odefinierat kommer glTF 2.0‑exportören automatiskt att konvertera standardmaterialet till PBR‑material. |
| [getPrettyPrint()](#getPrettyPrint--) | JSON‑innehållet i GLTF‑filen är indenterat för mänsklig läsning, standardvärdet är false. |
| [getSaveExtras()](#getSaveExtras--) | Spara scenobjektets dynamiska egenskaper i 'extra'-fält i den genererade glTF‑filen. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Serialisera material med KHR‑gemensamma material‑tillägg, standardvärdet är false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Tillämpa [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) på meshen. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | Filnamnet på den externa buffertfilen som används för att lagra binär data. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Anger om draco‑komprimering ska aktiveras. |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Bädda in alla externa resurser som base64 i en enda fil i ASCII-läge, standardvärdet är falskt. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ställer in standardkodningen för textbaserade filer. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Försök att kopiera texturer som används i scenen till utmatningskatalogen. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Använd extern draco-kodare för att påskynda draco-komprimeringshastigheten. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | När GLTF2-exportören upptäcker en ogiltig normal, kommer detta att användas istället för dess ursprungliga värde för att kringgå valideringen. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Filnamnet för den exporterande/importerande scenen. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Tillåter användaren att hantera hur externa beroenden ska hanteras under laddning/sparning. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ställer in fabriksklassen för FileSystem. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Vänd texturkoordinatens v(t)-komponent, standardvärdet är sant. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Standard glTF stöder endast PNG/JPG som sitt texturformat, det här alternativet kommer att styra hur Aspose.3D konverterar de icke‑standardbilderna till ett stödformat under exporten. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Vissa filer som OBJ är beroende av externa filer, sökvägarna gör att Aspose.3D kan leta efter externa filer att ladda. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Anpassad konverterare för att konvertera geometrins material till PBR‑material. Om detta är odefinierat kommer glTF 2.0‑exportören automatiskt att konvertera standardmaterialet till PBR‑material. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | JSON‑innehållet i GLTF‑filen är indenterat för mänsklig läsning, standardvärdet är false. |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Spara scenobjektets dynamiska egenskaper i 'extra'-fält i den genererade glTF‑filen. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Serialisera material med KHR‑gemensamma material‑tillägg, standardvärdet är false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Konstruktor för [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Konstruktor för [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


Filnamnet på den externa buffertfilen som används för att lagra binär data. Om denna fil inte anges kommer Aspose.3D att generera ett namn åt dig. Detta ignoreras vid export av glTF i binärt läge.

**Returns:**
java.lang.String - Filnamnet på den externa buffertfilen som används för att lagra binär data. Om denna fil inte anges kommer Aspose.3D att generera ett namn åt dig. Detta ignoreras vid export av glTF i binärt läge.
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


Hämtar om draco-komprimering ska aktiveras

**Returns:**
boolean - om draco‑komprimering ska aktiveras
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Bädda in alla externa resurser som base64 i en enda fil i ASCII-läge, standardvärdet är falskt.

**Returns:**
boolean - Bädda in alla externa resurser som base64 i en enda fil i ASCII‑läge, standardvärdet är false.
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
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Använd extern draco-kodare för att påskynda draco-komprimeringshastigheten.

**Returns:**
java.lang.String - Använd extern draco‑kodare för att påskynda draco‑komprimeringshastigheten. **Remarks:** Aspose.3D kommer att skapa en ny underprocess för att koda meshen till draco‑formatet, använd på egen risk.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


När GLTF2‑exportören upptäcker en ogiltig normal kommer detta att användas i stället för det ursprungliga värdet för att kringgå valideringen. Standardvärdet är (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
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
### getFlipTexCoordV() {#getFlipTexCoordV--}
```
public boolean getFlipTexCoordV()
```


Vänd texturkoordinatens v(t)-komponent, standardvärdet är sant.

**Returns:**
boolean - Vänd texturkoordinatens v(t)-komponent, standardvärdet är true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Standard glTF stöder endast PNG/JPG som sitt texturformat, detta alternativ styr hur Aspose.3D konverterar icke‑standardbilder till ett stödformat under exporten. Standardvärdet är [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
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
### getMaterialConverter() {#getMaterialConverter--}
```
public MaterialConverter getMaterialConverter()
```


Anpassad konverterare för att konvertera geometrins material till PBR‑material. Om detta är odefinierat kommer glTF 2.0‑exportören automatiskt att konvertera standardmaterialet till PBR‑material. Standardvärdet är null. Denna egenskap används vid export av en scen till en glTF 2.0‑fil.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


JSON‑innehållet i GLTF‑filen är indenterat för mänsklig läsning, standardvärdet är false.

**Returns:**
boolean - JSON‑innehållet i GLTF‑filen är indenterat för mänsklig läsning, standardvärdet är false.
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Spara scenobjektets dynamiska egenskaper i 'extra'-fält i den genererade glTF‑filen. Detta är användbart för att tillhandahålla programspecifika data. Standardvärdet är false.

**Returns:**
boolean - Spara scenobjektets dynamiska egenskaper i 'extra'-fält i den genererade glTF‑filen. Detta är användbart för att tillhandahålla programspecifika data. Standardvärdet är false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Serialisera material med KHR‑gemensamma material‑tillägg, standardvärdet är false. Att sätta detta till false får Aspose.3D att exportera en uppsättning vertex-/fragment‑shader om [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
boolean - Serialisera material med KHR‑gemensamma material‑tillägg, standardvärdet är false. Att sätta detta till false får Aspose.3D att exportera en uppsättning vertex-/fragment‑shader om [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** Denna egenskap fungerar endast för glTF 1.0
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

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


Filnamnet på den externa buffertfilen som används för att lagra binär data. Om denna fil inte anges kommer Aspose.3D att generera ett namn åt dig. Detta ignoreras vid export av glTF i binärt läge.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Anger om draco‑komprimering ska aktiveras.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Bädda in alla externa resurser som base64 i en enda fil i ASCII-läge, standardvärdet är falskt.

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

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Använd extern draco-kodare för att påskynda draco-komprimeringshastigheten.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.lang.String | Nytt värde **Remarks:** Aspose.3D kommer att skapa en ny underprocess för att koda meshen till draco‑formatet, använd på egen risk. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


När GLTF2‑exportören upptäcker en ogiltig normal kommer detta att användas i stället för det ursprungliga värdet för att kringgå valideringen. Standardvärdet är (0, 1, 0).

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nytt värde |

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

### setFlipTexCoordV(boolean value) {#setFlipTexCoordV-boolean-}
```
public void setFlipTexCoordV(boolean value)
```


Vänd texturkoordinatens v(t)-komponent, standardvärdet är sant.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Standard glTF stöder endast PNG/JPG som sitt texturformat, detta alternativ styr hur Aspose.3D konverterar icke‑standardbilder till ett stödformat under exporten. Standardvärdet är [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Nytt värde |

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

### setMaterialConverter(MaterialConverter value) {#setMaterialConverter-com.aspose.threed.MaterialConverter-}
```
public void setMaterialConverter(MaterialConverter value)
```


Anpassad konverterare för att konvertera geometrins material till PBR‑material. Om detta är odefinierat kommer glTF 2.0‑exportören automatiskt att konvertera standardmaterialet till PBR‑material. Standardvärdet är null. Denna egenskap används vid export av en scen till en glTF 2.0‑fil.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nytt värde |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


JSON‑innehållet i GLTF‑filen är indenterat för mänsklig läsning, standardvärdet är false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Spara scenobjektets dynamiska egenskaper i 'extra'-fält i den genererade glTF‑filen. Detta är användbart för att tillhandahålla programspecifika data. Standardvärdet är false.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Serialisera material med KHR‑gemensamma material‑tillägg, standardvärdet är false. Att sätta detta till false får Aspose.3D att exportera en uppsättning vertex-/fragment‑shader om [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | boolean | Nytt värde **Remarks:** Denna egenskap fungerar endast för glTF 1.0 |

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

