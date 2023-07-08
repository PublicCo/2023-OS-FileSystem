# 使用说明

相关的报告在report文件夹

## 运行要求

*编译器版本：*python3.10

*开发环境：*pycharm2022.3

*模块要求:*

```python
pyqt5 #前端UI
datetime #和文件时间有关
qdarkstyle #QSS主题
pickle #存档读写
bitarry #位图
```

*文件结构要求:*

>./
>│  FileManagement.ui
>│  file_system_components.py
>│  file_system_save.save
>│  main.py
>│  report.md
>│  ui_FileManagement.py
>│
>├─icon
>│      beforedir.png
>│      File.png
>│      HasContentDir.png
>│      NoContentFileDir.png
>│
>└─__pycache__
>        file_system_components.cpython-310.pyc
>        ui_FileManagement.cpython-310.pyc

*运行：*

确保当前文件夹下路径正确并安装指定模块后，在cmd中输入

>python main.py

或者在pycharm中打开该文件夹并运行main.py