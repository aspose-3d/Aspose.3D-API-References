---
title: "Watermark.EncodeWatermark"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Watermark-Methode. Kodieren Sie einen Text in ein blindes Wasserzeichen des Meshes"
type: docs
weight: 20
url: /de/net/aspose.threed.utilities/watermark/encodewatermark/
---
## EncodeWatermark(Mesh, string) {#encodewatermark}

Kodieren Sie einen Text in das blinde Wasserzeichen des Meshes.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | Mesh | Mesh zum Kodieren eines blinden Wasserzeichens |
| Text | String | Text, der in das Mesh kodiert werden soll |

### Rückgabewert

Eine neue Mesh-Instanz mit kodiertem blindem Wasserzeichen

## Hinweise

Sowohl `EncodeWatermark` als auch [`DecodeWatermark`](../decodewatermark/) führen eine Lizenzprüfung durch. Die Nutzung in der Testversion löst eine Ausnahme aus; Sie können [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) verwenden, um die Ausnahme zu unterdrücken, aber dies hebt die Einschränkung hier nicht auf. Eine gültige Lizenz ist erforderlich, um diese Funktionen ohne Einschränkungen zu nutzen.

## Beispiele

Der folgende Code zeigt, wie ein blindes Wasserzeichen in ein Mesh kodiert und in einer PLY-Datei gespeichert wird.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello");
new Scene(encodedMesh).Save("test.ply");
```

### Siehe auch

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string) {#encodewatermark_1}

Kodieren Sie einen Text in das blinde Wasserzeichen des Meshes.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | Mesh | Mesh zum Kodieren eines blinden Wasserzeichens |
| Text | String | Text, der in das Mesh kodiert werden soll |
| Passwort | String | Passwort zum Schutz des Wasserzeichens, optional |

### Rückgabewert

Eine neue Mesh-Instanz mit kodiertem blindem Wasserzeichen

## Hinweise

Sowohl `EncodeWatermark` als auch [`DecodeWatermark`](../decodewatermark/) führen eine Lizenzprüfung durch. Die Nutzung in der Testversion löst eine Ausnahme aus; Sie können [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) verwenden, um die Ausnahme zu unterdrücken, aber dies hebt die Einschränkung hier nicht auf. Eine gültige Lizenz ist erforderlich, um diese Funktionen ohne Einschränkungen zu nutzen.

## Beispiele

Der folgende Code zeigt, wie ein blindes Wasserzeichen in ein Mesh kodiert und in einer PLY-Datei gespeichert wird.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### Siehe auch

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)

---

## EncodeWatermark(Mesh, string, string, bool) {#encodewatermark_2}

Kodieren Sie einen Text in das blinde Wasserzeichen des Meshes.

```csharp
public static Mesh EncodeWatermark(Mesh input, string text, string password, bool permanent)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Eingabe | Mesh | Mesh zum Kodieren eines blinden Wasserzeichens |
| Text | String | Text, der in das Mesh kodiert werden soll |
| Passwort | String | Passwort zum Schutz des Wasserzeichens, optional |
| dauerhaft | Boolean | Das dauerhafte Wasserzeichen wird nicht überschrieben oder entfernt. |

### Rückgabewert

Eine neue Mesh-Instanz mit kodiertem blindem Wasserzeichen

## Hinweise

Sowohl `EncodeWatermark` als auch [`DecodeWatermark`](../decodewatermark/) führen eine Lizenzprüfung durch. Die Nutzung in der Testversion löst eine Ausnahme aus; Sie können [`SuppressTrialException`](../../../aspose.threed/trialexception/suppresstrialexception/) verwenden, um die Ausnahme zu unterdrücken, aber dies hebt die Einschränkung hier nicht auf. Eine gültige Lizenz ist erforderlich, um diese Funktionen ohne Einschränkungen zu nutzen.

## Beispiele

Der folgende Code zeigt, wie ein blindes Wasserzeichen in ein Mesh kodiert und in einer PLY-Datei gespeichert wird.

```csharp
Mesh mesh = (new Cylinder()).ToMesh();
var encodedMesh = Watermark.EncodeWatermark(mesh, "Hello", "password");
new Scene(encodedMesh).Save("test.ply");
```

### Siehe auch

* class [Mesh](../../../aspose.threed.entities/mesh/)
* class [Watermark](../)
* namespace [Aspose.ThreeD.Utilities](../../watermark/)
* assembly [Aspose.3D](../../../)


