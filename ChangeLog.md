# 更新日志

- 时间选择器支持设置时分秒间隔，参阅 [issues#270](https://github.com/gzu-liyujiang/AndroidPicker/issues/270)；

## 4.1.3 - 2021.11.07

- 滚轮选择器条目文字过长截取优化；
- 日期时间选择器支持滚动联动不重置开关；
- 滚轮选择器条目滚动展示效果优化；

## 4.1.2 - 2021.11.01

- 修复 Android 7.x 上滚轮选择器选中项重叠问题；

## 4.1.1 - 2021.10.28

- 滚轮选择器选中项文字支持加大加粗；
- 部分细节优化，部分效果图更新；

## 4.1.0 - 2021.10.28

- 支持滚轮选择器选中项设置圆角纯色背景；
- 所以选择器文本国际化，内置支持中文及英文；
- 手机号码前缀选择器数据完善，支持全球的国家及地区；
- 车牌、星座及性别等选择器调整，民族、星座及性别等默认值设置优化；
- 日历选择器支持自定义节日文本；

## 4.0.1 - 2021.09.26

- 优化选择器标题设置，避免设置不生效问题；

## 4.0.0 - 2021.09.18

- 支持设置弹窗样式，内置四种弹窗模式，支持全局弹窗配色，效果请运行Demo；
- 日历日期选择器重构，日历默认选中项展示到当前可见位置，Demo日历日期选择器自定义配色示例；
- 滚轮选择器滚动变化监听器优化，Demo滚轮选择器实时滚动变化监听示例；
- 二三级联动选择器默认值设置优化； 
- 文件目录选择器优化及界面调整；
- 颜色选择器优化及界面调整；
- 其他已知的小缺陷修复及代码优化；

## 3.1.2 - 2021.09.13

- 选择器弹窗效果优化，支持启用顶部圆角背景；
- 修正联动选择器当第二三级数据为空时滑动一下会导致滑动失效问题，参阅 [issues#263](https://github.com/gzu-liyujiang/AndroidPicker/issues/263)；
- 日历日期选择器默认选中项设置优化，参阅 [CSDN#comments_18122565](https://blog.csdn.net/waplyj/article/details/117857191#comments_18122565)；

## 3.1.1 - 2021.08.31

- 图片选择器增加自定义文件类型选择及取消回调；
- 默认值选中设置优化；
- 修复日历日期选择器月份可能缺失问题，参阅 [issues#262](https://github.com/gzu-liyujiang/AndroidPicker/issues/262);
- 日期时间选择器联动滚动优化；

## 3.1.0 - 2021.07.30

- 新增图片选择器（相机+相册+裁剪），可用于头像选择裁剪；
- 修复个别已知的可能的异常；
- 改进12小时制的上下午选择，参阅 [252#issuecomment-888115423](https://github.com/gzu-liyujiang/AndroidPicker/issues/252#issuecomment-888115423)；
- 民族选择器支持按民族代码、民族中文名及罗马拼写设置默认值；

## 3.0.8 - 2021.07.21

- 联动/日期/时间选择器有滚轮在滑动中时不允许另外的滚轮滑动，参阅 [issues#251](https://github.com/gzu-liyujiang/AndroidPicker/issues/251);
- 修复日期/时间选择器模式设置可能不生效问题;
- 修复时间选择器12小时制时间显示不正确问题，参阅 [issues#252](https://github.com/gzu-liyujiang/AndroidPicker/issues/252);

## 3.0.7 - 2021.07.15

- 时间选择器设置显示秒无效问题，参阅 [issues#249](https://github.com/gzu-liyujiang/AndroidPicker/issues/249)；

## 3.0.6 - 2021.07.08

- 滚轮控件弯曲模式增加指示线间隔控制；

## 3.0.5 - 2021.07.02

- 日期/时间选择器确保设置的日期时间范围有效，参阅 [issues#244](https://github.com/gzu-liyujiang/AndroidPicker/issues/244)；

## 3.0.4 - 2021.06.30

- 联动选择器增加初始数据加载进度控制，地址选择器数据加载过程避免卡顿感；
- 以日期选择器为例示范选择器界面个性化用法，参阅 [issues#243](https://github.com/gzu-liyujiang/AndroidPicker/issues/243)；
- 地址选择器新增国家统计局省市区数据示例；

## 3.0.3 - 2021.06.25

- 滚轮控件默认值设置优化；
- 小数选择器格式化示例；

## 3.0.2 - 2021.06.12

- 发布遗漏了的地址选择器模块；

## 3.0.1 - 2021.06.12

- 增加民族选择器；
- 抽取地址选择器模块，默认附带来源于国家统计局的省市区数据；
- 地址选择器演示添加新的省市区JSON数据；

## 3.0.0 - 2021.06.11

- 时隔两年，大刀阔斧的重构回归，全新的滚轮选择器、文件选择器、颜色选择器、日历选择器；

## 2.0.0 - 2020.10.20

- 从 Support v4/v7 迁移到 AndroidX ；

## 1.5.6.20181018 - 2018.10.18

- 兼容 Android 9.0（COMPILE_SDK_VERSION=28）；

## ~~1.5.6 - 2018.06.01~~

- 避免因 Android9.0 导致的编译问题；
- WheelView 优化……

## ~~1.5.5 - 2017.09.01~~

- 代码优化，新增一些设置方法；

## ~~1.5.4 - 2017.08.19~~

- 修复时间选择器 bug；
- 联动选择器支持设置宽度填充;

## ~~1.5.3 - 2017.07.01~~

- 修复默认无法选中第一项的问题；
- 新增日期时间选择器联动时是否重置下一级的索引的控制方法;
- 修复日期选择器 setSelectedItem 传值错误可能导致的奔溃问题;
- 新增多项选择器；

## ~~1.5.2 - 2017.05.14~~

- 有童鞋反应动画太慢，移除选择器默认的动画；
- DoublePicker 支持设置前缀及后缀标签;
- 修复联动选择器不滑动（使用默认项）就确定时的奔溃问题；
- 修复 setXXRangeStart()及 setXXRangeEnd()二者调用顺序颠倒出现的问题；

## ~~1.5.1 - 2017.05.03~~

- 日期时间选择器支持设置各项平分布局;
- 顶部按钮文字颜色默认调整为青蓝风格;
- 修复日期时间选择联动适时取值不对问题；
- 支持设置选中项的背景色及透明度；
- 增加港澳台的县级城市数据；
- 添加双项选择器，选择两项，数据不联动;

## ~~1.5.0 - 2017.05.01~~

- 基于 View 重构 WheelView；
- 联动选择器支持直接传入对象；
- 动画默认为 500 毫秒，应该不会太慢了；

## ~~1.4.6 - 2017.04.10~~

- 弹窗内部部分代码重构；
- 使用透明渐变位移动画，缓解初始化时默认选中项显示跳动问题；
- 日期时间选择联动时重置联动项的索引为 0；

## ~~1.4.5 - 2017.03.19~~

- - 解决选择器部分选项概率性不显示问题，感谢亮亮同学；

## ~~1.4.4 - 2017.03.8~~

- 解决滑动选项闪烁问题；修复已知的数组越界异常问题；

## ~~1.4.3 - 2017.01.16~~

- 解决默认选项选中失效问题；

## ~~1.4.2 - 2017.01.09~~

- 滑轮选择器默认禁用循环滚动；
- 日期时间选择器宽度兼容 480x800；
- demo 的地址选择器重构，方便回调；

## ~~1.4.1 - 2017.01.08~~

- 修复选择器在 Android4.X 版本上奔溃问题；
- 改进文件目录选择器的路径指示效果；

## ~~1.4.0 - 2017.01.07~~

- 重构 WheelView，大批量数据时滑动性能显著提升；
- 改进颜色选择器的颜色选择预览效果；
- 滑轮选择器可设置阴影效果；

## ~~1.3.5 - 2017.01.04~~

- 选择器引用的图片改成字节数组形式;
- 解决默认主题设置为 Material 时顶部按钮内边距过宽问题;
- demo 添加沉浸式状态栏功能

## ~~1.3.4 - 2017.01.01~~

- 重构日期时间选择器，默认选中当前日期时间;
- 支持设置顶部的左右边距;
- 优化多级选择器的数据联动；
- 支持将库打包为纯 jar 包，通过 jar 依赖;

## ~~1.3.3 - 2016.12.21~~

- 修复日期选择器月份范围设置可能无效的 bug;
- 支持设置顶部按钮按下状态的文字颜色;
- 选择器条目默认显示由 3 条改为 5 条，并修改条目文字的内边距；

## ~~1.3.2 - 2016.12.19~~

- 支持设置选中项分割线的宽比例、透明度、粗度；
- 修复小数选择器设置默认选择项可能无效的 bug；
- 添加中国大陆车牌号码选择器；

## ~~1.3.1 - 2016.12.17~~

- 对 1.2.\*版本作兼容处理。

## ~~1.3.0 - 2016.12.15~~

- 支持设置选择器主体背景颜色；
- 所有选择器支持滑动实时监听;
- 所有选择器支持内嵌到其他视图容器;
- 重构单项选择器，数字选择器支持小数；

## ~~1.2.4 - 2016.11.23~~

- 修复默认选中第一项时颜色不高亮问题；
- 修复联动选择器数组越界问题；
- 多级联动选择器支持设置各列比例；
- 时期及时间选择器内部逻辑修改；

## ~~1.2.3 - 2016.10.13~~

- 修复日期选择器中当开始年份和结束年份相同时的 Bug；
- 修复年月日时分选择器的设置默认值时分没有补零的 Bug；
- 支持所有选择器顶部高度及字号的设置；
- 修复日期选择器选中项显示有误问题，感谢@msdx；

## ~~1.2.2 - 2016.09.01~~

- 日期选择器支持年份正序和逆序；
- 时间选择器可以限定时分范围；
- 选择器可指定弹框显示位置，如居中；
- 日期选择器可以限定年月日范围；
- 修复几个已知的 bug；

## ~~1.2.1 - 2016.07.23~~

- 地址选择器增加获取城市编码，感谢@weishd；
- 修改注释，优化部分代码，修复一个已知的 bug；

## ~~1.1.3 - 2016.06.14~~

- 添加日期时间选择器，感谢@dongzhaoqi；

## ~~1.1.2 - 2016.05.06~~

- 添加二三级联动选择器；
- 文件选择器布局调整；

## ~~1.1.1 - 2016.04.23~~

- 地址选择器支持只选择省和市、不能混淆某些类，感谢@Wastrel 及@lutas2000；

## ~~1.1.0 - 2016.01.29~~

- 添加注解约束，如“setOffset()”只能是 1 至 4；
- 所有枚举类改为常量来表示，据说这样可以节约内存；
- 支持自定义选择器的顶部及底部的视图；
- 支持使用第三方动画库来实现窗口动画；

## ~~1.0.3 - 2016.01.19~~

- 日期时间、地址、单项、数字等选择器支持伪循环滚动。

## ~~1.0.2 - 2016.01.15~~

- 年或月变动时，保持之前选择的日不动：如果之前选择的日是之前年月的最大日，则日自动为该年月的最大日。

## ~~1.0.1 - 2016.01.14~~

- 精简文件选择器的数据适配器；
- 添加选择器顶部确定、取消按钮所在容器的背景色设置。

## ~~1.0.0 - 2016.01.13~~

- 发布到 jcenter，支持远程 maven 依赖。