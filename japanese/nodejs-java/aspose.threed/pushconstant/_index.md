---
title: "PushConstant"
second_title: "Node.js 用 Java 経由の Aspose.3D API リファレンス"
description: 
type: docs

url: /ja/nodejs-java/aspose.threed/pushconstant/
---
## PushConstant class

プッシュ定数を介してシェーダーにデータを提供するユーティリティ。


## メソッド

### constructor{#constructor}

| 名前 | 説明 |
| --- | --- |
| constructor() | PushConstant のコンストラクタ |

 **Result:**



---


### write{#write}

| 名前 | 説明 |
| --- | --- |
| write(mat) | 行列を定数に書き込む |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| mat | FMatrix4 | 書き込む行列 |

 **Result:**



---


### write{#write}

| 名前 | 説明 |
| --- | --- |
| write(n) | int 値を定数に書き込む |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | 数 | null |

 **Result:**



---


### write{#write}

| 名前 | 説明 |
| --- | --- |
| write(f) | float 値を定数に書き込む |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | 数 | null |

 **Result:**



---


### write{#write}

| 名前 | 説明 |
| --- | --- |
| write(vec) | 4 成分ベクトルを定数に書き込む |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ve | FVector4 | null |

 **Result:**



---


### write{#write}

| 名前 | 説明 |
| --- | --- |
| write(vec) | 3 成分ベクトルを定数に書き込む |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| ve | FVector3 | null |

 **Result:**



---


### write{#write}

| 名前 | 説明 |
| --- | --- |
| write(x, y, z, w) | 4 成分ベクトルを定数に書き込む |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
|  | 数 | null |
|  | 数 | null |
|  | 数 | null |
|  | 数 | null |

 **Result:**



---


### commit{#commit}

| 名前 | 説明 |
| --- | --- |
| commit(stage, commandList) | 準備されたデータをグラフィックス パイプラインにコミットする。 |

 **Parameters:**

| 名前 | 型 | 説明 |
| --- | --- | --- |
| stage | 数 | ShaderStage |
| commandLis | ICommandList | null |

 **Result:**



---



