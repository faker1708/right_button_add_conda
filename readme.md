


正文

https://blog.csdn.net/qq_24852439/article/details/88597644

计算机\HKEY_CLASSES_ROOT\Directory\Background\shell\conda_here\command


比如已经有了这个环境 python39

原本是这样进入环境
conda activate python39

原理就是把conda 换成前面这段代码

cmd.exe /s /k "C:\Users\dva\miniconda3\Scripts\activate.bat" activate python39

