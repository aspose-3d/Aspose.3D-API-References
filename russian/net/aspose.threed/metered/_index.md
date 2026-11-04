---
title: "Класс Metered"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Metered. Предоставляет методы для установки метрированного ключа"
type: docs
weight: 1620
url: /ru/net/aspose.threed/metered/
---
## Metered class

Предоставляет методы для установки измеряемого ключа.

```csharp
public class Metered
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Metered](metered/)() | Инициализирует новый экземпляр этого класса. |

## Методы

| Имя | Описание |
| --- | --- |
| [SetMeteredKey](../../aspose.threed/metered/setmeteredkey/)(string, string) | Устанавливает публичный и приватный метрированный ключ. Если вы приобретаете метрированную лицензию, при запуске приложения этот API должен быть вызван, обычно этого достаточно. Однако если постоянно не удаётся загрузить данные о потреблении и прошло более 24 часов, лицензия будет переведена в статус оценки; чтобы избежать такой ситуации, следует регулярно проверять статус лицензии, и если он находится в статусе оценки, вызвать этот API снова. |
| static [GetConsumptionCredit](../../aspose.threed/metered/getconsumptioncredit/)() | Получает кредит потребления |
| static [GetConsumptionQuantity](../../aspose.threed/metered/getconsumptionquantity/)() | Получает размер файла потребления |

## Примеры

В этом примере будет предпринята попытка установить измеряемый публичный и приватный ключ

```csharp
[C#]

Metered matered = new Metered();
matered.SetMeteredKey("PublicKey", "PrivateKey");


[Visual Basic]

Dim matered As Metered = New Metered
matered.SetMeteredKey("PublicKey", "PrivateKey")
```

файл jar компонента:

```csharp
Metered matered = new Metered();
matered.setMeteredKey("PublicKey", "PrivateKey");
```

### См. также

* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


