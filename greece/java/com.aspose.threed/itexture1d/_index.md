---
title: "ITexture1D"
second_title: "Aspose.3D for Java API Reference"
description: "Υφή 1Δ"
type: docs
weight: 252
url: /el/java/com.aspose.threed/itexture1d/
---

**All Implemented Interfaces:**
[com.aspose.threed.ITextureUnit](../../com.aspose.threed/itextureunit)
```
public interface ITexture1D extends ITextureUnit
```

Υφή 1Δ
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [load(TextureData bitmap)](#load-com.aspose.threed.TextureData-) | Φορτώστε το περιεχόμενο της υφής από το καθορισμένο Bitmap |
| [save(TextureData bitmap)](#save-com.aspose.threed.TextureData-) | Αποθηκεύστε το περιεχόμενο της υφής σε εξωτερικό αρχείο. |
| [save(String path, String format)](#save-java.lang.String-java.lang.String-) | Αποθηκεύστε το περιεχόμενο της υφής σε εξωτερικό αρχείο. |
| [toBitmap()](#toBitmap--) | Μετατρέψτε τη μονάδα υφής σε αντικείμενο [TextureData](../../com.aspose.threed/texturedata) |
### load(TextureData bitmap) {#load-com.aspose.threed.TextureData-}
```
public abstract void load(TextureData bitmap)
```


Φορτώστε το περιεχόμενο της υφής από το καθορισμένο Bitmap

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) |  |

### save(TextureData bitmap) {#save-com.aspose.threed.TextureData-}
```
public abstract void save(TextureData bitmap)
```


Αποθηκεύστε το περιεχόμενο της υφής σε εξωτερικό αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | Αποτέλεσμα bitmap για αποθήκευση. |

### save(String path, String format) {#save-java.lang.String-java.lang.String-}
```
public abstract void save(String path, String format)
```


Αποθηκεύστε το περιεχόμενο της υφής σε εξωτερικό αρχείο.

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| διαδρομή | java.lang.String | Όνομα αρχείου για αποθήκευση. |
| format | java.lang.String | Μορφή εικόνας |

### toBitmap() {#toBitmap--}
```
public abstract TextureData toBitmap()
```


Μετατρέψτε τη μονάδα υφής σε αντικείμενο [TextureData](../../com.aspose.threed/texturedata)

**Returns:**
[TextureData](../../com.aspose.threed/texturedata)
