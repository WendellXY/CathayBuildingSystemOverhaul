# Cathay Building System Overhaul

> 震旦建筑系统大修

## 戒律 Edict

```text
[1] effect_bundles_to_effects_junctions_tables
```

### 烛龙敕令 The Fire Dragons Statute

`wh3_main_edict_cth_the_fire_dragons_statute`

* 新募部队等级 Recruit rank: +2
* 招募花费 Recruitment cost: -5% -> -10%
* 当地招募容量 Local recruitment capacity: +1 -> +2

### 镔龙敕令 The Iron Dragons Statute

`wh3_main_edict_cth_the_iron_dragons_statute`

* 研究速率 Research Rate: +7% -> +15%

### 碧龙敕令 The Jade Dragons Statute

`wh3_main_edict_cth_the_jade_dragons_statute`

* 所有建筑收入产值 Economy GDP: +10%

### 凕龙敕令 The Sea Dragons Statute

`wh3_main_edict_cth_the_sea_dragons_statute`

* 贸易收入 Income from trade: +5% -> +10%
* 商品销售价值 caravan cargo value: +7%

### 飙龙敕令 The Storm Dragons Statute

`wh3_main_edict_cth_the_storm_dragons_statute`

* 战略地图移动距离 (当地敌军) Campaign movement range for enemy armies starting their turn in this region: -20% -> -30%
* 当地部队近战防御 Melee defence: +5 -> +7

### 长垣增援 The Great Bastion Growth Supplies

`wh3_main_edict_cth_the_great_bastion_growth_supplies`

TODO

### 长垣巡逻 The Great Bastion Patrols

`wh3_main_edict_cth_the_great_bastion_patrols`

TODO

### 长垣恢复 The Great Bastion Replenish

`wh3_main_edict_cth_the_great_bastion_replenish`

TODO

### 长垣强化 The Great Bastion Training

`wh3_main_edict_cth_the_great_bastion_training`

TODO

## 建筑 Building

```text
[1]: building_levels_tables
[2]: building_level_armed_citizenry_junctions_tables
[3]: building_effects_junction_tables
[4]: building_units_allowed_tables
[5]: armed_citizenry_unit_groups_tables
[6]: armed_citizenry_units_to_unit_groups_junctions_tables
```

### 厩舍序列 Stables

龙马场 Longma Paddocks wh3_main_cth_cavalry_3

* 建造时间 Create Time:  5 -> 4 [1]
* 建造花费 Create Cost: 8000 -> 4000 [1]
* 建造所需主城等级 Primary Slot Building Building Level Requirement: 5 -> 4 [1]

玉马厩 Jade Stables wh3_main_cth_cavalry_2

* 建造时间 Create Time:  3 -> 2 [1]
* 建造花费 Create Cost: 2000 -> 1000 [1]
* 建造所需主城等级 Primary Slot Building Building Level Requirement: 3 -> 2 [1]

### 熔炉序列 Forge

南皋锻坊 Nan-Gau Forge wh3_main_cth_gunners_1

* 建造时间 Create Time:  2 -> 1 [1]
* 建造花费 Create Cost: 1000 -> 500 [1]
* 建造所需主城等级 Primary Slot Building Building Level Requirement: 2 -> 1 [1]

### 市政序列 Civic

募工局 Labour Conscription Bureau wh3_main_cth_growth_yang_1

* 建筑成本 所有建筑 Construction cost of all buildings: -4% -> -10% [3]

竹架仓 Bamboo Scaffold Depot wh3_main_cth_growth_yang_2

* 建筑成本 所有建筑 Construction cost of all buildings: -5% -> -15% [3]
* 建筑时间 阴阳建筑 Building Construction Time: -1 [3]

伐木坊 Lumber Mill wh3_main_cth_growth_yang_2

* 建筑成本 所有建筑 Construction cost of all buildings: -6% -> -20% [3]
* 建筑时间 阴阳建筑 Building Construction Time: -2 [3]

雅茶会 Tea Parlour wh3_main_cth_growth_yin_1

* 所有建筑收入产值 Economy GDP: +2% -> +3% [3]

存思园 Contemplation Gardens wh3_main_cth_growth_yin_2

