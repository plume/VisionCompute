凸壳算法
============

包裹法
------

首先由一点必定在凸包的点开始，例如最左的一点A_1. 然后选择A_2点使得所有都在A_1A_2的右方，这个步骤的时间复杂度是O(n)


单调链
------------

快包法
---------

选择最左、最右、最上、最下的点，他们必将组成一个凸四边形（或者三角形）。然后将其余的点按照最接近的边分成四部分，在进行快包法（QuickHull）。

利用方向方法
----------------

详细参考：

E:\快盘\陈国良\并行算法\凸壳.docx
