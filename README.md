# StellarisDerby_Branch-Fitswc

## Todo⏱️（很快开工）

更改Namelist的工作方式使其更加易于本地化操作 **不论是中文还是英文**

## Changelog

>2023/1/16

1. 同步更改自rabbit分支
2. 跟进翻译+看了看代码。

>2023/1/11

1. 优化翻译，从文博那搬了一点过来。
2. 哇我真的是爱死文博那句Eclipse First, The stars nowhere.啦

>2023/1/7

1. 应数码的要求：将已有工程与数码的合并，此次合并有破坏性⚠️
   1. 提交包含的内容：数码的0.3(堕落GUI和事件) + 国策/理念：烛尽光殇 + 专属贸易政策 + 全部(包括其他例如内恰/速茶等)的英文本地化
   
2. 发现的问题：
    1. 发现本地化缺失 4 个(未知文案，补全 4 个)
         1. 缺失内容为：uma_fallen_empire.15.title uma_fallen_empire.15.desc uma_fallen_empire.15.a 现已全部补全
         2. 以上补全内容在：localisation\simp_chinese\UMA_events_l_simp_chinese.yml 的599-601行；在localisation\english\UMA_events_l_english.yml 的725-727行，Tom桑合并时要注意下~
         3. 补全的内容为：uma_fallen_empire_communication_office: 补全为：遗落特雷森通信办公室
         4. 上面的本地化文本位置于：localisation\simp_chinese(english)\UMA_fallen_empire_l_simp_chinese(l_english).yml
    1. 堕落GUI闪退(本次提交/合并已修复)
    2. 堕落GUI全部事件似乎无法正常触发/显示(依据本地化文件判断，当然没写完的话,,,,当我没说)
    3. 内恰的居酒屋的科技似乎没有图标(错误报告判断；真伪未验证)
    4. 堕落的陆军原来是个盒子(概率性的；但妹瑟说是老毛病了)

3. 更新的：
   1. Core Mod更新到Branch - agnes_digital中的0.3，其他分支的未进行同步
   2. 英文本地化目前的文本已全部完成
4. 发现的问题：
   1. 本地化缺失 4 个(未知文案，补全 1 个)
     1. 补全的内容为：uma_fallen_empire_communication_office: 补全为：遗落特雷森通信办公室
     2. 上面的本地化文本位置于：localisation\simp_chinese(english)\UMA_fallen_empire_l_simp_chinese(l_english).yml
   2. 堕落GUI闪退(本次提交/合并已修复)
   3. 堕落GUI全部事件似乎无法正常触发/显示(依据本地化文件判断，当然没写完的话,,,,当我没说)
   4. 内恰的居酒屋的科技似乎没有图标(错误报告判断；真伪未验证)
   5. 堕落的陆军原来是个盒子(概率性的；但妹瑟说是老毛病了)
>2023/1/4
1. 新增文本翻译(从Branch-agnes_digital处同步中文本地化)
- [X] UMA_ascension_perks_l_english.yml
- [X] UMA_events_l_english.yml
- [X] UMA_fallen_empire_l_english.yml
- [X] UMA_modifiers_l_english.yml
- [X] UMA_project_events_l_english.yml
1. 新增翻译events：200行，现有从各个分支同步的事件翻译共985行
2. 缩减部分的词句以考虑按钮能塞得下，毕竟英语不像中华文字一样博大精深
   
    eg：（庄生梦蝶，亦或蝶梦庄生）原定翻译为 Zhuang Zhou's Dreaming of Becoming a Butterfly, or a Butterfly's Dreaming of Becoming Zhuang Zhou.
    
    但这个按钮塞不下啊。

    故翻译为：Zhuang Zhou's Dreaming of Becoming a Butterfly(庄生梦蝶)

3. 顶级赶工，这个已经做完了，明天可以接着练习导数了。
   1. 我的Gammarly(辅助写作插件)在翻译Events时已经工作不来了(指一直转圈)
