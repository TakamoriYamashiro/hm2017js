# hm2017js

JavaScript(以下JS)の練習用です。

## JSを記述する場所

```
<script>
//ここにJSを記述
</script>
```

## JSを外部から読み込み

```
<script src="ファイルのパス"></script>
```

## 変数の宣言

int,charなどの型は指定せずにすべて varで宣言  
内部的に型は保持される。

```
var a = '12';
var b = 24;
var c = a+b;
console.log(c); // String型とint型がまざっており '1224'と出力される

```

```
var a = parseInt('12'); //int型にキャスト
var b = 24;
var c = a+b;
console.log(c); // int型同士で加算され 36と出力される
```

## 配列

配列の使い方。

```
var arr1 = [100,23,444];
console.log(arr1);

var arr2 = ['apple','orange','pen'];
console.log(arr2);

var arr3 = ['apple',30,'human'];
console.log(arr3);

```





