---
title: ObjLoadOptions
second_title: Aspose.3D for Java API Reference
description: Επιλογές φόρτωσης για wavefront obj
type: docs
weight: 115
url: /el/java/com.aspose.threed/objloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class ObjLoadOptions extends LoadOptions
```

Επιλογές φόρτωσης για wavefront obj
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [ObjLoadOptions()](#ObjLoadOptions--) | Κατασκευαστής του [ObjLoadOptions](../../com.aspose.threed/objloadoptions) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getEnableMaterials()](#getEnableMaterials--) | Ανακτά αν εισάγει υλικά για κάθε αντικείμενο |
| [getEncoding()](#getEncoding--) | Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [getFileName()](#getFileName--) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [getFileSystem()](#getFileSystem--) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Λαμβάνει την κλάση εργοστασίου για το FileSystem. |
| [getFlipCoordinateSystem()](#getFlipCoordinateSystem--) | Ανακτά αν αντιστρέφει το σύστημα συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή |
| [getLookupPaths()](#getLookupPaths--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [getNormalizeNormal()](#getNormalizeNormal--) | Ανακτά αν κανονικοποιεί το διάνυσμα κανονικής κατά τη φόρτωση. |
| [getScale()](#getScale--) | Κλίμακες στον άξονα x/y/z, η προεπιλεγμένη τιμή είναι 1.0 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setEnableMaterials(boolean value)](#setEnableMaterials-boolean-) | Ορίζει αν εισάγει υλικά για κάθε αντικείμενο |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ορίζει την κλάση εργοστασίου για το FileSystem. |
| [setFlipCoordinateSystem(boolean value)](#setFlipCoordinateSystem-boolean-) | Ορίζει αν αντιστρέφει το σύστημα συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [setNormalizeNormal(boolean value)](#setNormalizeNormal-boolean-) | Ορίζει αν κανονικοποιεί το διάνυσμα κανονικής κατά τη φόρτωση. |
| [setScale(double value)](#setScale-double-) | Κλίμακες στον άξονα x/y/z, η προεπιλεγμένη τιμή είναι 1.0 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### ObjLoadOptions() {#ObjLoadOptions--}
```
public ObjLoadOptions()
```


Κατασκευαστής του [ObjLoadOptions](../../com.aspose.threed/objloadoptions)

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


Ανακτά αν εισάγει υλικά για κάθε αντικείμενο

**Returns:**
boolean - αν εισάγει υλικά για κάθε αντικείμενο
### getEncoding() {#getEncoding--}
```
public Charset getEncoding()
```


Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.

**Returns:**
java.nio.charset.Charset - η προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιηθεί.
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
### getFlipCoordinateSystem() {#getFlipCoordinateSystem--}
```
public boolean getFlipCoordinateSystem()
```


Ανακτά αν αντιστρέφει το σύστημα συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή

**Returns:**
boolean - αν αντιστρέφει το σύστημα συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή
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
### getNormalizeNormal() {#getNormalizeNormal--}
```
public boolean getNormalizeNormal()
```


Ανακτά αν κανονικοποιεί το διάνυσμα κανονικής κατά τη φόρτωση. Η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean - αν κανονικοποιεί το διάνυσμα κανονικής κατά τη φόρτωση. Η προεπιλεγμένη τιμή είναι true.
### getScale() {#getScale--}
```
public double getScale()
```


Κλίμακες στον άξονα x/y/z, η προεπιλεγμένη τιμή είναι 1.0

**Returns:**
double - Κλίμακες στον άξονα x/y/z, η προεπιλεγμένη τιμή είναι 1.0
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




### setEnableMaterials(boolean value) {#setEnableMaterials-boolean-}
```
public void setEnableMaterials(boolean value)
```


Ορίζει αν εισάγει υλικά για κάθε αντικείμενο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setEncoding(Charset value) {#setEncoding-java.nio.charset.Charset-}
```
public void setEncoding(Charset value)
```


Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. Η προεπιλεγμένη τιμή είναι null, που σημαίνει ότι ο εισαγωγέας/εξαγωγέας θα αποφασίσει ποια κωδικοποίηση θα χρησιμοποιήσει.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.nio.charset.Charset | Νέα τιμή |

### setFileName(String value) {#setFileName-java.lang.String-}
```
public void setFileName(String value)
```


Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. Αυτό είναι προαιρετικό, αλλά χρήσιμο όταν γίνεται σειριοποίηση εξωτερικών πόρων όπως το υλικό του OBJ.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

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

### setFlipCoordinateSystem(boolean value) {#setFlipCoordinateSystem-boolean-}
```
public void setFlipCoordinateSystem(boolean value)
```


Ορίζει αν αντιστρέφει το σύστημα συντεταγμένων των σημείων ελέγχου/κανονικών κατά την εισαγωγή

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

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

### setNormalizeNormal(boolean value) {#setNormalizeNormal-boolean-}
```
public void setNormalizeNormal(boolean value)
```


Ορίζει αν κανονικοποιεί το διάνυσμα κανονικής κατά τη φόρτωση. Η προεπιλεγμένη τιμή είναι true.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setScale(double value) {#setScale-double-}
```
public void setScale(double value)
```


Κλίμακες στον άξονα x/y/z, η προεπιλεγμένη τιμή είναι 1.0

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | double | Νέα τιμή |

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

