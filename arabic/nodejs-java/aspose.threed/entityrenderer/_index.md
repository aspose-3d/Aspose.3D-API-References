---
title: "EntityRenderer"
second_title: "مرجع Aspose.3D لـ Node.js عبر Java API"
description: 
type: docs

url: /ar/nodejs-java/aspose.threed/entityrenderer/
---
## EntityRenderer class

قم بإنشاء فئة فرعية من هذه لتطبيق العرض لأنواع مختلفة من الكيانات.


## الطرق

### constructor{#constructor}

| الاسم | الوصف |
| --- | --- |
| constructor(key, features) | منشئ EntityRenderer |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| key | String | المفتاح الخاص بـ entity renderer |
| features | byte | EntityRendererFeatures |

 **Result:**



---


### constructor_overload{#constructor_overload}

| الاسم | الوصف |
| --- | --- |
| constructor_overload(key) | منشئ EntityRenderer |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| key | String | المفتاح الخاص بـ entity renderer |

 **Result:**



---


### initialize{#initialize}

| الاسم | الوصف |
| --- | --- |
| initialize(renderer) | تهيئة entity renderer |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| rendere | عارض | null |

 **Result:**



---


### resetSceneCache{#resetSceneCache}

| الاسم | الوصف |
| --- | --- |
| resetSceneCache() | المشهد قد تغير أو أُزيل، تحتاج إلى تحرير موارد العرض على مستوى المشهد في هذا |

 **Result:**



---


### frameBegin{#frameBegin}

| الاسم | الوصف |
| --- | --- |
| frameBegin(renderer, renderQueue) | بدء عرض إطار |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عارض | عارض | العارض الحالي |
| renderQueue | IRenderQueue | قائمة العرض |

 **Result:**



---


### frameEnd{#frameEnd}

| الاسم | الوصف |
| --- | --- |
| frameEnd(renderer, renderQueue) | ينهي عرض إطار |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عارض | عارض | العارض الحالي |
| renderQueue | IRenderQueue | قائمة العرض |

 **Result:**



---


### prepareRenderQueue{#prepareRenderQueue}

| الاسم | الوصف |
| --- | --- |
| prepareRenderQueue(renderer, queue, node, entity) | تحضير أوامر العرض للزوج المحدد من العقدة/الكيان. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عارض | عارض | مثيل العارض الحالي |
| قائمة | IRenderQueue | قائمة العرض المستخدمة لإدارة مهام العرض |
| عقدة | عقدة | العقدة الحالية |
| كيان | كيان | الكيان الذي يحتاج إلى العرض |

 **Result:**



---


### renderEntity{#renderEntity}

| الاسم | الوصف |
| --- | --- |
| renderEntity(renderer, commandList, node, renderableResource, subEntity) | كل مهمة عرض تُدفع إلى com.aspose.threed.IRenderQueue ستحصل على استدعاء RenderEntity المقابل لتنفيذ مهمة العرض الفعلية. |

 **Parameters:**

| الاسم | النوع | الوصف |
| --- | --- | --- |
| عارض | عارض | المُعالج |
| commandList | ICommandList | قائمة commandList المستخدمة لتسجيل أوامر العرض |
| عقدة | عقدة | العقدة نفسها التي تم تمريرها إلى PrepareRenderQueue للكيان الذي سيتم عرضه |
| renderableResource | Object | الكائن المخصص الذي تم تمريره إلى IRenderQueue أثناء PrepareRenderQueue |
| subEntity | Number | فهرس sub entity الذي تم تمريره إلى IRenderQueue |

 **Result:**



---


### dispose{#dispose}

| الاسم | الوصف |
| --- | --- |
| dispose() | يتم التخلص من مُعالج الكيان، أطلق الموارد المشتركة. |

 **Result:**



---



