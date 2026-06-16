---
title: "RvmLoadOptions"
second_title: "Référence d'API Aspose.3D pour Java"
description: "Options de chargement pour le fichier RVM d'AVEVA Plant Design Management Systems."
type: docs
weight: 157
url: /fr/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

Options de chargement pour le fichier RVM d'AVEVA Plant Design Management System. **Exemple:** Le code suivant montre comment personnaliser les paramètres de tessellation pour les géométries primitives importées du fichier RVM en utilisant RvmLoadOptions.

```
RvmLoadOptions opt = new RvmLoadOptions();
             opt.setRectangularTorusSegments(30);
             opt.setCylinderRadialSegments(20);
             opt.setDishLatitudeSegments(20);
             opt.setDishLongitudeSegments(20);
             opt.setCenterScene(true);
             var scene = Scene.fromFile("input.rvm", opt);
             scene.save("output.obj");
```
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | Construisez une instance de [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) |
| [RvmLoadOptions()](#RvmLoadOptions--) | Construisez une instance de [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) |
## Méthodes

| Méthode | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | Obtient le préfixe des attributs qui ont été définis dans des fichiers d'attributs externes. Le préfixe est utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:" |
| [getCenterScene()](#getCenterScene--) | Centrer la scène après son chargement. |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | Obtient le nombre de segments radiaux du cylindre, la valeur par défaut est 16 |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | Obtient le nombre de segments de latitude du plat, la valeur par défaut est 8 |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | Obtient le nombre de segments de longitude du plat, la valeur par défaut est 12 |
| [getEncoding()](#getEncoding--) | Obtient le codage par défaut pour les fichiers texte. |
| [getFileFormat()](#getFileFormat--) | Obtient le format de fichier spécifié dans l'option Enregistrement/Chargement actuelle. |
| [getFileName()](#getFileName--) | Le nom de fichier de la scène d'exportation/importation. |
| [getFileSystem()](#getFileSystem--) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Obtient la classe de fabrique pour FileSystem. |
| [getGenerateMaterials()](#getGenerateMaterials--) | Générer des matériaux avec des couleurs aléatoires pour chaque objet de la scène si la table des couleurs n'est pas exportée dans le fichier RVM. |
| [getLookupAttributes()](#getLookupAttributes--) | Obtient si les attributs doivent être chargés depuis un fichier de liste d'attributs externe (.att/.attrib/.txt), la valeur par défaut est true. |
| [getLookupPaths()](#getLookupPaths--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | Obtient le nombre de segments radiaux du tore rectangulaire, la valeur par défaut est 20 |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | Obtient le nombre de segments tubulaires du tore, la valeur par défaut est 20 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | Définit le préfixe des attributs qui ont été définis dans des fichiers d'attributs externes. Le préfixe est utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:" |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | Centrer la scène après son chargement. |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | Définit le nombre de segments radiaux du cylindre, la valeur par défaut est 16 |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | Définit le nombre de segments de latitude du plat, la valeur par défaut est 8 |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | Définit le nombre de segments de longitude du plat, la valeur par défaut est 12 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Définit le codage par défaut pour les fichiers texte. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Le nom de fichier de la scène d'exportation/importation. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Autoriser l'utilisateur à gérer les dépendances externes lors de l'enregistrement/chargement. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Définit la classe de fabrique pour FileSystem. |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | Générer des matériaux avec des couleurs aléatoires pour chaque objet de la scène si la table des couleurs n'est pas exportée dans le fichier RVM. |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | Définit si les attributs doivent être chargés depuis un fichier de liste d'attributs externe (.att/.attrib/.txt), la valeur par défaut est true. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Certains fichiers comme OBJ dépendent d'un fichier externe, les chemins de recherche permettent à Aspose.3D de rechercher le fichier externe à charger. |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | Définit le nombre de segments radiaux du tore rectangulaire, la valeur par défaut est 20 |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | Définit le nombre de segments tubulaires du tore, la valeur par défaut est 20 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


Construisez une instance de [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


Construisez une instance de [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions)

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
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


Obtient le préfixe des attributs qui ont été définis dans des fichiers d'attributs externes. Le préfixe est utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:"

**Returns:**
java.lang.String - le préfixe des attributs qui ont été définis dans des fichiers d'attributs externes, Le préfixe est utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:"
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


Centrer la scène après son chargement.

**Returns:**
boolean - Centrer la scène après son chargement.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCylinderRadialSegments() {#getCylinderRadialSegments--}
```
public int getCylinderRadialSegments()
```


Obtient le nombre de segments radiaux du cylindre, la valeur par défaut est 16

**Returns:**
int - le nombre de segments radiaux du cylindre, valeur par défaut 16
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


Obtient le nombre de segments de latitude du plat, la valeur par défaut est 8

**Returns:**
int - le nombre de segments de latitude du plat, valeur par défaut 8
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


Obtient le nombre de segments de longitude du plat, la valeur par défaut est 12

**Returns:**
int - le nombre de segments de longitude du plat, valeur par défaut 12
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Obtient le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.

**Returns:**
java.nio.charset.Charset - le codage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera du codage à utiliser.
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
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


Générer des matériaux avec des couleurs aléatoires pour chaque objet dans la scène si la table de couleurs n'est pas exportée dans le fichier RVM. La valeur par défaut est true

**Returns:**
boolean - Générer des matériaux avec des couleurs aléatoires pour chaque objet dans la scène si la table de couleurs n'est pas exportée dans le fichier RVM. La valeur par défaut est true
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


Obtient si les attributs doivent être chargés depuis un fichier de liste d'attributs externe (.att/.attrib/.txt), la valeur par défaut est true.

**Returns:**
boolean - indiquer si les attributs doivent être chargés depuis un fichier de liste d'attributs externe (.att/.attrib/.txt), valeur par défaut true.
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
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


Obtient le nombre de segments radiaux du tore rectangulaire, la valeur par défaut est 20

**Returns:**
int - le nombre de segments radiaux du tore rectangulaire, valeur par défaut 20
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


Obtient le nombre de segments tubulaires du tore, la valeur par défaut est 20

**Returns:**
int - le nombre de segments tubulaires du tore, valeur par défaut 20
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




### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


Définit le préfixe des attributs qui ont été définis dans des fichiers d'attributs externes. Le préfixe est utilisé pour éviter les conflits de noms, la valeur par défaut est "rvm:"

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.lang.String | Nouvelle valeur |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


Centrer la scène après son chargement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


Définit le nombre de segments radiaux du cylindre, la valeur par défaut est 16

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


Définit le nombre de segments de latitude du plat, la valeur par défaut est 8

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


Définit le nombre de segments de longitude du plat, la valeur par défaut est 12

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Définit l'encodage par défaut pour les fichiers texte. La valeur par défaut est null, ce qui signifie que l'importateur/exportateur décidera de l'encodage à utiliser.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.nio.charset.Charset | Nouvelle valeur |

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

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


Générer des matériaux avec des couleurs aléatoires pour chaque objet dans la scène si la table de couleurs n'est pas exportée dans le fichier RVM. La valeur par défaut est true

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


Définit si les attributs doivent être chargés depuis un fichier de liste d'attributs externe (.att/.attrib/.txt), la valeur par défaut est true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | boolean | Nouvelle valeur |

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

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


Définit le nombre de segments radiaux du tore rectangulaire, la valeur par défaut est 20

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


Définit le nombre de segments tubulaires du tore, la valeur par défaut est 20

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | Nouvelle valeur |

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

