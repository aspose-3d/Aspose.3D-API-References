---
title: IIndexBuffer
second_title: Referencia de API de Aspose.3D para Java
description: El buffer de índices describe la geometría utilizada en el pipeline de renderizado.
type: docs
weight: 242
url: /es/java/com.aspose.threed/iindexbuffer/
---

**All Implemented Interfaces:**
[com.aspose.threed.IBuffer](../../com.aspose.threed/ibuffer)
```
public interface IIndexBuffer extends IBuffer
```

El buffer de índices describe la geometría utilizada en el pipeline de renderizado.
## Métodos

| Método | Descripción |
| --- | --- |
| [getCount()](#getCount--) | Obtiene el número de índices en este búfer. |
| [getIndexDataType()](#getIndexDataType--) | Obtiene el tipo de datos de cada elemento. |
| [loadData(TriMesh mesh)](#loadData-com.aspose.threed.TriMesh-) | Cargar datos de índices desde [TriMesh](../../com.aspose.threed/trimesh) |
| [loadData(int[] indices)](#loadData-int---) | Cargar datos de índices |
| [loadData(short[] indices)](#loadData-short---) | Cargar datos de índices |
### getCount() {#getCount--}
```
public abstract int getCount()
```


Obtiene el número de índices en este búfer.

**Returns:**
int - el número de índices en este búfer.
### getIndexDataType() {#getIndexDataType--}
```
public abstract IndexDataType getIndexDataType()
```


Obtiene el tipo de datos de cada elemento.

**Returns:**
[IndexDataType](../../com.aspose.threed/indexdatatype) - the data type of each element.
### loadData(TriMesh mesh) {#loadData-com.aspose.threed.TriMesh-}
```
public abstract void loadData(TriMesh mesh)
```


Cargar datos de índices desde [TriMesh](../../com.aspose.threed/trimesh)

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| mesh | [TriMesh](../../com.aspose.threed/trimesh) |  |

### loadData(int[] indices) {#loadData-int---}
```
public abstract void loadData(int[] indices)
```


Cargar datos de índices

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índices | int[] |  |

### loadData(short[] indices) {#loadData-short---}
```
public abstract void loadData(short[] indices)
```


Cargar datos de índices

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| índices | short[] |  |

