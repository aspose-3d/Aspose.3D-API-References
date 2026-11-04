---
title: "Интерфейс ITextureUnit"
second_title: "Справочник API Aspose.3D для .NET"
description: "Интерфейс Aspose.ThreeD.Render.ITextureUnit. ITextureUnit представляет текстуру в памяти, которая разделяется между GPU и CPU и может быть использована в шейдере, тогда как Texture представляет лишь ссылку на внешний файл. Подробнее можно узнать https//en.wikipedia.org/wiki/Texture_mapping_unit"
type: docs
weight: 2170
url: /ru/net/aspose.threed.render/itextureunit/
---
## ITextureUnit interface

`ITextureUnit` представляет текстуру в памяти, которая разделяется между GPU и CPU и может быть использована в шейдере, тогда как [`Texture`](../../aspose.threed.shading/texture/) представляет лишь ссылку на внешний файл. Подробнее можно узнать https://en.wikipedia.org/wiki/Texture_mapping_unit

```csharp
public interface ITextureUnit : IDisposable
```

## Свойства

| Имя | Описание |
| --- | --- |
| [Depth](../../aspose.threed.render/itextureunit/depth/) { get; } | Получает высоту этой текстуры, для не‑3D текстур она всегда равна 1. |
| [Height](../../aspose.threed.render/itextureunit/height/) { get; } | Получает высоту этой текстуры. |
| [Magnification](../../aspose.threed.render/itextureunit/magnification/) { get; set; } | Получает или задает режим фильтрации при увеличении. |
| [Minification](../../aspose.threed.render/itextureunit/minification/) { get; set; } | Получает или задает режим фильтрации при уменьшении. |
| [Mipmap](../../aspose.threed.render/itextureunit/mipmap/) { get; set; } | Получает или задает режим фильтрации для мип‑карты. |
| [Scale](../../aspose.threed.render/itextureunit/scale/) { get; set; } | Получает или задает масштаб UV‑координаты. |
| [Scroll](../../aspose.threed.render/itextureunit/scroll/) { get; set; } | Получает или задает смещение UV‑координаты. |
| [Type](../../aspose.threed.render/itextureunit/type/) { get; } | Получает тип этой текстурной единицы. |
| [UWrap](../../aspose.threed.render/itextureunit/uwrap/) { get; set; } | Получает или задает режим обёртки для координаты U текстуры. |
| [VWrap](../../aspose.threed.render/itextureunit/vwrap/) { get; set; } | Получает или задает режим обёртки для координаты V текстуры. |
| [Width](../../aspose.threed.render/itextureunit/width/) { get; } | Получает ширину этой текстуры. |
| [WWrap](../../aspose.threed.render/itextureunit/wwrap/) { get; set; } | Получает или задает режим обертки для координаты W текстуры. |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


