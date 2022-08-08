# GriefPrevention简介
GriefPrevention是一款强大的插件。可以防止他人使用领地物品东西，防止领地内击杀动物，防止各种破坏等。主要性能还很好，适合ZG的渣机属性（

# GriefPrevention指令
|命令|说明|alias|
|:----|:----|:----|
|/AbandonClaim|删除您所在的领地|无|
|/AbandonAllClaims|删除您名下的所有领地|无|
|/ClaimExplosions|关闭领地防爆|无|
|/AccessTrust|给予另一个玩家您领地物品互动权限（拉动拉杆，按下按钮等）|/at|
|/ContainerTrust|给予玩家您领地的中级领地权限（使用箱子，附魔台，击杀动物等）|/ct|
|/Trust|给予一个玩家您领地的最高权限（无任何限制）|/t|
|/UnTrust|撤销一个玩家您领地的权限|/ut|
|/Untrust  All|撤销所有玩家您领地的权限|无|
|/TrustList|列出您给予了哪些玩家权限|无|
|/SubdivideClaims|切换铲子的子领地模式，用于划分子领地|/sc|
|/BasicClaims|将圈地管理工具（ZenGarden服务器指定金斧）切换普通模式|/bc|
|/PermissionTrust|授予一个玩家给予他人权限的权限|/pt|
|/BuyClaimBlocks|向服务器购买领地方块|/BuyClaim|
|/SellClaimBlocks|出售自己领地方块给服务器|/SellClaim|
|/GivePet|转让宠物|无|
|/ClaimsList|列出你的领地和所在方位|无|
|/IgnorePlayer|忽略目标玩家的聊天信息（拉黑）|/Ignore|
|/UnIgnorePlayer|取消忽略目标玩家的聊天信息（取消拉黑）|/UnIgnore|
|/IgnoredPlayerList|列出您拉黑的玩家|/IgnoreList|
|/Siege|向另一个玩家宣战|无|
|/Trapped|卡住脱离（回到领地出生点）|无|
|/UnlockDrops|您死后掉落在领地内的物品可供其他玩家拾取|无|
|/Claimsetspawn|把您所在的位置设置成领地出生点（需要站在领地中）|/cl w|
|/Claimspawn|回到领地传送点|/cl w|

# GriefPrevention基础操作
# 设置领地

您看到了一块风水宝地，想要占为己有：

![](assets/img/0.png)

（村民:wdnmd

直接在您想要的地方放上箱子即可

![](assets/img/1.png)

领地大小默认9x9，会在边缘显示两个金块和一个萤石

当然，您也可以通过金斧来创建一个矩形领地

选中一个方块做为领地边缘

![](assets/img/2.png)

再右键一个方块作为领地的角落

![](assets/img/3.png)

完成！

# 扩展领地

太小了，我想扩大领地，怎么办？

首先，用金斧右键萤石

![](assets/img/4.png)

然后，再用金斧右键想要扩到的土地

![](assets/img/5.png)

完成！

如果提示没有更多可用的方块...

每人初始有2^7个可用方块，每活跃一个小时可以增加100方块，当然，你还可以通过/buyclaimblocks购买。

# 设置权限

小伙伴很喜爱你这块风水宝地，前来看看

![](assets/img/6.png)

小伙伴默认是没有权限破坏方块的

![](assets/img/7.png)

但是可以与门交互

嘎吱嘎吱地，太烦了，怎么办？

![](assets/img/8.png)

安个按钮，就好啦！

小伙伴默认无法与任何开关交互

小伙伴在撒娇了，没办法，给他开门的权限吧

/Accesstrust test

![](assets/img/9.png)

进来啦！

# 删除领地

你在闲逛的时候发现有一块风水宝地被人占领，你心生嫉妒，站在你的领地里并输入/AbandonClaim

![](assets/img/10.png)

圈这块领地的所用方块将会原路返还。

/AbandonAllClaims可以删除所有领地

输入后需要输入/AbandonAllClaims confirm进行确认

# GriefPrevention进阶操作
# 攻打领地

你用棍子右键这个人的领地来查询领地大小和主人信息

![](assets/img/11.png)

好家伙，是手无寸铁的test

你就能轻松攻下他的领地了

输入/siege test

领地争夺战就开始啦！

中途如果退出服务器，就算做失败

![](assets/img/12.png)

![](assets/img/13.png)

两斧头轻松送走！

攻打下来以后，可以临时解锁对该领地的使用权（按动按钮，拉动拉杆等

当玩家手无寸铁，无法进行宣战

![](assets/img/14.png)

当玩家不在他的领地也是如此

![](assets/img/15.png)

# 卡住脱离

小伙伴因为上次被打败，怀恨在心，建造了一个陷阱，并圈好地

![](assets/img/16.png)

你没有建造或者破坏的权限，难道出不去了吗？

嘻嘻，万能的作者肯定想到这一点啦

输入/trapped，十秒钟后，就会被传送出这块领地

![](assets/img/17.png)

出来啦

![](assets/img/18.png)

批（杀）评（戮）教（开）育（始）

