---
title: "Énumération BoneLinkMode"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Aspose.ThreeD.Deformers.BoneLinkMode enum. Un mode de liaison d'os fait référence à la manière dont un os est connecté ou lié à son os parent dans une structure hiérarchique."
type: docs
weight: 200
url: /fr/net/aspose.threed.deformers/bonelinkmode/
---
## BoneLinkMode enumeration

Le mode de liaison d'un os fait référence à la manière dont un os est connecté ou lié à son os parent au sein d'une structure hiérarchique.

```csharp
public enum BoneLinkMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Normalize | `0` | Dans ce mode, les transformations des os enfants sont normalisées par rapport aux transformations de leur os parent. |
| Additive | `1` | Le mode additif calcule les transformations des os enfants en ajoutant leurs propres transformations locales à celles de leurs os parents. |
| TotalOne | `2` | Le mode Total One garantit que les transformations combinées des os parent et enfant aboutissent à une transformation combinée qui s'ajuste à une longueur totale d'une unité. |

### Voir aussi

* namespace [Aspose.ThreeD.Deformers](../../aspose.threed.deformers/)
* assembly [Aspose.3D](../../)


