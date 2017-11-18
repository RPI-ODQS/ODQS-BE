#运行开发环境（ubuntu+pycharm）


1. 下载源码 https或者ssh方式
2. git checkout 到相应的分支
3. 建立虚拟环境 virtualenv venv
4. 激活虚拟环境 source venv/bin/activate
5. 下载相应的工具包 pip install -r requirements.txt
6. 设置全局变量 export FLASK_APP=flasky.py
7. 初始化数据库 flask db upgrade; flask db migrate
8. 运行程序 flask run


