# JavaLocalClass
ローカルクラス

## 処理
[JavaClassAndObject](https://github.com/xekid78/JavaClassAndObject)の処理をローカルクロスにして見ました。

## コード
```
public class Sample43 {

	public static void main(String[] args) {

		class Msg {
			public void HelloWorld() {
				System.out.println("Hello World");
			}

		}

		Msg msg = new Msg();
		msg.HelloWorld();

	}

}
```

## 出力結果  
```
Hello World
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| 統合開発環境(IDE) | Eclipse 4.7.0 Oxygen |
| 開発言語 | Java8 |
