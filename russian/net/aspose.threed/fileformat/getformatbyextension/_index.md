---
title: "FileFormat.GetFormatByExtension"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод FileFormat. Получает предпочтительный формат файла из имени расширения файла. Имя расширения должно начинаться с точки"
type: docs
weight: 470
url: /ru/net/aspose.threed/fileformat/getformatbyextension/
---
## FileFormat.GetFormatByExtension method

Получает предпочтительный формат файла из имени расширения. Имя расширения должно начинаться с точки ('.').

```csharp
public static FileFormat GetFormatByExtension(string extensionName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| extensionName | String | Имя расширения начинается с '.' для запроса. |

### Возвращаемое значение

Экземпляр [`FileFormat`](../), иначе возвращается null.

## Примеры

Следующий код показывает, как сохранить сцену в память, используя указанный формат

```csharp
Scene scene = new Scene(new Box());
var outputFormat = ".glb";
var format = FileFormat.GetFormatByExtension(outputFormat);
using(var ms = new MemoryStream())
{
    scene.Save(ms, format);
}
```

### См. также

* class [FileFormat](../)
* namespace [Aspose.ThreeD](../../fileformat/)
* assembly [Aspose.3D](../../../)


