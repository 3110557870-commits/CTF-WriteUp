# [极客大挑战 2019]Havefun

## 题目信息

- 平台：BUUCTF
- 题型：Web
- 难度：⭐

## 考点

- PHP 代码审计
- GET 参数传递
- 源代码信息泄露

## 解题过程

### 1. 打开环境

访问题目给出的 URL，页面显示一只猫，没有任何输入框或交互功能。

### 2. 查看源代码
<img width="419" height="113" alt="image" src="https://github.com/user-attachments/assets/ccc5c1c1-590c-4bbf-9fe0-58ff495ecc3c" />
注释中说让cat=dog可以得到结果故

使用php语句：/index.php?cat=dog
