---
title: "FileFormat.CanImport"
second_title: "Справочник API Aspose.3D для .NET"
description: "Свойство FileFormat. Возвращает, поддерживает ли Aspose.3D импорт сцены из текущего формата файла"
type: docs
weight: 490
url: /ru/net/aspose.threed/fileformat/canimport/
---
## FileFormat.CanImport property

Получает, поддерживает ли Aspose.3D импорт сцены из текущего формата файла.

```csharp
public bool CanImport { get; }
```

## Примеры

Следующий код показывает, как проверить, поддерживается ли импорт из указанного формата.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanImport)
    Console.WriteLine($"Can import from {outputFormat}");
```

### См. также

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


