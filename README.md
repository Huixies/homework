# 8.5 MVVM

MVVM（Model-View-ViewModel）框架是**MVP 模式**与**WPF**结合。 WPF 的数据绑定与 Presentation Model 相结合是非常好的做法,使得可将视图和逻辑分离出来 。

> MVP（Model-View-Presenter）
>
> M 封装了核心数据、逻辑和功能的计算关系的模型
>
> V 视图（窗体）
>
> P 封装了窗体中的所有操作、响应用户的输入输出、事件等

##### MVVM 优点

1. **低耦合** 视图可以独立于模型变化和修改

   > 一个 ViewModel 可以绑定到不同的"View"上，当 View 变化的时候 Model 可以不变，当 Model 变化的时候 View 也可以不变。

2. **可重用性** 可以把一些视图逻辑放在一个 ViewModel 里面，让很多 view 重用这段视图逻辑。

3. **独立开发** 开发人员专注于业务逻辑和数据的开发，设计人员专注于页面设计

   > 使用 Expression Blend 可以很容易设计界面并生成 xaml 代码。

4. **可测试** 界面素来是比较难于测试的，测试可以针对 ViewModel 来写。