>2023/1/2
1. 快速修复：闪光系列赛：原翻译：Glitter(v./n. 闪光，闪烁，闪耀，闪现(当用作名词时)) Series 现同步(小萌？CY?)官方翻译为：Twinkle(v./n. 闪烁，闪耀；脚轻快地移动) Series 虽然在语法上感觉是错的但是还是用回官方的罢。
   ![](https://s3.bmp.ovh/imgs/2023/01/02/7a3f59498655b03f.jpg)
2. F的健康状态：糟糕的(连续的咳嗽)
3. 大家也要注意身体健康。
>2022/12/30
1. 跟进烛尽光殇翻译
2. 更新翻译，检查了语法错误，简洁了语言。
3. 我要咳飞了，淦 X﹏X
    
>2022/12/27
1. ~~(禁用)夹带私货：增加了麻酱的异常点与事件链（入门级代码/已单独于已有的事件文件分离）~~已删除

2. 跟进翻译文本
  - [X] UMA_ambient_object_l_english.yml 
 - [X] UMA_ancient_relics_l_english.yml
 - [X] UMA_army_l_english.yml
 - [X]  UMA_fallen_empire_l_english.yml
 - [X] UMA_nice_nature_enclave_l_english.yml
 - [X] UMA_opinion_modifier_l_english.yml
 - [X] study_l_english.yml
 - [X] UMA_ancrel_events_l_english .yml
 - [X] UMA_buildings_l_english.yml
 - [X] UMA_edicts_l_english.yml
 - [X] UMA_l_english.ym] UMA_events_l_english.yml (Pain)
 - [X] UMA_modifiers_l_english.yml
 - [X] UMA_planets_and_districts_l_english.yml
 - [X] UMA_pop_jobs_l_english .yml
 - [X]  UMA_project_events_l_english.yml
 - [X] UMA_technologies_l_english.yml
 - [X] UMA_test_gui_l_english.yml
 - [X] UMA_trait_l_english.yml

### 翻译速茶往事文本时我脑子里的：
  ![](https://s3.bmp.ovh/imgs/2022/12/27/75ce460c64b564e0.jpg)
  ![](https://s3.bmp.ovh/imgs/2022/12/27/016021448463c3a4.jpg)

**不行，太肝了**

>2022/12/26
1. 同步各分支本地化文件(Branch-tom/Branch-digital/Branch-rabbit)
   #### P.S.:study_l_simp_chinese.yml注释标记为临时本地化，暂时不作翻译

   (New)
 - [X] UMA_ambient_object_l_english.yml 
 - [X] UMA_ancient_relics_l_english.yml
 - [X] UMA_army_l_english.yml
 - [X]  UMA_fallen_empire_l_english.yml
 - [X] UMA_nice_nature_enclave_l_english.yml
 - [X] UMA_opinion_modifier_l_english.yml
 - [ ] ~~study_l_english.yml~~

   (Update)
 - [X] UMA_ancrel_events_l_english .yml
 - [X] UMA_buildings_l_english.yml
 - [X] UMA_edicts_l_english.yml
 - [X] UMA_l_english.ym] UMA_events_l_english.yml (Pain~)
 - [X] UMA_modifiers_l_english.yml
 - [X] UMA_planets_and_districts_l_english.yml
 - [X] UMA_pop_jobs_l_english .yml
 - [X]  UMA_project_events_l_english.yml
 - [X] UMA_technologies_l_english.yml
 - [X] UMA_test_gui_l_english.yml
 - [X] UMA_trait_l_english.yml

马娘 => Umamusume

狐狸娘 => ???(求助文博)

> 2022/12/24
1. 新增专有贸易政策的翻译
2. 对Name_List的多语言版本进行区分 eg:

    |   原   |       |
    |  ----  | ----  |
    | Umamusume  | （中文Namelist） |
    | Umamusume  | （英文Namelist） |
    
    |  当前提交   |     |
    |  ----  | ----  |
    | Umamusume  | （中文Namelist） |
    | Umamusume(English)  | （英文Namelist） |
    ⚠️**修改涉及的本地化文本包括英语和中文**

> 2022/12/23
1. 修复收集表编号16的bug(待验证)
2. 上传英语本地化翻译文件,并进行修改
3. **私货**帝宝语音助手-Voice by VITS（移除）
4. 新增英文Name_List