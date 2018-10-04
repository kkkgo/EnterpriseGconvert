# 适用于Win10 1703+的Enterprise G转换处理/批量激活部署程序
https://03k.org/1803entg.html  
本程序通过导入证书来转换1703+的Windows 10系统为Enterprise G，并且转换也是可逆的，例如原来是企业版，想要用回去企业版可以直接导入企业版的key即可，企业G有两个好处，一个是就是400年的kms宽限期，还有就是无法升级版本，对于不想让Windows更新升级的同学来说也方便，并且也能随时转换回去。  

## [转换程序下载(右键另存为)](https://raw.githubusercontent.com/lixuy/EnterpriseGconvert/master/EnterpriseGconvert.cmd).
#### 注：本程序仅执行转换操作，请自行处理系统激活。
下载后右键管理员运行即可。

## [转换程序_一键自动激活版下载(右键另存为)](https://github.com/lixuy/EnterpriseGconvert/raw/master/EnterpriseGconvert_auto.cmd).
#### 注：本程序仅供部署参考，请把kmsserver参数修改成自己的服务器地址。

## 逆转换回去企业版示例：
>slmgr /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43  
其他版本参考 https://docs.microsoft.com/zh-cn/windows-server/get-started/kmsclientkeys  

## 已测试过的系统版本  
#### 以下是测试通过的版本
>Windows 10 Home/Profesionnal/Education/Enterprise 1703  
Windows 10 Home/Profesionnal/Education/Enterprise 1709  
Windows 10 Home/Profesionnal/Education/Enterprise 1803  
Windows 10 Home/Profesionnal/Education/Enterprise 1809  
Windows 10 LTSC 2019  
#### 以下是测试不通过的版本
>Windows 10 Home/Profesionnal/Education/Enterprise 1511  
Windows 10 Home/Profesionnal/Education/Enterprise 1607  
Windows 10 LTSB 2015  
Windows 10 LTSB 2016
