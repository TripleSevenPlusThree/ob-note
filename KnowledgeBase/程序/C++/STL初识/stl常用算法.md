![[20231018_171345 1.png|750]]
# 常用遍历算法
![[20231018_171354 1.png|800]]
1. for_each 
- 可以用函数，或者仿函数
![[20231018_192246.png|900]]
![[20231018_192621.png|900]]
![[20231018_192630.png|900]]
![[20231018_192638.png|900]]
2. tansform
![[20231018_193906.png|900]]
![[20231018_172857.png|850]]
![[20231018_172905.png|800]]

## 常用查找算法
![[20231018_172957.png|800]]
- 查找算法找到满足条件的的元素就会退出，即只能返回一个迭代器
1. find
![[20231018_194143.png|800]]
![[20231018_174346.png|800]]
![[20231018_174405.png|890]]
![[20231018_174440.png|800]]![[20231018_174512.png|800]]
3. find_if
![[20231018_174603.png|800]]
![[20231018_175857.png|800]] 
![[20231018_175916.png|800]]
![[20231018_175929.png]]
![[20231018_175938.png|800]]
6. adjacent_find
![[20231018_180007.png|800]]
![[20231018_180358.png|800]]
8. binary_search
- 注意：必须是有序序列
![[20231018_180411.png|800]]
![[20231018_180813.png|800]]
![[20231018_180818.png|800]]
1. 统计算法 count
- 自定义数据类型要重载 == ，bool类型，参数要加const
![[20231018_180848.png|800]]
![[20231018_181631.png|800]]
![[20231018_181708.png|800]]
![[20231018_181728.png|800]]
![[20231018_181734.png|800]]
2. count_if

### 排序算法
![[20231018_190248 1.png|800]]
1. sort
![[20231018_190344.png|800]]
![[20231018_190650.png|800]]
![[20231018_190657.png|800]]
3. random_shuffle
![[20231018_200114.png|800]]
![[20231018_191242.png|800]]
![[20231018_191259.png]]
- **<font color="#e36c09">注意：要加随机数种子，才能实现每次都是不同的打乱顺</font><font color="#e36c09">序</font>**
5. merge
![[20231018_191408.png|800]]
![[20231018_191835.png|800]]
![[20231018_191846.png|800]]
- 注意：两个容器的顺序必须是有序的；第三个容器要记得开辟空间
7. reverse
![[20231018_191903.png|800]]
![[20231018_192204.png|800]]
![[20231018_192216.png|800]]
##### 注意：使用自定义数据类型时一般情况下要加谓词或重载 == ，参数要加const
            