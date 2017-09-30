## 但行好事　莫问前程

## 数据库内容的迁移备份
* [1.同类型数据库间的导入导出](#1)
* [2.不同类型间数据库的导入导出](#2)

## <h2 id="1">同类型数据库间的导入导出</h2>
### 导出(以SqlServer为例)：
- ①借助第三方连接工具Navicat Premium
- ②连接登录SqlServer数据库：
连接数据库
![SqlServer数据库连接](Image/SqlServer数据库连接.png)

测试连接
![SqlServer连接测试](Image/SqlServer连接测试.png)
</br>
- ③导出数据库内容（导出为sql脚本的格式）
![01](Image/导出数据01.png)
![02](Image/导出数据02.png)
![03](Image/导出数据03.png)
![04](Image/导出数据完成04.png)

### 导入(以SqlServer为例)：
- ①建一个测试的数据库名(test)，没硬性要求，自己可根据情况建库
- ②导入(以sql脚本的格式导入)

## <h2 id="2">不同类型间数据库的导入导出</h2>
### 导出(SqlServer --> MySql)
- 步骤
![01](Image/导出到不同类型数据库01.png)
![02](Image/导出到不同类型数据库02.png)
![03](Image/导出到不同类型数据库03.png)
![04](Image/导出到不同类型数据库04.png)
![05](Image/导出到不同类型数据库05.png)
![06](Image/导出到不同类型数据库完成06.png)
![07](Image/导出到不同类型数据库完成.png)

### 导入(SqlServer --> MySql)
- ①建一个测试的数据库名(test)，没硬性要求，自己可根据情况建库
- ②导入(以mdb数据库文件的格式导入)
