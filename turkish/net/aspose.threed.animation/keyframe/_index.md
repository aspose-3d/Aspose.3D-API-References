---
title: KeyFrame
second_title: Aspose.3D for .NET API Referansı
description: Bir anahtar çerçeve esas olarak bir zaman ve bir değer ile tanımlanır bazı enterpolasyon türleri için teğet/gerginlik/önyargı/süreklilik de son örneklenen değer hesaplanırken kullanılır. Anahtar çerçeve olmayan bir zaman konumundaki örneklenen değerler enterpolasyonludur önceki ve sonraki anahtar kareler arasındaki anahtar karelere göre İlk/son anahtar kareden önceki/sonraki değerExtrapolation./extrapolation sınıf.
type: docs
weight: 90
url: /tr/net/aspose.threed.animation/keyframe/
---
## KeyFrame class

Bir anahtar çerçeve esas olarak bir zaman ve bir değer ile tanımlanır, bazı enterpolasyon türleri için teğet/gerginlik/önyargı/süreklilik de son örneklenen değer hesaplanırken kullanılır. Anahtar çerçeve olmayan bir zaman konumundaki örneklenen değerler enterpolasyonludur önceki ve sonraki anahtar kareler arasındaki anahtar karelere göre İlk/son anahtar kareden önceki/sonraki değer,[`Extrapolation`](../extrapolation) sınıf.

```csharp
public class KeyFrame
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [KeyFrame](keyframe)(KeyframeSequence, double) | Belirtilen eğride yeni bir anahtar kare oluşturun |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bias](../../aspose.threed.animation/keyframe/bias) { get; set; } | TCB spline 'de kullanılan önyargıyı alır veya ayarlar |
| [Continuity](../../aspose.threed.animation/keyframe/continuity) { get; set; } | TCB spline 'de kullanılan sürekliliği alır veya ayarlar |
| [Flat](../../aspose.threed.animation/keyframe/flat) { get; set; } | Anahtar kare düzse alın veya ayarlayın. Sonraki veya önceki anahtar kare aynı değere sahipse anahtar kare düz olmalıdır. Düz anahtar karenin düz teğetleri ve sabit enterpolasyonu vardır. |
| [IndependentTangent](../../aspose.threed.animation/keyframe/independenttangent) { get; set; } | Teğetlerdeki çıkış ve sonrakini alır veya ayarlar. |
| [Interpolation](../../aspose.threed.animation/keyframe/interpolation) { get; set; } | Anahtarın enterpolasyon türünü alır veya ayarlar, list.data[index] algoritmayı örneklenen değerin nasıl hesaplandığını tanımlar. |
| [NextInTangent](../../aspose.threed.animation/keyframe/nextintangent) { get; set; } | Bu anahtar karede bir sonraki (sol) tanjantı alır veya ayarlar. |
| [NextInWeight](../../aspose.threed.animation/keyframe/nextinweight) { get; set; } | Bu anahtar karedeki bir sonraki (sol) ağırlığı alır veya ayarlar. |
| [OutTangent](../../aspose.threed.animation/keyframe/outtangent) { get; set; } | Bu anahtar karede çıkış(sağ) tanjantını alır veya ayarlar. |
| [OutWeight](../../aspose.threed.animation/keyframe/outweight) { get; set; } | Bu anahtar karedeki çıkış(sağ) ağırlığı alır veya ayarlar. |
| [StepMode](../../aspose.threed.animation/keyframe/stepmode) { get; set; } | Anahtarın adım modunu alır veya ayarlar. Enterpolasyon türü iseConstant , list.data[index], enterpolasyon sırasında hangi anahtar karenin değerinin kullanılacağına karar verir. APreviousValue sol ana karenin değerinin kullanılacağı anlamına gelir ANextValuesonraki sağ ana karenin değerinin kullanılacağı anlamına gelir |
| [TangentWeightMode](../../aspose.threed.animation/keyframe/tangentweightmode) { get; set; } | Anahtarın teğet ağırlık modunu alır veya ayarlar. Çıkış tanjantı veya sonraki tanjant, doğru seçilerek özelleştirilebilir[`WeightedMode`](../weightedmode) |
| [Tension](../../aspose.threed.animation/keyframe/tension) { get; set; } | TCB spline 'de kullanılan gerilimi alır veya ayarlar |
| [Time](../../aspose.threed.animation/keyframe/time) { get; set; } | Saniye cinsinden ölçülen list.data[index] anahtar çerçevesinin zaman konumunu alır veya ayarlar. |
| [TimeIndependentTangent](../../aspose.threed.animation/keyframe/timeindependenttangent) { get; set; } | Tanjantın zamandan bağımsız olduğunu alır veya ayarlar |
| [Value](../../aspose.threed.animation/keyframe/value) { get; set; } | Anahtar karenin değerini alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| override [ToString](../../aspose.threed.animation/keyframe/tostring)() | Anahtar karesinin dize temsilini alır |

### Ayrıca bakınız

* ad alanı [Aspose.ThreeD.Animation](../../aspose.threed.animation)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->
