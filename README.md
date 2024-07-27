# JLU-Website-Navigation
因吉林大学相关网站众多，为方便使用吉林大学网络服务，故以 2021 级本科生视角撰写此文。  
研究生相关网址有待完善，部分网站具有校区局限性，例：大学物理实验选课网站（南岭）。  
部分网站仅限校内访问或需使用WEBVPN系统。 
  
本文档至今为完全公益性质，完全免费且不涉及任何潜在的收费行为。本文档鼓励任何使用者将其传播到需要的人手中。  

如果你是第一次使用Github，在*Code*中可以找到PDF文件，或者可以在*Releases*中下载 :smile:   
如果仍找不到在哪里下载，使用这个链接：https://github.com/k0mp1exSTAR/JLU-Website-Navigation/releases  选择最新版本的PDF文件（Std版本）下载即可（zip和tar.gz文件不用管）
  
## 文档发布页面：

https://github.com/k0mp1exSTAR/JLU-Website-Navigation    
https://gitee.com/k0mp1exSTAR/JLU-Website-Navigation      
  
## 关于MD5/SHA256：
	MD5（Message Digest Algorithm 5）和SHA256（Secure Hash Algorithm 256-bit）是密码学中的哈希函数。
在本文档中用于数据完整性验证：通过计算数据的哈希值，可以对数据进行完整性验证。如果数据在传输或存储过程中被篡改，其哈希值将不匹配，从而发现数据的篡改。
注：若仅文件名变动，MD5和SHA256（SHA-2）输出值不受影响。

### 如何校验MD5/SHA256: 
如果你使用Windows10/11系统，这里提供一个较快捷的方法。  
同时按下Windows+R键，在弹出窗口中输入Powershell并确认，将会打开Powershell，在弹出的窗口中输入：  
Get-FileHash 文件路径 -Algorithm 算法名  
然后按下Enter键回车。  
“文件路径”为文档所在位置，例如你的文档放在D盘的“新建文件夹中”，则在这里输入“D:\新建文件夹\吉林大学网站导航v1.1.pdf”  
“算法名”填 “MD5”或“SHA256”  
以下是一个完整示例：  
`Get-FileHash D:\新建文件夹\吉林大学网站导航v1.1.pdf -Algorithm MD5`  
按下Enter键回车回车后得到如下输出：  
```
Algorithm     Hash                                     Path
---------     ----                                     ----
MD5           577B26FB775B2A83E112E4D8625F4D38         D:\吉林大学网站导航V1.1.pdf
```
这意味着此时D盘“新建文件夹”中的“吉林大学网站导航v1.1.pdf”MD5值为577B26FB775B2A83E112E4D8625F4D38，与GitHub页面所声明一致，则可认为此时你所持有的文件与Github页面所发布的原文件一致。  
如果你只是想确保拿到第一方版本，到文档发布页面去下载最新PDF文件最为快捷可靠。  
  
## 校验信息：
### v1.3.0 
MD5 327bd54398df1e7a5982d5cfae43208f  
SHA256 234b04293cfc00ae0f80f829d1e2fa2eea0909a637b120efce5419e58a52d8c5

### v1.2.1Std  
MD5 6B73563F51B0D1DEFB46491CE9A53A45  
SHA256 4BBB493A139BB28E6D755FF31FFDF10F392370C7798636FD9E2AD30A5AF6C7B7  
  
### v1.2.1Beta  
MD5 9199354FC3FE9EC812AD8551F2DA4E4F  
SHA256 4BBB493A139BB28E6D755FF31FFDF10F392370C7798636FD9E2AD30A5AF6C7B7  
