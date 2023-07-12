# Android定制化ART与逆向

> 

## ArtMethod结构

从Android 5.0（Lollipop）开始，ART取代了之前的Dalvik虚拟机作为Android的主要运行时环境。当分析到JNI函数时，一般都会通过`RegisterNatives`函数来确认JNI函数的地址，从而进行下一步的分析；更进一步，也存在非正常流程的JNI函数的绑定，那么我们怎么来追踪JNI函数的执行流程呢，此时就要提到`ArtMethod`的结构了

```c

```

## 参考文档

[ArtHook](https://github.com/mar-v-in/ArtHook)
[我为Dexposed续一秒——论ART上运行时 Method AOP实现 ](https://weishu.me/2017/11/23/dexposed-on-art/)
[ART 在 Android 安全攻防中的应用](https://evilpan.com/2021/12/26/art-internal/)
[android逆向奇技淫巧十三：定制art内核（一）：跟踪jni函数注册和调用，绕过反调试](https://www.cnblogs.com/theseventhson/p/14952092.html)
[android逆向奇技淫巧十四：定制art内核（二）：VMP逆向----仿method profiling跟踪jni函数执行](https://www.cnblogs.com/theseventhson/p/14961107.html)