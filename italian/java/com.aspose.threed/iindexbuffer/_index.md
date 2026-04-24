---
title: IIndexBuffer
second_title: Aspose.3D for Java API Reference
description: Il buffer di indice descrive la geometria usata nel pipeline di rendering.
type: docs
weight: 242
url: /it/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

Il buffer di indice descrive la geometria usata nel pipeline di rendering.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCount()](#getCount--) | Ottiene il numero di indici in questo buffer. |
| [getIndexDataType()](#getIndexDataType--) | Ottiene il tipo di dato di ogni elemento. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Carica i dati degli indici da [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | Carica i dati degli indici |
| [loadData(short[] indices)](#loadData-short---) | Carica i dati degli indici |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Ottiene il numero di indici in questo buffer.

**Returns:**
int - il numero di indici in questo buffer.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Ottiene il tipo di dato di ogni elemento.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Carica i dati degli indici da [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


Carica i dati degli indici

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indici | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


Carica i dati degli indici

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| indici | short[] |  |

