# FuckJLC

将其他EDA软件的gerber转换为傻逼立创EDA格式的脚本

立创EDA狗都不用

# Usage

``` python
python modify.py
```

请手动替换脚本中header和工作目录为你自己的

header获取方法：立创EDA导出gerber→随意打开一个gerber文件

## Noitce

目前仅对Kicad所导出的gerber做适配，其他软件请发Issue并附带目录结构或者自力更生PR

导出gerber时注意一些细节
* 使用`Protel格式文件扩展名`导出，此格式与LCEDA相同
* 钻孔文件也为gerber格式
* 不要使用扩展的X2格式（此项影响存疑）