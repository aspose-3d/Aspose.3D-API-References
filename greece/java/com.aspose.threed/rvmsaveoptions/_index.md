---
title: RvmSaveOptions
second_title: Aspose.3D for Java API Reference
description: Επιλογές αποθήκευσης για το αρχείο RVM του Avea PDMS.
type: docs
weight: 158
url: /el/java/com.aspose.threed/rvmsaveoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.SaveOptions](../../com.aspose.threed/saveoptions)
```
public class RvmSaveOptions extends SaveOptions
```

Επιλογές αποθήκευσης για αρχείο Aveva PDMS RVM. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε το χαρακτηριστικό σε RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [RvmSaveOptions()](#RvmSaveOptions--) | Κατασκευαστής της [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) |
| [RvmSaveOptions(FileContentType contentType)](#RvmSaveOptions-com.aspose.threed.FileContentType-) | Κατασκευαστής της [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributeListFile()](#getAttributeListFile--) | Αποκτά το όνομα αρχείου της λίστας χαρακτηριστικών, ο εξαγωγέας θα δημιουργήσει ένα όνομα βασισμένο στο όνομα του αρχείου .rvm όταν αυτή η ιδιότητα είναι ακαθόριστη, η προεπιλεγμένη τιμή είναι null. |
| [getAttributePrefix()](#getAttributePrefix--) | Αποκτά το πρόθεμα των χαρακτηριστικών που θα εξαχθούν, η εξαχθείσα ιδιότητα δεν θα περιέχει πρόθεμα, προσαρμοσμένες ιδιότητες με διαφορετικό πρόθεμα δεν θα εξαχθούν, η προεπιλεγμένη τιμή είναι 'rvm:'. |
| [getAuthor()](#getAuthor--) | Πληροφορίες συγγραφέα, η προεπιλεγμένη τιμή είναι '3d@aspose' |
| [getClass()](#getClass--) |  |
| [getCreationTime()](#getCreationTime--) | Η χρονική σήμανση που εξήγαγε αυτό το αρχείο, η προεπιλεγμένη τιμή είναι η τρέχουσα ώρα |
| [getEncoding()](#getEncoding--) | Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [getExportAttributes()](#getExportAttributes--) | Λαμβάνει αν θα εξαχθεί η λίστα χαρακτηριστικών σε εξωτερικό αρχείο .att, η προεπιλεγμένη τιμή είναι false. |
| [getExportTextures()](#getExportTextures--) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [getFileName()](#getFileName--) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [getFileNote()](#getFileNote--) | Σημείωση αρχείου στην κεφαλίδα του αρχείου. |
| [getFileSystem()](#getFileSystem--) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Λαμβάνει την κλάση εργοστασίου για το FileSystem. |
| [getLookupPaths()](#getLookupPaths--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributeListFile(String value)](#setAttributeListFile-java.lang.String-) | Ορίζει το όνομα αρχείου της λίστας χαρακτηριστικών, ο εξαγωγέας θα δημιουργήσει ένα όνομα βάσει του ονόματος του αρχείου .rvm όταν αυτή η ιδιότητα είναι ακαθόριστη, η προεπιλεγμένη τιμή είναι null. |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | Ορίζει το πρόθεμα των χαρακτηριστικών που θα εξαχθούν, η εξαγόμενη ιδιότητα δεν θα περιέχει πρόθεμα, προσαρμοσμένες ιδιότητες με διαφορετικό πρόθεμα δεν θα εξαχθούν, η προεπιλεγμένη τιμή είναι 'rvm:'. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Πληροφορίες συγγραφέα, η προεπιλεγμένη τιμή είναι '3d@aspose' |
| [setCreationTime(String value)](#setCreationTime-java.lang.String-) | Η χρονική σήμανση που εξήγαγε αυτό το αρχείο, η προεπιλεγμένη τιμή είναι η τρέχουσα ώρα |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [setExportAttributes(boolean value)](#setExportAttributes-boolean-) | Ορίζει αν θα εξαχθεί η λίστα χαρακτηριστικών σε εξωτερικό αρχείο .att, η προεπιλεγμένη τιμή είναι false. |
| [setExportTextures(boolean value)](#setExportTextures-boolean-) | Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [setFileNote(String value)](#setFileNote-java.lang.String-) | Σημείωση αρχείου στην κεφαλίδα του αρχείου. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ορίζει την κλάση εργοστασίου για το FileSystem. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmSaveOptions() {#RvmSaveOptions--}
```
public RvmSaveOptions()
```


Κατασκευαστής της [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions)

### RvmSaveOptions(FileContentType contentType) {#RvmSaveOptions-com.aspose.threed.FileContentType-}
```
public RvmSaveOptions(FileContentType contentType)
```


Κατασκευαστής της [RvmSaveOptions](../../com.aspose.threed/rvmsaveoptions)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) | Αρχείο RVM κειμένου ή δυαδικό? |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAttributeListFile() {#getAttributeListFile--}
```
public String getAttributeListFile()
```


Αποκτά το όνομα αρχείου της λίστας χαρακτηριστικών, ο εξαγωγέας θα δημιουργήσει ένα όνομα βασισμένο στο όνομα του αρχείου .rvm όταν αυτή η ιδιότητα είναι ακαθόριστη, η προεπιλεγμένη τιμή είναι null.

**Returns:**
java.lang.String - το όνομα αρχείου της λίστας χαρακτηριστικών, ο εξαγωγέας θα δημιουργήσει ένα όνομα βάσει του ονόματος του αρχείου .rvm όταν αυτή η ιδιότητα είναι ακαθόριστη, η προεπιλεγμένη τιμή είναι null. **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


Λαμβάνει το πρόθεμα των χαρακτηριστικών που θα εξαχθούν, η εξαγόμενη ιδιότητα δεν θα περιέχει πρόθεμα, προσαρμοσμένες ιδιότητες με διαφορετικό πρόθεμα δεν θα εξαχθούν, η προεπιλεγμένη τιμή είναι 'rvm:'. Για παράδειγμα, αν μια ιδιότητα είναι rvm:Refno=345, το εξαγόμενο χαρακτηριστικό θα είναι Refno = 345, το πρόθεμα αφαιρείται.

**Returns:**
java.lang.String - το πρόθεμα των χαρακτηριστικών που θα εξαχθούν, η εξαγόμενη ιδιότητα δεν θα περιέχει πρόθεμα, προσαρμοσμένες ιδιότητες με διαφορετικό πρόθεμα δεν θα εξαχθούν, η προεπιλεγμένη τιμή είναι 'rvm:'. Για παράδειγμα, αν μια ιδιότητα είναι rvm:Refno=345, το εξαγόμενο χαρακτηριστικό θα είναι Refno = 345, το πρόθεμα αφαιρείται. **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getAuthor() {#getAuthor--}
```
public String getAuthor()
```


Πληροφορίες συγγραφέα, η προεπιλεγμένη τιμή είναι '3d@aspose'

**Returns:**
java.lang.String - Πληροφορίες συγγραφέα, η προεπιλεγμένη τιμή είναι '3d@aspose' **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCreationTime() {#getCreationTime--}
```
public String getCreationTime()
```


Η χρονική σήμανση που εξήγαγε αυτό το αρχείο, η προεπιλεγμένη τιμή είναι η τρέχουσα ώρα

**Returns:**
java.lang.String - Η χρονική σήμανση που εξήγαγε αυτό το αρχείο, η προεπιλεγμένη τιμή είναι η τρέχουσα ώρα
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.

**Returns:**
java.nio.charset.Charset - η προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.
### getExportAttributes() {#getExportAttributes--}
```
public boolean getExportAttributes()
```


Λαμβάνει αν θα εξαχθεί η λίστα χαρακτηριστικών σε εξωτερικό αρχείο .att, η προεπιλεγμένη τιμή είναι false.

**Returns:**
boolean - αν θα εξαχθεί η λίστα χαρακτηριστικών σε εξωτερικό αρχείο .att, η προεπιλεγμένη τιμή είναι false. **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getExportTextures() {#getExportTextures--}
```
public boolean getExportTextures()
```


Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.

**Returns:**
boolean - Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.
### getFileFormat() {#getFileFormat--}
```
public FileFormat getFileFormat()
```


Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης.

**Returns:**
[FileFormat](../../com.aspose.threed/fileformat) - the file format that specified in current Save/Load option.
### getFileName() {#getFileName--}
```
public String getFileName()
```


Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ.

**Returns:**
java.lang.String - Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ.
### getFileNote() {#getFileNote--}
```
public String getFileNote()
```


Σημείωση αρχείου στην κεφαλίδα του αρχείου.

**Returns:**
java.lang.String - Σημείωση αρχείου στην κεφαλίδα του αρχείου. **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM.

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
```
### getFileSystem() {#getFileSystem--}
```
public FileSystem getFileSystem()
```


Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - Allow user to handle how to manage the external dependencies during load/save. **Example:** The default FileSystem is LocalFileSystem, it is not safe in environment like server side, But you can override the file system access by specifying a different implementation. Aspose.3D provides different FileSystem implementation like:

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Και μπορείτε επίσης να χρησιμοποιήσετε τη δική σας υλοποίηση.

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


Λαμβάνει την κλάση εργοστασίου για το FileSystem. Το προεπιλεγμένο εργοστάσιο θα δημιουργήσει το com.aspose.threed.LocalFileSystem, το οποίο δεν είναι κατάλληλο για περιβάλλον διακομιστή.

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
### getLookupPaths() {#getLookupPaths--}
```
public ArrayList<String> getLookupPaths()
```


Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση.

**Returns:**
java.util.ArrayList<java.lang.String> - Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέψουν στο Aspose.3D να ψάξει για εξωτερικό αρχείο προς φόρτωση. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να καθορίσετε χειροκίνητα τις υφές αναζήτησης, ώστε ο εισαγωγέας να τις βρει

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




### setAttributeListFile(String value) {#setAttributeListFile-java.lang.String-}
```
public void setAttributeListFile(String value)
```


Ορίζει το όνομα αρχείου της λίστας χαρακτηριστικών, ο εξαγωγέας θα δημιουργήσει ένα όνομα βάσει του ονόματος του αρχείου .rvm όταν αυτή η ιδιότητα είναι ακαθόριστη, η προεπιλεγμένη τιμή είναι null.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Νέα τιμή **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAttributePrefix(String value) {#setAttributePrefix-java.lang.String-}
```
public void setAttributePrefix(String value)
```


Ορίζει το πρόθεμα των χαρακτηριστικών που θα εξαχθούν, η εξαγόμενη ιδιότητα δεν θα περιέχει πρόθεμα, προσαρμοσμένες ιδιότητες με διαφορετικό πρόθεμα δεν θα εξαχθούν, η προεπιλεγμένη τιμή είναι 'rvm:'. Για παράδειγμα, αν μια ιδιότητα είναι rvm:Refno=345, το εξαγόμενο χαρακτηριστικό θα είναι Refno = 345, το πρόθεμα αφαιρείται.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Νέα τιμή **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public void setAuthor(String value)
```


Πληροφορίες συγγραφέα, η προεπιλεγμένη τιμή είναι '3d@aspose'

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Νέα τιμή **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setCreationTime(String value) {#setCreationTime-java.lang.String-}
```
public void setCreationTime(String value)
```


Η χρονική σήμανση που εξήγαγε αυτό το αρχείο, η προεπιλεγμένη τιμή είναι η τρέχουσα ώρα

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιήσει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset | Νέα τιμή |

### setExportAttributes(boolean value) {#setExportAttributes-boolean-}
```
public void setExportAttributes(boolean value)
```


Ορίζει αν θα εξαχθεί η λίστα χαρακτηριστικών σε εξωτερικό αρχείο .att, η προεπιλεγμένη τιμή είναι false.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | boolean | Νέα τιμή **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setExportTextures(boolean value) {#setExportTextures-boolean-}
```
public void setExportTextures(boolean value)
```


Προσπάθεια αντιγραφής των υφών που χρησιμοποιούνται στη σκηνή στον φάκελο εξόδου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setFileNote(String value) {#setFileNote-java.lang.String-}
```
public void setFileNote(String value)
```


Σημείωση αρχείου στην κεφαλίδα του αρχείου.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.lang.String | Νέα τιμή **Example:** Ο παρακάτω κώδικας δείχνει πώς να εξάγετε χαρακτηριστικό σε RVM. |

```
Scene scene = new Scene();
             var box = (new Box()).toMesh();
             //node's name is required to export attributes
             var boxNode = scene.getRootNode().createChildNode("box", box);
             boxNode.setProperty("rvm:Price", 12.0);
             boxNode.setProperty("rvm:Weight", 30.0);
             var opt = new RvmSaveOptions();
             //Properties with rvm: prefix will be exported.
             opt.setExportAttributes(true);
             opt.setAttributePrefix("rvm:");
             opt.setAuthor("Aspose.3D");
             opt.setFileNote("Test attribute export");
             scene.save("output.rvm", opt);
``` |

### setFileSystem(FileSystem value) {#setFileSystem-com.aspose.threed.FileSystem-}
```
public void setFileSystem(FileSystem value)
```


Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [FileSystem](../../com.aspose.threed/filesystem) | Νέα τιμή **Παράδειγμα:** Το προεπιλεγμένο FileSystem είναι το LocalFileSystem, δεν είναι ασφαλές σε περιβάλλον όπως η πλευρά του διακομιστή, αλλά μπορείτε να παρακάμψετε την πρόσβαση στο σύστημα αρχείων καθορίζοντας διαφορετική υλοποίηση. Το Aspose.3D παρέχει διαφορετικές υλοποιήσεις FileSystem όπως: |

 *  Memory-based file system
 *  Directory-based file system
 *  Dummy file system
 *  Zip file system

Και μπορείτε επίσης να χρησιμοποιήσετε τη δική σας υλοποίηση.

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


Ορίζει την κλάση εργοστασίου για το FileSystem. Το προεπιλεγμένο εργοστάσιο θα δημιουργήσει το com.aspose.threed.LocalFileSystem, το οποίο δεν είναι κατάλληλο για περιβάλλον διακομιστή.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | value | [FileSystemFactory](../../com.aspose.threed/filesystemfactory) | Νέα τιμή **Παράδειγμα:** Το προεπιλεγμένο FileSystem στα SaveOptions/LoadOptions είναι σύστημα αρχείων βασισμένο σε κατάλογο, μπορείτε να παρακάμψετε την προεπιλεγμένη υλοποίηση καθορίζοντάς το μέσω του IOConfig.FileSystemFactory: |

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

### setLookupPaths(ArrayList<String> value) {#setLookupPaths-java.util.ArrayList-java.lang.String--}
```
public void setLookupPaths(ArrayList<String> value)
```


Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
|  | τιμή | java.util.ArrayList<java.lang.String> | Νέα τιμή **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να καθορίσετε χειροκίνητα τις υφές αναζήτησης, ώστε ο εισαγωγέας να τις βρει |

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
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

