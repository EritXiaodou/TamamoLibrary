# TamamoLibrary
一个MC基岩版的Molang检测项与指令交互标签库

当前可用MolangTag标签 :
is_afking -挂机中
is_alive -存活中
is_burning -燃烧中(着火状态)
is_dead -死亡状态中
is_falling -处于空中
is_full -高血量状态(20滴血)
is_full_max -超额血量状态(24滴血)
is_in_air -暴露空气中
is_in_water -暴露在水中
is_jumping -跳跃状态中
is_low -低血量状态(1-8滴血)
is_moving -移动中
is_on_ground -在地面上
is_shifting -潜行中
is_sprinting -冲刺中(疾跑状态)
is_sleeping -睡觉中
is_swimming -游泳中
is_using_item -使用物品中
is_walking -行走中
has_health -拥有生命值

如何使用标签功能？
指令交互
假如想对移动中的玩家施加缓慢效果？
effect @a[tag=is_moving] slowness 15 1 true
假如想对意外失足的玩家施加缓慢效果？
effect @a[tag=falling] slow_falling 15 1 true
假如想让潜行状态下的玩家拾取周围的掉落物？
tp @e[type=item] @p[r=5,tag=shifting]
或者
tp @e[type=item] @p[r=5,tag=sneaking]

下载：
https://github.com/EritXiaodou/TmamaoLibrary/releases
第三方：
https://klpbbs.com/thread-80047-1-1.html
