---
title: "Scene"
second_title: "Aspose.3D для Node.js через Java API Reference"
description: 
type: docs

url: /ru/nodejs-java/aspose.threed/scene/
---
## Scene class

Сцена — это объект верхнего уровня, содержащий узлы, геометрию, материалы, текстуры, анимацию, позы, подп сцены и т.д.  Сцена может иметь подп сцены, обеспечивая поддержку нескольких документов в файлах вроде collada/blender/fbx.  Иерархию узлов можно получить через RootNodeLibrary, который используется для хранения ссылок на несвязанные объекты во время сериализации (например, метаданные или пользовательские объекты), чтобы их можно было использовать как библиотеку.


## Методы

### constructor{#constructor}

| Имя | Описание |
| --- | --- |
| constructor() | Инициализирует новый экземпляр класса Scene. |

 **Result:**



---


### constructor_overload{#constructor_overload}

| Имя | Описание |
| --- | --- |
| constructor_overload(entity) | Инициализирует новый экземпляр класса Scene с сущностью, присоединённой к новому узлу. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| entity | Entity | Исходная сущность, присоединённая к сцене |

 **Result:**



---


### constructor_overload2{#constructor_overload2}

| Имя | Описание |
| --- | --- |
| constructor_overload2(parentScene, name) | Инициализирует новый экземпляр класса Scene как под-сцену. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| parentScene | Scene | Родительская сцена. |
| name | String | Имя сцены. |

 **Result:**



---


### constructor_overload3{#constructor_overload3}

| Имя | Описание |
| --- | --- |
| constructor_overload3(fileName) | Инициализирует новый экземпляр класса Scene и сразу открывает файл. Это устаревший конструктор, пожалуйста, используйте #Error Cref: M:Aspose.ThreeD.Scene.FromFile(System.String,System.Threading.CancellationToken). |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла для открытия. |

 **Result:**



---


### getSubScenes{#getSubScenes}

| Имя | Описание |
| --- | --- |
| getSubScenes() | Получает все под-сцены |

 **Result:**



---


### getLibrary{#getLibrary}

| Имя | Описание |
| --- | --- |
| getLibrary() | Объекты, которые не используются напрямую в иерархии сцены, могут быть определены в Library. Это полезно, когда вы используете под-сцены и размещаете переиспользуемые компоненты под под-сценами. |

 **Result:**



---


### getAnimationClips{#getAnimationClips}

| Имя | Описание |
| --- | --- |
| getAnimationClips() | Получает все AnimationClip, определённые в сцене. |

 **Result:**



---


### getCurrentAnimationClip{#getCurrentAnimationClip}

| Имя | Описание |
| --- | --- |
| getCurrentAnimationClip() | Получает или задает активный AnimationClip |

 **Result:**



---


### setCurrentAnimationClip{#setCurrentAnimationClip}

| Имя | Описание |
| --- | --- |
| setCurrentAnimationClip(value) | Получает или задает активный AnimationClip |

 **Result:**



---


### getAssetInfo{#getAssetInfo}

| Имя | Описание |
| --- | --- |
| getAssetInfo() | Получает или задает информацию о верхнеуровневом ресурсе. Информация о документе. |

 **Result:**



---


### setAssetInfo{#setAssetInfo}

| Имя | Описание |
| --- | --- |
| setAssetInfo(value) | Получает или задает информацию о верхнеуровневом ресурсе. Информация о документе. |

 **Result:**



---


### getPoses{#getPoses}

| Имя | Описание |
| --- | --- |
| getPoses() | Получает все Pose, используемые в этой сцене. Позиции. |

 **Result:**



---


### getRootNode{#getRootNode}

| Имя | Описание |
| --- | --- |
| getRootNode() | Получает корневой узел сцены. Корневой узел. |

 **Result:**



---


### getScene{#getScene}

| Имя | Описание |
| --- | --- |
| getScene() | Получает сцену, к которой принадлежит этот объект. |

 **Result:**



---


### getName{#getName}

| Имя | Описание |
| --- | --- |
| getName() | Получает или задает имя. Имя. |

 **Result:**



---


### setName{#setName}

| Имя | Описание |
| --- | --- |
| setName(value) | Получает или задает имя. Имя. |

 **Result:**



---


### getProperties{#getProperties}

| Имя | Описание |
| --- | --- |
| getProperties() | Получает коллекцию всех свойств. |

 **Result:**



---


### getAnimationClip{#getAnimationClip}

| Имя | Описание |
| --- | --- |
| getAnimationClip(name) | Получает именованный AnimationClip |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Эта |

 **Result:**
AnimationClip


---


### clear{#clear}

| Имя | Описание |
| --- | --- |
| clear() | Очищает содержимое сцены и восстанавливает настройки по умолчанию. |

 **Result:**
AnimationClip


---


### createAnimationClip{#createAnimationClip}

