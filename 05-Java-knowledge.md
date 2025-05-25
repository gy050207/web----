# JavaScript 基础语法精要

## 1. 变量与常量
```javascript
// 使用let声明变量
let age = 22 

// 使用const声明常量
const TITLE = '不变的值'
```

## 2. 类型转换
```javascript
// 松散相等比较
console.log(18 == '10')  // true（值相等）

// 严格相等比较
console.log(18 === '10') // false（类型不同）

// 显式类型转换
console.log(18 + Number('10')) // 28
```

## 3. 流程控制
### 3.1 条件语句
```javascript
if(age >= 20) {
    console.log('可以领结婚证')
} else {
    console.log('不可以领结婚证')
}
```

### 3.2 循环结构
```javascript
// for循环
for(let i = 1; i < 10; i++){
    console.log(i)
}

// while循环
let temp = 70
while(temp > 60){
    console.log('喝水')
    temp -= 5
}
```

## 4. 函数基础
```javascript
// 无参函数
function sayHi() {
    console.log('hi')
}

// 带参函数
function sayHello(name) {
    console.log('hello ' + name)
}

// 函数调用
sayHi()
sayHello('World')
```

---
注意：实际文件内容与文件名存在偏差（JavaScript ≠ Java），建议后续：
1. 修正文件命名（例如改为05-JavaScript.html）
2. 补充ES6+新特性
3. 增加DOM操作示例