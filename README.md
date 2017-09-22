# mybatis-generator
mybatis代码自动生成

1.通过编译工具自动生成<br/>
下载项目并导入到工具(idea或eclipse)中，修改src/main/resources文件夹中generatorConfig.xml文件的相关配置.<br/>
maven的command line中配置"mybatis-generator:generate -e"，运行。

2.命令行方式自动生成<br/>
进入到lib文件夹下，修改generatorConfig.xml文件的相关配置<br/>
通过终端进入lib文件夹下<br/>
输入:java -jar mybatis-generator-core-1.3.5.jar -configfile generatorConfig.xml -overwrite 命令。

