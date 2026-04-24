---
title: ライセンス
second_title: Aspose.3D for Java API リファレンス
description: コンポーネントをライセンスするためのメソッドを提供します。
type: docs
weight: 93
url: /ja/java/com.aspose.threed/license/
---

**Inheritance:**
java.lang.Object
```
public class License
```

コンポーネントをライセンスするためのメソッドを提供します。

詳細を知りたい場合は、**Licensing and Subscription** のドキュメント記事をご覧ください。
## Constructors

| Constructor | 説明 |
| --- | --- |
| [License()](#License--) | このクラスの新しいインスタンスを初期化します。 |
## Methods

| Method | 説明 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setLicense(InputStream stream)](#setLicense-java.io.InputStream-) | コンポーネントにライセンスを付与します。 |
| [setLicense(String licenseName)](#setLicense-java.lang.String-) | コンポーネントにライセンスを付与します。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### License() {#License--}
```
public License()
```


このクラスの新しいインスタンスを初期化します。

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
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
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




### setLicense(InputStream stream) {#setLicense-java.io.InputStream-}
```
public void setLicense(InputStream stream)
```


コンポーネントにライセンスを付与します。

このメソッドを使用して、ストリームからライセンスをロードします。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| ストリーム | java.io.InputStream | ライセンスを含むストリーム。 |

### setLicense(String licenseName) {#setLicense-java.lang.String-}
```
public void setLicense(String licenseName)
```


コンポーネントにライセンスを付与します。

次の場所でライセンスを検索します:

1. 明示的なパス。

2. Aspose コンポーネントの JAR ファイルが含まれるフォルダー。

3. クライアントの呼び出し JAR ファイルが含まれるフォルダー。

**Parameters:**
| Parameter | Type | 説明 |
| --- | --- | --- |
| licenseName | java.lang.String | 完全なファイル名または短いファイル名を指定できます。空文字列を使用すると評価モードに切り替わります。 |

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

