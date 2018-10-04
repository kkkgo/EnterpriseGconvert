# 适用于1803+的Windows 10 Enterprise G转换处理程序
Windows10自1803之后是无法通过dism转换的，但可以通过导入证书来转换，并且转换也是可逆的，想要用回去企业版可以直接导入企业版的key就变回去企业版了，企业G有两个好处，一个是就是400年的kms宽限期，还有就是无法升级版本，对于不想让Windows更新升级的同学来说也方便，并且也能随时转换回去。
如果你的系统低于1803，请使用dism /online进行转换，参考（https://03k.org/make10entg.html）
### 注：本程序仅执行转换操作，请自行处理系统激活。
## [转换程序下载](https://raw.githubusercontent.com/lixuy/EnterpriseGconvert/master/EnterpriseGconvert.cmd).

下载后右键管理员运行即可。

##逆转换回去企业版示例：
>slmgr /ipk NPPR9-FWDCX-D2C8J-H872K-2YT43
