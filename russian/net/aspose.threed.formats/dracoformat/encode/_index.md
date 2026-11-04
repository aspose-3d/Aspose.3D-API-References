---
title: "DracoFormat.Encode"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод DracoFormat. Кодировать сущность в указанный поток."
type: docs
weight: 20
url: /ru/net/aspose.threed.formats/dracoformat/encode/
---
## Encode(Entity, Stream, DracoSaveOptions) {#encode_1}

Кодировать объект в указанный поток

```csharp
public void Encode(Entity entity, Stream stream, DracoSaveOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Сущность, которую нужно закодировать. |
| stream | Stream | Поток, в который будут записаны закодированные данные. |
| options | DracoSaveOptions | Дополнительные параметры для кодирования облака точек. |

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается, когда не удалось прочитать поток. |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, string, DracoSaveOptions) {#encode_2}

Кодировать объект в указанный файл

```csharp
public void Encode(Entity entity, string fileName, DracoSaveOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Сущность, которую нужно закодировать. |
| fileName | String | Имя файла для записи. |
| options | DracoSaveOptions | Дополнительные параметры для кодирования облака точек. |

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)

---

## Encode(Entity, DracoSaveOptions) {#encode}

Кодировать объект в необработанные данные Draco

```csharp
public byte[] Encode(Entity entity, DracoSaveOptions options = null)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| сущность | Сущность | Сущность, которую нужно закодировать. |
| options | DracoSaveOptions | Дополнительные параметры для кодирования облака точек. |

### Возвращаемое значение

Закодированные данные draco в виде байтов.

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

* class [Entity](../../../aspose.threed/entity/)
* class [DracoSaveOptions](../../dracosaveoptions/)
* class [DracoFormat](../)
* namespace [Aspose.ThreeD.Formats](../../dracoformat/)
* assembly [Aspose.3D](../../../)


