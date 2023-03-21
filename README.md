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
