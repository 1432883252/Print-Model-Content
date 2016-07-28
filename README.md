# -Model
能够直接打印出Model里的内容，而不是地址

咱们平时控制台里打印出的Model都是这种格式的：<ModelName:地址>

把这两个类（NSObject+DebugDescription.h，NSObject+DebugDescription.m)直接拖拽到工程中，直接model.debugDescription就可以直接看到model的内容啦
是不是很方便~
