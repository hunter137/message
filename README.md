# messagepython初级综合应用—学生信息管理系统

变量 流程控制 函数 模块

项目需求：

实现对名片的增删改查及退出 通过选择不同的数字进行选择不同的功能，用户的姓名 电话 QQ 邮件 如果用户查询到指定名片则可进行修改 利用模块化来进行开发。

步骤：

1.框架搭建

2.新增名片

3.显示所有名片

4.查询名片

5.查询成功后修改删除名片

6.让python能够直接运行

1.框架搭建

准备文件 确定文件名 能够在需要的位置编写代码，编写主题循环，实现基本的用户输入和判断

新建card_main.py 保存主程序功能，程序的入口 card_tools.py 将名片新增，查询，修改，删除等功能封装在不同的函数中。

思路：在主程序中要设置循环功能，非主动退出则一直循环运行。无限循环
