---
title: EntityRenderer
second_title: Aspose.3D for .NET API Referansı
description: Farklı türde varlıklar için işleme uygulamak için bunu alt sınıflandırın.
type: docs
weight: 1780
url: /tr/net/aspose.threed.render/entityrenderer/
---
## EntityRenderer class

Farklı türde varlıklar için işleme uygulamak için bunu alt sınıflandırın.

```csharp
public class EntityRenderer
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EntityRenderer](entityrenderer#constructor)(string) | Oluşturucusu[`EntityRenderer`](../entityrenderer) |
| [EntityRenderer](entityrenderer#constructor_1)(string, EntityRendererFeatures) | Oluşturucusu[`EntityRenderer`](../entityrenderer) |

## yöntemler

| İsim | Tanım |
| --- | --- |
| virtual [Dispose](../../aspose.threed.render/entityrenderer/dispose)() | Varlık oluşturucu atılıyor, paylaşılan kaynakları serbest bırakın. |
| virtual [FrameBegin](../../aspose.threed.render/entityrenderer/framebegin)(Renderer, IRenderQueue) | Bir çerçeve oluşturmaya başlayın |
| virtual [FrameEnd](../../aspose.threed.render/entityrenderer/frameend)(Renderer, IRenderQueue) | Bir çerçeve oluşturmayı bitirir |
| virtual [Initialize](../../aspose.threed.render/entityrenderer/initialize)(Renderer) | Varlık oluşturucuyu başlatın |
| virtual [PrepareRenderQueue](../../aspose.threed.render/entityrenderer/preparerenderqueue)(Renderer, IRenderQueue, Node, Entity) | Belirtilen düğüm/varlık çifti için işleme komutları hazırlayın. |
| virtual [RenderEntity](../../aspose.threed.render/entityrenderer/renderentity)(Renderer, ICommandList, Node, object, int) | [`IRenderQueue`](../irenderqueue) somut işleme işini gerçekleştirmek için karşılık gelen bir RenderEntity call olacaktır. |
| virtual [ResetSceneCache](../../aspose.threed.render/entityrenderer/resetscenecache)() | Sahne değişti veya kaldırıldı, this içinde sahne düzeyinde işleme kaynaklarının atılması gerekiyor |

### Ayrıca bakınız

* ad alanı [Aspose.ThreeD.Render](../../aspose.threed.render)
* toplantı [Aspose.3D](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.3D.dll -->