* 所有建筑收入产值 Economy GDP: +4% -> +6% [3]

政务府 Administration Centre wh3_main_cth_growth_yin_3

* 所有建筑收入产值 Economy GDP: +6% -> +12% [3]

### 工业序列 Industry

市货场 Wares Market wh3_main_cth_income_yang_1

* 财政收入 Income generated: +50 -> +100 [3]

商旅大集 Merchant Caravans wh3_main_cth_income_yang_2

* 财政收入 Income generated: +150 -> +225 [3]

商贸所 Trade Exchange wh3_main_cth_income_yang_3

* 财政收入 Income generated: +300 -> +450 [3]

香料市场 Spice Market wh3_main_cth_income_yin_1

* 财政收入 Income generated: +75 -> +50 [3]
* 贸易收入 Income from trade: +2% -> +4% [3]
* 商品销售价值 caravan cargo value: +2% [3]

宝玉馆 Gem Factors wh3_main_cth_income_yin_2

* 财政收入 Income generated: +150 -> +100 [3]
* 贸易收入 Income from trade: +4% -> +8% [3]
* 商品销售价值 caravan cargo value: +4% [3]

百货市 Goods Emporium wh3_main_cth_income_yin_3

* 财政收入 Income generated: +225 -> +200 [3]
* 贸易收入 Income from trade: +6% -> +12% [3]
* 商品销售价值 caravan cargo value: +8% [3]

### 征募序列 Conscription

当这个序列的建筑升级到3级后，将会降低近战部队（阳系建筑）或远程步兵（阴系建筑）1% 的维持费

When the Yin-Yang buildings of this chain are upgraded to level 3, it will reduce 1% upkeep of melee units (with the Yang building) or missile infantry (with the Yin building)

征募院 Conscription Office wh3_main_cth_order_yang_1

* 所在军队 补员速率 Force Own Regionwide: +2% [3]

崇阳观 Temple of Yang wh3_main_cth_order_yang_2

* 所在军队 补员速率 Force Own Regionwide: +4% [3]

神阳殿 Yang Sanctuary wh3_main_cth_order_yang_3

* 所在军队 补员速率 Force Own Regionwide: +6% [3]

### 哨站序列 Allied Outpost

> 让盟友不那么容易被消灭（指我的档每回合给女皇一万多块钱，她还是没了）
>
> Make allies less likely to be destroyed

Level 1

* 驻军 [2] [5] [6]
  * 玉勇 Jade Warriors x 2 wh3_main_cth_inf_jade_warriors_0
  * 玉勇弩手 Jade Warrior Crossbowmen x1 wh3_main_cth_inf_jade_warrior_crossbowmen_1

Level 2

* 驻军 [2] [5] [6]
  * 天廷龙卫 Dragon Guard x 1 wh3_main_cth_inf_dragon_guard_0
  * 天廷龙弩手 Dragon Guard Crossbowmen x 1 wh3_main_cth_inf_dragon_guard_crossbowmen_0

Level 3

* 驻军 [2] [5] [6]
  * 天廷龙卫 Dragon Guard x 1 wh3_main_cth_inf_dragon_guard_0
  * 天廷龙弩手 Dragon Guard Crossbowmen x 1 wh3_main_cth_inf_dragon_guard_crossbowmen_0
  * 天廷龙铳手 Dragon Guard Gunners x1 wh3_mod_cth_inf_dragon_guard_gunner_0

### 特殊建筑 Special Buildings

> 加强加成效果来弥补巍京两块黄地的惩罚

天堂花园 Paradise Gardens wh3_main_special_paradise_gardens

* 驻军 [2] [5] [6]
  * 天廷龙卫 Dragon Guard x 2 wh3_main_cth_inf_dragon_guard_0
  * 天廷龙弩手 Dragon Guard Crossbowmen x 2 wh3_main_cth_inf_dragon_guard_crossbowmen_0
  * 天廷龙铳手 Dragon Guard Gunners x1 wh3_mod_cth_inf_dragon_guard_gunner_0
* 所有建筑收入产值 Income from all buildings: +25% -> +50% [3]
* 发展 Growth: +5 -> +40 [3]

> 通过让双月神庙可以直接招募龙卫部队来降低巍京的建筑格子压力

