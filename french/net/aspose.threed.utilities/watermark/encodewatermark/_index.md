---
title: "Watermark.EncodeWatermark"
second_title: "Référence de l'API Aspose.3D pour .NET"
description: "Méthode Watermark. Encodez un texte dans le filigrane aveugle du maillage"
type: docs
weight: 20
url: /fr/net/aspose.threed.utilities/watermark/encodewatermark/
---
## EncodeWatermark(Mesh, string) {#encodewatermark}

Encodez un texte dans le filigrane aveugle du maillage.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Maillage | Maillage pour encoder un filigrane aveugle |
| texte | String | Texte à encoder dans le maillage |

### Valeur de retour

Une nouvelle instance de maillage avec un filigrane aveugle encodé

## Remarques

Les deux `EncodeWatermark` et [`DecodeWatermark`](../decodewatermark/) effectueront une vérification de licence. L'utilisation en version d'essai déclenchera une exception, vous pouvez utiliser [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) pour supprimer l'exception, mais cela ne lèvera pas la restriction ici. Une licence valide est requise pour utiliser ces fonctionnalités sans aucune restriction.

## Exemples

Le code suivant montre comment encoder un filigrane invisible dans un maillage et l'enregistrer au format ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello");
new Scene(encodedMesh).Save("test.ply");
```

### Voir aussi

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string) {#encodewatermark_1}

Encodez un texte dans le filigrane aveugle du maillage.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Maillage | Maillage pour encoder un filigrane aveugle |
| texte | String | Texte à encoder dans le maillage |
| mot de passe | String | Mot de passe pour protéger le filigrane, il est facultatif. |

### Valeur de retour

Une nouvelle instance de maillage avec un filigrane aveugle encodé

## Remarques

Les deux `EncodeWatermark` et [`DecodeWatermark`](../decodewatermark/) effectueront une vérification de licence. L'utilisation en version d'essai déclenchera une exception, vous pouvez utiliser [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) pour supprimer l'exception, mais cela ne lèvera pas la restriction ici. Une licence valide est requise pour utiliser ces fonctionnalités sans aucune restriction.

## Exemples

Le code suivant montre comment encoder un filigrane invisible dans un maillage et l'enregistrer au format ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### Voir aussi

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string, bool) {#encodewatermark_2}

Encodez un texte dans le filigrane aveugle du maillage.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password, bool permanent)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| entrée | Maillage | Maillage pour encoder un filigrane aveugle |
| texte | String | Texte à encoder dans le maillage |
| mot de passe | String | Mot de passe pour protéger le filigrane, il est facultatif. |
| permanent | Boolean | Le filigrane permanent ne sera pas écrasé ni supprimé. |

### Valeur de retour

Une nouvelle instance de maillage avec un filigrane aveugle encodé

## Remarques

Les deux `EncodeWatermark` et [`DecodeWatermark`](../decodewatermark/) effectueront une vérification de licence. L'utilisation en version d'essai déclenchera une exception, vous pouvez utiliser [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) pour supprimer l'exception, mais cela ne lèvera pas la restriction ici. Une licence valide est requise pour utiliser ces fonctionnalités sans aucune restriction.

## Exemples

Le code suivant montre comment encoder un filigrane invisible dans un maillage et l'enregistrer au format ply.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### Voir aussi

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


