sajiazheng(
https://github.com/tusenpo/FlappyFrog/issues/18
Download到本地之后 #18
 Open	MonFig opened this issue 25 days ago · 4 comments
Labels

None yet
Milestone

No milestone
Assignees

No one assigned
Notifications

  Subscribe
You’re not receiving notifications from this thread.
2 participants

@MonFig @tusenpo
@MonFig
 
MonFig commented 25 days ago
为什么会卡在历史的进程4%那里，，，，迷
@MonFig
 
MonFig commented 25 days ago
而且感觉长者撞管子的碰撞箱有点问题，碰撞判定有点错误，有时候明明可以擦边过的却没过过去。。。
@MonFig
 
MonFig commented 25 days ago
Mac的chrome和safari都没用。。。
@tusenpo
 Owner
tusenpo commented 24 days ago
第一个问题是因为浏览器默认不允许通过XHR访问本地文件
针对chrome浏览器，可以设置allow-file-access-from-files参数
在Mac OS X下的操作方法如下
先关闭chrome，然后打开终端(terminal)，输入 open /Applications/Google\ Chrome.app --args --allow-file-access-from-files ，回车

另一个办法是在本地搭建一个http server
比如 python -m SimpleHTTPServer 或者 npm install http-server
参考 https://github.com/lmccart/itp-creative-js/wiki/SimpleHTTPServer
@MonFig
 
MonFig commented 24 days ago
感谢回复！这个问题目前正考虑nginx来解决，不过很不幸我的电脑搭nginx好像也出了点问题。。。

闷声大发财~ #14
 Open	LewisTseng opened this issue 27 days ago · 2 comments
Labels

None yet
Milestone

No milestone
Assignees

No one assigned
Notifications

  Subscribe
You’re not receiving notifications from this thread.
3 participants

@LewisTseng @tusenpo @xielingzhi
@LewisTseng
 
LewisTseng commented 27 days ago • edited
楼主的这个Game，Excited！
我玩的时候一直在笑！
下面是我利用网页做成的Android App~
http://dwz.cn/3gTzN0
 :+1: 1  
@tusenpo
 Owner
tusenpo commented 27 days ago
能否放到GitHub上来？
@xielingzhi
 
xielingzhi commented 17 days ago
你这个apk非常吼！

楼主能否做个安卓APK或者swf😏 #13
 Open	NaClO3 opened this issue on Apr 29 · 3 comments
Labels

None yet
Milestone

No milestone
Assignees

No one assigned
Notifications

  Subscribe
You’re not receiving notifications from this thread.
3 participants

@NaClO3 @tusenpo @ragnaroks
@NaClO3
 
NaClO3 commented on Apr 29
我特地apply个帐号向楼主提建议
@tusenpo
 Owner
tusenpo commented 29 days ago • edited
做成APK不难，用WebView应该可以实现
做成SWF是不行的，因为这是用html5和javascript做的

是想下载下来玩吗，点击项目主页的"Download ZIP"按钮或者https://github.com/tusenpo/FlappyFrog/archive/gh-pages.zip ，下载后解压，用浏览器打开index.html
如果你用的是chrome浏览器，需要设置chrome的启动参数 --allow-file-access-from-files
@ragnaroks
 
ragnaroks commented 26 days ago
phaser性能如何?
@tusenpo
 Owner
tusenpo commented 26 days ago
@ragnaroks
phaser用于这个FlappyFrog，似乎很流畅
但是具体性能如何，我无法回答这个问题

那个“哟哟”声听着好难受啊能不能删掉 #11
 Open	S0ngyuLi opened this issue on Apr 21 · 7 comments
Labels

None yet
Milestone

No milestone
Assignees

No one assigned
Notifications

  Subscribe
You’re not receiving notifications from this thread.
7 participants

@S0ngyuLi @tusenpo @BersL @thinkerchan @liangshiyiniao @yeguanghao @maskerTUI
@S0ngyuLi
 
S0ngyuLi commented on Apr 21
No description provided.
@tusenpo
 Owner
tusenpo commented on Apr 22
先听听其他人怎么说吧
删掉也要按照基本法，要要……要好几个人一致通过
@BersL
 
BersL commented on Apr 23
:joy:那个哟哟好魔性啊！这是哪句话求告知 迫切想提升膜法姿势
@tusenpo
 Owner
tusenpo commented on Apr 23
@BersL
怒斥篇 「要...要要...要按照香港的...当然我们的決定权也是很重要的」
@thinkerchan
 
thinkerchan commented 29 days ago
不要删啊 这声音非常吼啊
@liangshiyiniao
 
liangshiyiniao commented 26 days ago
不要删啊多带感啊
@yeguanghao
 
yeguanghao commented 26 days ago
我希望删掉，真的难受
@maskerTUI
 
maskerTUI commented 22 days ago
别删，最多调小声点，我觉的这声音还是挺动听的。




)

# FlappyFrog
The violent **mo**dification of [Don't Touch My Birdie](https://github.com/marksteve/dtmb) by Mark Steve Samson
licensed under [Creative Com**mo**ns Attribution-NonCommercial 4.0 International License](https://creativecommons.org/licenses/by-nc/4.0/).

play: https://tusenpo.github.io/FlappyFrog/

the weird frog image is **mo**dified from [another frog image](https://amphibian.com/)
