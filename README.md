# PHP

php 檔案開頭須先加上 `<?php`。檔案命名規則可為英文數字底線混合使用。檔案名稱第一個必為英文開頭。

## Step 1. variable 
> tips:
>  1. 變數開頭都是 `$` 開頭
>  2. 變數不能使用數字開頭, ex: $1test (錯誤的)

```
$money = 1000; 
```


## Step 2. data types

### 字串
> tips:
>  1. 字串可用單引號或雙引號包起來
>  2. 如果單引號須還要單引號，需要使用 '\' 跳脫字元
$string = 'Hello world!';
$string_2 = 'It\'s an apple.';

### 整數
```
$money = 1000;
```

### 浮點數
```
$pi = 3.1415;
```

### 布林值(真假值)
```
$status = true;
$status = false;
```

### 陣列
> tips
>  1. 中括號代表陣列
>  2. 可不用寫 array()，直接用 [] 中括號 簡略寫法

```
$array = array(1, 3.14, 'apple', false);
$array = [1, 3.14, 'hello', true];
```



## Step 3. simple array 
> tips:
>  1. 陣列起始位置為 0
>            0. 1. 2. 3. 4. 5

```
$fibonacci = [1, 1, 2, 3, 5, 8];
$fibonacci[4]; // 值為 5
```


## Step 4. if 判斷 

>1. 0 ~ 60 分，為 C
>2. 61 ~ 80  分，為 B
>3. 81 分以上，為 A

```
$score = 70;

if ($score > 0 && $score <= 60) {
    echo 'C';
}
else if ($score >= 61 && $score <= 80) {
    echo 'B';
}
else {
    echo 'A';
}
```

> 1. `>` 大於
> 2. `<` 小於
> 3. `==` 等於
> 4. `!=` 不等於
> 5. `>=` 大於等於
> 6. `<=` 小於等於 
> 7. `===` 完整比對(型態也是一樣的)