---
title: シーン
second_title: Aspose.3D for Java API リファレンス
description: 
type: docs
weight: 161
url: /ja/java/com.aspose.threed/scene/
---

**Inheritance:**
java.lang.Object、[com.aspose.threed.A3DObject](../../com.aspose.threed/a3dobject)、[com.aspose.threed.SceneObject](../../com.aspose.threed/sceneobject)
```
public class Scene extends SceneObject
```
## Constructors

| Constructor | 説明 |
| --- | --- |
| [Scene(Entity entity)](#Scene-com.aspose.threed.Entity-) | [Scene](../../com.aspose.threed/scene) クラスの新しいインスタンスを初期化し、エンティティを新しいノードに添付します。 |
| [Scene(Scene parentScene, String name)](#Scene-com.aspose.threed.Scene-java.lang.String-) | [Scene](../../com.aspose.threed/scene) クラスの新しいインスタンスをサブシーンとして初期化します。 |
| [Scene()](#Scene--) | [Scene](../../com.aspose.threed/scene) クラスの新しいインスタンスを初期化します。 |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [VERSION](#VERSION) | 現在のリリースバージョンを取得します |
## Methods

| Method | 説明 |
| --- | --- |
| [clear()](#clear--) | シーンの内容をクリアし、デフォルト設定を復元します。 |
| [createAnimationClip(String name)](#createAnimationClip-java.lang.String-) | ショートカット関数で [AnimationClip](../../com.aspose.threed/animationclip) を作成および登録します。最初の [AnimationClip](../../com.aspose.threed/animationclip) は [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) に割り当てられます。 |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [findProperty(String propertyName)](#findProperty-java.lang.String-) | プロパティを検索します。 |
| [fromFile(String fileName)](#fromFile-java.lang.String-) | 指定されたパスからシーンを開きます |
| [fromFile(String fileName, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.Cancellation-) | 指定されたパスからシーンを開きます |
| [fromFile(String fileName, FileFormat format)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます |
| [fromFile(String fileName, FileFormat format, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます |
| [fromFile(String fileName, LoadOptions options)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます |
| [fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)](#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます |
| [fromStream(Stream stream)](#fromStream-com.aspose.threed.Stream-) | 指定されたストリームからシーンを開きます |
| [fromStream(Stream stream, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | 指定されたストリームからシーンを開きます |
| [fromStream(Stream stream, FileFormat format)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、指定されたストリームからシーンを開きます |
| [fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、指定されたストリームからシーンを開きます |
| [fromStream(Stream stream, LoadOptions options)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | 指定されたIO設定を使用して、指定されたストリームからシーンを開きます |
| [fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 指定されたIO設定を使用して、指定されたストリームからシーンを開きます |
| [fromStream(InputStream stream)](#fromStream-java.io.InputStream-) | 指定されたストリームからシーンを開きます |
| [fromStream(InputStream stream, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-) | 指定されたストリームからシーンを開きます |
| [fromStream(InputStream stream, FileFormat format)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、指定されたストリームからシーンを開きます |
| [fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、指定されたストリームからシーンを開きます |
| [fromStream(InputStream stream, LoadOptions options)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-) | 指定されたIO設定を使用して、指定されたストリームからシーンを開きます |
| [fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 指定されたIO設定を使用して、指定されたストリームからシーンを開きます |
| [getAnimationClip(String name)](#getAnimationClip-java.lang.String-) | 名前付き [AnimationClip](../../com.aspose.threed/animationclip) を取得します |
| [getAnimationClips()](#getAnimationClips--) | シーンで定義されたすべての [AnimationClip](../../com.aspose.threed/animationclip) を取得します |
| [getAssetInfo()](#getAssetInfo--) | トップレベルのアセット情報を取得します |
| [getClass()](#getClass--) |  |
| [getCurrentAnimationClip()](#getCurrentAnimationClip--) | アクティブな [AnimationClip](../../com.aspose.threed/animationclip) を取得します |
| [getLibrary()](#getLibrary--) | シーン階層で直接使用されないオブジェクトは、ライブラリで定義できます。 |
| [getName()](#getName--) | 名前を取得します。 |
| [getPoses()](#getPoses--) | このシーンで使用されているすべての [Pose](../../com.aspose.threed/pose) を取得します |
| [getProperties()](#getProperties--) | すべてのプロパティのコレクションを取得します。 |
| [getProperty(String property)](#getProperty-java.lang.String-) | 指定されたプロパティの値を取得します |
| [getRootNode()](#getRootNode--) | シーンのルートノードを取得します |
| [getScene()](#getScene--) | このオブジェクトが属するシーンを取得します |
| [getSubScenes()](#getSubScenes--) | すべてのサブシーンを取得します |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [open(Stream stream)](#open-com.aspose.threed.Stream-) | 指定されたストリームからシーンを開きます |
| [open(Stream stream, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-) | 指定されたストリームからシーンを開きます |
| [open(Stream stream, FileFormat format)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、指定されたストリームからシーンを開きます |
| [open(Stream stream, FileFormat format, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、指定されたストリームからシーンを開きます |
| [open(Stream stream, LoadOptions options)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-) | 指定されたIO設定を使用して、指定されたストリームからシーンを開きます |
| [open(Stream stream, LoadOptions options, Cancellation cancellationToken)](#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 指定されたIO設定を使用して、指定されたストリームからシーンを開きます |
| [open(InputStream stream)](#open-java.io.InputStream-) | 指定されたストリームからシーンを開きます |
| [open(InputStream stream, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.Cancellation-) | 指定されたストリームからシーンを開きます |
| [open(InputStream stream, FileFormat format)](#open-java.io.InputStream-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、指定されたストリームからシーンを開きます |
| [open(InputStream stream, FileFormat format, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、指定されたストリームからシーンを開きます |
| [open(InputStream stream, LoadOptions options)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-) | 指定されたIO設定を使用して、指定されたストリームからシーンを開きます |
| [open(InputStream stream, LoadOptions options, Cancellation cancellationToken)](#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 指定されたIO設定を使用して、指定されたストリームからシーンを開きます |
| [open(String fileName)](#open-java.lang.String-) | 指定されたパスからシーンを開きます |
| [open(String fileName, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.Cancellation-) | 指定されたパスからシーンを開きます |
| [open(String fileName, FileFormat format)](#open-java.lang.String-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます |
| [open(String fileName, FileFormat format, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます |
| [open(String fileName, LoadOptions options)](#open-java.lang.String-com.aspose.threed.LoadOptions-) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます |
| [open(String fileName, LoadOptions options, Cancellation cancellationToken)](#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、指定されたパスからシーンを開きます |
| [removeProperty(Property property)](#removeProperty-com.aspose.threed.Property-) | 動的プロパティを削除します。 |
| [removeProperty(String property)](#removeProperty-java.lang.String-) | 名前で識別される指定されたプロパティを削除します |
| [render(Camera camera, TextureData bitmap)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-) | 指定されたカメラの視点からシーンをビットマップにレンダリングします |
| [render(Camera camera, TextureData bitmap, ImageRenderOptions options)](#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-) | 指定されたカメラの視点からシーンをビットマップにレンダリングします |
| [render(Camera camera, String fileName)](#render-com.aspose.threed.Camera-java.lang.String-) | 指定されたカメラの視点からシーンを外部ファイルにレンダリングします |
| [render(Camera camera, String fileName, Vector2 size, String format)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-) | 指定されたカメラの視点からシーンを外部ファイルにレンダリングします |
| [render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)](#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-) | 指定されたカメラの視点からシーンを外部ファイルにレンダリングします |
| [save(Stream stream, FileFormat format)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、シーンをストリームに保存します |
| [save(Stream stream, FileFormat format, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、シーンをストリームに保存します |
| [save(Stream stream, SaveOptions options)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-) | 指定されたファイル形式を使用して、シーンをストリームに保存します |
| [save(Stream stream, SaveOptions options, Cancellation cancellationToken)](#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、シーンをストリームに保存します |
| [save(OutputStream stream, FileFormat format)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、シーンをストリームに保存します |
| [save(OutputStream stream, FileFormat format, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、シーンをストリームに保存します |
| [save(OutputStream stream, SaveOptions options)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-) | 指定されたファイル形式を使用して、シーンをストリームに保存します |
| [save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)](#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、シーンをストリームに保存します |
| [save(String fileName)](#save-java.lang.String-) | 指定されたファイル形式を使用して、シーンを指定されたパスに保存します。 |
| [save(String fileName, FileFormat format)](#save-java.lang.String-com.aspose.threed.FileFormat-) | 指定されたファイル形式を使用して、シーンを指定されたパスに保存します。 |
| [save(String fileName, FileFormat format, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、シーンを指定されたパスに保存します。 |
| [save(String fileName, SaveOptions options)](#save-java.lang.String-com.aspose.threed.SaveOptions-) | 指定されたファイル形式を使用して、シーンを指定されたパスに保存します。 |
| [save(String fileName, SaveOptions options, Cancellation cancellationToken)](#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-) | 指定されたファイル形式を使用して、シーンを指定されたパスに保存します。 |
| [setAssetInfo(AssetInfo value)](#setAssetInfo-com.aspose.threed.AssetInfo-) | トップレベルのアセット情報を設定します。 |
| [setCurrentAnimationClip(AnimationClip value)](#setCurrentAnimationClip-com.aspose.threed.AnimationClip-) | アクティブな[AnimationClip](../../com.aspose.threed/animationclip)を設定します。 |
| [setName(String value)](#setName-java.lang.String-) | 名前を設定します。 |
| [setProperty(String property, Object value)](#setProperty-java.lang.String-java.lang.Object-) | 指定されたプロパティの値を設定します |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Scene(Entity entity) {#Scene-com.aspose.threed.Entity-}
```
public Scene(Entity entity)
```


[Scene](../../com.aspose.threed/scene) クラスの新しいインスタンスを初期化し、エンティティを新しいノードに添付します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | entity | [Entity](../../com.aspose.threed/entity) | シーンにアタッチされた最初のエンティティ **Example:** 以下のコードは、[Entity](../../com.aspose.threed/entity) から直接 [getScene](../../com.aspose.threed/scene\#getScene) を作成する方法を示しています。 |

```
var scene = new Scene(new Box());
``` |

### Scene(Scene parentScene, String name) {#Scene-com.aspose.threed.Scene-java.lang.String-}
```
public Scene(Scene parentScene, String name)
```


[Scene](../../com.aspose.threed/scene) クラスの新しいインスタンスをサブシーンとして初期化します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| parentScene | [Scene](../../com.aspose.threed/scene) | 親シーンです。 |
| name | java.lang.String | シーンの名前。 |

### Scene() {#Scene--}
```
public Scene()
```


[Scene](../../com.aspose.threed/scene) クラスの新しいインスタンスを初期化します。

### VERSION {#VERSION}
```
public static final String VERSION
```


現在のリリースバージョンを取得します

### clear() {#clear--}
```
public void clear()
```


シーンの内容をクリアし、デフォルト設定を復元します。

### createAnimationClip(String name) {#createAnimationClip-java.lang.String-}
```
public AnimationClip createAnimationClip(String name)
```


ショートカット関数で [AnimationClip](../../com.aspose.threed/animationclip) を作成および登録します。最初の [AnimationClip](../../com.aspose.threed/animationclip) は [getCurrentAnimationClip](../../com.aspose.threed/scene\#getCurrentAnimationClip) に割り当てられます。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | アニメーションクリップの名前 |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - A new animation clip instance with given name
### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### findProperty(String propertyName) {#findProperty-java.lang.String-}
```
public Property findProperty(String propertyName)
```


プロパティを検索します。動的プロパティ（CreateDynamicProperty/SetProperty により作成）またはネイティブプロパティ（名前で識別）になる可能性があります。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| propertyName | java.lang.String | プロパティ名。 |

**Returns:**
[Property](../../com.aspose.threed/property) - The property.
### fromFile(String fileName) {#fromFile-java.lang.String-}
```
public static Scene fromFile(String fileName)
```


指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, Cancellation cancellationToken)
```


指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-}
```
public static Scene fromFile(String fileName, FileFormat format)
```


指定されたファイル形式を使用して、指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, FileFormat format, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-}
```
public static Scene fromFile(String fileName, LoadOptions options)
```


指定されたファイル形式を使用して、指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromFile(String fileName, LoadOptions options, Cancellation cancellationToken) {#fromFile-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromFile(String fileName, LoadOptions options, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream) {#fromStream-com.aspose.threed.Stream-}
```
public static Scene fromStream(Stream stream)
```


指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, Cancellation cancellationToken)
```


指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(Stream stream, FileFormat format)
```


指定されたファイル形式を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(Stream stream, LoadOptions options)
```


指定されたIO設定を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


指定されたIO設定を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream) {#fromStream-java.io.InputStream-}
```
public static Scene fromStream(InputStream stream)
```


指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 **Example:** 以下のコードは、キャンセルトークンソースを使用してストリームからシーンを作成する方法を示しています。 |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, Cancellation cancellationToken)
```


指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン **Example:** 以下のコードは、キャンセルトークンソースを使用してストリームからシーンを作成する方法を示しています。 |

```
var cts = new Cancellation();    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, cts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public static Scene fromStream(InputStream stream, FileFormat format)
```


指定されたファイル形式を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 **Example:** 以下のコードは、ストリームからシーンを作成する方法を示しています。 |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン **Example:** 以下のコードは、ストリームからシーンを作成する方法を示しています。 |

```
try(InputStream input = new FileInputStream("input.fbx")) {    
          Scene scene = Scene.fromStream(input);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public static Scene fromStream(InputStream stream, LoadOptions options)
```


指定されたIO設定を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 **Example:** 以下のコードは、ロードオプションを使用してストリームからシーンを作成する方法を示しています。 |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#fromStream-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public static Scene fromStream(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


指定されたIO設定を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン **Example:** 以下のコードは、ロードオプションを使用してストリームからシーンを作成する方法を示しています。 |

```
var opts = new FbxLoadOptions();    
     opts.getLookupPaths().add("textures");    
     try(InputStream input = new FileInputStream("input.fbx")) {    
         Scene scene = Scene.fromStream(input, opts);    
      }
``` |

**Returns:**
[Scene](../../com.aspose.threed/scene)
### getAnimationClip(String name) {#getAnimationClip-java.lang.String-}
```
public AnimationClip getAnimationClip(String name)
```


名前付き [AnimationClip](../../com.aspose.threed/animationclip) を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| name | java.lang.String | [AnimationClip](../../com.aspose.threed/animationclip) を検索するための名前 |

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - Returned AnimationClip
### getAnimationClips() {#getAnimationClips--}
```
public List<AnimationClip> getAnimationClips()
```


シーンで定義されたすべての [AnimationClip](../../com.aspose.threed/animationclip) を取得します

**Returns:**
java.util.List<com.aspose.threed.AnimationClip> - シーン内で定義されたすべての[AnimationClip](../../com.aspose.threed/animationclip)。
### getAssetInfo() {#getAssetInfo--}
```
public AssetInfo getAssetInfo()
```


トップレベルのアセット情報を取得します

**Returns:**
[AssetInfo](../../com.aspose.threed/assetinfo) - the top-level asset information **Example:** The following code shows how to read the application information from a FBX file:

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
```
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCurrentAnimationClip() {#getCurrentAnimationClip--}
```
public AnimationClip getCurrentAnimationClip()
```


アクティブな [AnimationClip](../../com.aspose.threed/animationclip) を取得します

**Returns:**
[AnimationClip](../../com.aspose.threed/animationclip) - the active [AnimationClip](../../com.aspose.threed/animationclip)
### getLibrary() {#getLibrary--}
```
public List<A3DObject> getLibrary()
```


シーン階層で直接使用されていないオブジェクトはライブラリで定義できます。サブシーンを使用し、再利用可能なコンポーネントをサブシーンの下に配置する場合に便利です。

**Returns:**
java.util.List<com.aspose.threed.A3DObject> - シーン階層で直接使用されていないオブジェクトはライブラリで定義できます。サブシーンを使用し、再利用可能なコンポーネントをサブシーンの下に配置する場合に便利です。
### getName() {#getName--}
```
public String getName()
```


名前を取得します。

**Returns:**
java.lang.String - 名前です。
### getPoses() {#getPoses--}
```
public Collection<Pose> getPoses()
```


このシーンで使用されているすべての [Pose](../../com.aspose.threed/pose) を取得します

**Returns:**
java.util.Collection<com.aspose.threed.Pose> - このシーンで使用されているすべての[Pose](../../com.aspose.threed/pose)。
### getProperties() {#getProperties--}
```
public PropertyCollection getProperties()
```


すべてのプロパティのコレクションを取得します。

**Returns:**
[PropertyCollection](../../com.aspose.threed/propertycollection) - the collection of all properties.
### getProperty(String property) {#getProperty-java.lang.String-}
```
public Object getProperty(String property)
```


指定されたプロパティの値を取得します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |

**Returns:**
java.lang.Object - 見つかったプロパティの値
### getRootNode() {#getRootNode--}
```
public Node getRootNode()
```


シーンのルートノードを取得します

**Returns:**
[Node](../../com.aspose.threed/node) - the root node of the scene. **Example:** The following code shows how to create a node with Box entity attached to the root node.

```
Scene scene = new Scene();
     scene.getRootNode().createChildNode(new Box());
     scene.save("box.stl");
```
### getScene() {#getScene--}
```
public Scene getScene()
```


このオブジェクトが属するシーンを取得します

**Returns:**
[Scene](../../com.aspose.threed/scene) - the scene that this object belongs to
### getSubScenes() {#getSubScenes--}
```
public List<Scene> getSubScenes()
```


すべてのサブシーンを取得します

**Returns:**
java.util.List<com.aspose.threed.Scene> - すべてのサブシーン
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### open(Stream stream) {#open-com.aspose.threed.Stream-}
```
public void open(Stream stream)
```


指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |

### open(Stream stream, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, Cancellation cancellationToken)
```


指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

### open(Stream stream, FileFormat format) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void open(Stream stream, FileFormat format)
```


指定されたファイル形式を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |

### open(Stream stream, FileFormat format, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

### open(Stream stream, LoadOptions options) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-}
```
public void open(Stream stream, LoadOptions options)
```


指定されたIO設定を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |

### open(Stream stream, LoadOptions options, Cancellation cancellationToken) {#open-com.aspose.threed.Stream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(Stream stream, LoadOptions options, Cancellation cancellationToken)
```


指定されたIO設定を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

### open(InputStream stream) {#open-java.io.InputStream-}
```
public void open(InputStream stream)
```


指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 **Example:** 以下のコードは、ストリームからシーンを開く方法を示しています。 |

```
var scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs);    
     }
``` |

### open(InputStream stream, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, Cancellation cancellationToken)
```


指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロード タスクのキャンセレーション トークン **Example:** 次のコードは、キャンセレーション トークンを使用してストリームからシーンを開く方法を示しています |

```
var scene = new Scene();    
     Cancellation cts = new Cancellation();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, cts);    
     }
``` |

### open(InputStream stream, FileFormat format) {#open-java.io.InputStream-com.aspose.threed.FileFormat-}
```
public void open(InputStream stream, FileFormat format)
```


指定されたファイル形式を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 **Example:** 次のコードは、ストリームからシーンを開く方法を示しています |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, FileFormat format, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロード タスクのキャンセレーション トークン **Example:** 次のコードは、ストリームからシーンを開く方法を示しています |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         scene.open(fs, FileFormat.GLTF2);    
     }
``` |

### open(InputStream stream, LoadOptions options) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-}
```
public void open(InputStream stream, LoadOptions options)
```


指定されたIO設定を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
|  | options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 **Example:** 次のコードは、追加のロード オプションを使用してストリームからシーンを開く方法を示しています |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(InputStream stream, LoadOptions options, Cancellation cancellationToken) {#open-java.io.InputStream-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(InputStream stream, LoadOptions options, Cancellation cancellationToken)
```


指定されたIO設定を使用して、指定されたストリームからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロード タスクのキャンセレーション トークン **Example:** 次のコードは、追加のロード オプションを使用してストリームからシーンを開く方法を示しています |

```
Scene scene = new Scene();    
     try(var fs = new FileInputStream("input.fbx")) {    
         var opt = new FbxLoadOptions();    
         opt.getLookupPaths().add("textures");    
         scene.open(fs, opt);    
     }
``` |

### open(String fileName) {#open-java.lang.String-}
```
public void open(String fileName)
```


指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |

### open(String fileName, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.Cancellation-}
```
public void open(String fileName, Cancellation cancellationToken)
```


指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

### open(String fileName, FileFormat format) {#open-java.lang.String-com.aspose.threed.FileFormat-}
```
public void open(String fileName, FileFormat format)
```


指定されたファイル形式を使用して、指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |

### open(String fileName, FileFormat format, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void open(String fileName, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | ファイル形式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

### open(String fileName, LoadOptions options) {#open-java.lang.String-com.aspose.threed.LoadOptions-}
```
public void open(String fileName, LoadOptions options)
```


指定されたファイル形式を使用して、指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |

### open(String fileName, LoadOptions options, Cancellation cancellationToken) {#open-java.lang.String-com.aspose.threed.LoadOptions-com.aspose.threed.Cancellation-}
```
public void open(String fileName, LoadOptions options, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、指定されたパスからシーンを開きます

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| options | [LoadOptions](../../com.aspose.threed/loadoptions) | ストリームを開くための詳細な構成。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | ロードタスクへのキャンセルトークン |

### removeProperty(Property property) {#removeProperty-com.aspose.threed.Property-}
```
public boolean removeProperty(Property property)
```


動的プロパティを削除します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| property | [Property](../../com.aspose.threed/property) | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### removeProperty(String property) {#removeProperty-java.lang.String-}
```
public boolean removeProperty(String property)
```


名前で識別される指定されたプロパティを削除します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | 削除するプロパティ |

**Returns:**
boolean - プロパティが正常に削除された場合は true
### render(Camera camera, TextureData bitmap) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-}
```
public void render(Camera camera, TextureData bitmap)
```


指定されたカメラの視点からシーンをビットマップにレンダリングします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | どのカメラの視点からシーンをレンダリングするか |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | レンダリング結果のターゲット |

### render(Camera camera, TextureData bitmap, ImageRenderOptions options) {#render-com.aspose.threed.Camera-com.aspose.threed.TextureData-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, TextureData bitmap, ImageRenderOptions options)
```


指定されたカメラの視点からシーンをビットマップにレンダリングします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | どのカメラの視点からシーンをレンダリングするか |
| bitmap | [TextureData](../../com.aspose.threed/texturedata) | レンダリング結果のターゲット |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | 内部設定の一部をカスタマイズするオプションです。 |

### render(Camera camera, String fileName) {#render-com.aspose.threed.Camera-java.lang.String-}
```
public void render(Camera camera, String fileName)
```


指定されたカメラの視点からシーンを外部ファイルにレンダリングします。デフォルトの出力サイズは 1024x768 で、出力形式は png です。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | どのカメラの視点からシーンをレンダリングするか |
| fileName | java.lang.String | 出力ファイルのファイル名 |

### render(Camera camera, String fileName, Vector2 size, String format) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-}
```
public void render(Camera camera, String fileName, Vector2 size, String format)
```


指定されたカメラの視点からシーンを外部ファイルにレンダリングします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | どのカメラの視点からシーンをレンダリングするか |
| fileName | java.lang.String | 出力ファイルのファイル名 |
| size | [Vector2](../../com.aspose.threed/vector2) | 最終的にレンダリングされた画像のサイズ |
| format | java.lang.String | 出力ファイルの画像形式 |

### render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options) {#render-com.aspose.threed.Camera-java.lang.String-com.aspose.threed.Vector2-java.lang.String-com.aspose.threed.ImageRenderOptions-}
```
public void render(Camera camera, String fileName, Vector2 size, String format, ImageRenderOptions options)
```


指定されたカメラの視点からシーンを外部ファイルにレンダリングします

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| camera | [Camera](../../com.aspose.threed/camera) | どのカメラの視点からシーンをレンダリングするか |
| fileName | java.lang.String | 出力ファイルのファイル名 |
| size | [Vector2](../../com.aspose.threed/vector2) | 最終的にレンダリングされた画像のサイズ |
| format | java.lang.String | 出力ファイルの画像形式 |
| options | [ImageRenderOptions](../../com.aspose.threed/imagerenderoptions) | 内部設定の一部をカスタマイズするオプションです。 |

### save(Stream stream, FileFormat format) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-}
```
public void save(Stream stream, FileFormat format)
```


指定されたファイル形式を使用して、シーンをストリームに保存します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 形式。 |

### save(Stream stream, FileFormat format, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、シーンをストリームに保存します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 形式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存タスクのキャンセレーション トークン |

### save(Stream stream, SaveOptions options) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-}
```
public void save(Stream stream, SaveOptions options)
```


指定されたファイル形式を使用して、シーンをストリームに保存します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | ストリームを保存するための詳細な構成です。 |

### save(Stream stream, SaveOptions options, Cancellation cancellationToken) {#save-com.aspose.threed.Stream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(Stream stream, SaveOptions options, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、シーンをストリームに保存します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| stream | [Stream](../../com.aspose.threed/stream) | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | ストリームを保存するための詳細な構成です。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存タスクのキャンセレーション トークン |

### save(OutputStream stream, FileFormat format) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-}
```
public void save(OutputStream stream, FileFormat format)
```


指定されたファイル形式を使用して、シーンをストリームに保存します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
|  | format | [FileFormat](../../com.aspose.threed/fileformat) | 形式。 **Example:** 次のコードは、シーンを保存する方法を示しています |

```
Scene scene = Scene.fromFile("input.fbx");    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ);    
     }
``` |

### save(OutputStream stream, FileFormat format, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、シーンをストリームに保存します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 形式。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存タスクのキャンセレーション トークン **Example:** 次のコードは、シーンを保存する方法を示しています |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, FileFormat.USDZ, cts);    
     }
``` |

### save(OutputStream stream, SaveOptions options) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-}
```
public void save(OutputStream stream, SaveOptions options)
```


指定されたファイル形式を使用して、シーンをストリームに保存します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
|  | options | [SaveOptions](../../com.aspose.threed/saveoptions) | ストリームを保存するための詳細な構成。 **Example:** 次のコードは、シーンを保存する方法を示しています |

```
Scene scene = Scene.fromFile("input.fbx");    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt);    
     }
``` |

### save(OutputStream stream, SaveOptions options, Cancellation cancellationToken) {#save-java.io.OutputStream-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(OutputStream stream, SaveOptions options, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、シーンをストリームに保存します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.OutputStream | 入力ストリーム、ユーザーはストリームのクローズを担当します。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | ストリームを保存するための詳細な構成です。 |
|  | cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存タスクのキャンセレーション トークン **Example:** 次のコードは、シーンを保存する方法を示しています |

```
Scene scene = Scene.fromFile("input.fbx");    
     var cts = new Cancellation();    
     var opt = new UsdSaveOptions();    
     opt.setPrimitiveToMesh(true);    
     try(var ms = new ByteArrayOutputStream())    
     {    
         scene.save(ms, opt, cts);    
     }
``` |

### save(String fileName) {#save-java.lang.String-}
```
public void save(String fileName)
```


指定されたファイル形式を使用して、シーンを指定されたパスに保存します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |

### save(String fileName, FileFormat format) {#save-java.lang.String-com.aspose.threed.FileFormat-}
```
public void save(String fileName, FileFormat format)
```


指定されたファイル形式を使用して、シーンを指定されたパスに保存します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 形式。 |

### save(String fileName, FileFormat format, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.FileFormat-com.aspose.threed.Cancellation-}
```
public void save(String fileName, FileFormat format, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、シーンを指定されたパスに保存します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| format | [FileFormat](../../com.aspose.threed/fileformat) | 形式。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存タスクのキャンセレーション トークン |

### save(String fileName, SaveOptions options) {#save-java.lang.String-com.aspose.threed.SaveOptions-}
```
public void save(String fileName, SaveOptions options)
```


指定されたファイル形式を使用して、シーンを指定されたパスに保存します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | ストリームを保存するための詳細な構成です。 |

### save(String fileName, SaveOptions options, Cancellation cancellationToken) {#save-java.lang.String-com.aspose.threed.SaveOptions-com.aspose.threed.Cancellation-}
```
public void save(String fileName, SaveOptions options, Cancellation cancellationToken)
```


指定されたファイル形式を使用して、シーンを指定されたパスに保存します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| fileName | java.lang.String | ファイル名。 |
| options | [SaveOptions](../../com.aspose.threed/saveoptions) | ストリームを保存するための詳細な構成です。 |
| cancellationToken | [Cancellation](../../com.aspose.threed/cancellation) | 保存タスクのキャンセレーション トークン |

### setAssetInfo(AssetInfo value) {#setAssetInfo-com.aspose.threed.AssetInfo-}
```
public void setAssetInfo(AssetInfo value)
```


トップレベルのアセット情報を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
|  | value | [AssetInfo](../../com.aspose.threed/assetinfo) | 新しい値 **Example:** 次のコードは、FBX ファイルからアプリケーション情報を読み取る方法を示しています： |

```
Scene scene = Scene.fromFile("test.fbx");
     System.out.printf("The FBX file is created by %s %s",
         scene.getAssetInfo().getApplicationName(),
         scene.getAssetInfo().getApplicationVersion());
``` |

### setCurrentAnimationClip(AnimationClip value) {#setCurrentAnimationClip-com.aspose.threed.AnimationClip-}
```
public void setCurrentAnimationClip(AnimationClip value)
```


アクティブな[AnimationClip](../../com.aspose.threed/animationclip)を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| value | [AnimationClip](../../com.aspose.threed/animationclip) | 新しい値 |

### setName(String value) {#setName-java.lang.String-}
```
public void setName(String value)
```


名前を設定します。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| 値 | java.lang.String | 新しい値 |

### setProperty(String property, Object value) {#setProperty-java.lang.String-java.lang.Object-}
```
public void setProperty(String property, Object value)
```


指定されたプロパティの値を設定します

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| プロパティ | java.lang.String | プロパティ名 |
| 値 | java.lang.Object | プロパティの値 |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final void wait(long arg0)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

