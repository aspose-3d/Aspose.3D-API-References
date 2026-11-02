---
title: "IBuffer"
second_title: "Referencia de API de Aspose.3D for Java"
description: "La interfaz base de todos los buffers gestionados utilizados en el renderizado"
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
| [getSize()](#getSize--) | Tamaño de este búfer en bytes |
| [loadData(byte[] data)](#loadData-byte---) | Cargar los datos en el búfer actual |
### getSize() {#getSize--}
```
public abstract int getSize()
```


Tamaño de este búfer en bytes

**Returns:**
int - Tamaño de este búfer en bytes
### loadData(byte[] data) {#loadData-byte---}
```
public abstract void loadData(byte[] data)
```


Cargar los datos en el búfer actual

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| datos | byte[] |  |

