### 适合会编程的人用的真正“参数化”建模的设计软件OpenSCAD的开发文档

### 一、形状
#### 方块：cube([x, y, z]) 或者 cube(n)
* 说明：该方法用来创建一个立方体。
* 参数：数组或者数字。x值为x轴的长度，y值为y轴的长度，z值为z轴的长度。如果只指定n值，则默认x、y、z都为n。

#### 圆形：sphere(n)
* 说明：该方法用来创建一个球体。
* 参数：数字。n值为该球体的半径。

#### 圆柱体：cylinder(h = 4, r = 2)
* 说明：该方法用来创建一个圆柱体。
* 参数：h和r，都是数字。h为高度，r为底面半径。

### 二、拼接
#### difference() {}
* 说明：取多个物体不交集的部分。
* 方法体：多个形状方法。

#### union() {}
* 说明：取多个物体交集的部分。
* 方法体：多个形状方法。

#### translate([x, y, z]) {}
* 说明：平移物体。
* 参数：数组。x值为x轴平移的距离，y值为y轴平移的距离，z值为z轴平移的距离。
* 方法体：多个形状方法。

### 三、渲染
#### color([r, g, b])
* 说明：物体颜色渲染。
* 参数：0 ~ 255

### 四、代码注释方法
#### 单行注释// 和 多行注释/**/



