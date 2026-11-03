---
title: "Aspose.ThreeD.Deformers"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Toutes les classes de déformeurs sont définies dans cet espace de noms"
type: docs
weight: 30
url: /fr/net/aspose.threed.deformers/
---
Toutes les classes de déformeurs sont définies dans cet espace de noms

## Classes

| Classe | Description |
| --- | --- |
| [Bone](./bone/) | Un os définit le sous-ensemble du point de contrôle de la géométrie et attribue un poids de mélange pour chaque point de contrôle. L'objet [`Bone`](../aspose.threed.deformers/bone/) ne peut pas être utilisé directement, une instance de [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) est utilisée pour déformer la géométrie, et [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) est fourni avec un ensemble d'os, chaque os étant lié à un nœud. NOTE : Un point de contrôle d'une géométrie peut être lié à plusieurs os. |
| [Deformer](./deformer/) | Classe de base pour [`SkinDeformer`](../aspose.threed.deformers/skindeformer/) et [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) |
| [MorphTargetChannel](./morphtargetchannel/) | Un MorphTargetChannel est utilisé par [`MorphTargetDeformer`](../aspose.threed.deformers/morphtargetdeformer/) pour organiser les géométries cibles. Certains formats de fichiers comme FBX prennent en charge plusieurs canaux en parallèle. |
| [MorphTargetDeformer](./morphtargetdeformer/) | MorphTargetDeformer fournit une animation par sommet. MorphTargetDeformer organise toutes les cibles via [`MorphTargetChannel`](../aspose.threed.deformers/morphtargetchannel/), chaque canal pouvant organiser plusieurs cibles. Une utilisation courante du déformeur de cible morphologique est d'appliquer des expressions faciales à un personnage. Plus de détails sont disponibles sur https://en.wikipedia.org/wiki/Morph_target_animation |
| [SkinDeformer](./skindeformer/) | Un déformeur de peau contient plusieurs os pour fonctionner, chaque os mélange une partie de la géométrie selon les poids des points de contrôle. |
## Énumération

| Énumération | Description |
| --- | --- |
| [BoneLinkMode](./bonelinkmode/) | Le mode de liaison d'un os fait référence à la manière dont un os est connecté ou lié à son os parent au sein d'une structure hiérarchique. |


