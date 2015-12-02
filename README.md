# AndroidProblem
开发中遇到的奇葩问题

2015-12-02

1、给一个TextView设置padding大小,要求paddingLeft是16dip,paddingRight也是16dip,paddingTop也是16dip,paddingBottom是10dip.

我的解决办法是
android:padding="16dip"
android:paddingBottom="10dip"

当我去看效果时结果不好用，上下的padding都是一样的,于是我采用最笨的办法

android:paddingLeft="16dip"
android:paddingRight="16dip"
android:paddingTop="16dip"
android:paddingBottom="10dip"
这样却能正常显示了。

谁有更简洁的办法？
