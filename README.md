# Single-reading
#### 这是一个使用单读app的接口完成的一个个人练习项目。
* 实现了首页的功能，完全模仿了原声app比较优雅的排版，其中storyboard的约束需要考虑的地方比较多，在原生app的排版上做了一些优化，使中间的文章描述更为居中。
* 项目中的下拉刷新使用了mjRefresh框架，传送门：https://github.com/CoderMJLee/MJRefresh
  但是在首页的collectionView的pagingEnabled属性为YES，与mjRefresh框架刷新完成后弹回原处的功能产生冲突，就使用了scrollView的 delegate来控制其滑动。
* 实现了进场动画效果
* 实现了首页两侧的菜单界面，使用了第三方框架MMdrawer，传送门：https://github.com/mutualmobile/MMDrawerController
* 实现了两侧菜单的出现动画，使用了UIKit的Animation
* 实现了点击文章后进入的UIWebView界面，但是原生APP的webView使用了JavaScript的交互，暂时未能实现。
* 实现了搜索文章功能
* 实现了个人信息界面，由于涉及第三方登录所以只是做出了UI界面。
