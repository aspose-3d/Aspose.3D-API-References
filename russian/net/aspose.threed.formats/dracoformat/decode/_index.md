---
title: "DracoFormat.Decode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод DracoFormat. Декодировать облако точек или сетку из указанного имени файла."
type: docs
weight: 10
url: /ru/net/aspose.threed.formats/dracoformat/decode/
---
## Decode(string) {#decode_1}

Декодировать облако точек или сетку из указанного имени файла

```csharp
public Geometry Decode(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла содержит файл drc. |

### Возвращаемое значение

Экземпляр [`Mesh`](../../../aspose.threed.entities/mesh/) или [`PointCloud`](../../../aspose.threed.entities/pointcloud/) зависит от содержимого файла.

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается, когда не удалось прочитать файл. |

## Примеры

Следующий код показывает, как кодировать и декодировать Mesh в/из массива байтов:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//кодировать сетку в формат Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//декодировать сетку из формата Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### См. также

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Decode(byte[]) {#decode}

Декодировать облако точек или сетку из данных в памяти

```csharp
public Geometry Decode(byte[] data)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| данные | Byte[] | Необработанные байты drc. |

### Возвращаемое значение

Экземпляр [`Mesh`](../../../aspose.threed.entities/mesh/) или [`PointCloud`](../../../aspose.threed.entities/pointcloud/) зависит от содержимого.

### Исключения

| исключение | условие |
| --- | --- |
| [ImportException](../../../aspose.threed/importexception/) | Выбрасывается, когда данные повреждены. |

## Примеры

Следующий код показывает, как кодировать и декодировать Mesh в/из массива байтов:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//кодировать сетку в формат Draco
byte[] draco = FileFormat.Draco.Encode(mesh);
//декодировать сетку из формата Draco
Mesh decodedMesh = (Mesh)FileFormat.Draco.Decode(draco);
```

### См. также

* class [Geometry](../../../aspose.threed.entities/geometry/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


