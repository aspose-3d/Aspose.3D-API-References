---
title: "ITextureCubemap"
second_title: "Aspose.3D for Java API Reference"
description: "Υφή χάρτη κύβου"
type: docs
weight: 255
url: /el/java/com.aspose.threed/itexturecubemap/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITextureCubemap extends ITextureUnit
```

Υφή χάρτη κύβου
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [load(CubeFace face, TextureData data)](#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Φορτώστε τα δεδομένα στο καθορισμένο πρόσωπο |
| [load(CubeFaceData<TextureData> data)](#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Φορτώστε το περιεχόμενο υφής από το καθορισμένο [TextureData](../../com.aspose.threed/texturedata) |
| [loadFromFiles(CubeFaceData<String> fileNames)](#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--) | Φορτώνει το περιεχόμενο υφής από τα καθορισμένα αρχεία |
| [save(CubeFace side, TextureData bitmap)](#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-) | Αποθηκεύει την καθορισμένη πλευρά στη μνήμη |
| [save(CubeFaceData<TextureData> bitmap)](#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--) | Αποθηκεύει το περιεχόμενο της υφής στη μνήμη. |
| [save(CubeFaceData<String> path, String format)](#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-) | Αποθηκεύει το περιεχόμενο των υφών των πλευρών του κύβου σε εξωτερικά αρχεία. |
| [toBitmap(CubeFace side)](#toBitmap-com.aspose.threed.CubeFace-) | Μετατρέψτε τη μονάδα υφής σε αντικείμενο [TextureData](../../com.aspose.threed/texturedata) |
### load(CubeFace face, TextureData data) {#load-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void load(CubeFace face, TextureData data)
```


Φορτώστε τα δεδομένα στο καθορισμένο πρόσωπο

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| face | [CubeFace](../../com.aspose.threed/cubeface) |  |
| data | [TextureData](../../com.aspose.threed/texturedata) |  |

### load(CubeFaceData<TextureData> data) {#load-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void load(CubeFaceData<TextureData> data)
```


Φορτώστε το περιεχόμενο υφής από το καθορισμένο [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δεδομένα | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> |  |

### loadFromFiles(CubeFaceData<String> fileNames) {#loadFromFiles-com.aspose.threed.CubeFaceData-java.lang.String--}
```
public abstract void loadFromFiles(CubeFaceData<String> fileNames)
```


Φορτώνει το περιεχόμενο υφής από τα καθορισμένα αρχεία

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fileNames | com.aspose.threed.CubeFaceData<java.lang.String> |  |

### save(CubeFace side, TextureData bitmap) {#save-com.aspose.threed.CubeFace-com.aspose.threed.TextureData-}
```
public abstract void save(CubeFace side, TextureData bitmap)
```


Αποθηκεύει την καθορισμένη πλευρά στη μνήμη

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(CubeFaceData<TextureData> bitmap) {#save-com.aspose.threed.CubeFaceData-com.aspose.threed.TextureData--}
```
public abstract void save(CubeFaceData<TextureData> bitmap)
```


Αποθηκεύει το περιεχόμενο της υφής στη μνήμη.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitmap | com.aspose.threed.CubeFaceData<com.aspose.threed.TextureData> | Αποτέλεσμα bitmap για αποθήκευση. |

### save(CubeFaceData<String> path, String format) {#save-com.aspose.threed.CubeFaceData-java.lang.String--java.lang.String-}
```
public abstract void save(CubeFaceData<String> path, String format)
```


Αποθηκεύει το περιεχόμενο των υφών των πλευρών του κύβου σε εξωτερικά αρχεία.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | com.aspose.threed.CubeFaceData<java.lang.String> | Ονόματα αρχείων για αποθήκευση. |
| format | java.lang.String | Μορφή εικόνας |

### toBitmap(CubeFace side) {#toBitmap-com.aspose.threed.CubeFace-}
```
public abstract TextureData toBitmap(CubeFace side)
```


Μετατρέψτε τη μονάδα υφής σε αντικείμενο [TextureData](../../com.aspose.threed/texturedata)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| side | [CubeFace](../../com.aspose.threed/cubeface) |  |

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
