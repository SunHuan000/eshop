# eshop
一、安装环境：
windows
python
django
django-oscar
sqlite

二、安装：
先安装anaconda3
pip install django
pip install django-oscar
sqlite安装：在http://www.sqlite.org/download.html下载 
            sqlite-tools-win32-*.zip和sqlite-dll-win32-*.zip 压缩文件
            创建文件夹 C:\sqlite，并在此文件夹下解压上面两个压缩文件，
            将得到 sqlite3.def、sqlite3.dll 和 sqlite3.exe 文件。
            添加 C:\sqlite 到 PATH 环境变量，在cmd输入sqlite3。
            
三、创建项目：
1：在工程放置的目录下，打开命令行，创建工程 
cd eshop
C:\eshop>django-admin startproject website 
2：进入工程目录 
cd .\website\ 
3：启动服务 
python .\manage.py runserver 
4：在浏览器打开localhost:8000
