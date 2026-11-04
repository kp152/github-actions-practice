# API 说明

## calculator 模块

简单的计算器，目前提供加法和乘法两个函数。

### add(a, b)

返回两个数的和。

参数：
- a (int/float): 加数
- b (int/float): 被加数

返回值：int/float，a + b

示例：

    from calculator import add
    result = add(2, 3)  # 5

---

### multiply(a, b)

返回两个数的乘积。

参数：
- a (int/float): 乘数
- b (int/float): 被乘数

返回值：int/float，a * b

示例：

    from calculator import multiply
    result = multiply(3, 4)  # 12

## pytest 测试

项目使用 pytest 进行单元测试，测试文件为 test_calculator.py：

| 测试用例 | 说明 |
|----------|------|
| test_add | 测试加法函数（含正数、负数） |
| test_multiply | 测试乘法函数（含零值） |

运行方式：

    pytest -v