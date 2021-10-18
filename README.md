# W806_CoreMark
联盛德W806 MCU CoreMark 测试代码  
## How To USE  
在[开发板资料网站](https://h.hlktech.com/Mobile/download/fdetail/143.html)下载开发资料，然后解压`WM_SDK_W806.rar`。把解压后的app目录中的内容替换成这个git仓库中的内容。按照《W80X_MCU_快速入门_V0.1》，在CDK中建立项目，然后配置文件，把coremark文件夹、core_portme.h、core_poreme.c添加进项目，再把之前的main.c删除。编译，然后按照教程将fls文件下载到单片机中，执行并等待测试结果。  
## Test Result  
默认使用-O2优化选项，其余优化选项的结果可以自行测试。 
![测试结果](./coremark.PNG)