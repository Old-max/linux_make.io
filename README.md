# linux_make.io
sln2mak to make file

2021/7/13
  sln2mak 生成的makefile，在u网运行，对于-I的option，如果有多条记录，在windows是通过；分隔的，linux需要每条路径都配置-I选项
  自己生成的lib文件（*.a),在libs+=的配置后面不能增加-l，直接写库的名字，并且用相对路径
  
