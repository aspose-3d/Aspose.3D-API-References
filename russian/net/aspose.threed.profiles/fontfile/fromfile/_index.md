---
title: "FontFile.FromFile"
second_title: "Справочник API Aspose.3D для .NET"
description: "Метод FontFile. Загрузить FontFile из имени файла"
type: docs
weight: 10
url: /ru/net/aspose.threed.profiles/fontfile/fromfile/
---
## FontFile.FromFile method

Загрузить FontFile из имени файла

```csharp
public static FontFile FromFile(string fileName)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| fileName | String | Путь к файлу шрифта |

### Возвращаемое значение

Экземпляр FontFile

### Исключения

| исключение | условие |
| --- | --- |
| IOException | Выбрасывается, когда не удалось прочитать файл. |

## Примеры

Следующий код показывает, как создать 3D‑сетку из текста, используя указанный файл шрифта.

```csharp
var font = FontFile.FromFile(@"CascadiaCode-Regular.otf");
var text = new Text();
text.Font = font;
text.Content = "ABC";
text.FontSize = 10;
var linear = new LinearExtrusion(text, 10).ToMesh();
var scene = new Scene(linear);
scene.Save(@"test.stl");
```

### См. также

* class [FontFile](../)
* namespace [Aspose.ThreeD.Profiles](../../fontfile/)
* assembly [Aspose.3D](../../../)


