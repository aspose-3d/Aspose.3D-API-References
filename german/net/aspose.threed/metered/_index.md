---
title: "Klasse Metered"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Aspose.ThreeD.Metered Klasse. Stellt Methoden zum Setzen des gemessenen Schlüssels bereit"
type: docs
weight: 1620
url: /de/net/aspose.threed/metered/
---
## Metered class

Stellt Methoden bereit, um den gemessenen Schlüssel zu setzen.

```csharp
public class Metered
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [Metered](metered/)() | Initialisiert eine neue Instanz dieser Klasse. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [SetMeteredKey](../../aspose.threed/metered/setmeteredkey/)(string, string) | Setzt den öffentlichen und privaten gemessenen Schlüssel. Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Sollte jedoch stets das Hochladen von Verbrauchsdaten fehlschlagen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf. |
| static [GetConsumptionCredit](../../aspose.threed/metered/getconsumptioncredit/)() | Liefert Verbrauchsguthaben |
| static [GetConsumptionQuantity](../../aspose.threed/metered/getconsumptionquantity/)() | Liefert die Dateigröße des Verbrauchs |

## Beispiele

In diesem Beispiel wird versucht, den öffentlichen und privaten gemessenen Schlüssel zu setzen

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

die Komponenten‑Jar‑Datei:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### Siehe auch

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


