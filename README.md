﻿trade-impexp
=============================================

进出口数据的导入导出查询数据...


0	col001  	数字	月份
1	col002		文本	产品代码
2	PName		备注	产品名称
3	E2		备注	企业性质
4	TradeName	备注	贸易方式
5	cityName	备注	城市
6	CountryName	备注	国家
7	PGCountryName	备注	国家
8	CustomsName	备注	出口海关
9	TransName	备注	运输方式
10	UnitName	备注	单位
11	Col012		数字	数量
12	Col013		数字	金额

==============================================

1.注意:下次做项目要从顶层开始，先写view层，保证项目能跑通，再补齐service层,最后实现底层。

问题:
1.jpa配置问题，致项目起不来;
2.解压日志记录，导入日志记录
3.导入数据，更新年月
4.detail,sum表的list条件(criteria)查询

5.添加权限验证