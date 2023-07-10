# Android定制化ART与逆向

## ArtMethod结构

从Android 5.0（Lollipop）开始，ART取代了之前的Dalvik虚拟机作为Android的主要运行时环境。当分析到JNI函数时，一般都会通过`RegisterNatives`函数来确认JNI函数的地址，从而进行下一步的分析；更进一步，也存在非正常流程的JNI函数的绑定，那么我们怎么来追踪JNI函数的执行流程呢，此时就要提到`ArtMethod`的结构了

```c

```

## 参考文档

[](https://www.cnblogs.com/theseventhson/p/14952092.html)