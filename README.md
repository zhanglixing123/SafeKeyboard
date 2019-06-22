# **SafeKeyboard**
Android自定义安全软键盘，完全自定义，方便、安全、可靠

预览<br>
![image](https://img-blog.csdn.net/20180516102718149)

## **历史更新**


### 二、 2019/06/22
* 1 . 支持多个 EditText 共用一个 SafeKeyboard, 各键盘无缝切换
* 2 . 支持根据不同 EditText 的 InputType 默认使用不同的键盘(目前仅支持数字键盘和身份证键盘)
* 3 . 支持锁定英文大写
* 4 . 增加两种数字键盘、增加一个身份证键盘, 对两种键盘的数字支持随机显示
* 5 . SafeKeyboard 提供接口指定显示身份证键盘的 EditText
* 6 . 支持记住每个 EditText 对应的上次打开的键盘类型, 再次显示 SafeKeyboard 时显示该中类型键盘, 此功能可在 SafeKeyboardView 的属性中 打开/关闭
* 7 . 项目本身支持 lambda 表达式

### 一、 2018/07/29
* 1 . `AndroidMenifest.xml` 文件中添加 `"android:windowSoftInputMode="stateAlwaysHidden">"`, 兼容低版本系统, 重新进入软件界面系统软键盘自动弹出的问题。

* 2 . 解决特殊键盘图标在不同屏幕上显示变形问题, 不需要手动设置图片显示时与按键边界的边距。
* 3 . `SafeKeyboard` 提供接口设置特殊按键的自定义图片
