---
title: IIndexBuffer
second_title: Aspose.3D for Java API Reference
description: Το buffer δεικτών περιγράφει τη γεωμετρία που χρησιμοποιείται στην αλυσίδα απόδοσης.
type: docs
weight: 242
url: /el/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

Το buffer δεικτών περιγράφει τη γεωμετρία που χρησιμοποιείται στην αλυσίδα απόδοσης.
## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| [getCount()](#getCount--) | Λαμβάνει τον αριθμό των δεικτών σε αυτό το buffer. |
| [getIndexDataType()](#getIndexDataType--) | Λαμβάνει τον τύπο δεδομένων κάθε στοιχείου. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Φορτώνει δεδομένα δεικτών από το [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | Φορτώνει δεδομένα δεικτών |
| [loadData(short[] indices)](#loadData-short---) | Φορτώνει δεδομένα δεικτών |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Λαμβάνει τον αριθμό των δεικτών σε αυτό το buffer.

**Returns:**
int - ο αριθμός των δεικτών σε αυτό το buffer.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Λαμβάνει τον τύπο δεδομένων κάθε στοιχείου.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Φορτώνει δεδομένα δεικτών από το [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


Φορτώνει δεδομένα δεικτών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτες | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


Φορτώνει δεδομένα δεικτών

**Parameters:**
| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| δείκτες | short[] |  |

