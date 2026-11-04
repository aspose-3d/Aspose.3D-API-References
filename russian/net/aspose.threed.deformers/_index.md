---
title: "Aspose.ThreeD.Deformers"
second_title: "Справочник API Aspose.3D для .NET"
description: "Все классы деформеров определены в этом пространстве имён"
type: docs
weight: 30
url: /ru/net/aspose.threed.deformers/
---
Все классы деформеров определены в этом пространстве имён

## Классы

| Класс | Описание |
| --- | --- |
| [Bone](./bone/) | Кость определяет подмножество контрольных точек геометрии и задаёт вес смешивания для каждой контрольной точки. Объект [`Bone`](../aspose.threed.deformers/bone/) нельзя использовать напрямую, для деформации геометрии используется экземпляр [`SkinDeformer`](../aspose.threed.deformers/skindeformer/), и [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) поставляется с набором костей, каждая кость привязана к узлу. ПРИМЕЧАНИЕ: Контрольная точка геометрии может быть привязана к более чем одной кости. |
| [Deformer](./deformer/) | Базовый класс для [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) и [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) |
| [MorphTargetChannel](./morphtargetchannel/) | MorphTargetChannel используется [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) для организации целевых геометрий. Некоторые форматы файлов, такие как FBX, поддерживают несколько каналов одновременно. |
| [MorphTargetDeformer](./morphtargetdeformer/) | MorphTargetDeformer обеспечивает покоординатную анимацию. MorphTargetDeformer организует все цели через [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/), каждый канал может содержать несколько целей. Распространённое применение деформера морф-целей — применение мимики к персонажу. Более подробная информация доступна по адресу https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | Skin деформер содержит несколько костей для работы, каждая кость смешивает часть геометрии по весам контрольных точек. |
## Перечисление

| Перечисление | Описание |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | Режим соединения кости относится к способу, которым кость соединяется или связывается с родительской костью в иерархической структуре. |


