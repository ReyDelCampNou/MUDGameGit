# MUDGameGit
## 人物类character

#### 属性：
&nbsp;
Id  
&nbsp;
名字name  
&nbsp;
等级level  
&nbsp;
体力值health_point  
&nbsp;
魔力值 mana_point  
&nbsp;
防御力physical_defence  
&nbsp;
法术抗性 magic_defence  
&nbsp;
攻击力	attack_point  
&nbsp;
暴击值 critic  
&nbsp;
暴击伤害 critical_damage  
&nbsp;
命中值 hit_value  
&nbsp;
闪避值 dodge_value  
&nbsp;
速度 speed  
&nbsp;
暴击抗性 critical_defence  
&nbsp;
效果抗性 cc_defence  

#### 行为：
&nbsp;
攻击 attack  
&nbsp;
技能 skill  
&nbsp;
逃跑 escape  
&nbsp;
交谈 communicate  
&nbsp;
死亡 die

### 主角类 hero
#### 属性：
&nbsp;
物品 item  
&nbsp;
装备栏 equipment_slot  

#### 行为：
&nbsp;
使用道具 use_item  
&nbsp;
休息 rest  
&nbsp;
拾取 pick  
&nbsp;
移动 move  

### npc类（人物类）npc
#### 属性：
&nbsp;
刷新条件 recur_condition  
&nbsp;
掉落物 drop_item  
&nbsp;
仇恨值 hostility  
&nbsp;

#### 行为：
&nbsp;
掉落物品 dropout  

## 物品类 item
#### 属性：
&nbsp;
价值 value  
&nbsp;
Id  
&nbsp;
数量 number  
&nbsp;


#### 行为：
&nbsp;
使用 be_used


### 装备类（物品）equipment
#### 属性：
&nbsp;
防御力补正additional_physical_defence  
&nbsp;
法术抗性补正 additional_magic_defence  
&nbsp;
攻击力补正	additional_attack_point  
&nbsp;
暴击值补正 additional_critic  
&nbsp;
暴击伤害补正 additional_critical_damage  
&nbsp;
命中值补正 additional_hit_value  
&nbsp;
闪避值补正 additional_dodge_value  
&nbsp;
速度补正 additional_speed  
&nbsp;
暴击抗性补正 additional_critical_defence  
&nbsp;
效果抗性补正 additional_cc_defence

#### 行为：
&nbsp;
被穿戴 equip  
&nbsp;
被卸下 unequip  

## 房间类 room
#### 属性：
&nbsp;
上面的房间 up_room  
&nbsp;
下面的房间 down_room  
&nbsp;
左边的房间 left_room  
&nbsp;
右边的房间right_room  
&nbsp;
隐藏的房间 hidden_room  
&nbsp;
内部的物品 contained_item  
&nbsp;
内部的人物 contained_character  
&nbsp;

#### 行为：
&nbsp;
人物更新 update_character  
&nbsp;
物品更新 update_item  
&nbsp;
野怪刷新 renew_enemy
&nbsp;

## 指令类：
#### 属性：
&nbsp;
世界时间 global_time  
&nbsp;

#### 行为：
&nbsp;
读取指令 load_command  
&nbsp;
执行指令 execute_command  
&nbsp;
