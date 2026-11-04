---
title: "PlyFormat.Decode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PlyFormat. Декодировать облако точек или сетку из указанного потока"
type: docs
weight: 10
url: /ru/net/aspose.threed.formats/plyformat/decode/
---
## Decode(string) {#decode_2}

Декодировать облако точек или сетку из указанного потока.

```csharp
public Geometry Decode(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Входной поток |

### Возвращаемое значение

Экземпляр [`Mesh`](../../../aspose.threed.entities/mesh/) или [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Примеры

Следующий код показывает, как декодировать сетку из файла PLY:

```csharp
//Создать тестовый файл для декодирования
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Декодировать файл
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### См. также

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(string, PlyLoadOptions) {#decode_3}

Декодировать облако точек или сетку из указанного потока.

```csharp
public Geometry Decode(string fileName, PlyLoadOptions opt)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Входной поток |
| opt | PlyLoadOptions | Параметр загрузки формата PLY |

### Возвращаемое значение

Экземпляр [`Mesh`](../../../aspose.threed.entities/mesh/) или [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Примеры

Следующий код показывает, как декодировать сетку из файла PLY:

```csharp
//Создать тестовый файл для декодирования
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Декодировать файл
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### См. также

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream) {#decode}

Декодировать облако точек или сетку из указанного потока.

```csharp
public Geometry Decode(Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток |

### Возвращаемое значение

Экземпляр [`Mesh`](../../../aspose.threed.entities/mesh/) или [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Примеры

Следующий код показывает, как декодировать сетку из файла PLY:

```csharp
//Создать тестовый файл для декодирования
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Декодировать файл
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### См. также

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(Stream, PlyLoadOptions) {#decode_1}

Декодировать облако точек или сетку из указанного потока.

```csharp
public Geometry Decode(Stream stream, PlyLoadOptions opt)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | Stream | Входной поток |
| opt | PlyLoadOptions | Параметр загрузки формата PLY |

### Возвращаемое значение

Экземпляр [`Mesh`](../../../aspose.threed.entities/mesh/) или [`PointCloud`](../../../aspose.threed.entities/pointcloud/)

## Примеры

Следующий код показывает, как декодировать сетку из файла PLY:

```csharp
//Создать тестовый файл для декодирования
FileFormat.PLY.Encode(new Sphere(), "sphere.ply");
//Декодировать файл
var mesh = (Mesh)FileFormat.PLY.Decode("sphere.ply")
```

### См. также

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [PlyLoadOptions](../../plyloadoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


