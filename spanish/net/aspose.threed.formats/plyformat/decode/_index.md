---
title: "PlyFormat.Decode"
second_title: "Referencia de la API de Aspose.3D para .NET"
description: "Método PlyFormat. Decodifica una nube de puntos o malla del flujo especificado"
type: docs
weight: 10
url: /es/net/aspose.threed.formats/plyformat/decode/
---
## Decode(string) {#decode_2}

Decodifica una nube de puntos o malla del flujo especificado.

```csharp
public Geometry Decode(string fileName)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | El flujo de entrada |

### Valor de retorno

Una instancia de [`Mesh`](../../../aspose.threed.entities/mesh/) o [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Ejemplos

El siguiente código muestra cómo decodificar una malla de un archivo PLY:

```csharp
//Generar un archivo de prueba para decodificación
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Decodificar el archivo
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Ver también

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(string, PlyLoadOptions) {#decode_3}

Decodifica una nube de puntos o malla del flujo especificado.

```csharp
public Geometry Decode(string fileName, PlyLoadOptions opt)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| fileName | String | El flujo de entrada |
| opt | PlyLoadOptions | La opción de carga del formato PLY |

### Valor de retorno

Una instancia de [`Mesh`](../../../aspose.threed.entities/mesh/) o [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Ejemplos

El siguiente código muestra cómo decodificar una malla de un archivo PLY:

```csharp
//Generar un archivo de prueba para decodificación
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Decodificar el archivo
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Ver también

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream) {#decode}

Decodifica una nube de puntos o malla del flujo especificado.

```csharp
public Geometry Decode(Stream stream)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de entrada |

### Valor de retorno

Una instancia de [`Mesh`](../../../aspose.threed.entities/mesh/) o [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Ejemplos

El siguiente código muestra cómo decodificar una malla de un archivo PLY:

```csharp
//Generar un archivo de prueba para decodificación
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Decodificar el archivo
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Ver también

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream, PlyLoadOptions) {#decode_1}

Decodifica una nube de puntos o malla del flujo especificado.

```csharp
public Geometry Decode(Stream stream, PlyLoadOptions opt)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| stream | Stream | El flujo de entrada |
| opt | PlyLoadOptions | La opción de carga del formato PLY |

### Valor de retorno

Una instancia de [`Mesh`](../../../aspose.threed.entities/mesh/) o [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Ejemplos

El siguiente código muestra cómo decodificar una malla de un archivo PLY:

```csharp
//Generar un archivo de prueba para decodificación
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Decodificar el archivo
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### Ver también

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


