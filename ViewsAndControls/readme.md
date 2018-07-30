# 视图和控件
在屏幕上显示您的内容并定义该内容允许的交互。

--------------
## 概述
视图和控件是应用程序用户界面的可视构建块。使用它们在屏幕上绘制和整理应用的内容。
![](https://docs-assets.developer.apple.com/published/4d53baf7cb/75c071dc-3a79-466b-99d1-f8ef216a94aa.png)
视图可以包含其他视图。将一个视图嵌入另一个视图中会在主视图（称为 **superview**）和嵌入视图（称为 **subview**）之间创建一个包含关系。查看层次结构可以更轻松地管理视图。
你还可以使用视图执行以下任何操作：
- 响应触摸和其他事件（直接或与手势识别相联系）。
- 使用Core Graphics或UIKit类绘制自定义内容。
- 支持拖放交互。
- 响应焦点变化。
- 为视图的大小，位置和外观属性设置动画。

[UIView](./UIView.md)是所有视图的根类，并定义了它们的常见行为。

[UIControl](./UIControl.md)定义了特定于按钮，开关和为用户交互设计的其他视图的其他行为。


## 基础视图
- [class UIView](./UIView.md) 管理屏幕上矩形区域内容的对象。

## 容器视图
> 使用容器视图组织和显示大型数据集。

- [Collection View](./ColllectionViews.md) 使用可配置且高度可自定义的布局显示嵌套视图。
- [Table View](./TableView.md) 在可自定义行的单列中显示数据。
- [class UIStackView](./UIStackView.md) 线性的界面，用于在列或行中布置视图集合。
- [class UIScrollView](./UIScrollView.md) 允许滚动和缩放其包含视图的视图。

## 内容视图
- [class UIActivityIndicatorView](./UIActivityIndicatorView.md) 显示任务正在进行的视图。
- [class UIImageView](./UIImageView.md) 在界面中显示单个图像或一系列动画图像的对象。
- [class UIPickView](./UIPickView.md) 使用 spinning-wheel  或 slot-machine 比喻来显示一组或多组值的视图。
- [class UIProgressView](./UIProgressView.md) 描述任务随时间推移的进度的视图。
- ~~[class UIWebview](./UIWebview.md)~~ <Badge text="弃用" vertical="middle" type="warn"/>  在您的应用中嵌入网页内容的视图。
