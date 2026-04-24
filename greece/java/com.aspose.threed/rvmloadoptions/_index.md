---
title: RvmLoadOptions
second_title: Aspose.3D for Java API Reference
description: Επιλογές φόρτωσης για το αρχείο RVM του AVEVA Plant Design Management Systems.
type: docs
weight: 157
url: /el/java/com.aspose.threed/rvmloadoptions/
---

**Inheritance:**
java.lang.Object, [com.aspose.threed.IOConfig](../../com.aspose.threed/ioconfig), [com.aspose.threed.LoadOptions](../../com.aspose.threed/loadoptions)
```
public class RvmLoadOptions extends LoadOptions
```

Επιλογές φόρτωσης για το αρχείο RVM του AVEVA Plant Design Management System. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να προσαρμόσετε τις παραμέτρους τεσσαριάσματος για πρωτόγονες γεωμετρίες που εισάγονται από αρχείο RVM χρησιμοποιώντας RvmLoadOptions.

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
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [RvmLoadOptions(FileContentType contentType)](#RvmLoadOptions-com.aspose.threed.FileContentType-) | Δημιουργήστε μια παρουσία του [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) |
| [RvmLoadOptions()](#RvmLoadOptions--) | Δημιουργήστε μια παρουσία του [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions) |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAttributePrefix()](#getAttributePrefix--) | Λαμβάνει το πρόθεμα των χαρακτηριστικών που ορίστηκαν σε εξωτερικά αρχεία χαρακτηριστικών, το πρόθεμα χρησιμοποιείται για την αποφυγή συγκρούσεων ονομάτων, η προεπιλεγμένη τιμή είναι "rvm:" |
| [getCenterScene()](#getCenterScene--) | Κεντράρετε τη σκηνή μετά τη φόρτωση. |
| [getClass()](#getClass--) |  |
| [getCylinderRadialSegments()](#getCylinderRadialSegments--) | Λαμβάνει τον αριθμό των ακτινικών τμημάτων του κυλίνδρου, η προεπιλεγμένη τιμή είναι 16 |
| [getDishLatitudeSegments()](#getDishLatitudeSegments--) | Λαμβάνει τον αριθμό των τμημάτων γεωγραφικού πλάτους του πιάτου, η προεπιλεγμένη τιμή είναι 8 |
| [getDishLongitudeSegments()](#getDishLongitudeSegments--) | Λαμβάνει τον αριθμό των τμημάτων γεωγραφικού μήκους του πιάτου, η προεπιλεγμένη τιμή είναι 12 |
| [getEncoding()](#getEncoding--) | Λαμβάνει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [getFileFormat()](#getFileFormat--) | Λαμβάνει τη μορφή αρχείου που καθορίζεται στην τρέχουσα επιλογή Αποθήκευσης/Φόρτωσης. |
| [getFileName()](#getFileName--) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [getFileSystem()](#getFileSystem--) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [getFileSystemFactory()](#getFileSystemFactory--) | Λαμβάνει την κλάση εργοστασίου για το FileSystem. |
| [getGenerateMaterials()](#getGenerateMaterials--) | Δημιουργήστε υλικά με τυχαία χρώματα για κάθε αντικείμενο στη σκηνή εάν ο πίνακας χρωμάτων δεν εξάγεται μέσα στο αρχείο RVM. |
| [getLookupAttributes()](#getLookupAttributes--) | Λαμβάνει αν θα φορτωθούν χαρακτηριστικά από εξωτερικό αρχείο λίστας χαρακτηριστικών (.att/.attrib/.txt), η προεπιλεγμένη τιμή είναι true. |
| [getLookupPaths()](#getLookupPaths--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [getRectangularTorusSegments()](#getRectangularTorusSegments--) | Λαμβάνει τον αριθμό των ακτινικών τμημάτων του ορθογώνιου δακτυλίου, η προεπιλεγμένη τιμή είναι 20 |
| [getTorusTubularSegments()](#getTorusTubularSegments--) | Λαμβάνει τον αριθμό των σωληνικών τμημάτων του δακτυλίου, η προεπιλεγμένη τιμή είναι 20 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAttributePrefix(String value)](#setAttributePrefix-java.lang.String-) | Ορίζει το πρόθεμα των χαρακτηριστικών που ορίστηκαν σε εξωτερικά αρχεία χαρακτηριστικών, το πρόθεμα χρησιμοποιείται για την αποφυγή συγκρούσεων ονομάτων, η προεπιλεγμένη τιμή είναι "rvm:" |
| [setCenterScene(boolean value)](#setCenterScene-boolean-) | Κεντράρετε τη σκηνή μετά τη φόρτωση. |
| [setCylinderRadialSegments(int value)](#setCylinderRadialSegments-int-) | Ορίζει τον αριθμό των ακτινικών τμημάτων του κυλίνδρου, η προεπιλεγμένη τιμή είναι 16 |
| [setDishLatitudeSegments(int value)](#setDishLatitudeSegments-int-) | Ορίζει τον αριθμό των τμημάτων γεωγραφικού πλάτους του πιάτου, η προεπιλεγμένη τιμή είναι 8 |
| [setDishLongitudeSegments(int value)](#setDishLongitudeSegments-int-) | Ορίζει τον αριθμό των τμημάτων γεωγραφικού μήκους του πιάτου, η προεπιλεγμένη τιμή είναι 12 |
| [setEncoding(Charset value)](#setEncoding-java.nio.charset.Charset-) | Ορίζει την προεπιλεγμένη κωδικοποίηση για αρχεία κειμένου. |
| [setFileName(String value)](#setFileName-java.lang.String-) | Το όνομα αρχείου της εξαγόμενης/εισαγόμενης σκηνής. |
| [setFileSystem(FileSystem value)](#setFileSystem-com.aspose.threed.FileSystem-) | Επιτρέπει στον χρήστη να διαχειριστεί πώς να διαχειρίζεται τις εξωτερικές εξαρτήσεις κατά τη φόρτωση/αποθήκευση. |
| [setFileSystemFactory(FileSystemFactory value)](#setFileSystemFactory-com.aspose.threed.FileSystemFactory-) | Ορίζει την κλάση εργοστασίου για το FileSystem. |
| [setGenerateMaterials(boolean value)](#setGenerateMaterials-boolean-) | Δημιουργήστε υλικά με τυχαία χρώματα για κάθε αντικείμενο στη σκηνή εάν ο πίνακας χρωμάτων δεν εξάγεται μέσα στο αρχείο RVM. |
| [setLookupAttributes(boolean value)](#setLookupAttributes-boolean-) | Ορίζει αν θα φορτωθούν χαρακτηριστικά από εξωτερικό αρχείο λίστας χαρακτηριστικών (.att/.attrib/.txt), η προεπιλεγμένη τιμή είναι true. |
| [setLookupPaths(ArrayList<String> value)](#setLookupPaths-java.util.ArrayList-java.lang.String--) | Ορισμένα αρχεία όπως το OBJ εξαρτώνται από εξωτερικό αρχείο, οι διαδρομές αναζήτησης θα επιτρέπουν στο Aspose.3D να αναζητήσει εξωτερικό αρχείο για φόρτωση. |
| [setRectangularTorusSegments(int value)](#setRectangularTorusSegments-int-) | Ορίζει τον αριθμό των ακτινικών τμημάτων του ορθογώνιου δακτυλίου, η προεπιλεγμένη τιμή είναι 20 |
| [setTorusTubularSegments(int value)](#setTorusTubularSegments-int-) | Ορίζει τον αριθμό των σωληνικών τμημάτων του δακτυλίου, η προεπιλεγμένη τιμή είναι 20 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### RvmLoadOptions(FileContentType contentType) {#RvmLoadOptions-com.aspose.threed.FileContentType-}
```
public RvmLoadOptions(FileContentType contentType)
```


Δημιουργήστε μια παρουσία του [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| contentType | [FileContentType](../../com.aspose.threed/filecontenttype) |  |

### RvmLoadOptions() {#RvmLoadOptions--}
```
public RvmLoadOptions()
```


Δημιουργήστε μια παρουσία του [RvmLoadOptions](../../com.aspose.threed/rvmloadoptions)

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
### getAttributePrefix() {#getAttributePrefix--}
```
public String getAttributePrefix()
```


Λαμβάνει το πρόθεμα των χαρακτηριστικών που ορίστηκαν σε εξωτερικά αρχεία χαρακτηριστικών, το πρόθεμα χρησιμοποιείται για την αποφυγή συγκρούσεων ονομάτων, η προεπιλεγμένη τιμή είναι "rvm:"

**Returns:**
java.lang.String - το πρόθεμα των χαρακτηριστικών που ορίστηκαν σε εξωτερικά αρχεία χαρακτηριστικών, Το πρόθεμα χρησιμοποιείται για την αποφυγή συγκρούσεων ονομάτων, η προεπιλεγμένη τιμή είναι "rvm:"
### getCenterScene() {#getCenterScene--}
```
public boolean getCenterScene()
```


Κεντράρετε τη σκηνή μετά τη φόρτωση.

**Returns:**
boolean - Κεντράρετε τη σκηνή μετά τη φόρτωσή της.
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


Λαμβάνει τον αριθμό των ακτινικών τμημάτων του κυλίνδρου, η προεπιλεγμένη τιμή είναι 16

**Returns:**
int - ο αριθμός των ακτινικών τμημάτων του κυλίνδρου, η προεπιλεγμένη τιμή είναι 16
### getDishLatitudeSegments() {#getDishLatitudeSegments--}
```
public int getDishLatitudeSegments()
```


Λαμβάνει τον αριθμό των τμημάτων γεωγραφικού πλάτους του πιάτου, η προεπιλεγμένη τιμή είναι 8

**Returns:**
int - ο αριθμός των τμημάτων γεωγραφικού πλάτους του πιάτου, η προεπιλεγμένη τιμή είναι 8
### getDishLongitudeSegments() {#getDishLongitudeSegments--}
```
public int getDishLongitudeSegments()
```


Λαμβάνει τον αριθμό των τμημάτων γεωγραφικού μήκους του πιάτου, η προεπιλεγμένη τιμή είναι 12

**Returns:**
int - ο αριθμός των τμημάτων γεωγραφικού μήκους του πιάτου, η προεπιλεγμένη τιμή είναι 12
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
### getGenerateMaterials() {#getGenerateMaterials--}
```
public boolean getGenerateMaterials()
```


Δημιουργήστε υλικά με τυχαία χρώματα για κάθε αντικείμενο στη σκηνή εάν ο πίνακας χρωμάτων δεν έχει εξαχθεί στο αρχείο RVM. Η προεπιλεγμένη τιμή είναι true

**Returns:**
boolean - Δημιουργήστε υλικά με τυχαία χρώματα για κάθε αντικείμενο στη σκηνή εάν ο πίνακας χρωμάτων δεν έχει εξαχθεί στο αρχείο RVM. Η προεπιλεγμένη τιμή είναι true
### getLookupAttributes() {#getLookupAttributes--}
```
public boolean getLookupAttributes()
```


Λαμβάνει αν θα φορτωθούν χαρακτηριστικά από εξωτερικό αρχείο λίστας χαρακτηριστικών (.att/.attrib/.txt), η προεπιλεγμένη τιμή είναι true.

**Returns:**
boolean - αν θα φορτωθούν χαρακτηριστικά από εξωτερικό αρχείο λίστας χαρακτηριστικών (.att/.attrib/.txt), η προεπιλεγμένη τιμή είναι true.
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
### getRectangularTorusSegments() {#getRectangularTorusSegments--}
```
public int getRectangularTorusSegments()
```


Λαμβάνει τον αριθμό των ακτινικών τμημάτων του ορθογώνιου δακτυλίου, η προεπιλεγμένη τιμή είναι 20

**Returns:**
int - ο αριθμός των ακτινικών τμημάτων του ορθογώνιου δακτυλίου, η προεπιλεγμένη τιμή είναι 20
### getTorusTubularSegments() {#getTorusTubularSegments--}
```
public int getTorusTubularSegments()
```


Λαμβάνει τον αριθμό των σωληνικών τμημάτων του δακτυλίου, η προεπιλεγμένη τιμή είναι 20

**Returns:**
int - ο αριθμός των σωληνικών τμημάτων του δακτυλίου, η προεπιλεγμένη τιμή είναι 20
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


Ορίζει το πρόθεμα των χαρακτηριστικών που ορίστηκαν σε εξωτερικά αρχεία χαρακτηριστικών, το πρόθεμα χρησιμοποιείται για την αποφυγή συγκρούσεων ονομάτων, η προεπιλεγμένη τιμή είναι "rvm:"

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | java.lang.String | Νέα τιμή |

### setCenterScene(boolean value) {#setCenterScene-boolean-}
```
public void setCenterScene(boolean value)
```


Κεντράρετε τη σκηνή μετά τη φόρτωση.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setCylinderRadialSegments(int value) {#setCylinderRadialSegments-int-}
```
public void setCylinderRadialSegments(int value)
```


Ορίζει τον αριθμό των ακτινικών τμημάτων του κυλίνδρου, η προεπιλεγμένη τιμή είναι 16

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setDishLatitudeSegments(int value) {#setDishLatitudeSegments-int-}
```
public void setDishLatitudeSegments(int value)
```


Ορίζει τον αριθμό των τμημάτων γεωγραφικού πλάτους του πιάτου, η προεπιλεγμένη τιμή είναι 8

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setDishLongitudeSegments(int value) {#setDishLongitudeSegments-int-}
```
public void setDishLongitudeSegments(int value)
```


Ορίζει τον αριθμό των τμημάτων γεωγραφικού μήκους του πιάτου, η προεπιλεγμένη τιμή είναι 12

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

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

### setGenerateMaterials(boolean value) {#setGenerateMaterials-boolean-}
```
public void setGenerateMaterials(boolean value)
```


Δημιουργήστε υλικά με τυχαία χρώματα για κάθε αντικείμενο στη σκηνή εάν ο πίνακας χρωμάτων δεν έχει εξαχθεί στο αρχείο RVM. Η προεπιλεγμένη τιμή είναι true

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | boolean | Νέα τιμή |

### setLookupAttributes(boolean value) {#setLookupAttributes-boolean-}
```
public void setLookupAttributes(boolean value)
```


Ορίζει αν θα φορτωθούν χαρακτηριστικά από εξωτερικό αρχείο λίστας χαρακτηριστικών (.att/.attrib/.txt), η προεπιλεγμένη τιμή είναι true.

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

### setRectangularTorusSegments(int value) {#setRectangularTorusSegments-int-}
```
public void setRectangularTorusSegments(int value)
```


Ορίζει τον αριθμό των ακτινικών τμημάτων του ορθογώνιου δακτυλίου, η προεπιλεγμένη τιμή είναι 20

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

### setTorusTubularSegments(int value) {#setTorusTubularSegments-int-}
```
public void setTorusTubularSegments(int value)
```


Ορίζει τον αριθμό των σωληνικών τμημάτων του δακτυλίου, η προεπιλεγμένη τιμή είναι 20

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| τιμή | int | Νέα τιμή |

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

