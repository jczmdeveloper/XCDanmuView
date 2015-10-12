# XCDanmuView
自己开发的Android弹幕效果View，支持从左向右 和 从右向左 移动 两个方向
效果图如下：


![iamge](https://raw.githubusercontent.com/jczmdeveloper/XCDanmuView/master/screenshots/01.gif)


使用方法如下（默认方向为从右向左移动，无需设置方向）：
mDanmuView = (XCDanmuView)findViewById(R.id.danmu);
mDanmuView.setDirection(XCDanmuView.XCDirection.FORM_LEFT_TO_RIGHT);
mDanmuView.initDanmuItemViews(mStrItems);
