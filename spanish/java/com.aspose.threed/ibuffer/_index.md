---
title: IBuffer
second_title: Referencia de API de Aspose.3D para Java
description: La interfaz base de todos los buffers gestionados utilizados en el renderizado
type: docs
weight: 239
url: /es/java/com.aspose.threed/ibuffer/
---

**All Implemented Interfaces:**
java.io.Closeable
```
public interface IBuffer extends Closeable
```

La interfaz base de todos los buffers gestionados utilizados en el renderizado
## Métodos

| Método | Descripción |
| --- | --- |
| [getSize()](#getSize--) | Tamaño de este buffer en bytes |
| [loadData(byte[] data)](#loadData-byte---) | Cargar los datos en el buffer actual |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Tamaño de este buffer en bytes

**Returns:**
int - Tamaño de este buffer en bytes
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Cargar los datos en el buffer actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] |  |

