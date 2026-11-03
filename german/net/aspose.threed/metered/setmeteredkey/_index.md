---
title: "Metered.SetMeteredKey"
second_title: "Aspose.3D für .NET API-Referenz"
description: "Metered method. Setzt den öffentlichen und privaten Metered-Schlüssel. Wenn Sie eine Metered-Lizenz beim Start der Anwendung erwerben, sollte diese API normalerweise aufgerufen werden; das ist ausreichend. Sollte jedoch stets das Hochladen von Verbrauchsdaten fehlschlagen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie regelmäßig den Lizenzstatus prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf."
type: docs
weight: 20
url: /de/net/aspose.threed/metered/setmeteredkey/
---
## Metered.SetMeteredKey method

Setzt den öffentlichen und privaten gemessenen Schlüssel. Wenn Sie eine gemessene Lizenz erwerben, sollte diese API beim Start der Anwendung aufgerufen werden; normalerweise reicht das aus. Sollte jedoch stets das Hochladen von Verbrauchsdaten fehlschlagen und 24 Stunden überschreiten, wird die Lizenz auf den Evaluierungsstatus gesetzt. Um einen solchen Fall zu vermeiden, sollten Sie den Lizenzstatus regelmäßig prüfen; ist er im Evaluierungsstatus, rufen Sie diese API erneut auf.

```csharp
public void SetMeteredKey(string publicKey, string privateKey)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| publicKey | String | öffentlicher Schlüssel |
| privateKey | String | privater Schlüssel |

### Siehe auch

* class [Metered](../)
* namespace [Aspose.ThreeD](../../metered/)
* assembly [Aspose.3D](../../../)


