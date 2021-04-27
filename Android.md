1.EventBus：EventBus是Android开发中使用的发布/订阅事件总线框架，基于观察者模式将接收者和发送者分开，简化了组件间的通信，使用简单，效率高体积小。
![[Event官方架构图.png]]

2.Android webView调试工具使用方式
1.用chrome浏览器打开chrome://inspect/#devices
2.开启翻墙
3.设置webView 为debug 模式
if (Build.VERSION.SDK_INT>= Build.VERSION_CODES.KITKAT) {  
    try {  
        WebView.setWebContentsDebuggingEnabled(mWebViewDebug);  
 } catch (Throwable e) {  
        e.printStackTrace();  
 }  
}

3. Android 签名包下debug
在app目录下的android MandroidManifest的application节点下 添加android:debuggable="true"
