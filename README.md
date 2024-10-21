# 项目说明

在minimap_replay的基础上添加服务器部署的能力。

# 使用说明

1. 配置一套能够顺利运行minimap_replay项目的python环境（比如需要原项目都没提到的langdetect、hanzidentifier库）
2. 在以上配置好的环境中，安装flask
3. 使用`sqlite3 file_mapping.db`命令创建数据库文件
4. 使用`python app.py`命令运行项目

注：可以使用`nohup python app.py > server.log 2>&1 &`命令让该服务在后台运行。

# 致谢

1. 感谢WOWs-Builder-Team提供的replay文件转换工具项目：[minimap_renderer](https://github.com/WoWs-Builder-Team/minimap_renderer)
2. 感谢fantasy提供的flask文件上传下载项目：[文件上传](https://gitee.com/fantasy_5/file-upload)
