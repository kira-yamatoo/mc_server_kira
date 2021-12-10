客户端:https://github.com/kira-yamatoo/mc_client_kira
---

- 0x00、若无法运行.bat/.sh脚本，请检查脚本中的.jar文件名称与根目录下.jar名称是否一致
```
java -jar CatServer-50610c7-universal.jar
```

- 1、打开enla.txt将eula设置为true，即同意用户协议。
```
eula=true
```

- 非正版玩家，请在首次运行后打开server.properties修改配置：启用正版验证修改为false
```
online-mode=false
```

- 2、以文本形式打开start.bat将-Xms -Xmx设置为合适的内存大小(至少2G，推荐4G或8G以上)
```
-Xms4G -Xmx4G
```

- 3、自行添加模组，请将mod放置于/mods目录下
```
！！！请注意，若在服务器端添加了mod则客户端也必须一样的mod！！！
```
- 4、运行start.bat即可开服

- 5、使用搜索引擎获取自身的公网ip，加上端口号25565
```
如49.0.0.1:25565即为客户端添加服务器时的地址
- 注意：
若使用的是ISP而不是云服务器则每次重启计算机后ip都有可能会发生改变
若无法连接至服务器时，请检查ip地址是否有变化
```