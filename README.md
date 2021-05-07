# C++ Kick Start 

C++ 编程 Kick Start 包括三小时的C++语言基础、算法掌握能力笔试挑战考察。

## 提交回答流程
1. 复制或者fork本题目至本地文本编辑器
2. 答题～
3. 填写姓名，年龄，籍贯，学校名称&专业，工作年限
4. 提交电子文档至 tech_support@shconnet.com.cn 并联系试题考察 Admin。
5. 等待反馈

其中包含三部分内容，1.基础、2.算法、3.工程经验
在 `?` 处填写答案

## 基础

### 1. 请写出数据结构的时间复杂度

### vector:
| push_back | pop_back | insert | erase | clear | emplace_back | emplace |
| ---------  |--| --| -- | -- | -- | -- |
| O(?) | O(?) | O(?) | O(?) | O(?) | O(?) | O(?) |

### list:
| push_front | push_back | pop_back | insert | erase | emplace_back |
| ---------  |--| --| -- | -- | -- |
| O(?) | O(?) | O(?) | O(?) | O(?) | O(?) |

### map:
| insert | erase | clear |
| ---------  |--| --| 
| O(?) | O(?) | O(?) |

### 2. 设计一个函数 std::vector<std::vector<int>> `purmutate_list`(std::vector<int>& in) 要求输出数组所有交换组合。

举例:
``` cpp
std::vector<int> numbers {7,9,11,-5,20};
purmutate_list(numbers);
// output
// (7),(7,9),(9,7),...,(7,9,11), ..... (7,9,11,-5,20),(20,-5,11,9,7)
```
解答:
???

## 算法

### 3. 现有重量为 [1,33,56,76,30,60,51,61,21,3,6,10,7,14,32,43]， 吨的货物需要运输，每辆卡车有限载重是100吨，计算出至少需要多少量卡车存放货物，并返回货物在列表中的数组下标索引号。(加分:在最少卡车数量的前提下尽可能的均匀分配，使得每辆卡车配重公平)

举例:
``` cpp
std::vector<int> cargos {7,9,81,70};
const int MAX_TRUCK_LOAD = 100;
distribute_trucks(cargos, MAX_TRUCK_LOAD);

// output
// Truck1: [0,2] --> cargos: {7,81} ---> SUM: 88
// Truck2: [1,3] --> cargos: {9,70} ---> SUM: 79
```


## 工程
### 4. 请简述 MVC 的设计理念
### 5. 请简述控制反转的框架API设计理念
### 6. 请简述命令式编程和声明式编程的区别
