# AcidIsland-server-config
这是海岛服务器的服务器配置文件合集，服务端建设已完成

**有建议？请提issue告诉我！**

这些配置文件可以让你搭建起一个基本的海岛服务器，插件少对配置要求低，保留了纯粹的海岛体验
没有加什么限制


插件列表：

![image](https://user-images.githubusercontent.com/25699126/116084468-6aca8e00-a6d0-11eb-812b-e88f2aef9b47.png)


请下载Release中的整合端


**在正式开服前先完成下面的几个步骤**

1.更新paper核心

2.tablist配置中的website和qq群改成你的，修改Tablist的显示效果成你想要的

3.server.properties按需修改

4.**你需要设置op来启用server.properties中设置的spawn-protection出生点保护（不设置op 服务器将会忽略这一项，主城就不会被保护）**

5.**在控制台中输入gamerule keepInventory true来开启死亡不掉落（默认是没有开的）**

6.在一个岛上搭好商店（用半砖商店slabbo插件）并设置warp，在主城建好公告墙

7.检查luckperms的权限设置，看情况修改，也可以直接用（默认的设置能正常游玩并且玩家不会滥用权限）

8.使用lp user <name> parent add op将op的名字添加到op权限组来获得完全的权限。


游玩提示

1./ai创建/传送海岛

2./menu打开海岛菜单（command.yml中为ai controlpanel设置的别名）

3.半砖商店用法，用木棍右键半砖打开gui菜单

4.有铁块电梯


默认的一些设置：

1.玩家能创建的半砖商店数量不限（权限slabbo.limit.*   将星号改为数字可限制数量）

2.酸水的伤害改小了一点，时间缩短，水中停留1s后生效，酸水不摧毁物品

3.ess设置允许放岩浆桶tnt（主城有保护）

4.各种插件的配置都修改了一点，bukkit.yml spigot.yml paper.yml优化了一下（只改了几个地方）

5.海岛成就有汉化

6.玩家可以创建ess的warp，也可以用海岛的木牌warp（需要岛屿达到10级）

7.正版验证关闭

8.最低钱数为-10，最小支付金额为0.01

9.铁块电梯最大传送距离14格（插件的默认设置）

10.一个ip最多注册3个用户

总之就是看情况改一下插件的配置，也可以直接用。这些配置是测试过的，能正常游玩




已知bug：

1.创建海岛时的提示文字开头有几个乱码的中文（不影响玩）


2021-04-26更新

完成

2021-04-25更新

完成了TabList插件的配置

2021-04-24更新

完成EssX和luckperms的配置，添加了基本权限

