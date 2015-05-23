<<<<<<< HEAD
#Flasky
========
##参考书的描述
>This repository contains the source code examples for my O'Reilly book [Flask Web Development](http://www.flaskbook.com).

以上是原书信息的一些描述

跟着书本敲代码，存储到这里，敲完了再考虑什么时候写点作业好了

##关于manage.run()的运行参数引用
>运行hello.py，会显示一个用法消息：
```$python hello.py
usage: hello.py [-h] {shell,runserver}...```

>positional arguments:
>{shell, runserver}
>shell >在Flask应用上下文中运行Python shell
>runserver >运行Flask开发服务器：app.run()```

```optional arguments:
-h, --help >显示帮助信息并退出```

>shell命令用于在程序的上下文中启动Python shell会话。可以使用这个会话运行维护任务或测试、调试异常。

>runserver命令用来启动web服务器，运行 python pyfile.py runserver将以调试模式启动web服务器，以下还有其他选项可用：

```(venv) $ python pyfile.py runserver --help
usage: pyfile.py runserver [-h] [-t HOST] [-p PORT] [--threaded]
                             [--processes PROCESSES] [--passthrough-errors] [-d]
                             [-r]```

>examples
```python pyfile.py runserver --host 0.0.0.0 --port 9000
* Running on http://0.0.0.0:9000/
* Restarting with reload```

========

>>>>>>> cc1796ed8b7e2f74839b21d883acf8dc9c13e1f1
