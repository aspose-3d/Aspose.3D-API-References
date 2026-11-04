---
title: "FileFormat.CanExport"
second_title: "Справочник API Aspose.3D для .NET"
description: "FileFormat свойство. Возвращает, поддерживает ли Aspose.3D экспорт сцены в текущий формат файла"
type: docs
weight: 480
url: /ru/net/aspose.threed/fileformat/canexport/
---
## FileFormat.CanExport property

Получает, поддерживает ли Aspose.3D экспорт сцены в текущий формат файла.

```csharp
public bool CanExport { get; }
```

## Примеры

Следующий код показывает, как проверить, поддерживается ли экспорт в указанный формат.

```csharp
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
if (format.CanExport)
    Console.WriteLine($"Can export to {outputFormat}");
```

### См. также

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


