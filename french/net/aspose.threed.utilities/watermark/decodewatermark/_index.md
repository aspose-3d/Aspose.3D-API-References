---
title: "Watermark.DecodeWatermark"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Watermark. Décode le filigrane à partir d'un maillage"
type: docs
weight: 10
url: /fr/net/aspose.threed.utilities/watermark/decodewatermark/
---
## DecodeWatermark(Mesh) {#decodewatermark}

Décodez le filigrane depuis un maillage

```csharp
public static string DecodeWatermark(Mesh input)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Maillage | Le maillage pour extraire le filigrane |

### Valeur de retour

Filigrane aveugle ou null si aucun filigrane n'est décodé.

### Exceptions

| exception | condition |
| --- | --- |
| UnauthorizedAccessException | Le maillage est protégé par un mot de passe, et le mot de passe fourni est incorrect. |

## Remarques

Les deux [`EncodeWatermark`](../encodewatermark/) et `DecodeWatermark` effectueront une vérification de licence. L'utilisation en version d'essai déclenchera une exception, vous pouvez utiliser [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) pour supprimer l'exception, mais cela ne lèvera pas la restriction ici. Une licence valide est requise pour utiliser ces fonctionnalités sans aucune restriction.

## Exemples

Le code suivant montre comment décoder un filigrane aveugle à partir d'un maillage enregistré dans un fichier 3D

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh);
```

### Voir aussi

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## DecodeWatermark(Mesh, string) {#decodewatermark_1}

Décodez le filigrane depuis un maillage

```csharp
public static string DecodeWatermark(Mesh input, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Maillage | Le maillage pour extraire le filigrane |
| mot de passe | String | Le mot de passe pour déchiffrer le filigrane |

### Valeur de retour

Filigrane aveugle ou null si aucun filigrane n'est décodé.

### Exceptions

| exception | condition |
| --- | --- |
| UnauthorizedAccessException | Le maillage est protégé par un mot de passe, et le mot de passe fourni est incorrect. |

## Exemples

Le code suivant montre comment décoder un filigrane aveugle à partir d'un maillage enregistré dans un fichier 3D

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh, "password");
```

### Voir aussi

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


