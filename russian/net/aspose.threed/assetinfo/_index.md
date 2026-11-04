---
title: "Класс AssetInfo"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.AssetInfo. Информация об объекте. Информацию об объекте можно прикрепить к Scene. Дочерняя Scene может иметь собственный AssetInfo, чтобы переопределить определение родителя"
type: docs
weight: 130
url: /ru/net/aspose.threed/assetinfo/
---
## AssetInfo class

Информация об объекте. Информацию об объекте можно прикрепить к [`Scene`](../scene/). Дочерняя [`Scene`](../scene/) может иметь собственный `AssetInfo`, чтобы переопределить определение родителя.

```csharp
public class AssetInfo : A3DObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [AssetInfo](assetinfo/#constructor)() | Инициализирует новый экземпляр класса `AssetInfo`. |
| [AssetInfo](assetinfo/#constructor_1)(string) | Инициализирует новый экземпляр класса `AssetInfo`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [Ambient](../../aspose.threed/assetinfo/ambient/) { get; set; } | Получает или задает цвет окружающего освещения по умолчанию для этого объекта |
| [ApplicationName](../../aspose.threed/assetinfo/applicationname/) { get; set; } | Получает или задает приложение, создавшее этот объект |
| [ApplicationVendor](../../aspose.threed/assetinfo/applicationvendor/) { get; set; } | Получает или задает название поставщика приложения |
| [ApplicationVersion](../../aspose.threed/assetinfo/applicationversion/) { get; set; } | Получает или задает версию приложения, создавшего этот объект. |
| [Author](../../aspose.threed/assetinfo/author/) { get; set; } | Получает или задает автора этого объекта |
| [AxisSystem](../../aspose.threed/assetinfo/axissystem/) { get; set; } | Получает или задает систему координат, вектор вверх и вектор передней части информации об объекте. |
| [Comment](../../aspose.threed/assetinfo/comment/) { get; set; } | Получает или задает комментарий к этому объекту. |
| [CoordinateSystem](../../aspose.threed/assetinfo/coordinatesystem/) { get; set; } | Получает или задает систему координат, используемую в этом объекте. |
| [Copyright](../../aspose.threed/assetinfo/copyright/) { get; set; } | Получает или задает авторские права документа |
| [CreationTime](../../aspose.threed/assetinfo/creationtime/) { get; set; } | Получает или задает время создания этого объекта |
| [FrontVector](../../aspose.threed/assetinfo/frontvector/) { get; set; } | Получает или задает вектор передней части, используемый в этом объекте. |
| [Keywords](../../aspose.threed/assetinfo/keywords/) { get; set; } | Получает или задает ключевые слова этого объекта |
| [ModificationTime](../../aspose.threed/assetinfo/modificationtime/) { get; set; } | Получает или задает время изменения этого объекта |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [Revision](../../aspose.threed/assetinfo/revision/) { get; set; } | Получает или задает номер ревизии этого объекта, обычно используемый в системе контроля версий. |
| [Subject](../../aspose.threed/assetinfo/subject/) { get; set; } | Получает или задает тему этого объекта |
| [Title](../../aspose.threed/assetinfo/title/) { get; set; } | Получает или задает заголовок этого объекта |
| [UnitName](../../aspose.threed/assetinfo/unitname/) { get; set; } | Получает или задает единицу длины, используемую в этом объекте, например: см/м/км/дюйм/фут |
| [UnitScaleFactor](../../aspose.threed/assetinfo/unitscalefactor/) { get; set; } | Получает или задает коэффициент масштабирования к реальному метру. |
| [UpVector](../../aspose.threed/assetinfo/upvector/) { get; set; } | Получает или задает вектор вверх, используемый в этом объекте. |
| [Url](../../aspose.threed/assetinfo/url/) { get; set; } | Получает или задает URL этого объекта. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

## Примеры

Следующий код показывает, как прочитать информацию об объекте из файла fbx:

```csharp
Scene scene = Scene.FromFile("test.fbx");
Console.WriteLine($"The file is created at {scene.AssetInfo.CreationTime} by {scene.AssetInfo.ApplicationName} {scene.AssetInfo.ApplicationVersion} ");
```

### См. также

* class [A3DObject](../a3dobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


