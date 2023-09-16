# 编译原理 作业1

王田雨 2000012903

## 3.3.2

### 1

由a、b组成，且以a开始和结尾的字符串

### 2

由a、b组成的字符串

### 3

由a、b组成，且倒数第三位为a的字符串

### 4

由a、b组成，且包含3个b的字符串

### 5

由a、b组成，且a、b个数均为偶数的字符串

## 3.3.3

### 1

$ n+1$

### 2

$ n+1$

### 3

$ n-1$

### 4

$ \frac{n(n + 1)}{2} + 1$

### 5

$2^n$

## 3.3.5

### 1

$\sum=\{a,b,c,d,...,z\}$

$S \rightarrow$ `^[^aeiou]*a[^eiou]*e[^aiou]*i[^aeou]*o[^aeiu]*u[^aeio]*`

### 2

$\sum=\{a,b,c,d,...,z\}$

$S \rightarrow$ `a*b*c*d*...z*`

### 3

引号一定匹配

$S \rightarrow$ `"/*"(\"[^\"]*\"|[^\*\"]|\*[^\/\"])*"*/"`

### 6

$S \rightarrow$ `(aa|bb)*((ab|ba)(aa|bb)*(ab|ba)(aa|bb)*)*b(aa|bb)*((ab|ba)(aa|bb)*(ab|ba)(aa|bb)*)*`

### 9

$S \rightarrow$ `b*a*b?a*`
