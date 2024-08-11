# Morse-Code-Tools
摩尔斯代码工具箱
<br/>
https://github.com/lijiaxuan1811/Morse-Code-Tools
<br/>
如有任何问题，请在此提交Issue，非常感谢！
<br/>
最新版本：V1.1(x86/x64) 2024.08.11 UTC20:05
<br/>
作者：lijiaxuan1811
<br/>
网站：https://www.yuanshen.dev/
<br/>
邮箱：lijiaxuan1811@163.com
<br/>
版本历史：
<br/>
V1.1(x86/x64)-2024.08.11 UTC20:05
<br/>
-支持多线程异步执行，发声之时不再导致程序卡死
<br/>
v1.0(x86/x64)-2024.08.10 UTC23:00
<br/>
-首发版本，支持将以下字符转为摩尔斯电码：
<br/>
26个拉丁字母（大/小写），10个阿拉伯数字，19个特殊符号（. , ? ' ! / \ ( ) & : ; = + - _ " $ @）
<br/>
-支持更改电码速度（单位为词每分钟（WPM），默认值为20WPM）
<br/>
-支持更改电码音高（单位为赫兹（Hz），默认值为600Hz）
已知问题：
<br/>
由于直接调用Windows系统API，若CPU占用率较高时可能会导致发声断续