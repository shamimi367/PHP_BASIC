# PHP基礎 02

## 動的型付
PHPは実行時にデータの型が決まる動的型付です。

## 四則演算
|  演算子  |  例  |
| ---- | ---- |
|  加算  |  a + b  |
|  減算  |  a - b  |
|  積  |  a * b  |
|  商  |  a / b  |
|  剰余  |  a % b  |

## 比較演算
|  演算子  |  結果  |
| ---- | ---- |
|  $a == $b  |  左辺と右辺は等しい  |
|  $a === $b  |  左辺と右辺が等しくかつ同じ型である  |
|  $a != $b  |  左辺と右辺が等しない  |
|  $a <> $b  |  左辺と右辺が等しない  |
|  $a < $b  |  左辺は右辺より小さい  |
|  $a <= $b  |  左辺は右辺以下である  |
|  $a > $b  |  左辺は右辺より大きい  |
|  $a >= $b  |  左辺は右辺以上である  |

詳細は下記URLにて確認  
https://www.php.net/manual/ja/language.operators.comparison.php

### 真偽値判定
boolean値以外、文字列や整数でも真偽値判定が可能。  
詳細は下記URLを参照  
https://www.php.net/manual/ja/types.comparisons.php  

## 条件分岐
```
//基本構文
if( <条件> ){
    //条件が真の時実行
}else{
    //条件が偽の時実行
}
```

## SWITCH構文
https://www.php.net/manual/ja/control-structures.switch.php　　

## 基本練習
https://github.com/takujiozaki/PHP_BASIC/tree/main/SAMPLE02