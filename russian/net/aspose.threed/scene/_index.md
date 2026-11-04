---
title: "Класс Scene"
second_title: "Справочник API Aspose.3D для .NET"
description: "Aspose.ThreeD.Scene класс. Сцена — это объект верхнего уровня, который содержит узлы, геометрии, материалы, текстуры, анимацию, позы, подсцены и т.д. Сцена может иметь подсцены, выступая в роли поддержки нескольких документов в файлах, таких как collada/blender/fbx. Иерархию узлов можно получить через RootNodeLibrary, который используется для хранения ссылки на отсоединённые объекты во время сериализации (например, метаданные или пользовательские объекты), чтобы их можно было использовать как библиотеку"
type: docs
weight: 2500
url: /ru/net/aspose.threed/scene/
---
## Scene class

Сцена — это объект верхнего уровня, который содержит узлы, геометрии, материалы, текстуры, анимацию, позы, подсцены и т.д. Сцена может иметь подсцены, выступая в роли поддержки нескольких документов в файлах, таких как collada/blender/fbx. Иерархию узлов можно получить через [`RootNode`](./rootnode/)[`Library`](./library/), который используется для хранения ссылки на отсоединённые объекты во время сериализации (например, метаданные или пользовательские объекты), чтобы их можно было использовать как библиотеку.

