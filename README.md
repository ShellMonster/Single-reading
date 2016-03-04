# Single-reading
#### 这是一个使用单读app的接口完成的一个个人练习项目，功能完成了约80%。
*实现了首页的功能，完全模仿了原声app比较优雅的排版，其中storyboard的约束需要考虑的地方比较多，在原生app的排版上做了一些优化，使中间的文章描述更为居中。
*项目中的下拉刷新使用了mjRefresh框架，传送门：https://github.com/CoderMJLee/MJRefresh 但是在首页的collectionView的pagingEnabled属性为YES，与mjRefresh框架刷新完成后弹回原处的功能产生冲突
