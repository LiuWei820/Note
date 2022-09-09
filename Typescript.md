## 1.Typescript介绍

![1651976764892](Typescript.assets/1651976764892.png) 

![1651977031346](Typescript.assets/1651977031346.png) 

## 2.Typescript初体验

![1651977229004](Typescript.assets/1651977229004.png) 

![1651977626582](Typescript.assets/1651977626582.png) 

![1651978133226](Typescript.assets/1651978133226.png) 

## 3.Typescript常用类型

![1651978908630](Typescript.assets/1651978908630.png) 

![1651979981148](Typescript.assets/1651979981148.png) 

![1651980055293](Typescript.assets/1651980055293.png) 

### 1.原始类型

![1651980427160](Typescript.assets/1651980427160.png) 

### 2.数组类型和联合类型

![1651980390903](Typescript.assets/1651980390903.png) 

![1651980673767](Typescript.assets/1651980673767.png) 

### 3.类型别名（type）

![1651980866080](Typescript.assets/1651980866080.png) 

### 4.函数类型

#### 设定函数参数和返回值的类型

![1651981136452](Typescript.assets/1651981136452.png) 

![1651981413065](Typescript.assets/1651981413065.png) 

#### 是否有返回值

**如果函数没有返回值，那么，函数返回值类型为：void**

![1651981523975](Typescript.assets/1651981523975.png) 

#### 是否传参

![1651996916753](Typescript.assets/1651996916753.png) 

![1651997052837](Typescript.assets/1651997052837.png) 

### 5.对象类型

![1651998386612](Typescript.assets/1651998386612.png) 

**写法一**

![1651998562811](Typescript.assets/1651998562811.png) 

**写法二**

![1651998772961](Typescript.assets/1651998772961.png) 

#### 可选属性

![1652008973599](Typescript.assets/1652008973599.png) 

### 6.接口

#### 初识

![1652009213026](Typescript.assets/1652009213026.png) 

#### 接口（interface）与type之间的对比

![1652009452991](Typescript.assets/1652009452991.png) 

#### 接口之间的继承

![1652009546386](Typescript.assets/1652009546386.png) 

![1652009678829](Typescript.assets/1652009678829.png) 

### 7.元祖

![1652009913119](Typescript.assets/1652009913119.png) 

### 8.类型推论

![1652010316921](Typescript.assets/1652010316921.png) 

### 9.类型断言

![1652010853906](Typescript.assets/1652010853906.png) 

### 10.字面量类型

![1652016752162](Typescript.assets/1652016752162.png) 

![1652011226280](Typescript.assets/1652011226280.png) 

### 11.枚举

![1652015657448](Typescript.assets/1652015657448.png) 

#### 数字枚举

![1652015941978](Typescript.assets/1652015941978.png) 

#### 字符串枚举

![1652016204695](Typescript.assets/1652016204695.png) 

#### 枚举的特性

![1652016666825](Typescript.assets/1652016666825.png) 

### 12.any类型

![1652017364192](Typescript.assets/1652017364192.png) 

**（1）声明变量不提供类型也不提供默认值（可以传入任意的值，代码不会有任何的错误）**

![1652017165973](Typescript.assets/1652017165973.png) 

![1652017209300](Typescript.assets/1652017209300.png) 

**（2）函数参数不加类型（可以传入任意的值，代码不会有任何的错误）**

![1652017261014](Typescript.assets/1652017261014.png) 

![1652017287844](Typescript.assets/1652017287844.png) 

### 13.typeof运算符

![1652058289521](Typescript.assets/1652058289521.png) 

![1652058427744](Typescript.assets/1652058427744.png) 

## 4.Typescript高级类型

### 1.class类

#### 1.class类的基本使用

![1652058824057](Typescript.assets/1652058824057.png) 

![1652058791604](Typescript.assets/1652058791604.png) 

#### 2.class类的构造函数

![1652059136271](Typescript.assets/1652059136271.png) 

![1652059111352](Typescript.assets/1652059111352.png) 

#### 3.class类的实例方法

**方法的类型注解（参数和返回值）与函数用法相同**

![1652059630437](Typescript.assets/1652059630437.png) 

#### 4.class类的继承

##### 1.extends继承

**类继承的两种方式：1.extends（继承父类）2.implements（实现接口）**

**说明：JS中只有extends，而implements是TS提供的**

![1652060027778](Typescript.assets/1652060027778.png) 

**解释：**

**（1）通过extends关键字实现继承**   

**（2）子类Dog继承父类Animal，则Dog的实例对象dog就同时具有了父类Animal和子类Dog的所有属性和方法**

##### 2.implements继承

![1652061155741](Typescript.assets/1652061155741.png) 

**解释：**

**（1）通过implements关键字让class实现接口**   

**（2）Person类实现接口Singable意味着，Person类中必须提供Singable接口中指定的所有方法和属性**

### 2.类成员可见性

#### 1.public（公有成员）

![1652061585149](Typescript.assets/1652061585149.png) 

#### 2.protected（受保护成员）

**protected：表示受保护的，仅对其声明所在类和子类中（非实例对象）可见**

![1652062337940](Typescript.assets/1652062337940.png) 

