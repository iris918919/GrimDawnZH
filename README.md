恐怖黎明中文本地化
===

beta19版汉化正在进行中

所有文本均已升级至beta19，先同步或反向更新后再进行修改！

翻译时注意使用`中文标点符号`，中文不需要留大量空格

查看beta19文本变动：https://github.com/esclaveDuReve/GrimDawn/compare/beta19

游戏版本更新时不要改动诸如ui skills uimain items creatures等后六个文件，等待英文更新完毕后再进行翻译。

否则会产生大量冲突！

发现与最新版英文原文不一致请及时通知

现存问题：护甲等级栏超出范围，中文字体打开游戏后切出在切入游戏多次会导致游戏崩溃（已向开发者反映）

更新：中文存在换行问题，英文很多时候可以自动换行而中文不行，必须人为添加{^n}换行符，一个换行符代表本行结束另起一行，连续两个代表空一行

经过测试现规定翻译换行标准如下：（文本请全部使用中文标点，方便计算字符个数，一个中文字符相当于两个英文字母或标点的占位）

装备描述（用于史诗装备）18个中文字符加上开头的 “ 半个引号 

tagWeaponSwordC008Desc=“当仅仅贿赂政敌已不足以解决问题时，马{^n}尔茅斯的大法官会采取另一种解决之道。”

任务文本 18个中文字符

你已经找到了西北方的田地，你应该探索{^n}霍姆斯特德看看那儿是不是还适合种庄稼{^n}，有没有人还活着。

技能 16个

tagClass01SkillDescription01A=战斗时，自然地跟随周期性的节奏感{^n}，施展抑扬顿挫的打击，每次第三击{^n}造成大量伤害。虽然可以被预判，但{^n}却强效有力，难以实施反击。

教程 9个

tagTutorialTip09TextA=商人出售与收购在凯{^n}恩世界的险境中生存{^n}所必需的武器装备。

请务必遵守标准，否则翻译完会出现这种情况：

“当仅仅贿赂政敌已不足以解决问题时...
