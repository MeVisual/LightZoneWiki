# LNU | LightZone通用指令一览
*默认使用`T`键或`/`键打开聊天框。此页介绍大部分情况下都可用的指令，某些特殊情况独占的指令不会在此提及，请查看相关子服节点的游戏内说明。该页面可能不会及时更新。绝大部分命令都可使用`Tab`键智能补全。*

## Server | 服务器基础相关
`/hub 服务器标识符`  **(\*仅MUA网络下可用)** 前往其他MUA成员的服务器  
`/server Oriland` 进入Oriland子服  
`/server Pixeltale` 进入Pixeltale子服  
`/server Forecus` 进入Forecus子服    
`/spawn` 返回当前子服的主城  
`/back` 返回上一位置(同一节点内由于死亡、传送等引起的位置变化)   
`/msg 玩家名 消息内容` 向指定玩家发送私聊(可跨子服)  
`/tpa 玩家名称` 向指定玩家发送传送请求  
`/tpaccept` 当有传送请求时,接受其他玩家发送过来的tpa请求  
`/tpdeny` 当有传送请求时,拒绝其他玩家发送过来的tpa请求  
`/sethome 自定义名称` 将当前脚下的位置设置为家  
`/home 自定义名称` 传送至家  
`/delhome 自定义名称` 删除设定的家  
`/co i` 切换CoreProtect检查器开/关  *在CoreProtect检查器状态下点击方块可查询其修改历史*  

## Gsit | 玩家动作

*空手右键楼梯也可触发坐下动作,所有动作用潜行键取消。*  
`/sit` 坐在一个方块上  
`/lay` 躺在一个方块上  
`/bellyflop` 趴在一个方块上  
`/spin`  在一个方块上旋转 <sup>~~转转转转转转转~~</sup>  
`/crawl` 在地上爬行  


## Skulls | 头颅装饰相关
`/skulls` 打开一个装饰品菜单  
`/ph spawn` 生成一个可放置的自己的头颅  

## VeinMiner | 连锁采集相关 <sup>仅Oriland节点可用</sup>
*完整VeinMiner文档见[VeinMiner | SpigotMC](https://www.spigotmc.org/resources/veinminer.12038/)*  
`/veinminer toggle` 开启/关闭连锁采集  
`/veinminer mode 模式名` 切换连锁采集触发模式  
*连锁采集模式名解释如下:*
- `always` 总是触发
- `sneak` 仅在潜行时触发
- `stand` 仅在站立时触发
- `none` 禁用连锁采集
- `client` 仅在按下对应键时触发，需要客户端安装[VeinMiner Companion](https://www.curseforge.com/minecraft/mc-mods/veinminer-companion)才能使用。
