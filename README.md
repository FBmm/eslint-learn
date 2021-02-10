# eslint-learn

npm 脚本
```
# eslint 检测 src/main.js 文件
npm run lint

# 自动修复
npm run lint --fix
```

基本 eslint 配置
```js
"rules": {
    "semi": ["warn", "never"], // 警告 行尾分号
    "no-console": ["warn"], // 警告 console.log
    "no-debugger": ["warn"], // 警告 debugger
    "quotes": ["warn", "single"], // 推荐使用单引号
    "no-unreachable": ["warn"], // 警告 return、throw、continue 和 break 语句出现的代码
    "no-cond-assign": ["error"], // 禁止条件表达式中出现赋值操作符
    "no-constant-condition": ["error"], // 禁止在条件中使用常量表达式
    "no-dupe-args": ["error"], // 禁止 function 定义重名参数
    "no-dupe-keys": ["error"], // 禁止对象中出现重复的 key
    "no-duplicate-case": ["error"], // 禁止出现重复的 case 标签
    "no-empty": ["error"], // 禁止出现空语句块
    "no-extra-boolean-cast": ["error"], // 禁止不必要的布尔转换
    "no-extra-parens": ["error"], // 禁止不必要的括号
    "no-extra-semi": ["error"], // 禁止不必要的分号
    "no-func-assign": ["error"], // 禁止对 function 声明重新赋值
    "no-inner-declarations": ["error"], // 禁止在嵌套的块中出现变量声明或 function 声明
    "no-invalid-regexp": ["error"], // 禁止 RegExp 构造函数中存在无效的正则表达式字符串
    "no-irregular-whitespace": ["error"], // 禁止不规则的空白
    "no-obj-calls": ["error"], // 禁止把全局对象作为函数调用
    "no-sparse-arrays": ["error"], // 禁用稀疏数组
    "use-isnan": ["error"], // 要求使用 isNaN() 检查 NaN
    "valid-typeof": ["error"], // 验证 typeof 值
    "no-empty-pattern": ["error"], // 禁止使用空解构模式
    "no-global-assign": ["error"], // 禁止对原生对象或只读的全局对象进行赋值
    "no-redeclare": ["error"], // 禁止多次声明同一变量
    "no-unused-vars": ["error"], // 禁止出现未使用过的变量
    "no-class-assign": ["error"], // 禁止修改类声明的变量
    "no-const-assign": ["error"], // 禁止修改 const 声明的变量
}
```

