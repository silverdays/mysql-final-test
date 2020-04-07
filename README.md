# mysql-final-test
2019-2020 mysql final test

姓名：

学号：

说明：考试为开卷，可以上网；

1. 打印当前时间（例如 2020-04-07 13:41:42），写出SQL语句和结果

2. 打印自己的姓名和学号( 例如 张三+123456 或者 zhangsan+123456 显示包含加号)，写出SQL语句和结果

3 建立如下表1和表2，写出建表语句和插入语句。

表1：其中deptno为主键
```
deptno,deptno,loc
(10, "ACCOUNTING", "NEW YORK"),
(20, "RESEARCH", "DALLAS"),
(30, "SALES", "CHICAGO"),
(40, "OPERATIONS", "BOSTON")
```

表2：其中empno字段为主键，deptno字段需要在表1中存在
```
  empno, ename, job, MGR, Hiredate, sal, comm, deptno
  (7369, "SMITH", "CLERK", 7902, "1981-03-12", 800.00, NULL, 20),
	(7499, "ALLEN", "SALESMAN", 7698, "1982-03-12", 1600, 300, 30),
	(7521, "WARD", "SALESMAN", 7698, "1838-03-12", 1250, 500, 30),
	(7566, "JONES", "MANAGER", 7839, "1981-03-12", 2975, NULL, 20),
	(7654, "MARTIN", "SALESMAN", 7698, "1981-01-12", 1250, 1400, 30),
	(7698, "BLAKE", "MANAGER", 7839, "1985-03-12", 2450, NULL, 10),
	(7788, "SCOTT", "ANALYST", 7566, "1981-03-12", 3000, NULL, 20),
	(7839, "KING", "PRESIDENT", NULL, "1981-03-12", 5000, NULL, 10),
	(7844, "TURNER", "SALESMAN", 7689, "1981-03-12", 1500, 0, 30),
	(7878, "ADAMS", "CLERK", 7788, "1981-03-12", 1100, NULL,20),
	(7900, "JAMES", "CLERK", 7698,"1981-03-12",  950, NULL, 30),
	(7902, "FORD", "ANALYST", 7566, "1981-03-12", 3000, NULL, 20),
	(7934, "MILLER", "CLERK", 7782, "1981-03-12", 1300, NULL, 10)
```

3.1 表2 中再插入一条记录：`(你的学号，你的姓名或者拼音， “CLERK”, 7782, 你的生日,  NULL, NULL, 10)`
  例如：`	(12345,  "Zhangsan", "CLERK", 7782, "2000-03-12", NULL, NULL, 10)`

3.2 表中姓名（ename字段）最长的人

3.3 有几种职位（job字段）？分别是什么？

3.4 将MILLER的 comm 改为300；

3.5 计算每个人的收入(ename, sal + comm)，并按收入降序排序。 提示计算时 NULL 要当做 0 处理； 

3.6 显示每个人的下属,没有下属的显示 NULL

3.7 显示每个人所在的城市(loc)


