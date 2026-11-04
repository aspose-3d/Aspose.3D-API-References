---
title: "Enum StencilAction"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Render.StencilAction enum. Действия теста трафарета"
type: docs
weight: 2430
url: /ru/net/aspose.threed.render/stencilaction/
---
## StencilAction enumeration

Действия теста трафарета

```csharp
public enum StencilAction
```

### Значения

| Имя | Значение | Описание |
| --- | --- | --- |
| Keep | `0` | Сохранить текущее значение |
| Zero | `1` | Устанавливает значение буфера трафарета в 0 |
| Replace | `2` | Устанавливает буфер трафарета в ref, где определено в [`StencilReference`](../renderstate/stencilreference/) |
| Increment | `3` | Увеличивает текущее значение буфера трафарета, ограничивая его максимальным значением. |
| IncrementWrap | `4` | Увеличивает текущее значение буфера трафарета и сбрасывает его к нулю, когда оно достигает максимального значения. |
| Decrement | `5` | Увеличивает текущее значение буфера трафарета, ограничивая его нулём. |
| DecrementWrap | `6` | Уменьшает текущее значение буфера трафарета и сбрасывает его к максимальному значению, когда оно достигает нуля. |
| Invert | `7` | Побитово инвертирует текущее значение буфера трафарета. |

### См. также

* namespace [Aspose.ThreeD.Render](../../aspose.threed.render/)
* assembly [Aspose.3D](../../)


