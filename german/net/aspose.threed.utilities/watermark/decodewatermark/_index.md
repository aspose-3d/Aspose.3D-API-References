---
title: "Watermark.DecodeWatermark"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Watermark-Methode. Dekodiere das Wasserzeichen aus einem Mesh"
type: docs
weight: 10
url: /de/net/aspose.threed.utilities/watermark/decodewatermark/
---
## DecodeWatermark(Mesh) {#decodewatermark}

Dekodiere das Wasserzeichen aus einem Mesh

```csharp
public static string DecodeWatermark(Mesh input)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | Mesh | Das Mesh zum Extrahieren des Wasserzeichens |

### Rückgabewert

Blindes Wasserzeichen oder null, wenn kein Wasserzeichen dekodiert wurde.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| UnauthorizedAccessException | Das Mesh ist durch ein Passwort geschützt, und das angegebene Passwort ist falsch. |

## Hinweise

Sowohl [`EncodeWatermark`](../encodewatermark/) als auch `DecodeWatermark` führen eine Lizenzprüfung durch. Die Nutzung in der Testversion löst eine Ausnahme aus; Sie können [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) verwenden, um die Ausnahme zu unterdrücken, aber dies hebt die Einschränkung hier nicht auf. Eine gültige Lizenz ist erforderlich, um diese Funktionen ohne Einschränkungen zu nutzen.

## Beispiele

Der folgende Code zeigt, wie ein blindes Wasserzeichen aus einem in einer 3D-Datei gespeicherten Mesh dekodiert wird.

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh);
```

### Siehe auch

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## DecodeWatermark(Mesh, string) {#decodewatermark_1}

Dekodiere das Wasserzeichen aus einem Mesh

```csharp
public static string DecodeWatermark(Mesh input, string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | Mesh | Das Mesh zum Extrahieren des Wasserzeichens |
| Passwort | String | Das Passwort zum Entschlüsseln des Wasserzeichens |

### Rückgabewert

Blindes Wasserzeichen oder null, wenn kein Wasserzeichen dekodiert wurde.

### Ausnahmen

| Ausnahme | Bedingung |
| --- | --- |
| UnauthorizedAccessException | Das Mesh ist durch ein Passwort geschützt, und das angegebene Passwort ist falsch. |

## Beispiele

Der folgende Code zeigt, wie ein blindes Wasserzeichen aus einem in einer 3D-Datei gespeicherten Mesh dekodiert wird.

```csharp
Mesh mesh = (Mesh)FileFormat.PLY.Decode("test.ply");
String watermark = Watermark.DecodeWatermark(mesh, "password");
```

### Siehe auch

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


