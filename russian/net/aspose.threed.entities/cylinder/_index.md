---
title: "Класс Cylinder"
second_title: "Справочник API Aspose.3D для .NET"
description: "Класс Aspose.ThreeD.Entities.Cylinder. Параметрический цилиндр. Его также можно использовать для представления конуса, когда один из параметров radiusTop/radiusBottom равен нулю"
type: docs
weight: 360
url: /ru/net/aspose.threed.entities/cylinder/
---
## Cylinder class

Параметрический цилиндр. Его также можно использовать для представления конуса, когда один из параметров radiusTop/radiusBottom равен нулю.

```csharp
public class Cylinder : Primitive
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Cylinder](cylinder/#constructor)() | Инициализирует новый экземпляр класса `Cylinder`. |
| [Cylinder](cylinder/#constructor_1)(double, double) | Инициализирует новый экземпляр класса `Cylinder`. |
| [Cylinder](cylinder/#constructor_2)(double, double, double) | Инициализирует новый экземпляр класса `Cylinder`. |
| [Cylinder](cylinder/#constructor_3)(double, double, double, int, int, bool) | Инициализирует новый экземпляр класса `Cylinder`. |
| [Cylinder](cylinder/#constructor_4)(string, double, double, double, int, int, bool, double, double) | Инициализирует новый экземпляр класса `Cylinder`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CastShadows](../../aspose.threed.entities/primitive/castshadows/) { get; set; } | Получает или задает, может ли эта геометрия отбрасывать тень |
| [Excluded](../../aspose.threed/entity/excluded/) { get; set; } | Получает или задает, следует ли исключать эту сущность при экспорте. |
| [GenerateFanCylinder](../../aspose.threed.entities/cylinder/generatefancylinder/) { get; set; } | Получает или задает, генерировать ли цилиндр в виде веера, когда ThetaLength меньше 2*PI, иначе модель не будет разрезана. |
| [Height](../../aspose.threed.entities/cylinder/height/) { get; set; } | Получает или задает высоту цилиндра. |
| [HeightSegments](../../aspose.threed.entities/cylinder/heightsegments/) { get; set; } | Получает или задаёт сегменты высоты. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [OffsetBottom](../../aspose.threed.entities/cylinder/offsetbottom/) { get; set; } | Получает или задает смещение трансформации вершин нижней стороны. |
| [OffsetTop](../../aspose.threed.entities/cylinder/offsettop/) { get; set; } | Получает или задает смещение трансформации вершин верхней стороны. |
| [OpenEnded](../../aspose.threed.entities/cylinder/openended/) { get; set; } | Получает или задает значение, указывающее, открытый ли этот `Cylinder`. Значение по умолчанию — false. |
| [ParentNode](../../aspose.threed/entity/parentnode/) { get; set; } | Получает или задает первый родительский узел; если установлен первый родительский узел, эта сущность будет отсоединена от остальных родительских узлов. |
| [ParentNodes](../../aspose.threed/entity/parentnodes/) { get; } | Получает все родительские узлы, сущность может быть присоединена к нескольким родительским узлам для инстанцирования геометрии |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RadialSegments](../../aspose.threed.entities/cylinder/radialsegments/) { get; set; } | Получает или задает радиальные сегменты. |
| [RadiusBottom](../../aspose.threed.entities/cylinder/radiusbottom/) { get; set; } | Получает или задает радиус нижней крышки цилиндра. |
| [RadiusTop](../../aspose.threed.entities/cylinder/radiustop/) { get; set; } | Получает или задает радиус верхней крышки цилиндра. |
| [ReceiveShadows](../../aspose.threed.entities/primitive/receiveshadows/) { get; set; } | Получает или задает, может ли эта геометрия принимать тени. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [ShearBottom](../../aspose.threed.entities/cylinder/shearbottom/) { get; set; } | Получает или задает сдвиговое преобразование нижней стороны, вектор хранит значение сдвига (по оси x, по оси z), измеренное в радианах, значение по умолчанию — (0, 0). |
| [ShearTop](../../aspose.threed.entities/cylinder/sheartop/) { get; set; } | Получает или задает сдвиговое преобразование верхней стороны, вектор хранит значение сдвига (по оси x, по оси z), измеренное в радианах, значение по умолчанию — (0, 0). |
| [ThetaLength](../../aspose.threed.entities/cylinder/thetalength/) { get; set; } | Получает или задает длину θ. Значение по умолчанию — 2π. |
| [ThetaStart](../../aspose.threed.entities/cylinder/thetastart/) { get; set; } | Получает или задает начальное значение θ. Значение по умолчанию — 0. |

## Методы

| Имя | Описание |
| --- | --- |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetBoundingBox](../../aspose.threed/entity/getboundingbox/)() | Получает ограничивающий параллелепипед текущей сущности в её системе координат объектного пространства. |
| virtual [GetEntityRendererKey](../../aspose.threed/entity/getentityrendererkey/)() | Получает ключ рендерера сущности, зарегистрированного в рендерере |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |
| override [ToMesh](../../aspose.threed.entities/cylinder/tomesh/)() | Преобразовать текущий объект в сетку |

### См. также

* class [Primitive](../primitive/)
* namespace [Aspose.ThreeD.Entities](../../aspose.threed.entities/)
* assembly [Aspose.3D](../../)


