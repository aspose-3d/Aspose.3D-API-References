---
title: "License.License"
second_title: "Справочник API Aspose.3D для .NET"
description: "Конструктор License. Инициализирует новый экземпляр этого класса."
type: docs
weight: 10
url: /ru/net/aspose.threed/license/license/
---
## License constructor

Инициализирует новый экземпляр этого класса.

```csharp
public License()
```

## Примеры

В этом примере будет предпринята попытка найти файл лицензии с именем MyLicense.lic в папке, содержащей компонент, в папке, содержащей вызывающую сборку, в папке входной сборки, а затем во встроенных ресурсах вызывающей сборки.

```csharp
[C#]

License license = new License();
license.SetLicense("MyLicense.lic");


[Visual Basic]

Dim license As license = New license
License.SetLicense("MyLicense.lic")
```

файл jar компонента:

```csharp
License license = new License();
license.setLicense("MyLicense.lic");
```

### См. также

* class [License](../)
* namespace [Aspose.ThreeD](../../license/)
* assembly [Aspose.3D](../../../)


