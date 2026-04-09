---
title: GltfSaveOptions
second_title: Aspose.3D for Java API Reference
description: Opzioni di salvataggio per il formato glTF.
type: docs
weight: 74
url: /it/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

Opzioni di salvataggio per il formato glTF.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Costruttore di [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Costruttore di [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Applica [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) alla mesh. |
| [getBufferFile()](#getBufferFile--) | Il nome file del buffer esterno utilizzato per memorizzare i dati binari. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Restituisce se abilitare la compressione draco |
| [getEmbedAssets()](#getEmbedAssets--) | Incorpora tutti gli asset esterni come base64 in un unico file in modalità ASCII, il valore predefinito è false. |
| [getEncoding()](#getEncoding--) | Restituisce la codifica predefinita per i file di testo. |
| [getExportTextures()](#getExportTextures--) | Prova a copiare le texture usate nella scena nella directory di output. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Utilizza un codificatore draco esterno per accelerare la velocità di compressione draco. |
| [getFallbackNormal()](#getFallbackNormal--) | Quando l'esportatore GLTF2 rileva una normale non valida, questo verrà usato al posto del valore originale per aggirare la convalida. |
| [getFileFormat()](#getFileFormat--) | Restituisce il formato file specificato nell'opzione Salva/Carica corrente. |
| [getFileName()](#getFileName--) | Il nome file della scena di esportazione/importazione. |
| [getFileSystem()](#getFileSystem--) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Restituisce la classe factory per FileSystem. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Capovolgi la componente v(t) della coordinata della texture, il valore predefinito è true. |
| [getImageFormat()](#getImageFormat--) | Lo standard glTF supporta solo PNG/JPG come formato texture; questa opzione guiderà come Aspose.3D converte le immagini non standard in un formato supportato durante l'esportazione. |
| [getLookupPaths()](#getLookupPaths--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [getMaterialConverter()](#getMaterialConverter--) | Convertitore personalizzato per convertire il materiale della geometria in materiale PBR. Se non assegnato, l'esportatore glTF 2.0 convertirà automaticamente il materiale standard in materiale PBR. |
| [getPrettyPrint()](#getPrettyPrint--) | Il contenuto JSON del file GLTF è indentato per la lettura umana, il valore predefinito è false |
| [getSaveExtras()](#getSaveExtras--) | Salva le proprietà dinamiche dell'oggetto scena nei campi 'extra' nel file glTF generato. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Serializza i materiali usando le estensioni di materiale comuni KHR, il valore predefinito è false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Applica [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) alla mesh. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | Il nome file del buffer esterno utilizzato per memorizzare i dati binari. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Imposta se abilitare la compressione draco |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Incorpora tutti gli asset esterni come base64 in un unico file in modalità ASCII, il valore predefinito è false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Imposta la codifica predefinita per i file di testo. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Prova a copiare le texture usate nella scena nella directory di output. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Utilizza un codificatore draco esterno per accelerare la velocità di compressione draco. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | Quando l'esportatore GLTF2 rileva una normale non valida, questo verrà usato al posto del valore originale per aggirare la convalida. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Il nome file della scena di esportazione/importazione. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Imposta la classe factory per FileSystem. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Capovolgi la componente v(t) della coordinata della texture, il valore predefinito è true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Lo standard glTF supporta solo PNG/JPG come formato texture; questa opzione guiderà come Aspose.3D converte le immagini non standard in un formato supportato durante l'esportazione. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Convertitore personalizzato per convertire il materiale della geometria in materiale PBR. Se non assegnato, l'esportatore glTF 2.0 convertirà automaticamente il materiale standard in materiale PBR. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | Il contenuto JSON del file GLTF è indentato per la lettura umana, il valore predefinito è false |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Salva le proprietà dinamiche dell'oggetto scena nei campi 'extra' nel file glTF generato. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Serializza i materiali usando le estensioni di materiale comuni KHR, il valore predefinito è false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Costruttore di [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Costruttore di [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

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
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Applica [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) alla mesh. Il valore predefinito è false.

**Returns:**
boolean - Applica [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) alla mesh. Il valore predefinito è false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


Il nome del file del buffer esterno utilizzato per memorizzare i dati binari. Se questo file non è specificato, Aspose.3D genererà un nome per te. Questo è ignorato quando si esporta glTF in modalità binaria.

**Returns:**
java.lang.String - Il nome del file del buffer esterno utilizzato per memorizzare i dati binari. Se questo file non è specificato, Aspose.3D genererà un nome per te. Questo è ignorato quando si esporta glTF in modalità binaria.
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


Restituisce se abilitare la compressione draco

**Returns:**
boolean - se abilitare la compressione draco
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Incorpora tutti gli asset esterni come base64 in un unico file in modalità ASCII, il valore predefinito è false.

**Returns:**
boolean - Incorpora tutte le risorse esterne come base64 in un unico file in modalità ASCII, il valore predefinito è false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Restituisce la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Returns:**
java.nio.charset.Charset - la codifica predefinita per i file di testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Prova a copiare le texture usate nella scena nella directory di output.

**Returns:**
boolean - Prova a copiare le texture usate nella scena nella directory di output.
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Utilizza un codificatore draco esterno per accelerare la velocità di compressione draco.

**Returns:**
java.lang.String - Usa un codificatore draco esterno per accelerare la velocità di compressione draco. **Remarks:** Aspose.3D creerà un nuovo sottoprocesso per codificare la mesh nel formato draco, usalo a tuo rischio.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


Quando l'esportatore GLTF2 rileva una normale non valida, questo valore verrà usato al posto di quello originale per aggirare la validazione. Il valore predefinito è (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Restituisce il formato file specificato nell'opzione Salva/Carica corrente.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.

**Returns:**
java.lang.String - Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

E puoi anche utilizzare la tua implementazione.

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


Ottiene la classe factory per FileSystem. La factory predefinita creerà com.aspose.threed.LocalFileSystem, che non è adatta per l'ambiente server.

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


Capovolgi la componente v(t) della coordinata della texture, il valore predefinito è true.

**Returns:**
boolean - Inverti la componente v(t) della coordinata texture, il valore predefinito è true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Lo standard glTF supporta solo PNG/JPG come formato texture; questa opzione guiderà come Aspose.3D converte le immagini non standard in un formato supportato durante l'esportazione. Il valore predefinito è [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare.

**Returns:**
java.util.ArrayList<java.lang.String> - Alcuni file come OBJ dipendono da file esterni; i percorsi di ricerca consentiranno ad Aspose.3D di cercare i file esterni da caricare. **Esempio:** Il codice seguente mostra come specificare manualmente le texture di ricerca, così l'importatore può trovarle

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


Convertitore personalizzato per convertire il materiale della geometria in materiale PBR. Se non assegnato, l'esportatore glTF 2.0 convertirà automaticamente il materiale standard in materiale PBR. Il valore predefinito è null. Questa proprietà è usata quando si esporta una scena in un file glTF 2.0.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


Il contenuto JSON del file GLTF è indentato per la lettura umana, il valore predefinito è false

**Returns:**
boolean - Il contenuto JSON del file GLTF è indentato per la lettura umana, il valore predefinito è false
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Salva le proprietà dinamiche dell'oggetto scena nei campi 'extra' nel file glTF generato. Questo è utile per fornire dati specifici dell'applicazione. Il valore predefinito è false.

**Returns:**
boolean - Salva le proprietà dinamiche dell'oggetto scena nei campi 'extra' nel file glTF generato. Questo è utile per fornire dati specifici dell'applicazione. Il valore predefinito è false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Serializza i materiali usando le estensioni di materiale comuni KHR, il valore predefinito è false. Impostare questo a false farà sì che Aspose.3D esporti un set di shader vertex/fragment se [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
boolean - Serializza i materiali usando le estensioni di materiale comuni KHR, il valore predefinito è false. Impostare questo a false farà sì che Aspose.3D esporti un set di shader vertex/fragment se [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** Questa proprietà funziona solo per glTF 1.0
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


Applica [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) alla mesh. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


Il nome del file del buffer esterno utilizzato per memorizzare i dati binari. Se questo file non è specificato, Aspose.3D genererà un nome per te. Questo è ignorato quando si esporta glTF in modalità binaria.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Imposta se abilitare la compressione draco

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Incorpora tutti gli asset esterni come base64 in un unico file in modalità ASCII, il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Imposta la codifica predefinita per i file basati su testo. Il valore predefinito è null, il che significa che l'importatore/esportatore deciderà quale codifica utilizzare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.nio.charset.Charset | Nuovo valore |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Prova a copiare le texture usate nella scena nella directory di output.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Utilizza un codificatore draco esterno per accelerare la velocità di compressione draco.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore **Remarks:** Aspose.3D creerà un nuovo sottoprocesso per codificare la mesh nel formato draco, usalo a tuo rischio. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


Quando l'esportatore GLTF2 rileva una normale non valida, questo valore verrà usato al posto di quello originale per aggirare la validazione. Il valore predefinito è (0, 1, 0).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nuovo valore |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Il nome file della scena di esportazione/importazione. È opzionale, ma utile quando si serializzano risorse esterne come il materiale di OBJ.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.lang.String | Nuovo valore |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Consente all'utente di decidere come gestire le dipendenze esterne durante il caricamento/salvataggio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nuovo valore **Esempio:** Il FileSystem predefinito è LocalFileSystem, non è sicuro in ambienti come il lato server, ma è possibile sovrascrivere l'accesso al file system specificando un'implementazione diversa. Aspose.3D fornisce diverse implementazioni di FileSystem come: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

E puoi anche utilizzare la tua implementazione.

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


Imposta la classe factory per FileSystem. La factory predefinita creerà com.aspose.threed.LocalFileSystem, che non è adatta per l'ambiente server.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nuovo valore **Esempio:** Il FileSystem predefinito in SaveOptions/LoadOptions è un file system basato su directory; è possibile sovrascrivere l'implementazione predefinita specificandola tramite IOConfig.FileSystemFactory: |

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


Capovolgi la componente v(t) della coordinata della texture, il valore predefinito è true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Lo standard glTF supporta solo PNG/JPG come formato texture; questa opzione guiderà come Aspose.3D converte le immagini non standard in un formato supportato durante l'esportazione. Il valore predefinito è [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Nuovo valore |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Alcuni file, come OBJ, dipendono da file esterni; i percorsi di ricerca consentono ad Aspose.3D di cercare il file esterno da caricare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
|  | valore | java.util.ArrayList<java.lang.String> | Nuovo valore **Esempio:** Il codice seguente mostra come specificare manualmente le texture di ricerca, così l'importatore può trovarle |

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


Convertitore personalizzato per convertire il materiale della geometria in materiale PBR. Se non assegnato, l'esportatore glTF 2.0 convertirà automaticamente il materiale standard in materiale PBR. Il valore predefinito è null. Questa proprietà è usata quando si esporta una scena in un file glTF 2.0.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nuovo valore |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


Il contenuto JSON del file GLTF è indentato per la lettura umana, il valore predefinito è false

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Salva le proprietà dinamiche dell'oggetto scena nei campi 'extra' nel file glTF generato. Questo è utile per fornire dati specifici dell'applicazione. Il valore predefinito è false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Serializza i materiali usando le estensioni di materiale comuni KHR, il valore predefinito è false. Impostare questo a false farà sì che Aspose.3D esporti un set di shader vertex/fragment se [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean | Nuovo valore **Remarks:** Questa proprietà funziona solo per glTF 1.0 |

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

