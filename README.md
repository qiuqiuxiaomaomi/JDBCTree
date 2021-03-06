# JDBCTree
JDBC驱动程序技术研究


![](https://i.imgur.com/fF1MCR0.png)

<pre>
          JDBC是一种用于执行SQL语句的Java API,可以为多种关系型数据库提供统一访问接口，
      它由一组用Java语言编写的类和接口组成。JDBC提供了一种基准，据此可以构建更高级的工具
      和接口，使数据库开发人员能够编写数据库应用程序，简言之，JDBC就是Java用于执行SQL语句
      实现数据库操作的API。

          数据库驱动程序就是提供用于操作数据库的一段代码。JDBC是一套协议，是Java开发人员
      个数据库厂商达成的协议，也就是由sun定义一组接口，由数据库厂商来实现，并规定开发人员
      访问数据库所使用的方法的调用规范。
</pre>

<pre>
实现JDBC操作的四个核心对象：
      1）DriverManager：驱动管理
      2）Connection：创建连接
      3）Statement：操作SQL语句，并返回相应结果的对象
      5）ResultSet:结果集处理
</pre>

![](https://i.imgur.com/FmiWtBV.png)

<pre>
JDBC工作整体流程

      1）加载驱动
      2）建立连接
      3）创建语句对象
      5）创建SQL语句
      6）执行SQL语句
      7）处理结果集
      8）关闭连接
</pre>

JDBC实际调用过程

![](https://i.imgur.com/5nXh9qo.png)
