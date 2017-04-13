# Data Binding Formatter Plugin

现已在 JetBrans Plugin 中心提供 [下载](https://plugins.jetbrains.com/plugin/8616?pr=idea)

写一个 Android Data Binding 的实体类是一个非常痛苦的事情,要为所有 getter 函数添加 @Bindable 注解,
对 所有 setter 函数加入 notify ,如果一个实体类有 10 几个成员对象,自动生成 getter 和 setter 之后的操作把手也累断了.

所以我写了一个 IDEA 的扩展,来自动完成这些操作.