**解释：**

**（1）在类属性或方法前面添加protected关键字，来修饰该属性或方法是受保护的**

**（2）在子类的方法内部可以通过this来访问父类中受保护成员，但是，对实例不可见！**

#### 3.private（私有成员）

![1652081368654](Typescript.assets/1652081368654.png) 

#### 4.readly（只读修饰符）

![1652081907835](Typescript.assets/1652081907835.png) 

![1652082044683](Typescript.assets/1652082044683.png) 

![1652082088566](Typescript.assets/1652082088566.png) 

![1652081994279](Typescript.assets/1652081994279.png) 

### 3.类型兼容性

#### 1.类与类之间的兼容性

![1652082692494](Typescript.assets/1652082692494.png) 

![1652083015777](Typescript.assets/1652083015777.png) 

![1652083000511](Typescript.assets/1652083000511.png) 

#### 2.接口之间的兼容性

**接口之间的兼容性，类似于class，并且，class和interface之间也可以兼容**

**（成员多的可以赋值给成员少的）**

![1652084629030](Typescript.assets/1652084629030.png) 

![1652084808466](Typescript.assets/1652084808466.png) 

#### 3.函数之间的兼容性

##### 1.根据参数个数判断

![1652084889643](Typescript.assets/1652084889643.png) 

##### 2.根据参数类型判断	 

![1652086900842](Typescript.assets/1652086900842.png) 

![1652086891633](Typescript.assets/1652086891633.png) 

##### 3.根据返回值类型判断

![1652091495085](Typescript.assets/1652091495085.png) 

![1652091639075](Typescript.assets/1652091639075.png) 	

### 4.交叉类型

![1652091857221](Typescript.assets/1652091857221.png) 

![1652092104661](Typescript.assets/1652092104661.png) 

**交叉类型（&）和接口继承（extends）的对比**

![1652100037709](Typescript.assets/1652100037709.png) 

### 5.泛型

#### 1.调用泛型函数

![1652103507439](Typescript.assets/1652103507439.png) 

![1652103533056](Typescript.assets/1652103533056.png) 

#### 2.简化调用泛型函数

![1652173256190](Typescript.assets/1652173256190.png) 

#### 3.泛型约束

##### **1.指定更加具体的类型**

![1652173539761](Typescript.assets/1652173539761.png) 

##### **2.添加约束**

![1652173831023](Typescript.assets/1652173831023.png) 

![1652173964119](Typescript.assets/1652173964119.png) 

#### 4.类型变量之间的约束

![1652174807131](Typescript.assets/1652174807131.png)  

![1652174900611](Typescript.assets/1652174900611.png) 

#### 5.泛型接口

![1652434251959](Typescript.assets/1652434251959.png) 

![1652434368089](Typescript.assets/1652434368089.png) 

![1652435145420](Typescript.assets/1652435145420.png) 

#### 	6.泛型类

![1652443419256](Typescript.assets/1652443419256.png) 

![1652443226343](Typescript.assets/1652443226343.png) 

#### 7.泛型工具类

![1652443749371](Typescript.assets/1652443749371.png) 

##### 1.Partial（将所有属性变为可选)

![1652443877896](Typescript.assets/1652443877896.png) 

![1652444024719](Typescript.assets/1652444024719.png) 

##### 2.Readonly（只读）

![1652444236268](Typescript.assets/1652444236268.png) 

![1652444223214](Typescript.assets/1652444223214.png) 

##### 3.Pick（构造新类型）

![1652444407539](Typescript.assets/1652444407539.png) 

##### 4.Record构造一个对象类型

![1652444607061](Typescript.assets/1652444607061.png) 

![1652444744877](Typescript.assets/1652444744877.png) 

### 6.索引签名类型

![1652445152854](Typescript.assets/1652445152854.png) 

![1652445176233](Typescript.assets/1652445176233.png) 

**数组中使用索引签名类型**

![1652445883518](Typescript.assets/1652445883518.png) 

![1652446070977](Typescript.assets/1652446070977.png) 

### 7.映射类型

#### 1.基本书写规则

![1652446864521](Typescript.assets/1652446864521.png) 

![1652446926284](Typescript.assets/1652446926284.png) 

#### 2.根据对象类型来创建

![1652495838778](Typescript.assets/1652495838778.png) 

![1652495783797](Typescript.assets/1652495783797.png) 

#### 3.Partial 的实现

![1652496263352](Typescript.assets/1652496263352.png) 

#### 4.索引查询类型

![1652496776312](Typescript.assets/1652496776312.png) 

![1652496764954](Typescript.assets/1652496764954.png) 

#### 5.同时查询多个索引的类型

![1652496951020](Typescript.assets/1652496951020.png) 

## 5.Typescript类型声明文件

### 1.概述

![1652497503664](Typescript.assets/1652497503664.png) 

### 2.TS中的两种文件类型（.ts文件 和 .d.ts文件）

![1652499098733](Typescript.assets/1652499098733.png) 

**index.ts文件**

![1652499166616](Typescript.assets/1652499166616.png) 

**index.d.ts文件**

![1652499132796](Typescript.assets/1652499132796.png) 

### 3.类型声明文件的的使用声明






