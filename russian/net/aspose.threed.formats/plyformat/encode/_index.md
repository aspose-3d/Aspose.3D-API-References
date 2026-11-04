---
title: "PlyFormat.Encode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод PlyFormat. Кодировать объект и сохранять результат в поток"
type: docs
weight: 20
url: /ru/net/aspose.threed.formats/plyformat/encode/
---
## Encode(Entity, Stream) {#encode}

Кодировать объект и сохранить результат в поток.

```csharp
public void Encode(Entity entity, Stream stream)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Объект для кодирования |
| stream | Stream | Поток для записи, этот метод не закроет этот поток |

## Примеры

Следующий код показывает, как закодировать сетку в файл PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//закодировать сетку в формат PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### См. также

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, Stream, PlySaveOptions) {#encode_1}

Кодировать объект и сохранить результат в поток.

```csharp
public void Encode(Entity entity, Stream stream, PlySaveOptions opt)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Объект для кодирования |
| stream | Stream | Поток для записи, этот метод не закроет этот поток |
| opt | PlySaveOptions | Параметры сохранения |

## Примеры

Следующий код показывает, как закодировать сетку в файл PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//закодировать сетку в формат PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### См. также

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string) {#encode_2}

Кодировать объект и сохранить результат во внешний файл.

```csharp
public void Encode(Entity entity, string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Объект для кодирования |
| fileName | String | Файл для записи |

## Примеры

Следующий код показывает, как закодировать сетку в файл PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//закодировать сетку в формат PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### См. также

* class [Entity](../../../aspose.threed/entity/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, PlySaveOptions) {#encode_3}

Кодировать объект и сохранить результат во внешний файл.

```csharp
public void Encode(Entity entity, string fileName, PlySaveOptions opt)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Объект для кодирования |
| fileName | String | Файл для записи |
| opt | PlySaveOptions | Параметры сохранения |

## Примеры

Следующий код показывает, как закодировать сетку в файл PLY:

```csharp
Mesh mesh = (new Sphere()).ToMesh();
//закодировать сетку в формат PLY
FileFormat.PLY.Encode(mesh, "sphere.ply");
```

### См. также

* class [Entity](../../../aspose.threed/entity/)
* class [PlySaveOptions](../../plysaveoptions/)
* class [PlyFormat](../)
* namespace [Aspose.ThreeD.Formats](../../plyformat/)
* assembly [Aspose.3D](../../../)