```csharp
public class Scene : SceneObject
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [Scene](scene/#constructor)() | Инициализирует новый экземпляр класса `Scene`. |
| [Scene](scene/#constructor_1)(Entity) | Инициализирует новый экземпляр класса `Scene` с сущностью, прикреплённой к новому узлу. |
| [Scene](scene/#constructor_2)(Scene, string) | Инициализирует новый экземпляр класса `Scene` как под-сцену. |

## Свойства

| Имя | Описание |
| --- | --- |
| [AnimationClips](../../aspose.threed/scene/animationclips/) { get; } | Получает все [`AnimationClip`](../../aspose.threed.animation/animationclip/) определённые в сцене. |
| [AssetInfo](../../aspose.threed/scene/assetinfo/) { get; set; } | Получает или задаёт информацию о верхнеуровневом ресурсе |
| [CurrentAnimationClip](../../aspose.threed/scene/currentanimationclip/) { get; set; } | Получает или задаёт активный [`AnimationClip`](../../aspose.threed.animation/animationclip/) |
| [Library](../../aspose.threed/scene/library/) { get; } | Объекты, которые не используются напрямую в иерархии сцены, могут быть определены в Library. Это полезно, когда вы используете sub-scenes и размещаете переиспользуемые компоненты под sub-scenes. |
| virtual [Name](../../aspose.threed/a3dobject/name/) { get; set; } | Получает или задает имя. |
| [Poses](../../aspose.threed/scene/poses/) { get; } | Получает все [`Pose`](../pose/) используемые в этой сцене. |
| [Properties](../../aspose.threed/a3dobject/properties/) { get; } | Получает коллекцию всех свойств. |
| [RootNode](../../aspose.threed/scene/rootnode/) { get; } | Получает корневой узел сцены. |
| [Scene](../../aspose.threed/sceneobject/scene/) { get; } | Получает сцену, к которой принадлежит этот объект |
| [SubScenes](../../aspose.threed/scene/subscenes/) { get; } | Получает все подсцены |

## Методы

| Имя | Описание |
| --- | --- |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile)(string) | Открывает сцену по указанному пути |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_3)(string, CancellationToken) | Открывает сцену по указанному пути |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_1)(string, FileFormat, CancellationToken) | Открывает сцену по указанному пути, используя указанный формат файла. |
| static [FromFile](../../aspose.threed/scene/fromfile/#fromfile_2)(string, LoadOptions, CancellationToken) | Открывает сцену по указанному пути, используя указанный формат файла. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_2)(Stream, CancellationToken) | Открывает сцену из указанного потока |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream)(Stream, FileFormat, CancellationToken) | Открывает сцену из указанного потока, используя указанный формат файла. |
| static [FromStream](../../aspose.threed/scene/fromstream/#fromstream_1)(Stream, LoadOptions, CancellationToken) | Открывает сцену из указанного потока, используя указанную конфигурацию ввода-вывода. |
| [Clear](../../aspose.threed/scene/clear/)() | Очищает содержимое сцены и восстанавливает настройки по умолчанию. |
| [CreateAnimationClip](../../aspose.threed/scene/createanimationclip/)(string) | Сокращённая функция для создания и регистрации [`AnimationClip`](../../aspose.threed.animation/animationclip/). Первый [`AnimationClip`](../../aspose.threed.animation/animationclip/) будет назначен в [`CurrentAnimationClip`](./currentanimationclip/). |
| [FindProperty](../../aspose.threed/a3dobject/findproperty/)(string) | Находит свойство. Это может быть динамическое свойство (Созданное с помощью CreateDynamicProperty/SetProperty) или нативное свойство(Определяемое по его имени) |
| [GetAnimationClip](../../aspose.threed/scene/getanimationclip/)(string) | Получает именованный [`AnimationClip`](../../aspose.threed.animation/animationclip/) |
| [GetProperty](../../aspose.threed/a3dobject/getproperty/)(string) | Получить значение указанного свойства |
| [Open](../../aspose.threed/scene/open/#open)(Stream) | Открывает сцену из указанного потока |
| [Open](../../aspose.threed/scene/open/#open_4)(string) | Открывает сцену по указанному пути |
| [Open](../../aspose.threed/scene/open/#open_3)(Stream, CancellationToken) | Открывает сцену из указанного потока |
| [Open](../../aspose.threed/scene/open/#open_8)(string, CancellationToken) | Открывает сцену по указанному пути |
| [Open](../../aspose.threed/scene/open/#open_6)(string, LoadOptions) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [Open](../../aspose.threed/scene/open/#open_1)(Stream, FileFormat, CancellationToken) | Открывает сцену из указанного потока, используя указанный формат файла. |
| [Open](../../aspose.threed/scene/open/#open_2)(Stream, LoadOptions, CancellationToken) | Открывает сцену из указанного потока, используя указанную конфигурацию ввода-вывода. |
| [Open](../../aspose.threed/scene/open/#open_5)(string, FileFormat, CancellationToken) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [Open](../../aspose.threed/scene/open/#open_7)(string, LoadOptions, CancellationToken) | Открывает сцену по указанному пути, используя указанный формат файла. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(Property) | Удаляет динамическое свойство. |
| [RemoveProperty](../../aspose.threed/a3dobject/removeproperty/)(string) | Удалить указанное свойство, определяемое по имени |
| [Render](../../aspose.threed/scene/render/#render_2)(Camera, string) | Рендерит сцену во внешний файл с точки зрения заданной камеры. Размер вывода по умолчанию — 1024x768, а формат вывода — png. |
| [Render](../../aspose.threed/scene/render/#render)(Camera, TextureData) | Рендерит сцену в bitmap с точки зрения заданной камеры. |
| [Render](../../aspose.threed/scene/render/#render_1)(Camera, TextureData, ImageRenderOptions) | Рендерит сцену в bitmap с точки зрения заданной камеры. |
| [Render](../../aspose.threed/scene/render/#render_3)(Camera, string, Vector2, string) | Рендерит сцену во внешний файл с точки зрения заданной камеры. |
| [Render](../../aspose.threed/scene/render/#render_4)(Camera, string, Vector2, string, ImageRenderOptions) | Рендерит сцену во внешний файл с точки зрения заданной камеры. |
| [Save](../../aspose.threed/scene/save/#save_4)(string) | Сохраняет сцену по указанному пути, используя указанный формат файла. |
| [Save](../../aspose.threed/scene/save/#save)(Stream, FileFormat) | Сохраняет сцену в поток, используя указанный формат файла. |
| [Save](../../aspose.threed/scene/save/#save_2)(Stream, SaveOptions) | Сохраняет сцену в поток, используя указанный формат файла. |
| [Save](../../aspose.threed/scene/save/#save_5)(string, FileFormat) | Сохраняет сцену по указанному пути, используя указанный формат файла. |
| [Save](../../aspose.threed/scene/save/#save_7)(string, SaveOptions) | Сохраняет сцену по указанному пути, используя указанный формат файла. |
| [Save](../../aspose.threed/scene/save/#save_1)(Stream, FileFormat, CancellationToken) | Сохраняет сцену в поток, используя указанный формат файла. |
| [Save](../../aspose.threed/scene/save/#save_3)(Stream, SaveOptions, CancellationToken) | Сохраняет сцену в поток, используя указанный формат файла. |
| [Save](../../aspose.threed/scene/save/#save_6)(string, FileFormat, CancellationToken) | Сохраняет сцену по указанному пути, используя указанный формат файла. |
| [Save](../../aspose.threed/scene/save/#save_8)(string, SaveOptions, CancellationToken) | Сохраняет сцену по указанному пути, используя указанный формат файла. |
| [SetProperty](../../aspose.threed/a3dobject/setproperty/)(string, object) | Устанавливает значение указанного свойства |

## Поля

| Имя | Описание |
| --- | --- |
| const [Version](../../aspose.threed/scene/version/) | Получает текущую версию релиза |

### См. также

* class [SceneObject](../sceneobject/)
* namespace [Aspose.ThreeD](../../aspose.threed/)
* assembly [Aspose.3D](../../)


