---
title: MappingMode
second_title: Aspose.3D for .NET API Referansı
description: Öğenin bir yüzeye nasıl eşlendiğini belirler. MappingMode./mappingmode nasıl tanımlandıVertexElement./vertexelement geometrinin yüzeyine eşlenir.
type: docs
weight: 440
url: /tr/net/aspose.threed.entities/mappingmode/
---
## MappingMode enumeration

Öğenin bir yüzeye nasıl eşlendiğini belirler. [`MappingMode`](../mappingmode) nasıl tanımlandı[`VertexElement`](../vertexelement) geometrinin yüzeyine eşlenir.

```csharp
public enum MappingMode
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| ControlPoint | `0` | Her veri geometrinin kontrol noktasına eşlenir. |
| PolygonVertex | `1` | Veriler çokgenin tepe noktasına eşlenir Bir kontrol noktası birden çok çokgen tarafından paylaşıldığında ve veriler şu şekilde eşlenir:PolygonVertex farklı çokgen tepe noktası olarak kontrol noktasının kendi data |
| Polygon | `2` | Veriler çokgene eşlenir. Her çokgen tepe noktası, eşleme modu açıkken aynı verileri paylaşır.Polygon . |
| Edge | `3` | Veriler, kenarla eşlenir. Eşleme yapılırken her kenar uç noktası aynı verileri paylaşır.Edge . |
| AllSame | `4` | Tüm yüzeyle eşlenen bir veri. Hangi veri kontrol noktası/çokgen tepe noktası/kenar uç noktaları olarak yorumlanırsa yorumlansın, veri her zaman tarafından tanımlananla aynıdır.AllSame . |

### Ayrıca bakınız

* ad alanı [Aspose.ThreeD.Entities](../../aspose.threed.entities)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
