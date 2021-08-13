# hoshinobot-birthday
hoshinobot插件：角色生日提醒，以及通过生日查询角色。

添加方法（二选一）：
  1.将birthday文件夹放到HoshinoBot\hoshino\modules目录下，在__bot__.py内添加插件。
  
  2.将birthday.py放到HoshinoBot\hoshino\modules\priconne\games目录下，无需修改__bot__.py。

* 2021/08/13：将角色生日数据获取来源修改为priconne\\_pcr_data.py。
* 别问为什么一开始不这么写，一开始这里根本没有角色生日信息！
* 别问为什么现在才想起来改，摸了！

功能：

  生日查询指令（需要开启birthday_search服务）：
  
    谁的生日是+生日 这天哪位'老婆'过生日呢
    
    谁的生日是今天 看看今天哪位'老婆'过生日呢
    
    角色+的生日是那天 看看'老婆'的生日是那天
    
  生日提醒（需要开启birthday_reminder服务）：
  
    每天00：01提醒今天过生日的角色
