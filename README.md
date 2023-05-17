# Self-use-lottery-simulator--easy-to-customize
可简单自定义的抽卡模拟器  
设置了五个稀有度等级：普通、稀有、史诗、传说、神话  
除了最低和最高的稀有度，中间三个稀有度等级都设置了保底机制  
（很简单的保底机制，而且有概率出现十连普通，即没有触发任何保底机制，本人纯小白，如果有大佬看到了，希望指点一下，这个问题我应该会放进issues里，如果我能搞懂怎么使用github的话。。）
每个稀有度等级下都设置了三个奖池（除了最低的“普通”稀有度）：例如技能、光环、物品。  
打开.exe 之前会判断目前.exe文件所在目录下是否有 config.ini 配置文件，如果没有则自动生成默认配置文件。  
打开config.ini 即可简单自定义抽卡机：  
1. 金币和抽卡券数量  
2. 保底数  
3. 各稀有度出现概率  
4. 奖池内容  

这个项目并不是我完全原创的，来源：https://github.com/lswlc33/Yuanshen_Lottery_Simulator  
感谢原作者大佬  
我只是根据自己的需要稍微修改了一下文本以及添加了代码  
还有一点忘记说了，这个抽卡模拟器使用了部分《原神》的素材（比如金币是原石，抽卡券是纠缠之缘），都是沿用了原作者的设计，也就是前端设计我只修改了文本（因为是自用，夹带了一点个人xp，还请无视ww）  
暂时没有什么了，希望未来还有机会研究python并给这个抽卡模拟器“换个皮”  
（敲代码真有意思）