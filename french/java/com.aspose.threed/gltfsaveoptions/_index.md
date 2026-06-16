---
title: "GltfSaveOptions"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Options d'enregistrement pour le format glTF."
type: docs
weight: 74
url: /fr/java/com.aspose.threed/gltfsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class GltfSaveOptions extends SaveOptions
```

Options d'enregistrement pour le format glTF.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GltfSaveOptions(FileContentType contentType)](#GltfSaveOptions-com.aspose.threed.FileContentType-) | Constructeur de [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
| [GltfSaveOptions(FileFormat format)](#GltfSaveOptions-com.aspose.threed.FileFormat-) | Constructeur de [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getApplyUnitScale()](#getApplyUnitScale--) | Appliquer [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) au maillage. |
| [getBufferFile()](#getBufferFile--) | Le nom de fichier du tampon externe utilisé pour stocker les données binaires. |
| [getClass()](#getClass--) |  |
| [getDracoCompression()](#getDracoCompression--) | Obtient si la compression draco doit être activée |
| [getEmbedAssets()](#getEmbedAssets--) | Intègre tous les actifs externes en base64 dans un seul fichier en mode ASCII, la valeur par défaut est false. |
| [getEncoding()](#getEncoding--) | Obtient le codage par défaut pour les fichiers texte. |
| [getExportTextures()](#getExportTextures--) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [getExternalDracoEncoder()](#getExternalDracoEncoder--) | Utilisez l'encodeur draco externe pour accélérer la vitesse de compression draco. |
| [getFallbackNormal()](#getFallbackNormal--) | Lorsque l'exportateur GLTF2 détecte une normale invalide, celle-ci sera utilisée à la place de sa valeur originale pour contourner la validation. |
| [getFileFormat()](#getFileFormat--) | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [getFileName()](#getFileName--) | Le nom de fichier de la scène d'exportation/importation. |
| [getFileSystem()](#getFileSystem--) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtient la classe de fabrique pour FileSystem. |
| [getFlipTexCoordV()](#getFlipTexCoordV--) | Inverser le composant v(t) de la coordonnée de texture, la valeur par défaut est true. |
| [getImageFormat()](#getImageFormat--) | Le glTF standard ne prend en charge que les formats PNG/JPG comme textures ; cette option indiquera comment Aspose.3D convertit les images non standard en format pris en charge lors de l'exportation. |
| [getLookupPaths()](#getLookupPaths--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [getMaterialConverter()](#getMaterialConverter--) | Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si celui-ci n'est pas assigné, l'exportateur glTF 2.0 convertira automatiquement le matériau standard en matériau PBR. |
| [getPrettyPrint()](#getPrettyPrint--) | Le contenu JSON du fichier GLTF est indenté pour une lecture humaine, la valeur par défaut est false |
| [getSaveExtras()](#getSaveExtras--) | Enregistrez les propriétés dynamiques de l'objet de scène dans les champs 'extra' du fichier glTF généré. |
| [getUseCommonMaterials()](#getUseCommonMaterials--) | Sérialisez les matériaux en utilisant les extensions de matériau communes KHR, la valeur par défaut est false. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setApplyUnitScale(boolean value)](#setApplyUnitScale-boolean-) | Appliquer [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) au maillage. |
| [setBufferFile(String value)](#setBufferFile-java.lang.String-) | Le nom de fichier du tampon externe utilisé pour stocker les données binaires. |
| [setDracoCompression(boolean value)](#setDracoCompression-boolean-) | Définit si la compression draco doit être activée |
| [setEmbedAssets(boolean value)](#setEmbedAssets-boolean-) | Intègre tous les actifs externes en base64 dans un seul fichier en mode ASCII, la valeur par défaut est false. |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Définit le codage par défaut pour les fichiers texte. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie. |
| [setExternalDracoEncoder(String value)](#setExternalDracoEncoder-java.lang.String-) | Utilisez l'encodeur draco externe pour accélérer la vitesse de compression draco. |
| [setFallbackNormal(Vector3 value)](#setFallbackNormal-com.aspose.threed.Vector3-) | Lorsque l'exportateur GLTF2 détecte une normale invalide, celle-ci sera utilisée à la place de sa valeur originale pour contourner la validation. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Le nom de fichier de la scène d'exportation/importation. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Définit la classe de fabrique pour FileSystem. |
| [setFlipTexCoordV(boolean value)](#setFlipTexCoordV-boolean-) | Inverser le composant v(t) de la coordonnée de texture, la valeur par défaut est true. |
| [setImageFormat(GltfEmbeddedImageFormat value)](#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-) | Le glTF standard ne prend en charge que les formats PNG/JPG comme textures ; cette option indiquera comment Aspose.3D convertit les images non standard en format pris en charge lors de l'exportation. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [setMaterialConverter(MaterialConverter value)](#setMaterialConverter-com.aspose.threed.MaterialConverter-) | Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si celui-ci n'est pas assigné, l'exportateur glTF 2.0 convertira automatiquement le matériau standard en matériau PBR. |
| [setPrettyPrint(boolean value)](#setPrettyPrint-boolean-) | Le contenu JSON du fichier GLTF est indenté pour une lecture humaine, la valeur par défaut est false |
| [setSaveExtras(boolean value)](#setSaveExtras-boolean-) | Enregistrez les propriétés dynamiques de l'objet de scène dans les champs 'extra' du fichier glTF généré. |
| [setUseCommonMaterials(boolean value)](#setUseCommonMaterials-boolean-) | Sérialisez les matériaux en utilisant les extensions de matériau communes KHR, la valeur par défaut est false. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### GltfSaveOptions(FileContentType contentType) {#GltfSaveOptions-com.aspose.threed.FileContentType-}
```
public GltfSaveOptions(FileContentType contentType)
```


Constructeur de [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### GltfSaveOptions(FileFormat format) {#GltfSaveOptions-com.aspose.threed.FileFormat-}
```
public GltfSaveOptions(FileFormat format)
```


Constructeur de [GltfSaveOptions](../../com.aspose.threed/gltfsaveoptions)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| format | [FileFormat](../../com.aspose.threed/fileformat) |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getApplyUnitScale() {#getApplyUnitScale--}
```
public boolean getApplyUnitScale()
```


Appliquer [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) au maillage. La valeur par défaut est false.

**Returns:**
booléen - Appliquer [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) au maillage. La valeur par défaut est false.
### getBufferFile() {#getBufferFile--}
```
public String getBufferFile()
```


Le nom du fichier du tampon externe utilisé pour stocker les données binaires. Si ce fichier n'est pas spécifié, Aspose.3D générera un nom pour vous. Cela est ignoré lors de l'exportation glTF en mode binaire.

**Returns:**
java.lang.String - Le nom du fichier du tampon externe utilisé pour stocker les données binaires. Si ce fichier n'est pas spécifié, Aspose.3D générera un nom pour vous. Ceci est ignoré lors de l'exportation du glTF en mode binaire.
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


Obtient si la compression draco doit être activée

**Returns:**
boolean - si la compression draco doit être activée
### getEmbedAssets() {#getEmbedAssets--}
```
public boolean getEmbedAssets()
```


Intègre tous les actifs externes en base64 dans un seul fichier en mode ASCII, la valeur par défaut est false.

**Returns:**
booléen - Intégrer tous les actifs externes en base64 dans un seul fichier en mode ASCII, la valeur par défaut est false.
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Obtient le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.

**Returns:**
java.nio.charset.Charset - le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie.

**Returns:**
boolean - Tente de copier les textures utilisées dans la scène vers le répertoire de sortie.
### getExternalDracoEncoder() {#getExternalDracoEncoder--}
```
public String getExternalDracoEncoder()
```


Utilisez l'encodeur draco externe pour accélérer la vitesse de compression draco.

**Returns:**
java.lang.String - Utiliser un encodeur draco externe pour accélérer la vitesse de compression draco. **Remarks:** Aspose.3D créera un nouveau sous‑processus pour encoder le maillage au format draco, utilisez-le à vos propres risques.
### getFallbackNormal() {#getFallbackNormal--}
```
public Vector3 getFallbackNormal()
```


Lorsque l'exportateur GLTF2 détecte une normale invalide, celle-ci sera utilisée à la place de sa valeur originale pour contourner la validation. La valeur par défaut est (0, 1, 0).

**Returns:**
[Vector3](../../com.aspose.threed/vector3) - When GLTF2 exporter detected an invalid normal, this will be used instead of its original value to bypass the validation. Default value is (0, 1, 0)
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.

**Returns:**
java.lang.String - Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Et vous pouvez également utiliser votre propre implémentation.

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


Obtient la classe de fabrique pour FileSystem. La fabrique par défaut créera com.aspose.threed.LocalFileSystem qui n'est pas adaptée à un environnement serveur.

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


Inverser le composant v(t) de la coordonnée de texture, la valeur par défaut est true.

**Returns:**
booléen - Inverser le composant v(t) des coordonnées de texture, la valeur par défaut est true.
### getImageFormat() {#getImageFormat--}
```
public GltfEmbeddedImageFormat getImageFormat()
```


Le glTF standard ne prend en charge que les formats PNG/JPG comme textures, cette option indique comment Aspose.3D convertit les images non standard en format pris en charge lors de l'exportation. La valeur par défaut est [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Returns:**
[GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) - Standard glTF only supports PNG/JPG as its texture format, this option will guide how Aspose.3D convert the non-standard images to supported format during the exporting. Default value is [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger.

**Returns:**
java.util.ArrayList<java.lang.String> - Certains fichiers comme OBJ dépendent de fichiers externes, les chemins de recherche permettront à Aspose.3D de rechercher les fichiers externes à charger. **Example:** Le code suivant montre comment spécifier manuellement les textures de recherche, afin que l'importateur puisse les trouver

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


Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si celui-ci n'est pas assigné, l'exportateur glTF 2.0 convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. Cette propriété est utilisée lors de l'exportation d'une scène vers un fichier glTF 2.0.

**Returns:**
[MaterialConverter](../../com.aspose.threed/materialconverter) - Custom converter to convert the geometry's material to PBR material If this is unassigned, glTF 2.0 exporter will automatically convert the standard material to PBR material. Default value is null This property is used when exporting a scene to a glTF 2.0 file.
### getPrettyPrint() {#getPrettyPrint--}
```
public boolean getPrettyPrint()
```


Le contenu JSON du fichier GLTF est indenté pour une lecture humaine, la valeur par défaut est false

**Returns:**
booléen - Le contenu JSON du fichier GLTF est indenté pour la lecture humaine, la valeur par défaut est false
### getSaveExtras() {#getSaveExtras--}
```
public boolean getSaveExtras()
```


Enregistrer les propriétés dynamiques de l'objet de scène dans les champs 'extra' du fichier glTF généré. Cela est utile pour fournir des données spécifiques à l'application. La valeur par défaut est false.

**Returns:**
booléen - Enregistrer les propriétés dynamiques de l'objet de scène dans les champs 'extra' du fichier glTF généré. Cela est utile pour fournir des données spécifiques à l'application. La valeur par défaut est false.
### getUseCommonMaterials() {#getUseCommonMaterials--}
```
public boolean getUseCommonMaterials()
```


Sérialiser les matériaux en utilisant les extensions de matériau communes KHR, la valeur par défaut est false. Mettre cela à false entraînera Aspose.3D à exporter un ensemble de shaders vertex/fragment si [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Returns:**
booléen - Sérialiser les matériaux en utilisant les extensions de matériau communes KHR, la valeur par défaut est false. Mettre cela à false entraînera Aspose.3D à exporter un ensemble de shaders vertex/fragment si [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders) **Remarks:** Cette propriété ne fonctionne que pour glTF 1.0
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


Appliquer [AssetInfo.getUnitScaleFactor](../../com.aspose.threed/assetinfo\#getUnitScaleFactor) au maillage. La valeur par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setBufferFile(String value) {#setBufferFile-java.lang.String-}
```
public void setBufferFile(String value)
```


Le nom du fichier du tampon externe utilisé pour stocker les données binaires. Si ce fichier n'est pas spécifié, Aspose.3D générera un nom pour vous. Cela est ignoré lors de l'exportation glTF en mode binaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setDracoCompression(boolean value) {#setDracoCompression-boolean-}
```
public void setDracoCompression(boolean value)
```


Définit si la compression draco doit être activée

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setEmbedAssets(boolean value) {#setEmbedAssets-boolean-}
```
public void setEmbedAssets(boolean value)
```


Intègre tous les actifs externes en base64 dans un seul fichier en mode ASCII, la valeur par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset | Nouvelle valeur |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Essaie de copier les textures utilisées dans la scène vers le répertoire de sortie.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setExternalDracoEncoder(String value) {#setExternalDracoEncoder-java.lang.String-}
```
public void setExternalDracoEncoder(String value)
```


Utilisez l'encodeur draco externe pour accélérer la vitesse de compression draco.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur **Remarks:** Aspose.3D créera un nouveau sous‑processus pour encoder le maillage au format draco, utilisez-le à vos propres risques. |

### setFallbackNormal(Vector3 value) {#setFallbackNormal-com.aspose.threed.Vector3-}
```
public void setFallbackNormal(Vector3 value)
```


Lorsque l'exportateur GLTF2 détecte une normale invalide, celle-ci sera utilisée à la place de sa valeur originale pour contourner la validation. La valeur par défaut est (0, 1, 0).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [Vector3](../../com.aspose.threed/vector3) | Nouvelle valeur |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Le nom de fichier de la scène d'exportation/importation. Ceci est optionnel, mais utile lors de la sérialisation d'actifs externes comme le matériau d'OBJ.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Nouvelle valeur **Example:** Le système de fichiers par défaut est LocalFileSystem, il n'est pas sûr dans un environnement côté serveur, mais vous pouvez remplacer l'accès au système de fichiers en spécifiant une implémentation différente. Aspose.3D fournit différentes implémentations de FileSystem comme : |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Et vous pouvez également utiliser votre propre implémentation.

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


Définit la classe de fabrique pour FileSystem. La fabrique par défaut créera com.aspose.threed.LocalFileSystem qui n'est pas adaptée à un environnement serveur.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Nouvelle valeur **Example:** Le système de fichiers par défaut dans SaveOptions/LoadOptions est un système de fichiers basé sur les répertoires, vous pouvez remplacer l'implémentation par défaut en le spécifiant via IOConfig.FileSystemFactory : |

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


Inverser le composant v(t) de la coordonnée de texture, la valeur par défaut est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setImageFormat(GltfEmbeddedImageFormat value) {#setImageFormat-com.aspose.threed.GltfEmbeddedImageFormat-}
```
public void setImageFormat(GltfEmbeddedImageFormat value)
```


Le glTF standard ne prend en charge que les formats PNG/JPG comme textures, cette option indique comment Aspose.3D convertit les images non standard en format pris en charge lors de l'exportation. La valeur par défaut est [GltfEmbeddedImageFormat.PNG](../../com.aspose.threed/gltfembeddedimageformat\#PNG)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [GltfEmbeddedImageFormat](../../com.aspose.threed/gltfembeddedimageformat) | Nouvelle valeur |

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
|  | valeur | java.util.ArrayList<java.lang.String> | Nouvelle valeur **Example:** Le code suivant montre comment spécifier manuellement les textures de recherche, afin que l'importateur puisse les trouver |

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


Convertisseur personnalisé pour convertir le matériau de la géométrie en matériau PBR. Si celui-ci n'est pas assigné, l'exportateur glTF 2.0 convertira automatiquement le matériau standard en matériau PBR. La valeur par défaut est null. Cette propriété est utilisée lors de l'exportation d'une scène vers un fichier glTF 2.0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | [MaterialConverter](../../com.aspose.threed/materialconverter) | Nouvelle valeur |

### setPrettyPrint(boolean value) {#setPrettyPrint-boolean-}
```
public void setPrettyPrint(boolean value)
```


Le contenu JSON du fichier GLTF est indenté pour une lecture humaine, la valeur par défaut est false

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setSaveExtras(boolean value) {#setSaveExtras-boolean-}
```
public void setSaveExtras(boolean value)
```


Enregistrer les propriétés dynamiques de l'objet de scène dans les champs 'extra' du fichier glTF généré. Cela est utile pour fournir des données spécifiques à l'application. La valeur par défaut est false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setUseCommonMaterials(boolean value) {#setUseCommonMaterials-boolean-}
```
public void setUseCommonMaterials(boolean value)
```


Sérialiser les matériaux en utilisant les extensions de matériau communes KHR, la valeur par défaut est false. Mettre cela à false entraînera Aspose.3D à exporter un ensemble de shaders vertex/fragment si [getExportShaders](../../com.aspose.threed/gltfsaveoptions\#getExportShaders)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur **Remarks:** Cette propriété ne fonctionne que pour glTF 1.0 |

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
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

