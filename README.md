# pscaner

pscaner introduction：

1、This tool using python socket to check ports opened or not.

2、The fast mode used python's multithreading which will create a thread for every port, it means scanning speed is extreamly fast, but it also will use a lot of CPU resources. 

3、U can export result as a file

using：

1、(*)Input a ip address（it only accept 1 correct ip adderss. e.g xxx.xxx.xxx.xxx）

2、(optional,default using "Common" mode)Choosing scanning mode（Fast or Slow） and scaned ports(Common or All), "Common" includes 67 common ports, and "All" includes all 65535 ports.

3、Click "start" button or press "Return" on keyboard to start scannig.

4、（optional）, U can export result as file or just check result in UI.

法律免责声明

未经事先双方同意，使用pscan扫描目标是非法的。 pscan仅用于安全测试目的.
【免责声明】本仓库所涉及的技术、思路和工具仅供安全技术研究，任何人不得将其用于非授权扫描测试，不得将其用于非法用途和盈利，否则后果自行承担。

Usage pscan for attacking targets without prior mutual consent is illegal. pscan is for security testing purposes only.
