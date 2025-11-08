# 前端 (JavaScript/HTML) 代码规范
(Frontend Code Style Guide)

## 来源声明 (Source Declaration)

本文档严格遵循 **Google JavaScript Style Guide** (谷歌 JavaScript 风格指南) 作为核心规范。

**官方链接:** [https://google.github.io/styleguide/jsguide.html](https://google.github.io/styleguide/jsguide.html)

---

## 关键规范摘要

### 1. 格式化 (Formatting)
* **缩进:** 必须使用 **2 个空格** 进行缩进。(注意：不是 Python 的 4 个！)
* **行长:** 每行代码最大长度不应超过 **80 个字符**。
* **分号:** **所有**语句结尾都**必须**加分号 (`;`)。

### 2. 命名规范 (Naming Conventions)
* **函数/变量:** `camelCase` (小驼峰命名法), 例如 `listBody` 或 `fetchContacts`。
* **类名/构造函数:** `PascalCase` (大驼峰命名法)。
* **常量:** `CONSTANT_CASE` (全大写+下划线), 例如 `const API_BASE_URL`。

### 3. 字符串 (Strings)
* 优先使用**单引号** (`'`) 来定义字符串，而不是双引号 (`"`)。

### 4. 变量声明 (Variables)
* **禁止**使用 `var`。
* 优先使用 `const` (用于不改变的常量)。
* 仅在变量需要被重新赋值时才使用 `let`。

### 5. 控制结构 (Braces)
* **所有**控制结构（`if`, `else`, `for`, `while`）都**必须**使用花括号 (`{}`)，即使只有一行代码，以防止出错。
* 花括号遵循 K&R 风格（左花括号 ` { ` 不换行）。
