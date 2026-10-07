# H-P-01解题思路
1. 基类Shape，包含area()虚函数。
2. 子类Circle继承Shape，包含构造函数(传入半径r）和重写后的area计算面积。
3. 子类Square继承Shape，包含构造函数（传入边长side）和重写后的area计算面积。
4. 主程序初始化Cir和Squ，创建包含Cir、Squ的列表Shapelist，循环遍历列表，进行计算。