双月神庙 The Temple of The Two Moons wh3_main_special_the_temple_of_the_two_moons

* 驻军 [2] [5] [6]
  * 天廷龙卫 Dragon Guard x 2 wh3_main_cth_inf_dragon_guard_0
  * 天廷龙弩手 Dragon Guard Crossbowmen x 2 wh3_main_cth_inf_dragon_guard_crossbowmen_0
  * 天廷龙铳手 Dragon Guard Gunners x1 wh3_mod_cth_inf_dragon_guard_gunner_0
* 维持费 天廷龙卫与天廷龙弩手部队 Upkeep of Celestial Dragon Guard and Celestial Dragon Crossbowmen units: -5% -> -15% [3]
* 允许招募 天廷龙卫与天廷龙弩手部队 Allowed to recruit Dragon Guard and Dragon Crossbowmen [4]

> 原效果过于鸡肋，配不上这名字，所以我进行了加强

天廷 Celestial Palace wh3_main_special_celestial_palace

* 驻军 [2] [5] [6]
  * 天廷龙卫 Dragon Guard x 1 wh3_main_cth_inf_dragon_guard_0
  * 俑士禁卫 Terracotta Sentinel x 2 wh3_main_cth_mon_terracotta_sentinel_0
  * 司天丞 Astromancer x 1 wh3_main_cth_cha_astromancer_2
* 全派系 所有建筑收入产值 Factionwide Income from all buildings: +5% -> +10% [3]
* 全派系 掌控力 Factionwide Order: +2 -> +4 [3]
* 全派系 新募领主等级 Factionwide Lord recruit rank: +2 -> +4 [3]

> 让第九高墙更像一座城墙，并且添加了类似于长垣的降低所在军队维持费的效果（虽然基本没用）

第九高墙 The Ninth Wall wh3_main_special_the_ninth_wall

* 新增两个对应的低级建筑 Added Two Corresponding Lower-level Building
* 驻军 [2] [5] [6]
  * 天廷龙卫 Dragon Guard x 2 wh3_main_cth_inf_dragon_guard_0
  * 天廷龙弩手 Dragon Guard Crossbowmen x 2 wh3_main_cth_inf_dragon_guard_crossbowmen_0
  * 巨炮 Grand Cannon x 2 wh3_main_cth_art_grand_cannon_0
  * 巨龙马骑兵 Great Longma Riders x 1 wh3_main_cth_cav_jade_longma_riders_0
* 所在军队 维持费 Regionwide Force Upkeep: -65%/-55%/-45% [3]
* 掌控力 Order: +12/+6/+3 [3]
* 防御补给 Initial Supply Points: 1000/500/250 [3]
* 守城期间 部队损耗 Siege Defend Attrition: -50%/-40%/-30% [3]
* 所在军队 守城期间 近战防御 Melee Regionwide Defence Siege Defence: +15/+10/+5 [3]
* 所有军队 防御时 近战防御 All Force Melee Defence While Defending: +8/+6/+4 [3]
* 所有军队 守城战时 弹药容量 All Force Siege Defend Attrition: +50%/+40%/+30% [3]

> 增强大使馆对贸易收入的 Buff

大使馆 The Great Embassy wh3_main_special_the_great_embassy

* 财政收入 Income generated: +300 -> +500 [3]
* 贸易收入 Income from trade: +10% -> +30% [3]
* 商品销售价值 caravan cargo value: +24% [3]

> 增加研究速率，并且允许直接招募五行战争罗盘（缓解格子压力）

钦天监 Grand Observatory of Xing Po wh3_main_special_grand_observatory_of_xing_po

* 研究速率 Research Speed +15% [3]
* 允许招募 五行战争罗盘 Allowed to recruit War Compass [4]

> 增强震旦部队的补员能力，同时碧血道观所在行省为长垣腹地，可以一定程度上缓解长垣压力

碧血道观 Temple of the Jade Blood Sorcerers wh3_main_special_temple_of_the_jade_blood_sorcerers

* (行省) 部队补员速率 (ProvinceWide) Replenishment Rate: +5% -> +10% [3]
* 掌控力 Order: +2 -> +4 [3]
* 邻近行省 掌控力 Order Osmosis: +1 -> +2 [3]
