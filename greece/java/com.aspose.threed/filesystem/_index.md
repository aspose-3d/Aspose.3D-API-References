---
title: FileSystem
second_title: Aspose.3D for Java API Reference
description: File system encapsulation.
type: docs
weight: 67
url: /el/java/com.aspose.threed/filesystem/
---

**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.io.Closeable
```
public abstract class FileSystem implements Closeable
```

Ενσωμάτωση συστήματος αρχείων. Aspose.3D θα το χρησιμοποιήσει για ανάγνωση/εγγραφή εξαρτήσεων. **Παράδειγμα:** Ο παρακάτω κώδικας δείχνει πώς να εισάγετε αρχείο και να παρέχετε εξαρτημένα αρχεία σε έναν συγκεκριμένο φάκελο

```
var inputFile = "input.fbx";
     var format = FileFormat.detect(inputFile);
     //create a load options instance and specify a zip file system
     var opt = format.createLoadOptions();
     opt.setFileSystem(new LocalFileSystem("textures/"));
     //load the file
     var scene = Scene.fromFile(inputFile, opt);
```
## Constructors

| Constructor | Περιγραφή |
| --- | --- |
| [FileSystem()](#FileSystem--) |  |
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [close()](#close--) | Αποδεσμεύστε το σύστημα αρχείων και απελευθερώστε τους πόρους του. |
| [createDummyFileSystem()](#createDummyFileSystem--) | Δημιουργήστε ένα εικονικό σύστημα αρχείων, οι λειτουργίες ανάγνωσης/εγγραφής είναι εικονικές. |
| [createLocalFileSystem(String directory)](#createLocalFileSystem-java.lang.String-) | Αρχικοποιήστε ένα νέο [FileSystem](../../com.aspose.threed/filesystem) που έχει πρόσβαση μόνο σε τοπικό φάκελο. |
| [createMemoryFileSystem()](#createMemoryFileSystem--) | Δημιουργήστε ένα σύστημα αρχείων βασισμένο στη μνήμη, το οποίο θα αντιστοιχίσει τις λειτουργίες ανάγνωσης/εγγραφής στη μνήμη. |
| [createMemoryFileSystem(HashMap<String,MemoryStream> files)](#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--) | Δημιουργήστε ένα σύστημα αρχείων βασισμένο στη μνήμη, το οποίο θα αντιστοιχίσει τις λειτουργίες ανάγνωσης/εγγραφής στη μνήμη. |
| [createZipFileSystem(Stream stream)](#createZipFileSystem-com.aspose.threed.Stream-) | Δημιουργήστε ένα σύστημα αρχείων για να παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. |
| [createZipFileSystem(Stream stream, String baseDir)](#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-) | Δημιουργήστε ένα σύστημα αρχείων για να παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. |
| [createZipFileSystem(String fileName)](#createZipFileSystem-java.lang.String-) | Σύστημα αρχείων που παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readFile(String fileName, IOConfig options)](#readFile-java.lang.String-com.aspose.threed.IOConfig-) | Δημιουργήστε μια ροή για την ανάγνωση εξαρτήσεων. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
| [writeFile(String fileName, IOConfig options)](#writeFile-java.lang.String-com.aspose.threed.IOConfig-) | Δημιουργήστε μια ροή για τη γραφή εξαρτήσεων. |
### FileSystem() {#FileSystem--}
```
public FileSystem()
```


### close() {#close--}
```
public void close()
```


Αποδεσμεύστε το σύστημα αρχείων και απελευθερώστε τους πόρους του.

### createDummyFileSystem() {#createDummyFileSystem--}
```
public static FileSystem createDummyFileSystem()
```


Δημιουργήστε ένα εικονικό σύστημα αρχείων, οι λειτουργίες ανάγνωσης/εγγραφής είναι εικονικές.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A dummy file system **Example:** The following code shows how to export file to memory, and ignore all dependent file generation.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var dfs = FileSystem.CreateDummyFileSystem();
     opt.setFileSystem(dfs);
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
```
### createLocalFileSystem(String directory) {#createLocalFileSystem-java.lang.String-}
```
public static FileSystem createLocalFileSystem(String directory)
```


Αρχικοποιήστε ένα νέο [FileSystem](../../com.aspose.threed/filesystem) που έχει πρόσβαση μόνο σε τοπικό φάκελο. Όλες οι λειτουργίες ανάγνωσης/εγγραφής αρχείων σε αυτήν την παρουσία του FileSystem θα αντιστοιχίζονται στον καθορισμένο φάκελο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| directory | java.lang.String | Ο φάκελος στο φυσικό σας σύστημα αρχείων ως ο εικονικός ριζικός φάκελος. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A new instance of file system to provide local file access
### createMemoryFileSystem() {#createMemoryFileSystem--}
```
public static FileSystem createMemoryFileSystem()
```


Δημιουργήστε ένα σύστημα αρχείων βασισμένο στη μνήμη, το οποίο θα αντιστοιχίσει τις λειτουργίες ανάγνωσης/εγγραφής στη μνήμη.

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createMemoryFileSystem(HashMap<String,MemoryStream> files) {#createMemoryFileSystem-java.util.HashMap-java.lang.String-com.aspose.threed.MemoryStream--}
```
public static FileSystem createMemoryFileSystem(HashMap<String,MemoryStream> files)
```


Δημιουργήστε ένα σύστημα αρχείων βασισμένο στη μνήμη, το οποίο θα αντιστοιχίσει τις λειτουργίες ανάγνωσης/εγγραφής στη μνήμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| αρχεία | java.util.HashMap<java.lang.String,com.aspose.threed.MemoryStream> | Αυτό σας επιτρέπει να διαβάζετε/γράφετε τα εικονικά αρχεία. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A memory-based file system **Example:** The following code shows how to export file to memory, includes the dependent file by using MemoryFileSystem.

```
//create a scene with material
     Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box()).setMaterial(new LambertMaterial());
     //create a save option and specify the file system, so the dependent file will be written to memory
     var opt = FileFormat.WAVEFRONTOBJ.createSaveOptions();
     var mfs = new HashMap<String, MemoryStream>();
     opt.setFileSystem(FileSystem.createMemoryFileSystem(mfs));
     //obj's material file name is associated with the obj's file name, so we need a explicit name.
     opt.setFileName("test.obj");
     try (var ms = new MemoryStream())
     {
         scene.save(ms, opt);
     }
     //the test.obj was written to variable ms, and we can also get the test.mtl file content by
     var materialFile = mfs.get("test.mtl");
```
### createZipFileSystem(Stream stream) {#createZipFileSystem-com.aspose.threed.Stream-}
```
public static FileSystem createZipFileSystem(Stream stream)
```


Δημιουργήστε ένα σύστημα αρχείων για να παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα διαγραφεί μετά τη λειτουργία ανοίγματος/αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Η ροή για πρόσβαση στο αρχείο zip |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(Stream stream, String baseDir) {#createZipFileSystem-com.aspose.threed.Stream-java.lang.String-}
```
public static FileSystem createZipFileSystem(Stream stream, String baseDir)
```


Δημιουργήστε ένα σύστημα αρχείων για να παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα διαγραφεί μετά τη λειτουργία ανοίγματος/αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | Η ροή για πρόσβαση στο αρχείο zip |
| baseDir | java.lang.String | Ο βασικός φάκελος μέσα στο αρχείο zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
### createZipFileSystem(String fileName) {#createZipFileSystem-java.lang.String-}
```
public static FileSystem createZipFileSystem(String fileName)
```


Σύστημα αρχείων για να παρέχει πρόσβαση μόνο για ανάγνωση σε καθορισμένο αρχείο zip ή ροή zip. Το σύστημα αρχείων θα διαγραφεί μετά τη λειτουργία ανοίγματος/αποθήκευσης.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου για το αρχείο zip. |

**Returns:**
[FileSystem](../../com.aspose.threed/filesystem) - A zip file system
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




### readFile(String fileName, IOConfig options) {#readFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream readFile(String fileName, IOConfig options)
```


Δημιουργήστε μια ροή για την ανάγνωση εξαρτήσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Όνομα αρχείου για άνοιγμα ανάγνωσης |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Επιλογές αποθήκευσης ή φόρτωσης |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for reading the file.
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

### writeFile(String fileName, IOConfig options) {#writeFile-java.lang.String-com.aspose.threed.IOConfig-}
```
public abstract Stream writeFile(String fileName, IOConfig options)
```


Δημιουργήστε μια ροή για τη γραφή εξαρτήσεων.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileName | java.lang.String | Το όνομα του αρχείου για άνοιγμα εγγραφής |
| options | [IOConfig](../../com.aspose.threed/ioconfig) | Επιλογές αποθήκευσης ή φόρτωσης |

**Returns:**
[Stream](../../com.aspose.threed/stream) - Stream for writing the file