| Имя | Описание |
| --- | --- |
| createAnimationClip(name) | Сокращённая функция для создания и регистрации AnimationClip. Первый AnimationClip будет назначен CurrentAnimationClip |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| name | String | Имя анимационного клипа |

 **Result:**
AnimationClip


---


### open{#open}

| Имя | Описание |
| --- | --- |
| open(fileName, options) | Открывает сцену из указанного пути, используя заданный формат файла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| опции | LoadOptions | Более подробная конфигурация для открытия потока. |

 **Result:**
AnimationClip


---


### open{#open}

| Имя | Описание |
| --- | --- |
| open(fileName) | Открывает сцену из указанного пути |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |

 **Result:**
AnimationClip


---


### fromFile{#fromFile}

| Имя | Описание |
| --- | --- |
| fromFile(fileName) | Открывает сцену из указанного пути |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |

 **Result:**
AnimationClip


---


### save{#save}

| Имя | Описание |
| --- | --- |
| save(fileName) | Сохраняет сцену в указанный путь, используя заданный формат файла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |

 **Result:**
AnimationClip


---


### save{#save}

| Имя | Описание |
| --- | --- |
| save(fileName, format) | Сохраняет сцену в указанный путь, используя заданный формат файла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| format | FileFormat | Формат. |

 **Result:**
AnimationClip


---


### save{#save}

| Имя | Описание |
| --- | --- |
| save(fileName, options) | Сохраняет сцену в указанный путь, используя заданный формат файла. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| fileName | String | Имя файла. |
| опции | SaveOptions | Более подробная конфигурация для сохранения потока. |

 **Result:**
AnimationClip


---


### render{#render}

| Имя | Описание |
| --- | --- |
| render(camera, fileName) | Рендерит сцену во внешний файл с точки зрения указанной camera. Размер вывода по умолчанию 1024x768, а формат вывода — png |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С какой точки зрения camera следует отрендерить сцену |
| fileName | String | Имя файла вывода |

 **Result:**
AnimationClip


---


### render{#render}

| Имя | Описание |
| --- | --- |
| render(camera, fileName, size, format) | Рендерит сцену во внешний файл с точки зрения указанной camera. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С какой точки зрения camera следует отрендерить сцену |
| fileName | String | Имя файла вывода |
| size | Vector2 | Размер итогового отрендеренного изображения |
| format | String | Формат изображения выходного файла |

 **Result:**
AnimationClip


---


### render{#render}

| Имя | Описание |
| --- | --- |
| render(camera, fileName, size, format, options) | Рендерит сцену во внешний файл с точки зрения указанной camera. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С какой точки зрения camera следует отрендерить сцену |
| fileName | String | Имя файла вывода |
| size | Vector2 | Размер итогового отрендеренного изображения |
| format | String | Формат изображения выходного файла |
| опции | ImageRenderOptions | Опция для настройки некоторых внутренних параметров. |

 **Result:**
AnimationClip


---


### render{#render}

| Имя | Описание |
| --- | --- |
| render(camera, bitmap) | Отрисовать сцену в bitmap с точки зрения заданной камеры. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С какой точки зрения camera следует отрендерить сцену |
| bitmap | TextureData | Цель отрисованного результата |

 **Result:**
AnimationClip


---


### render{#render}

| Имя | Описание |
| --- | --- |
| render(camera, bitmap, options) | Отрисовать сцену в bitmap с точки зрения заданной камеры. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| camera | Camera | С какой точки зрения camera следует отрендерить сцену |
| bitmap | TextureData | Цель отрисованного результата |
| опции | ImageRenderOptions | Опция для настройки некоторых внутренних параметров. |

 **Result:**
AnimationClip


---


### removeProperty{#removeProperty}

| Имя | Описание |
| --- | --- |
| removeProperty(property) | Удаляет динамическое свойство. |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | Property | Какое свойство удалить |

 **Result:**
boolean


---


### removeProperty{#removeProperty}

| Имя | Описание |
| --- | --- |
| removeProperty(property) | Удалить указанное свойство, определённое по имени |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| propert | String | null |

 **Result:**
boolean


---


### getProperty{#getProperty}

| Имя | Описание |
| --- | --- |
| getProperty(property) | Получить значение указанного свойства |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | String | Имя свойства |

 **Result:**
Object


---


### setProperty{#setProperty}

| Имя | Описание |
| --- | --- |
| setProperty(property, value) | Устанавливает значение указанного свойства |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| property | String | Имя свойства |
| value | Object | Значение свойства |

 **Result:**
Object


---


### findProperty{#findProperty}

| Имя | Описание |
| --- | --- |
| findProperty(propertyName) | Находит свойство. Это может быть динамическое свойство (Created by CreateDynamicProperty/SetProperty) или нативное свойство (Identified by its name) |

 **Parameters:**

| Имя | Тип | Описание |
| --- | --- | --- |
| propertyName | String | Имя свойства. |

 **Result:**
Property


---



